# power_bi_analyst

Repositório relacionado a formação de Power BI Analyst

Atividade 3:
Após a integração do banco de dados com o Power BI, foi realizada a verificação de cabeçalhos e dos tipos de dados;
Transformei os dados monetários para o tipo "decimal fixo";
Em seguida, verifiquei se haviam valores nulos nas tabelas "employee" e "departament" e os substituí por valores válidos;
Mesclei a tabela employee com a departament a fim de associar o nome do departamento aos colaboradores, os colaboradores com o gerente;
Realizei a mescla de colunas para unir as colunas de nome e sobrenome, e também o nome do departamento com a sua localização;
Agrupei os dados de forma que pudesse visualizar quantos colaboradores existem por gerente;
Por fim, excluí as colunas desnecessárias.



STAR SCHEMA FINANCIAL:

Diagrama Star schema construido através da sample Financial;
À partir dela foram divididos em diferentes tabelas informaçãoes sobre produtos, vendas, descontos, detalhes do produto e data;
Para definir os relacionamentos foi necessário criar colunas "ID", além disso, a tabela calendário foi criada utilizando DAX.

