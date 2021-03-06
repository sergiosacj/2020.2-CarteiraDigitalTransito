# NFR Framework

## 1. Introdução
&emsp;&emsp;Inicialmente proposto em 1992 e desenvolvido por Dr. Lawrence Chung, em 1999. “O NFR Framework é uma abordagem orientada a processos, onde os requisitos não-funcionais são explicitamente representados como metas a serem obtidas” [CHUNG, 1995].<br>
&emsp;&emsp;Estão relacionados com o comportamento dum sistema e não com as suas funcionalidades, pois descreve como o sistema funciona, não como o sistema faz.<br>
&emsp;&emsp;São, normalmente, representados por gráficos SIG (Softgoal Interdependency Graph), que descrevem as dependências entre os softgoals e como eles são decompostos;

## 2. Metodologia
&emsp;&emsp;Podem ser abordados diversos tipos de softgoals no NFR framework como: Usabilidade, Performance, Segurança, etc. Sendo assim, a aplicação da técnica deu-se, primeiramente, pela análise dos [requisitos não funcionais](../../elicitacao/requisitos/#requisitos-nao-funcionais) elicitados anteriormente. Tal análise teve como objetivo a identificação dos tipos de softgoals que os requisitos tentam cobrir.<br>
&emsp;&emsp;Analisados os requistos, conclui-se que, no geral, os requisitos do projeto buscam englobar as seguintes softgoals:

- Usabilidade;
- Eficiência;
- Confiabilidade;
- Portabilidade;

&emsp;&emsp;Feitas as devidas análises e definas as softgoals, para o desenvolvimento dos gráficos foi elaborada um padrão de representação que está representado na legenda abaixo.

![Legenda](../assets/imagens/nfr/legenda.jpeg)
<center>Figura 1: Legenda</center>
<br>
&emsp;&emsp;Sendo assim, utilizando a ferramenta Draw.Io, foram desenvolvidos os gráficos SIG que segem.

## 3. Usabilidade
### 3.1. Sem propagação
![SIG Usabilidade](../assets/imagens/nfr/nfr-usabilidade.png)
<center>Figura 2: SIG Usabilidade sem propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/48573556/113076618-d4c14780-91a5-11eb-83a0-bc7cda32812f.png)</center>
### Com propagação
![SIG Usabilidade](../assets/imagens/nfr/nfr-usabilidade-p.png)
<center>Figura 3: SIG Usabilidade com propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/48573556/113079410-58c9fe00-91ab-11eb-9c1b-6bbdccc31d23.png)</center>

## 4. Portabilidade

### 4.1. Sem propagação
![SIG Portabilidade](../assets/imagens/nfr/nfr-portabilidade.png)
<center>Figura 4: SIG Portabilidade sem propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/52640974/113037174-80997180-916b-11eb-981d-0d0e5c4eaabb.png)</center>

### 4.2. Com propagação
![SIG Portabilidade](../assets/imagens/nfr/nfr-portabilidade-p.png)
<center>Figura 5: SIG Portabilidade com propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/52640974/113144699-eb968700-9203-11eb-8ea6-29bcdfccd2ff.png)</center>

## 5. Confiabilidade
### 5.1. Sem propagação
![SIG Confiabilidade](../assets/imagens/nfr/nfr-confiabilidade.png)
<center>Figura 6: SIG Confiabilidade sem propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/48573556/113079616-c544fd00-91ab-11eb-8941-614455ce6c25.png)</center>

### 5.2. Com propagação
![SIG Confiabilidade](../assets/imagens/nfr/nfr-confiabilidade-p.png)
<center>Figura 7: SIG Confiabilidade com propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/48573556/113079416-5b2c5800-91ab-11eb-9dff-ed3e59058b4c.png)</center>

## 6. Eficiência

### 6.1. Sem propagação
![SIG Eficiência](../assets/imagens/nfr/nfr-eficiencia.png)
<center>Figura 8: SIG Eficiência sem propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/52640974/113145063-5d6ed080-9204-11eb-9d49-57ce22849b58.png)</center>

### 6.2. Com propagação
![SIG Eficiência](../assets/imagens/nfr/nfr-eficiencia-p.png)
<center>Figura 9: SIG Eficiência com propagação<br>[Link para a imagem expandida](https://user-images.githubusercontent.com/52640974/113145257-9d35b800-9204-11eb-9e00-134905b99764.png)</center>

## 7. Acompanhamento
&emsp; &emsp; Todas as correções sugeridas foram aplicadas, como adicionar as referências necessárias.

## 8. Bibliografia

> - Requisitos Não-Funcionais. UFPE. Disponível em: https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf. Acesso em: 16 de out. de 2020.
> - BRITO, Isabel Sofia; JANEIRO, José; GOMES, Joaquim. "NFR Framework, Engenharia de Software (2007-2008)". Disponível em: <http://jaejaneiro.orgfree.com/engsofnfr.pdf>
> - SILVA, Reinaldo Antônio. "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados (2019)".
> - CHUNG, L. e NIXON, B., “Using Non-Functional Requirements to Systematically Support Change”, 1995;

## 9. Versionamento

| Versão | Data       | Modificação          | Autor      |
| :----: | ---------- | -------------------- | ---------- |
|  0.1	 | 25/03/201  | Análise dos requisitos não funcionais e definição dos softgoals | Daniel e Emily |
|  1.0   | 25/03/2021 | Adição da introdução | Emily Dias |
|  1.1   | 27/03/2021 | Adição dos participantes | Emily Dias |
|  1.2   | 30/03/2021 | Adição dos ítens de portabilidade e eficiência | Emily Dias |
|  1.3   | 30/03/2021 | Padronização do documento e adição da metodologia e dos ítens de usabilidade e confiabilidade | Daniel Porto |
|  1.4   | 31/03/2021 | Padronização dos ítens de portabilidade e eficiência | Emily Dias |
|  1.5   | 23/04/2021 | Adição de referência | Emily Dias |
|  1.6   | 01/05/2021 | Adição do acompanhamento | Emily Dias |
|  1.7   | 02/05/2021 | Ajuste de documento | Emily Dias |
