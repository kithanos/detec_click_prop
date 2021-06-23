# detec_click_prop
Detecção de cliques falsos em propagandas

Projeto: Detecção de Fraudes no Tráfego de Cliques em Propagandas de Aplicações Mobile
Autor: Lucas Kitano
GitHub: https://github.com/kithanos

Este projeto é parte integrante do curso Big Data Analytics com R e Microsoft Azure Machine Learning
da Formação Cientista de Dados da DataScience Academy (https://www.datascienceacademy.com.br)

O arquivo "Deteccao_Fraude_Clicks.R" contém o script em R, já o arquivo "Deteccao_Fraude_Clicks.Rmd" é
o R MarkDown para geração do relatório PDF "Deteccao_Fraude_Clicks.Rmd", para a sua reprodução é necessário 
possuir o MikTex instalado: https://miktex.org/

Além disso, para a reprodução do script em R, são necessárias as seguites bibliotecas:

library(sqldf)
library("ggplot2")
library("dplyr")
library(ROSE)
library(C50)
library(caret)

O Dataset de teste está localizado na pasta /datasets, enquanto o dataset completo original (~7,6 GB) pode
ser baixado na página do Kaggle (https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data)
arquivo "train.csv"
