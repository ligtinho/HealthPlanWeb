# HealthPlan Web

A HealthPlan Web é uma aplicação REST desenvolvida com Spring Boot para gerenciar planos de saúde. Esta API oferece recursos para realizar operações CRUD (Create, Read, Update, Delete) em planos de saúde, beneficiários e outras funcionalidades relacionadas.

## Características Principais
- Cadastrar um beneficiário junto com seus documentos;
- Listar todos os beneficiários cadastrados;
- Listar todos os documentos de um beneficiário a partir de seu id;
- Atualizar os dados cadastrais de um beneficiário;
- Remover um beneficiário.

## Tecnologias Utilizadas
- Java 8
- Spring Boot
- H2 Database
- Maven
- Swagger
  
Front-end
- Thymeleaf
- JavaScript
- jQuery

## Configuração do Ambiente de Desenvolvimento
1. Baixe o repositório.

## Informações importantes
Documentação dos endpoints: http://localhost:8080/swagger-ui/index.html

Login e senha para autorização da API:
Login: admin
Senha: admin

Console do banco de dados H2: localhost:8080/h2-console/
Login: admin
Senha: admin

## Link principal
localhost:8080
Login: admin
Senha: admin

O banco de dados começa vazio, então primeiramente cadastrar um novo beneficiário.

## Executando o Build e Iniciando a Aplicação
Certifique-se de ter o Maven instalado.

```bash
mvn clean install
java -jar target/HealthPlan-1.0.jar
