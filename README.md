#API REST com Spring Boot para gerenciamento de pessoas

Essa API foi criada para o desafio de projeto da Digital Innovation One. Neste projeto foi utilizado:

- Spring Boot 2.5.4
- Java 11
- Maven

Para exextuar o projeto, utilize o seguinte código no diretório do projeto:

ˋˋˋ
mvn spring-boot:run
ˋˋˋ

Após o comando, abra o navegador e entre no seguinte endereço:

ˋˋˋ
http://localhost:8080/api/v1/people
ˋˋˋ

Este endereço pode ser usado para listar as pessoas salvas, armazenar novas pessoas.<br>
Para buscar uma pessoa específica, digite o endereço acima seguido pela ID que deseja, podendo buscar, atualizar ou deletar.<br></br>
Também foi criado um deploy em nuvem pelo Heroku no seguinte endereço:

ˋˋˋ
https://personapi-example.herokuapp.com/api/v1/people/
ˋˋˋ