# Predição da Gravidade de Acidentes de Trânsito

Este projeto tem como objetivo desenvolver um modelo preditivo para classificar a gravidade de acidentes de trânsito em áreas urbanas, utilizando variáveis temporais, operacionais e geográficas. A solução visa apoiar políticas públicas de prevenção, planejamento urbano e construção de sistemas de alerta em tempo real, contribuindo para cidades mais inteligentes e seguras.

## Objetivo

Classificar acidentes como graves ou não graves com base em dados como tipo de veículo envolvido, fatores contribuintes, horário, dia da semana, bairro e outras características contextuais. O modelo pode ser utilizado por prefeituras, Detrans ou plataformas urbanas para antecipar riscos e direcionar ações preventivas.

## Metodologia

1. Pré-processamento:
   - Combinação e transformação de colunas de data/hora
   - Criação de variáveis temporais (hora, dia da semana, mês, ano)
   - Remoção de colunas com alta taxa de nulos e variáveis irrelevantes
   - Tratamento de valores ausentes e registros duplicados

2. Engenharia de atributos:
   - Codificação de variáveis categóricas com OneHotEncoder
   - Balanceamento de classes com SMOTE

3. Modelagem:
   - Rede Neural com Keras (feedforward)
   - Regularização com L2, dropout e early stopping
   - Avaliação com classification report, matriz de confusão e ROC AUC

## Bibliotecas Utilizadas

pandas  
numpy  
matplotlib  
seaborn  
plotly  
scikit-learn  
imblearn  
tensorflow  
statsmodels

## Execução

O notebook está com os resultados executados e comentados.  
Pode ser aberto diretamente em qualquer ambiente Jupyter ou Google Colab para exploração e adaptação.

## Estrutura

predicao-acidentes-graves/  
├── notebooks/  
│   └── Predicao_acidentes_graves.ipynb  
├── README.md  
├── requirements.txt  
└── LICENSE

## Autor

Heitor Tonet  
Engenheiro de Controle e Automação e Cientista de Dados. Atua em projetos voltados para segurança urbana, mobilidade inteligente, manutenção preditiva e aprendizado de máquina aplicado a sistemas reais.

## Licença

Este projeto está sob a licença MIT.
