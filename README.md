# 📋 To-Do List API & Web App

## 🏢 Empresa
**Pacheco Barroso**

## 💼 Vaga
**Programador**

## 🗓️ Entrevista

| Detalhe       | Informação                           |
|---------------|--------------------------------------|
| **Data**      | 11/06/2025                           |
| **Local**     | Condomínio TSE, villa 17 (frente à academia Bai) |

---

## 🧪 Teste Técnico: To-Do List - Laravel RESTful API + Web App (Livewire 3)

### 📌 Objetivo
Desenvolver uma aplicação **API RESTful** em **Laravel** com funcionalidades completas de gerenciamento de tarefas (To-Do List), incluindo uma **interface web** utilizando **Bootstrap 5** e **Livewire 3**.

---

## 🔧 Funcionalidades da API

| Ação               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Criar tarefa       | Criar tarefa com `título (obrigatório)` e `descrição`.                    |
| Listar tarefas     | Listar **todas as tarefas** do utilizador autenticado.                    |
| Atualizar status   | Atualizar status da tarefa: `pendente`, `em andamento`, `concluída`.     |
| Deletar tarefa     | Excluir tarefa existente.                                                 |
| Filtrar por status | Permitir filtro por `status`.                                             |

---

## 🖥️ Funcionalidades da App Web (Livewire 3 + Bootstrap 5)

| Ação               | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| Criar tarefa       | Criar tarefa com `título (obrigatório)` e `descrição`.                    |
| Listar tarefas     | Listar todas as tarefas.                                                  |
| Atualizar status   | Alterar status: `pendente`, `em andamento`, `concluída`.                  |
| Deletar tarefa     | Excluir tarefas.                                                          |
| Filtros            | Filtrar por `status`, `título` e `utilizador`.                            |

---

## ✅ Validações da API

| Campo     | Regras de Validação                     |
|-----------|------------------------------------------|
| `title`   | Obrigatório (`required`)                 |
| `status`  | Deve ser um dos: `pending`, `in_progress`, `completed` |

---

## 🔁 Respostas da API

| Código HTTP | Situação                            |
|-------------|--------------------------------------|
| 200         | OK (requisição bem-sucedida)         |
| 201         | Created (recurso criado)             |
| 404         | Not Found (recurso não encontrado)   |
| 422         | Validation Error (erro de validação) |

---

## 🗄️ Banco de Dados

- Utilizar **Eloquent ORM** para todas as interações.
- Utilizar **migrations** para estrutura da base de dados.

---

## 🧪 Testes Unitários

| Teste                         | Descrição                           |
|-------------------------------|--------------------------------------|
| Criar tarefa                  | Testar criação com dados válidos.    |
| Listar tarefas                | Testar listagem de tarefas.          |
| Atualizar status              | Testar atualização de status.        |
| Deletar tarefa                | Testar exclusão de tarefa.           |
| Filtrar por status            | Testar filtro de tarefas por status. |

---

## 📄 Documentação

### 📘 README.md
Deve conter:

| Seção                  | Descrição                                                  |
|------------------------|------------------------------------------------------------|
| Instalação             | Como clonar e instalar o projeto.                         |
| Migrations             | Comando para rodar as migrations.                         |
| Execução               | Como iniciar o servidor local (`php artisan serve`).       |
| Testes API             | Como testar usando Postman ou `curl`.                      |

### 🔍 Swagger (OpenAPI)
- Documentação completa dos endpoints.
- Incluir:
  - Métodos (`GET`, `POST`, `PUT`, `DELETE`)
  - Parâmetros
  - Exemplos de resposta
  - Códigos HTTP

---

## 🧑‍💻 Boas Práticas e Avaliação

| Item                                | Critério                                                         |
|-------------------------------------|------------------------------------------------------------------|
| Organização                         | Seguir arquitetura MVC e Design Patterns.                        |
| Nomeação                            | Utilizar nomes claros e em inglês.                               |
| Recursos Laravel                    | Uso correto de migrations, Eloquent, validação, rotas.           |
| Tratamento de Erros                 | Implementar respostas e mensagens claras.                        |
| Documentação                        | Simples, objetiva e útil.                                        |
| Git e Commits                       | Utilizar **Gitflow**, com **commits claros e frequentes**.       |

---

## 🧭 Observações Finais

- A entrevista será acompanhada de **apresentação** e **execução prática** do teste.
- Projeto avaliado com base em clareza, organização, boas práticas e funcionalidade.
