Para lidarmos com arquitetura baseada em eventos podemos usar o padrão de design Observer, que consiste em uma série de eventos, os observaveis, e uma lista de clientes, os observadores.[^1]
  
O criação de um observável é simples, pois eles são em suma vetores que contém callbacks (diretas ou por referência) que serão chamadas quando um determinado evento ocorrer na aplicação[^2]
  
Um problema desse padrão de design é o acoplamento, já que cada observador deverá sempre ser declarado junto ao seus observaveis. Esses defeitos são corrigidos pela arquitetura Publicar/Increver-se[^3]

A aquitetura de Publish/Subscribe generaliza o design de Observers, oferecendo um modelo onde temos publicadores e inscritos, que são conectados por meio de canais[^4]
  
Quando comparados a Observers essa arquitetura reduz o acoplamento a partir de uma implementação com maior nível de abstração usando os canais como interfaces compartilhadas para passarem mensagens (eventos) a frente[^5]

[^1]: Pragmatic Programmer: Your journey to mastery, David Thomas e Andrew Hunt 225  
[^2]: Pragmatic Programmer: Your journey to mastery, David Thomas e Andrew Hunt 226
[^3]: Pragmatic Programmer: Your journey to mastery, David Thomas e Andrew Hunt 226
[^4]: Pragmatic Programmer: Your journey to mastery, David Thomas e Andrew Hunt 227
[^5]: Pragmatic Programmer: Your journey to mastery, David Thomas e Andrew Hunt 227

#desenvolvimento 