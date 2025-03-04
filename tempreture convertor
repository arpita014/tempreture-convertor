package Task1;
import java.util.Scanner;
public class temperatureConvertor{
	public static void main(String[]args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the temperature value:");
		double temp=sc.nextDouble();
		
		System.out.println("Enter the Original unit of measurement(C,F,or K)");
		char originalUnit=sc.next().toUpperCase().charAt(0);
		
		double celsius=0,fahrenheit=0,kelvin = 0;
		
		switch(originalUnit) {
		case 'C':
			celsius=temp;
			fahrenheit=celsiusToFaherenheit(celsius);
			kelvin=celsiusToKelvian(celsius);
			break;
		
		case 'F':
			fahrenheit=temp;
			celsius=fahrenheitToCelsius(fahrenheit);
			kelvin=fahrenheitToKelvian(fahrenheit);
			break;
			
		case 'K':
			kelvin=temp;
			celsius=kelvinToCelsius(kelvin);
			fahrenheit=kelvinToFaherenheit(kelvin);
			break;
			default:
				System.out.println("Invalid unit of measurement");

		}
		
		System.out.println("converted tempratures");
		System.out.printf("Celsius:%.2f\n",celsius);
		System.out.printf("Fahrenheit:%.2f\n",fahrenheit);
		System.out.printf("Kelvin:%.2f\n",kelvin);
	}

	private static double kelvinToFaherenheit(double kelvin) {
		// TODO Auto-generated method stub
		return kelvin-273.15;
	}

	private static double kelvinToCelsius(double kelvin) {
		// TODO Auto-generated method stub
		return (kelvin-273.15)*9/5+32;
	}

	private static double celsiusToFaherenheit(double celsius) {
		// TODO Auto-generated method stub
		return (celsius*9/5)+32;
	}

	private static double celsiusToKelvian(double celsius) {
		// TODO Auto-generated method stub
		return celsius +273.15;
	}

	private static double fahrenheitToKelvian(double fahrenheit) {
		// TODO Auto-generated method stub
		return (fahrenheit-32)*5/9+273.15;
	}

	private static double fahrenheitToCelsius(double fahrenheit) {
		// TODO Auto-generated method stub
		return (fahrenheit-32)*5/9;
	}
}
