# Examen
Ejercisios del examen

import java.util.Scanner;

public class Cubo{
 public static void main (String []arg){
 Scanner sc = new Scanner(System.in);
 int cubo;
 System.out.print("Tu numero por favor: ");
 int numero = sc.nextInt();
 while (numero>=0){
 
cubo = numero*numero*numero;
System.out.println("El cubo de " +numero + " es " +cubo);
System.out.println("Introduce otro numero ");
numero = sc.nextInt();
}
}
}
