# Previsão de Vendas de Medicamentos para Câncer de Próstata

Este projeto realiza análise e modelagem preditiva com dados da IQVIA para prever o comportamento de vendas de medicamentos voltados ao tratamento do câncer de próstata. Foram desenvolvidos dois modelos supervisionados com abordagens distintas:

- **Modelo 1:** Previsão do **valor da venda** com base em variáveis históricas e de mercado.
- **Modelo 2:** Previsão das **vendas para os próximos 6 meses**, permitindo insights temporais para planejamento estratégico.

---

## Objetivos

- Aplicar técnicas de pré-processamento e normalização.
- Construir modelos de regressão supervisionada para previsão de vendas.
- Gerar visualizações para interpretar padrões, tendências e desempenho dos modelos.
- Apoiar decisões de negócio por meio de previsões robustas.

---

### Técnicas Utilizadas

- Regressão supervisionada
- Análise exploratória de dados (EDA)
- Pré-processamento (tratamento de outliers, normalização, encoding)
- Visualização com gráficos interativos
- Divisão treino/teste e validação cruzada
- Avaliação de desempenho (RMSE, R², MAE)
  
---

## Tecnologias Utilizadas

- **Linguagem:** Python 3.11
- **Bibliotecas:**  
  - Pandas, NumPy  
  - Scikit-learn  
  - Matplotlib, Seaborn  
  - XGBoost / LightGBM *(se aplicável)*

---

## Estrutura do Projeto
├── data/ # Arquivos brutos e tratados (não incluídos)
├── tratamentos e modelo de previsões/ # Jupyter notebooks com a análise e modelagem
└── README.md # Este arquivo

Todo o projeto foi desenvolvido no Google Colab, facilitando a reprodutibilidade e visualização interativa dos resultados.


### Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repo.git


### Observações
O modelo leva em consideração tendências sazonais e padrões históricos observados nos dados.

Resultados e gráficos estão integrados aos notebooks para facilitar a interpretação.

### Próximos Passos
  - Implementar ajuste automático de hiperparâmetros
  - Incorporar variáveis externas (ex: políticas de mercado, concorrência)
  - Criar dashboard com visualização interativa


### Autora
[juliana Silva]
[LinkedIn]
