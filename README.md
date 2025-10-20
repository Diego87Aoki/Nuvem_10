# 🧩 Postman e MongoDB Atlas – Aula Prática U3 RAP S2

Projeto desenvolvido como parte da disciplina **Computação em Nuvem**, do curso de **Análise e Desenvolvimento de Sistemas** da **Anhanguera – Unidade 4 Ouro Verde**, sob orientação da professora **Simone Canto**.

---

## 🎯 Objetivo da Atividade

O objetivo desta prática foi compreender o uso integrado de ferramentas em **ambiente de computação em nuvem**, explorando:

- **MongoDB Atlas** como serviço de banco de dados NoSQL em nuvem.  
- **Postman** como ferramenta de teste e desenvolvimento de APIs.  
- **Node.js** como intermediário entre o cliente (Postman) e o banco de dados (MongoDB).

Essa integração permite compreender, de forma prática, o ciclo completo de funcionamento de uma API moderna — **do envio de dados à persistência em nuvem**.

---

## 🧠 Conceitos Principais

### 🔸 MongoDB Atlas
O **MongoDB Atlas** é um banco de dados **NoSQL orientado a documentos**, acessível via nuvem.  
Os dados são armazenados no formato **JSON**, o que torna o sistema flexível para lidar com informações **não estruturadas** ou **semi-estruturadas**.

**Exemplos de dados manipulados:**
```json
{
  "fabricante": "Ford",
  "modelo": "Ka",
  "ano": 2010,
  "preco": 11000
}
````

### 🔸 Postman

O **Postman** é uma ferramenta para **testar APIs REST**.
Ele permite enviar requisições HTTP (`GET`, `POST`, `PUT`, `DELETE`) e visualizar as respostas do servidor.
É ideal para validar rotas, parâmetros e o comportamento de APIs conectadas a bancos de dados.

---

## ⚙️ Fluxo de Integração

1. Criar o banco de dados no **MongoDB Atlas**.
2. Configurar a aplicação **Node.js** com a string de conexão.
3. Utilizar o **Postman** para testar as rotas HTTP da API:

   * `GET /carros` → lista todos os carros.
   * `POST /carros` → adiciona um novo carro.
   * `DELETE /carros/:id` → exclui um carro pelo ID.

---

## 📋 Tecnologias Utilizadas

| Tecnologia            | Função                                             |
| --------------------- | -------------------------------------------------- |
| **MongoDB Atlas**     | Armazenamento de dados em nuvem (NoSQL)            |
| **Node.js / Express** | Criação e execução da API                          |
| **Postman**           | Teste e validação das requisições HTTP             |
| **JavaScript (JSON)** | Formato de dados trocados entre cliente e servidor |

---

## 📚 Resultados Esperados

* Compreensão prática sobre o uso de **bancos de dados em nuvem**.
* Teste de **APIs RESTful** usando o Postman.
* Integração entre **Node.js e MongoDB Atlas**.
* Experiência com **armazenamento de dados não estruturados**.

---

## 👨‍💻 Autor

**Diego Roberto Aragan Aoki**
RA: 403131612035
Curso: Análise e Desenvolvimento de Sistemas
Unidade: Anhanguera – Ouro Verde
Professora: Simone Canto
📅 Data da entrega: 20/10/2025

---

## 📄 Licença

Este projeto é de caráter **educacional**, desenvolvido para fins acadêmicos no contexto da disciplina *Computação em Nuvem*.
Sinta-se à vontade para estudar, adaptar e evoluir o código para fins de aprendizado.
