# Protótipos Simples Calculadora Portugol





### Protótipo de calculadora adição:



programa
{
	

	funcao inicio()
	{
		inteiro a, b, soma
		
		escreva("Soma: ")
		leia(a)
		limpa()
		escreva("Soma: " ,a, " + ")
		leia(b)
		limpa()
		soma=a+b
		escreva("Soma: " ,a, " + " ,b, " = " ,soma)



	}

}





### Calculadora de divisão, multiplicação, adição e subtração simples: 



programa
{
	

	funcao inicio()
	{
		cadeia op
		real n1, n2, res
		
		escreva ("+, -, * ou / ? \n")
		leia(op)
		limpa()
		escreva("Insira os valores: \n")
		leia(n1)
		limpa()
		escreva("Insira os valores: \n")
		escreva(n1, " ", op, " " )
		leia(n2)
		limpa()
		
		se (op=="+")
			{res = n1+n2}
	
		 senao se (op=="-")
			{res = n1-n2}
	
		 senao se (op=="*")
			{res = n1*n2}
	
		senao se (op=="/")
			{res = n1/n2}
		
		senao
			res=0.0


​		
		escreva("Resultado: \n ", n1, " ",op," ",n2," = ",res) 


​	
	}

}



