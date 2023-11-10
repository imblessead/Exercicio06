# Exercicio06
Exercicio06

package exercicios;

import java.util.Scanner;

public class Exercicio06 {

	public static void main(String[] args) {
Scanner scanner = new Scanner (System.in);
		
		System.out.println("Base : ");
		int Base = scanner.nextInt();
		
		System.out.println("Altura: ");
		int Altura = scanner.nextInt();
		
		int alto = Altura+Altura;
		int meio = Base+Base;
		
		System.out.println("A altura do retangulo tem: " + alto);
		System.out.println("A base tem : " + meio);
		
		scanner.close();
		
		// a area do retangulo e a base e altura 

	}

}
