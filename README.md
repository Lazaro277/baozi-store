# Baozi Store

API REST desenvolvida em Java com Spring Boot para gerenciamento de produtos, clientes e pedidos de uma loja fictícia de baozi.

## Tecnologias utilizadas

- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven

## Funcionalidades

- Cadastro, consulta e exclusão de produtos
- Cadastro, consulta e exclusão de clientes
- Cadastro, consulta e exclusão de pedidos

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/Lazaro277/baozi-store.git
   ```

2. Crie o banco de dados `baozi_store` no MySQL.

3. Configure as credenciais do banco no arquivo `application.properties`.

4. Execute a aplicação pelo Eclipse ou utilizando o Maven.

## Endpoints

| Recurso | Endpoint |
|---|---|
| Produtos | `/api/produtos` |
| Clientes | `/api/clientes` |
| Pedidos | `/api/pedidos` |

A API permite operações de cadastro, consulta e exclusão utilizando os métodos HTTP.

## Autor

**Lázaro Messias**

[GitHub](https://github.com/Lazaro277)
