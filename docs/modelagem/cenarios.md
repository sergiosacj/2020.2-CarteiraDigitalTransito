## Introdução

## Metodologia 

## Cenários

### C01 - Realizar login
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Realizar login no CDT |
| **Contexto** | - Local: Tela inicial da aplicação;<br> - Tempo: 1 a 2 minutos;<br> - Pré-condições: Acesso à internet e cadastro no sistema GOV.br. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não possuir cadastro no GOV.br;<br> - Usuário esquece a senha. |
| **Episódios** | - Novo usuário instala e abre a aplicação;<br> - Usuário seleciona a opção "Entrar com GOV.br";<br> - Usuário informa o CPF e senha;<br> - Usuário autoriza utilização dos dados pessoais na aplicação. |
| **Rastreabilidade** | RF1 |

### C02 - Cadastrar
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Criar uma conta no GOV.br |
| **Contexto** | - Local: Tela inicial da aplicação;<br> - Tempo: 5 a 7 minutos;<br> - Pré-condição: Acessoa à internet. |
| **Atores** | Usuários |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não possuir cadastro no GOV.br;<br> - Usuário esquece a senha. |
| **Episódios** | - Usuário abre a aplicação;<br>- Usuário seleciona a opção entrar com GOV.br;<br> - Usuário percebe que não tem cadatro no GOV.br;<br> - Usuário seleciona a opção "Crie sua conta";<br> - Usuário seleciona uma opção de cadastro no sistema GOV.br.<br> |
| **Rastreabilidade** | RF8 |

### C03 - Realizar logout
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Realizar logout no CDT |
| **Contexto** | - Local: Aba do menu de opções;<br> - Tempo: 5 segundos;<br> - Pré-condição: Estar logado no CDT. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega.<br> |
| **Episódios** | - Usuário deseja sair da aplicação;<br> - Usuário acessa o menu de opções;<br> - Usuário seleciona a opção "Sair da conta". |
| **Rastreabilidade** | RF9|

### C04 - Cadastrar CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Cadastrar o documento de CNH |
| **Contexto** | - Local: Aba Habilitação;<br> - Tempo: 2 a 3 minutos;<br> - Pré-condição: Estar logado no CDT. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão.  |
| **Episódios** | - Usuário deseja ter acesso a sua CNH;<br> - Usuário seleciona a opção "Habilitação" na Home do CDT;<br> - Usuário seleciona a opção "Toque para baixar sua CNH";<br> - Usuário registra uma chave de acesso; |
| **Rastreabilidade** | RF3, RF10, RF19 | 

### C05 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar a cnh digital |
| **Contexto** | - Local: Aba Habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso; |
| **Episódios** | - Usuário deseja acessar a CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso. |
| **Rastreabilidade** | RF3, RF19 |

### C06 - Exportar CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Obter a CNH em pdf para compartilhamento |
| **Contexto** | - Local: Aba habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário não ter espaço de armazenamento;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário deseja exportar a CNH em pdf;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Exportar";<br> - Usuário confirma a exportação e valida com a chave de acesso. |
| **Rastreabilidade** | RF3, RF5, RF10  |

### C07 - Remover a habilitação
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Remover a CNH cadastrada |
| **Contexto** |  - Local: Aba habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário deseja remover a CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digitar a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Remover";<br> - Usuário informa a chave de acesso; |
| **Rastreabilidade** | RF10, RF11 |

### C08 - Acessar Histórico da CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar o Histótico de habilitações  |
| **Contexto** |  - Local: Aba habilitação <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário deseja acessasr o histórico de CNH;<br> - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digita a chave de acesso;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Histórico". |
| **Rastreabilidade** | RF5, RF10 |

### C09 - Consultar Infrações por Infrator
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Consultar se há infração por infrator cadastrado |
| **Contexto** | - Local: Aba Infrações <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada.|
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado.  |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão. |
| **Episódios** | - Usuário deseja consultar se há infrações em seu nome;<br> - Usuário seleciona a opção "Infrações" na tela inicial;<br> - Usuário seleciona a opção "Por Infrator". |
| **Rastreabilidade** | RF7, RF15  |

### C10 - Solicitar boleto para infrações por infrator
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Solicitar boleto para pagar a infração pendente. |
| **Contexto** | - Local: Aba Infrações <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação cadastrada, ter infração por infrator registstrada.|
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter infrações pendentes por infrator.|
| **Episódios** | - Usuário deseja solicitar boleto para pagar as infrações em seu nome;<br> - Usuário seleciona a opção "Infrações" na tela inicial;<br> - Usuário seleciona a opção "Por Infrator";<br> - Usuário seleciona a infração;<br> - Usuário seleciona a opção "Solicitar Boleto". |
| **Rastreabilidade** | RF7, RF15, RF17  |

### C11 - Consultar Infrações por Veículo
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Consultar se há infrações por Veículos cadastrados |
| **Contexto** | - Local: Aba Infrações <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter veículo  cadastrado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão.- Usuário não ter veículo cadastrado.|
| **Episódios** | - Usuário deseja consultar se há infrações em seu nome;<br> - Usuário seleciona a opção "Infrações" na tela inicial;<br> - Usuário seleciona a opção "Por Veículo". |
| **Rastreabilidade** | RF2, RF15 |

### C12 - Solicitar boleto para infrações por veículo
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Solicitar boleto para pagar a infração pendente por veículo. |
| **Contexto** | - Local: Aba Infrações <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter veículo  cadastrado. ter infração no veículo cadastrado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter veículo cadastrado; <br> - Usuário não ter infrações no veículo cadastrado. |
| **Episódios** | - Usuário deseja solicitar boleto para pagar as infrações do veículo cadastrado;<br> - Usuário seleciona a opção "Infrações" na tela inicial;<br> - Usuário seleciona a opção "Por Veículo";<br> - Usuário seleciona a infração;<br> - Usuário seleciona a opção "Solicitar Boleto". |
| **Rastreabilidade** | RF2, RF15, RF17 |

### C13 - Consultar campanhas educacionais
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Exibir a campanha educacional vigente no momento |
| **Contexto** | - Local: Aba Educação<br> - Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter campanha vigente. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão.|
| **Episódios** | - Usuário deseja consultar a campanha educacional vigente no momento;<br> - Usuário seleciona a opção "Educação" na tela inicial. |
| **Rastreabilidade** | RF12, RF25 |

### C14 - Consultar informações detalhadas dos veículos cadastrados
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Exibir informações detalhadas do veículo cadastrado |
| **Contexto** | - Local: Aba Veículos<br> - Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo cadastrado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter veículo cadastrado. |
| **Episódios** | - Usuário deseja consultar informações detalhadas de um veículo cadastrado;<br> - Usuário seleciona a opção "Veículos" na tela inicial;<br> - Usuário seleciona o veículo que quer consultar. |
| **Rastreabilidade** | RF13 |

### C15 - Consultar detalhes de recalls pendentes dos veículos cadastrados
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Exibir detalhes de recalls pendentes para os veículos cadastrados |
| **Contexto** | - Local: Aba Veículos<br> - Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo cadastrado, existir recall para o veículo com chassi determinado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter veículo cadastrado. |
| **Episódios** | - Usuário deseja consultar se há recalls pendentes de um veículos cadastrado;<br> - Usuário seleciona a opção "Veículos" na tela inicial;<br> - Usuário seleciona o veículo que quer consultar;<br> - Usuário desliza o dedo sobre a tela no sentido da direita para esquerda;<br> - Usuário seleciona a opção "Sim, toque para detalhar". |
| **Rastreabilidade** | RF13 |

### C16 - Acessar CRLV
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar o CRLV digital |
| **Contexto** | - Local: Aba Veículos<br> - Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo cadastrado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter veículo cadastrado. |
| **Episódios** | - Usuário deseja acessar o CRLV de um veículo cadastrado;<br> - Usuário seleciona a opção "Veículos" na tela inicial;<br> - Usuário seleciona o veículo que quer consultar;<br> - Usuário seleciona a opção "Baixar CRLV digital". |
| **Rastreabilidade** | RF4, RF5, RF10, RF13 |


##Bibliografia
>

## Versionamento
| Versão | Data | Modificação | Autor |
|:-:|--|--|--|
|1.0|16/03/2021| Adição dos tópicos da página e cenários iniciais | Daniel P. e Yan Andrade |
|2.0|19/03/2021| Adição dos cenários 9 a 16 e correção de pequenos erros ortográficos | Yan Andrade |
