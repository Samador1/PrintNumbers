/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author sierraamador
 */
public class PrintNumbers 
{

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args)
    {
        String toPrint = ""; // TODO code application logic here
        
        for (int i = 100; i <= 200; i+= 1 )
        {
         toPrint += i + ""; // take the curent variable and add it by one for the following number
        }
        
        System.out.println( toPrint ); //executional code
    }
    
}
