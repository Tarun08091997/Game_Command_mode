// Guess The number game
package tarun;
import java.util.Random;
import java.util.Scanner;


/**
 * @author TARUN
 * TODO 1. create class Guess with private rand,noofguess as well as getter & setter
 * 2. Create a fun isCorrect() & print if it is greater or smaller 
 * for ever loop increase value of noofguess and print it as a score
 *3. scan number as input-user
 */

public class GuessTheNumber {
	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		System.out.println("Welcome to Guess The Number Game");
		int input_value=0;
		Guess num  = new Guess();
		int Value = num.getNumber();
		int NoOfGuess = num.getNoofGuess();
		System.out.println("Input a Number");
        
		while(sc.hasNext() && (input_value != Value)) {
			NoOfGuess++;
			System.out.println("Input Number again");
			input_value = sc.nextInt();
			IsCorrect(input_value,Value,NoOfGuess);
			
		}
		sc.close();
	}
	
	public static void IsCorrect(int iv,int rv,int NoOfGuess) {	
		if (iv > rv) {
			System.out.println("Input value is larger than The Number");
		}
		else if(iv < rv) {
			System.out.println("Input Value is smaller than The Number");
		}
		else {
			System.out.println("You Win, The number you guessed is  : "+ rv+"\nYour score is :"+NoOfGuess);
		}	
	}
	
}
	

class Guess {
	
	Random rand = new Random();
    private int a = rand.nextInt(100); // Random b/w 0-100
	private int g = 0;                //no of guess value
	
    public int getNumber() {
    	return a;
    }
    public int getNoofGuess() {
    	return g;
    }
}




	
