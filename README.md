# Predição do Campeonato Brasileiro por Monte Carlo

Projeto acadêmico desenvolvido na disciplina ME524 — Computação Aplicada à Estatística, da Universidade Estadual de Campinas (UNICAMP), em 2026. O trabalho utiliza simulações de Monte Carlo para estudar possíveis classificações finais do Campeonato Brasileiro de Futebol.

## Objetivos

- Estimar as probabilidades de título e rebaixamento das equipes;

- Analisar a pontuação final do campeão e os critérios de desempate;

- Avaliar a variabilidade das estimativas por meio de bootstrap;

- Implementar uma alteração no modelo para considerar o mando de campo e comparar os resultados.

## Dados

O projeto utiliza a base [`brasileirao_2026.csv`](brasileirao_2026.csv), com informações sobre as partidas realizadas e pendentes do Campeonato Brasileiro de 2026.

## Metodologia

A análise utiliza distribuições de Poisson para modelar o número de gols marcados e sofridos pelas equipes, com parâmetros estimados a partir dos resultados anteriores. Por meio de simulações de Monte Carlo, são gerados diferentes cenários para a classificação final do campeonato. Também é aplicado o método bootstrap para avaliar a variabilidade das estimativas e são comparados modelos com e sem ajuste para o mando de campo.

## Ferramentas

Linguagem: R

Pacotes: tidyverse

Métodos estatísticos: simulação de Monte Carlo e bootstrap

## Arquivos

- [`brasileirao_2026.csv`](brasileirao_2026.csv): base de dados com informações de todos os jogos Campeonato Brasileiro de 2026, para os jogos que ainda não haviam sido realizados, o número de gols nas partidas está vazio.

- [`ME524_Laboratorio1.pdf`](ME524_Laboratorio1.pdf): relatório do projeto, com a análise dos dados, a metodologia, os resultados e as conclusões.

- [`ME524_Laboratorio1.qmd`](ME524_Laboratorio1.qmd): código-fonte do projeto, incluindo a estimação dos parâmetros, as simulações de Monte Carlo, o bootstrap e a comparação entre os modelos.

## Autores

Nicole de Barros Silva

Gustavo Coimbra de Souza Teixeira

Sofia Moreira Marinho
