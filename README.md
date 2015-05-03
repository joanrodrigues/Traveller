# Traveller
Path finder

Boas!
Este programa contém um algoritmo que tem como objectivo detectar uma rota optima num conjunto de cidades a visitar segundo uma categoria seleccionada pelo utilizador,
nomedamente preço, distancia ou tempo. 
Em primeiro lugar, é importante referir que o programa que efectua tal algoritmo tem por nome o "Source.cpp" e ainda estão incluidos
os ficheiros txt que correspondem às matrizes de distancia, tempo e preço entre cidades.
Para iniciar o algoritmo, o utilizador deverá introduzir a cidade de origem e destino, e ainda que categoria deseja que seja 
responsável pela determinação da rota.


O algoritmo em si aplica algo semelhante ao "nearest neighborhood algorithm" mas de forma um pouco diferente, já que o faz para
3 minimos sucessivamente. Portanto, em vez de calcular 1 minimo, calcula 3 minimos referentes à cidade em que se localiza e 
selecciona 3 rotas diferentes.
As rotas sao todas comparadas no sentido de se obter um minimo relativamente ao valor de soma_final distancia/tempo/custo.


