# ⚡ Voltiq — Análise de Veículos Elétricos

> Projeto de análise de dados e modelagem preditiva para entender como fatores técnicos e de uso impactam a adoção e o valor de revenda de veículos elétricos.

---

## 📌 Sobre o Projeto

O **Voltiq** é um projeto completo de ciência de dados desenvolvido em Python, com foco em veículos elétricos. A análise cobre desde a exploração estatística dos dados até a construção de modelos de machine learning para prever o valor de revenda.

---

## 🗂️ Estrutura do Projeto

```
voltiq/
├── analise_veiculos_eletricos_FINAL.ipynb  → Notebook principal (dados embutidos)
└── README.md
```

> Os dados já estão embutidos diretamente no notebook. Não é necessário fazer upload de nenhum arquivo CSV!

---

## 🚀 Como Executar

### Google Colab (recomendado)
1. Acesse [colab.research.google.com](https://colab.research.google.com)
2. Clique em **Arquivo → Fazer upload de notebook**
3. Selecione o arquivo `analise_veiculos_eletricos_FINAL.ipynb`
4. Execute as células em ordem com `Shift + Enter`

### Jupyter Notebook / VSCode
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
jupyter notebook analise_veiculos_eletricos_FINAL.ipynb
```

---

## 📦 Bibliotecas Utilizadas

| Biblioteca | Versão mínima | Finalidade |
|-----------|--------------|------------|
| pandas | 1.3+ | Manipulação de dados |
| numpy | 1.21+ | Cálculos numéricos |
| matplotlib | 3.4+ | Visualizações |
| seaborn | 0.11+ | Gráficos estatísticos |
| scikit-learn | 0.24+ | Modelos de machine learning |
| statsmodels | 0.12+ | Testes estatísticos |

---

## 📊 Entregas do Projeto

### Entrega 1 — Exploração Estatística
- Análise exploratória inicial: dimensões, tipos, valores ausentes e estatísticas descritivas
- Distribuição das variáveis numéricas e categóricas
- Comparação entre grupos: tipo de veículo e região
- Testes estatísticos: ANOVA e Kruskal-Wallis
- Mapa de correlação entre variáveis numéricas

### Entrega 2 — Tendências de Mercado
- Agregações anuais dos principais indicadores (revenda, custos, CO₂, autonomia)
- Gráficos de evolução ao longo do tempo
- Projeção futura com regressão linear

### Entrega 3 — Modelagem Preditiva
- Preparação e codificação das variáveis
- Treinamento de 6 algoritmos: Regressão Linear, Ridge, Lasso, Árvore de Decisão, Random Forest e Gradient Boosting
- Comparação por R², MAE e RMSE
- Análise de importância das variáveis
- Recomendações estratégicas para o negócio

---

## 🗃️ Dicionário de Dados

| Coluna | Tipo | Descrição |
|--------|------|-----------|
| ID_Veiculo | Inteiro | Identificador único do veículo |
| Marca | Texto | Fabricante (ex: Tesla, BMW) |
| Modelo | Texto | Modelo específico (ex: Model 3, Leaf) |
| Ano | Inteiro | Ano de fabricação |
| Regiao | Texto | Região de registro |
| Tipo_Veiculo | Texto | Tipo (SUV, Sedã, Hatchback, etc.) |
| Capacidade_Bateria_kWh | Numérico | Capacidade total da bateria em kWh |
| Saude_Bateria_% | Numérico | Estado de saúde da bateria em % |
| Autonomia_km | Numérico | Autonomia estimada em km |
| Quilometragem_km | Numérico | Quilometragem total percorrida |
| CO2_Economizado_ton | Numérico | CO₂ evitado estimado em toneladas |
| Custo_Manutencao_USD | Numérico | Custo anual de manutenção em USD |
| Custo_Seguro_USD | Numérico | Custo anual de seguro em USD |
| Valor_Revenda_USD | Numérico | **Variável-alvo:** valor de revenda em USD |

---

## 💡 Principais Resultados

- Capacidade e saúde da bateria são os fatores mais impactantes no valor de revenda
- SUVs apresentam valores de revenda superiores aos demais tipos
- Diferenças regionais significativas justificam estratégias de precificação locais
- O Random Forest foi o modelo com melhor desempenho preditivo
- O CO₂ economizado cresce a cada ano, reforçando o impacto ambiental positivo

---

## 👩‍💻 Tecnologias

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-150458?style=flat&logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24+-F7931E?style=flat&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
