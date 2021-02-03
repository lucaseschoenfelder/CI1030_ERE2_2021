# CI1030_ERE2_2021
Projeto criado como requisito parcial à conclusão da matéria CI1030, ministrada no ERE2 em 2021 pelo professor Drº André Grégio.

## Dataset escolhido
[Spambase](https://archive.ics.uci.edu/ml/datasets/spambase)

## Link para download
https://archive.ics.uci.edu/ml/machine-learning-databases/spambase/

## Campos do dataset
O dataset possui 4.601 instâncias caracterizadas por **57 atributos**, sendo estes:
* **_word\_freq\_WORD_**: 48 atributos do tipo real contínuo [0,100]. Descrevem a frequência em porcentagem que a palavra WORD aparece no email.
* **_char\_freq\_CHAR_**: 6 atributos do tipo real contínuo [0,100]. Descrevem a frequência em porcentagem que o caracter CHAR aparece no email.
* **_run\_length\_average_**: 1 atributo do tipo real contínuo [1,...]. Descreve o comprimento médio de sequências ininterruptas de caracteres em maiúsculo.
* **_run\_length\_longest_**: 1 atributo do tipo inteiro contínuo [1,...]. Descreve o comprimento da mais longa sequência ininterrupta de caracters em maiúsculo.
* **_capital\_run\_length\_total_**: 1 atributo do tipo inteiro contínuo [1,...]. Descreve o número total de caracteres em maiúsculo.
* **_spam_**: 1 atributo do tipo nominal {0,1}. Descreve se o e-mail foi considerado spam (1) ou não (0). 
