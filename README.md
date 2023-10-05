# Resolvedor de expressões numéricas 
Um resolver de expressões numéricas (infixas e posfixas). O sistema tem suporte a modificação da representação da expressão numérica, assim como a possibilidade de solução automática da expressão.


## Ler Expressão Numérica: 
* Esta operação deve ler uma expressão numérica passada como argumento e armazenar essa expressão no programa. A expressão pode estar em notação infixa ou posfixa e o programa deve verificar se a expressão numérica é válida. Por exemplo, 3 + 4 é uma expressão válida, mas 2 + - x não é. E só deve armazenar a expressão se a mesma for válida 
## Converter para Notação Posfixa: 
* Esta operação deve converter a expressão armazenada no programa para a notação posfixa. Mais informações sobre a notação posfixa podem ser encontradas em https://pt.wikipedia.org/wiki/Notacão_polonesa_inversa
## Converter para Notação Infixa: 
* Esta operação deve converter a expressão armazenada no programa para a notação infixa com parênteses. Mais informações obre essa notação podem ser encontradas em https://pt.wikipedia.org/wiki/Notação_infixa
## Resolver Expressão: 
* Esta operação deve resolver a expressão armazenada e apresentar o valor numérico final correspondente a computação da expressão.


## Exemplo Entradas
* LER POSFIXA  7.325484  2.298093  2.321958  /  4.759999  *  * 
INFIXA
* Saída: RESOLVE # 34.510905
* LER INFIXA  ( ( ( ( 4.771053 ) / ( 8.509878 ) ) + ( ( 2.799444 ) - ( 6.606407 ) ) ) - ( ( 3.703479 ) / ( 6.146766 ) ) )
POSFIXA
* Saída: RESOLVE # -3.848823
* Ex: ./bin/main < entdouble.s11.n10.i.in

## Estrtura
*  |- src
*  |- bin
*  |- obj
*  |- include
*  Makefile

 ## Uso
 * make run
 * ./bin/main < file.in



