# Projeto de Previsão de Cancelamento de Streaming com Orange 📊🎬

## 🎯 Objetivo

Este projeto visa prever a probabilidade de cancelamento (churn) de assinaturas de um serviço de streaming, utilizando dados de uma planilha Excel e a ferramenta de análise de dados visual **Orange Data Mining**. O principal objetivo é **identificar os fatores que mais contribuem para o churn e construir um modelo preditivo capaz de alertar sobre possíveis cancelamentos.**

## 🛠️ Ferramentas Utilizadas

* **🍊 Orange Data Mining:** Software de código aberto para análise de dados visual, aprendizado de máquina e mineração de dados. O fluxo de trabalho analítico foi construído através da interface de arrastar e soltar.
* **📈 Microsoft Excel:** Utilizado para armazenar e organizar os dados históricos de assinaturas.

## ⚙️ Fluxo de Trabalho no Orange

O projeto utilizou os seguintes widgets no Orange para construir o modelo de previsão:

1.  **📤 Data (Arquivo Excel):** Importação da planilha Excel contendo os dados de assinaturas.
2.  **📈 Data Table:** Visualização e inspeção dos dados importados.
3.  **✂️ Select Columns:** Seleção das colunas relevantes para a análise.
4.  **✨ Preprocess:** Realização de etapas de pré-processamento dos dados (tratamento de valores ausentes, normalização, etc.).
5.  **📊 Feature Statistics:** Obtenção de estatísticas descritivas das variáveis.
6.  **🥇 Rank:** Avaliação da importância de cada variável na predição do churn.
7.  **🌳 Random Forest:** Utilização do algoritmo Random Forest para construir o modelo preditivo de classificação.
8.  **📉 Logistic Regression:** Utilização do algoritmo de Regressão Logística como modelo de comparação.
9.  **🧠 Learner:** Conectores para os algoritmos de aprendizado (Random Forest e Logistic Regression).
10. **🧪 Test and Score:** Avaliação do desempenho dos modelos utilizando divisão de dados em treino e teste e cálculo de métricas (acurácia, precisão, recall, F1-score, AUC).
11. **📈 Evaluation Results:** Exibição das métricas de avaliação dos modelos.
12. **📊 ROC Analysis:** Análise da Curva ROC para visualizar o desempenho dos classificadores.
13. **📊 Confusion Matrix:** Visualização da matriz de confusão para análise detalhada das previsões.
14. **✅ Resultado Final (Opcional):** Exibição da probabilidade de churn ou classificação final.
15. **💾 Save Data (Opcional):** Salvamento dos resultados ou dados processados.

![Captura de tela 2025-04-06 153304](https://github.com/user-attachments/assets/4f1dbc29-45e6-4696-8cf8-705ba75f1c99)


## 🚀 Como Utilizar (Demonstração)

Para visualizar o fluxo de trabalho completo e os resultados da análise, abra o arquivo `.ows` (workflow do Orange) fornecido neste repositório com o Orange Data Mining.

## 📝 Observações

Este projeto demonstra a aplicação da análise de dados visual com Orange para a previsão de churn em um serviço de streaming, utilizando dados de uma planilha Excel. A identificação de variáveis importantes e a avaliação de modelos de machine learning fornecem insights valiosos para a retenção de clientes.

---
