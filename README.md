# prog-online-dz
package com.gmail.turq;
import java.util.Scanner;
public class Zadacha2s {

		

			public static void main(String[] args) {
				// TODO Auto-generated method stub
				Scanner sc=new Scanner(System.in);
				System.out.println("Напишите 5-значное число");
				int number=sc.nextInt();;
				int a=number / 10000;;
				int b = number % 10000/1000;
				int c = number % 1000/ 100;
				int d = number % 100/ 10;
				int e = number % 10;
				
			
				
				System.out.println(a);
				System.out.println(b);
				System.out.println(c);
				System.out.println(d);
				System.out.println(e);
			}

		
	}
