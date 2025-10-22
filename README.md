📊 Análise de Vendas

Este projeto realiza uma análise exploratória de dados (EDA) sobre um conjunto de vendas, utilizando Python e bibliotecas de visualização. O objetivo é compreender o comportamento das vendas, clientes, produtos e faturamento, além de gerar insights relevantes para decisões estratégicas.

🚀 Tecnologias Utilizadas

Python 3.13

Pandas – Manipulação e limpeza de dados

Matplotlib e Seaborn – Visualizações gráficas

Google Colab – Ambiente de execução e integração com Google Drive

📁 Estrutura do Projeto
Etapa	Descrição
1. Importações	Importação das bibliotecas essenciais.
2. Montagem do Drive	Conexão com o Google Drive para acessar os dados.
3. Leitura dos Dados	Leitura do arquivo data.csv contendo o histórico de vendas.
4. Limpeza e Tratamento	Conversão de tipos de dados, remoção de duplicatas e preenchimento de valores ausentes.
5. Criação de Colunas	Criação da coluna Faturamento (Quantity * UnitPrice).
6. Análise Exploratória	Visualização de distribuições, tendências e correlações entre variáveis.
   
🧹 Etapas de Limpeza e Transformação

Conversão da coluna InvoiceDate para formato datetime

Conversão de CustomerID para string

Remoção de duplicatas

Preenchimento de valores nulos em Description com 'Desconhecido'

Criação da métrica Faturamento

📈 Exemplos de Análises e Visualizações

Volume de vendas por país, produto e cliente

Distribuição de preços e quantidades

Análise temporal das vendas

Identificação de produtos mais vendidos e clientes mais lucrativos

(As visualizações são geradas com matplotlib.pyplot e seaborn.)

🧠 Possíveis Extensões

Criação de dashboard interativo no Power BI

Integração com SQL para consultas dinâmicas

Cálculo de KPIs (faturamento total, ticket médio, margem, etc.)

Geração de DRE automatizada com base nas vendas


📄 Autor

Thaysse Macedo
Profissional da área de Análise de Dados e estudante de Análise e Desenvolvimento de Sistemas.

📄 Fonte de dados
https://www.kaggle.com/datasets/carrie1/ecommerce-data
