# 🚢 Controle de Embarcações — Marinha do Brasil

Relatório em Power BI que analisa os **Registros de Embarcações** da Marinha do Brasil, comparando os anos de **2024** e **2025**.


---

## 📌 Sobre o projeto

Este projeto foi desenvolvido como exercício prático de Business Intelligence, cobrindo todo o fluxo: tratamento de dados, modelagem, criação de medidas DAX e construção de um relatório interativo no Power BI.

- **Fonte dos dados:** [ex: dados públicos da Marinha do Brasil / Diretoria de Portos e Costas]
- **Período analisado:** 2024 e 2025
- **Ferramentas utilizadas:** Excel (tratamento de dados) e Power BI (modelagem e visualização)

## ❓ Perguntas de negócio respondidas

O relatório foi construído para responder a 5 perguntas:

1. **Registro por Embarcação** — quantos registros existem por tipo de embarcação?
2. **Maior Volume por UF** — qual estado concentra o maior volume de registros?
3. **Média de Volume Portuária** — qual a média de registros por porto/capitania?
4. **Maiores Registros Portuários** — quais portos têm o maior volume de registros?
5. **Percentual por Embarcação** — qual o peso percentual de cada tipo de embarcação no total?

## 🖼️ Prints do relatório

### Página 2024
![Página 2024] https://github.com/KawaiMatheus/Portfolio/blob/8f66ba35e4af2a6ea3926c1a39b06d0f055c8869/Projeto%20Marinha/R_M_2024.png

### Página 2025 (com comparativo 2024 x 2025)
![Página 2025](caminho/para/print-2025.png)

## 🧮 Principais medidas DAX

| Medida | O que faz |
|---|---|
| `Total de Registros` | Soma total de registros de embarcações |
| `Média Portuária` | Média de registros por porto/capitania |
| `% Embarcação` | Percentual de cada tipo de embarcação sobre o total |

> Adicione aqui a fórmula DAX de cada medida, se quiser detalhar ainda mais.

## 🛠️ Tratamento e modelagem de dados

- Padronização dos nomes de colunas (ex: coluna originalmente chamada `RJ` renomeada para `UF`; coluna `Rebocador` renomeada para `Tipo de Embarcação`/`Embarcação`, já que continha vários tipos de embarcação, não só rebocadores)
- Separação dos dados por ano (`Embarcações_2024` e `Embarcações_2025`) para permitir comparação lado a lado
- Criação de slicer por UF para exploração interativa

## 📂 Estrutura do repositório

```
├── Projeto_Marinha.pbix     # Relatório Power BI
├── ProjetoMarinha.xlsx      # Base de dados tratada
└── README.md                # Este arquivo
```

## ▶️ Como abrir

1. Baixe o arquivo `Projeto_Marinha.pbix`
2. Abra no [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (gratuito)
3. Explore os filtros e slicers para navegar pelos dados

---

👤 Kawai Matheus D. Silva

*Projeto desenvolvido como parte do meu portfólio de análise de dados.*
