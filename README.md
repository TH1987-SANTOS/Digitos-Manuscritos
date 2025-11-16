# 🧠 Classificação de Dígitos — Projeto MNIST (sklearn.datasets)

Este projeto apresenta uma solução completa e didática para o problema de classificação de dígitos manuscritos utilizando o dataset **Digits** do `sklearn.datasets`, uma versão reduzida do clássico MNIST. O objetivo é demonstrar um pipeline limpo, organizado e reprodutível, ideal para estudos, portfólio e entrevistas técnicas.

---

## 📌 Objetivos do Projeto

- Explorar o dataset e visualizar imagens.
- Realizar pré-processamento simples.
- Treinar um modelo baseline (Regressão Logística).
- Avaliar o modelo e interpretar métricas.
- Identificar padrões de erro.
- Criar visualizações claras e profissionais.
- Sugerir próximos passos para aprimoramento do modelo.

---

## 📂 Estrutura do Projeto

📁 Projeto-MNIST/
├── Mnist.ipynb 
├── README.md 
├── requirements.txt 
└── models

---

## 📊 Sobre o Dataset

Usamos o dataset **Digits** do `sklearn`, que contém:

- 1.797 imagens
- Imagens de 8×8 pixels
- Valores de 0 a 16 (intensidade)
- Classes de **0 a 9**

É excelente para estudos iniciais de visão computacional com machine learning tradicional.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python 3.10+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook / JupyterLab

---

## ▶️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/TH/Projeto-MNIST.git
cd Projeto-MNIST


---

## 📊 Sobre o Dataset

Usamos o dataset **Digits** do `sklearn`, que contém:

- 1.797 imagens
- Imagens de 8×8 pixels
- Valores de 0 a 16 (intensidade)
- Classes de **0 a 9**

É excelente para estudos iniciais de visão computacional com machine learning tradicional.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- Python 3.10+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Jupyter Notebook / JupyterLab

---

## ▶️ Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/TH1987-SANTOS/Projeto-MNIST.git
cd Projeto-MNIST

🚀 Pipeline Desenvolvido

 A solução implementa as seguintes etapas:

1. Importação das bibliotecas

2. Carregamento e exploração do dataset

3. Visualização das imagens

4. Normalização dos dados

5. Divisão treino/teste

6. Treinamento de modelo baseline (Regressão Logística)

7. Métricas:

- Acurácia

- Classification Report

- Matriz de Confusão

8. Curva de Aprendizado

9. Comparação com modelos:

- KNN

- SVM

10. Salvamento do modelo com Joblib

📈 Resultados Obtidos

O modelo baseline apresentou:

- Boa acurácia geral

- Desempenho consistente em validação cruzada

- Erros concentrados em pares semelhantes, como:

- 3 vs 5

- 8 vs 9


🧩 Exemplos de Visualizações Incluídas

- Grid de imagens dos dígitos

- Distribuição das classes

- Matriz de confusão normalizada

- Curva de aprendizado

- Amostras de previsões incorretas

💾 Salvamento do Modelo

O modelo treinado é salvo em:

models/logistic_mnist_digits.joblib


Isso permite reutilizar o classificador sem precisar reexecutar o notebook.

🧭 Próximos Passos Recomendados

- Treinar um MLPClassifier (rede neural)

- Migrar para o MNIST original (28×28)

- Implementar GridSearchCV ou Optuna

- Criar um pipeline com sklearn.pipeline

- Implementar pré-processamento avançado

- Criar um dashboard (Plotly/Streamlit/Gradio)

- Criar versão web interativa para desenhar dígitos