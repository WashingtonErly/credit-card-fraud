# Credit Card Fraud Detection

Projeto de análise de dados e aplicação de técnicas estatísticas e de *Machine Learning* para identificação de possíveis fraudes em transações com cartão de crédito.

## Objetivo

Desenvolver e avaliar modelos de classificação capazes de identificar transações potencialmente fraudulentas.

O projeto será desenvolvido como parte do Trabalho de Conclusão de Curso (TCC) da pós-graduação em Machine Learning e Estatística USP/Esalq

## Etapas do projeto

- [ ] **1. Entendimento dos dados:** conhecer a base, as variáveis e a definição de fraude.
- [ ] **2. Análise exploratória:** investigar distribuições, relações entre variáveis e possíveis inconsistências.
- [ ] **3. Pré-processamento:** tratar valores ausentes, duplicidades e preparar as variáveis.
- [ ] **4. Análise estatística:** avaliar características das transações e diferenças entre classes.
- [ ] **5. Modelagem:** desenvolver modelos de classificação para detecção de fraudes.
- [ ] **6. Avaliação:** comparar os modelos utilizando métricas adequadas ao problema.
- [ ] **7. Conclusões:** interpretar os resultados, limitações e possibilidades de aplicação.

## Tecnologias

- Python 3.12
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Spyder
- Conda
- Git e GitHub

## Estrutura do projeto

```text
credit-card-fraud/
├── codigo/       # Scripts Python
├── dados/        # Bases de dados locais
├── notebooks/    # Análises exploratórias e experimentos
├── .gitignore    # Arquivos excluídos do versionamento
└── README.md     # Documentação do projeto
```

## Ambiente de desenvolvimento

O projeto utiliza um ambiente Conda isolado chamado `credit_fraud`, com Python 3.12.

Para ativar o ambiente:

```bash
conda activate credit_fraud
```

## Dados

As bases de dados utilizadas serão armazenadas localmente na pasta `dados/`.
A base de dados usada foi *Credit Card Fraud Detection* disponibilizada no Kaggle pelo link "https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud"

## Avaliação dos modelos

A avaliação deverá considerar métricas como:

- Precisão (*Precision*);
- Revocação (*Recall*);
- F1-score;
- Matriz de confusão;
- PR-AUC e, quando pertinente, ROC-AUC.

Como fraudes geralmente representam uma pequena parcela das transações, a análise não deverá se limitar à acurácia.

## Status

Projeto em fase de estruturação do ambiente e preparação dos dados.
