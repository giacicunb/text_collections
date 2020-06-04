# Diário Oficial da Prefeitura do Recife 2009

### Description

5144 statemets of the Diario Oficial da Prefeitura do Recife (DORE) 2009 regarding retirement acts. Each instance is described by [secao,text,int_label]:

- **secao**: {Text} a Department of the *Prefeitura do Recife* responsible for creating the act
- **text**: {Text} raw text of the retirement act
- **int_label**: {Integer} the attribute **secao** in integer representation

There are 20 possible labels, i.e., Departments of *Diario Oficial da Prefeitura do Recife*:

0: 'Poder Executivo'
1: 'Licitações'
2: 'Secretaria de Assuntos Jurídicos'
3: 'Secretaria de Cultura'
4: 'Secretaria de Educação, Esporte e Lazer'
5: 'Secretaria de Finanças'
6: 'Secretaria de Direitos Humanos e Segurança Cidadã'
7: 'Secretaria de Saneamento'
8: 'Secretaria de Serviços Públicos'
9: 'Secretaria de Saúde'
10: 'Poder Legislativo - old'
11: 'Notícias'
12: 'Secretaria de Administração e Gestão de Pessoas'
13: 'Secretaria de Assistência Social'
14: 'Secretaria de Ciência, Tecnologia e Desenvolvimento Econômico'
15: 'Secretaria de Planejamento Participativo, Obras e Desenvolvimento Urbano e Ambiental'
16: 'Secretaria de Coordenação Política de Governo'
17: 'Secretaria de Comunicação'
18: 'Fundação de Cultura Cidade do Recife - FCCR'
19: 'Secretaria de Habitação'

### Source

http://dados.recife.pe.gov.br/dataset/diario-oficial

### Files

**dore_2009.csv**: raw csv file structured as ['ano','edicao','data','caderno','secao','responsavel','titulo','conteudo_ordem','conteudo'];

**dore_2009_proc.csv**: processed file obtained from **dore_2009.csv** structured as ['secao','conteudo','int_label'];

**preliminary_analysis_dore.ipynb**: Python file por preliminary text set analysis;

**.data**: *(not available)* structure set or derived TF-IDF representation of this text collection;
**.zip**: *(not available)* compacted files of all texts, each file as a single text file;

### References


### Source

