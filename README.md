# 📊 Dashboard de Análise de Vendas no Varejo (Power BI)

Este projeto apresenta um **dashboard analítico desenvolvido em Power BI** para análise de desempenho de vendas, produtos e estoque em um cenário de varejo.

O objetivo do projeto é transformar dados brutos em **informações estratégicas para tomada de decisão**, permitindo visualizar tendências de vendas, desempenho das lojas e comportamento dos produtos.

Este dashboard foi desenvolvido como parte do meu **portfólio de Análise de Dados**.

---

# 🎯 Objetivos do Projeto

O dashboard foi criado para responder perguntas de negócio importantes, como:

* Qual é a receita total da empresa?
* Quais produtos vendem mais e menos?
* Qual loja apresenta melhor desempenho?
* Como as vendas evoluem ao longo do tempo?
* Como o estoque está distribuído entre os produtos?

---

# 📈 Insights Extraídos dos Dados

Durante a análise do conjunto de dados, alguns padrões importantes podem ser observados:

• Alguns produtos concentram grande parte do volume de vendas, indicando **possíveis produtos estratégicos para o negócio**.

• A comparação entre lojas permite identificar **diferenças de desempenho regional**, ajudando a entender onde existem oportunidades de crescimento.

• A análise temporal mostra **variações nas vendas ao longo dos dias**, permitindo detectar períodos de maior ou menor demanda.

• A distribuição de vendas por categoria ajuda a entender **quais segmentos possuem maior participação no faturamento**.

Esses insights são úteis para apoiar decisões como:

* Estratégias de estoque
* Planejamento de vendas
* Promoções e campanhas
* Otimização do portfólio de produtos

---

# 🧠 Estrutura do Dashboard

O relatório foi dividido em **três páginas analíticas principais**.

---

## 📈 Visão Geral de Vendas

Esta página apresenta os principais indicadores de desempenho comercial.

Principais métricas:

* Receita total
* Quantidade vendida
* Lucro do período

Visualizações incluídas:

* Receita por loja
* Tendência diária de vendas
* Comparação de desempenho entre lojas

<img width="1326" height="742" alt="image" src="https://github.com/user-attachments/assets/37cc65b7-10b6-4491-a1ee-4a588ef0e4a4" />


---

## 🛒 Análise de Produtos

Esta página analisa o desempenho individual dos produtos.

Indicadores principais:

* Total de produtos
* Produto mais vendido
* Produto menos vendido

Visualizações:

* Top 5 produtos mais vendidos
* Tabela detalhada de vendas por produto
* Distribuição de vendas por categoria

<img width="1309" height="726" alt="image" src="https://github.com/user-attachments/assets/69862045-3139-47b7-b1aa-f140f2eae27f" />


---

## 📦 Monitoramento de Estoque

Esta página apresenta informações relacionadas ao estoque das lojas.

Indicadores analisados:

* Loja com maior estoque
* Margem de lucro
* Análise de custos

Visualizações:

* Distribuição do estoque por produto
* Tendência de vendas ao longo do tempo

<img width="1312" height="736" alt="image" src="https://github.com/user-attachments/assets/9171745a-99e7-47ac-86db-fe01e861705f" />


---

# 🔄 Atualização dos Dados

O projeto utiliza um **pipeline de ingestão de dados baseado em pasta (Folder)**.

O Power BI lê automaticamente todos os arquivos CSV localizados dentro da pasta de dados e os combina durante a atualização do relatório.

### Estrutura da pasta de dados

data/

vendas_jan.csv
vendas_fev.csv
vendas_mar.csv

Sempre que um novo arquivo for adicionado à pasta, ele será automaticamente incluído na análise após a atualização do relatório.

### Como adicionar novos dados

1. Copie o novo arquivo CSV para a pasta **data**
2. Certifique-se de que o arquivo possui as mesmas colunas
3. Clique em **Atualizar** no Power BI

O dashboard será atualizado automaticamente.

---

# ⚙️ Ferramentas Utilizadas

Este projeto foi desenvolvido utilizando:

* Power BI
* DAX (Data Analysis Expressions)
* Power Query
* Modelagem de dados
* Arquivos CSV como fonte de dados

---

# 📊 Métricas Calculadas

O dashboard calcula diversas métricas importantes para análise de desempenho:

* Receita total
* Quantidade vendida
* Lucro
* Preço médio por produto
* Desempenho das lojas
* Produtos mais vendidos
* Distribuição de estoque

---

# 📁 Estrutura do Projeto

retail-sales-powerbi-dashboard

data/
Arquivos CSV utilizados no projeto

dashboard/
Arquivo do Power BI (.pbix)

images/
Capturas de tela do dashboard

README.md

---

# 🚀 Possíveis Melhorias Futuras

Algumas melhorias que podem ser implementadas em versões futuras:

* Análise de lucro por produto
* Alertas automáticos de estoque baixo
* Segmentação de clientes
* Modelos de previsão de vendas
* Integração com banco de dados em tempo real

---

# 👨‍💻 Autor

Luiggy Collyer
Analista de Dados (Júnior)

GitHub
https://github.com/LuiggyARC
