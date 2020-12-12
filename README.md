# Construindo uma API.NET c/ MongoDB

Copyright - Gabriel Faraday



**Descrição** - Atividade do Bootcamp Avanade Fullstack Developer ministrado pelo Gabriel Faraday.

**Objetivo** - Criar uma Api.Net com MongoDB para localização de pessoas afetadas pela covid-19.

- [ ] .NetCore (c#)
- [ ] MongoDB Atlas

**Conteúdo** - Conceitos de frontend, backend, api, verbos http e banco de dados no-sql

## Passos para rodar o projeto:

1. Criar um cluster no mongodb Atlas (Free);

2. Criar um usuário no DB via MongoBD Atlas e seleciar o Authentication Method - Password

3. No meu Network Access liberar os IP's que podem acessar o database

4. Ir no cluster, clicar em Connect, selecionar o item Connect your aplication e selecionar qual a linguagem da aplicação

5. Criar um projeto dotnet via CLI

   ` dotnet new api -n <nome do projeto>`

6. Copiar a connection string e substituir no appsettings.json. 

7. Alterar a tag password pela senha gerada anteriormente e o nome do DB

8. Instalar o pacote para atuar com geolocalização em mongoDB via CLI

   `dotnet add package MongoDB.Driver`

9. Debugar o projeto (F5 no Visual Studio Code) ou via CLI

   `dotnet run`

10. Consumir a API via plataforma (Postman/Insomnia) e fazer o gerenciamento via Atlas

Referências:

https://docs.mongodb.com/

https://docs.mongodb.com/manual/

https://docs.mongodb.com/ecosystem/drivers/csharp/

https://docs.atlas.mongodb.com/

