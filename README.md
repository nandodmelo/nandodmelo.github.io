# nandodmelo.github.io
Creating RL algorithms from scratch for portfolio optimization

Modelos de Q-Learning buscam aproximar o problema através de uma tabela (Q-Table), que aproxima a recompensa para o par ação ( $a$ )/estado( $s$ ).
Porém quando temos um espaço de possibilidades muito grande, isso se torna uma problema. Quando olhamos uma tarefa razoavelmente simples, como jogar um jogo do Atari, temos mais possibilidades de estado x ação x recompensa, que o número de átomos no Universo [https://www.youtube.com/watch?v=zR11FLZ-O9M&t=2400s&ab_channel=LexFridman].

Uma das maneiras de contornar essa limitação, é aproximar nossa Q-table para uma Rede Neural:

![Schema](nandodmelo.github.io/SchemaDQN.png)
