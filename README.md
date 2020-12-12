#Construindo um projeto de uma API.NET integrada ao MongoDB

Copyright - Gabriel Faraday

1º passo - Criar um cluster no mongodb Atlas (Free);
2º passo - Criar um projeto dotnet
            CLI: dotnet new api -n Api

3º passo - Criar um usuário no DB via MongoBD Atlas
            Authentication Method - Password
4º passo - No meu Network Access liberar os IP's que podem acessar o database
5º passo - Ir no cluster, clicar em Connect, selecionar o item Connect your aplication e selecionar qual a linguagem da aplicação
6º passo - Copiar a connection string e substituir a tag password pela senha gerada anteriormente
7º passo - incluido no appsettings.json, a connection string e o nome do banco.
8º passo - instalar o pacote para atuar com geolocalização em mongoDB
            CLI: dotnet add package MongoDB.Driver
9º passo - criar a classe de contexto e criar a classe Model
10º passo - criar a classe controller

