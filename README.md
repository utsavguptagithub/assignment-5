# assignment-5

Q1.Write a program to print MySirG N times on the screen
  
  code : #include<stdio.h>
         int main()
{
    int i =1,n;
    printf("enter the number");
    scanf("%d",&n);
    while(i<=n)
    {
        printf("\n mysirg ");
        i++;
    }
}
  
  
  
  Q2 Write a program to print the first N natural numbers.
     code :-
       
       #include<stdio.h>
       int main()
{
    int i =1,n;
    printf("enter the number");
    scanf("%d",&n);
    while(i<=n)
    {
        printf("\n %d ",i);
        i++;
    }
}




Q3. Write a program to print the first N natural numbers in reverse order

code:-
  #include<stdio.h>
    int main()
{
    int i =1,n;
    printf("enter the number");
    scanf("%d",&n);
    while(i>=n)
    {
        printf("\n %d ",i);
        i--;
    }
}
  
  
  Q4.Write a program to print the first N odd natural numbers
  
  code:-
       #include<stdio.h>
        int main()
{
    int i =1,n;
    printf("enter the number");
    scanf("%d",&n);
    while(i<=n)
    {
        printf("\n %d ",i*2-1);
        i++;
    }
}

Q5.Write a program to print the first N odd natural numbers in reverse order.

 code:- 
 
 
 
 
 Q6. Write a program to print the first N even natural numbers
 
 code:-
   #include<stdio.h>
    int main()
{
    int i=i,n;
    printf("enter the number");
    scanf("%d",&n);

    while(i<=10)
    {
        printf("\n %d ",i*2);
        i++;
    }
}


Q7.  Write a program to print the first N even natural numbers in reverse order


 code :-
      #include<stdio.h>
       int main()
{
    int i=i,n;
    printf("enter the number");
    scanf("%d",&n);

    while(i>=10)
    {
        printf("\n %d ",i*2);
        i--;
    }
}
    
    
    Q8. Write a program to print squares of the first N natural numbers
    
    code :-
    
       #include<stdio.h>
int main()
{
    int i=i,n;
    printf("enter the number");
    scanf("%d",&n);

    while(i<=n)
    {
        printf(" %d ",i*i);
        i++;
    }
}
   
   
   
   Q9. Write a program to print cubes of the first N natural numbers
   
   
   code :-
    int i=i,n;
    printf("enter the number");
    scanf("%d",&n);

    while(i<=n)
    {
        printf(" %d ",i*i*i);
        i++;
    }
}


Q10. Write a program to print a table of N.


#include<stdio.h>
int main()
{
    int i=i,n;
    printf("enter the number");
    scanf("%d",&n);

    while(i<=20)
    {
        printf(" %d ",i*n);
        i++;
    }
}
