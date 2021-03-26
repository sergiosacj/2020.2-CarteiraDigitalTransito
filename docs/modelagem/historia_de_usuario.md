# História de Usuário 

## Introdução 
&emsp;&emsp;Uma história de usuário é uma breve declaração que descreve algo que o sistema deve fazer para o usuário. É um tipo de especificação de requisitos adotado por muitas equipes de projetos "ageis".

&emsp;&emsp;Ela se restringe a definir o escopo sem entrar no detalhamento do passo a passo ou das regras de negócio que se aplicam à tarefa do software. Os detalhes do comportamento do sistema são desenvolvidos por meio de interações entre a equipe de desenvolvimento e o dono do produto; pela definição de um critério de aceitação.(VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira. Engenharia de Requisitos: Software Orientado ao Negócio).

## Metodologia
Para criarmos as histórias de usuário nos baseamos no cenários da aplicação, criando as histórias apartir deles.
A organização das histórias ficaram da seguinte maneira: 
utilizamos a sigla 'EP' signficando que será abordado os casos de uso de um dado épico seguido do número do épico e logo após o nome do épico. Exemplo: 

EP01: Conta de Usuário

Em cada épico será descritos as suas histórias de usuário, iniciando com a sigla 'US' para identificar que é uma história de usuário seguido do numero da história e em seguida o nome da história.Exemplo:

US01:Cadastrar

O padrão de escrita será assim:

Eu, como < TIPO DE USUÁRIO >, desejo < OBJETIVO > para < UMA RAZÃO >


## Histórias de Usuário

## EP01: Conta de Usuário
 ### **US01:Cadastrar**
 &emsp;&emsp;Eu, como usuário, desejo fazer o cadastro na conta do GOV.br para ter acesso ao sistema do CDT.

 &emsp;&emsp;Critérios de aceitação:

 - Deve apresentar uma tela para criação da conta no GOV.br
 - Deve ter um botão para redirecionar o usuário para o site do GOV.br para fazer o cadastro
 - Deve concluir o cadastro salvando os dados do usuário
 - Deve ser possível acessar o CDT após o cadastro no GOV.br

 ### **US02:Realizar o login**
&emsp;&emsp;Eu, como usuário, desejo realizar o login na aplicação, para ter acesso às funcionalidades do CDT

&emsp;&emsp;Critérios de aceitação:

- Deve ter um botão para realizar o login
- Deve ter um campo para preencher com o CPF do usuário
- Deve ter um campo para preencher com a senha do usuário
- Deve realizar a conexão com o CDT


 ### **US03:Alterar foto do perfil de usuário**
&emsp;&emsp;Eu, como usuário desejo alterar a foto de usuário, para atualizar a foto do perfil de usuário

&emsp;&emsp;Critérios de aceitação:
- Deve ter conter um botão próximo a foto do usuário para poder alterar a foto
- Deve apresentar as opções de onde se deve buscar a imagem desejada.
- Deve realizar conexão com o CDT
- Deve conter um botão para salvar as alterações
- Deve concluir a alteração exibindo a imagem atualizada

 ### **US04:Realizar Logout**
&emsp;&emsp;Eu, como usuário desejo sair da minha conta no CDT, para que eu consiga apagar meus registros de usuário

&emsp;&emsp;Critérios de aceitação:
- Deve conter um boão para sair da conta
- Deve fazer o logout da conta no CDT
- Deve ter apresentar uma informação sobre a realização bem sucedida do logout da conta

## EP02: Habilitação
 ### **US05: Acessar Habilitação**
&emsp;&emsp;Eu, como usuário desejo acessar a habilitação, para ter acesso a ela dentro do aplicativo

&emsp;&emsp;Critérios de aceitação:
- Deve conter um botão para acessar a CNH
- Deve possuir um campo para validar a chave de acesso
- Deve exibir a CNH

 ### **US06: Baixar a CNH digital**
&emsp;&emsp;Eu, como usuário desejo baixar a CNH digital, para manter o documento no aparelho

&emsp;&emsp;Critérios de aceitação:
- Deve conter um botão para baixar a CNH
- Deve possuir um campo para validar a chave de acesso
- Deve baixar a CNH



## Referências Bibliográficas
> - VAZQUEZ, Carlos Eduardo, SIMÕES, Guilherme Siqueira - Engenharia de Requisitos: Software Orientado ao Negócio. Acesso em: 25 de Março de 2021

## Versionamento

| Versão | Data       | Modificação                                               | Autor         |
| ------ | ---------- | --------------------------------------------------------- | ------------  |
|  0.1   | 25/03/2021 | Criação dos tópicos do documento e inserção da Introdução | Estevão Reis  |
|  0.2   | 26/03/2021 | Criação de 6 histórias de usuário                         | Estevao e Yan |
|  0.3   | 26/03/2021 | Descrição da metodologia utilizada                        | Estevao Reis  |