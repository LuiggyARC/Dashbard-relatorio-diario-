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

<img width="1307" height="736" alt="image" src="https://github.com/user-attachments/assets/347f8f6d-8b78-4e52-aa91-ecaa23e4c9a7" />


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

<img width="1310" height="732" alt="image" src="https://github.com/user-attachments/assets/6fcfe1e4-1424-4a59-a60a-6e11b4b2decb" />


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

<img width="1310" height="735" alt="image" src="https://github.com/user-attachments/assets/983206e6-dbfd-40ee-8714-d308fade6abb" />


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
* Python para organização e modelagem
* Dados internos autorizados

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

---

# 👨‍💻 Autor

Luiggy Collyer
Analista de Dados (Júnior)

GitHub
https://github.com/LuiggyARC
