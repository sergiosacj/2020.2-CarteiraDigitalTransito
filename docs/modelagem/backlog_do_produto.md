# Backlog do Produto

## Introdução

&emsp;&emsp; O backlog do produto é uma técnica geralmente utilizada no desenvolvimento ágil. É basicamente uma lista com breves descrições de funcionalidades ou desejos necessários para alcançar um objetivo. Essa lista traz os requisitos para um projeto, priorizados de acordo com o valor entregue para o cliente. Desse modo, por meio desse documento será possível ter uma visão mais ampla do produto.

## Metodologia

&emsp;&emsp; Criaremos uma tabela no seguinte molde:

| Épico | História de Usuário | Rastreabilidade | Ator | Desejo | Objetivo | Prioridade |
|-|-|-|-|-|-|-|
| Cadastro | US01 | RF8 | Motorista | Realizar cadastro no CDT | Ter acesso à CNH virtualmente | Alta |

&emsp;&emsp; Desse modo, teremos catalogado todos os requisitos, com todas as suas prioridades, mais todos os épicos e histórias de usuário.

## Backlog

&emsp;&emsp; Para facilitar a visualização, a tabela está disponível de duas maneiras diferentes (excel e markdown).

### Tabela em excel

![backlog](https://raw.githubusercontent.com/Requisitos-de-Software/2020.2-CarteiraDigitalTransito/01eea60432a697ade96e1c03e96d88a571a3f23a/docs/assets/imagens/backlog.png)

### Tabela em markdown

| Épico | História de Usuário | Rastreabilidade | Ator | Desejo | Objetivo | Prioridade |
| - | - | - | - | - | - | - |
| Cadastrar | US01 | RF01 | usuário | fazer o cadastro com a conta GOV.br | acessar o sistema do app CDT | Alta |
| Cadastrar | US02 | RF01 | usuário | fazer login na aplicação | ter acesso as funcionalidades do aplicativo | Alta |
| Cadastrar | US03 | RF10 | usuário | alterar a foto de usuário | atualizar foto do perfil de usuário | Média |
| Cadastrar | US04 | RF9 | usuário | sair da conta | apagar registros de usuário | Alta |
| Cadastrar | US05 | RF12, RF24 | usuário | acessar as mensagens do sistema | conseguir ter acesso as notificações do sistema | Baixa |
| Cadastrar | US06 | RF12, RF14 | usuário | acessar o documento de política de privacidade | ter conhecimento da utilização de dados | Baixa |
| Cadastrar | US07 | RF12 | usuário | acessar o termo de responsabilidade | ter conhecimento da responsabilidade em utilizar o sistema | Baixa |
| Cadastrar | US08 | RF21 | usuário | aderir ao SNE | realizar o pagamento de infrações com mais facilidade | Média |
| Habilitação | US09 | RF3, RF8, RF19 | usuário | acessar a habilitação | ter acesso a ela dentro do aplicativo | Alta |
| Habilitação | US10 | RF3, RF10, RF19 | usuário | baixar a CNH digital | manter o documento no aparelho | Alta |
| Habilitação | US11 | RF3, RF5, RF10 | usuário | exportar a CNH digital | conseguir a CNH no formato .pdf | Alta |
| Habilitação | US12 | RF10, RF11 | usuário | remover a CNH do aplicativo | conseguir apagar meus dados da CNH do dispositivo | Média |
| Habilitação | US13 | RF5, RF10 | usuário | acessar histórico de habilitações | conseguir ter dados detalhados da CNH | Média |
| Veículos | US14 | RF4, RF5, RF13, RF15 | usuário | acessar o CRLV do meu veículo cadastrado | para que consiga ter acesso ao CRLV dentro do sistema | Alta |
| Veículos | US15 | RF4, RF10 | usuário | baixar o CRLV do meu veículo cadastrado | para manter o CRLV no aparelho | Alta |
| Veículos | US16 | RF4, RF5, RF10, RF13 | usuário | exportar o CRLV do meu veículo cadastrado | para que consiga o CRLV no formato .pdf | Alta |
| Veículos | US17 | RF10, RF11 | usuário | remover o CRLV do meu veículo cadastrado | para que eu consiga apagar meus dados do CRLV do meu dispositivo | Média |
| Veículos | US18 | RF4, RF5, RF10, RF13, RF15 | usuário | consultar recall do meu veículo cadastrado |  acessar os detalhes de recall dos meus veículos | Alta |
| Veículos | US19 | RF10, RF23 | usuário | indicar o principal condutor de um veículo | indicar o responsável pelas multas de tráfego de veículo | Média |
| Veículos | US20 | RF10, RF23 | usuário | excluir o principal condutor de um veículo | para que outra pessoa responda pelas multas de tráfego de veículo | Média |
| Veículos | US21 | RF10, RF23 | usuário | aceitar um convite para ser o principal condutor de um veículo | para que seja responsável pelas multas de tráfego de veículo e portar dados do veículo | Média |
| Veículos | US22 | RF10, RF23 | usuário | recusar um convite para ser o principal condutor de um veículo | para que não seja responsável pelas multas de tráfego de veículo e portar dados do veículo | Média |
| Veículos | US23 | RF10 | usuário | compartilhar o CRLV do meu veículo cadastrado | para que outros condutores possam utilizar o CRLV do meu veículo | Média |
| Veículos | US24 | RF10 | usuário | parar de compartilhar o CRLV do meu veículo com outro condutor | para ter controle de quem pode compartilhar o CRLV | Média |
| Veículos | US25 | RF10 | usuário | aceitar o compartilhamento do CRLV | conseguir acessar o CRLV compartilhado pelo proprietário do veículo | Média |
| Veículos | US26 | RF10 | usuário | recusar o compartilhamento do CRLV realizado pelo proprietário do veículo | para que não tenha mais o CRLV do veículo compartilhado | Média |
| Infrações | US27 | RF7, RF15, RF17 | usuário | solicitar boleto para infrações por infrator | poder fazer o pagamento da infração | Média |
| Infrações | US28 | RF7, RF15 | usuário | consultar as infrações por veículo | ter a relação de infrações em cada veículo cadastrado | Média |
| Infrações | US29 | RF2, RF15 | usuário | consultar infrações por veículo | ter a relação de infrações de cada veículo separadas | Média |
| Infrações | US30 | RF17 | usuário | solicitar boleto para infrações por veículo | fazer pagamento de infrações | Alta |
| Infrações | US31 | RF20 | usuário | informar o real infrator | real responsável pela infração ser penalizado | Média |
| Educação | US32 | RF12, RF25 | usuário | consultar campanhas educacionais | aprender mais sobre os cuidados e boas práticas que se deve ter no trânsito | Média |

## Bibliografia

> O que é backlog. Disponível em: https://blog.runrun.it/o-que-e-backlog/#:~:text=Como%20foi%20dito%2C%20backlog%2C%20tamb%C3%A9m,n%C3%A3o%20atribu%C3%ADdas%20a%20um%20respons%C3%A1vel, acesso em: 29 de Mar. de 2021

## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 29/03/2021 | Criação do documento | Enzo Gabriel |
| 1.1 | 29/03/2021 | Complementando introdução e adicionando metodologia | Sérgio Cipriano |
| 1.2 | 30/03/2021 | Criando sessão de backlog com todos os requisitos (faltando apenas popular as demais colunas) | Sérgio Cipriano |
| 2.0 | 30/03/2021 | Adição de todos os elementos no backlog (32 Histórias de Usuário) | Sérgio Cipriano e Enzo Gabriel |
| 2.1 | 31/03/2021 | Correções semânticas e adicionando espaços entre colunas |  Sérgio Cipriano |
| 2.2 | 31/03/2021 | Adição da coluna prioridade |  Enzo Gabriel |
| 2.3 | 31/03/2021 | Criação da imagem em excel |  Enzo Gabriel |
| 2.4 | 01/03/2021 | Adição da imagem criada em excel |  Sérgio Cipriano |
