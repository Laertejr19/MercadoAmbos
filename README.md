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

/
├── css/
│   ├── style.css
│   └── style2.css
├── img/
│   ├── Cliente.jpg
│   ├── Fornecedor.jpeg
│   ├── frutas.png
│   ├── frutas2.png
│   └── Hortifrutigranjeiros.jpg
├── js/
│   ├── backend.js
│   ├── calculo.js
│   ├── firebaseConfig.js
│   ├── fornecedor.js
│   ├── pagina2.js
│   ├── pagina3.js
│   └── script.js
├── cliente.html
├── fornecedor.html
├── header.html
├── index.html
├── pagina2.html
├── pagina3.html
└── pagarC.html

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/mercado-ambos.git

   Abra o arquivo index.html diretamente no navegador.

O projeto já está configurado com um projeto Firebase público.
Para uso em produção ou com dados privados, crie seu próprio projeto no Firebase e substitua as credenciais em js/firebaseConfig.js.

Configuração Firebase (Opcional)
As coleções utilizadas são:

contas → contas a receber (clientes)
boletos → contas a pagar (fornecedores)

Licença

Projeto livre para uso pessoal, educacional ou como base para sistemas semelhantes.
Sem licença formal definida.
Desenvolvido como um sistema prático de controle financeiro para pequenos comércios.
