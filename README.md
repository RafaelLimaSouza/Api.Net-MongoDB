#Construindo um projeto de uma API.NET integrada ao MongoDB

Copyright - Gabriel Faraday

Atividade do Bootcamp Avanade Fullstack Developer ministrado pelo Gabriel Faraday.

Objetivo - Criar uma Api.Net com MongoDB para localização de pessoas afetadas pela covid-19.

Tecnologias - .NetCore (c#)
                MongoDB Atlas

Conteúdo - Conceitos de frontend, backend, banco de dados no-sql

Passos para rodar o projeto:

1º passo - Criar um cluster no mongodb Atlas (Free);
2º passo - Criar um projeto dotnet
            CLI: dotnet new api -n <nome do projeto>
3º passo - Criar um usuário no DB via MongoBD Atlas e seleciar o Authentication Method - Password
4º passo - No meu Network Access liberar os IP's que podem acessar o database
5º passo - Ir no cluster, clicar em Connect, selecionar o item Connect your aplication e selecionar qual a linguagem da aplicação
6º passo - Copiar a connection string e substituir no appsettings. Alterar a tag password pela senha gerada anteriormente
7º passo - Alterar o nome do DB
8º passo - instalar o pacote para atuar com geolocalização em mongoDB
            CLI: dotnet add package MongoDB.Driver
9º passo - Debugar o projeto
            CLI: dotnet run
10º passo - Consumir a API via plataforma (Postman/Insomnia) e fazer o gerenciamento via Atlas

Referências:

https://docs.mongodb.com/

https://docs.mongodb.com/manual/

https://docs.mongodb.com/ecosystem/drivers/csharp/

https://docs.atlas.mongodb.com/

