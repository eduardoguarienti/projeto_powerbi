# Análise Exploratória de Dados no Power BI

![Proj1](https://github.com/eduardoguarienti/projeto_powerbi/blob/main/proj_powerbi1.png)

***

### Projeto

- [Acesse a análise](https://app.powerbi.com/view?r=eyJrIjoiZTYxNTU1ZmUtOGMyMy00NWYyLTk1Y2MtZjNiMTRiYjE4YWJjIiwidCI6IjBiYzA2NzRiLWZmMWEtNDVkZC05ZThiLTg5NTIwZGUzMzMxYSJ9&pageName=52d3a55840e8fff3227b)

Em meu projeto de Power BI, procurei entender como as variáveis-chave do negócio se relacionavam, além de buscar a melhor visualização e interatividade possível para os diferentes dashboards, tentando encontrar o equilíbrio entre riqueza de informações e clareza, usando diferentes tipos de gráficos e tabelas. Também fiz uso de várias medidas DAX para entender de forma sintética a performance do negócio, como margens, quantidade de clientes e vendas totais.

### Medidas utilizadas
- `M Avg Sales per Transaction = [M: Total Sales]/ DISTINCTCOUNT('Sample - Superstore'[Order ID])`
- `M Customer Count = DISTINCTCOUNT('Sample - Superstore'[Customer ID])`
- `M Profit Margin = DIVIDE([M Total Profits],[M: Total Sales])`
- `M Total Profits = SUM('Sample - Superstore'[Profit])`
- `M Total Units Sold = SUM('Sample - Superstore'[Quantity])`
- `M Total Sales = SUM('Sample - Superstore'[Sales])`

***

### Dados utilizados

Utilizei os dados de um grande varejo estadunidense especializado diferentes gamas de produtos de escritório, que, dentre outras informações, continha ID do pedido, data do pedido, segmento e localização do cliente, além de informações sobre vendas e lucros.

- [Link do Kaggle do conjunto de dados utilizado](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final/code?datasetId=1940216&sortBy=voteCount)

***  

![Proj2](https://github.com/eduardoguarienti/projeto_powerbi/blob/main/proj_powerbi2.png)


***

- [Clique aqui para visualizar o projeto](https://app.powerbi.com/view?r=eyJrIjoiZTYxNTU1ZmUtOGMyMy00NWYyLTk1Y2MtZjNiMTRiYjE4YWJjIiwidCI6IjBiYzA2NzRiLWZmMWEtNDVkZC05ZThiLTg5NTIwZGUzMzMxYSJ9&pageName=52d3a55840e8fff3227b)
