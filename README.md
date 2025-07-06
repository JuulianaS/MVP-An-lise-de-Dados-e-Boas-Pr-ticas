# MVP Análise de Dados e Boas Práticas

## 📌 Projeto: Análise da Demanda de Medicamentos para Câncer de Próstata (Estágio Avançado)

**Autora:** Juliana Silva
**Matrícula:** 4052025000237

---

## 📖 Contexto

O câncer de próstata é uma das principais causas de mortalidade masculina no Brasil, principalmente em estágios avançados. O tratamento envolve medicamentos altamente especializados, cujo consumo e valor podem refletir aspectos importantes relacionados ao acesso à saúde, gestão hospitalar, disponibilidade regional e estratégias comerciais das empresas farmacêuticas.

Este projeto utiliza dados reais disponibilizados pela IQVIA, devidamente anonimizados, garantindo total confidencialidade e conformidade com as normas éticas.

---

## 🎯 Objetivos

O projeto busca realizar uma análise exploratória profunda e criar modelos preditivos robustos com duas vertentes principais:

* **Modelo Preditivo de Regressão:** Estimar o valor das vendas individuais com base em atributos como localização, canal de venda, produto e quantidade comercializada.
* **Modelo de Séries Temporais (Prophet):** Prever vendas totais (valor e unidades) dos próximos meses, identificando tendências e auxiliando o planejamento estratégico.

---

## 📁 Estrutura do projeto

```
│
├── 📂 dados
│   └── Demanda_Medicamentos.csv
│
├── 📂 notebooks (Mesmo arquivo disponível nas duas versões)
│   └── analise_exploratoria_e_modelagem.ipynb
│   └── analise_exploratoria_e_modelagem.py
│
└── README.md
```

---

## 🛠️ Ferramentas e Tecnologias

* **Python**
* **Google Colab**
* **Pandas**
* **Matplotlib e Seaborn**
* **Scikit-learn** (Regressão Linear, Random Forest, Pipeline, ColumnTransformer, SelectKBest)
* **Prophet** (Modelagem de séries temporais)

---

## ✅ Principais resultados

* **Random Forest** apresentou resultados excelentes (R² próximo a 1.0), indicando ótima captura das complexidades e não linearidades dos dados.
* **Regressão Linear** obteve desempenho razoável (R² médio \~0,59).
* **Prophet** apresentou previsões promissoras, mas com recomendações de ampliar o histórico temporal para melhorar a precisão.

---

## 📊 Insights Estratégicos

* O mercado de medicamentos oncológicos está em expansão moderada, indicando oportunidades para investimentos logísticos e estratégias comerciais específicas.
* Canal hospitalar apresenta valores mais altos, reforçando sua importância estratégica.
* Estabilidade relativa nos valores médios anuais demonstra um mercado consistente, mas com oportunidades pontuais de melhoria regional e por produto.

---

## 📈 Possíveis melhorias futuras

* Aumentar a base temporal dos dados para melhorar a precisão dos modelos preditivos.
* Testar os modelos com novos dados para avaliar melhor a generalização e reduzir risco de overfitting.
* Incorporar variáveis externas (campanhas de saúde pública, mudanças regulatórias, etc.) para melhorar previsões futuras.

---

## 📜 Licença

Este projeto utiliza dados anonimizados com permissão da IQVIA e destina-se exclusivamente a fins acadêmicos e analíticos.


### Autora
[juliana Silva][LinkedIn](https://www.linkedin.com/in/jjulianasilva/)

[Link do Google Colab](https://colab.research.google.com/drive/1QyWgRWg2Q7r76WkHXsczTTnNWMXKGG4g?usp=sharing)

