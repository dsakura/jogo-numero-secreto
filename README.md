# 🎮 Jogo do Número Secreto

![Badge de Status](https://img.shields.io/badge/status-conclu%C3%ADdo-green)

Um jogo simples e interativo para adivinhar um número secreto, desenvolvido com tecnologias web front-end básicas. O projeto foi criado como parte da Imersão DevOps da Alura.

![Uma captura de tela da interface do jogo, mostrando o título "Jogo do Número Secreto", um campo para inserir um número e os botões "Chutar" e "Novo Jogo"](./img/ia.png) 
> **Nota:** Você pode substituir a imagem acima por uma captura de tela real do seu jogo!

## 🚀 Como Jogar

1.  Abra o arquivo `index.html` em qualquer navegador web moderno.
2.  A página exibirá a mensagem "Escolha um número entre 1 e 10".
3.  Digite seu palpite no campo de entrada e clique no botão **"Chutar"**.
4.  Você receberá uma dica por texto e voz, informando se o número secreto é maior ou menor que o seu chute.
5.  Continue chutando até acertar!
6.  Ao acertar, o jogo exibirá uma mensagem de parabéns e habilitará o botão **"Novo jogo"** para você começar uma nova partida.

## ✨ Funcionalidades

-   **Interface Intuitiva:** Design limpo e simples, focado na experiência do jogador.
-   **Feedback por Voz:** Utiliza a API ResponsiveVoice.js para ler as instruções e dicas em voz alta (em Português do Brasil).
-   **Lógica de Jogo Inteligente:**
    -   O sistema não repete um número secreto até que todos os números possíveis (de 1 a 10) tenham sido sorteados.
    -   Contador de tentativas para acompanhar seu desempenho.
-   **Responsividade:** O layout se adapta a diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando as seguintes tecnologias:

-   **HTML5:** Para a estrutura semântica da página.
-   **CSS3:** Para estilização, gradientes e layout responsivo.
-   **JavaScript (ES6+):** Para toda a lógica do jogo, manipulação do DOM e interatividade.
-   **ResponsiveVoice.js:** Biblioteca externa para a funcionalidade de text-to-speech.
-   **Google Fonts:** Para a tipografia (`Chakra Petch` e `Inter`).

## 📂 Estrutura do Projeto
├── 📄 index.html # Arquivo principal da estrutura da página
├── 🎨 style.css # Folha de estilos
├── ⚙️ app.js # Lógica principal do jogo
├── 🖼️ img/ # Pasta com as imagens utilizadas
└── 📄 README.md # Este arquivo
