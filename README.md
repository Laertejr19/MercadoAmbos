Mercado Ambos - Sistema de Gestão de Contas
Sistema web simples para gerenciamento de contas a pagar (fornecedores) e contas a receber (clientes) de um mercado/hortifrúti chamado "Ambos".
Descrição
Aplicação frontend desenvolvida em HTML, CSS e JavaScript vanilla, com integração ao Firebase Firestore para armazenamento de dados em tempo real.
Permite:

Cadastrar contas de clientes (a receber)
Cadastrar boletos de fornecedores (a pagar)
Listar todas as contas/boletos com cálculo automático de juros por dia de atraso
Visualizar valor total com juros aplicados
Marcar pagamento parcial ou total de boletos (com modal)
Excluir contas ou boletos
Interface responsiva com tema verde escuro, inspirado em mercados de hortifrúti

Funcionalidades Principais

Tela Inicial (index.html): Apresentação com cards para acessar Contas a Receber e Contas a Pagar.
Contas a Receber (pagina2.html): Lista todas as contas de clientes, calcula dias vencidos/atrasados e valor total com juros.
Contas a Pagar (pagina3.html): Lista boletos de fornecedores, permite pagamento parcial via modal e atualiza status (Em aberto / Parcial / Pago).
Cadastro de Cliente (cliente.html): Formulário para registrar nova conta a receber.
Cadastro de Fornecedor (fornecedor.html): Formulário para registrar novo boleto a pagar.
Cálculo de Juros: Automático com base em % ao dia e dias de atraso.

Tecnologias Utilizadas

HTML5
CSS3 (com variáveis e layout flexbox)
JavaScript (ES6 modules)
Firebase Firestore (banco de dados NoSQL em nuvem)
Nenhuma dependência externa além do SDK do Firebase

Estrutura de Pastas
text/
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
│   ├── calculo2.js
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
Como Usar

Clone o repositório
Abra o arquivo index.html em um navegador
O sistema funcionará imediatamente, pois utiliza Firebase como backend
Cadastre contas e boletos pelas telas respectivas
Acesse as listas para visualizar, pagar ou excluir registros

Configuração do Firebase
O projeto já está configurado com um projeto Firebase público (mercado-ambos).
Os dados são armazenados nas coleções:

contas → contas a receber (clientes)
boletos → contas a pagar (fornecedores)

Atenção: Como as credenciais estão expostas, recomenda-se criar seu próprio projeto Firebase e substituir a configuração em js/firebaseConfig.js.
Capturas de Tela
Tela Inicial
Contas a Receber
Contas a Pagar
Licença
Projeto livre para uso pessoal ou educacional. Sem licença formal definida.
Desenvolvido como projeto prático de gerenciamento financeiro simples para pequenos comércios.
