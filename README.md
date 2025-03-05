# Regressão Logística para Predição de Doenças Cardíacas

Este projeto utiliza **Regressão Logística** para prever a presença de doenças cardíacas com base em dados clínicos. Este é o meu **primeiro modelo de classificação** e faz parte da minha jornada na área de ciência de dados.

## Descrição do Projeto

O objetivo principal foi desenvolver um modelo capaz de prever se um paciente tem ou não uma doença cardíaca com base em variáveis como idade, pressão arterial, níveis de colesterol, entre outras.

## Conjunto de Dados
O dataset utilizado contém **303 registros** com **14 atributos**, incluindo:
- Idade
- Sexo
- Pressão arterial em repouso
- Colesterol
- Frequência cardíaca máxima
- Angina induzida por exercício
- Entre outras variáveis clínicas

A variável alvo é a coluna `target`, que indica:
- **1:** Doença cardíaca presente
- **0:** Doença cardíaca ausente

## Tecnologias Utilizadas
- **Python**
- **Pandas** (manipulação de dados)
- **NumPy** (operações numéricas)
- **Scikit-learn** (modelo de regressão logística e métricas)
- **Matplotlib** & **Seaborn** (visualização de dados)

## Etapas do Projeto
1. **Análise Exploratória dos Dados**
   - Visualização das variáveis
   - Verificação de dados faltantes (nenhum valor ausente foi encontrado)
  
2. **Pré-processamento**
   - Padronização das variáveis numéricas usando `StandardScaler`
   - Separação entre features e variável alvo

3. **Divisão dos Dados**
   - Separação em conjunto de treino (90%) e teste (10%) com `train_test_split`
  
4. **Treinamento do Modelo**
   - Utilização do modelo **LogisticRegression** do Scikit-learn

5. **Avaliação**
   - Matriz de Confusão
   - Relatório de Classificação (Precision, Recall, F1-Score)
   - Acurácia

## Resultados
O modelo apresentou bons resultados para um primeiro projeto, destacando:
- Acurácia: **85%**
- F1-Score: **84%**
- Curva ROC indicando boa capacidade de separação entre classes

## Melhorias Futuras
- Validação cruzada para uma avaliação mais robusta
- Implementação de técnicas para lidar com classes desbalanceadas
- Ajuste de hiperparâmetros para melhorar a performance
- Comparação com outros algoritmos de classificação (Random Forest, SVM)

---

Este projeto marca o início da minha jornada na área de Ciência de Dados. Fique à vontade para contribuir ou deixar sugestões! 😊
