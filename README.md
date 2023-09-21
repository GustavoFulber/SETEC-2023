Avalie o professor: https://docs.google.com/forms/d/e/1FAIpQLSc6TD9479DWJJcot6CXp3MXhbGFUYR-1JmTpWln3UP8dyljDA/viewform?usp=sf_link


Projeto API de Mensagens em C# com .NET 7
Este projeto tem como objetivo criar uma API de mensagens usando C# e .NET 7. A API será capaz de enviar e receber mensagens, bem como autenticar usuários usando JWT.

Dependências
As seguintes dependências são necessárias para o projeto:

AutoMapper: Para mapear objetos de domínio para DTOs.
Cronos: Para manipulação de data e hora.
MailKit: Para enviar e-mails.
Microsoft.EntityFrameworkCore: Para o mapeamento objeto-relacional e o acesso ao banco de dados.
Microsoft.AspNetCore.Authentication.JwtBearer: Para autenticação JWT.
Microsoft.Extensions.Hosting: Para hospedar a aplicação.
MySql.Data & MySqlConnector: Para conexão com banco de dados MySQL.
Newtonsoft.Json: Para serialização e desserialização de objetos JSON.
Pomelo.EntityFrameworkCore.MySql: Provedor de banco de dados MySQL para Entity Framework Core.
Swashbuckle.AspNetCore: Para documentação da API usando Swagger.
Microsoft.AspNetCore.Cryptography.KeyDerivation: Para hash de senhas.
Instalação
Certifique-se de ter o .NET 7 instalado em sua máquina.
Clone o repositório para sua máquina local.
Abra o terminal e navegue até a pasta do projeto.
Execute o comando dotnet restore para instalar todas as dependências necessárias.
Configuração
Antes de executar a aplicação, você precisará configurar o banco de dados e a chave secreta para assinatura do token JWT.

Abra o arquivo appsettings.json e configure a string de conexão do banco de dados e a chave secreta.
Execute o comando dotnet ef database update para criar o banco de dados.
Execução
Para executar a aplicação, abra o terminal, navegue até a pasta do projeto e execute o comando dotnet run.

Documentação
A documentação da API está disponível em https://localhost:7206/swagger.
