# actividad2_punto13_poo
package esferas3;
import java.util.Scanner;
import java.util.Scanner;

public class Esferas3 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        double  pesoa,pesob,pesoc;
        
        Scanner ingresotecl = new Scanner (System.in);
       
        System.out.println("Ingrese el peso de la esfera A: ");
        pesoa = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el peso de la esfera B: ");
        pesob = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el peso de la esfera C: ");
        pesoc = ingresotecl.nextDouble();
        
        if ((pesoa>pesob)&&(pesoa>pesoc)){
            System.out.println("la esfera A es la de mayor peso");
        }
        else{
            if ((pesob>pesoa)&&(pesob>pesoc)){
                System.out.println("la esfera B es la de mayor peso");
            }
        else {
              System.out.println("la esfera C es la de mayor peso");  
            }
        }


    }
    
}
