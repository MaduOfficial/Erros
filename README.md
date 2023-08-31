Erros no java

                                                                    Entendendo os Erros
                                                          
O que vaos fazer
.Exemplos de erros e como acertá-los
.Entender o que acontece

                                                                     Tipos de Erros

.Erros de Sintaxe
.Erros de Semântica
.Erros em Tempo de Execução

O que é um erro de Sintaxe:A linguagem JAVA para você compilar um programa java existe um passo a passo que é você criar um arquivo você salvar esse arquivo
como .java, e dentro desse arquivo tem uma estrutura que é experada pelo programa pelo compilador java pela jvm e ai tem uma série de coisas que você pode
colocar nesse arquivo, você pode colocar em codes você faz os pacotes e voc^também pode ter uma classe, você pode ter várias classes.

Erro1:

package com.madu.erros1.teste1;

public class Erros1Teste1 {

	public static void main(String[] args) {
		
		System.out.println("Hello World)
	}
	
}


Correção do Erro1:

package com.madu.erros1.teste1;

public class Erros1Teste1 {

	public static void main(String[] args) {
		
		System.out.println("Hello World");
	}
	
}

Erro2:

package com.madu.erros2.teste1;

public class Erros2Teste1 {

	public static void main(String[] args){
		
		var int cont;
		
		System.out.println("Hello World");

	}

}

_

package com.madu.erros2.teste1;

public class Erros2Teste1 {

	public static void main(String[] args){
		
		int cont;
		
		System.out.println("Você digitou: " + cont);

	}

}

Correção do Erro2:

package com.madu.erros2.teste1;

public class Erros2Teste1 {

	public static void main(String[] args){
		
		int cont = 0;
		
		System.out.println("Você digitou: " + cont);

	}

}


Erro3:

package com.madu.erros3.teste1;

public class Erros3Teste1 {

	public static void Main(String[] args) {
		
		//System.out.println("Você digitou: ");
		System.out.println("Você digitou: " + 1/0);
	}

}


Correção Erro3:

package com.madu.erros3.teste1;

public class Erros3Teste1 {

	public static void main(String[] args) {
		
		//System.out.println("Você digitou: ");
		System.out.println("Você digitou: " + 1/0);
	}

}
