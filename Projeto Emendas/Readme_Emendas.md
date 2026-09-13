# Controle de Emendas Parlamentares por Área — Dashboard Power BI

> ⚠️ **Aviso**: este é um projeto de **amostra/simulação, com fins exclusivamente de aprendizado**. Os dados aqui utilizados são reduzidos (uma amostra de ~177 registros) e não representam o conjunto completo de emendas parlamentares reais. O objetivo é praticar modelagem de dados, DAX e criação de dashboards no Power BI — não fornecer uma análise oficial ou completa do tema.

## 🎯 Objetivo

Este projeto simula um painel de controle de gastos com **emendas parlamentares** distribuídas por área/função orçamentária, ano e unidade da federação (UF). O objetivo é responder perguntas como:

- Qual o total pago em emendas por função (Saúde, Educação, Urbanismo, etc.)?
- Como o total pago evoluiu ao longo dos anos?
- Qual o gasto médio, mínimo e total por UF?
- Quais os principais programas associados aos valores pagos por estado?

## 📊 Sobre o dashboard

O relatório possui uma página (**"Gastos de Emendas por Área"**) com os seguintes elementos:

| Visual | Descrição |
|---|---|
| Cartão KPI | Total Pago (indicador principal), com linha de tendência por número da emenda |
| Gráfico de linha | Total Pago por Ano da Emenda |
| Gráfico de barras | Total Pago por Nome Função |
| Tabela dinâmica | Total Pago, Gasto Médio e Gasto Mínimo por UF, com o programa associado |
| Segmentações (slicers) | Filtro por Ano da Emenda e por Nome Função |

## 🗂️ Estrutura dos dados

Os dados estão na planilha `EmendasParlamentares.xlsx`, com as seguintes colunas:

- `Ano da Emenda`, `Tipo de Emenda`
- `Código do Autor da Emenda`, `Nome do Autor da Emenda`, `Número da emenda`
- `Possui Apoiador/Solicitante?`
- `Localidade de aplicação do recurso`, `Município`, `UF`, `Região`
- `Código Função`, `Nome Função`
- `Código Subfunção`, `Nome Subfunção`
- `Código Programa`, `Nome Programa`
- `Valor Empenhado`, `Valor Pago`

A amostra cobre os anos de **2018 a 2026**, **23 UFs** e **14 funções orçamentárias**, sem valores nulos.

> 💡 O modelo de dados inspirado no tema de emendas parlamentares tem como referência pública o [Portal da Transparência](https://portaldatransparencia.gov.br/) e a [Câmara dos Deputados](https://www.camara.leg.br/), mas os valores usados aqui foram simplificados/reduzidos para fins didáticos e **não devem ser usados como fonte oficial**.

## 🛠️ Tecnologias utilizadas

- Power BI Desktop (modelagem, DAX e visualização)
- Excel (fonte de dados)

## 📁 Arquivos neste repositório

- `Projeto_Parlamentar.pbix` — arquivo do relatório Power BI
- `EmendasParlamentares.xlsx` — base de dados utilizada
- `screenshots/` — capturas de tela do dashboard *(adicione aqui os prints)*

## ▶️ Como usar

1. Baixe o [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (gratuito).
2. Clone este repositório ou baixe o arquivo `.pbix`.
3. Abra o arquivo `Projeto_Parlamentar.pbix` no Power BI Desktop.
4. Explore o dashboard usando as segmentações de Ano e Função.

## 📌 Próximos passos / melhorias futuras

- Expandir a amostra de dados
- Adicionar tabela calendário para análises temporais mais robustas
- Criar uma segunda página com detalhamento por município
- Documentar as medidas DAX utilizadas

## 👤 Kawai Matheus D. Silva

Projeto desenvolvido como prática de estudo em Power BI.

---
*Este projeto é apenas para fins educacionais e de portfólio.*
