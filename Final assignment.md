# Assignment
C Language program for finding prime Number between 2 to 100.


/* Name        :Muhammad Naeem
   father name : Ali Akbar
   semester    : First
   department  : CS
   batch       : 2022-2026
   assignment  : fundamental of programing*/



#include <stdio.h>

int isprime (int);  // function prototype
int isprime(int x)  // function Initialization
   { 
     int c=0;
     int i=0;
     for(i=0;i<=x;i++)
   {
     if(x % i==0)
   { c++;             };}
   
   if(c==2){ return 1 ; }
   else    { return 0 ; }
    };

int main()  //main function starts
    {  printf("__Software For finding Prime Numbers___\n\n");
       printf("\n 1 For prime Numbers\n");
       printf(" 0 For None prime Numbers\n ");
       int x=0;
       int k=1;
 
while(k!=0)  // starting of while loop
    {
       int x=0;
       printf(" \nEnter a number between 2 and 100 : ");
       scanf("%d",&x);
   
if((x<=100)&&(x>=2))
    { printf("Result : %d",isprime(x));  // function call
    
    printf(" \n\nDo you want to continue 0 or 1 ");
    scanf("%d",&k);
    
    if(k!=0 && k!=1)
    {  printf("Invalid Input"); 
       break;}
    else { continue; }
    
    }
 
   else { 
          printf(" \nNumber is Out of range \n");
          printf(" \nPress 1 to try again : ");
          scanf("%d",&k);
        }
    if(k!=1)
        {
    printf("\n Invalid Input ! ...");
    break;
        }} // closing of while loop
    
      return 0;
         }   // main function close
    
