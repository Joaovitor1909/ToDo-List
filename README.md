
# To-do List App (JavaScript)

This is a simple **To-Do List App** built using only **HTML, CSS, and Vanilla JavaScript**.

The goal is to practice DOM manipulation, events, local storage (`localStorage`), and dynamic creation of elements.

---
  
## 📌 Features

- ➕ **Add tasks**

- ✏️ **Edit tasks**

- ❌ **Delete tasks**

- ✔️ **Mark tasks as completed**

- 💾 **Automatic saving to localStorage**

- 🔄 **Dynamic list rendering**

- 🧩 Modular function-based structure
  

---

## 🗂️ Project Structure

```
📦 todo-app
├── index.html
├── style.css
└── script.js
```
---

## 🧠 Core Logic
### 📥 Load data from localStorage
The function `getSavedData()` retrieves saved tasks.

If none exist, it creates two default tasks.

### 💾 Save changes

`setNewData()` sends the updated array back to localStorage.

### 🏗️ Create list elements

`generateLiTask()` dynamically builds each `<li>` containing:

- check button

- task text

- edit button

- edit input field

- delete button

### 🖱️ Events

All interactions go through `clickedUl()`, which detects which button was clicked and triggers the appropriate action.

### 🔄 Rendering

`renderTasks()` clears and rebuilds the entire list each time it runs.

---

## 🚀 How to Run

1. Download or clone this repository:

```bash

git  clone  https://github.com/Joaovitor1909/ToDo-List.git

2.  Open  the  `index.html`  file  in  your  browser.

3.  Start  adding  your  tasks!

```
---


## ✨ Technologies Used

-  **HTML5**

-  **CSS3**

-  **JavaScript ES6+**

-  **LocalStorage**
---

  

  

## 📄 License

This project is open for study and personal use.
Feel free to modify and improve it!

---

## 👤 Autor

Developed by **Joaovitor19909**, based on lessons from **Serliv**.

---

# 📝 To-do List App – Lista de Tarefas (JavaScript)



Este é um projeto simples de **Lista de Tarefas (Todo App)** desenvolvido utilizando apenas **HTML, CSS e JavaScript puro (Vanilla JS)**.

O objetivo é treinar manipulação de DOM, eventos, armazenamento local (`localStorage`) e criação dinâmica de elementos.

  

---

  

## 📌 Funcionalidades

  

- ➕ **Adicionar tarefas**

- ✏️ **Editar tarefas**

- ❌ **Excluir tarefas**

- ✔️ **Marcar tarefa como concluída**

- 💾 **Salvar automaticamente no localStorage**

- 🔄 **Renderização dinâmica da lista**

- 🧩 Estrutura modular baseada em funções

  

---

  

## 🗂️ Estrutura do Projeto

```

📦 todo-app

├── index.html

├── style.css

└── script.js

```

---

  

## 🧠 Lógica Principal do Projeto

  

### 📥 Carregar dados do localStorage

A função `getSavedData()` busca as tarefas salvas.

Se não existir, cria duas tarefas iniciais.

  

### 💾 Salvar alterações

`setNewData()` envia o array atualizado para o localStorage.

  

### 🏗️ Criar elementos da lista

`generateLiTask()` monta dinamicamente cada `<li>` com:

- botão de check

- texto

- botão de edição

- campo para edição

- botão de deletar

  

### 🖱️ Eventos

Toda interação da lista passa por `clickedUl()`, que detecta qual botão foi clicado e executa a ação correspondente.
  

### 🔄 Renderização

`renderTasks()` sempre limpa e redesenha toda a lista.

---
  

## 🚀 Como executar

  

1. Baixe ou clone este repositório:

```bash

git clone https://github.com/Joaovitor1909/ToDo-List.git

```

2. Abra o arquivo `index.html` em qualquer navegador.

3. Comece a adicionar suas tarefas!

---
  

## ✨ Tecnologias Utilizadas


-  **HTML5**

-  **CSS3**

-  **JavaScript ES6+**

-  **LocalStorage**

  

---

  

## 📄 Licença

  

Este projeto é livre para estudo e uso pessoal.

Sinta-se à vontade para modificar e evoluir!

  

---


## 👤 Autor
  
Desenvolvido por **Joaovitor19909**, com base nas aulas da **Serliv**.
