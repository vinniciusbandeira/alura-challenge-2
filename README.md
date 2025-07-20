Projeto ETL e Análise de Churn - Telecom X
Descrição
Este projeto tem como objetivo analisar a evasão de clientes (churn) da empresa Telecom X, utilizando dados reais fornecidos em formato JSON. A evasão de clientes é um desafio importante que impacta diretamente na receita e crescimento da empresa.
Por meio da extração, limpeza, tratamento e análise exploratória dos dados, buscamos identificar padrões e fatores que influenciam o cancelamento dos serviços. Além disso, foi realizada uma análise de correlação para explorar quais variáveis numéricas têm maior relação com a evasão.

Estrutura do Projeto
TelecomX_Data.json: arquivo com os dados originais dos clientes.
Projeto_ETL_Churn.ipynb: notebook com o código completo para importação, limpeza, análise e visualizações.
README.md: este arquivo com as informações sobre o projeto.

Passos Realizados
Importação dos Dados: Dados foram carregados a partir do arquivo JSON fornecido pela Telecom X.
Limpeza e Tratamento:
Identificação e tratamento de valores nulos, especialmente na coluna Cobranca_Total, que teve valores nulos substituídos pela média da coluna.
Conversão das colunas numéricas para o tipo correto.
Renomeação das colunas para facilitar manipulação.
Criação da variável Qtd_Servicos para contar a quantidade de serviços contratados por cliente.

Análise Exploratória de Dados:
Visualização da distribuição dos clientes que cancelaram versus os que permaneceram ativos.
Análise da variável Cobranca_Total segmentada por churn, com gráficos boxplot e histogramas.
Exploração dos valores únicos das variáveis categóricas para identificar inconsistências.

Análise de Correlação:
Conversão da variável Churn para numérica para facilitar análise.
Cálculo da correlação entre as variáveis numéricas e o churn, destacando aquelas com maior influência.
Visualização da matriz de correlação com heatmap para facilitar a interpretação.

Conclusões e Recomendações:
Clientes com cobrança total mais alta tendem a apresentar maior risco de churn.
A quantidade de serviços contratados e características demográficas também influenciam o comportamento de cancelamento.
Recomenda-se investir em programas de retenção focados em clientes com perfil de risco, revisar pacotes de serviços, e aprimorar a coleta dos dados para futuras análises.

Resultados
Identificamos padrões claros entre a cobrança total dos clientes e a evasão, com valores mais elevados associados a maior churn.
A análise de serviços contratados mostrou que clientes com menos serviços têm maior propensão a cancelar.
As variáveis demográficas, como gênero e tempo de contrato, também apresentaram impacto significativo.
O relatório final traz recomendações estratégicas para mitigar a evasão, focando em retenção e melhoria da oferta de serviços.
