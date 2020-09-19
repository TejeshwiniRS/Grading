/* Grading
Grading a student using if-else-if ladder.*/

#include <stdio.h>

int main()

{

  int n;
   
  printf("Enter the marks: ");
  
  scanf("%d",&n);
  
  if(n>=85 && n<=100)
    printf("Your grade is A");
  
  else if(n>=70 && n<85)
    printf("Your grade is B");
    
  else if(n>=55 && n<70)
    printf("Your grade is C");
    
  else if(n>=40 && n<55)
    printf("Your grade is D");
    
  else
    printf("Your grade is F");
   
return 0;

}
   
  
