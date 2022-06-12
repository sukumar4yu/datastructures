public class Fib{
  public static void main(String[] args){
   Fib f = new Fib();
   //System.out.println(f.fib(8));
   //f.fibInLoop(8);
   f.factorialLoop(5);
  
  }
   //3 -> fib(2) + fib(1) - > fib(1)+fib(0)+fib(1)
  public int fib(int n){
   if(n < 2){
    System.out.println("n is "+n);
    return n;
   }
   int value = fib(n-1)+fib(n-2);
   System.out.println(value );
   return value ;
  }

   public void fibInLoop(int n){
     int[] result = new int[n];
     result[0] = 0;
     result[1] = 1;
     for(int i=2; i<n; i++){
       result[i] = result[i-1]+result[i-2];
     }
     for(int i=0; i<n;i++){
	System.out.println(result[i]);
     }
   }

  public void factorialLoop(int n){
    int result=n;
     while(n >= 2){
      result = result*(n-1);
      n--;
    }
    System.out.println("factorial is " + result);
  }

   public factorialRecursion(int n){
     if(n ==1){
      return n;
     }
     return n*factorialRecursion(n-1);
   }
