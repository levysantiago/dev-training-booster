1. Para um jogo, precisamos saber se um personagem morreu ou não depois de 
sofrer um ataque. Faça uma função que receba 2 parâmetros, 'dano' e 'saude'. 
A função deve retornar '1' se o dano for matar o personagem (ou seja, deixar 
sua saúde menor ou igual a zero) e '0' caso contrário.

2. Precisamos limitar as posições em que um inimigo pode andar na tela. 
A menor posição possível é 0 e a maior, 100: qualquer valor maior que 100 ou 
menor que 0 sairia fora da tela. Precisamos de uma função LimitaPosicao que 
recebe uma POSICAO que pode ter qualquer valor positivo ou negativo, verifica 
se ela é válida ou não e retorna sempre um valor corrigido entre 0 e 100.

3. Escreva uma função em JavaScript que realize a conversão de uma temperatura fornecida em graus Fahrenheit (F) para Celsius (C).
`Dica: para converter uma temperatura em F para C, subtraia 32 da temperatura e multiplique o resultado por 0,5556 (ou 5/9).`

4. Escreva uma função que receba como parâmetro o ano em que a pessoa nasceu.
Esta função deve calcular a idade da pessoa e depois retornar a idade calculada.
Execute esta função e imprima a idade na tela como o exemplo: `"Sua idade é: 25 anos"`.

5. No jogo fotnite o jogador deve ficar dentro da área segura que é um domo que
vai diminuindo de tamanho com o tempo. Dependendo de onde o jogador esteja, caso
sua posição esteja fora do domo, ele é eliminado da partida, caso ele ainda esteja dentro do domo, ele ainda está vivo. Faça uma função que receba três entradas, `inicioDomo`,
`fimDomo` e `posicaoJogador`. Sendo que todas essas entradas são números inteiros.
Caso a posicao do jogador seja maior do que o fim do domo ou menor do que o início
do domo, a função deve retornar `"Você foi eliminado"`. Caso a posição do jogador 
esteja entre o início e o fim do domo, a função deve retornar `"Você ainda está na partida"`.