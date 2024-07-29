# DIO - Trilha Java Básico
Site: <a href="https://www.dio.me/" target="_blank">DIO</a>

# Desafio API RESTful
Projeto de API RESTful utilizando java e Spring Boot

## Diagrama de Classes - Domínio da API

```mermaid
classDiagram
  class User {
    -String name
    -Account account
    -Feature[] features
    -Card card
    -News[] news
  }

  class Account {
    -String number
    -String agency
    -Number balance
    -Number limit
  }

  class Feature {
    -String icon
    -String description
  }

  class Card {
    -String number
    -Number limit
  }

   class News {
    -String icon
    -String description
  }
```


#### Autor : [Matheus Pacheco](https://github.com/matheuspacheco99)

