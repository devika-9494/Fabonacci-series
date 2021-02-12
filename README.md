# Fabonacci-series
//using for loop
public class fibonacciExample
{
public static void main(string[] args)
{
//set  it to the number of elements you want in the fibonacci series
int MaxNumber=10;
int PreviousNumber=0;
int NextNumber=1;
system.out.print("fibonacci series of"+MaxNumber+"numbers:");
for(int i=1;i<=MaxNumber;i++)
{
system.out.print(PreviousNumber+" ");
/*on each iteration,we are assigning second number to the first number and assigning the sum of last two number to the second number.
int sum=PreviousNumber+NextNumber;
PreviousNumber=NextNumber;
NextNumber=sum;
}
}
}
