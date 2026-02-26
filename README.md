# 📦 Cadastro de Produtos (Evolução & Refatoração) - Projeto Fullstack

![Status](https://img.shields.io/badge/Status-Andamento-yellow)

Este repositório contém a versão evoluída do meu projeto de Cadastro de Produtos. O foco principal desta etapa foi elevar a qualidade do código através de refatoramento e da implementação de padrões robustos de desenvolvimento em **Java** e **Spring Boot**.

## 🚀 Novos Aprendizados e Implementações

Nesta versão, foquei em práticas que aproximam o projeto de aplicações reais de mercado:

- 🏗️ **Padrão DTO (Data Transfer Object)**: Implementei o uso de DTOs para garantir o desacoplamento entre as entidades de domínio e a camada de apresentação, melhorando a segurança e o controle dos dados trafegados.
- 🛡️ **Validações e Exceções**: Desenvolvi um sistema de tratamento de exceções personalizado para lidar com erros de forma elegante e adicionei validações de campos para garantir a integridade dos dados inseridos.
- 🧹 **Refatoramento & Clean Code**: Realizei uma limpeza profunda no código original, aplicando princípios de Clean Code para tornar a lógica mais legível, manutenível e profissional.
- 🔄 **Persistência Avançada**: Refinei o mapeamento e a comunicação com o banco de dados **H2 Console**, focando em boas práticas de persistência.

## 🛠️ Como Acessar o H2 Console

Para visualizar os dados em memória:

1. Inicie a aplicação.
2. Acesse: `http://localhost:8080/h2-console`
3. Verifique se a **URL JDBC** está configurada corretamente (ex: `jdbc:h2:mem:testdb`) e clique em **Connect**.

## 🖥️ Repositório do Front-End
👉🏻 [**Cadastro de Produtos - Angular**](https://github.com/kauanzin222/NewVersion-ProductRegistration-Angular)

---
*Projeto desenvolvido para fins de estudo, refatoração e aperfeiçoamento técnico. 📚*
