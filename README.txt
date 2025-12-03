🛒 Vending Machine Social – E-commerce Comunitário

Simulação de um sistema de distribuição automatizada de itens essenciais para comunidades carentes.

📌 Sobre o Projeto

Este projeto foi desenvolvido como parte da atividade 2 – Projeto E-commerce Social, cujo objetivo é criar uma aplicação que simula uma Vending Machine Comunitária, permitindo que usuários se identifiquem e realizem retiradas de produtos essenciais, com cálculo de tempo de atendimento e registro das operações para controle de ONGs ou órgãos públicos parceiros.

🎯 Objetivo

Criar uma plataforma simples e funcional que simule:

Distribuição automatizada de itens essenciais.

Controle de identificação dos usuários.

Registro e histórico das retiradas.

Relatórios de utilização para entidades parceiras.

🧩 Funcionalidades Implementadas
🏷️ Catálogo de Produtos

Página inicial listando todos os itens disponíveis.

Cada produto contém:

Nome

Descrição

Preço simbólico

Tempo de reposição (min/item)

Botão “Adicionar ao Carrinho”

🛒 Carrinho de Retiradas

Exibe os itens selecionados pelo usuário.

Calcula quantidade total e custo simulado.

Botões para limpar carrinho ou registrar retirada.

👤 Identificação do Usuário

Métodos possíveis:

Biometria simulada (mock)

Número de documento + senha

ID temporário (para testes)

Após identificação, o usuário é vinculado ao carrinho e ao registro de retirada.

⏱️ Cálculo de Lead Time (Tempo de Atendimento)

A aplicação utiliza a fórmula definida no desafio:

Lead Time = Tempo fixo da máquina + (Quantidade solicitada × Tempo de reposição do item)


Tempo fixo simulado: 5 min

Cada item possui seu próprio tempo de reposição.

🗂️ Banco de Dados / Registros

O sistema armazena:

Usuários cadastrados

Produtos

Histórico de retiradas (data, itens, quantidades, tempo estimado)

Para fins educacionais, os dados podem ser salvos em:

LocalStorage (modo simulado)

JSON local

Banco real (opcional para grupos avançados)

📊 Relatórios para ONG / Órgão Público

A plataforma inclui uma área com relatórios de:

Quantidade de retiradas por usuário

Itens mais consumidos

Custos simbólicos acumulados

Frequência de uso da máquina