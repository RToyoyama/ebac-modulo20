# Projeto de Credit Score com Naive Bayes

## 📝 Descrição

Este projeto demonstra a aplicação do algoritmo Naive Bayes para a classificação de score de crédito. O objetivo é construir um modelo preditivo capaz de classificar clientes em diferentes categorias de risco de crédito com base em suas características financeiras e comportamentais.

Este trabalho é uma continuação do Módulo 17, onde os dados foram pré-processados, as classes foram balanceadas e as variáveis categóricas foram transformadas.

## 📊 Dados

O projeto utiliza quatro arquivos CSV:

*   `X_train_balanceado.csv`: Dados de treino com as variáveis preditoras.
*   `y_train_balanceado.csv`: Dados de treino com a variável alvo (score de crédito).
*   `X_test.csv`: Dados de teste com as variáveis preditoras.
*   `y_test.csv`: Dados de teste com a variável alvo.

A base de treinamento foi balanceada para garantir que o modelo não tivesse viés em relação a nenhuma classe específica.

## 🚀 Como Executar

Para executar o projeto e analisar os resultados, siga os passos abaixo:

1.  Certifique-se de ter o Python e o Jupyter Notebook (ou um ambiente compatível como o VS Code com a extensão Python) instalados.
2.  Instale as bibliotecas necessárias:
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn
    ```
3.  Abra e execute o notebook `Profissao Cientista de Dados M20 Pratique.ipynb`. O notebook contém todo o processo, desde o carregamento dos dados até a avaliação do modelo.

## 📈 Resultados

O modelo **Gaussian Naive Bayes** treinado alcançou um excelente desempenho tanto no conjunto de treinamento quanto no de teste:

*   **Acurácia no Treino:** ~98.7%
*   **Acurácia no Teste:** ~98.0%
*   **Recall (Macro) no Teste:** ~99.0%

As métricas próximas entre treino e teste indicam que o modelo tem uma ótima capacidade de generalização e não sofre de overfitting. A matriz de confusão mostrou um número mínimo de erros de classificação.

## 🛠️ Tecnologias Utilizadas

*   Python
*   Pandas
*   NumPy
*   Seaborn
*   Matplotlib
*   Scikit-learn
