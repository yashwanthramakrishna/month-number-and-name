# month-number-and-name
import java.util.Scanner;
 class Application 

{
    public static void main(String[] args) {
    int a;
    Scanner input = new Scanner (System.in);
    System .out.println ("Enter the number of month");
    a = input.nextInt();
    
    
    if (a<=12)
    switch(a)
    {
        case 1: System.out.println ("the month is january");
        break;
        
        case 2: System .out .println ("the month is febrauary");
        break;
        
        case 3: System .out .println ("the month is March ");
        break;
        
        case 4 : System .out.println ("the month is april");
        break ;
        
        case 5 : System .out.println ("the month is may");
        break;
        
        case 6 : System .out.println ("the month is june");
        break ;
        
        
        case 7 : System .out.println (" the month is my luckiest month its july ");
        break;
        
        case 8 : System .out .println ("the month is august ");
        break;
        
        case 9 : System .out.println ("the month is september");
        break;
        
        case 10: System.out.println ("the month is october");
        break;
        
        
        case 11 : System .out.println ("the month is november");
        break;
        
        case 12: System .out.println ("the month is december");
        break;
        }
        
        else
        {
        
    
            
            System.out.println ("Input is error give the input between 1 and 13");
            
        
        
    }
    
    
    
    
        
    }
}
