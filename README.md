# 📘 Predição e Classificação de Preços de Imóveis

## 🏠 Sobre o Projeto

Este projeto tem como objetivo analisar um conjunto de dados imobiliários e desenvolver modelos estatísticos e de machine learning capazes de:

- ✅ Prever o preço de imóveis (regressão)
- ✅ Classificar imóveis em faixas de preço (classificação)
- ✅ Realizar EDA, testes estatísticos e otimização de modelos
- ✅ Interpretar resultados e validar o desempenho das abordagens

O trabalho segue a metodologia apresentada em sala, incluindo regressão linear, regressão múltipla, modelos polinomiais e algoritmos de classificação supervisionada.

---

## 🔍 Etapas do Projeto

### 1️⃣ Análise Exploratória de Dados (EDA)
- Distribuições das variáveis
- Outliers e comportamento geral dos dados
- Relação entre área, preço e demais atributos
- Heatmaps e gráficos de dispersão

### 2️⃣ Correlação e Testes Estatísticos
- Matriz de correlação (Pearson)
- Identificação de multicolinearidade
- Testes de hipótese para validar significância

### 3️⃣ Regressão Linear Simples
- Ajuste com uma variável (ex.: área)
- Métricas: MAE, RMSE, R²
- Análise de resíduos e QQ plot

### 4️⃣ Regressão Linear Múltipla
- Normalização com StandardScaler
- Divisão treino/teste
- Análise de multicolinearidade com VIF

### 5️⃣ Regressão Polinomial
- Modelos grau 2 e 3
- Avaliação de overfitting

### 6️⃣ Classificação: Criação das Classes
- O preço contínuo foi convertido em três faixas: baixo, médio e alto.
- Isso permitiu aplicar modelos de classificação ao problema.

### 7️⃣ Modelos de Classificação
- Regressão Logística
- Naive Bayes
- KNN
- Random Forest
- SVM

**Métricas:** Acurácia, F1-Score, Precision, Recall, Matriz de Confusão

### 8️⃣ Otimização (Cross Validation e Hyperparameter Tuning)
- **KFold**: Validação cruzada para estabilidade
- **GridSearchCV / RandomizedSearchCV**: Ajuste de hiperparâmetros

---

## 🎯 Principais Conclusões

✔️ **Regressão múltipla** foi o melhor modelo para previsão contínua  
✔️ **Regressão logística** melhor desempenho na classificação  
✔️ Modelos polinomiais não superaram consistentemente os lineares  
✔️ Classes extremas apresentaram maior sobreposição  
✔️ Otimização aprimorou significativamente o desempenho final  

---

## 🛠 Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Statsmodels
