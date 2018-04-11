# árvore de Decisão

## 1. Introdução

árvore de decisão é um modelo de aprendizagem supervisionado, onde são dados
um conjunto de dados rotulados onde se tem uma variavel alvo predefinida para ser
a saida do sistema onde os dados rotulados são responsaveis por treinar o sistema
para se obter a saida. árvores de decisão são muito utilizadas em problemas de
classificação, podendo trabalha com dados continuos ou categoricas como forma de resultado
de seu processamento.
Para conseguir classificar determinada instancia existente na árvore, ela é percorrida
de cima para baixo, onde em para se definir a que nó será visitado, depende do teste
que compoem cada relacionamento dos nós até que seja visitado um nó folha finalizando assim a
a busca pela classificação de instancia.

<img src="imagens/arvore-de-decisao.jpeg">

## 2. Tipos de árvore de Decisão
* <b>árvore de decisão categoricas</b>: árvores de decisão categoricas, são árvores que tem
por alvo uma variavel chamada de variavel categorica: Exemplo um paciente vai ao medico
com febre e desconfia de estar com dengue, as possibilidade para esse paciente é que ele pode
está com com Dengue ou Não.

* <b>árvore de decisão continuas</b>: árvores de decisão, são árvores que tem por variavel alvo, uma variavel chamada de variavel continua (colocar exemplo)

## 3. Terminologia

<b>Nó raiz: </b> Representa toda polução ou amostra que pode ser divida em dois ou mais conjuntos.
<b>Separação:</b> É o processo responsavel por dividir um nó em dois ou mais sub-nós
<b>Nó de decisão:</b> É como é chamado a o nó proveniente da subdivisão de um outro nó
<b>folha/Nó terminal:</b>É o nó terminal, o ultimo nó sem subdivisão
<b>Poda:</b> É a ação de retirar um nó da árvore
<b>Sub-árvore:</b> Uma sub-seção da árvore serja direita ou esquerda.

<img src='imagens/explica-arvore.png'>

## 4. Justificava

A escolha do algoritmo se deu primeiramente pelo fato do problema ser de classificação e árvores de decisão são comumente utilizadas nesses tipos de abordagem. além de ter algumas das  seguintes vantagens:

* árvores são simples de enteder e serem interpretadas.
* Requerem pouca preparação dos dados.
* Capaz de trabalhar com dados numericos e categoricos.
* Bom funcinamento na predição dos dados.

## 5. Referencia
skelearn. http://scikit-learn.org/stable/modules/tree.html acessado em 09/04/2018.
Anaytics Vdhaya.
https://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/
acessado em 09/04/2018.
