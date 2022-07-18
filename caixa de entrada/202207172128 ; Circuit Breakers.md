Circuit breaker é o padrão de estabilidade que consiste em encapsular operações "perigosas" em componentes que conseguem encerrar suas execuções caso algo saia fora dos parâmetros considerados seguros ou esperados para a operação[^1]

Para que eles sejam bem implementados é preciso que o Circuit breaker analise a densidade das falhas (falhas por espaço de tempo) e não apenas a quantidade total de erros disparados, pois cinco falhas em cinco minutos são muito mais preocupantes do que cinco falhas em cinco horas[^2]

[1]: Release It! Páginas 95 e 96  
[2]: Release It! Página 97
