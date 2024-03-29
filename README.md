# #include<iostream>
#include<conio.h>
using namespace std;
 int main()
 {
     int num1,num2;
    cout <<"Enter 2 number : ";
    cin>> num1>>num2;

     int sum = num1+num2;
     cout<<"sum is : "<< sum;
     cout<< endl;

      int sub = num1 - num2;
     cout<<"subtraction is : "<< sub;
     cout<< endl;

     int mul = num1*num2;
     cout<<"multiplication is : "<< mul;
     cout<< endl;

     double div =(float) num1/num2; // type casting
     cout<<"division is : "<< div;
     cout<< endl;

     int rem = num1/num2;
     cout<<"Remainder is : "<< rem;
     cout<< endl;
     getch();

 }
