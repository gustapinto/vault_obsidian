No desenvolvimento de software existem dois tipos diferentes de duplicação de código:[^1]  
- Duplicação real/verdadeira: Ocorre quando toda alteração em uma instância acarreta na mudança obrigatória de todas as suas duplicatas;  
- Duplicação acidental/falsa: Diferente da duplicação real a duplicação acidental ocorre quando dois artefatos de código aparentemente duplicados na realidade realizam duas funcionalidades diferentes, não tendo que mudar juntas e com o código evoluindo de maneira distinta ao longo do tempo.  

É importante saber identificar e diferenciar cada tipo de duplicação, pois se tratarmos uma duplicação acidental como verdadeira se tornará difícil separar a falsa duplicata da instância original no futuro.[^2] Enquanto que se não tratarmos uma duplicação verdadeira corremos o risco da mesma se tornar cada vez mais complexa, não respeitando o SRP[^3] ou DRY.   

[^1]: Arquitetura limpa, página 154  
[^2]: Arquitetura limpa, página 155  
[^3]: [[202110241952 | Principio da responsabilidade única]]  

