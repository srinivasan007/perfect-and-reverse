# perfect-and-reverse
program


//perfect_number

public class perfect {

	public static void main(String args[])
	{
	
		int n,i=1,sum=0;
		Scanner scan=new Scanner(System.in);
		System.out.println("enetr the number:");
		n=scan.nextInt();
		while(i<n)
		{
		      if(n%i==0)
		      {
		      sum=sum+i;
		      }
		      i++;
		}
		
	if(sum==n)
	
		System.out.println("given number is a perfect no:"+n);
	else
		System.out.println("given number is not a perfect no:"+n);

		
		
	}
}







//program for reverse a number

public class revnum {
	static int rev=0,t;
	public static void main(String[] args) {
		System.out.println("enter a number");
		Scanner s=new Scanner(System.in);
		long n=s.nextInt();
			while(n!=0)
			{	t=(int) (n%10);
				rev=rev*10+t;
				n=n/10;
			}
			System.out.println("the reversed number is"+rev);
	}

}



