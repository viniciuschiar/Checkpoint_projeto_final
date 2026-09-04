# Desafio Final — Análise de Dados de Energia
# Vinicius Sanches Chiarle RM:568846  Mateus Felipe Curtale Serafim RM:571129
## Sobre o projeto

Este projeto foi desenvolvido como parte do Desafio Final de Análise de Dados, com o objetivo de aplicar conceitos de programação, análise de dados e visualização utilizando dados reais disponibilizados publicamente.

A atividade utiliza dados de carga elétrica do Sistema Interligado Nacional (SIN), obtidos por meio da API pública do Operador Nacional do Sistema Elétrico (ONS).

A análise foi realizada utilizando Python, com foco na organização dos dados, criação de indicadores, filtros, visualizações e interpretação dos resultados.

## Objetivo

O objetivo principal do projeto é analisar o comportamento da carga de energia elétrica em uma determinada região durante um período específico, identificando padrões, variações e períodos de maior demanda.

A atividade também busca desenvolver habilidades de:

Coleta de dados por API;
Manipulação de dados com Python;
Criação e tratamento de DataFrames;
Cálculo de indicadores estatísticos;
Filtragem e seleção de dados;
Criação de gráficos;
Interpretação de resultados;
Comunicação dos resultados de uma análise de dados.
## Fonte dos dados

Os dados utilizados neste projeto são provenientes do Operador Nacional do Sistema Elétrico (ONS), por meio de sua plataforma de dados abertos.

ONS — Dados Abertos

Portal oficial:

https://dados.ons.org.br/

Dataset utilizado

Carga Verificada

https://dados.ons.org.br/dataset/carga-energia-verificada

API utilizada

A coleta dos dados foi realizada por meio da API pública de Carga Verificada:

https://apicarga.ons.org.br/prd/cargaverificada

Os dados são públicos e disponibilizados pelo ONS para consulta e utilização em análises.

## Período e região analisados

Para a análise apresentada no projeto, foram considerados dados referentes à:

Região/área: SP — São Paulo
Data inicial: 01/08/2025
Data final: 07/08/2025

O período foi utilizado para observar o comportamento da carga elétrica e realizar as análises propostas na atividade.

## Tecnologias utilizadas

O projeto utiliza as seguintes tecnologias:

Python
Jupyter Notebook
Google Colab
Pandas
Matplotlib
Seaborn
SymPy
API REST
Orange Data Mining
Estrutura do projeto
desafio-final-energia-ons/
│
├── README.md
│
├── Desafio_Final_Energia_ONS_API_Final.ipynb
│
└── workflow_01.ows
Arquivos

Desafio_Final_Energia_ONS_API_Final.ipynb

Notebook principal contendo a coleta dos dados, tratamento, cálculos, análises, gráficos e interpretações.

workflow_01.ows

Workflow utilizado para a análise dos dados no Orange Data Mining.

README.md

Documento com a descrição do projeto, metodologia e fontes dos dados utilizados.

## Metodologia

O desenvolvimento da atividade segue as seguintes etapas:

## 1. Coleta dos dados

Os dados são obtidos diretamente da API pública do ONS.

A requisição utiliza os parâmetros necessários para consultar os dados de carga verificada referentes ao período e à região analisada.

## 2. Criação do DataFrame

Após a obtenção dos dados, as informações são organizadas em um DataFrame utilizando a biblioteca Pandas.

Essa estrutura permite realizar consultas, filtros, cálculos e manipulações dos dados.

## 3. Exploração dos dados

São realizadas verificações iniciais para compreender a estrutura do conjunto de dados, incluindo:

Quantidade de registros;
Colunas disponíveis;
Tipos de dados;
Valores ausentes;
Valores mínimos e máximos;
Características gerais dos dados.
## 4. Indicadores

São calculados indicadores estatísticos para compreender o comportamento da carga, incluindo:

Carga mínima;
Carga máxima;
Carga média;
Mediana;
Amplitude;
Identificação de períodos de maior demanda.
## 5. Filtros e DataFrames derivados

São criados filtros para selecionar registros de acordo com determinados critérios de carga.

A partir desses filtros são construídos DataFrames derivados, permitindo analisar situações específicas dentro do período estudado.

## 6. Percentuais

Também são calculados percentuais para avaliar a participação de determinados períodos ou condições em relação ao conjunto total de dados.

## 7. Visualização

Os dados são representados graficamente utilizando ferramentas de visualização em Python.

Os gráficos auxiliam na identificação de:

Variações da carga;
Picos de demanda;
Períodos de menor demanda;
Tendências ao longo do período analisado.
## 8. Interpretação

Após os cálculos e visualizações, os resultados são interpretados de forma a relacionar os valores encontrados com o comportamento da carga elétrica.

Resultados esperados

A análise busca identificar o comportamento da demanda de energia durante o período selecionado, destacando principalmente:

Momentos de maior consumo;
Momentos de menor consumo;
Variações da carga;
Média de carga no período;
Pico de demanda;
Diferenças entre os períodos analisados.

Os valores e gráficos finais podem ser consultados diretamente no notebook do projeto.
