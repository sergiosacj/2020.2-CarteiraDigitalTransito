# Especificação Suplementar

## 1. Introdução

### 1.1 Finalidade

Este documento tem o objetivo de apresentar os requisitos não-funcionais da aplicação CDT. A Especificação Suplementar mostra requisitos que não foram identificados em um primeiro momento.

### 1.2 Escopo

A CDT é um aplicativo de dispositivo móvel que tem o intuito de facilitar a vida do motorista, fazendo com que o mesmo não precise mais sair com documentos como sua CNH e os documentos de seu carro quando for digirir.

## 2. Definições, Acrônimos e Abreviações

| Abreviação | Definição|
|--|--|
| CDT | Carteira Digital de Trânsito |
| CNH | Carteira Nacional de Habilitação |
| FURPS+ | Acrônimo de Funcionality(funcionalidade), Usability(usabilidade), Reliability(confiabilidade), Performance(Desempenho), Suportability(suportabilidade) e '+' que representa outros atributos |

## 3. Metodologia

O levantamento de requisitos no documento foi feito com base no método FURPS+, aplicando-o de acordo com as características da aplicação.

## 4. Levantamento dos Requisitos

### 4.1 Requisitos de Funcionalidades

Os requisitos referentes às funcionalidades do aplicativo CDT foram listados em documentos anteriores.

### 4.2 Requisitos de Usabilidade

* Intuitividade

    A interface deve ter fácil compreensão e memorização para qualquer pessoa ser capaz de utilizar.

* Linguagem simples e clara

    A linguagem da aplicação não deve ser um problema pra nenhum tipo de usuário, portatno uma linguagem simples é o ideal.

* Padrão de cores

    A aplicação deve ter um padrão de cores de telas e botões para não causar confusão em nenhum usuário.

### 4.3 Requisitos de Confiabilidade

* Segurança de dados
    
    É imprescindível a seguranças dos dados dos usuários, tendo em vista que são dedos pessoais como CPF, número da CNH, CRLV e CRV dos carros em seu nome.

* Login com o sistema gov.br

    Por motivos de segurança na aplicação, o login no sistema deve ser feito com o sistema gov.br, usando as credencias cadastradas no mesmo.

* Avisos de login indesejados

    O sistema deve informar caso a conta de um usuário seja logada em outros dispositivos.

* Multas apresentadas no aplicativo condizentes

    A tela de consulta de multas na aplicação deve ser condizente com as multas registradas no DETRAN.

### 4.4 Requisitos de Perfomance

* Aplicação leve

    Por ser uma aplicação simples, não deve consumir muitos recursos.

* Tempo de resposta

    O tempo de resposta da aplicação deve ser rápido para evitar problema de satisfação dos usuários.

* Funcionamento offline

    O sistema deve ser capaz de mostrar algumas telas offline, como a tela da CNH digital, pois os usuários podem precisar em momentos que não possuam conexão.

### 4.5 Requisitos de Suportabilidade

* Compatibilidade

    A aplicação CDT deve ser capaz de servir usuários de sistema iOS e Android.

* Responsividade

    A aplicação deve ser capz de se ajustar ao tamanho da tela do dispositivo do usuário.

## 5. Licenciamento

O uso das informações obtidas na aplicação é limitado ao cumprimento do que dispõe o Código de Trânsito Brasileiro(Lei 9.503, de 23 de setembro de 1997).

## 6. Bibliografia

> Projeto de Requisitos de Software Nubank Especificação Suplementar. Disponível em: https://requisitos-2017-2-nubank.github.io/Nubank/siki/esp-suplementar.html#:~:text=Finalidade%2C%20confiabilidade%2C%20desempenho%20e%20suportabilidade, acesso em: 18 de Mar. de 2021
> Projeto de Software Floricultura Beija-flor Especificação Suplementar. Disponível em: https://silo.tips/download/php-software-company-samily-rocha-gois-francisco-luiz-sobrinho-projeto-de-softwa, acesso em: 20 de Mar. de 2021
>Software Requirements Specification Amazing Lunch Indicator. Disponível em: http://www.cse.chalmers.se/~feldt/courses/reqeng/examples/srs_example_2010_group2.pdf, acesso em: 20 de Mar. de 2021


## Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 18/03/2021 | Criação do documento | Enzo Gabriel |
| 1.1 | 20/03/2021 | Atualização do documento | Enzo Gabriel |
