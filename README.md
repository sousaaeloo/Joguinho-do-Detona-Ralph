# Jogo "Detona Ralph" - Whack-a-Mole Style

Este projeto é um jogo simples inspirado no clássico "Whack-a-Mole", onde o jogador precisa clicar nos inimigos que aparecem aleatoriamente em uma grade de quadrados para marcar pontos. O jogo é baseado no filme "Detona Ralph" e usa imagens e sons temáticos.

## Índice
<ul>
<li>Descrição<li>
Estrutura do Projeto
<li>Funcionalidades
<li>Como Jogar
<li>Tecnologias Utilizadas
<ul><br>

## Descrição

Neste jogo, o jogador precisa clicar rapidamente em um inimigo, o Ralph, que aparece aleatoriamente em uma grade de 3x3 quadrados. O jogo tem um cronômetro que começa em 60 segundos, e o objetivo é fazer o máximo de pontos possível antes que o tempo acabe.

## Estrutura do Projeto
O projeto está organizado da seguinte forma:

/
|-- index.html
|-- styles/
|   |-- reset.css
|   |-- main.css
|-- script/
|   |-- engine.js
|-- image/
|   |-- player.png
|   |-- ralph.png
|-- audios/
|   |-- hit.m4a

## Arquivos principais:
- index.html: Contém a estrutura principal da página.

- main.css: Estilos da interface do jogo.
- engine.js: Script que controla a lógica do jogo (exibição de inimigos, cronômetro e pontuação).

## Funcionalidades
- Tempo Limite: O jogador tem 60 segundos para acumular o maior número de pontos.

- Pontuação: A pontuação aumenta ao acertar o inimigo Ralph.
Inimigos Aleatórios: O Ralph aparece aleatoriamente em diferentes quadrados na grade.

- Som de Efeito: Um efeito sonoro é reproduzido ao acertar o inimigo.

- Vida do Jogador: Exibição de 3 vidas iniciais no cabeçalho (não implementada completamente no código).

## Como Jogar

- Início do Jogo: O jogo começa automaticamente assim que a página é carregada.

- Objetivo: Clique no Ralph (inimigo) sempre que ele aparecer em um dos quadrados.

- Fim de Jogo: Quando o cronômetro chegar a zero, o jogo termina e sua pontuação final é exibida.

## Tecnologias Utilizadas

- HTML5: Estrutura do jogo.

- CSS3: Estilos visuais, incluindo o uso de Flexbox para layout.

- JavaScript: Manipulação da DOM e lógica do jogo.

- Google Fonts: Utilização da fonte "Press Start 2P" para um estilo retrô.

- Imagens e Áudio: Utilização de imagens e som para tornar o jogo mais dinâmico e imersivo.

## Melhorias Futuras
- Implementar sistema de vidas para o jogador.

- Adicionar níveis de dificuldade.

- Melhorar a responsividade para dispositivos móveis.

- Adicionar uma tela inicial e final de jogo.
