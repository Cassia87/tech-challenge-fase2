# 🍷 TECH CHALLENGE - Fase 2

## Wine Quality Classification

Projeto desenvolvido para o **Tech Challenge - Fase 2**, com o objetivo de aplicar técnicas de **Machine Learning** para classificar a qualidade de vinhos tintos a partir de suas características físico-químicas.

---

## 📌 Objetivo

Desenvolver modelos de classificação capazes de prever se um vinho é de **boa qualidade** ou de **baixa/média qualidade**, utilizando algoritmos de Machine Learning.

Para isso, a variável **quality** foi transformada em uma classificação binária:

- **1** → Vinhos de boa qualidade (nota ≥ 7)
- **0** → Vinhos de baixa ou média qualidade (nota < 7)

---

## 📊 Dataset

O projeto utiliza o **Wine Quality Dataset**, composto por características físico-químicas de vinhos tintos, como:

- Fixed Acidity
- Volatile Acidity
- Citric Acid
- Residual Sugar
- Chlorides
- Free Sulfur Dioxide
- Total Sulfur Dioxide
- Density
- pH
- Sulphates
- Alcohol

---

## 🔍 Etapas do Projeto

- Análise exploratória dos dados (EDA)
- Tratamento de dados
- Identificação de dados duplicados
- Tratamento de valores ausentes
- Análise da distribuição das variáveis
- Identificação de outliers
- Análise de correlação entre as variáveis
- Transformação da variável alvo em classificação binária
- Padronização das variáveis numéricas
- Treinamento dos modelos
- Avaliação dos resultados

---

## 🤖 Modelos Utilizados

- K-Nearest Neighbors (KNN)
- Random Forest

---

## 📈 Resultados

| Modelo | Acurácia |
|---------|---------:|
| KNN | **87%** |
| Random Forest | **92%** |

O modelo **Random Forest** apresentou o melhor desempenho, alcançando **92% de acurácia** na classificação dos vinhos.

---

## 📁 Estrutura do Projeto

```text
wine-quality-classification/
│
├── data/
│   └── Base de dados utilizada
│
├── notebooks/
│   └── Notebook com toda a análise e modelagem
│
├── src/
│   └── Scripts auxiliares de pré-processamento e treinamento
│
├── results/
│   └── Gráficos, matrizes de confusão e métricas
│
├── requirements.txt
│
└── README.md
```

---

## 🛠 Tecnologias Utilizadas

- Python
- Google colab

---

## 👩‍💻 Autora

**Cassia Guedes**
