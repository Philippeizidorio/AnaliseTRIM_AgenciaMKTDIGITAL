# Dashboard No Power BI: Análise De Campanhas Para Traçar Planos De Ação - Agência De Marketing Digital
![Alt ou título da imagem](https://github.com/Philippeizidorio/Dashboard_PowerBIMarketing/assets/145637595/32d3174e-fdfb-40b2-ac0d-4367e8b308c9)
### ◾Contexto: 

A empresa de Marketing Digital "X" precisa atingir uma meta ambiciosa neste
trimestre e precisa identificar os melhores planos de ação para alcançá-la. Para
isso, ela precisa de um dashboard gerencial no Power BI que permita acompanhar os
principais indicadores de desempenho. Com esses dados, a equipe poderá avaliar a situação 
atual de cada campanha, identificar oportunidades de otimização e escolher
os melhores planos de ação com o objetivo de aumentar o número de usuários cadastrados 
e impulsionar o crescimento da empresa. O dashboard será uma ferramenta essencial para 
a tomada de decisão mais informada e estratégica.

### ◾Análise Exploratória De Dados(AED): 

Após ter coletado os dados da base em .CSV, foi feita uma análise exploratória a fim de realizarmos certos tratamentos, removendo erros, outliers além de trabalharmos no entendimento dos dados, identificação de tendências e extração de insights. 

### ◾Requisitos de dados: 

- **Data do período analisado:** [Data do período p/análise temporal]
- **Receita total:** [Receita total da data]
- **Soma da Receita média por compra:** [Soma da Receita média na data]
- **Total de compradores:** [Quantidade de compradores na data]
- **Visualizações:** [Quantidade de visualizações na data]
- **Compradores por dia:** [Quantidade de compradores no dia]
- **Compradores por origem:** [Quantidade de compradores por origem]
- **Usuários totais por plataforma:** [Quantidade de usuários na plataforma]
- **Usuários totais por cidade:** [Quantidade de usuários na plataforma por cidade]
- **Usuários ativos por gênero:** [Quantidade de compradores por gênero]
- **Percentual de Visualização:** [% de visualização em relação a quant. de usuários ativos]

### ◾Extract,Transform, And Load(ETL): 

Realizei a extração, manipulação, modelagem de dados no formato multidimensional e carregamento dos mesmos através da ferramenta Power Query do Power BI, sendo necessária a criação de novos índices de colunas e tabelas, posteriormente, trabalhei na união dessas com a tabela Fact por meio de suas respectivas Foreign Keys(FKs) além da adição de uma nova coluna calculada.

### ◾ Criação Do Dashboard:

Por fim, com todas as etapas anteriores plenamente definidas, é momento da criação do dashboard em sí, para isso, utilizei os seguintes gráficos e recursos do Power BI ↓

1. Filtro De Data;
2. Cards Únicos;
3. Gráfico Tipo Pizza;
4. Gráfico Tipo Barras;
5. Gráfico Tipo Linhas;
6. Botão para alternar entre as páginas;
7. Formatação visual;
8. Recursos de análise;
9. Por último e não menos importante: um bom storytelling. 

Você pode visualizar o resultado do Dashboard na web [**CLICANDO AQUI!**](https://app.powerbi.com/view?r=eyJrIjoiMWUzNTA4NTAtOWRhYy00NzBiLTk5YzUtYzU1N2FmNzM4OTM5IiwidCI6IjRhMTg3ZWI1LTNmM2UtNDViOS05ODZkLTI4ZTY3YzI4Njk1NiJ9) Ou acessando a demonstração do mesmo que está em formato .pdf logo acima nos arquivos deste repositório. 

### ◾ Através desse relatório, podemos analisar que no trimestre: 
1. Usuários oriundos das cidades de Brasília, Salvador e São Paulo representam a maior quantidade de compradores e receita média por compra;
3. Website é a plataforma que contém a maior quantidade de usuários ativos com mais de 5 milhões;
4. Website é a plataforma que trouxe maior parte do montante faturado no quarter em questão;
5. Brasília e São Paulo são as cidades que apresentam a maior média de entrada de novos usuários no período, possuindo grande tendência em trazer um _CAC(Custo de aquisição por cliente)_ menor;
6. O público do negócio é majoritariamente do sexo feminino;
7. A origem dos compradores se dá em grande parte das redes sociais, busca orgânica e anúncios pagos.

### ◾ Tecnologias Utilizadas: 
<div <br> 
<img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white">
<img src="https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white">
</div> 

## Autor:

<img  src="https://github.com/Philippeizidorio/AnaliseTRIM_AgenciaMKTDIGITAL/assets/145637595/9800ac43-2070-48d4-9002-dbf82f756f2c" width="80" alt="cognitiveclass.ai logo" align="left" /> 

### &nbsp;&nbsp;Philippe Izidório

<p>
&nbsp;&nbsp;Estudante De Ciência De Dados / Business Intelligence / Analista De Dados<br/>
&nbsp;&nbsp;LinkedIn: https://www.linkedin.com/in/philippeizidorio/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E-mail: euphilippeizidorio@gmail.com<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Portifólio de projetos em Data Science: https://github.com/Philippeizidorio
</p>
