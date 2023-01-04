# Portfolio R

Este repositório reúne projetos relacionados à Ciência de Dados desenvolvidos em linguagem R com fins acadêmicos, profissionais e de auto-aprendizado.
Os projetos são apresentados como Repositórios, Notebooks Kaggle, documentos R Markdown no RPubs, Dashboards Shiny e Artigos científicos publicados.

## Análise de Dados

- [Análise de dados da empresa Bellabeat](https://www.kaggle.com/code/rubensocj/an-lise-de-dados-da-empresa-bellabeat)  
**Descrição:** Uma empresa de tecnologia de produtos voltados à saúde para mulheres deseja usar análise de dados para identificar oportunidades de crescimento. Estudo de caso realizado durante o curso Google Data Analytics.  
**Tipo:** Notebook Kaggle.  
**Técnicas:** Limpeza de Dados, Visualização de Dados, Análise de Correlação.  
**Pacotes:** `tidyverse`, `ggpubr`, `corrplot`, `lubridate`.

- [Processamento de dados da Fundação Cearense Meteorologia (FUNCEME)](https://github.com/rubensocj/series-FUNCEME)  
**Descrição:** Automatiza o processo de importação, limpeza e organização de dados de postos pluviométricos do Estado do Ceará.  
**Tipo:** Repositório.  
**Técnicas:** Limpeza de Dados.  
**Pacotes:** `diplyr`, `tidyr`.  

- [Processamento de dados da Rede Integrada de Monitoramento de Águas Subterrâneas (RIMAS)](https://github.com/rubensocj/series-RIMAS)  
**Descrição:** Automatiza o processo de importação, limpeza e organização de dados de poços de monitoramento do Serviço Geológico do Brasil (CPRM).  
**Tipo:** Repositório.  
**Técnicas:** Limpeza de Dados.  
**Pacotes:** `diplyr`.  

## Análise de Séries Temporais

- [Simulação de valores ausentes em séries temporais de precipitação para avaliação de métodos de imputação](https://github.com/rubensocj/arquivo-R/blob/main/src/CunhaJuniorFirmino2022_Climatologia.pdf)  
**Descrição:** Comparação de métodos multivariados de imputação em séries temporais de precipitação pluviométrica usando simulação.  
**Tipo:** Artigo.  
**Técnicas:** Imputação, Visualização de Dados, Análise de Correlação, Regressão Linear.  
**Pacotes:** `neuralnet`, `imputeTestbench`.

- [Preenchimento de falhas em séries temporais de níveis de águas subterrâneas usando métodos univariados](https://github.com/rubensocj/arquivo-R/blob/main/src/CunhaJunior2022_ENREHSE.pdf)  
**Descrição:** Comparação de métodos univariados de imputação em séries temporais de níveis de águas subterrâneas usando simulação.  
**Tipo:** Artigo.  
**Técnicas:** Imputação, Interpolação, Decomposição, Visualização de Dados.  
**Pacotes:** `imputeTS`, `imputeTestbench`.

- [Combinação de preditores de séries temporais](https://rpubs.com/rubensocj/combination-of-forecasts)  
**Descrição:** Técnicas de ensemble são usadas para previsão de uma série temporal do número de mortes decorrentes de doenças no pulmão registradas no Reino Unido.  
**Tipo:** R Markdown.  
**Técnicas:** ARIMA, ETS, Ensemble, Previsão, Visualização de Dados.  
**Pacotes:** `forecast`.

## Aprendizado de Máquina

- [Implementação de redes neurais usando o algoritmo Extreme Learning Machine em R](https://github.com/rubensocj/extreme-learning-machine)  
**Descrição:** Implementação de variações do algoritmo Extreme Learning Machine para treinamento de Redes Neurais Artificiais. Escrito para auto-aprendizado.  
**Tipo:** Repositório.  
**Técnicas:** Extreme Learning Machine, Redes Neurais Artificiais.  
**Pacotes:** `base`, `MASS`.

## Modelagem Estatística

- [Análise de Probit para cálculo de concentrações letais](https://rpubs.com/rubensocj/probit)  
**Descrição:** Um modelo Probit é usado para o cálculo de concentrações letais de cloreto de cobre e cloreto de zinco em espécies de nematoides a partir de testes de toxicidade. Estudo de caso usando dados públicos para aplicar códigos desenvolvidos para uma análise particular.  
**Tipo:** R Markdown.  
**Técnicas:** Modelos Lineares Generalizados, Modelo Probit, Distribuição de Bernoulli, Distribuição Binomial.  
**Pacotes:** `stats`.

- [Análise da associação entre incidência de dengue e
pluviosidade na Região Metropolitana do Cariri, Ceará](https://github.com/rubensocj/arquivo-R/blob/main/src/CunhaJunior2022_GaiaScientia.pdf)  
**Descrição:** Modelos Lineares Generalizados são usados para analisar a associação entre casos de dengue e chuva na Região Metropolitana do Cariri, Ceará.  
**Tipo:** Artigo.  
**Técnicas:** Previsão, Modelos Lineares Generalizados, Testes de Normalidade, Distribuição Binomial Negativa, Análise de Correlação, Correlação-cruzada, Visualização de Dados.  
**Pacotes:** `stats`, `MASS`, `nortest`.
