
# Projeto Final - O Desafio - Tryitter

Contexto:
O objetivo é proporcionar um ambiente em que as pessoas estudantes poderão, por meio de textos e imagens, compartilhar suas experiências e também acessar posts que possam contribuir para seu aprendizado.💚

Você fará parte do time de desenvolvimento do Back-End dessa rede social! Bora realizar esse desafio!?🚀

Após muitas reuniões com todo o time que faz parte deste projeto, vocês decidiram nomear essa rede social como Tryitter, pois ela terá características próximas à estrutura de uma outra rede social já existente, o Twitter.

![Logo](https://content-assets.betrybe.com/prod/Arquitetura%20do%20Tema%201.jpeg)


## Requisitos técnicos:


- Utilizar C#, SQL Server e Azure;
- Ter rotas autenticadas e rotas anônimas;
- Utilizar os frameworks xUnit e FluentAssertions para criar testes.

## Funcionalidades:


- Implementar um C.R.U.D. para as contas de pessoas estudantes;
- Implementar um C.R.U.D. para um post de uma pessoa estudante;
- Alterar um post depois de publicado.

## Extra:

- Implementar três endpoints referentes à publicação de posts:
- Inserir um post;
- Listar todos os seus posts;
- Listar o último post.
- Implementar dois endpoints referentes à procura de posts em outras contas:
- Listar todos os posts de uma conta x;
- Listar o último post de uma conta x.
- Implemente testes com uma cobertura boa para suas funcionalidades. Isso mostra como sua aplicação está preparada para o futuro;
- Mostre testes de carga com centenas ou milhares de requisições sendo respondidas sem o servidor travar. Isso mostra como trabalhar bem com assincronicidade.
   
## Docker Compose

Para subir um banco de dados utilizando container, consta na raíz do diretório um arquivo docker-compose.yaml. O mesmo subirá um container com o banco MySQL configurado para a conexão com a aplicação.

## Migrations

    Verifique suas configuração de conexão ao banco apontam corretamente para o banco de dados válido. Caso utilize o docker-compose.yaml, isso acontecerá automaticamente.

Rode o comando: dotnet ef migrations add <nome da migration>

Em seguida rode: dotnet ef database update

## Fluxo do Usuário
[Projeto Tryitter](https://youtu.be/a08rxu2cUtI)

Para rodar os testes, rode o seguinte comando

```bash
  npm run test
  
 ## Tecnologias Utilizadas

   - C#
   - .dotNET 6
   - BCrypt
   - XUnit Testes
   - FluentAssertions
   - Mock
   - QRCoder para geração de QRCode
   - RestSharp para conexões Http em outros endpoints
   - NewtonSoft para serilização dos Json's    
   - AutoMapper
  
## Referência

 - [Macoratti](https://www.macoratti.net/)
 - [Desenvolvedor.io](https://desenvolvedor.io/
 - [Balta.io](https://balta.io/cursos/aplicando-orientacao-a-objetos-em-projetos-reais-com-csharp-11-e-dotnet-7)
  
## Autor

- [alexandre-pas](https://www.github.com/alexandre-pas)



