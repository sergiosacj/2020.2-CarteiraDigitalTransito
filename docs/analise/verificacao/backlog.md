# Verificação do Backlog e História de Usuários
&emsp; &emsp;Este documento visa verificar o backlog de produto para detectar os erros e defeitos antes de finalizar o projeto. O backlog será analisado a forma como foram escritas e organizadas as histórias de usuário.</br>
&emsp; &emsp;Para a verificação do backlog foi escolhida a estratégia de inspeção por checklist, por ser simples, objetiva e a mais eficaz em comparação às outras neste contexto.


## Contexto
 - Técnica: Inspeção
 - Autores: Sérgio Cipriano e Enzo Gabriel
 - Revisores: Estevao Reis e Daniel Porto
 - Inspetores: Estevao Reis
## Checklist

| Número | Questão |
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
### Legenda
|Simbolo|Descrição|
|-------|---------|
|✔     | Contém   |
|✖     |Não Contém|

### Resultados

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

## Conclusão
### Problemas Encotrados
#### US02:Realizar o login
##### Problemas 

8 - Erro de acentuação no Backlog: "Ter acesso as funcionalidades".
##### Possíveis soluções
 
8 - Mudar para "Ter acesso às funcionalidades".

### US04:Realizar Logout

##### Problemas 
1 - Não é dito de onde é apagado os registros do usuário, se na base de dados do CDT ou se no aparelho onde se está utilizando o aplicativo</br>
5 - Uso expressão "registro de usuário" pode não ser claro para o usuário</br>
10 - Fazer o logout na aplicação não necessariamente apaga os registros do usuário
##### Possíveis soluções
Devido a incoerência entre desejo e objetivo, não será apontado soluções para os outros problemas.</br>
10 - Mudar DESEJO para "sair da conta"; e OBJETIVO para: "Impedir que outras pessoas acessem minha conta em meu aparelho"


### US05: Acessar mensagens do sistema
##### Problemas 
3 - As expressões "acessar" e "ter acesso" levam a redundância.

##### Possíveis soluções
3 - Mudar DESEJO para "Visualizar as mensagens do sistema";

### US14: Acessar CRLV dos veículos cadastrados
##### Problemas 
3 - As expressões "acessar" e "ter acesso" levam a redundância.

##### Possíveis soluções
3 - Mudar DESEJO para "Visualizar o CRLV do meu veículo cadastrado".

### US19: Indicar o principal condutor
##### Problemas 
3 - A indicar "indicar" se repete em DESEJO e OBJETIVO, causando rendundância.

##### Possíveis soluções
3 - Mudar DESEJO para "Definir o principal condutor de um veículo;

### US24: Parar de compartilhar o CRLV
##### Problemas 
10 - Incoerência entre DESEJO e OBJETIVO

##### Possíveis soluções
10 - Mudar OBJETIVO para "Para ter controle de quem pode ter acesso ao CRLV do meu veículo";

## Bibliografia

> - VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira - Engenharia de Requisitos: Software Orientado ao Negócio. Acesso em: 09 de Abril de 2021

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 08/04/2021 | Criação do documento com os checklist em todas as histórias de usuário do Backlog | Estevao Reis |
| 2.0 | 11/04/2021 | Mudança de toda a organização e layout do documento e verificação da US01 até a US16| Estevao Reis|
| 3.0 | 11/04/2021 | Mudança na organização e layout dos Resultados| Estevao Reis|
| 4.0 | 11/04/2021 | Mundanças nos critérios 9 e 10 e nova verificação de todos os US| Estevao Reis|