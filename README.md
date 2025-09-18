/* Program Aritmatika 
Alfin Tsabitul azmi , XII.3*/

#include <cmath>
#include <iostream>
using namespace std;
int a, b, c, hasil1, hasil2;
int main()
{
    cout<<"     program Aritmatika"<<endl;
    cout<<"  Alfin tsabitul azmi  XII.3"<<endl;
    cout<<"==============================="<<endl;
    cout << "Masukan nilai a:";
    cin>> a;
    cout << "Masukan nilai b:";
    cin>> b;
    cout << "Masukan nilai c:";
    cin>> c;
    cout<<"==============================="<<endl;
    cout<<"Penjumlahan a+b  :"<<a+b<<endl;
    cout<<"Penjumlahan a+b+c:"<<a+b+c<<endl;
    cout<<"Pengurangan a-b  :"<<a-b<<endl;
    cout<<"Pengurangan a-b-c:"<<a-b-c<<endl;
    cout<<"Perkalian a*b    :"<<a*b<<endl;
    cout<<"Perkalian a*b*c  :"<<a*b*c<<endl;
    cout<<"Pembagian a/b    :"<<a/b<<endl;
    cout<<"Pembagian a/b/c  :"<<a/b/c<<endl;
    cout<<"Perpangkatan a^b :"<<pow(a,b)<<endl;
    hasil1=pow (a,b); 
    cout<<"Perpangkatan a^b :"<<pow(a,b)<<endl;
    hasil2=sqrt (a+b); 
    cout<<"Hasil akar a+b   :"<<hasil2<<endl;
    return 0;
}
