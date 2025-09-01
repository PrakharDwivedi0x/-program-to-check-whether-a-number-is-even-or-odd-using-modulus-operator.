# -program-to-check-whether-a-number-is-even-or-odd-using-modulus-operator.

#include <stdio.h>
int main()
{
  
 int number;
 
 printf("enter number");
 scanf("%d" , &number);
 
 if (number%2 == 0) {
   printf("number is even");
 }
  else {printf("number is odd");}
       
}
