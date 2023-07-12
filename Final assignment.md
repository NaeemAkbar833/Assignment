
# Assignment-
C language Program to find prime numbers between 2 and 100.
This C language program is designed to find prime numbers between 2 and 100. The program includes a function named isprime which takes an integer x as an input and checks if it is a prime number Using For loop.The function returns 1 if the number is prime and 0 if it is not.
The main function of the program prints a menu for the user to choose between finding prime numbers or non-prime numbers. The user is then prompted to enter a number between 2 and 100. If the entered number is within the specified range, the isprime function is called to check if the number is prime or not. The result is then printed on the screen.
The user can choose to continue or exit the program by entering 1 or 0 respectively. If the user enters an invalid input, the program will display an error message and exit.


/* Name        :Muhammad Naeem
   father name : Ali Akbar
   semester    : First
   department  : CS
   batch       : 2022-2026
   assignment  : fundamental of programing*/



#include <stdio.h>

int isprime (int);
int isprime(int x)
   { int c=0;
     int i=0;
     for(i=0;i<=x;i++)
   {
     if(x % i==0)
   { c++;             };}
   
   if(c==2){ return 1 ; }
   else    { return 0 ; }
    };

int main()
    {  printf("__Software For finding Prime Numbers___\n\n");
       printf("\n 1 For prime Numbers\n");
       printf(" 0 For None prime Numbers\n ");
       int x=0;
       int k=1;
 
while(k!=0)
    {
       int x=0;
       printf(" \nEnter a number between 2 and 100 : ");
       scanf("%d",&x);
   if((x<=100)&&(x>=2))
    { printf("Result : %d",isprime(x));
    printf(" \n\nDo you want to continue 0 or 1 ");
    scanf("%d",&k);
    if(k!=0 && k!=1)
    {  printf("Invalid Input"); 
       break;
    }
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
        }}
    
      return 0;
         }
    
    write a report of this program how its work
Sent message. # Assignment- C language Program to find prime numbers between 2 and 100 . /* Name :Muhammad Naeem father name : Ali Akbar semester : First department : CS batch : 2022-2026 assignment : fundamental of programing*/ #include <stdio.h> int isprime (int); int isprime(int x) { int c=0; int i=0; for(i=0;i<=x;i++) { if(x % i==0) { c++; };} if(c==2){ return 1 ; } else { return 0 ; } }; int main() { printf("__Software For finding Prime Numbers___\n\n"); printf("\n 1 For prime Numbers\n"); printf(" 0 For None prime Numbers\n "); int x=0; int k=1; while(k!=0) { int x=0; printf(" \nEnter a number between 2 and 100 : "); scanf("%d",&x); if((x<=100)&&(x>=2)) { printf("Result : %d",isprime(x)); printf(" \n\nDo you want to continue 0 or 1 "); scanf("%d",&k); if(k!=0 && k!=1) { printf("Invalid Input"); break; } else { continue; } } else { printf(" \nNumber is Out of range \n"); printf(" \nPress 1 to try again : "); scanf("%d",&k); } if(k!=1) { printf("\n Invalid Input ! ..."); break; }} return 0; } write a report of this program how its work
This C language program is designed to find prime numbers between 2 and 100. The program includes a function named isprime which takes an integer x as an input and checks if it is a prime number. The function returns 1 if the number is prime and 0 if it is not.

The main function of the program prints a menu for the user to choose between finding prime numbers or non-prime numbers. The user is then prompted to enter a number between 2 and 100. If the entered number is within the specified range, the isprime function is called to check if the number is prime or not. The result is then printed on the screen.

The user can choose to continue or exit the program by entering 1 or 0 respectively. If the user enters an invalid input, the program will display an error message and exit.
/* Name        :Muhammad Naeem
   father name : Ali Akbar
   semester    : First
   department  : CS
   batch       : 2022-2026
   assignment  : fundamental of programing*/



#include <stdio.h>

int isprime (int);
int isprime(int x)
   { int c=0;
     int i=0;
     for(i=0;i<=x;i++)
   {
     if(x % i==0)
   { c++;             };}
   
   if(c==2){ return 1 ; }
   else    { return 0 ; }
    };

int main()
    {  printf("__Software For finding Prime Numbers___\n\n");
       printf("\n 1 For prime Numbers\n");
       printf(" 0 For None prime Numbers\n ");
       int x=0;
       int k=1;
 
while(k!=0)
    {
       int x=0;
       printf(" \nEnter a number between 2 and 100 : ");
       scanf("%d",&x);
   if((x<=100)&&(x>=2))
    { printf("Result : %d",isprime(x));
    printf(" \n\nDo you want to continue 0 or 1 ");
    scanf("%d",&k);
    if(k!=0 && k!=1)
    {  printf("Invalid Input"); 
       break;
    }
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
        }}
    
      return 0;
         }
    
    


/* Name        :Muhammad Naeem
   father name : Ali Akbar
   Roll Number : 52
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
    
