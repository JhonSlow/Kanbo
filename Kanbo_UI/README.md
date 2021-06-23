## Kanbo Application

Essa é uma implementação simples de um kanban board para fins academicos.

Foram utilizadas as seguintes tecnologias:

- MySql database
- Java backend (Spring Boot)
- Angular frontend

A aplicação possui um unico ponto de acesso para os usuarios: "http://localhost:4200/"

### Prerequisites

Ferramentas:
  NodeJS.

Bibliotecas:
  @angular/cdk/drag-drop
  @angular/router
  @angular/core
  @angular/material


### How to run it?

Para rodar a aplicação será necessario que o back-end(API) esteja rodando antes que o front-end(UI) seja iniciado.

Na sequencia, basta abrir o terminal no directorio da aplicação e digitar "$ng serve" que a aplicação sera inciada em "http://localhost:4200".

#### kanban-mysql (Database)

Os dados necessarios para que a aplicação funcione corretaemnte serão armazenados com MySql, utilizando as seguintes diretrizes:
  ports:
    - 3306-3306
  environment:
    - DB:kanban
    - USER:user
    - PASSWORD:""


