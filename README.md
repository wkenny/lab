lab
===
import java.util.Scanner;


public class lab5 {

	public static void main(String[]arg){
		
		int n;
		//n is the input number
		
		Scanner Input= new Scanner(System.in);
		
		System.out.println("please enter a number:");
		n= Input.nextInt();
		int rev=0;
		//rev = reverse
		int s=0;
	
		
		for ( int i=0; n>i	;i++){
			// i is the starting number   
			
				int initial=i;
			// initial = i so that later can prove the reverse number = initial number
				while ( i>0){
				rev = i%10;
				i=i/10;
				s=s*10+rev;
				}
				
		
				if ( initial==s){
				System.out.print(initial);
				break;
				
			
					}	
			
			
		}
	}

	
	

