Design por contrato é uma técnica de gerenciamento de software que prega a construção desse a partir de funcionalidades, direitos e responsabilidades definidos entre o cliente e a equipe de desenvolvimento.

Essa técnica prevê o desenvolvimento de software baseado em rotinas (contratos) e que uma delas não falhará, e se falhar o fará rápido e com uma boa mensagem de Exceção.

Os contratos são construídos seguindo o padrão:
1.  Pré condições
    São as condições que devem estar corretas para que a rotina prossiga, como sempre passar bons dados para a rotina consumir.

2.  Pós condições
    São os estados de execução que garantem que uma rotina terá fim.

Algumas linguagens de programação dão suporte nativo ao esquema de pré e pós condições, como Clojure e Elixir.
>   Será que esse suporte provém por serem linguagens funcionais ?
>   PS. Sim, esse suporte está intimamente ligado as linguagens funcionais (revelado pelos autores alguns parágrafos a frente)

Esse conceito pode também ser aplicado a partir de código "preguiçoso", ou seja, em Funções que aceitem poucas entradas, validando-as e retornando poucas coisas.

---
Pragmatic programmer: your journey to mastery, tópico 23, David Thomas e Andrew Hunt