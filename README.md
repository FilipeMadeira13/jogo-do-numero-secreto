<h1 align="center">🎯 Jogo do Número Secreto</h1>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-EM%20DESENVOLVIMENTO-yellow?style=for-the-badge" alt="Status: Em Desenvolvimento"/>
  <img src="https://img.shields.io/badge/VERSÃO-1.0.0-blue?style=for-the-badge" alt="Versão 1.0.0"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
</p>

---

## 📋 Índice

- [📋 Índice](#-índice)
- [📖 Descrição do Projeto](#-descrição-do-projeto)
- [🚧 Status do Projeto](#-status-do-projeto)
- [🎮 Demonstração](#-demonstração)
- [✅ Funcionalidades](#-funcionalidades)
- [📁 Acesso ao Projeto](#-acesso-ao-projeto)
- [🕹️ Como Jogar](#️-como-jogar)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [📂 Estrutura do Projeto](#-estrutura-do-projeto)
- [👤 Autor](#-autor)

---

## 📖 Descrição do Projeto

O **Jogo do Número Secreto** é uma aplicação web interativa desenvolvida com JavaScript puro onde o objetivo é adivinhar um número sorteado aleatoriamente pelo sistema, em um intervalo de 1 a 500.

A cada tentativa, o jogo fornece dicas indicando se o número secreto é maior ou menor que o palpite, tornando a experiência desafiadora e divertida. Ao final, o jogo exibe quantas tentativas foram necessárias. O projeto também conta com acessibilidade por voz, lendo as mensagens em português via ResponsiveVoice.

---

## 🚧 Status do Projeto

<h4 align="center">
  🚧 Em desenvolvimento — pronto para testes 🚧
</h4>

---

## 🎮 Demonstração

Acesse a versão online e jogue agora:

👉 **[jogo-kappa-flame.vercel.app](https://jogo-kappa-flame.vercel.app/)**

> Abaixo, um exemplo da interface do jogo em funcionamento:

<!-- Substitua pelo caminho de um gif/screenshot real do jogo -->
<!-- ![Demonstração do jogo](img/demo.gif) -->

---

## ✅ Funcionalidades

- `Número aleatório`: sorteia um número secreto entre 1 e 500 a cada nova partida
- `Dicas inteligentes`: informa se o palpite deve ser maior ou menor que o número secreto
- `Contador de tentativas`: registra e exibe quantas tentativas o jogador usou
- `Reinício de partida`: botão "Novo jogo" reseta o jogo para uma nova rodada
- `Leitura em voz alta`: as mensagens do jogo são narradas em português via ResponsiveVoice.js

---

## 📁 Acesso ao Projeto

Você pode acessar o jogo de duas formas:

**▶ Online (sem instalação):**  
Acesse diretamente pelo link: [jogo-kappa-flame.vercel.app](https://jogo-kappa-flame.vercel.app/)

**💻 Localmente:**  
1. Clone ou baixe este repositório:
   ```bash
   git clone https://github.com/seu-usuario/jogo-numero-secreto.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd jogo-numero-secreto
   ```
3. Abra o arquivo `index.html` diretamente no seu navegador.

> Não é necessário instalar dependências. O projeto roda com HTML, CSS e JavaScript puros.

---

## 🕹️ Como Jogar

1. Abra o jogo no navegador.
2. Digite um número entre **1 e 500** no campo de entrada.
3. Clique em **Chutar**.
4. O jogo indicará se o número secreto é **maior** ou **menor** que o seu palpite.
5. Continue tentando até acertar!
6. Ao acertar, veja quantas tentativas você usou e clique em **Novo jogo** para jogar novamente.

---

## 🛠️ Tecnologias Utilizadas

- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML) — estrutura da página
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS) — estilos e layout responsivo
- [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) — lógica do jogo e interações
- [ResponsiveVoice.js](https://responsivevoice.org/) (via CDN) — leitura em voz alta das mensagens

---

## 📂 Estrutura do Projeto

```
jogo-numero-secreto/
│
├── index.html   # Interface principal do jogo
├── style.css    # Estilos e layout responsivo
├── app.js       # Lógica do jogo e interações
└── img/         # Imagens utilizadas no projeto
```

> **Observação:** o intervalo máximo do número secreto é configurado em `app.js` pela variável `numeroMaximo = 500`. Para alterar a dificuldade, basta modificar esse valor.

---

## 👤 Autor

Desenvolvido como projeto de estudo de JavaScript interativo.

| [<img src="https://github.com/ghost.png" width=80><br><sub>Filipe Madeira Aqui</sub>](https://github.com/FilipeMadeira13) |
|:---:|

> Sinta-se à vontade para abrir uma *issue* ou entrar em contato pelo GitHub!
