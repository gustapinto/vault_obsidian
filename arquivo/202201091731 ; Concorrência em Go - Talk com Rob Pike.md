- Concorrência é uma das melhores formas de aproximar o comportamento de um software do mundo real
- Go usa *channels* para comunicação entre as goroutines concorrentes
- Goroutines são estritamente assíncronas
- Goroutines são gerneciadas internamente pela linguagem a partir de uma pilha
- Operações de atribuição `c <- 1` e uso `<-c` de channels são fases síncronas e bloqueantes por padrão, podendo então ser usados por multiplas goroutines sem o risco de condições de corrida ocorrerem
- Em goroutines temos o padrão de generators, que são funções que retornam channels, elas são normalmente usadas como handlers ou serviçoes dentro de um processo maior
- Em goroutines as operações de `select` atuam como uma forma de estrutura de controle usando channels e fazendo *"match"* com o channel que retornar resultados primeiro

[# Google I/O 2012 - Go Concurrency Patterns](https://www.youtube.com/watch?v=f6kdp27TYZs)