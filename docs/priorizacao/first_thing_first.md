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
|Tipo|Identificação|Requisito|Prioridade|
|----|-------------|---------|----------|
|Não Funcional| **RNF6** | Ser prático e intuitivo |1,466|
|Não Funcional| **RNF8** | Ser objetivo | 1,128 |
|Não Funcional| **RNF2** | Ter acesso rápido e eficiente aos documentos | 1,047 |
|Não Funcional| **RNF1** | Ter acessibilidade | 0,950 |
|Funcional    | **RF14** | Ter sistema de notificação ao receber multa | 0,920 |
|Não Funcional| **RNF7** | Ser minimalista | 0,782 |
|Funcional    | **RF9** | Fazer logout na aplicação | 0,718 |
|Não Funcional| **RNF5** | Centralizar o máximo de documentos relacionados ao veículo possível | 0,705 |
|Funcional    | **RF7** | Checar quantidades de pontos da CNH | 0,697 |
|Funcional    | **RF3** | Ter acesso a versão digital da CNH | 0,689|
|Não Funcional| **RNF3** | Desburocratizar demandas relativas a DETRAN e DENATRAN | 0,647 |
|Não Funcional| **RNF9** | Possuir recursos off-line | 0,614 |
|Funcional    | **RF23** | Declarar motorista usual | 0,598  |
|Funcional    | **RF20** | Declarar o real infrator | 0,596  |
|Não Funcional| **RNF10** | Ser responsivo | 0,574 |
|Funcional    | **RF4** | Ter acesso a versão digital do CRLV | 0,557 |
|Funcional    | **RF17** | Gerar boleto bancário para pagamento de multas | 0,549|
|Não Funcional| **RNF4** | Ser compatível com todos dispositivos disponíveis no mercado | 0,509 |
|Funcional   | **RF18** | Recorrer a multas | 0,467 |
|Não Funcional| **RNF11**	|Ser seguro	| 0,464 |
|Funcional    | **RF2** | Ter acesso às multas do seu veículo | 0,429 |
|Funcional    | **RF21** | Ter sistema de notificação quando se aproximar da validade da CNH | 0,421 |
|Funcional    | **RF8** | Cadastro na aplicação | 0,408 |
|Funcional    | **RF15** | Ter detalhes sobre a situação perante ao departamento de trânsito | 0,389 |
|Funcional    | **RF16** | Ver quais dispositivos estão logados | 0,383 |
|Funcional    | **RF19** | Validar documentos | 0,382 |
|Funcional    | **RF12** | Se informar sobre o detran/denatran | 0,361 |
|Funcional    | **RF22** | Marcar vistorias | 0,344 |
|Funcional    | **RF13** | Ter dados detalhados de cada veículo | 0,330 |
|Funcional    | **RF11** | Excluir documentos | 0,297 |
|Funcional    | **RF6** | Poder marcar a renovação da CNH | 0,295 |
|Funcional    | **RF1** | Ter login integrado com o sistema GOV.br | 0,286 |
|Funcional    | **RF24** | Ter serviço de mensagens diretas para se comunicar com atendentes do DETRAN em caso de necessitar de suporte | 0,262 |
|Funcional    | **RF25** | Ter acesso a campanhas de segurança do trânsito do Denatran | 0,258 |
|Funcional    | **RF5** | Ter todas as informações dos documentos | 0,156 |
|Funcional    | **RF10** | Gerenciar documentos | 0,129 |  


## Bibliografia

> First Things First: Prioritizing Requirements. E.Wiegers, Karl. Disponível em: https://www.processimpact.com/articles/prioritizing.pdf Acesso em 11 de março de 2020

## Versionamento

|Data|Versão|Descrição|Autor|
|----|------|---------|-----|
|10/03/2021|0.1|Criação da planilha com os requisitos|Daniel Porto|
|11/03/2021|1.0|Primeiros passos na estruturação do documento|Estevão Reis|
|11/03/2021|2.0|Remodelando estrutura: aprimoramento da introdução, adição da bibliografia e descrição melhor definida da metodologia|Sérgio Cipriano|