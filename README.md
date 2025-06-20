# 🌾 Classificação de Variedades de Grãos de Trigo com CRISP-DM

**Disciplina:** CTWP – Ciência e Tecnologia de Web e Processos  
**Fase:** 04  
**Aluno:** Kleber Foks RM 562225 

---

## 📌 Objetivo

Aplicar a metodologia **CRISP-DM** para desenvolver um modelo de aprendizado de máquina capaz de classificar três variedades de grãos de trigo com base em suas características físicas, utilizando o conjunto de dados **Seeds Dataset** (UCI Machine Learning Repository).

---

## 🗂️ Estrutura do Projeto

FASE 04/
└── CTWP/
└── Cap11/
├── CRISP_DM_Seeds_Classification.ipynb
└── README.md

yaml
Copiar
Editar

---

## 📊 Etapas do Projeto

### 1. **Entendimento e Pré-processamento dos Dados**
- Leitura do dataset e análise exploratória.
- Visualização de correlações com gráficos (`pairplot`, `boxplot`, `histogramas`).
- Normalização dos dados com `StandardScaler`.

### 2. **Modelagem**
- Divisão dos dados em treino (70%) e teste (30%).
- Treinamento de três modelos:  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM)  
  - Random Forest

### 3. **Avaliação**
- Avaliação com métricas: **accuracy, precision, recall, f1-score**.
- Otimização com `GridSearchCV` para KNN, SVM e Random Forest.

### 4. **Visualização**
- Gráfico comparativo de acurácia dos modelos.
- Matriz de confusão do modelo com melhor desempenho (SVM).

---

## 🧠 Resultados

- **Melhor Modelo:** SVM (otimizado)  
- **Acurácia Final:** 92.06%

---

## 📁 Dataset

- Fonte: [Seeds Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/236/seeds)  
- Atributos: área, perímetro, compacidade, comprimento/largura do núcleo, assimetria, sulco central, variedade (target)

---

## ✅ Conclusão

A metodologia **CRISP-DM** guiou eficientemente o desenvolvimento do projeto.  
O uso de algoritmos supervisionados mostrou ser eficaz na tarefa de classificação de grãos, com o modelo SVM atingindo alta performance.

---
