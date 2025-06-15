# Desafio Controle de Fluxo 🚀

Este projeto foi desenvolvido para exercitar conceitos de **Controle de Fluxo** na linguagem **Java**, incluindo estrutura de repetição (`for`) e tratamento de exceções customizadas.

## 📌 Objetivo

Criar um sistema que recebe dois números inteiros como entrada e realiza a contagem entre eles. Se o primeiro número for maior que o segundo, o sistema deve lançar uma **exceção personalizada**.

## 📜 Regras do Desafio

1. O sistema recebe dois números via **terminal**.
2. Se o primeiro número for **maior** que o segundo, deve lançar uma exceção `ParametrosInvalidosException`.
3. Se os números forem válidos, o sistema imprime uma contagem progressiva dos números.
4. Exemplo:
   - Entrada: `12` e `30`
   - Saída:
     ```
     Imprimindo o número 1
     Imprimindo o número 2
     ...
     Imprimindo o número 18
     ```

## 🔧 Tecnologias Utilizadas

- **Java** (JDK 8+)
- **Scanner** (entrada de dados via terminal)
- **Exceções Personalizadas** (`ParametrosInvalidosException`)

## 📁 Estrutura do Projeto
DesafioControleFluxo/ 
│── src/ 
│─ Contador.java 
│   ├── ParametrosInvalidosException.java 
│── README.md

