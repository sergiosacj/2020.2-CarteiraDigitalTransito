# Verificação das Histórias de Usuário
&emsp; &emsp;Este documento visa verificar as Histórias de Usuário para detectar os erros e defeitos antes de finalizar o projeto.</br>
&emsp; &emsp;Para a verificação das Histórias de usuário foi escolhida a estratégia de inspeção por checklist, por ser simples, objetiva e a mais eficaz em comparação às outras neste contexto.

## 1. Contexto
 - Técnica: Inspeção
 - Autores: Estevao Reis e Yan Andrade
 - Revisores: Sérgio Cipriano e Emily Dias
 - Inspetores: Estevão Reis


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
| 9 | Possui critérios de aceitação coerentes? |
| 10 | Possui ator coerente? |
| 11 | A história de usuário é coerente? | 

### 2.2. Legenda
|Símbolo|Descrição|
|-------|---------|
|✔     | Contém   |
|✖     |Não Contém|

### 2.3. Resultados

|US  |1|2 |3|4 |5|6|7|8 |9|10|11|
|----|-|--|-|--|-|-|-|--|-|--|--|
|US01|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US02|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US03|✔|✔|✖|✖|✖|✔|✔|✔|✔|✔ |✔|
|US04|✖|✔|✔|✔|✖|✔|✔|✔|✔|✔ |✖|
|US05|✔|✔|✖|✔|✔|✔|✔|✔|✔|✔ |✔|
|US06|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US07|✔|✔|✖|✖|✔|✔|✔|✔|✔|✔ |✔|
|US08|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US09|✔|✔|✖|✔|✖|✔|✔|✔|✔|✔ |✔|
|US10|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US11|✔|✔|✔|✔|✔|✔|✔|✔|✖|✔ |✔|
|US12|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US13|✔|✔|✖|✔|✖|✔|✔|✖|✔|✔ |✔|
|US14|✔|✔|✖|✔|✔|✔|✔|✔|✔|✔ |✔|
|US15|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US16|✔|✔|✔|✔|✔|✔|✔|✖|✔|✔ |✔|

|US  |1|2 |3|4 |5|6|7|8 |9|10|11|
|----|-|--|-|--|-|-|-|--|-|--|--|
|US17|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US18|✔|✔|✔|✔|✔|✔|✔|✖|✔|✔ |✔|
|US19|✔|✔|✔|✔|✔|✔|✔|✖|✔|✔ |✔|
|US20|✔|✔|✔|✔|✔|✔|✔|✖|✔|✔ |✔|
|US21|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US22|✔|✖|✔|✔|✔|✔|✔|✖|✔|✔ |✖|
|US23|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US24|✔|✔|✔|✔|✖|✔|✔|✔|✔|✔ |✔|
|US25|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US26|✔|✖|✔|✔|✔|✔|✔|✔|✔|✔ |✖|
|US27|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US28|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US29|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US30|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US31|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|
|US32|✔|✔|✔|✔|✔|✔|✔|✔|✔|✔ |✔|

## 3. Conclusão
### 3.1. Problemas Encontrados

#### US03:Alterar foto do perfil de usuário

##### Problemas 

3 4 5 - Redundância na frase da história de usuário: "Eu, como um usuário, desejo alterar a foto de usuário, para atualizar a foto do perfil de usuário".</br>
&emsp;&emsp;&emsp;
Redundância no critério de aceitação "Deve ter conter um botão próximo a foto do usuário para poder alterar a foto".

##### Possíveis soluções
 
3 4 5 - Mudar para "Eu, como um usuário, desejo alterar a foto de perfil,para atualiza-la".</br>
&emsp;&emsp;&emsp;Mudar para "Deve ter conter um botão próximo a foto do usuário para poder altera-la".

#### US04:Realizar Logout
##### Problemas 
1 - Não é dito de onde é apagado os registros do usuário, se na base de dados do CDT ou se no aparelho onde se está utilizando o aplicativo.</br>
5 - Uso expressão "registro de usuário" pode não ser claro para o usuário.</br>
11 - Fazer o logout na aplicação não necessariamente apaga os registros do usuário.
##### Possíveis soluções
Devido a incoerência da história de usuário, não será apontado soluções para os outros problemas.</br>
11 - Mudar para " Eu, como um usuário, desejo sair da minha conta no CDT, para impedir que outras pessoas acessem ela em meu aparelho".

#### US05: Acessar mensagens do sistema
##### Problemas 
3 - As expressões "acessar" e "ter acesso" levam a redundância.
##### Possíveis soluções
3 - Mudar para "Eu, como usuário, desejo visualizar as mensagens do sistema, para que eu consiga ter acesso as notificações".

#### US07: Acessar o termo de responsabilidade
##### Problemas 
3 - Uso repetido da palavra "responsabilidade".</br>
4 - Informação "sabendo que o mesmo pode me punir por descumprir as regras impostas" desnecessária.</br>

##### Possíveis soluções
3 4 - Mudar para "Eu, como usuário, desejo acessar o termo de responsabilidade, para que eu tenha conhecimento da mesma".

#### US09: Acessar Habilitação 
##### Problemas 
3 5 - Redundância na frase da história de usuário.
##### Possíveis soluções
3 5 - Mudar para "Eu, como um usuário, desejo ter acesso à habilitação, para visualizar ela dentro do aplicativo".

#### US11: Exportar a CNH digital
##### Problemas 
9 - Deveria ter um critério de aceitação anterior as que existem.

##### Possíveis soluções
9 Adicionar esse critério no início "Deve conter um botão na tela inicial para acessar a área de habilitação".

#### US13: Acessar histórico da CNH

##### Problemas
3 - A expressão "da minha CNH" repete duas vezes, causando redundância.</br>
5 - A expressão "ter dados detalhados da minha CNH" pode não ser agradável ao público pela falta de artigos definidos.</br>
8 - Erro gramatical na história de usuário: "[...]para que eu conisga ter dados[..]";</br>
&emsp;Erro gramatical no critério de aceitação: "Deve ser possível exibbir a CNH selecionada".

##### Possíveis Soluções
3 5 8 - Mudar para "Eu, como usuário, desejo visualizar o histórico da minha CNH, para que eu consiga ter acesso aos dados detalhados da minha CNH".</br>
8 - Mudar para "Deve ser possível exibir a CNH selecionada".</br>

#### US14: Acessar CRLV dos veículos cadastrados

##### Problemas
3 - Redundância: "acessar" e "ter acesso" na mesma frase.
##### Possíveis Soluções
 3 - Mudar para "Eu, como usuário, desejo acessar o CRLV dos meu veículo cadastrado, para que consiga visualiza-lo dentro do sistema".


#### US16: Exportar CRLV dos veículos cadastrados
##### Problemas
8 - Erro ortográfico na frase "[...]para que consiga o CRLV nop formato .pdf".
##### Possíveis Soluções
8 - Mudar para "[...]para que consiga o CRLV no formato .pdf".

#### US18: Consultar Recall
##### Problemas
8 - Erro de concordância no critério "Deve conter um botão para acessar o dados do veículo selecionado".

##### Possíveis Soluções
8 - Mudar para "Deve conter um botão para acessar os dados do veículo selecionado".


#### US19: Indicar o principal condutor
##### Problemas
8 - Erro de concordância no critério "Deve conter um botão para acessar o dados do veículo selecionado".

##### Possíveis Soluções
8 - Mudar para "Deve conter um botão para acessar os dados do veículo selecionado".

#### US20: Excluir o principal condutor
##### Problemas
8 - Erro de concordância no critério "Deve conter um botão para acessar o dados do veículo selecionado".

##### Possíveis Soluções
8 - Mudar para "Deve conter um botão para acessar os dados do veículo selecionado".
#### US22: Recusar o principal condutor
##### Problemas
2 11 - A história de usuário está incoerente pelo uso do "mais", pois se o condutor recusa o convite de ser o principal condutor ele não chegou a ser o principal condutor e, portanto, nunca foi o responsável.</br>
8 - Erro de concordância no critério "Deve conter um botão para acessar o dados do veículo selecionado".

##### Possíveis Soluções
2 11 - Mudar para "Eu, como usuário, desejo recusar um convite para ser o principal condutor de um veículo, para que eu não seja responsável pelas multas de tráfego de veículo e portar dados do veículo".</br>
8 - Mudar para "Deve conter um botão para acessar os dados do veículo selecionado".

#### US24: Parar de compartilhar o CRLV
##### Problemas
5 - A frase da História de Usuário não foi bem formulada.
##### Possíveis Soluções
5 - Mudar para " Eu, como usuário, desejo parar de compartilhar o CRLV do meu veículo com outro condutor, para ter controle de quem pode ter acesso ao CRLV do meu veículo".


#### US26: Remover compartilhamento do CRLV
##### Problemas
2 11 - A história de usuário está incoerente pelo uso do "mais", pois se não foi aceito o compartilhamento do CRLV do veículo, entao ele nunca teve acesso.</br>
##### Possíveis Soluções
2 11 - "Eu, como usuário, desejo recusar o compartilhamento do CRLV realizado pelo proprietário do veículo, para que não tenha acesso ao CRLV do veículo compartilhado".

### 3.2. Dados Percentuais

#### 3.2.1.Histórias de Usuário
|US  |Porcentagem de Sucesso|
|----|-|
|US01|100%|
|US02|100%|
|US03|100%|
|US04|100%|
|US05|100%|
|US06|100%|
|US07|100%|
|US08|100%|
|US09|100%|
|US10|100%|
|US11|100%|
|US12|100%|
|US13|100%|
|US14|100%|
|US15|100%|
|US16|100%|
|US17|100%|
|US18|100%|
|US19|100%|
|US20|100%|
|US21|100%|
|US22|100%|
|US23|100%|
|US24|100%|
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
| 1 | Todas as informações necessárias estão presentes? |100%|
| 2 | As informações são consistentes? |100%|
| 3 | As informações são concisas? |100%|
| 4 | Há apenas informações necessárias? | 100%|
| 5 | Uso de linguagem compreensível e agradável ao público? |100%|
| 6 | Possui rastreabilidade? |100%|
| 7 | O épico associado é coerente? |100%|
| 8 | A ortografia está correta? |100%|
| 9 | Possui critérios de aceitação coerentes? |100%|
| 10 | Possui ator coerente? |100%|
| 11 | A história de usuário é coerente? | 100%|

## 4. Acompanhamento
&emsp; &emsp; Ainda não foi feito as correções necessárias.

## 5. Bibliografia

> - VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira - Engenharia de Requisitos: Software Orientado ao Negócio. Acesso em: 09 de Abril de 2021

## 6.Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 12/04/2021 | Criação do documento | Estevão Reis |
| 2.0 | 12/04/2021 | Verificação da US01 à US16 | Estevão Reis |
| 3.0 | 12/04/2021 | Verificação da US017 à US32 | Estevão Reis |