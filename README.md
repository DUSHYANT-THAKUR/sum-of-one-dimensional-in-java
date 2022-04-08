# sum-of-one-dimensional-in-java
import java.util.Scanner;
public class multiplication {

	public static void main(String[] args) {
		int i,j,k,sum=0;
		int[][] arr1;
		int[][] arr2;
		int[][] mul;
		arr1=new int[2][2];
		arr2=new int[2][2];
		mul=new int[2][2];
		Scanner obj=new Scanner(System.in);
		System.out.println("enter the element in first=");
		for(i=0;i<2;i++)
		{
			for(j=0;j<2;j++)
			{
			arr1[i][j]=obj.nextInt();	
			}
		}
		
		for(i=0;i<2;i++)
		{
			for(j=0;j<2;j++)
			{
				arr2[i][j]=obj.nextInt();
			}
		}
		for(i=0;i<2;i++)
		{
			for(j=0;j<2;j++)
			{
				for(k=0;k<2;k++)
				{
					sum=sum+arr1[i][k]*arr2[k][j];
				}
				mul[i][j]=sum;
				System.out.print(mul[i][j]+" ");
			}
			System.out.println();
			
		}
		
		
		// TODO Auto-generated method stub

	}

}
