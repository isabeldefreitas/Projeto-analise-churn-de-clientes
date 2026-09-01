# 📊 Customer Churn Analysis

## 📌 Sobre o projeto

Este projeto tem como objetivo analisar o **Customer Churn**, identificando padrões e características relacionados à saída de clientes.

A análise foi desenvolvida a partir de uma base de dados contendo informações demográficas, financeiras e comportamentais dos clientes. Os dados foram tratados e enriquecidos para facilitar a exploração das informações e a identificação de possíveis fatores relacionados ao cancelamento.

Os resultados foram apresentados em um dashboard interativo desenvolvido no **Power BI**, dividido entre uma visão geral da base e uma análise mais detalhada dos clientes e do churn.

---

# 🎯 Objetivo

O objetivo do projeto é responder perguntas como:

- Qual é a taxa geral de churn?
- Qual é o perfil dos clientes da base?
- Existem diferenças no churn entre países?
- Clientes ativos apresentam um comportamento diferente dos clientes que cancelaram?
- O tempo de relacionamento influencia no comportamento dos clientes?
- Existe alguma relação entre score, idade, produtos contratados e churn?

---

# 📂 Base de Dados

A base utilizada contém informações de **10.000 clientes**, incluindo características como:

| Variável | Descrição |
|---|---|
| `CustomerId` | Identificador do cliente |
| `CreditScore` | Score de crédito |
| `Geography` | País do cliente |
| `Gender` | Gênero |
| `Age` | Idade |
| `Tenure` | Tempo de relacionamento |
| `Balance` | Saldo do cliente |
| `NumOfProducts` | Quantidade de produtos contratados |
| `HasCrCard` | Possui cartão de crédito |
| `IsActiveMember` | Indica se o cliente está ativo |
| `EstimatedSalary` | Salário estimado |
| `Exited` | Indica se o cliente deixou a empresa |

---

# 🔄 Tratamento e Preparação dos Dados

O tratamento e preparação dos dados foram feitos por meio do Power Query para facilitar a análise.


# 📈 Dashboard

O dashboard foi desenvolvido no **Power BI** e está dividido em duas páginas principais.

## 🏠 Dados Gerais

A primeira página apresenta uma visão geral da base.

Principais indicadores:

* Total de clientes;
* Média de idade;
* Taxa de churn;
* Saldo médio.

Além dos indicadores, a página apresenta análises sobre:

* Distribuição etária;
* Clientes por gênero;
* Clientes com cartão de crédito;
* Distribuição geográfica.

---

## 🔍 Detalhes

A segunda página permite uma exploração mais detalhada dos dados.

Entre as análises disponíveis estão:

* Clientes ativos versus cancelamentos;
* Distribuição de clientes por score;
* Clientes por tempo de relacionamento;
* Churn por país.

Também foram disponibilizados filtros para facilitar a exploração dos dados de acordo com características como:

* Gênero;
* Cliente ativo;
* Cartão de crédito;
* Status de churn;
* Número de produtos.

---

# 💡 Principais Insights

A análise permitiu identificar alguns padrões relacionados ao comportamento dos clientes.

## 📉 Taxa geral de churn

A base possui aproximadamente **10 mil clientes**.

Desses, **2.037 clientes saíram**, representando uma taxa de churn de aproximadamente:

### 20,37%

---

## 🌍 Churn por país

A análise mostra diferenças significativas entre os países presentes na base.

| País    | Taxa de Churn |
| ------- | ------------: |
| Germany |        32,44% |
| Spain   |        16,67% |
| France  |        16,15% |

A Alemanha apresenta uma taxa de churn consideravelmente superior aos outros países analisados.

---

## 👤 Clientes ativos e churn

Clientes não ativos apresentam uma taxa de churn maior do que clientes ativos.

| Status            | Taxa de Churn |
| ----------------- | ------------: |
| Cliente ativo     |        14,27% |
| Cliente não ativo |        26,85% |

Esse resultado indica uma possível relação entre o nível de atividade do cliente e a probabilidade de cancelamento.

---

## 👴 Idade dos clientes

Os clientes que saíram apresentam uma idade média superior à dos clientes que permaneceram.

| Grupo        | Média de idade |
| ------------ | -------------: |
| Permaneceram |      37,4 anos |
| Saíram       |      44,8 anos |

---

## 📦 Quantidade de produtos

A quantidade de produtos contratados também apresenta diferenças no comportamento dos clientes.

| Produtos   | Taxa de Churn |
| ---------- | ------------: |
| 1 produto  |        27,71% |
| 2 produtos |         7,58% |

Clientes com dois produtos apresentam uma taxa de churn significativamente menor em comparação aos clientes que possuem apenas um produto.

> Os grupos com três e quatro produtos possuem uma quantidade menor de clientes e, por isso, devem ser analisados com cautela.

---
# 🧠 Conclusões

A análise mostrou que o churn não está distribuído de forma uniforme entre os clientes.Esses resultados demonstram como a análise de dados pode auxiliar na identificação de segmentos que merecem maior atenção e na investigação de possíveis estratégias de retenção de clientes.

---  

# 🛠️ Tecnologias e Ferramentas

* Power BI
* Power Query
* Análise de Dados
* Tratamento de Dados
* Visualização de Dados



