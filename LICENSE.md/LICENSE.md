package algoritma2;
import java.util.Scanner;

public class ebob {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		
		System.out.println("Birinci sayıyı giriniz= ");
		int n1 = input.nextInt();
		System.out.println("İkinci sayıyı giriniz= ");
		int n2 = input.nextInt();
		
		int ebob= 1;
		int limit;
		
		if(n1<n2)
		{
			limit=n1;
		}
		else
			limit=n2;
		for(int i=1; i<=limit; i++)
		{
			if(n1 % i==0 && n2 % i==0)
			{
				ebob=i;
			}
			
		}
		System.out.println("ortak bölen ="+ ebob);
			

	}

}
