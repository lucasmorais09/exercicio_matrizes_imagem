# exercicio_matrizes_imagem
Código que constrói uma imagem por meio de dados inseridos pelo usuário em uma matriz. 
------------------------------------------------------
# ALGORITMO DO EXERCÍCIO
Início

	Declarar variaveis 
	matriz[][] = new int [16][16]
	int = coluna = 0, linha = 0
	int result
 	Para linha de 1 até 16 faça 
	  Para coluna de 1 até 16 faça 
	  Digite somente os números de 0 até 3:
	  Leia número digitado(result)
	  Se result == 0 || result == 1 || result == 2 || result == 3 Entao
		matriz[linha][coluna] = result
	  SeNao 
		Pede para o usuário digitar os valores solicitados
		coluna = coluna - 1
	  FimSe
	  FimPara			
	FimPara
	Para linha de 1 até 16 faça 
	Quebrar linha
	  Para coluna de 1 até 16 faça
	  Escreva (matriz[linha][coluna])
	  FimPara
	FimPara
  
Fim
------------------------------------------------------
![fluxograma_matrizes_imagem](https://user-images.githubusercontent.com/84599880/171444170-259081f3-b5dd-4d42-809e-807805938631.png)
