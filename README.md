# Coverting
import java.util.Scanner;


public class TransferSystemTo {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner scanner = new Scanner(System.in);
		short inputNumber = scanner.nextShort();
		if (inputNumber > 0 && inputNumber <256) {
			convertToBinary(inputNumber);
		}
		else
		{
			System.out.println("This is not in this range");
		}
	}
	
	//This method convert to binary
	public static void convertToBinary (short inputNumber) {
	
		for (short i=0; i < inputNumber; i++) {
			
		}
	}
	public static void isNumberOdd (int number) {
		if (number%2==1) {
			System.out.println("The number is odd");
		}
		else {
			System.out.println("The number isn even");
		}
	}

}
