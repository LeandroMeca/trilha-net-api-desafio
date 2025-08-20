<h1>Sistema de Agendamento de Tarefas com .NET e Entity Framework</h1>

<h2>Visão Geral do Projeto</h2>
<p>Este projeto consiste em uma API RESTful simples, construída com .NET e Entity Framework Core, para o gerenciamento de uma lista de tarefas. A aplicação permite criar, consultar, atualizar e deletar tarefas, persistindo os dados em um banco de dados SQL Server. A documentação da API é gerada automaticamente e pode ser acessada de forma interativa através do Swagger.</p>

<h2>Tecnologias</h2>
<p>.NET 8 (ou superior)</p>
<p>Entity Framework Core</p>
<p>Swagger (Swashbuckle)</p>
<p>SQL Server</p>

<h2>Ferramentas utilizadas</h2>
<p>Visual Studio Code (ou Visual Studio)</p>
<p>SQL Server Management Studio (ou Azure Data Studio)</p>
<p>.NET CLI</p>

<h2>Pacotes utilizados</h2>
<p>Microsoft.EntityFrameworkCore.SqlServer</p>
<p>Microsoft.EntityFrameworkCore.Design</p>
<p>Swashbuckle.AspNetCore</p>
<p>Microsoft.EntityFrameworkCore.Tools</p>
<p>dotnet-ef (Ferramenta Global)</p>

<h2>Comandos</h2>
<p>O comando abaixo cria a estrutura da migration baseada no seu modelo de dados:</p>
<p>dotnet ef migrations add CriacaoInicial</p>
<p>Este comando aplica a migration e cria ou atualiza as tabelas no banco de dados:</p>
<p>dotnet ef database update</p>

<h2>Como Executar o Projeto</h2>
<p>Primeiramente, você precisa ter o .NET SDK e um banco de dados SQL Server instalados. Após clonar o repositório, configure sua string de conexão no arquivo 'appsettings.json'. Em seguida, abra o terminal na pasta do projeto, instale as dependências com o comando 'dotnet restore'. Depois, aplique as migrations com 'dotnet ef database update' para criar as tabelas. Por fim, execute o projeto com 'dotnet run' e acesse a documentação interativa pela URL fornecida no console, adicionando /swagger ao final.</p>

<h2>Conclusão</h2>
<p>Apesar de ser um projeto de escopo reduzido, ele serve como uma excelente base para entender os fundamentos da construção de APIs com .NET e Entity Framework. Pode ser facilmente expandido com novas funcionalidades, tornando-se uma ferramenta útil para o dia a dia e para estudos.</p>
