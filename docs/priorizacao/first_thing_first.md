# First Things First

## Introdução

&emsp;&emsp; First Things First é uma técnica de priorização onde há um levantamento de dados de benefícios, custos e riscos relacionados a cada requisito. Ao utilizar essa técnica, nosso objetivo é estabelecer uma certa ordem de prioridade em relação à implementação das funcionalidades, tendo como base os fatores que impactam na disponibilização delas aos usuários finais.

## Metodologia

&emsp;&emsp; Nessa prática de priorização, contruímos uma tabela de forma que equilibrou os posionamentos do cliente e do desenvolvedor. Para isso, seguimos os seguintes passos:

- __Passo 1:__ Listagem de todos os requisitos, retirando aqueles dependentes de outro(s) requisito(s).
- __Passo 2:__ Estimativa do benefício relativo que cada funcionalidade fornece ao usuário final e ao cliente (classificada de 1 à 9, sendo 1 menos significativo e 9 mais significativo).
- __Passo 3:__ Estimativa da penalidade em decorrência da não aplicação ou atraso da aplicação do requisito (classificada de 1 à 9, sendo 1 menor penalidade e 9 maior penalidade). 
- __Passo 4:__ Estimativa do custo relativo de implementação de cada requisito (variando de 1 à 9, sendo 1 o menor custo e 9 o maior custo).
- __Passo 5:__ Estimativa do grau relativo ao risco de aplicação para cada requisito (variando de 1 à 9, sendo 1 o menor risco e 9 o maior risco).
- __Passo 6:__ Cálculos:
    - A Coluna valor total é a soma do (Benefício Relativo * Peso Relativo + Penalidade Relativa * Peso Relativo).
    - Calcular a prioridade para cada requisito usando: valor % / (custo % * Peso custo + risco % * Peso Risco).
- __Passo 7:__ Ordenação da lista em ordem decrescente de prioridade.

&emsp;&emsp; Os passos são uma versão adaptada do material dos materiais utilizados como estudo, a ideia era definir um modelo que se adequasse ao nosso modelo de trabalho. 

## Aplicação da técnica no projeto

Para esse método de priorização, utilizamos os requisitos elicitados nos documentos de brainstorming, questionário e introspecção.

## Bibliografia

> First Things First: Prioritizing Requirements. E.Wiegers, Karl. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf Acesso em 11 de março de 2020

## Versionamento

|Data|Versão|Descrição|Autor|
|----|------|---------|-----|
|10/03/2021|0.1|Criação da planilha com os requisitos|Daniel Porto|
|11/03/2021|1.0|Primeiros passos na estruturação do documento|Estevão Reis|
|11/03/2021|2.0|Remodelando estrutura: aprimoramento da introdução, adição da bibliografia e descrição melhor definida da metodologia|Sérgio Cipriano|