# TirePressure1
import java.util.Scanner;
public class Program {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int Tirepressure;
		
		Scanner sc = new Scanner(System.in);
		
		System.out.println("What is your current tire pressure?");
		
		Tirepressure = sc.nextInt();
		
		if(Tirepressure < 25) {
			System.out.println("TIRE LOW");
		}
		
		
		

	}

}
