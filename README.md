# Capivara's Adventure

É um jogo no estilo side-scroller, ou seja, no mesmo estilo do flappy bird, onde é um jogo no qual a jogabilidade é vista do ângulo da câmera de visão lateral e, à medida que o personagem do jogador se move para a esquerda ou para a direita, a tela rola com ele.
Nele você joga com uma capiva e não pode deixá-lo bater nos objetos que aparecem de maneira aleatória no mapa.

## Telas

Na tela inicial, temos dois botões, o de início para começar o jogo e o de sair para deixar o jogo, além disso temos o gif da capivara que é o personagem que o jogador controla andando junto com o nome do jogo.

Na tela do jogo temos um cenário que se move enquanto a medida que a capivara avança no mapa.

## Jogabilidade

A capivara inicia o jogo com uma velocidade de 10.0 pixels e cresce a medida que vai avançando até chegar a velocidade máxima de 25 pixels. Além disso os obstáculos que são uma estrela do mar, um barril quebrado e um castelo de areia que vem de baixo e são estáticos, e um passarinho que pode vem por cima e se movendo junto ao mapa.

### Os obstáculos

1. Obstáculos estáticos
   Os obstáculos estáticos aparecem sempre a mesma distância um do outro, e é moficado a quantidade de obstáculos de acordo com o nível de dificuldade do jogo, ou seja, chegando até 3 obstáculos.
2. Pássarinho
   O passarinho começa a aparecer quando o jogador chega no último nível de dificulade, podendo aparecer em diferentes posições y e aparecendo se forma aleatória.
## Score

A pontuação cresce conforme a dificuldade do jogo aumenta, onde ele começa adicionando 10 por milisegundo dividido por 5000 e termina adicionado 25 por milisegundo dividido por 5000. Além disso, conforme você vai jogando o jogo marca a sua maior pontuação durante a jogatina no high socre.
