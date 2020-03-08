# youryear
calcula tu edad
import java.util.Scanner;

public class tarea2 {
	
	public static void main(String[] args) {
        // TODO code application logic here


       String N;
          
       int A, AA=2020, ED;
       
	Scanner Leer= new Scanner(System.in);
        System.out.println("Ingrese su nombre ");
        N=Leer.nextLine();
        System.out.println("Ingrese su año de nacimiento ");
        A=Leer.nextInt();
        ED=AA-A;
                
         System.out.println("Hola " +N);
        
        System.out.println("Su edad es: " + ED);
        
       
        
    }
}
