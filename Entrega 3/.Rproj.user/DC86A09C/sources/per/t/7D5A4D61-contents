setwd("~/PUCRIO/Verão/Estatística/Aulas de Data Science/Entregas data science/entrega 3")
library(ggplot2)
library(tidyverse)
base = read.csv('base.csv', encoding = "UTF-8" )
colnames(base)[c(1,7)] = c('rank', 'Pontos_de_liga')


ggplot(base, aes(Vitórias, Torneios_Jogados)) +
  geom_point(aes(size = Pontos_de_liga), color = '#E69F00',alpha = 0.4) +
  theme(legend.position="top")

ggplot(base, aes(rank, Pontos_de_liga)) +geom_point(color = '#56B4E9')+
  geom_line(color = '#56B4E9')+
  theme_minimal()
