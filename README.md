# Domain-Driven-Design-using-Java-2
Treinamento intensivo - Java

//Escreva um programa para ler o ano de nascimento de uma pessoa e escrever
// uma mensagem que diga se ela poderá ou não votar este ano (não é necessário considerar o mês em que ela nasceu).


import java.util.Scanner;

public class IntensivoJava2 {
public static void main(String[] args) {
Scanner scanner = new Scanner(System.in);

        System.out.println("Digite o ano que você nasceu: ");
        int anoNascimento = scanner.nextInt();

        int idade = 2025 - anoNascimento;

        if (idade >=16){
            System.out.println("Pode votar");
        } else {
            System.out.println("não pode votar");
        }


        scanner.close();

    }


}