<h1>Construindo um Sistema de Agendamento de Tarefas com Entity Framework</h1>
<h2>Visão Geral do Projeto</h2>
<p>Uma Api simples e com apenas uma entidade para criação de tarefas sendo ela executada ou pendente</p>
<h2>Tecnologias</h2>
<p>Entity Framework</p>
<p>Swagger</p>
<p>SQLServer</p>
<h2>Ferramentas utilizadas</h2>
<p>VsCode, SQLServer, Microsoft SqlServer Management Studio</p>
<h2>Pacotes utilizados</h2>
<p>dotnet ef migrations add Tarefa</p>
<p>dotnet add package Microsoft.EntityFrameworkCore.SqlServer --version 9.0.3</p>
<p>dotnet add package Microsoft.EntityFrameworkCore.Design --version 9.0.3</p>
<p>dotnet add package Swashbuckle.AspNetCore --version 9.0.3</p>
<p>dotnet add package Microsoft.EntityFrameworkCore.Tools --version 9.0.3</p>
<p>dotnet tool install --global dotnet-ef --version 9.0.3</p>
<h2>Comandos</h2>
<p></p>
<p>depois que criar o banco de dados - dotnet ef migrations add Tarefa</p>
<p>esse comando vai criar as tabelas no banco de dados - dotnet ef database update</p>
<h2>Como Executar o Projeto</h2>
<p>Primeiramente você preciso ter algum banco de dados instalado e configurado o acesso, com as ferramentas instaladas é preciso ter a string de conexão do banco de dados e os devidos pacotes instalados, e migrations configuradas utilizar o comando dotnet run e acessar pelo link liberado com /swagger</p>
<h2>Conclusão</h2>
<p>Apesar de um projeto extremamente pequeno pode ser muito util e de grande ajuda no dia dia </p>

