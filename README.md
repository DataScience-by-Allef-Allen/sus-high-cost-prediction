# 💰🏥 SUS High-Cost Patient Predictor

Este projeto tem como objetivo desenvolver um modelo de machine learning para prever pacientes com alto custo no Sistema Único de Saúde (SUS), com base em variáveis clínicas, demográficas e assistenciais. A proposta é identificar perfis de pacientes com maior risco de gerar altos custos, contribuindo para uma melhor gestão de recursos públicos em saúde.

Para facilitar o desenvolvimento e a compreensão do pipeline, o conjunto original com **5.282.340 linhas** foi reduzido para **1.000 linhas**. No entanto, o dataset completo está disponível para quem quiser utilizar o projeto com toda a base original.

Este repositório contém todas as etapas do projeto: pré-processamento, análise exploratória, modelagem com múltiplos algoritmos, otimização de hiperparâmetros, avaliação e comparação de resultados.

---

## 📥 Download do Dataset Completo

> 🔗 [[Clique aqui para baixar o dataset original com mais de 5 milhões de linhas](https://www.kaggle.com/datasets/llefrobsonallen/pacientes-de-alto-custo-no-sus-v2)]

---

## 📊 Sobre

- **Base usada:** Dataset de pacientes do SUS com custos assistenciais  
- **Tarefa:** Classificação binária (Alto custo vs. Baixo custo)  
- **Amostra para projeto:** 1.000 linhas (extraídas da base original)  
- **Técnicas utilizadas:**
  - Análise exploratória (EDA)
  - Algoritmos supervisionados
  - Otimização com GridSearchCV e RandomizedSearchCV
  - Avaliação com métricas e gráficos
  - Visualização de impacto de variáveis

---

## 🧪 Tecnologias

- **Ambiente:** Python + Google Colab  
- **Manipulação de dados:** Pandas, NumPy  
- **Visualização:** Matplotlib, Seaborn
- **Modelos de machine learning:**
  - Regressão Logística, LDA, KNN, SVM  
  - Random Forest, XGBoost, LightGBM  
  - Redes neurais com MLPClassifier  
- **Validação e otimização:** Cross-Validation, GridSearchCV, RandomizedSearchCV

---

## 📚 Projeto de Referência


Este projeto foi desenvolvido utilizando como **base de dados e inspiração para engenharia de atributos** o repositório [projeto_final_datasus](https://github.com/renatagr/projeto_final_datasus), criado por [Renata GR](https://github.com/renatagr). O trabalho dela serviu como referência para adaptação dos dados brutos do SUS e estruturação inicial do problema.

---

## 👨‍💻 Autor

**Allef Allen**  
[DataScience-by-Allef-Allen](https://github.com/DataScience-by-Allef-Allen)
