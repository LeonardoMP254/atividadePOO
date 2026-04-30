# 💬 Simulador de Conversa Interativa (Chat com Escolhas)

## 📌 Sobre o projeto

Este projeto consiste em uma simulação de conversa interativa entre um aluno e um professor, desenvolvida utilizando **HTML, CSS e JavaScript**.

A aplicação funciona como um pequeno sistema de diálogo onde o usuário pode escolher respostas por meio de botões, e a conversa evolui dinamicamente com base nessas escolhas — semelhante a um **chat interativo ou visual novel**.

---

## 🎯 Objetivo

O principal objetivo do projeto foi:

* Praticar manipulação do DOM com JavaScript
* Criar interações dinâmicas em uma página web
* Simular um fluxo de conversa com múltiplos caminhos
* Melhorar a organização e reutilização de código

---

## 🛠️ Tecnologias utilizadas

* HTML5 → estrutura da página
* CSS3 → estilização da interface
* JavaScript → lógica da aplicação e interatividade

---

## ⚙️ Funcionalidades

* Exibição de mensagens no formato de chat
* Escolha de respostas através de botões
* Atualização dinâmica da conversa
* Remoção de opções após seleção (simulando envio de mensagem)
* Respostas diferentes com base nas escolhas do usuário

---

## 🧠 Lógica do sistema

O sistema funciona através da criação dinâmica de elementos HTML usando JavaScript:

* `createElement()` → cria novas mensagens
* `innerHTML` → define o conteúdo das mensagens
* `appendChild()` → adiciona mensagens ao chat
* `remove()` → remove botões após escolha

A conversa segue um fluxo baseado em funções como:

* `positivo()`
* `negativo()`
* `mentir()`
* `verdade()`

Cada função representa uma decisão do usuário e altera o rumo da conversa.

---

## 📁 Estrutura do projeto

```
📦 projeto-chat
 ┣ 📜 index.html
 ┣ 📜 style.css
 ┗ 📜 script.js
```

---

## 🚀 Como executar

1. Baixe ou clone o projeto
2. Abra o arquivo `index.html` em seu navegador
3. Interaja com os botões para navegar pela conversa

---

## 💡 Possíveis melhorias

* Adicionar animação de "digitando..."
* Implementar rolagem automática do chat
* Criar múltiplos caminhos de história mais complexos
* Salvar progresso da conversa
* Melhorar o design (responsividade e layout)

---

## 📷 Demonstração

*(Você pode adicionar aqui prints do seu projeto rodando)*

---

## 👨‍💻 Autor

Projeto desenvolvido por você como prática de desenvolvimento web e lógica de programação.

---

## 📚 Considerações finais

Este projeto é uma ótima base para evoluir para aplicações mais complexas, como:

* Sistemas de atendimento automatizado (chatbots)
* Jogos interativos baseados em escolhas
* Interfaces dinâmicas com manipulação de estado

---
