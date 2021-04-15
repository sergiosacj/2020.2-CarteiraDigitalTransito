# Verificação - NFR Framework

Para a verificação do NFR foi utilizado a estratégia de verificação por checklist, por ser mais simples, por ter uma visualização melhor do Framework e por ser mais objetivo. Este documento é bom para identificar as possíveis falhas e erros encontrados neste artefato.

## 1. Contexto

- Técnica utilizada: Técnica de Leitura Check-List
- Autores do documento: Emily Dias e Daniel Porto.
- Revisor: Yan Andrade.
- Inspetor: Emily Dias.

O documento verificado está disponível [aqui](https://requisitos-de-software.github.io/2020.2-CarteiraDigitalTransito/modelagem/nfr_framework/)

## 2. Checklist

### 2.1. Legenda

|Símbolo|Descrição|
|:-|:-|
|OK|Contém|
|X|Não contém|

### 2.2. Resultados

|Número|Itens|NFR Usabilidade|NFR Eficiência|NFR Confiabilidade|NFR Portabilidade|
|:-|:-:|:-:|:-:|:-:|:-:|
|1| Respeita as regras de metodologia?|OK|OK|OK|OK|
|2| Softgoals autoexplicativos?|OK|OK|OK|OK|
|3| Operadores com finalidades definidas?|OK|OK|OK|OK|
|4| Operadores geram impactos nos softgoals?|OK|OK|OK|OK|
|5| Operadores geram impactos em outros operadores?|OK|OK|OK|X|
|6| SoftGoals geram impactos em outros softgoals?|OK|OK|OK|OK|
|7| Existe ao menos um operador que tenha dependências(AND/OR) para atender o softgoal?|OK|OK|OK|OK|
|8| Softgoals escritos como nome?|OK|OK|OK|OK|
|9| Operadores escritos como verbos?|OK|OK|OK|OK|
|10| Os critérios são completamente satisfatórios?|X|X|X|X|
|11| Os critérios são parcialmente satisfatórios?|OK|OK|OK|OK|
|12| Existência de softgoals ou operadores que não são satisfatórios?|OK|OK|OK|OK|
|13| Possui rastreabilidade?|OK|OK|OK|OK|
|14| Possui versionamento?|OK|OK|OK|OK|
|15| NFR condiz com requisitos já apresentados?|OK|OK|OK|OK|
||**Porcentagem de sucesso**|**93%**|**93%**|**93%**|**87%**|

## 3. Conclusão

Com este documento de verificação foi detectado que o documento de NFR ficou como esperado com resalvas em algumas coisas por exemplo, os critérios do app não são completamente satisfatórios e o NFR de Portabilidade não tem operadores que geram impactos em outros.

## 4. Referências

- [Página de verificação do NFR do grupo Mia Ajuda - 2020.1](https://requisitos-de-software.github.io/2020.1-Mia-Ajuda/#/pages/analysis/verification/verificationNFR)

- [Página de verificação do NFR do grupo Guardiões da Saúde - 2020.1](https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/verificacao-e-validacao/verificacao/NFR/)

## 5. Versionamento
| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 10/04/2021 | Adição dos itens do documento | Emily Dias |
| 1.1 | 10/04/2021 | Padronizando o documento | Emily Dias |
| 1.2 | 14/04/2021 | Adicionando tópicos padrão | Emily Dias |