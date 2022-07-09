# Base N para decimal
1. Seja $n$ o número de digitos no número (ex: 1011 $n=4$)
2. Seja $b$ a base númerica do número
3. Seja $s$ o número decimal, orginalmente 0
4. Para cada dígito $d$ do número, da esquerda para a direita faça:
	1. Subtraia 1 de $n$, de modo que $n = n -1$
	2. Multiplique o dígito por $b^n$, e some a $s$, de modo que $s=d*b^n$
5. $s$ será o valor decimal total após conversão

# Decimal para base N
1. Seja $n$ o número decimal
2. Seja $m$ o número convertido que está sendo composto, inicialmente vazio
3. Seja $b$ a base para qual o número será convertido
4. Repetir até que $n = 0$:
	1. Dividir $n/b$, onde o resultado será $d$ e o resto $r$
	2. Escreva $r$ como o número mais a esquerda de $m$ (inserir a frente dos demais números de $m$)
	3. $d$ será o novo valor de $n$
5. $m$ será o valor convertido de decimal para a base $b$

