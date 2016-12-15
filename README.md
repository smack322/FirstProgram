# FirstProgram
import java.util.Scanner;

　
public class apples {
    public static void main(String[]args) {	
    	
    	Scanner prompt = new Scanner(System.in);
    	
    	System.out.println("Type your username: ");
    	String username = prompt.nextLine();
    	
    	System.out.println("Type your password: ");
    	String password = prompt.nextLine();
    	
    	if (username =="alex") && (password =="mightyducks")){
    		System.out.println("You are now logged into the system!");	
    	}
    	else if (username.equals("emily") && password.equals("cat")){
    		System.out.println("You are now logged into the system!");
    	}
    	else{
    		System.out.println("Your username or password was invalid!");
    	}
    	
    	

    } 
    
}
