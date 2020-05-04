# TemperatureCheck
one of my first program

package temperatura;
import java.util.Scanner;


/**
 * @author Tomek
 */
public class Temperatura {

   
    public static void main(String[] args) {   
        System.out.println("Temperature Check");
        
        System.out.println("WRITE TEMPERATURE");
        Scanner a = new Scanner(System.in);
        int a1 = a.nextInt();
        
        if(a1>0){
            System.out.println(a1+ "POSITIVE TEMPERATURE");
        }
        else if (a1<0){
            System.out.println(a1+ "NEGATIVE TEMPERATURE");
        }  
        else if (a1==0){
            System.out.println(a1+ "TEMPERATURE IS ZERO");
        } 
    } 
}
