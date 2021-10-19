É uma estratégia para lidar e gravar dados nos quais as operações e transações são salvas mas o estado final não, e quando esse estado for solicitado apenas retornamos o "somatório" de todas as operações, mantendo assim um abiente CR (*Create* e *Read*), perpetuando um estado de imutabilidade generalizada, onde não há a necessidade de espaços transacionais[^1] para lidarmos com a mutabilidade de um estado final. [^2]  

[^1]: [[202110191854 ; Mutabilidade em programação funcional]]  
[^2]:  Arquitetura limpa, página 55  