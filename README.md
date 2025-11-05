# EDA-II-

# 🌸 Análise Exploratória de Dados — Iris Dataset

Este repositório contém um **notebook completo de Análise Exploratória de Dados (EDA)** desenvolvido no **Google Colab**, com base no **clássico dataset Iris**.  
O objetivo é explorar, visualizar e compreender o comportamento das variáveis numéricas e categóricas, identificando padrões, correlações e possíveis outliers.

---

## 📘 Sobre o Projeto

O **Iris Dataset** é amplamente utilizado no ensino de Machine Learning e Estatística.  
Ele contém **150 amostras** de três espécies de flores (*setosa*, *versicolor* e *virginica*), com as seguintes medições:

| Coluna              | Descrição                     |
|---------------------|--------------------------------|
| sepal length (cm)   | Comprimento da sépala          |
| sepal width (cm)    | Largura da sépala              |
| petal length (cm)   | Comprimento da pétala          |
| petal width (cm)    | Largura da pétala              |
| species             | Espécie da flor (rótulo alvo)  |

---

## 🎯 Objetivos da Análise

- Realizar **limpeza e inspeção** da base de dados  
- Explorar **distribuições** e **relações** entre as variáveis  
- Identificar **outliers** e **correlações** relevantes  
- Aplicar **PCA** (Análise de Componentes Principais) para visualização em 2D  
- Gerar **insights visuais** sobre as diferenças entre as espécies  

---

## 🧩 Tecnologias Utilizadas

- **Python 3.8+**
- **Google Colab**
- **Pandas** — Manipulação e limpeza de dados  
- **NumPy** — Cálculos e operações vetoriais  
- **Matplotlib / Seaborn** — Visualizações gráficas  
- **Scikit-learn** — Carregamento do dataset e PCA  
- **Plotly** *(opcional)* — Visualizações interativas

---

## 🚀 Como Executar no Google Colab

1. Acesse o notebook no Google Colab:  
   **[`iris_eda_colab.ipynb`](./iris_eda_colab.ipynb)**

2. Execute as células na ordem:
   - Instalação das dependências (`pip install ...`)
   - Importação das bibliotecas  
   - Carregamento e exploração do dataset  
   - Visualizações e conclusões  

3. Não é necessário fazer download de dados — o *Iris Dataset* já está incluído no `scikit-learn`.

---

## 📊 Principais Análises

- **Distribuições individuais** (histogramas e boxplots)  
- **Relações entre variáveis** (pairplot e heatmap de correlação)  
- **Comparação entre espécies**  
- **Detecção de outliers via IQR**  
- **PCA (2D)** para visualização da separação entre classes  

---

## 🧠 Insights Obtidos

- A espécie **setosa** se diferencia claramente das demais em comprimento e largura da pétala.  
- As espécies **versicolor** e **virginica** possuem sobreposição parcial, mas são separáveis via PCA.  
- Nenhum valor ausente foi encontrado.  
- As variáveis **petal length** e **petal width** são as mais relevantes para classificação.

---

## 📈 Próximos Passos

- Criar modelos de **classificação supervisionada** (KNN, SVM, Decision Tree).  
- Avaliar métricas de desempenho (acurácia, precisão, recall, F1-score).  
- Comparar resultados com e sem normalização / PCA.

---

## 👨‍💻 Autor

Desenvolvido por **[Victor Emanuel Maksud Carneiro]**  
Inspirado no projeto original de **Fabrício Valadares** ([fvaladares/iris_eda](https://github.com/fvaladares/iris_eda))  

📅 *Ano: 2025*  


