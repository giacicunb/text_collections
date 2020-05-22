# DODF v1

### Description

717 statemets of the Diario Oficial do Distrito Federal (DODF) regarding retirement acts. Each instance is described by [label,text,isValid]:

- **label**: {Text} a Department of the *Governo do Distrito Federal* responsible for creating the act
- **text**: {Text} raw text of the retirement act
- **isValid**: {Binary} if the retirement act is valid or not 

There are 19 possible labels, i.e., Departments of *Governo do Distrito Federal*:

0) SECRETARIA DE ESTADO DE SEGURANÇA PÚBLICA
1) SECRETARIA DE ESTADO DE CULTURA
2) SECRETARIA DE ESTADO DE FAZENDA, PLANEJAMENTO, ORÇAMENTO E GESTÃO
3) CASA CIVIL
4) SECRETARIA DE ESTADO DE OBRAS E INFRAESTRUTURA
5) SECRETARIA DE ESTADO DE EDUCAÇÃO
6) DEFENSORIA PÚBLICA DO DISTRITO FEDERAL
7) SECRETARIA DE ESTADO DE SAÚDE
8) TRIBUNAL DE CONTAS DO DISTRITO FEDERAL
9) SECRETARIA DE ESTADO DE DESENVOLVIMENTO URBANO E HABITAÇÃO
10) PODER LEGISLATIVO
11) SECRETARIA DE ESTADO DE JUSTIÇA E CIDADANIA
12) SECRETARIA DE ESTADO DE TRANSPORTE E MOBILIDADE
13) CONTROLADORIA GERAL DO DISTRITO FEDERAL
14) PODER EXECUTIVO
15) SECRETARIA DE ESTADO DE AGRICULTURA, ABASTECIMENTO E DESENVOLVIMENTO RURAL
16) SECRETARIA DE ESTADO DE ECONOMIA, DESENVOLVIMENTO, INOVAÇÃO, CIÊNCIA E TECNOLOGIA
17) SECRETARIA DE ESTADO DE DESENVOLVIMENTO ECONÔMICO
18) SECRETARIA DE ESTADO DO MEIO AMBIENTE

### Source

Tribunal de Contas do Distrito Federal

### Files

**dodftrain.csv**: csv file structured as [label,text of the scientific paper];

**preliminary_analysis_dodf.ipynb**: Python file por preliminary text set analysis;

**.data**: *(not available)* structure set or derived TF-IDF representation of this text collection;
**.zip**: *(not available)* compacted files of all scientific papers;

### References

[1] - DE ARAUJO, Pedro Henrique Luz; DE CAMPOS, Teófilo Emidio; DE SOUSA, Marcelo Magalhães Silva. Inferring the source of official texts: can SVM beat ULMFiT?. In: International Conference on Computational Processing of the Portuguese Language. Springer, Cham, 2020. p. 76-86.
