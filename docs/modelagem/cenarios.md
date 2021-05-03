# Cenários

## 1. Introdução
&emsp;&emsp;O propósito desse documento é exibir a metodologia utilizada para aplicar o método de cenários na modelagem dos requsitos e seus resultados.<br> 
&emsp;&emsp;A técnica de cenários se trata de utilizar um conjunto de narrativas de situações e caminhos que se encontram no escopo do sistema e que possibilita a identificação de componentes de design. Em outras palavras, os cenários descrevem, narrando de forma textual, o sistema da perspectiva de um ou mais atores em determinadas situações de uso das funcionalidades.

## 2. Metodologia 
&emsp;&emsp;A aplicação da técnica deu-se com auxílio dos participantes da equipe que utilizam a aplicação. É interessante mostrar que, por ter um escopo razoavelmente grande, o CDT tem uma gama muito ramificada de usuários por funcionalidades. Por exemplo, nem sempre um usuário tem veículos em seu nome e, se ele fosse utilizado para traçar os cenários, as funcionalidades referentes a veículos ficariam de fora da técnica.<br>
&emsp;&emsp;Sendo assim, foi utilizado também o [**tutorial de utilização do CDT**](https://portalservicos.denatran.serpro.gov.br/carteiradigital/tutoriais/html/demo_1.html) disponibilizado pelo DENATRAN, para identificar o máximo de possibilidades de cenários.

### 2.1. Nomenclatura 
&emsp;&emsp;Para especificar os cénarios foram utilizadas tabelas contendo os seguintes Elementos:

- **Objetivo:** o que os atores tem como finalidade nesse cenário;
- **Contexto:** onde se inicia a interação, quanto tempo dura, e qual o estado dos atores antes de iniciar;
- **Atores:** todos os envolvidos que tem participação no cenário;
- **Recursos:** o que é necessário para a situação acontecer;
- **Exceção:** o que levará os atores para fluxos de exceção;
- **Episódios:** narração detalhada das interações;
- **Rastreabilidade:** os requisitos envolvidos.

## 3. Cenários
&emsp;&emsp;A seguir estão os resultados da aplicação dessa técnica. Os cenários a seguir contemplam todos os requisitos referentes as funcionalidades já presentes na aplicação. 
### C01 - Cadastrar
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Criar uma conta no GOV.br. |
| **Contexto** | - Local: Tela inicial da aplicação;<br> - Tempo: 5 a 7 minutos;<br> - Pré-condição: Acessoa à internet. |
| **Atores** | Usuários |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão. |
| **Episódios** | - Usuário abre a aplicação;<br>- Usuário seleciona a opção entrar com GOV.br;<br> - Usuário seleciona a opção "Crie sua conta";<br> - Usuário seleciona uma opção de cadastro no sistema GOV.br;<br>- Usuário informa os dados requisitados na opção selecionada. |
| **Rastreabilidade** | RF8 |

### C02 - Realizar o primeiro login na aplicação
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Realizar login no CDT pela primeira vez. |
| **Contexto** | - Local: Tela inicial da aplicação;<br> - Tempo: 1 a 2 minutos;<br> - Pré-condições: Acesso à internet e cadastro no sistema GOV.br. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Perda de conexão;<br>- Usuário não possuir cadastro no GOV.br;<br>- Usuário esquece a senha;<br>- Usuário não recebe o código de validação. |
| **Episódios** | - Usuário abre a aplicação;<br>- Usuário seleciona a opção "Entrar com GOV.br";<br>- Usuário informa o CPF e senha;<br>- Usuário selecionaa opção "Entrar";<br>- Usuário preenche o campo "celular";<br>- Usuário seleciona a opção "Enviar Código.";<br>- Usuário recebe o código de confirmação por sms;<br>- Usuário digita o código recebido no campo "Código de confirmação SMS";<br>- Usuário seleciona a opção "validar código";<br>- Usuário autoriza utilização dos dados pessoais na aplicação. |
| **Rastreabilidade** | RF1 |

### C03 - Realizar login regular
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Realizar login no CDT. |
| **Contexto** | - Local: Tela inicial da aplicação;<br> - Tempo: 1 minuto;<br> - Pré-condições: Acesso à internet, cadastro no sistema GOV.br e já ter feito longin alguma vez. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Perda de conexão;<br>- Usuário não possuir cadastro no GOV.br;<br>- Usuário esquece a senha. |
| **Episódios** | - Usuário abre a aplicação;<br>- Usuário seleciona a opção "Entrar com GOV.br";<br>- Usuário informa o CPF e senha;<br>- Usuário selecionaa opção "Entrar";<br>- Usuário seleciona a opção "validar código";<br>- Usuário autoriza utilização dos dados pessoais na aplicação. |
| **Rastreabilidade** | RF1 |

### C04 - Realizar logout
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Realizar logout no CDT. |
| **Contexto** | - Local: Aba do menu de opções;<br> - Tempo: 10 segundos;<br> - Pré-condição: Estar logado no CDT. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega.<br> |
| **Episódios** | - Usuário acessa o menu de opções;<br> - Usuário seleciona a opção "Sair da conta". |
| **Rastreabilidade** | RF9 |

### C05 - Baixar a CNH digital com validação por certificação digital
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Baixar o documento de CNH no APP. |
| **Contexto** | - Local: Aba Habilitação;<br> - Tempo: 1 minuto;<br> - Pré-condição: Estar logado no CDT, ter certificação digital ativa no portal do DENATRAN e ser o primeiro documento digital a ser baixado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Perda de conexão;<br>- Usuário não ter certificação digital do DENATRAN. |
| **Episódios** | - Usuário seleciona a opção "Habilitação" na Home do CDT;<br> - Usuário seleciona a opção "Toque para baixar sua CNH";<br>- Usuário seleciona a opção "Com certificado digital";<br> - Usuário cadastra uma chave de acesso;<br>- Usuário seleciona sim ou não para biometria em dispositivos compatíveis. |
| **Rastreabilidade** | RF3, RF10, RF19 |

### C06 - Baixar a CNH digital sem validação por certificação digital
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Baixar o documento de CNH no APP. |
| **Contexto** | - Local: Aba Habilitação;<br> - Tempo: 2 minutos;<br> - Pré-condição: Estar logado no CDT, ser o primeiro documento digital a ser baixado e ter realizado a validação pessoalmente no DETRAN. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado e dados da CNH. |
| **Exceção** | - Smartphone descarrega;<br>- Perda de conexão;<br>- Usuário não ter validado do DETRAN<br>- Usuário não ter acesso aos dados da CNH. |
| **Episódios** | - Usuário seleciona a opção "Habilitação" na Home do CDT;<br> - Usuário seleciona a opção "Toque para baixar sua CNH";<br>- Usuário informa o número de registro da CNH;<br>- Usuário informa o código de segurança da CNH;<br>- Usuário seleciona a opção "Baixar CNH digital";<br> - Usuário cadastra uma chave de acesso;<br>- Usuário seleciona sim o não para biometria em dispositivos compatíveis. |
| **Rastreabilidade** | RF3, RF10, RF19 |

### C07 - Baixar a CNH digital com validação pelo smartphone
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Baixar o documento de CNH no APP. |
| **Contexto** | - Local: Aba Habilitação;<br> - Tempo: 2 minutos;<br> - Pré-condição: Estar logado no CDT e ser o primeiro documento digital a ser baixado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado e QR code da CNH. |
| **Exceção** | - Smartphone descarrega;<br>- Perda de conexão;<br>- Usuário não ter o QR code da CNH;<br>- Usuário não saber o CEP. |
| **Episódios** | - Usuário seleciona a opção "Habilitação" na Home do CDT;<br> - Usuário seleciona a opção "Toque para baixar sua CNH";<br>- Usuário seleciona a opção "Validar utilizando o celular";<br>- Usuário concede acesso do CDT à câmera do aparelho;<br>- Usuário avança nas informações deslizando para esquerda;<br>- Usuário seleciona a opção "Vamos começar?"<br>- Usuário escaneia o QR code da CNH;<br>- Usuário seleciona a opção "Avançar";<br>- Usuário escaneia o seu rosto de olhos fechados;<br>- Usuário escaneia o seu rosto de olhos aberto e sorrindo;<br>- Usuário informa o CEP do seu endereço;<br>- Usuário seleciona a opção "Validar";<br>- Usuário informa o número de telefone com DDD;<br>- Usuário seleciona a opção "Concluir";<br> - Usuário cadastra uma chave de acesso;<br>- Usuário seleciona sim o não para biometria em dispositivos compatíveis. |
| **Rastreabilidade** | RF3, RF10, RF19 |

### C08 - Acessar a CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar a CNH digital |
| **Contexto** | - Local: Home do CDT  <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação baixada e conta validada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso; |
| **Episódios** | - Usuário seleciona a opção "Habilitação";<br> - Usuário digitar a chave de acesso ou insere a digital. |
| **Rastreabilidade** | RF3, RF8, RF19 |

### C09 - Exportar CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Obter a CNH em PDF. |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 45 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação baixada e conta validada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário não tem espaço de armazenamento;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário seleciona a opção "Habilitação";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Exportar";<br> - Usuário confirma a exportação;<br>- Usuário digita a chave de acesso ou insere a digital;<br>- Usuário informa o destino par a importação. |
| **Rastreabilidade** | RF3, RF5, RF10  |

### C10 - Remover CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Remover a CNH baixada. |
| **Contexto** |  - Local: Home do CDT <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação baixada e conta validada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário seleciona a opção "Habilitação";<br> - Usuário digitar a chave de acesso ou insere a dital;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Remover";<br> - Usuário informa a chave de acesso;<br>- Usuário seleciona a opção "Confirmar remoção". |
| **Rastreabilidade** | RF10, RF11 |

### C11 - Acessar Histórico da CNH
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar o Histórico de habilitações.  |
| **Contexto** |  - Local: Home do CDT <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação baixada e conta validada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário seleciona a opção "Habilitação" na tela inicial;<br> - Usuário digita a chave de acesso ou isere a digital;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Histórico da CNH". |
| **Rastreabilidade** | RF5, RF10 |

### C12 - Baixar CRLV digital de todos os veículos que é proprietário
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Baixar o CRLV de todos os veículos em seu nome no APP. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, não ter CNH baixada e ter veículo em seu nome. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado e dados do CRLV. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter veículos no nome;<br>- Usuário não ter os dados do CRLV |
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário seleciona a opção "Toque para adicionar um CRLV";<br> - Usuário informa o número do RENAVAM;<br>- Usuário informa o númeor de segurnaça do CRV;<br>- Usuário seleciona a opção "Adicionar";<br>- Usuário cadastra uma chave de acesso;<br>- Usuário seleciona sim o não para biometria em dispositivos compatíveis.|
| **Rastreabilidade** | RF4, RF10 |

### C13 - Acessar o CRLV de um veículo 
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar o CRLV de um veículo. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo em seu nome e ter CNH ou CRLV baixados. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br>- Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer consultar o CRLV. |
| **Rastreabilidade** | RF4, RF5, RF13, RF15 |

### C14 - Consultar o Recall de um veículo 
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Consultar os detalhes do Recall de um veículo. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 45 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo com Recall em seu nome e ter CNH ou CRLV baixados. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso;<br> - Perda de conexão. |
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br>- Usuário localiza o veículo que possui Recall;<br> - Usuário seleciona o veículo;<br>- Usuário desliza a tela pra a esquerda quatro vezes;<br>- Usuário seleciona a opção "Sim, toque para detalhar". |
| **Rastreabilidade** | RF4, RF5, RF10, RF13, RF15 |

### C15 - Exportar o CRLV de um veículo 
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Obter o CRLV de um veículo em PDF. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 45 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo em seu nome e ter CNH ou CRLV baixados. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega.<br>- Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer consultar o CRLV;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Exportar";<br> - Usuário confirma a exportação;<br>- Usuário digita a chave de acesso ou insere a digital;<br>- Usuário informa o destino par a importação. |
| **Rastreabilidade** | RF4, RF5, RF10, RF13 |

### C16 - Remover o CRLV de um veículo 
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Remover o CRLV de um veículo. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 45 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo em seu nome e ter CRLV baixada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega.<br>- Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer consultar o CRLV;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Remover";<br>- Usuário digita a chave de acesso ou insere a digital.|
| **Rastreabilidade** | RF10, RF11 |

### C17 - Indicar o principal condutor
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Indicar o principal condutor de um veículo. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 1 minuto<br> - Pré-condição: Estar logado no CDT, ter veículo em seu nome e CRLV baixada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega.<br>- Usuário esquece a chave de acesso. |
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer indicar o principal condutor;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Principal condutor";<br>- Usuário digita o CPF do principal condutor;<br>- Usuário seleciona a opção "Indicar";<br>- Usuário seleciona a opção "Entendi".|
| **Rastreabilidade** | RF10, RF23 |

### C18 - Excluir o principal condutor
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Excluir o principal condutor de um veículo. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo em seu nome com principal condutor indicado e ter CNH ou CRLV baixados. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso.|
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer excluir o principal condutor;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Principal condutor";<br>- Usuário seleciona a opção "Excluir";<br>- Usuário seleciona a opção "Sim";<br>- Usuário seleciona a opção "Entendi".|
| **Rastreabilidade** | RF10, RF23 |

### C19 - Aceitar ser o principal condutor
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Aceitar um convite para ser o principal condutor de um veículo. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter um convite para ser o principal condutor de um veículo e ter CNH baixada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso.|
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que possui o convite;<br> - Usuário seleciona a opção "Aceitar".|
| **Rastreabilidade** | RF10, RF23 |

### C20 - Recusar ser o principal condutor
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Deixar de ser o principal condutor de um veículo. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 45 segundos<br> - Pré-condição: Estar logado no CDT, ser o principal condutor de um veículo e ter CNH baixada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso.|
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer deixar de ser o principal condutor;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Recusar principal condutor";<br>- Usuário seleciona a opção "Sim".|
| **Rastreabilidade** | RF10, RF23 |

### C21 - Compartilhar o CRLV
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Compartilhar o CRLV com o algum outro condutor. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 45 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo em seu nome e CRLV baixados. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso,<br>- Usuário esquece os dados do condutor.|
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer compartilhar o CRLV;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Compartilhar";<br> - Usuário seleciona a opção "Toque para compartilhar esse veículo";<br>- Usuário digita o CPF do condutor;<br>- Usuário digita o apelido do condutor;<br>- Usuário seleciona a opção "Compartilhar".|
| **Rastreabilidade** | RF10|

### C22 - Parar de compartilhar o CRLV
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Parar de compartilhar o CRLV com o algum outro condutor. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 45 segundos<br> - Pré-condição: Estar logado no CDT, ter veículo em seu nome e ter CRLV compartlhada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso.|
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer compartilhar o CRLV;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Compartilhar";<br> - Usuário seleciona a opção "Toque para compartilhar esse veículo";<br>- Usuário condutor com o qual deseja parar de compartilhar;<br>- Usuário seleciona a opção "Remover";<br> - Usuário digitar a chave de acesso ou insere a digital.|
| **Rastreabilidade** | RF10 |

### C23 - Aceitar compartilhamento de CRLV
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Aceitar um convite de compartilhamento de CRLV. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter um convite de compartilhamento de CRLV de um veículo e ter CNH baixada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso.|
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que possui o convite;<br> - Usuário seleciona a opção "Aceitar".|
| **Rastreabilidade** | RF10 |

### C24 - Remover Compartilhamento de CRLV
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Recusar o compartilhamento de CRLV. |
| **Contexto** | - Local: Home do CDT<br>- Tempo: 45 segundos<br> - Pré-condição: Estar logado no CDT, ter crlv compartilhado e ter CNH baixada. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet, CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br>- Usuário esquece a chave de acesso.|
| **Episódios** | - Usuário seleciona a opção "Veículos";<br> - Usuário digitar a chave de acesso ou insere a digital;<br> - Usuário seleciona o veículo que quer recusra compartilhamento;<br> - Usuário seleciona o icone de três pontos verticais;<br> - Usuário seleciona a opção "Remover compartilhamento".;<br>- Usuário digitar a chave de acesso ou insere a digital. |
| **Rastreabilidade** | RF10 |

### C25 - Consultar Infrações por Infrator
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Consultar se há infração por infrator cadastrado |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação baixada.|
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão. |
| **Episódios** | - Usuário seleciona a opção "Infrações";<br> - Usuário seleciona a opção "Por Infrator". |
| **Rastreabilidade** | RF7, RF15  |

### C26 - Solicitar boleto para infrações por infrator
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Solicitar boleto para pagar a infração pendente. |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter habilitação baixada, ter infração por infrator registrada.|
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter infrações pendentes por infrator.|
| **Episódios** |  - Usuário seleciona a opção "Infrações" na tela inicial;<br> - Usuário seleciona a opção "Por Infrator";<br> - Usuário seleciona a infração;<br> - Usuário seleciona a opção "Solicitar Boleto". |
| **Rastreabilidade** | RF7, RF15, RF17  |

### C27 - Consultar Infrações por Veículo
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Consultar se há infrações por Veículos cadastrados |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter veículo cadastrado. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão.<br>- Usuário não ter veículo cadastrado.|
| **Episódios** | - Usuário seleciona a opção "Infrações";<br> - Usuário seleciona a opção "Por Veículo". |
| **Rastreabilidade** | RF2, RF15 |

### C28 - Solicitar boleto para infrações por veículo
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Solicitar boleto para pagar a infração pendente por veículo. |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter veículo  cadastrado e com infrações. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter veículo cadastrado. |
| **Episódios** | - Usuário seleciona a opção "Infrações";<br> - Usuário seleciona a opção "Por Veículo";<br> - Usuário seleciona a infração;<br> - Usuário seleciona a opção "Solicitar Boleto". |
| **Rastreabilidade** | RF17 |

### C29 - Informar real infrator
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Declarar o real responsável por uma infração. |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 30 segundos <br> - Pré-condição: Estar logado no CDT, ter veículo  cadastrado e com infrações. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão;<br> - Usuário não ter veículo cadastrado. |
| **Episódios** | - Usuário seleciona a opção "Infrações";<br> - Usuário seleciona a opção "Por Veículo";<br> - Usuário seleciona a infração;<br> - Usuário seleciona a opção "Informar real infrator". |
| **Rastreabilidade** | RF20 |

### C30 - Consultar campanhas educacionais
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Exibir a campanha educacional vigente no momento. |
| **Contexto** | - Local: Home do CDT<br> - Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT, ter campanha vigente. |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão.|
| **Episódios** | - Usuário seleciona a opção "Educação" na tela inicial. |
| **Rastreabilidade** | RF12, RF25 |

### C31 - Acessar mensagens do sistema
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Acessar mensagens do sistema. |
| **Contexto** | - Local: Home do CDT<br> - Tempo: 20 segundos<br> - Pré-condição: Estar logado no CDT |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão.|
| **Episódios** | - Usuário toca no íconde de envelope no barra superior. |
| **Rastreabilidade** | RF12, RF24 |

### C32 - Gerenciar foto
| Elementos | Respostas |
| -- | -- |
| **Objetivo** |  Acesssar opções de gerenciamento da foto de perfil. |
| **Contexto** | - Local: Home do CDT<br> - Tempo: 20 segundos<br> - Pré-condição: Estar logado no CDT |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega;<br> - Perda de conexão.|
| **Episódios** | - Usuário toca no ícone de câmera a baixo do círculo onde está a inicial do seu nome. |
| **Rastreabilidade** | RF10 |

### C33 - Acessar a política de privaciadade
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Ler a política de privacidade do sistema. |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 20 segundos<br> - Pré-condição: Estar logado no CDT |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega.|
| **Episódios** | - Usuário acessa o menu de opções;<br> - Usuário seleciona a opção "Política de privacidade".|
| **Rastreabilidade** | RF14, RF12 |

### C34 - Acessar o termo de responsabilidade
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Ler o termo de responsabilidade. |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 20 segundos<br> - Pré-condição: Estar logado no CDT |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega.|
| **Episódios** | - Usuário acessa o menu de opções;<br> - Usuário seleciona a opção "Termo de responsabilidade".|
| **Rastreabilidade** | RF12 |

### C35 - aderir ao SNE 
| Elementos | Respostas |
| -- | -- |
| **Objetivo** | Aderir ao sistema de notificação eletrônica. |
| **Contexto** | - Local: Home do CDT <br> - Tempo: 30 segundos<br> - Pré-condição: Estar logado no CDT |
| **Atores** | Usuário |
| **Recursos** | Smartphone, internet e CDT instalado. |
| **Exceção** | - Smartphone descarrega.|
| **Episódios** | - Usuário acessa o menu de opções;<br>- Usuário seleciona a opção "Preferências";<br>- Usuário seleciona a opção "Sistema de Notificação Eletrônica - SNE";<br>- Usuário lê os termos de adesão;<br>- Usuário seleciona a opção "Aderir";<br>- Usuário informa o número de registro da CNH;<br>- Usuário informa o código de segurança da CNH;<br>- Usuário seleciona a opção "Aderir ao SNE". |
| **Rastreabilidade** | RF21 |

## 4. Bibliografia
> - SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 10;
> - LUCENA, Sérgio; KEMCZINSKI, Avenilde; GASPARINE, Isabela; MATOS, Alexandre; OGAWA, Aline; Modelagem de requisitos baseada em cenários para o Storyboard da Metodologia para Construção de  Objetos de Aprendizagem Interativos.

## 5. Versionamento
| Versão | Data | Modificação | Autor |
|:-:|--|--|--|
|1.0|16/03/2021| Adição dos tópicos da página e cenários iniciais | Daniel P. e Yan Andrade |
|2.0|19/03/2021| Adição dos cenários 9 a 16 e correção de pequenos erros ortográficos | Yan Andrade |
|3.0|20/03/2021| Correção dos cenários e adição do restante. | Daniel Porto |
|3.1|20/03/2021| Adição da introdução e da descrição da metodologia| Daniel Porto |
|3.2|21/03/2021| Correção de erros de digitação após revisão | Daniel Porto |
|  3.3   | 02/05/2021 | Ajuste de documento | Emily Dias |
