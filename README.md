# Avanade Decola Tech 2025 
JAVA RESTful API criada para o Decola Tech 2025

## Diagrama de classes

# Diagrama de Classes - Usuário do Banco

Este diagrama representa a estrutura de classes baseada no JSON de um usuário do banco.

```mermaid
classDiagram
    class Usuario {
        +string name
    }

    class Conta {
        +string number
        +string agency
        +float balance
        +float limit
    }

    class Feature {
        +string icon
        +string description
    }

    class Cartao {
        +string number
        +float limit
    }

    class Noticias {
        +string icon
        +string description
    }

    Usuario --> Conta : possui
    Usuario --> Feature : possui *
    Usuario --> Cartao : possui
    Usuario --> Noticias : possui

```
