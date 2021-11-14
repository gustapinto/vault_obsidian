Ao estabelecer limites de arquitetura devemos particionar o software em componentes e organizar esses componentes em duas grandes áreas - as regras de negócio (alto nível) e os plug-ins (baixo nível) - de forma que as classes e módulos de baixo nível dependam dos de alto nível, e nunca o oposto, mantendo um digrafo de dependências que trata o alto nível como fonte, ou seja, com as setas se afastando dela.[^1]  

[^1]: Arquitetura limpa, página 173  
