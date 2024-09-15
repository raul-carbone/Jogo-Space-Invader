# Space Invader Game 
Este é um jogo simples de tiro no estilo **Space Invaders**, desenvolvido em **Python** usando a biblioteca **Pygame**. O objetivo do jogo é controlar uma nave espacial, destruir os inimigos e evitar que eles atinjam a parte inferior da tela.

## Pré-requisitos 
Antes de começar, você precisa ter o **Python** instalado, bem como as seguintes dependências: 
1. **Python 3.x**: Se ainda não o tem, baixe-o [aqui](https://www.python.org/downloads/). 
2. **Pygame**: Para instalar o Pygame, execute o seguinte comando: `pip install pygame`

## Instalação

1.  Clone este repositório ou faça o download do código-fonte:
		`git clone https://github.com/seu-usuario/space-invader-game.git` 

2.  Navegue até a pasta do projeto:
`cd space-invader-game` 

3.  Certifique-se de que todas as imagens e sons necessários estão na mesma pasta que o script principal. O código espera os seguintes arquivos:
    
    -   `background.png` (Imagem de fundo do jogo)
    -   `ufo.png` (Ícone da janela do jogo)
    -   `player.png` (Imagem da nave do jogador)
    -   `enemy.png` (Imagem do inimigo)
    -   `bullet.png` (Imagem da bala)
    -   `background.wav` (Som de fundo)
    -   `laser.wav` (Som do disparo da bala)
    -   `explosion.wav` (Som da explosão)
4.  Execute o jogo:
`python main.py`

## Como Jogar

-   Mova a nave com as teclas **esquerda** (`←`) e **direita** (`→`).
-   Atire nos inimigos pressionando a **barra de espaço** (`SPACE`).
-   O jogo termina quando um inimigo atinge a parte inferior da tela (cerca de Y = 440).

## Estrutura do Código

O código principal segue a seguinte estrutura:

1.  **Importações**: Importa as bibliotecas necessárias, como `pygame`, `random` e `math`.
2.  **Inicialização do Pygame**: Cria a tela, carrega imagens e sons.
3.  **Jogador**: A nave controlada pelo jogador.
4.  **Inimigos**: Vários inimigos se movendo na tela com velocidade e posições iniciais aleatórias.
5.  **Bala**: O jogador pode atirar balas que se movem para cima.
6.  **Colisões**: Verifica se uma bala atingiu um inimigo.
7.  **Pontuação**: Exibe a pontuação atual do jogador.
8.  **Game Over**: Exibe a mensagem de "GAME OVER" quando um inimigo atinge a área inferior da tela.
