# Laddar.Java
import java.util.Scanner;

public class Ladder
{

     
  public static void main(String []args)
  {
     
    Scanner sc=new Scanner(System.in);  
        
        
    double height = sc.nextDouble();
        
    double v = sc.nextDouble();
        
        
    double ladderLength = height / Math.sin(Math.toRadians(v));
        
            System.out.println(""+(int)Math.ceil(ladderLength));
        
    
  }

}
