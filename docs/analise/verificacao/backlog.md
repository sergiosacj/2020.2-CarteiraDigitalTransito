# Verificação do Backlog
&emsp; &emsp;Este documento visa verificar o backlog de produto para detectar os erros e defeitos antes de finalizar o projeto.</br>
&emsp; &emsp;Para a verificação do backlog foi escolhida a estratégia de inspeção por checklist, por ser simples, objetiva e a mais eficaz em comparação às outras neste contexto.


## 1. Contexto
 - Técnica: Inspeção
 - Autores: Sérgio Cipriano e Enzo Gabriel
 - Revisores: Estevão Reis e Daniel Porto
 - Inspetores: Estevão Reis

 O documento verificado está disponível [aqui](https://requisitos-de-software.github.io/2020.2-CarteiraDigitalTransito/modelagem/backlog_do_produto/)
## 2. Checklist
### 2.1.Perguntas
| Número | Pergunta |
|:--:|--|
| 1 | Todas as informações necessárias estão presentes? |
| 2 | As informações são consistentes? |
| 3 | As informações são concisas? |
| 4 | Há apenas informações necessárias? | 
| 5 | Uso de linguagem compreensível e agradável ao público? |
| 6 | Possui rastreabilidade? | 
| 7 | O épico associado é coerente? |
| 8 | A ortografia está correta? |
| 9 | Possui ator coerente? |
|10 | Desejo e objetivo coerentes?|

### 2.2. Legenda
|Símbolo|Descrição|
|-------|---------|
|✔     | Contém   |
|✖     |Não Contém|

### 2.3. Resultados

|US  |1|2 |3|4 |5|6|7|8 |9|10
|----|-|--|-|--|-|-|-|--|-|--|
|US01|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US02|✔|✔|✔|✔|✔|✔|✔|✖|✔|✔ |
|US03|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US04|✖|✔|✔|✔|✖|✔|✔|✔|✔|✖ |
|US05|✔|✔|✖|✔|✔|✔|✔|✔|✔|✔ |
|US06|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US07|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US08|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US09|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US10|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US11|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US12|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US13|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US14|✔|✔|✖|✔|✔|✔|✔|✔|✔|✔ |
|US15|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US16|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |

|US  |1|2 |3|4 |5|6|7|8 |9|10 
|----|-|--|-|--|-|-|-|--|-|--|
|US17|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US18|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US19|✔|✔|✖|✔|✔|✔|✔|✔|✔|✔ |
|US20|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US21|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US22|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US23|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US24|✔|✔|✔|✔|✔|✔|✔|✔|✔|✖ |
|US25|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US26|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US27|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US28|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US29|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US30|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US31|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |
|US32|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |

## 3. Conclusão
### 3.1. Problemas Encontrados
#### US02:Realizar o login
##### Problemas 

8 - Erro de acentuação no Backlog: "Ter acesso as funcionalidades".
##### Possíveis soluções
 
8 - Mudar para "Ter acesso às funcionalidades".

#### US04:Realizar Logout

##### Problemas 
1 - Não é dito de onde é apagado os registros do usuário, se na base de dados do CDT ou se no aparelho onde se está utilizando o aplicativo</br>
5 - Uso expressão "registro de usuário" pode não ser claro para o usuário</br>
10 - Fazer o logout na aplicação não necessariamente apaga os registros do usuário
##### Possíveis soluções
Devido a incoerência entre desejo e objetivo, não será apontado soluções para os outros problemas.</br>
10 - Mudar DESEJO para "sair da conta"; e OBJETIVO para: "Impedir que outras pessoas acessem minha conta em meu aparelho"

#### US05: Acessar mensagens do sistema
##### Problemas 
3 - As expressões "acessar" e "ter acesso" levam a redundância.

##### Possíveis soluções
3 - Mudar DESEJO para "Visualizar as mensagens do sistema";

#### US14: Acessar CRLV dos veículos cadastrados
##### Problemas 
3 - As expressões "acessar" e "ter acesso" levam a redundância.

##### Possíveis soluções
3 - Mudar DESEJO para "Visualizar o CRLV do meu veículo cadastrado".

#### US19: Indicar o principal condutor
##### Problemas 
3 - A indicar "indicar" se repete em DESEJO e OBJETIVO, causando redundância.

##### Possíveis soluções
3 - Mudar DESEJO para "Definir o principal condutor de um veículo;

#### US24: Parar de compartilhar o CRLV
##### Problemas 
10 - Incoerência entre DESEJO e OBJETIVO

##### Possíveis soluções
10 - Mudar OBJETIVO para "Para ter controle de quem pode ter acesso ao CRLV do meu veículo";

### 3.2. Dados Percentuais
#### 3.2.1.Backlog do Produto
|US  |Porcentagem de Sucesso|
|----|-|
|US01|100%|
|US02|90%|
|US03|100%|
|US04|70%|
|US05|90%|
|US06|100%|
|US07|100%|
|US08|100%|
|US09|100%|
|US10|100%|
|US11|100%|
|US12|100%|
|US13|100%|
|US14|90%|
|US15|100%|
|US16|100%|
|US17|100%|
|US18|100%|
|US19|90%|
|US20|100%|
|US21|100%|
|US22|100%|
|US23|100%|
|US24|90%|
|US25|100%|
|US26|100%|
|US27|100%|
|US28|100%|
|US29|100%|
|US30|100%|
|US31|100%|
|US32|100%|

### 3.2.2.Perguntas
| Número | Pergunta |Porcentagem de Sucesso|
|:--:|--|---|
| 1 | Todas as informações necessárias estão presentes? |96,88%|
| 2 | As informações são consistentes? |100%|
| 3 | As informações são concisas? |90,63%|
| 4 | Há apenas informações necessárias? |100% |
| 5 | Uso de linguagem compreensível e agradável ao público? |96,88%|
| 6 | Possui rastreabilidade? | 100%|
| 7 | O épico associado é coerente? |100%|
| 8 | A ortografia está correta? |96,88%|
| 9 | Possui ator coerente? |100%|
|10 | Desejo e objetivo coerentes?|93,75%|



## 4. Acompanhamento
&emsp; &emsp; Ainda não foram feitas as correções necessárias.

## 5. Bibliografia

> - VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira - Engenharia de Requisitos: Software Orientado ao Negócio. Acesso em: 09 de Abril de 2021

## 6.Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 08/04/2021 | Criação do documento com os checklist em todas as histórias de usuário do Backlog | Estevão Reis |
| 2.0 | 11/04/2021 | Mudança de toda a organização e layout do documento e verificação da US01 até a US16| Estevão Reis|
| 3.0 | 11/04/2021 | Mudança na organização e layout dos Resultados| Estevão Reis|
| 4.0 | 11/04/2021 | Mudanças nos critérios 9 e 10 e nova verificação de todos os US| Estevão Reis|
| 5.0 | 11/04/2021 | Correção no título, correções ortográficas em todo documento, mudança na introdução, inserção do subtópico "Perguntas" em "Checklist" e mudança do nome da coluna "Questões" para "Perguntas"| Estevão Reis|
| 6.0 | 11/04/2021 | Inserção dos Dados percentuais | Estevão Reis|
| 6.1 | 12/04/2011 | Correção de erros ortográficos | Estevão Reis|
| 6.2 | 14/04/2011 | Inserção do link do documento verificado | Estevão Reis|