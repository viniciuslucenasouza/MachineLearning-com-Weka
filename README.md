# MachineLearning-com-Weka
Realizado em 2012
O projeto tem como foco utilizar ferramentas e conceitos de Mineração de Dados usados durante a disciplina numa forma prática combinando com conjuntos de dados biológicos retirados do conjunto de dados do UCI Machine Learning Repository. Retirado da área "Life Sciences" escolhemos os dados Ecoli, Yeast e Parkinsond para esse trabalho. 

Usamos 3 classificadores pertencentes a ferramenta WEKA a fim realizar o experimento, KNN,  redes neurais MLP e SVM assim como o banco de dados selecionado foi Ecoli, Yeast e Parkinsons. Após tratarmos o arquivo de dados para o formato .arff de forma que obtemos os atributos.
No trabalho fizemos também, para exemplificar, representações gráficas scatter plot e  boxplot a fim de facilitar a visualização do arranjo de dados. Assim como anotar as médias, desvios padrão, moda, mediana,  cutose e obliquidade para cada um dos atributos usados.

# Banco de dados
EDIT
You may find at:
http://www.sgi.com/tech/mlc/db/lymphography.all
http://www.sgi.com/tech/mlc/db/lymphography.data
http://www.sgi.com/tech/mlc/db/lymphography.names
http://www.sgi.com/tech/mlc/db/lymphography.test
And You may find at:
http://www.cs.umb.edu/~rickb/files/UCI/primary-tumor.arff

Voce precisa de permissão de aceso:
https://archive.ics.uci.edu/ml/datasets/primary+tumor
https://archive.ics.uci.edu/ml/datasets/Lymphography
O objetivo do trabalho é descrever a base de dados e os algritmos utilizados analizando os resultados comparativamente, das duas bases retiradas do site UCI (http://archive.ics.uci.edu/ml/datasets.html).
Iremos utilizar duas bases de dados, iremos trabalhar os atributos e filtros sobre eles além de analizar e comparar as técnicas discutidas. 
Foi escolhido a base Lymphoma (http://www.upo.es/eps/bigs/dataSet/Lymphoma45x4026+2classes.arff) e 
Colon Cancer (http://www.upo.es/eps/bigs/dataSet/colon.arff) para análise.

# Sobre WEKA
Download: http://www.cs.waikato.ac.nz/ml/weka/downloading.html
O pacote de software Weka (Waikato Environment for Knowledge Analysis) começou a ser escrito em 1993, usando Java, na Universidade de Waikato, Nova Zelândia sendo adquirido posteriormente por uma empresa no final de 2006. O Weka encontra-se licenciado ao abrigo da General Public License sendo portanto possível estudar e alterar o respectivo código fonte.
O Weka tem como objectivo agregar algoritmos provenientes de diferentes abordagens/paradigmas na sub-área da inteligência artificial dedicada ao estudo da aprendizagem por parte de máquinas, procede à análise computacional e estatística dos dados fornecidos recorrendo a técnicas de data-minning tentando, indutivamente, a partir dos padrões encontrados gerar hipóteses para soluções e no extremos inclusive teorias sobre os dados em questão.
