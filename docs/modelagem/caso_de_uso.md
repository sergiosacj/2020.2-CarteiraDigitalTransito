# Casos de Uso

## Introdução

&emsp;&emsp;Os casos de uso são a próxima etapa no processo de design, depois de ter a lista completa dos requisitos. Os casos de uso integram os requisitos em um pacote abrangente que descreve a interação do usuário com o sistema.<br>
&emsp;&emsp;Eles começam onde o processo de coleta de requisitos termina. Os requisitos determinam quais Casos de Uso o sistema terá, e muitos dos requisitos se tornarão sua lógica de negócios.

# Diagrama casos de uso

## UC01 - Fazer o login

|      UC01       | Descrição                                                 |
| :-------------: | --------------------------------------------------------- |
|    Descrição    | Logar no sistema                                          |
|      Ator       | Usuário                                                   |
|  Pré-condições  | Acesso à internet e cadastro no sistema GOV.br            |
|      Ação       | Entrar no app e ser capaz de acessar todas as opções dele |
|     Evento      | -                                                         |
| Rastreabilidade | RF1 - Ter login integrado com o sistema GOV.br            |

## UC02 - Cadastrar CNH

|      UC02       | Descrição                                                                                                |
| :-------------: | -------------------------------------------------------------------------------------------------------- |
|    Descrição    | O usuário cadastra a CNH                                                                                 |
|      Ator       | Usuário                                                                                                  |
|  Pré-condições  | Acesso à internet                                                                                        |
|      Ação       | O usuário cadastra o documento CNH no aplicativo                                                         |
|     Evento      | -                                                                                                        |
| Rastreabilidade | RF3 - Ter acesso a versão digital da CNH,<br> RF10 - Gerenciar documentos, <br>RF19 - Validar documentos |

## UC03 - Acessar a CNH

|      UC03       | Descrição                                                                                                                               |
| :-------------: | --------------------------------------------------------------------------------------------------------------------------------------- |
|    Descrição    | O usuário acessar a CNH                                                                                                                 |
|      Ator       | Usuário                                                                                                                                 |
|  Pré-condições  | Estar logado no CDT, ter habilitação cadastrada                                                                                         |
|      Ação       | - Usuário deseja acessar a CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso. |
|     Evento      | -                                                                                                                                       |
| Rastreabilidade | RF3 - Ter acesso a versão digital da CNH,<br> RF19 - Validar documentos, <br>RF19 - Validar documentos                                  |

## UC04 - Acessar Histórico da CNH

|      UC04       | Descrição                                                                                                                                                                                                                                                   |
| :-------------: | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|    Descrição    | Acessar o Histórico de habilitações                                                                                                                                                                                                                         |
|      Ator       | Usuário                                                                                                                                                                                                                                                     |
|  Pré-condições  | Estar logado no CDT, ter habilitação cadastrada.                                                                                                                                                                                                            |
|      Ação       | - Usuário deseja acessasr o históico de CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Histórico". |
|     Evento      | -                                                                                                                                                                                                                                                           |
| Rastreabilidade | RF5 - Ter todas as informações dos documentos, RF10 - Gerenciar documentos                                                                                                                                                                                  |

## UC05 - Exportar CNH

|      UC05       | Descrição                                                                                                                                                                                                                                                                                                                 |
| :-------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|    Descrição    | Obter a CNH em pdf para compartilhamento                                                                                                                                                                                                                                                                                  |
|      Ator       | Usuário                                                                                                                                                                                                                                                                                                                   |
|  Pré-condições  | Estar logado no CDT, ter habilitação cadastrada.                                                                                                                                                                                                                                                                          |
|      Ação       | - Usuário deseja exportar a CNH em pdf;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Exportar";<br> - Usuário confirma a exportação e valida com a chave de acesso. |
|     Evento      | -                                                                                                                                                                                                                                                                                                                         |
| Rastreabilidade | RF3 - Ter acesso a versão digital da CNH, RF5 - Ter todas as informações dos documentos, RF10 - Gerenciar documentos                                                                                                                                                                                                      |

## Bibliografia

> - WHITNEY, Ellen - Introduction to Gathering Requirements and Creating Use Cases. Disponível em: <https://www.codemag.com/article/0102061/Introduction-to-Gathering-Requirements-and-Creating-Use-Cases>. Acesso em: 18 Março 2021.

## Versionamento

| Versão | Data       | Modificação                        | Autor      |
| ------ | ---------- | ---------------------------------- | ---------- |
| 0.1    | 18/03/2021 | Criação dos tópicos do documento   | Emily Dias |
| 0.2    | 19/03/2021 | Adição de algumas UCs no documento | Emily Dias |
