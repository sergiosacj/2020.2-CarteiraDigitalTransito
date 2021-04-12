# Validação por pontos de vista (Viewpoint)

## Introdução

&emsp;&emsp; A técnica é baseada no fato de que os requisitos de software podem e devem ser eliciados de diferentes pontos de vista, e que a avaliação resultante das diferenças deles pode ser usada como uma forma de auxiliar na validação inicial dos requisitos. É também uma linguagem para expressar diferentes pontos de vista, além de prover um conjunto de heurísticas para realizar uma análise sintaticamente orientada às visões propostas. Essa análise de pontos de vista é capaz de diferenciar entre informações ausentes e informações conflitantes, fornecendo, assim, suporte para a resolução de pontos de vista.

## Metodologia

&emsp;&emsp; A metodologia adotada para a execução da validação por pontos de vista foi proposta por Julio Cesar Sampaio do Prado Leite e Peter A. Freeman. Além de ser recomendada para a disciplina, se adequa ao escopo do nosso projeto. Desse modo, o domínio utilizado para os pontos de vistas apresentados é o próprio domínio geral da aplicação, tendo como base todos os artefatos gerados até então. O escopo será reduzido e irá desconsiderar documentos propostos pelo próprio app, visto que não foram elaborados pelos integrantes do trabalho e foram criados sobre diferentes lincensas.

&emsp;&emsp; Cada viewpoint adotará uma perspectiva diferente visando validar diferentes pontos de vista. A Viewpoint Processo adotará a perspectiva de processo, enquanto a Viewpoint Autor adotará a perspectiva do autor.

&emsp;&emsp; A única mudança adotada, em relação a metodologia utilizada da bibliografia já citada, é de substituir a seção que indica se um objeto pertence ao outro por meio da identação na perspectiva de processo (quando a relação é pequena apenas é feito uma separação pela operação de parênteses). Desse modo, é possível determinar essa relação visualmente, o que simplifica o uso das viewpoints.

## Viewpoint Processo

```
Perspectiva de Processo:
    ((usuario =id-usuario =nome =foto-perfil)
     (habilitacao =cnh =qr-code)
     (veiculos (veiculo =id-veiculo))
     (educacao (campanha =id-campanha =imagem-promocional))
     (infracoes
        (por-infratores =adesao-SNE (infrator =id-infrator))
        (por-veiculos (veiculo =id-veiculo)))
     (central-mensagens (mensagem =id-mensagem =data =hora =conteudo))
     (barra-lateral =central-mensagens =politica-privacidade =termo-responsabilidade =preferencias =suport =sobre))

Hierarquia:
(é-um
    (objeto (habilitacao veiculos educacao infracoes central-mensagens barra-lateral))
    (agente (usuario infrator)))
```

## Viewpoint Autor

&emsp;&emsp; O autor reponsável pela perspectiva é o Sérgio Cipriano. A persperctiva apresentada é um retrato da sua visão sobre o app no dia 12/04/2021.

```
Perspectiva do Autor:
    ((usuario =nome =foto-perfil(=camera =galeria))
     (habilitacao =digital-identificacao =cnh =qr-code =historico)
     (veiculos (veiculo))
     (educacao (campanha))
     (infracoes
        (por-infratores =termo-adesao-SNE)
        (por-veiculos)
     (central-mensagens)
     (barra-lateral =central-mensagens =politica-privacidade =termo-responsabilidade =preferencias =suport =sobre))

Hierarquia:
(é-um
    (objeto (habilitacao veiculos educacao infracoes central-mensagens barra-lateral))
    (agente (usuario)))
```

## Conclusão sobre os resultados

&emsp;&emsp; O objetivo dessa seção é fazer a identificação e comparação das duas viewpoints e ver se existe alguma inconsistência, fato errado ou faltante dado os dois pontos de vista.

### Inconsistências

#### Perspectiva do Processo

- Não apresenta nenhuma inconsistência.

#### Perspectiva do Autor

- Não é possível verificar a função da central de mensagens, ou seja, não está definido que tipo de comunicação ocorre naquela aba.
- Na seção das infrações, o termo de adesão do SNE pode ser facilmente aceito, mas, para lê-lo, é necessário navegar por dois botões extras. Essa decisão incentiva que o usuário aceite o termo sem realizar a leitura, o que é imoral.

### Fatos faltantes

&emsp;&emsp; Os fatos relatados não estavam presentes em ambas as perspectivas:

- Veículos (objeto - Lo10)
- Infrações (objeto - Lo11)
- Campanhas (objeto - Lo12)
- Histórico (objeto - Lo14)

&emsp;&emsp; A ausência dos fatos citados está diretamente ligada às perspectivas trabalhadas não terem tais objetos no banco de dados.

## Avaliação e Integração

&emsp;&emsp; É notório que os elementos expostos na perspectiva do processo estão melhor detalhados, tendo em vista que representam uma visão geral sobre a aplicação. Desse modo, é importante apontar que fatos inconsistentes na perspectiva do autor não são considerados inconsistentes na perspectiva do processo já que refletem uma visão mais técnica do software e não como um produto em si.

&emsp;&emsp; Além disso, é válido afirmar que os fatos faltantes estão de acordo com os requisitos elicitados e verificados até o presente momento (12/04/2021), como também o com o léxico trabalhado.

## Bibliografia

> do Prado Leite, Julio Cesar Sampaio, and Peter Freeman. "Requirements validation through viewpoint resolution." IEEE Trans. Software Eng. 17.12 (1991): 1253-1269.

## Versionamento

| Versão | Data | Modificação | Autor |
|--|--|--|--|
| 1.0 | 12/04/2021 | Criação de todos os tópicos do documento | Sérgio Cipriano |