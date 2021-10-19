No capitúlo 6 temos a segregação de mutabilidade, que se baseia em separar os componentes imutáveis dos mutáveis em uma arquitetura que faz uso de linguagens de programação funcionais. [^1]  
Nessa segregação os componentes que lidam com mutabilidade são tratados e executados em um espaço de memória transacional que lida com operações de criação, acesso e atualização de um estado da mesma forma que os discos, evitando assim *locks* e condições de corrida em abientes altamente concorrentes.  [^1]  

[^1]: Arquitetura limpa, páginas 52 e 53

#desenvolvimento #funcional 