# História de Usuário 

## 1.Introdução 

&emsp;&emsp; "Uma história de usuário é uma breve declaração que descreve algo que o sistema deve fazer para o usuário. É um tipo de especificação de requisitos adotado por muitas equipes de projetos 'ageis'. Ela se restringe a definir o escopo sem entrar no detalhamento do passo a passo ou das regras de negócio que se aplicam à tarefa do software. Os detalhes do comportamento do sistema são desenvolvidos por meio de interações entre a equipe de desenvolvimento e o dono do produto; pela definição de um critério de aceitação." (VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: Software Orientado ao Negócio).

## 2.Metodologia

&emsp;&emsp; Para criarmos as histórias de usuário nos baseamos nos cenários da aplicação, criando as histórias a partir deles.
A organização das histórias ficou da seguinte maneira:utilizamos a sigla 'EP' significando que será abordado os casos de uso de um dado épico seguido do número do épico e logo após o nome do épico. Exemplo:

EP01: Conta de Usuário

&emsp;&emsp; Em cada épico será descritos as suas histórias de usuário, iniciando com a sigla 'US' para identificar que é uma história de usuário seguido do número da história e em seguida o nome da história.Exemplo:

US01:Cadastrar

O padrão de escrita será assim:

Eu, como um < TIPO DE USUÁRIO >, desejo < OBJETIVO > para < UMA RAZÃO >

## 3.Histórias de Usuário

### EP01: Conta de Usuário

#### **US01:Cadastrar**

&emsp;&emsp; Eu, como um usuário, desejo fazer o cadastro na conta do GOV.br para ter acesso ao sistema do CDT.

Critérios de aceitação:

 - Deve apresentar uma tela para criação da conta no GOV.br
 - Deve ter um botão para redirecionar o usuário para o site do GOV.br para fazer o cadastro
 - Deve concluir o cadastro salvando os dados do usuário
 - Deve ser possível acessar o CDT após o cadastro no GOV.br

#### **US02:Realizar o login**

&emsp;&emsp; Eu, como um usuário, desejo realizar o login na aplicação, para ter acesso às funcionalidades do CDT

Critérios de aceitação:

- Deve ter um botão para realizar o login
- Deve ter um campo para preencher com o CPF do usuário
- Deve ter um campo para preencher com a senha do usuário
- Deve realizar a conexão com o CDT

#### **US03:Alterar foto do perfil de usuário**

&emsp;&emsp; Eu, como um usuário, desejo alterar a foto de perfil,para atualizá-la

Critérios de aceitação:

- Deve ter conter um botão próximo a foto do usuário para poder alterá-la
- Deve apresentar as opções de onde se deve buscar a imagem desejada
- Deve realizar conexão com o CDT
- Deve conter um botão para salvar as alterações
- Deve concluir a alteração exibindo a imagem atualizada

#### **US04:Realizar Logout**

&emsp;&emsp; Eu, como um usuário, desejo sair da minha conta no CDT, para impedir que outras pessoas acessem ela em meu aparelho

Critérios de aceitação:

- Deve conter um botão para sair da conta
- Deve fazer o logout da conta no CDT
- Deve apresentar uma informação sobre a realização bem sucedida do logout da conta

#### **US05: Acessar mensagens do sistema**

&emsp;&emsp; Eu, como usuário, desejo visualizar as mensagens do sistema, para que eu consiga ter acesso às notificações

Critérios de aceitação:

- Deve conter um campo destinado somente às mensagens do sistema
- Deve ser exibidas as últimas mensagens recebidas

#### **US06: Acessar a política de privacidade**

&emsp;&emsp; Eu, como usuário, desejo acessar o documento de política de privacidade, para que eu possa ter conhecimento de como meus dados estão sendo utilizados

Critérios de aceitação:

- Deve conter um botão para acessar o documento de política de privacidade
- Deve ser exibido o documento de política de privacidade

#### **US07: Acessar o termo de responsabilidade**

&emsp;&emsp; Eu, como usuário, desejo acessar o termo de responsabilidade, para que eu tenha conhecimento da mesma

Critérios de aceitação:

- Deve conter um botão para acessar o termo de responsabilidade
- Deve ser exibido o termo de responsabilidade

#### **US08: Aderir ao SNE**

&emsp;&emsp; Eu, como usuário, desejo aderir ao SNE, para que o pagamento de infrações seja realizado com mais facilidade

Critérios de aceitação:

- Deve conter um botão que indique os termo de condições de adesão do SNE 
- Deve ser possível aceitar ou rejeitar o termo de condições de adesão do SNE 
- Deve apresentar uma informação sobre a realização bem sucedida da adesão ao SNE


### EP02: Habilitação

#### **US09: Acessar Habilitação**

&emsp;&emsp; Eu, como um usuário, desejo ter acesso à habilitação, para visualizar ela dentro do aplicativo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de habilitação
- Deve conter um botão para acessar a CNH
- Deve possuir um campo para validar a chave de acesso
- Deve exibir a CNH

#### **US10: Baixar a CNH digital**

&emsp;&emsp; Eu, como um usuário, desejo baixar a CNH digital, para manter o documento no aparelho

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de habilitação
- Deve conter um botão para baixar a CNH
- Deve possuir um campo para validar a chave de acesso
- Deve baixar a CNH

#### **US11: Exportar a CNH digital**

&emsp;&emsp; Eu, como usuário, desejo exportar a CNH digital, para que consiga a CNH no formato .pdf

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de habilitação
- Deve conter um botão para exportar a CNH
- Deve possuir um campo para validar a chave de acesso
- Deve exibir a CNH no formato .pdf no local de importação

#### **US12: Remover CNH**

&emsp;&emsp; Eu, como usuário, desejo remover a CNH, para que eu consiga apagar meus dados da CNH do meu dispositivo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de habilitação
- Deve conter um botão para remover a CNH
- Deve fazer a remoção de todos os dados da CNH
- Deve apresentar uma informação sobre a realização bem sucedida da remoção da CNH

#### **US13: Acessar histórico da CNH**

&emsp;&emsp; Eu, como usuário, desejo visualizar o histórico da minha CNH, para que eu consiga ter acesso aos dados detalhados da minha CNH

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de habilitação
- Deve conter um botão para acessar o histórico da CNH
- Deve ser exibidas todas as CNHs
- Deve ser possível selecionar a CNH a ser exibida/consultada
- Deve ser possível exibir a CNH selecionada

### EP03: Veículos

#### **US14: Acessar CRLV dos veículos cadastrados**

&emsp;&emsp; Eu, como usuário, desejo acessar o CRLV do meu veículo cadastrado, para que consiga visualizá-lo dentro do sistema

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar o CRLV do veículo selecionado
- Deve possuir um campo para validar a chave de acesso
- Deve exibir o CRLV do veículo selecionado

#### **US15: Baixar CRLV dos veículos cadastrados**

&emsp;&emsp; Eu, como usuário, desejo baixar o CRLV do meu veículo cadastrado, para manter o CRLV no aparelho

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar o CRLV do veículo selecionado
- Deve conter um botão para baixar o CRLV
- Deve possuir um campo para validar a chave de acesso
- Deve baixar o CRLV

#### **US16: Exportar CRLV dos veículos cadastrados**

&emsp;&emsp; Eu, como usuário, desejo exportar o CRLV do meu veículo cadastrado, para que consiga o CRLV no formato .pdf

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar o CRLV do veículo selecionado
- Deve conter um botão para exportar o CRLV
- Deve possuir um campo para validar a chave de acesso
- Deve exibir o CRLV no formato .pdf no local de importação

#### **US17: Remover CRLV dos veículos cadastrados**

&emsp;&emsp; Eu, como usuário, desejo remover o CRLV do meu veículo cadastrado, para que eu consiga apagar meus dados do CRLV do meu dispositivo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar o CRLV do veículo selecionado
- Deve conter um botão para remover o CRLV
- Deve apresentar uma informação sobre a realização bem sucedida da remoção do CRLV

#### **US18: Consultar Recall**

&emsp;&emsp; Eu, como usuário, desejo consultar recall do meu veículo cadastrado, para que eu consiga acessar os detalhes de recall dos meus veículos

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar os dados do veículo selecionado
- Deve conter um botão para consultar o recall
- Deve apresentar os detalhes do recall do veículo selecionado

#### **US19: Indicar o principal condutor** 

&emsp;&emsp; Eu, como usuário, desejo indicar o principal condutor de um veículo, para que o devido responsável responda pelas multas de tráfego de veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar os dados do veículo selecionado
- Deve conter um botão para consultar o principal condutor
- Deve conter um botão para indicar o principal condutor
- Deve conter um campo para inserir o CPF do principal condutor
- Deve conter um botão para confirmar o principal condutor


#### **US20: Excluir o principal condutor** 

&emsp;&emsp; Eu, como usuário, desejo excluir o principal condutor de um veículo, para que o mesmo não responda mais pelas multas de tráfego de veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar os dados do veículo selecionado
- Deve conter um botão para consultar o principal condutor
- Deve conter um botão para remover o principal condutor
- Deve conter um botão para confirmar a remoção do principal condutor

#### **US21: Aceitar o principal condutor** 

&emsp;&emsp; Eu, como usuário, desejo aceitar um convite para ser o principal condutor de um veículo, para que eu seja responsável pelas multas de tráfego de veículo e portar dados do veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão de aceitar o convite de principal condutor do veículo selecionado 


#### **US22: Recusar o principal condutor** 

&emsp;&emsp; Eu, como usuário, desejo recusar um convite para ser o principal condutor de um veículo, para que eu não seja responsável pelas multas de tráfego de veículo e portar dados do veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar os dados do veículo selecionado
- Deve conter um botão de recusar o convite de principal condutor do veículo selecionado 
- Deve conter um botão para confirmar recusar ser o principal condutor

#### **US23: Compartilhar o CRLV** 

&emsp;&emsp; Eu, como usuário, desejo compartilhar o CRLV do meu veículo cadastrado, para que outros condutores possam utilizar o CRLV do meu veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar o CRLV do veículo selecionado
- Deve conter um botão para compartilhar o CRLV 
- Deve conter um campo para inserir o CPF do condutor
- Deve conter um campo para inserir o apelido do condutor
- Deve conter um botão de afirmação para permitir o compartilhamento

#### **US24: Parar de compartilhar o CRLV** 

&emsp;&emsp; Eu, como usuário, desejo parar de compartilhar o CRLV do meu veículo com outro condutor, para ter controle de quem pode ter acesso ao CRLV do meu veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão para acessar os veículos cadastrados
- Deve ser possível selecionar um dos veículos cadastrados
- Deve conter um botão para acessar o CRLV do veículo selecionado
- Deve conter um botão para remover o compartilhamento do CRLV com outro condutor
- Deve apresentar uma informação sobre a realização bem sucedida da remoção do compartilhamento do CRLV com o condutor

#### **US25: Aceitar compartilhamento do CRLV**

&emsp;&emsp; Eu, como usuário, desejo aceitar o compartilhamento do CRLV, para que eu consiga acessar o CRLV compartilhado pelo proprietário do veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão de aceitar o convite de compartilhamento do CRLV do veículo selecionado 
- Deve exibir o CRLV do veículo selecionado

#### **US26: Remover compartilhamento do CRLV**

&emsp;&emsp; Eu, como usuário, desejo recusar o compartilhamento do CRLV realizado pelo proprietário do veículo, para que não tenha acesso ao CRLV do veículo compartilhado

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de veículos
- Deve conter um botão de remover o compartilhamento do CRLV do veículo selecionado 
- Deve apresentar uma informação sobre a realização bem sucedida da remoção do compartilhamento do CRLV com o proprietário do veículo

### EP04: Infrações

#### **US27**: Consultar Infrações por Infrator

&emsp;&emsp; Eu, como um usuário, desejo consultar as infrações por infrator, para saber quem foi o responsável pela infração naquele veículo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de infrações
- Deve possuir a opção de verificar infrações por infrator
- Deve mostrar a lista com todas as infrações cometidas 
- Deve ser possível verificar as informações detalhadas de cada infração

#### **US28**: Solicitar Boleto para Infrações por Infrator

&emsp;&emsp; Eu, como um usuário, desejo solicitar boleto para infrações por infrator, para poder fazer o pagamento da infração

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de infrações
- Deve possuir a opção de verificar infrações por infrator
- Deve mostrar a lista com todas as infrações cometidas 
- Deve ser possível verificar as informações detalhadas de cada infração
- Deve conter um botão para solicitar o boleto da infração
- Deve baixar o boleto em pdf para o dispositivo utilizado no momento da solicitação

#### **US29**: Consultar Infrações por Veículo

&emsp;&emsp; Eu, como um usuário, desejo consultar as infrações por veículo, para ter a relação de infrações em cada veículo que eu possuo

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de infrações
- Deve possuir a opção de verificar infrações por veículo
- Deve mostra a lista de veículos que possuo
- Deve ser possível selecionar um dos veículos
- Deve mostrar a lista com todas as infrações cometidas com aquele veículo 
- Deve ser possível verificar as informações detalhadas de cada infração

#### **US30**: Solicitar Boleto para Infrações por Veículo

&emsp;&emsp; Eu, como um usuário, desejo solicitar boleto para infrações por veículo, para poder fazer o pagamento da infração

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de infrações
- Deve possuir a opção de verificar infrações por veículo
- Deve mostra a lista de veículos que possuo
- Deve ser possível selecionar um dos veículos
- Deve mostrar a lista com todas as infrações cometidas com aquele veículo 
- Deve ser possível verificar as informações detalhadas de cada infração
- Deve conter um botão para solicitar o boleto da infração
- Deve baixar o boleto em pdf para o dispositivo utilizado no momento da solicitação.

#### **US31**: Informar real infrator

&emsp;&emsp; Eu, como um usuário, desejo informar o real infrator, para que o real responsável pela infração seja penalizado

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de infrações
- Deve mostrar a lista com todas as infrações cometidas
- Deve ser possível verificar as informações detalhadas de cada infração
- Deve conter um botão para informação o real infrator
- Deve conter um formulário para que eu possa informar o real infrator

### EP05: Educação

#### **US32**: Consultar campanhas educacionais

&emsp;&emsp; Eu, como um usuário, desejo consultar campanhas educacionais, para aprender e me conscientizar mais sobre sobre os cuidados e boas práticas que se deve ter no trânsito

Critérios de aceitação:

- Deve conter um botão na tela inicial para acessar a área de educação
- Deve conter todo o material educacional e campanhas vigente no momento do acesso
- Deve ser possível acessar qualquer um desses conteúdos

## Referências Bibliográficas
> - VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira - Engenharia de Requisitos: Software Orientado ao Negócio. Acesso em: 25 de Março de 2021

## Versionamento

| Versão | Data       | Modificação                                                                                                |       Autor      |
| ------ | ---------- | ---------------------------------------------------------------------------------------------------------- | ---------------- |
|  0.1   | 25/03/2021 | Criação dos tópicos do documento e inserção da Introdução                                                  |  Estevão Reis    |
|  1.0   | 26/03/2021 | Criação de 6 histórias de usuário                                                                          |  Estevão e Yan   |
|  1.1   | 26/03/2021 | Descrição da metodologia utilizada                                                                         |  Estevão Reis    |
|  2.0   | 28/03/2021 | Criação das histórias de usuário referente as Infrações e Educação                                         |  Estevão Reis    |
|  3.0   | 29/03/2021 | Criação de novas histórias de usuário referente a Veículos, Habilitação e Conta de Usuário                 |      Yan         |
|  3.1   | 30/03/2021 | Correções de Erros Ortográficos e versionamento                                                            |  Estevão Reis    |
|  3.2   | 30/03/2021 | Ajustando a formatação e corrigindo na citação                                                             |  Sérgio Cipriano |
|  4.0   | 22/04/2021 | Correções de erros de ortografia, concordância, reformulação de histórias de usuário e adição de critérios |  Estevão Reis    |