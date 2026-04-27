# Arquitetura do Projeto

## Modelo Arquitetural (C4 Model)
O projeto foi modelado utilizando o C4 Model, nos níveis Context e Container.

## Diagrama de Contexto
![Contexto](./images/c4-context.png)

## Diagrama de Containers
![Containers](./images/c4-container.png)

---

## Tecnologias Escolhidas

### Frontend
React

Justificativa:
Interface responsiva e componentizada.

### Backend
Node.js + Express

Justificativa:
Simplicidade para APIs REST e rápida implementação.

### Banco de Dados
PostgreSQL

Justificativa:
Armazenamento relacional para usuários, hábitos e metas.

---

## Projeto Arquitetural

A solução adota arquitetura em camadas:

- Camada de apresentação (Frontend)
- Camada de negócio (Backend)
- Camada de dados (Banco)

O frontend consome serviços expostos pelo backend, responsável pela lógica de negócio e persistência dos dados.

---

## Justificativa do Modelo Escolhido

O modelo C4 foi escolhido por permitir representar a arquitetura em diferentes níveis de abstração, facilitando entendimento da solução e comunicação do projeto.
