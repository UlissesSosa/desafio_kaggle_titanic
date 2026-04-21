# Titanic Survival Prediction - Kaggle Challenge

## Descrição
Análise preditiva de sobrevivência do Titanic usando Decision Tree Classifier.

## Resultados
- Acurácia no treino: 82.7%
- Acurácia no teste: 96.7%
- O arquivo de submissão para o Kaggle está em: `sobreviventes.csv`
- Este arquivo contém 418 predições (PassengerId e Survived) geradas pelo modelo Decision Tree.

## Pontuação no Kaggle
- Public Score: 0.77511

## Features utilizadas
- Sexo (One-Hot Encoding)
- Classe (Pclass)
- Porto de embarque (Embarked)
- Idade
- Número de irmãos/cônjuges (SibSp)
- Número de pais/filhos (Parch)
- Tarifa (Fare)

## Como executar
1. Instalar dependências: `pip install -r requirements.txt`
2. Executar notebook: `jupyter notebook notebooks/kaggle_titanic.ipynb`