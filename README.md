# Pagamentos Extraorçamentários

###### Aqui, você terá acesso a:
- Arquivo .pbix para caso queira interagir;
- Base de dados antes do tratamento;
- Print do Dashboard feito em Power BI

## Introdução
No site de [dados abertos do Governo Federal](https://dados.gov.br/home) foi encontrada uma base que descrevia algumas das 
despesas do governo estadual da Bahia ao longo dos anos de 2019 até 2021.  

## Conclusão
Se torna perceptível com muita clareza que há dois órgãos responsáveis pela maior parte do consumo dos recursos: Diretoria do Tesouro e Tribunal de Justiça, há um destaque destes não apenas na quantidade mas também na recorrência das contribuições.

É importante observar que apesar de serem as duas principais fontes de consumo, há quase o dobro de diferença do primeiro para o segundo colocado (enquanto a Diretoria consumiu aprox. 360 milhões, o Tribunal atingiu mais de 630 milhões).

O peso do Tribunal de Justiça pode não ser necessariamente negativo, visto que é a entidade responsável por garantir o direito dos cidadãos. Porém, é necessário haver controle e responsabilidade.

## Pontos a melhorar
- Visto que alguns dados possuem um valor exorbitante se comparados aos demais, acredito que haveriam outras formas de passar a informação, de montar o Dashboard afim de trazer mais eficácia e entendimento mais ágil da informação apresentada.
- Seria interessante realizar novos estudos dentro exclusivamente da seara da Diretoria e do Tribunal, separadamente, para um entendimento mais aprofundado das fontes destas despesas.

## Passo a passo
- OBJETIVO: Tratamento dos dados e montagem de um Dashboard que pudesse tornar possível a identificação das principais despesas do governo.

- EXTRAÇÃO: A base de dados foi fornecida através do site, sem que fosse necessária a utilização de nenhum mecanismo de coleta.
- TRANSFORMAÇÃO: Através do Excel e Power Query foi feita toda a etapa de tratamento dos dados, eliminando colunas obsoletas para a análise, sintetizando os dados e compactando-os.
- LOAD: Foi criado o template no Figma utilizando a paleta de tons da bandeira do estado de forma moderna e suave, somadas a distribuição das visualizações dentro do Power BI considerando os conceitos de Storytelling afim de facilitar a interpretação dos dados.

![Aqui insiro um print do Dashboard](https://github.com/BitencourtVitor/Pagamentos_Extraorcamentarios/blob/main/print%20dashboard%20completo.png)
