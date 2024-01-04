# greengrocer
It calculates the total  payment in the greengrocer.
package patikaAcademy;

import java.util.Scanner;


public class manav {

	public static void main(String[] args) {
	
		/*
		  Meyveler ve KG Fiyatları 
		  Armut : 2,14 TL 
		  Elma : 3,67 TL
		  Domates : 1,11 TL
		  Muz: 0,95 TL 
		  Patlıcan : 5,00 TL
		 */
		
		Scanner input =new Scanner(System.in);

		double elma,armut,domates,muz,patlican, total;
		 
		System.out.println("Alınan armut miktarı:");
		armut= input.nextDouble();
		
		System.out.println("Alınan elma miktarı:");
		elma= input.nextDouble();
		
		System.out.println("Alınan domates miktarı:");
		domates= input.nextDouble();
		
		System.out.println("Alınan patlıcan miktarı:");
		patlican= input.nextDouble();
		
		System.out.println("Alınan muz miktarı:");
		muz= input.nextDouble();
		
		total = (elma*3.67)+ (armut*2.14)+(domates *1.11)+ (muz*0.95)+(patlican*5);
		System.out.print("Toplam tutar:"+ total);
		
	
		
	}

}
