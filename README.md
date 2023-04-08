# Portfólio R

Este repositório reúne projetos relacionados à Ciência de Dados desenvolvidos em linguagem R para fins acadêmicos, profissionais e de auto-aprendizado.
Os projetos são apresentados como Repositórios, Notebooks Kaggle, Pacotes R, documentos R Markdown, Dashboards Shiny e Artigos científicos.

## Visualização de Dados

- [Visualização dinâmica de dados de casos de dengue no estado do Ceará](https://rubensocj.shinyapps.io/dengue-ce/)  
**Descrição:** Ferramenta interativa para visualização de dados de casos de dengue nos municípios do estado do Ceará, obtidos da Secretaria da Saúde (SESA) pelo portal IPECEDATA.  
**Tipo:** Dashboard Shiny  
**Técnicas:** Visualização de Dados  
**Pacotes:** shiny, shinydashboard, shinyjs, dplyr, ggplot2, gridExtra, treemapify, geobr

- [Online ML Classifier](https://rubensocj.shinyapps.io/online-ml-classifier/)  
**Descrição:** Ferramenta online para classificação estatística usando diversos algoritmos de aprendizado de máquina supervisionado, tais como Support Vector Regression, Naive Bayes, k-Nearest Nerighbors, Decision Trees e Random Forest.  
**Tipo:** Dashboard Shiny  
**Técnicas:** Visualização de Dados, Classificação  
**Pacotes:** shiny, shinyjs, shinythemes, shinyBS, DT, e1071, rpart, randomForest

## Desenvolvimento

- [hidrotsbr: Process hydrological time series data of Brazil](https://github.com/rubensocj/hidrotsbr)  
**Descrição:** O pacote fornece ferramentas para automatizar o processo de importação, limpeza e tratamento de dados de diferente serviços hidrológicos do Brasil. Atualmente, o pacote contém funções para dados do Serviço Geológico do Brasil (CPRM) e da Funcação Cearense de Meteorologia (FUNCEME)  
**Tipo:** Pacote R  
**Técnicas:** Limpeza de Dados  
**Pacotes:** diplyr, tidyr  

## Análise de Dados

- [Análise de dados da empresa Bellabeat](https://www.kaggle.com/code/rubensocj/an-lise-de-dados-da-empresa-bellabeat)  
**Descrição:** Uma empresa de tecnologia de produtos voltados à saúde para mulheres deseja usar análise de dados para identificar oportunidades de crescimento. Estudo de caso realizado durante o curso Google Data Analytics.  
**Tipo:** Notebook Kaggle  
**Técnicas:** Limpeza de Dados, Visualização de Dados, Análise de Correlação  
**Pacotes:** dplyr, ggplot2, ggpubr, corrplot, lubridate

- [Violence against Women: Exploratory Data Analysis](https://www.kaggle.com/rubensocj/violence-against-women-exploratory-data-analysis)  
**Descrição:** Análise Exploratória de Dados de uma pesquisa realizada em países africanos, asiáticos e sul-americanos abordando as atitudes e as justificativas para cometer atos de violência contra as mulheres.  
**Tipo:** Notebook Kaggle  
**Técnicas:** Limpeza de Dados, Visualização de Dados, Análise Exploratória de Dados  
**Pacotes:** dplyr, ggplot2

## Análise de Séries Temporais

- [Simulação de valores ausentes em séries temporais de precipitação para avaliação de métodos de imputação](https://github.com/rubensocj/arquivo-R/blob/main/src/CunhaJuniorFirmino2022_Climatologia.pdf)  
**Descrição:** Comparação de métodos multivariados de imputação em séries temporais de precipitação pluviométrica usando simulação.  
**Tipo:** Artigo  
**Técnicas:** Imputação, Visualização de Dados, Análise de Correlação, Regressão Linear  
**Pacotes:** neuralnet, imputeTestbench

- [Preenchimento de falhas em séries temporais de níveis de águas subterrâneas usando métodos univariados](https://github.com/rubensocj/arquivo-R/blob/main/src/CunhaJunior2022_ENREHSE.pdf)  
**Descrição:** Comparação de métodos univariados de imputação em séries temporais de níveis de águas subterrâneas usando simulação.  
**Tipo:** Artigo  
**Técnicas:** Imputação, Interpolação, Decomposição, Visualização de Dados  
**Pacotes:** imputeTS, imputeTestbench

- [Combinação de preditores de séries temporais](https://rpubs.com/rubensocj/combination-of-forecasts)  
**Descrição:** Técnicas de ensemble são usadas para previsão de uma série temporal do número de mortes decorrentes de doenças no pulmão registradas no Reino Unido.  
**Tipo:** R Markdown  
**Técnicas:** ARIMA, ETS, Ensemble, Previsão, Visualização de Dados  
**Pacotes:** forecast

## Aprendizado de Máquina

- [Previsão de preços de imóveis usando técnicas avançadas de regressão](https://www.kaggle.com/code/rubensocj/regress-o-lasso-svr-e-random-forest)  
**Descrição:** Aplicação de técnicas Regressão LASSO, Support Vector Regression (SVR) e Random Forest (RF) para previsão dos preços de imóveis em Ames, Iowa, Estados Unidos.  
**Tipo:** Notebook Kaggle  
**Técnicas:** Regressão, Previsão, Análise Exploratória de Dados, LASSO, Support Vector Regression, Random Forest  
**Pacotes:** e1071, randomForest, glmnet, dplyr, corrplot

- [Implementação de redes neurais usando o algoritmo Extreme Learning Machine em R](https://github.com/rubensocj/extreme-learning-machine)  
**Descrição:** Implementação de variações do algoritmo Extreme Learning Machine para treinamento de Redes Neurais Artificiais. Escrito para auto-aprendizado.  
**Tipo:** Repositório  
**Técnicas:** Extreme Learning Machine, Redes Neurais Artificiais  
**Pacotes:** base, MASS

## Modelagem Estatística

- [Análise da associação entre incidência de dengue e
pluviosidade na Região Metropolitana do Cariri, Ceará](https://github.com/rubensocj/arquivo-R/blob/main/src/CunhaJunior2022_GaiaScientia.pdf)  
**Descrição:** Modelos Lineares Generalizados são usados para analisar a associação entre casos de dengue e chuva na Região Metropolitana do Cariri, Ceará.  
**Tipo:** Artigo  
**Técnicas:** Previsão, Modelos Lineares Generalizados, Testes de Normalidade, Distribuição Binomial Negativa, Análise de Correlação, Correlação-cruzada, Visualização de Dados  
**Pacotes:** stats, MASS, nortest

- [Análise de Probit para cálculo de concentrações letais](https://rpubs.com/rubensocj/probit)  
**Descrição:** Um modelo Probit é usado para o cálculo de concentrações letais de cloreto de cobre e cloreto de zinco em espécies de nematoides a partir de testes de toxicidade. Estudo de caso usando dados públicos para aplicar códigos desenvolvidos para uma análise particular.  
**Tipo:** R Markdown  
**Técnicas:** Modelos Lineares Generalizados, Modelo Probit, Distribuição de Bernoulli, Distribuição Binomial  
**Pacotes:** stats
