
# 🛒 Grocery Store API – Postman Tests

## 📖 Sobre

Testes de API desenvolvidos no Postman, organizados por cenários positivos e negativos.

**Testes focados em garantir segurança, validação de dados e comportamento esperado da API.**

---

## 📂 Estrutura dos testes

* **Happy Path** → fluxo principal funcionando
* **Missing Authentication** → requisições sem token
* **Invalid Authentication** → token inválido
* **Invalid Inputs** → dados incorretos

---

## 🔐 Variáveis de ambiente

O projeto utiliza variáveis para:

* autenticação (`token`)
* controle de dados entre requisições

---

## ▶️ Como executar

1. Importar collection e environment no Postman
2. Configurar as variáveis de ambiente
3. Executar via Collection Runner

---

## 🎯 Objetivo

Validar o comportamento da API em diferentes cenários, incluindo sucesso, falhas de autenticação e entradas inválidas.

---

## 📌 Aprendizados

* Organização de testes por cenário
* Validação de respostas positivas e negativas
* Uso de variáveis de ambiente
* Testes de autenticação
