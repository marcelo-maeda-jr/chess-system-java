# Chess System Java
<p>Sistema de jogo de xadrez, projeto desenvolvido em Java, no curso <a href="#">Java COMPLETO Programação Orientada a Objetos + Projetos.</a></p>

## Sobre
O projeto consiste em um jogo de xadrez simples, onde os jogadores podem realizar os movimentos do jogo fornecendo as coordenadas de origem e destino. O objetivo do jogo é capturar o Rei do jogador adversário.

## Como jogar?
Para jogar é necessario ter instalado o [Git](https://git-scm.com) em sua máquina.

Para executar o jogo, abra o Git Bash na pasta bin do projeto e digite o comando `java application/Program`.

Os jogo começa sempre pelas peças brancas. Cada jogador tem seu turno, e em cada turno o jogador deve escolher uma de suas peças e movimenta-las para uma posição válida.

### Movimentando as peças
Durante o seu turno, o jogador é livre para escolher qualquer uma de suas peças livres, desde que ela possa realizar um movimento. O jogador indica qual peça ele deseja movimentar informando uma coordenada de origem (Source), após escolher, será indicado quais os movimentos possíveis da peça escolhida. O jogador então informa uma das coordenadas de destino (Target).

### Capturando as peças
Para capturar uma peça do adversário. O jogador deve movimentar sua peças para a posição onde se encontra a peça do adversário.

### Peças
#### Peão [P]
O Peão se move andando para frente, sempre na mesma coluna, nunca andando para trás. Quando alcança a última fileira, o peão é promovido, podendo o jogador escolher a que peça o peão será promovido (Torre, Cavalo, Bispo, Rainha). Em seu primeiro movimento,cada peão pode avançar duas casas. O movimento de captura do peão é realizado na diagonal. Caso haja uma peça em frente ao peão, ele fica impossibilitado de se movimentar.

#### Torre [R]
A Torre se move percorrendo o tabuleiro em movimentos horizontais e verticais. Podendo se movimentar quantas casas quiser, porém em apenas um sentido por jogada.

#### Cavalo [N]
O Cavalo se movimenta em "L". Duas casas na vertical/horizontal e depois uma na horizontal/vertical. O cavalo é a única peça que pode se movimentar sobre outras peças, seja sua ou do adversário.

#### Bispo [B]
O Bispo se move percorrendo o tabuleiro em direções diagonais. Podendo se movimentar quantas casas quiser.

#### Rainha ou Dama [Q]
A Rainha pode se mover em todas as direções, horizontais, verticais ou diagonais. Podendo se movimentar quantas casas quiser, poré em apenas uma direção por jogada.

#### Rei [K]
O Rei pode se mover em todas as direções, porém uma casa por vez. O rei nunca pode se mover para uma posição o coloque sobre risco (Xeque).

### Fim de jogo
O joga acaba quando um dos jogadores captura o Rei adversário.

## Tecnologia Utilizada
- Java
  - Estrutura sequencial
  - Estrutura condicional
  - Estruturas repetitivas
  - Programação orientada à objetos
    - Encapsulação / Modificadores de acesso
    - Construtures
    - Associação
    - Enumeração
    - Herança
    - Polimorfismo
    - Método toString
    - Sobrecarga
    - Sobrescrita
    - Downcasting
    - Membros Estáticos
    - Exceções / Tratamento de Exceções Personalizadas
    - Métodos e Classes abstrato
  - Estrutura de dados
    - Lista
    - Matriz
