# Jogo da Memória

Este é um jogo da memória temático da série The Boys desenvolvido em HTML, CSS e JavaScript. O jogo consiste em encontrar pares de cartas idênticas em um conjunto embaralhado.

## Funcionalidades

- **Login:** Antes de começar a jogar, o jogador precisa inserir um nome no campo de login. O botão de jogar só fica habilitado quando o nome tem mais de 3 caracteres.

- **Jogo:** Após o login, o jogador é redirecionado para a página do jogo. O tempo começa a contar a partir de 40 segundos. O jogador precisa encontrar todos os pares de cartas idênticas antes que o tempo acabe.

- **Cartas:** As cartas são exibidas viradas para baixo. Ao clicar em uma carta, ela vira para cima, revelando seu conteúdo. Se duas cartas viradas para cima forem iguais, elas permanecem viradas para cima. Caso contrário, elas são viradas para baixo novamente.

- **Fim do jogo:** O jogo termina quando todas as cartas forem encontradas e viradas para cima ou quando o tempo acabar. Um alerta é exibido ao jogador informando o resultado.

## Estrutura de Arquivos

O projeto está estruturado da seguinte forma:

- **index.html:** Página inicial com o formulário de login.
- **pages/game.html:** Página do jogo.
- **src/login.js:** Script em JavaScript responsável pelo login.
- **src/game.js:** Script em JavaScript responsável pela lógica do jogo.
- **styles/:** Pasta contendo os arquivos CSS para estilização.
- **img/:** Pasta contendo as imagens utilizadas no jogo.

## Como Jogar

1. Abra o arquivo `index.html` no seu navegador ou acesse o link do projeto hospedado.
2. Insira seu nome no campo de login.
3. Clique no botão "Play" para começar o jogo.
4. Encontre todos os pares de cartas idênticas antes que o tempo acabe.
5. Ao final do jogo, um alerta informará se você venceu ou perdeu.

Divirta-se jogando o Jogo da Memória! 🃏🧠
