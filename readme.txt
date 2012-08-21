No diret�rio "geo" est�o todos os dados dos pa�ses, estados/departamentos/divis�es e cidades no formato JSON.

geo/countries => Lista dos pa�ses.

geo/states => Lista dos estados/departamentos/divis�es por pa�s.
(Cada arquivo corresponde a um pa�s.)

geo/cities => Lista das cidades dividido por estados/departamentos/divis�es.
(Cada diret�rio corresponde a um pa�s e cada arquivo a um estado/departamento/divis�o.)

RELACIONAMENTO:
Os arquivos no diret�rio "states" tem o nome de seu respectivo pa�s no c�digo ISO.
No diret�rio "cities" cada sub-diret�rio tem o nome de seu respectivo pa�s no c�digo ISO, os arquivos nele contidos s�o nomeados
com um valor chave correspondente a um estado/departamento/divis�o.

Ex.: (iso)BR->(dir: states/BR.json)21->(dir: cities/BR/21.json)Rio de Janeiro
