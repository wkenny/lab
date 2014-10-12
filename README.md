lab
===

lab 5

import java.util.Scanner;


public class lab5 {

	public static void main(String[]arg){
		
		int n;
		
		Scanner Input= new Scanner(System.in);
		
		System.out.println("please enter a number:");
		n= Input.nextInt();
		int rev=0;
		int s=0;
	
		
		for ( int i=0; n>i	;i++){
				int t=i;
				
				while ( i>0){
				rev = i%10;
				i=i/10;
				s=s*10+rev;
				}
				
		
				if ( t==rev){
				System.out.print(rev);
				break;
				
			
					}	
			
			
		}
	}
	
			
	}
	

		

