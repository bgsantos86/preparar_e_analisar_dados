# Projeto Preparar e Analisar Dados (API Twitter)
Udacity: Nanodegree Fundamentos em Data Science II
Data: 22 de agosto de 2018
<hr>

## Introdução
Dados do mundo real raramente vem limpos. Colete dados de uma série de fontes em uma variedade de formatos, avalie sua qualidade e arrumação e, então, limpe-os. Isso é chamado de data wrangling. Você irá documentar seus esforços de wrangling em um notebook Jupyter, além de exibi-los por meio de análises e visualizações usando Python e/ou SQL.

O conjunto de dados no qual você irá fazer o wrangling (e analisar e visualizar) é o arquivo de tweets do usuário do Twitter @dog_rates, também conhecido como WeRateDogs. WeRateDogs é uma conta no Twitter que classifica os cães das pessoas com um comentário bem humorado sobre o cão. Ele foi iniciado em 2015 pelo estudante universitário Matt Nelson e recebeu cobertura da mídia internacional. Em outubro de 2017 tinha mais 3,7 milhões de seguidores. Estas classificações têm quase sempre um denominador de 10. Mas e os numeradores? Quase sempre maior que 10. 11/10, 12/10, 13/10, etc. Por quê? Porque "são bons cães, Brent."

WeRateDogs deu à Udacity acesso exclusivo a seu arquivo tweets para este projeto. Este arquivo contém dados básicos de tweets para todos os seus mais de 5000 tweets como eles estavam em 1 de agosto de 2017. Voltaremos a esse assunto em breve.

## Qual é o software de que eu preciso?
**Software:**
* Notebook Jupyter.
* sqllite
* Google Docs (para criação de pdfs)

**Bibliotecas:**
* pandas
* numpy
* requests
* json
* tweepy

## Motivação do projeto
**Objetivo**: Preparar e analisar os dados da conta de twitter WeRateDogs para criar analises e visualizações interessantes e úteis. Os arquivos disponibilizado são ótimos, mas somente contém informações basicas. Adicionalmente foi obtido mais dados usando a API do Twitter, então foi realizada uma etapa de limpeza para que fosse possível visualizações e analises surpreendentes.

**Pontos principais**: 
* Só queremos classificações originais (não retweets) que têm imagens.
* Avaliar e limpar totalmente todo o banco de dados requer um esforço excepcional para que apenas um subconjunto de seus problemas (oito problemas de qualidade e dois problemas de arrumação) precisem ser avaliados e limpos.
* A limpeza inclui a fusão de acordo com as regras de dados arrumados para facilitar a análise e visualização.

## Especificações do projeto
### Funcionalidade e leitura do código
* Todo o código está dentro do Jupyter Notebook name wrangle_act.ipynb e roda sem erros;
* The Jupyter Notebook é intuitivo e de fácil visualização. O código está comentado efetivamente e é intercalado com celúlas Markdown.
* Os passos do processo de *data wrangling* (gather, assess, and clear) estão claramente identificados nos comentários ou celúlas markdown. 
### Obtendo os dados (gathering)
A data é considerada obtida (gathering) com sucesso se: 
* Tem ao menos 3 diferentes fontes
* Foi utilizado pelo menos 3 diferentes tipos de arquivos
Cada pedaço de data é importado em seu próprio dataframe.

### Analisando os dados (assessing)
Os dois tipos de analise dos dados foi realizado: visualmente e programaticamente.
* Analise visual: Um pedaço de cada amostra é visualizado no Jupyter Notebook
* Analise através da programação: uso de métodos e funções do pandas para acessar os dados.
Ao menos 8 problemas de qualidade e 2 problemas de arrumação devem ser detectados, e incluídos para posterios limpeza para satisfazer a motivação do projeto. Cada problema deve ser documentado em uma ou mais sentenças cada.

### Limpando os dados (clearing)
As etapas de Definir, codificar e testar do processo de limpeza (clear) estão devidamente documentados.</br>
Copias dos dataframes originais foram realizados para proceder com a limpeza.
Todos os problemas identificados na fase de analise foram limpos com sucesso (se possível) usando o Python e o Pandas, considerando garantir as motivações do projeto
Um dataset arrumado (ou datasets) com todos os pedaços dos dados obtidos foram criados.
### Armazenando e atuando em cima dos dados limpos obtido
### Report



Arquivo principal: wrangle_act.ipynp

## Referencias & citações
#### Githubs
[RedRock42](https://github.com/RedRock42/Udacity-Nanodegree-Portfolio/tree/master/P4.Wrangling%20%26%20Analyzing%20Twitter%20Data)</br>
[latinacode](https://github.com/latinacode/Wrangle-and-Analyze-Data)</br>
[SThornewillvE](https://github.com/SThornewillvE/Udacity-Project---Data-Wrangling)</br>
[abodacs](https://github.com/abodacs/Wrangle-and-Analyze-Data-DAND-project)</br>
[Mitul2991](https://github.com/Mitul2991/Udacity-Project---Wrangling-and-analyzing-data-from-twitter-archives)</br>
[bcko](https://github.com/bcko/Ud-DA-DataWrangling)</br>
[kdow](https://github.com/kdow/WeRateDogs)</br>
[sanjeevai](https://github.com/sanjeevai/Wrangle_and_Analyze_data)</br>
[wanderly0501](https://github.com/wanderly0501/Data-Wrangling-of-WeRateDogs-Tweet-Archive)</br>
[anoru](https://github.com/anoru/Wrangling-Data-WeRateDogs)
