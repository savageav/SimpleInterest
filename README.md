#include<iostream.h>
#include<conio.h>
void main()
{
    int p,r,t; float s;
    cout<<"Enter the principal amount:";
    cin>>p;
    cout<<"Enter the rate:";
    cin>>r;
    cout<<"Enter the time duration:";
    cin>>t;
    s=(p*r*t)/100;
    cout<<"The simple interest as calculated by the provided values is:"<<s;
    getch();
}
