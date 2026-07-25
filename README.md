# Portfólio — Ciência de Dados e Machine Learning

Este repositório reúne projetos de análise de dados e machine learning, com foco em aplicar boas práticas de todo o pipeline: entendimento e tratamento de dados, engenharia de features, modelagem, avaliação crítica de resultados e comunicação clara das decisões tomadas.

Mais do que reproduzir soluções prontas, o objetivo de cada projeto aqui é questionar as escolhas metodológicas ao longo do caminho — testando hipóteses, comparando abordagens alternativas e validando se cada decisão (tratamento de dado, engenharia de feature, escolha de algoritmo) realmente melhora o resultado final.

## Projetos

### 🏠 [Predição de Preços de Casas](./Predição_de_Preços_de_Casas.ipynb)
Projeto de regressão sobre o dataset Ames Housing, que replica e expande um notebook de referência do Kaggle. Inclui:
- Investigação e correção de inconsistências em dados faltantes (garagem, porão)
- Identificação e correção de vazamento de dado (data leakage) no escalonamento das features
- Comparação controlada entre duas abordagens de engenharia de features (com e sem remoção de multicolinearidade e termos polinomiais), testando 8 algoritmos de regressão diferentes
- Conclusão baseada em evidência sobre o peso relativo de tratamento de dados, engenharia de features e escolha de algoritmo no resultado final

### 💳 [Detecção de Fraude em Cartão de Crédito](./Detecção_de_Fraude_de_cartão_de_crédito.ipynb)
Projeto de classificação utilizando a metodologia SEMMA (Sample, Explore, Modify, Model, Assess), com um `RandomForestClassifier` para detectar transações fraudulentas. Compara abordagens com e sem undersampling para lidar com o desbalanceamento de classes, avaliando o impacto de cada uma na performance do modelo.

## Tecnologias utilizadas
Python, pandas, scikit-learn, XGBoost, seaborn/matplotlib, Jupyter Notebook
