# Sobre

Aqui eu pontuo, de forma geral e pouco estruturada, os tópicos que serão abordados no curso. A ideia é condensar o todo e depois repartir em aulas.

## Pré-requisitos

- teóricos: matemática básica
    - funções e estatística
- práticos: Python e alguma familiaridade com as bibliotecas Pandas e Numpy (bônus: matplotlib pra visualização)
- momento para mostrar como instalar dependências?

## Definição e exemplos

- definição formal: o que é
    - conjunto de dados sucessivo (sequência de números), dependentes do tempo e amostrados em intervalos fixos
- notação matemática e visualização
- características principais
    - dependência: a relação entre amostras próximos, sequenciais
	- estacionariedade: com base nos dois descritores estatísticos básicos (média e variância), pergunta-se: a série tende a mudar muito?
- áreas de aplicação e exemplos
    - economia, processamento de sinais, metereologia, controle, e tudo mais que se preocupe com o tempo

## Tipos de aplicação

- análise: extração de características significativas
    - componentes e suas tendências, além de padrões 
- predição: ver o futuro com base em dados passados

## Componentes

- autocorrelação
- quais são: base, tendência, sazonalidade, ciclo, aleatoriedade/ruído/resíduo/erro
- composições: aditivas, multiplicativas
- decomposição: como extrair e visualizar cada componente

## Classificação

- estacionária
- não-estacionária
- testes de estacionariedade
- plot de Dicker-Fuller

## Manipulações básicas

- filtragens
    - média móvel
    - diferenciação
    - suavização exponencial
- autorregressão
- predição simples
- LOESS (regressão localizada)
- ARIMA
- SARIMA

## Detecção de Anomalias

- LOESS + resíduo
- CART: classification and regression trees
- detecção por predição
- clusterização

## Tópicos avançados

- SARIMAX, VARMAX, CNN, LSTM, RESNET, autoencoders para detecção de anomalias
