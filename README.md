# TopicosForum

TopicosForum é um desafio para criação de uma API REST backend usando **Spring Boot**.  
O objetivo é implementar um sistema de gerenciamento de tópicos de fórum com operações completas de CRUD (Create, Read, Update, Delete), seguindo boas práticas do desenvolvimento REST, com persistência em banco relacional e autenticação/autorização.

---

## Funcionalidades

- Criar um novo tópico  
- Listar todos os tópicos  
- Visualizar um tópico específico  
- Atualizar um tópico  
- Excluir um tópico  

---

## Objetivos

- Desenvolver rotas REST seguindo padrões e melhores práticas  
- Validar dados conforme regras de negócio  
- Utilizar banco de dados relacional para persistência  
- Implementar autenticação e autorização para proteger os recursos  

---

## Tecnologias Utilizadas

- Java 17+  
- Spring Boot  
- Spring Data JPA  
- Banco relacional (MySQL)  
- Spring Security  
- Maven ou Gradle  

---

## Endpoints

| Método | Endpoint           | Descrição                |
|--------|--------------------|--------------------------|
| POST   | `/topicos`         | Criar um novo tópico     |
| GET    | `/topicos`         | Listar todos os tópicos  |
| GET    | `/topicos/{id}`    | Visualizar tópico pelo ID|
| PUT    | `/topicos/{id}`    | Atualizar um tópico       |
| DELETE | `/topicos/{id}`    | Excluir um tópico         |

---

## Como Executar

1. Clone o repositório:  
   ```bash
https://github.com/manobernardo/topicosForum.git
