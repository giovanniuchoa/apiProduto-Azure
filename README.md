# DevOps - Sistemas de Informação - Grupo 8

## 👥 Equipe
- Nome 1 - Giovanni Uchoa
- Nome 2 - João Gregorini
- Nome 3 - Bruno Guttervill

## 👥 Descrição do Sistema
- A linguagem utilizada na construção da API foi C#, no ambiente do .NET 9.0 utilizando Entity Framework como ORM code-first implementando em um banco de dados SQL Server.
- Criamos cinco endpoints, são eles: GET, GET List, POST, PUT e DELETE da entidade "Produto".
- Testes: unitários e integrados.
- A documentação Swagger está disponível em `webapp-dotnet-produtos-gpc7bsdteyezchaf.brazilsouth-01.azurewebsites.net`.

## 👥 Estratégia de Branches (Gitflow)
- Branch principal: `main`
- Branch de desenvolvimento: `develop`
- Branch de release: `release`
- Branches de tarefa: `usuario/tarefa`

## 👥 Políticas de Branch
- Commits diretos na `main`: **não permitidos**.
- Pull requests: **obrigatórios**, com **aprovação** de ao menos 1 membro.

## 👥 Azure Pipeline
- Arquivo de configuração: `azure-pipelines.yml`
- Stages implementados: build, test, deploy
- Deploy realizado no: **Azure App Service** (webapp-dotnet-produtos)
- Banco de dados: **DBaaS** - SQL Server (sql-server-grupo8).
