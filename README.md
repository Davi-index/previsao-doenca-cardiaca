# PREVISÃO DE DOENÇA CARDÍACA: UM CLASSIFICADOR DE RISCO COM REDES NEURAIS

Este projeto implementa uma Rede Neural para classificação automática da previsão de doenças cárdiacas a partir de estatisticas de hábitos dos pacientes
O objetivo é auxiliar no diagnóstico de previsão de doenças cardíacas (como hipertensão, insuficiência cardíaca e arritmias), reduzindo erros humanos e acelerando o processo, especialmente em locais com escassez de especialistas.
O documento inclui, de forma clara e bem definida:

🎯 Objetivo do Projeto&nbsp;&nbsp;&nbsp; - &nbsp;&nbsp;&nbsp;
📊 Descrição dos Dados&nbsp;&nbsp;&nbsp; - &nbsp;&nbsp;&nbsp;
⚙️ Pré-processamento&nbsp;&nbsp;&nbsp;

🧠 Modelo e Treinamento&nbsp;&nbsp;&nbsp; - &nbsp;&nbsp;&nbsp;
📈 Resultados&nbsp;&nbsp;&nbsp;- &nbsp;&nbsp;&nbsp;
Considerações finais e tecnologias utilizadas
##  Artigo

Os detalhes teóricos, metodologia, resultados completos e discussões adicionais estão descritos no artigo produzido durante o projeto:
O artigo passará por correções finalizará seu desenvolvimento até o momento de sua publicação
[**Acessar o artigo completo**](https://www.overleaf.com/read/gdytwjmphnmz#38d172) 

## Objetivo do Projeto

O objetivo principal deste projeto é desenvolver um modelo computacional capaz de prever a ocorrência de doença cardíaca em pacientes a partir de variáveis clínicas e demográficas.

O estudo busca:

Auxiliar na identificação precoce de indivíduos em risco;

Avaliar o desempenho de redes neurais na área da saúde;

Investigar o impacto do pré-processamento de dados na performance do modelo;

Fornecer subsídios para apoio à tomada de decisão clínica.

## Descrição dos Dados

O conjunto de dados utilizado é composto por informações clínicas e comportamentais relacionadas à saúde cardiovascular de pacientes. O dataset inclui variáveis numéricas e categóricas, como:

age: idade do paciente

sex: sexo biológico

cigsPerDay: número de cigarros consumidos por dia

totChol: colesterol total

sysBP / diaBP: pressão arterial sistólica e diastólica

BMI: índice de massa corporal

heartRate: frequência cardíaca

glucose: nível de glicose

TenYearCHD: variável alvo (0 = saudável, 1 = doença cardíaca)

O dataset foi carregado a partir de um arquivo CSV e analisado quanto à sua estrutura, presença de valores ausentes e distribuição estatística.

## Pré-Processamento dos Dados

O pré-processamento foi uma etapa essencial do projeto, uma vez que a qualidade dos dados impacta diretamente o desempenho do modelo.

As principais etapas realizadas foram:

Tratamento de Valores Ausentes

Variáveis numéricas: imputação pela média;

Variáveis categóricas: imputação pela moda.

## Tecnologias Utilizadas

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Google Colab
