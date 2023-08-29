# Prevendo preços de imóveis 
- Vamos trabalhar em um sistema preditivo para prever preços de imóveis na região do Airbnb Rio de Janeiro
- Este é um projeto completo de Ciências de Dados. Do carregamento ao deploy
- Os dados eu peguei deste link no Kaggle= https://www.kaggle.com/datasets/allanbruno/airbnb-rio-de-janeiro?resource=download

## 🤔 Objetivo
- Criar um sistema na qual tanto o ofertante do imóvel e o cliente possa usar
- O ofertande poderá saber o preço ideal na qual deve cobrar
- O cliente poderá fazer um comparativo do imóvel na qual ele estar analisando com os demais ofertados

## ⚙ Etapas do projeto
- Carregamento dos dados
- Limpeza dos dados
- Análise Exploratória
- Pré-processamento
- Modelagem Preditiva
- Deploy do Modelo escolhido

## 📌 Solução
- No carregamento dos dados, utilizo a biblioteca pathilb para pegar os arquivos CSV
- Na limpeza dos dados, realizo remocão de features, altero os tipos de dados, removo valores duplicados e trato valores ausentes
- Na análise Exploratória, realizo análise descritiva e análise estatítica, com uso de diversoss gráficos 
- No pré-processamento aplico técnicas de enconding utilizando o One-hot-Enconding
- Na nossa modelagem preditiva testos 3 modelos
  
        Regressão Linear
        Ramdom Forest
        Extra Trees
  O escolhido com base no desempenho das métricas estatítica foi o *Extra Trees*
  
- Para fazer o deploy criei um arquivo de python para isso, e utilizo a biblioteca streamit
