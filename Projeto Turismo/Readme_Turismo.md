# 🌍 Análise de Turismo Internacional no Brasil (2023–2025)

Projeto de prática em **Power BI** com o objetivo de analisar a chegada de turistas internacionais ao Brasil entre 2023 e 2025, explorando origem, destino, via de acesso e sazonalidade das viagens.

## 📌 Sobre o projeto

O relatório consolida três bases anuais de chegadas de turistas estrangeiros ao país e apresenta a evolução do fluxo turístico por:

- Continente e país de origem
- Estado (UF) de destino
- Via de acesso (aérea, terrestre, marítima, fluvial)
- Mês do ano (sazonalidade)

O dashboard foi construído com foco em navegação intuitiva entre os anos e no uso de visuais analíticos avançados, como o **Principais Fatores (Key Influencers)**.

## 🗂️ Fonte dos dados

Bases anuais de chegadas de turistas internacionais ao Brasil (2023, 2024 e 2025), com colunas de continente/país de origem, UF de destino, via de acesso, mês e número de chegadas. Os arquivos originais apresentavam pequenas inconsistências de nomenclatura entre os anos (ex.: `UF Destino` x `UF de Destino`, `Via` x `Via_de_acesso`), tratadas na etapa de modelagem.

## 🧭 Estrutura do relatório

| Página | Conteúdo |
|---|---|
| **Info** | Capa e navegação entre os anos |
| **Visitas 2023 / 2024 / 2025** | Total por continente de origem, ranking de países, total por via de acesso, sazonalidade mensal, mapa por estado de destino e análise de Principais Fatores (UF de destino x continente de origem) |

## 📊 Principais insights

- O fluxo total de chegadas cresceu ano a ano: **5,87 milhões (2023) → 6,72 milhões (2024) → 9,29 milhões (2025)**
- A **Argentina** é disparadamente o principal país de origem nos três anos, respondendo por cerca de 30–36% das chegadas
- **América do Sul** é o continente de origem dominante (~59–65% do total), seguida por Europa e América do Norte
- **São Paulo** e **Rio de Janeiro** concentram a maior parte das chegadas por UF de destino em todos os anos
- A via **aérea** é o principal meio de acesso (~64–66% das chegadas), seguida pela via terrestre

## 🛠️ Ferramentas utilizadas

- **Power BI Desktop** (modelagem, medidas DAX e visualização)
- **Power Query** para limpeza e padronização das três bases anuais, incluindo uma coluna auxiliar de número do mês para garantir a ordenação cronológica correta nos gráficos de sazonalidade
- Visuais: gráfico de colunas, gráfico de linha, mapa (Azure Map), tabelas dinâmicas e Principais Fatores (Key Influencers)

## 🚀 Como usar

1. Baixe o arquivo `BI_Turismo_Brasil.pbix`
2. Abra no Power BI Desktop
3. Navegue entre as páginas de 2023, 2024 e 2025 usando os botões da capa

## 📈 Possíveis evoluções

- Consolidar as três tabelas anuais em uma única tabela fato com coluna `Ano`, reduzindo a duplicação de medidas e permitindo comparação direta entre anos em um único visual
- Adicionar página comparativa entre os três anos

## 📷 Prints do dashboard

[#Info ] https://github.com/KawaiMatheus/Portfolio/blob/e426b948d49d2b228b7dfe12bf85f7a192754655/Projeto%20Turismo/Info_Turismo.png

[#Visita_2023] https://github.com/KawaiMatheus/Portfolio/blob/ddc48971c9125e3dde2583fbd60d06fb426efd02/Projeto%20Turismo/Turismo_2023.png

[#Visita_2024] https://github.com/KawaiMatheus/Portfolio/blob/481a056ae8a1639eb5734c4ade74b5423f65aa9d/Projeto%20Turismo/Turismo_2024.png

[#Visita_2025] https://github.com/KawaiMatheus/Portfolio/blob/dd18f81fba71127d67a1b239d888a0921f9359a4/Projeto%20Turismo/Turismo_2025.png

---

Projeto desenvolvido para fins de estudo e prática de Power BI.
