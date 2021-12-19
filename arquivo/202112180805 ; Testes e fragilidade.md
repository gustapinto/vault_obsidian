Testes não devem depender de atributos frágeis e mutáveis do sistema, pois uma simples modificação neles podem atingir dezenas de testes, portanto é preciso projetar software de modo que as regras de negócio possam ser testadas independentemente de componentes altamente mutáveis.[^1]  

Uma maneira de lidar com a testagem de componentes mutáveis é a criação de uma PAI mockada específica para testes que permita ao desenvolvedor contornar detalhes como GUIs, bancos de dados e sistemas de autenticação.[^2]  

[^1]: Arquitetura limpa, página 251  
[^2]: Arquitetura limpa, página 252 