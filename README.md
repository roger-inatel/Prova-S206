# Testes de API - Prova (Postman)

Este projeto consiste em uma coleção de testes de API utilizando o **Postman** com os seguintes endpoints da API **Swagger Petstore**:

## ✅ Requisições Realizadas

- **2 requisições GET**
  - 🔹 Login de usuário
  - 🔹 Logout de usuário
- **1 requisição POST**
  - 🔹 Envio de informações relacionadas a um pet via `petId`
- **1 requisição DELETE**
  - 🔹 Exclusão de informações relacionadas a um pet via `petId`

---

## Requisitos

Para executar o projeto, você precisa ter instalado:

- [Postman](https://www.postman.com/downloads/)
- [Node.js](https://nodejs.org/) (necessário para execução via terminal com Newman)
- Newman e Mochawesome Reporter:
  
```bash
npm install -g newman newman-reporter-mochawesome
