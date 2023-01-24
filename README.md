# Web Services com Spring Boot e JPA/Hibernate
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DanielSalge/-workshop-springboot3-jpa/blob/main/LICENSE) 

# Sobre o projeto

Web Services com Spring Boot e JPA/Hibernate é uma aplicação backend desenvolvida durante o curso Java COMPLETO 2023 Programação Orientada a Objetos +Projetos. Curso organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em um webservice divididos em camadas das quais são: Resource Layer(rest controller) que recebe as requisições e irão responder de acordo com o comportamento do sistema; Service Layer; e Data Access Layer(data repositories). Todas as camada anteriormente citadas comunicam-se com as entidades do projeto. 

## Modelo de Domínio
![Domain Model](https://github.com/DanielSalge/assets/blob/main/modelo%20de%20dominio.png)

## Instância de Domínio
![Domain Instance](https://github.com/DanielSalge/assets/blob/main/modelo%20de%20instanciação.png)

## Camadas Lógicas
![Logical Layers](https://github.com/DanielSalge/assets/blob/main/logical%20layers.png)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Implantação em produção
- Banco de dados: Postgresql

# Como executar o projeto

## Back end
Pré-requisitos: Java 17+

```bash
# clonar repositório
git clone https://github.com/DanielSalge/-workshop-springboot3-jpa.git

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run

# no postman
get http://localhost:8080/users

# no navegador:
localhost:8080/h2-console/
Driver Class: org.h2.Driver
JDBC URL: jdbc:h2:mem:testdb
Username: sa
```
# Autor

Daniel Solis Salge

https://www.linkedin.com/in/danielsalge/
