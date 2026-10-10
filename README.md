# Reprodução: Does the Election of a Female Leader Clear the Way for More Women in Politics? (Baskaran & Hessami, 2018)

Este repositório contém o código em R (`.Rmd`) referente à replicação empírica do artigo de Baskaran e Hessami (2018), publicado no *American Economic Journal: Economic Policy*. Trata-se de um exercício prático desenvolvido para a disciplina de Microeconometria do curso de mestrado em Economia (PPGE-UFF), ministrado pela professora Daniele Carusi no segundo semestre de 2026.

## Objetivo
Avaliar se a eleição acirrada de uma prefeita mulher gera um efeito causal positivo (medido pelo *rank improvement*) na posição de candidatas ao conselho municipal em listas abertas, utilizando a estratégia de **Regressão Descontínua (RDD / *Regression Discontinuity Design*)**.

## Requisitos
Para compilar o relatório e rodar o script adequadamente, certifique-se de ter as seguintes bibliotecas instaladas no R:
```R
install.packages(c("haven", "sandwich", "rdrobust"))
