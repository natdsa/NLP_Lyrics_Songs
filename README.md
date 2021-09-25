# NLP_Lyrics_Songs

O objetivo deste estudo é empregar técnicas de Processamento de Linguagem Natural em letras de música de alguns artistas brasileiros. Foram coletadas todas as letras de músicas de cada artista, disponíveis no Genius (https://genius.com). 
Nesse trabalho foram consideradas 360 letras de músicas dos seguintes artistas: Criolo, Fernandinho, Os Barões da Pisadinha e Pitty. A escolha dos artistas foi motivada por possuírem gêneros musicais distintos, possibilitando trazer uma maior diversidade ao conjunto de dados.
O trabalho foi desenvolvido utilizando a linguagem Python/ Jupyter Notebook. Todas as bibliotecas utilizadas encontram-se disponíveis no notebook, enviado em anexo a este documento. Para a representação textual foram utilizadas as seguintes técnicas de NLP: Embedding, similaridade de palavras, bigramas, Análise de Sentimentos (Textblob e Afinn).

Em resumo, o pipeline de dados foi realizado da seguinte maneira:
1.	Coleta de dados, mediante uso de API
2.	Agrupamento e tratamento dos dados
3.	Preprocessamento do texto
4.	Aplicação de técnicas de representação textual
5.	Aplicação de técnicas de análise de sentimentos
6.	Tópico por artista: Representação de palavras mais faladas e bigrama.

As letras de música são uma excelente forma de estudar representação textual. O conteúdo é bastante rico, tanto pela poética - vide Criolo - ou expressões populares, como as canções de Os Barões da Pisadinha. Alguns pontos de dificuldade foram encontrados. Destaca-se na análise de sentimentos, os métodos aqui estudados, na grande maioria das canções, obtiveram-se um score neutro.
Para futuros trabalhos, sugere-se a utilização de canções por décadas. Pode-se levantar como hipótese se há diferença entre as palavras das músicas dos anos 80 para as palavras das canções dos anos 2010. Será que existe diferença?
