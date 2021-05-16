package tarun;

//Creating a Rock Paper Scissor game
/*TODO- 1. import random,Scanner class(ran for random and sc for scanner)
* 2. take input from User
* 3. Print the result of Computer in R,P,s forms 
* 4. Declare the winner or looser
*/

import java.util.Random;
import java.util.Scanner;

public class RockPaperScissor {

	public static void main(String[] args) {
		Random ran = new Random();
		Scanner sc = new Scanner(System.in);
		
		int a=4;   //to take i/p from user
		int b=4; //i/p from computer
		String userin ="";
		String sysin="";
//Take i/p from user
		System.out.println("Enter your choice \n1. Rock \n2. Paper \n3. Scissor \n\n");
		while(sc.hasNextInt()) {
				a=sc.nextInt();
				userin = RPS(a);
				
//Random value genration
				b = 1+ran.nextInt(3);
				sysin = RPS(b);
				
//To check if i/p data is correct
				if(sysin != "" && userin !="") {
				  System.out.println("Your Input:"+ userin);
				  System.out.println("System Output:"+ sysin);
				
				  if((userin == "Rock" && sysin == "Paper" ) || (userin == "Paper" && sysin == "Scissor") || (userin == "Scissor" && sysin == "Rock") )
				    {
					  System.out.println("You Lost this Round \nPlease , Try again \n");		
				    }
				  else if(sysin==userin)
				    {
					  System.out.println("This match is draw \nPlease , Try again \n");
				    }
				  else
				  {
					  System.out.println("You WON \n");
				  }
			                                    }
			
			                  }
		
	sc.close();	
	
	}
	
public static String RPS(int b) {
	String value="";
	
	switch(b){
	case 1: value = "Rock";
	        break;
	case 2: value = "Paper";
	        break;
	case 3: value = "Scissor";
	        break;
	default:System.out.println("Please,print a valid choice");
	
	          
}
	return(value);
}


      
}
