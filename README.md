import java.util.Scanner;
 class palindrome{
 public static void main(String[] args) {
  int n,rev=0,y;
  Scanner sc = new Scanner(System.in);
  System.out.println("Enter Number To Check Palindrome");   
n=sc.nextInt();
y=n;
while(n>0)
{
    rev=(rev*10)+n%10;
    n=n/10;
}
if(y==rev)
System.out.println("Palindrome");
else
System.out.println("Not Palindrome");

}   
}
