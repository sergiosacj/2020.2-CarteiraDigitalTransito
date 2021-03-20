# Léxico

## 1. Introdução

&emsp;&emsp; Léxico é a técnica que se baseia na ideia de aquisição de
vocabulário. Desse modo, o foco é entender a linguagem do problema, sem
necessariamente precisar se preocupar em entender o problema.

## 2. Motivação

&emsp;&emsp; Com essa técnica é possível representar aspectos abstratos de
maneira mais concreta, o que simplifica o entendimento dos aspectos técnicos.

## 3. Metodologia

&emsp;&emsp; **LAL - Léxico Ampliado da Linguagem**, técnica trabalhada nesse
documento, trata-se de um método para compor os cenários, descrevendo termos
relacionados ao software avaliado.

&emsp;&emsp; Cada símbolo possui um nome, uma classificação, uma noção, um ou
mais impactos e zero ou mais sinônimos. O padrão a seguir será usado para
definir cada léxico:

### *Símbolo*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto/Estado/Verbo | Denotação | Conotação | Opcional |

&emsp;&emsp; Padrão do símbolo:

**L [primeira letra da classificação em minúsculo] [número de criação da classificação] - [nome do símbolo]**

&emsp;&emsp; A nomenclatura definida teve como objetivo facilitar futuras
citações. Desse modo, para referenciar os léxicos descritos nesse documento,
basta referenciar o símbolo, seguindo o padrão definido, e adicionar um link
direto para seção desse léxico.

&emsp;&emsp; É importante ressaltar que a fonte primária dos léxicos são os
documentos trabalhados na elicitação de requisitos e a Rich Picture. Conforme
o projeto dê seguimento, é possível adicionar uma quantidade maior de fontes.

## 4. Léxicos

### *Lo1 - Carteira Digital de Trânsito*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Software que disponibiliza documentos emitidos pelo Denatran | Disponibilização oficial de documentos governamentais | CDT |

### *Lo2 - Denatran*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Órgão responsável pelo aplicativo do CDT. Órgão máximo executivo do Sistema Nacional de Trânsito com autonomia administrativa e técnica, e jurisdição sobre todo o território brasileiro. É um dos órgãos responsáveis pelo cumprimento das leis de trânsito. | Disponibilização oficial de documentos governamentais | Departamento Nacional de Trânsito |

### *Lo3 - SERPRO*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Órgão responsável pela disponibilização dos dados do CDT. É a maior empresa pública (estatal) de prestação de serviços de Tecnologia da Informação do Brasil. Criada em 1964, tem como função modernizar e agilizar os sistemas de dados estratégicos da administração pública da União. | Disponibilização oficial de documentos governamentais | Serviço Federal de Processamento de Dados |

### *Lo4 - Central de Mensagens*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Forma na qual o Denatran notifica o usuário | O usuário é notificado rapidamente.</br> O ator, Denatran, pode encaminhar avisos em massa | - |

### *Lo5 - Política de privacidade*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Transparência da política do aplicativo, definida pelo Denatran | Permite ao usuário entender como funciona a coleta de informações; cookies e tecnologias semelhantes; armazenamento dos dados coletados; uso das informações fornecidas; compartilhamento de informações de terceiros; como contactar e esclarecer dúvidas | - |

### *Lo6 - Termo de Responsabilidade*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Documento ao qual o usuário deve seguir para que o Denatran tenha garantia de veracidade dos dados recebidos, sob pena de incorrer nas sanções previstas nos artigos 299 e 307 do Código Penal (falsidade ideológica e falsa identidade) | Define responsabilidades que o usuário precisa ter ao usar o aplicativo | Termo de Compromisso |

### *Lo7 - Sistema de Notificação Eletrônica*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Sistema que visa substituir o envio das notificações por correspondências impressas | Desconto no pagamento da sua infração, notificações são consideradas expedidas a partir da disponibilização e registro no SNE, proprietário será considerado notificado após 30 dias de inclusão da informação na Central de Mensagens | SNE |

### *Lo8 - Preferências*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto| Aba na qual o usuário define as preferências do comportamento do aplicativo | Permite ao usuário definir os critérios para se ter acesso à CNH (com ou sem biometria) e definir se está de acordo com o Sistema de Notificação Eletrônica definido pelo Denatran | - |

### *Lo9 - Habilitação*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Carteira Nacional de Trânsito | Ter acesso online à carteira e ter um QR Code para facilitar a verificação por agentes de trânsito | Carteira, Carteira Nacional de Habilitação, CNH |

### *Lo10 - Veículos*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Veículos já cadastrados no banco de dados do Denatran | Permite ao proprietário o acesso digital das informações relativas à todos os seus veículos | - |

### *Lo11 - Infrações*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Disponibiliza acesso à infrações por infrator e por veículo | Após aceitar o termo de compromisso do SNE, o usuário tem acesso à infrações cometidas e catalogadas na sua CNH. Além disso, é possível visualizar infrações cometidas para cada veículo do proprietário | Multas |

### *Lo12 - Educação*

| Classificação | Noção | Impacto(s) | Sinônimos(s) |
| ------------- | ----- | ------- | --------- |
| Objeto | Disponibiliza acesso à campanhas de concientização | Informa todos os usuários do CDT acerca de qualquer campanha vigente | Concientização, Informações, Campanhas |


## 5. Bibliografia

> SAMPAIO, Julio; FRANCO, Ana. "A strategy for Conceptual Model Acquisition". Departamento de informática, Pontíficia Universidade Católica, Rio de Janeiro.

## 6. Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|19/03/2021|1.0|Criação do template do documento|Sérgio Cipriano|
|20/03/2021|2.0|Adição da introdução, motivação e metodologia|Sérgio Cipriano|
