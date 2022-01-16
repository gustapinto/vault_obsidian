Ao extrairmos dados de um banco de dados, principalmente de bancos relacionais, temos duas grandes estratégias de ingestão:  
- Extração completa - é o modelo mais simples, e envolve retirarmos todos os dados e uma tabela a cada trabalho de extração, tornando-a mais ideial com bancos de dados e tabelas menores, já que com um maior volume de dados esse processamento se torna lento e custoso. ex: `SELECT * FROM extracted_data;` [^1]  
- Extração incremental - envolve apenas extrairmos os dados que foram modificados após o último trabalho de extração, esse método é o mais indicado quando estamos lidando com volumes maiores de dados, pois agiliza o processamento e evita o retrabalho de processamento de dados que já foram ingeridos anteriormente. Quando estamos lidando com volumes realmente massivos de dados o mais ideal é manter as informações da última execução em uma tabela menor, que servirá como "indice"[^3] ex: `SELECT * FROM extracted_data WHERE updated_at >= last_execution_job` [^2]  

[^1]: Data pipelines, página 41  
[^2]: Data pipelines, página 42  
[^3]: Data pipelines, página 43  