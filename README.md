# ⏳ Tratamento e Limpeza de dados de venda de produtos
Limpeza e organização de dados afim de estruturar uma base para análise. Tendo como principal objetivo o Cálculo RFM:
- R é a recência, diferença em dias da última compra do cliente e da última
compra disponível no conjunto de dados, que calcularam previamente.
- F é a frequência, ou seja, a quantidade de compras feitas pelo cliente;
- M é o ticket médio, ou seja, a média das compras feitas pelo cliente.

## 📖 Análise Descritiva 
Esta etapa consiste em explorar os dados do dataset para compreender melhor as variáveis e identificar problemas. Para isso, é foi utilizada a biblioteca Pandas para importar, manipular e realizar cálculos estatísticos com os dados, além das bibliotecas de visualização. Nesse caso em específico, todo esse processo gira em torno de pesquisar o mercado apontando os produtos que já existem hoje e seus diferenciais,  apresentando de forma clara os concorrentes diretos e indiretos, destacando seus diferenciais e pontos fortes. É importante sempre avaliar o dataset da forma que ele vem do cliente e fazer uma avaliação prévia nos dados, seja verificando se há valores faltantes, a presença de outliers ou até mesmo os tipos de variáveis (floats, strings e/ou inteiros).

## 📚 Análise Exploratória e Modelagem do Dados 
Depois de um pré tratamento dos dados, é importante visualizar a presença de valores que destoam da faixa de valores que existem dentro do dataset. Para isso, foi criado o gráfico de boxplot para enteder e visualizar esse aspecto:

![image](https://github.com/juanlucas7/Data_Cleaning_Wrangling/assets/149596266/a81ee40b-0556-40c5-ade1-624ebd40986e)

## 📊 Plotagem Gráfica:

De acordo com as orientações do cliente, foi solicitado a plotagem de: 

### Top 10 Países com Maior Valor em Vendas

![image](https://github.com/juanlucas7/Data_Cleaning_Wrangling/assets/149596266/54f0e971-b370-455c-9382-2c271a00fc47)


### Top 10 Produtos Mais Vendidos

![image](https://github.com/juanlucas7/Data_Cleaning_Wrangling/assets/149596266/9813b9a9-f586-4531-b9a2-a8d94d0174e5)


