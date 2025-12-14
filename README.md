# Mercado Ambos - Sistema de Gestão de Contas

Sistema web simples para gerenciamento financeiro de contas a pagar (fornecedores) e contas a receber (clientes) de um mercado ou hortifrúti chamado **Ambos**.

## Descrição

Aplicação frontend desenvolvida com **HTML**, **CSS** e **JavaScript** (ES6 modules), integrada ao **Firebase Firestore** para armazenamento de dados em tempo real.

Permite o controle completo de:
- Contas a receber de clientes
- Contas a pagar para fornecedores
- Cálculo automático de juros por dia de atraso
- Pagamento parcial ou total de boletos
- Exclusão de registros

Interface clean com tema verde, inspirada em mercados de hortifrúti.

## Funcionalidades

- **Tela Inicial** – Acesso rápido às seções de Contas a Pagar e Contas a Receber
- **Cadastro de Clientes** – Registro de contas a receber com valor, vencimento, juros e status
- **Cadastro de Fornecedores** – Registro de boletos a pagar
- **Listagem de Contas a Receber** – Exibe dias até/atraso, juros acumulados e valor total atualizado
- **Listagem de Contas a Pagar** – Permite pagamento parcial via modal, atualiza valor pago e status (Em aberto / Parcial / Pago)
- **Exclusão** de contas e boletos
- **Persistência** de dados no Firebase Firestore

## Tecnologias

- HTML5
- CSS3 (Flexbox, variáveis CSS)
- JavaScript Vanilla (ES6 modules)
- Firebase Firestore (backend NoSQL)

## Estrutura do Projeto

