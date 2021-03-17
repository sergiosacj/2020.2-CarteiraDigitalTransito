## Introdução

## Metodologia 

## Cenários

### C01 - Realizar login
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Realizar login no CDT |
| **Contexto** | - Local: Tela inicial da aplicação;<br> - Tempo: 1 a 2 minutos;<br> - Pré-condições: Acesso à internet e cadastro no sistema GOV.br. |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não possuir cadastro no GOV.br;<br> - Usuário esquece a senha. |
| **Episódios** | - Novo usuário instala e abre a aplicação;<br> - Usuário seleciona a opção "Entrar com GOV.br";<br> - Usuário informa o CPF e senha;<br> - Usuário autoriza utilização dos dados pessoais na aplicação. |
| **Rastreabilidade** | RF1 |

### C02 - Cadastrar
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Crair uma conta no GOV.br |
| **Contexto** | - Local: Tela inicial da aplicação;<br> - Tempo: 5 a 7 minutos;<br> - Pré-condição: Acessoa à internet. |
| **Atores** | Usuários |
| **Rescursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não possuir cadastro no GOV.br;<br> - Usuário esquece a senha. |
| **Episódios** | - Usuário abre a aplicação;<br>- Usuário seleciona a opção entrar com GOV.br;<br> - Usuário percebe que não tem cadatro no GOV.br;<br> - Usuário seleciona a opção "Crie sua conta";<br> - Usuário seleciona uma opção de cadastro no sistema GOV.br.<br> |
| **Rastreabilidade** | RF8 |

### C03 - Realizar logout
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Realizar logout no CDT |
| **Contexto** | - Local: Aba do menu de opções;<br> - Tempo: 5 segundos;<br> - Pré-condição: Estar logado no CDT |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega.<br> |
| **Episódios** | - Usuário deseja sair da aplicação;<br> - Usuário acessa o menu de opções;<br> - Usuário seleciona a opção "Sair da conta". |
| **Rastreabilidade** | RF9|

### C04 - Cadastrar CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Cadastrar o documento de CNH |
| **Contexto** | - Local: Aba Habilitação;<br> - Tempo: 2 a 3 minutos;<br> - Pré-condição: Estar logado no CDT |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega; <br> - Perda de concexão;  |
| **Episódios** | - Usuário deseja ter acesso a sua CNH;<br> - Usuário seleciona a opção "Habilitação" na Home do CDT;<br> - Usuário seleciona a opção "Toque para baixar sua CNH";<br> - Usuário registra uma chave de acesso; |
| **Rastreabilidade** | RF3, RF10, RF19 | 

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessa a cnh digital |
| **Contexto** | - Local: Aba Habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso; |
| **Episódios** | - Usuário deseja acessar a CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso. |
| **Rastreabilidade** | RF3, RF19 |

### C06 - Exportar CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Obter a CNH em pdf para compartilhamento |
| **Contexto** | - Local: Aba habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada. |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega<br>; - Usuário não ter espço de armazenamento<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário deseja exportar a CNH em pdf;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Exportar";<br> - Usuário confirma a exportação e valida com a chave de acesso. |
| **Rastreabilidade** | RF3, RF5, RF10  |

### C07 - Remover a habilitação
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Remover a CNH cadastrada |
| **Contexto** |  - Local: Aba habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada. |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário deseja remover a CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Remover";<br> - Usuário informa a chave de acesso; |
| **Rastreabilidade** | RF10, RF11 |

### C08 - Acessar Histórico da CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar o Histótico de habilitações  |
| **Contexto** |  - Local: Aba habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada. |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário deseja acessasr o históico de CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Histórico". |
| **Rastreabilidade** | RF5, RF10 |

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |   |
| **Contexto** | - Local: <br> - Tempo: <br> - Pré-condição: |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> |
| **Episódios** | |
| **Rastreabilidade** |   |

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |   |
| **Contexto** | - Local: <br> - Tempo: <br> - Pré-condição: |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> |
| **Episódios** | |
| **Rastreabilidade** |   |

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |   |
| **Contexto** | - Local: <br> - Tempo: <br> - Pré-condição: |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> |
| **Episódios** | |
| **Rastreabilidade** |   |

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |   |
| **Contexto** | - Local: <br> - Tempo: <br> - Pré-condição: |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> |
| **Episódios** | |
| **Rastreabilidade** |   |

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |   |
| **Contexto** | - Local: <br> - Tempo: <br> - Pré-condição: |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> |
| **Episódios** | |
| **Rastreabilidade** |   |

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |   |
| **Contexto** | - Local: <br> - Tempo: <br> - Pré-condição: |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> |
| **Episódios** | |
| **Rastreabilidade** |   |

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |   |
| **Contexto** | - Local: <br> - Tempo: <br> - Pré-condição: |
| **Atores** | Usuário |
| **Rescursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> |
| **Episódios** | |
| **Rastreabilidade** |   |

##Bibliografia
>

## Versionamento
| Versão | Data | Modificação | Autor |
|:-:|--|--|--|
|1.0|16/03/2021| Adição dos tópicos da página e cenários iniciais | Daniel P. e Yan Andrade |
