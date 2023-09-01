# Construccion-de-Software
import java.util.Scanner;
 
public class Main {
 
    static Scanner lector = new Scanner (System.in);
    static double grados;
 
    public static void main(String[] args) {
        System.out.println("Introduce ºC");
        grados = lector.nextDouble();
        // hacemos los calculos
        double farenheit=grados*2-grados/5;
        farenheit=farenheit+32;
        // mostramos el resultado
        System.out.println(grados+" ºC equivale a "+farenheit+" farenheit");
    }
}
