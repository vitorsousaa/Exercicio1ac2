# Exercicio 1 ac2
Exercicio 1 ac2 Calculo de media 


import java.util.Scanner;

public class ac2 {

	public static void main(String[] args) {
		 Scanner ler= new Scanner(System.in);
	        int ra;
	        double n1, n2, n3, m;
	        int i, cont = 0;
	        for (i = 0; i < 10; i++);
	        cont++;
	        System.out.printf("Digite o RA do aluno, se nao houver digite 0  ");
	         ra = ler.nextInt();
	         System.out.printf("Digite a primeira nota  ");
	         n1 = nextDouble();
	          System.out.printf("Digite a segunda nota  ");
	         n2 = nextDouble();
	          System.out.printf("Digite a terceira nota  ");
	         n3 = nextDouble();

	         m = (n1+n2+n3)/3;
	         
	         if (m>6) {
	         System.out.printf("Voce foi reprovado  " + m);
	         }
	         
	         else if (m>6 && m < 8) {
	             System.out.printf("Voce esta de recuperacao  " + m);
	         }
	         
	         else {
	            System.out.printf("Voce esta aprovado  ");
	         }
	    }

	private static double nextDouble() {
		
		return 0;
	}

![media ac2](https://user-images.githubusercontent.com/103973613/169720768-9b45c0a9-fe14-47f3-95fb-d4baadc62561.png)

	
	
	}
