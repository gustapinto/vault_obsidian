No desenvolvimento de software Atores são linhasde processamento virtuais, independentes, possuindo estados privados, esses atores são ativados e iniciam seu processamento ao receberem mensagens (interações externas), com cada ator podendo iniciar novos atores para realizarem o processamento dessa mensagem. [^1]

Segundo Thomas e Hunt existem muitas informações sobre os atores que normalmente não são descritas em suas definições formais, como:[^2]
1. Os atores não gerenciam, nem orquestram, nenhum fluxo de dados da tarefa que estão realizando, necessitando de meios externos para tais;
2. Os estados dos atores são totalmente dependentes das mensagens que eles recebem;
3. Todas as mensagens sãounidirecionais, com os atores não replicando ou respondendo diretamente as mensagens que recebem;
4. Um ator só processa uma mensagem por vez, sempre.

Os autores discutem também que uma arquitetura baseada em atores é a melhor maneira de se implementar processos concorrentes, já que a implementação de atores é relativamente simples, dependendo unicamente de um sistema de gerenciamento de mensagens (Message Broker).[^3]

[^1]: Pragmatic programmer, your journey to mastery, David Thomas e Andrew Hunt, página 285
[^2]: Pragmatic programmer,your journey to mastery, David Thomas e Andre Hunt, página 286
[^3]: Pragmatic programmer,your journey to mastery, David Thomas e Andre Hunt, página 292

#desenvolvimento 