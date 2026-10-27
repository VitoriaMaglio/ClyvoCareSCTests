Testes de Software — ClyvoCare

Testes manuais

Foram elaborados 16 casos de teste manuais no Azure Boards, abrangendo autenticação, autorização, cadastro de tutores, pets, veterinários, clínicas e funcionalidades do sistema.

Automação de testes

A automação foi desenvolvida utilizando o Postman, com requisições HTTP e scripts JavaScript para validar as respostas da API REST desenvolvida em Spring Boot.

Foram implementados 13 cenários automatizados, incluindo testes positivos e negativos.

Execução

Os testes foram executados por meio do Postman Collection Runner, utilizando o ambiente ClyvoCare Local.

Resultado final: todos os testes automatizados passaram na execução da coleção, sem falhas.

Como executar

Inicie a API ClyvoCare e suas dependências -> ajuste as variáveis de ambiente da aplicação.

Importe a coleção e o ambiente disponíveis na pasta tests/postman.

Configure a URL da API e as credenciais dos usuários de teste.

Selecione o ambiente ClyvoCare Local.

Execute a coleção utilizando o Postman Collection Runner.

Confira os resultados na aba de execução.


Azure -> https://dev.azure.com/RM563509/ClyvoCareScrum 
