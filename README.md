# arraysExerciseTwo
Escreva um trecho Java que leia 10 valores double do teclado e armazene-os em uma matriz de dimensões 2x5.



package aula04.arrays;
import java.util.Scanner;

public class arraysMultiDimensionais {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double[][] numbers = new double [2][5];

        System.out.println("Digite o valor 1: ");
        numbers[0][0] = sc.nextDouble();
        System.out.println("Digite o valor 2: ");
        numbers[0][1] = sc.nextDouble();
        System.out.println("Digite o valor 3: ");
        numbers[0][2] = sc.nextDouble();
        System.out.println("Digite o valor 4: ");
        numbers[0][3] = sc.nextDouble();
        System.out.println("Digite o valor 5: ");
        numbers[0][4] = sc.nextDouble();
        System.out.println("Digite o valor 6: ");
        numbers[1][0] = sc.nextDouble();
        System.out.println("Digite o valor 7: ");
        numbers[1][1] = sc.nextDouble();
        System.out.println("Digite o valor 8: ");
        numbers[1][2] = sc.nextDouble();
        System.out.println("Digite o valor 9: ");
        numbers[1][3] = sc.nextDouble();
        System.out.println("Digite o valor 10: ");
        numbers[1][4] = sc.nextDouble();

        System.out.println(numbers[0][0]);
        System.out.println(numbers[0][1]);
        System.out.println(numbers[0][2]);
        System.out.println(numbers[0][3]);
        System.out.println(numbers[0][4]);
        System.out.println(numbers[1][0]);
        System.out.println(numbers[1][1]);
        System.out.println(numbers[1][2]);
        System.out.println(numbers[1][3]);
        System.out.println(numbers[1][4]);
    }
}

