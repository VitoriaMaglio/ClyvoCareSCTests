🧪 Testes de Software — ClyvoCare

Este repositório contém a documentação e os testes de software desenvolvidos para o projeto ClyvoCare, incluindo testes manuais e automatizados para validar as principais funcionalidades da API REST desenvolvida em Spring Boot.

📋 1. Testes Manuais

Foram elaborados 16 casos de teste manuais, documentados e organizados no Azure Boards, abrangendo as principais funcionalidades do sistema:

Autenticação e autorização de usuários;

Cadastro e gerenciamento de tutores;

Cadastro e gerenciamento de pets;

Cadastro de veterinários;

Cadastro e gerenciamento de clínicas;

Validação das regras de negócio e permissões de acesso.

🔗 Azure Boards: Acessar projeto ClyvoCareScrum

🤖 2. Automação de Testes

A automação foi desenvolvida utilizando o Postman, por meio de requisições HTTP e scripts em JavaScript para validar as respostas da API REST.

Foram implementados 13 cenários de testes automatizados, contemplando:

Testes positivos: validação de operações executadas com sucesso;

Testes negativos: verificação do tratamento de erros, entradas inválidas e acessos não autorizados;

Validação de status HTTP: verificação dos códigos de resposta esperados;

Validação de respostas: conferência dos dados retornados pela API.

🛠️ Tecnologias utilizadas

Java e Spring Boot — Desenvolvimento da API REST;

Postman — Automação e execução dos testes;

JavaScript — Scripts de validação;

Azure Boards — Planejamento e gerenciamento dos testes manuais.

✅ 3. Resultados da Execução

Os testes automatizados foram executados por meio do Postman Collection Runner, utilizando o ambiente ClyvoCare Local.

Indicador

Resultado

Casos de teste manuais

16

Cenários automatizados

13

Ferramenta de execução

Postman Collection Runner

Ambiente utilizado

ClyvoCare Local

Resultado final

✅ Todos os testes passaram

Falhas identificadas

0

Resultado: todos os cenários automatizados foram executados com sucesso, sem falhas na execução da coleção.

🚀 4. Como Executar os Testes Automatizados

Pré-requisitos:

API ClyvoCare e suas dependências em execução localmente ou usar link da aplicação no Render;

Postman instalado;

Ambiente da aplicação configurado;

Credenciais válidas para os usuários de teste.

Passo a passo (Links no tópico 6):

Inicie a API ClyvoCare e configure as variáveis de ambiente necessárias.

Abra o Postman.

Importe os arquivos de coleção e ambiente disponíveis no diretório tests/postman/.

Configure a URL base da API e as credenciais dos usuários de teste.

Selecione o ambiente ClyvoCare Local.

Execute a coleção utilizando o Postman Collection Runner.

Confira os resultados e as validações na aba de execução.

📂 5. Estrutura do Repositório

ClyvoTests/
├── azure/
│   ├── Capturar.PNG
│   └── link.txt
│
└── tests/
    ├── README.md
    └── postman/
        ├── Capturar.PNG
        ├── ClyvoCare - Automated Tests.postman_collection.json
        └── ClyvoCare Local.postman_environment.json

🔗 6. Links do Projeto

Azure Boards: [ClyvoCareScrum](https://dev.azure.com/RM563509/ClyvoCareScrum/_workitems/recentlyupdated/)

Repositório da API: [ClyvoCareSC](https://github.com/VitoriaMaglio/ClyvoCareSC.git)

Link da API na nuvem para testes: 	https://clyvocaresc.onrender.com
Usar esse link acima na variável de ambiente baseUrl no Postman -> Assim é possível realizar os testes automatizados sem precisar ter a aplicação rodando localmente.

Repositório de Testes: ClyvoCareSCTests

Vídeo explicativo: [https://www.youtube.com/watch?v=xcwvwPT6sRg ](https://youtu.be/xcwvwPT6sRg?is=szFKm2j4Xc2H0Pdg)

Projeto acadêmico — FIAP | Análise e Desenvolvimento de Sistemas

Sprint 4 — Testes de Software
