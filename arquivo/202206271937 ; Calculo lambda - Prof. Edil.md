# Tipos de programação de computadores

## Programação imperativa
- Se baseia na mudança de estados de uma máquina pela manipulação direta de seu registro de memória
- É muito ligada a operação das máquinas de Turing


## Programação funcional
- Raramente manipula memória, evitando efeitos colaterais
- Baseada no cálculo $\lambda$


# Cálculo $\lambda$

## Sintaxe do cálculo $\lambda$
A sintaxe do cálculo $\lambda$ é composta por:
- Variáveis, que são nomes
- Abstração $\lambda$, que é qualquer termo $\lambda x.M$ (parâmetro forma)
- Aplicação, que é qualquer termo $M N$ (argumento)


### Relação com funções
O cálculo de $\lambda$ é análogo a funções, tal que uma abstração $\lambda$ é na verdade uma função anônima, isso é, uma função onde não há a "declaração" de domínio ($f(x)$, $g(x)$, etc...):
- $\lambda x.10x \equiv f(x)=10x$


## Semantica do cálculo $\lambda$
### Conversão $\alpha$
É o ato de "renomear" uma variável para evitar confusão e conflito de termos
- $\lambda x.M[x] \to \lambda y.M[y]$

### Redução $\beta$
É o ato de substituir todas as ocorrências de $x$ pela expressão $e$
- $(\lambda x.x)f = f$
- $\lambda x(f1 x)(\lambda z.z) = f1(\lambda z.z)$

#### Forma normal
É uma expressão $\lambda$ onde não se pode mais fazer redução $\beta$


## Transparência referencial
É o fato de cada abstração $\lambda$ possuir apenas uma parâmetro e uma saída, onde a saíde de $\lambda$ só dependende da entrada, com o mesmo conjunto de entradas levando sempre ao mesmo conjunto de saídas


## Aplicação $\lambda$ em lógica booleana
- If: $\lambda b\space x\space y \to b\space x\space y$
- True: $\lambda x\space y \to x$
- False: $\lambda x\space y \to y$

### Exemplos
#### If True a b
$(\lambda b\space x\space y.b\space x\space y)True\space a\space b$
$(\lambda x\space y.True\space x\space y)\space a\space b$
$(\lambda x\space y.(\lambda p\lambda q.p)\space x\space y)\space a\space b$
$(\lambda x\space y.x)\space a\space b$
$a$

#### If False a b
$(\lambda b\space x\space y.b\space x\space y)False\space a\space b$
$(\lambda x\space y.False\space x\space y)\space a\space b$
$(\lambda x\space y.(\lambda p\lambda q.q)\space x\space y)\space a\space b$
$(\lambda x\space y.y)\space a\space b$
$b$
---
#funcional 
