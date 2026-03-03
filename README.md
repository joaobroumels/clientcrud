# Client CRUD API

API REST desenvolvida com **Java e Spring Boot** para gerenciamento de clientes, aplicando boas práticas como arquitetura em camadas, validação de dados e tratamento global de exceções.

---

## 🚀 Tecnologias utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Jakarta Validation

---

## 📌 Funcionalidades

- ✔ Busca paginada de clientes
- ✔ Busca por ID
- ✔ Inserção de cliente
- ✔ Atualização de cliente
- ✔ Remoção de cliente
- ✔ Validação de dados
- ✔ Tratamento de exceções (404 e 422)

---

## 🏗️ Arquitetura

Projeto estruturado em camadas:

- Controller
- Service
- Repository
- DTO
- Exception Handler

---

## ▶️ Como executar o projeto

```bash
git clone https://github.com/joaobroumels/clientcrud
cd clientcrud
./mvnw spring-boot:run
