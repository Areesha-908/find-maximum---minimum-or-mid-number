# find maximum , minimum or mid number
#include<iostream>
using namespace std;
int main()
{
int a,b,c;
cout<<"enter values of a,b or c"<<endl;
cin>>a>>b>>c;
int max=a;
if(b>a&&b>c)
 max=b;
if(c>a&&c>b)
 max=c;
 cout<<"maximum="<<max<<endl;
 int min=a;
if(b<a&&b<c)
 min=b;
if(c<a&&c<b)
 min=c;
 cout<<"minimum="<<min<<endl;
 int mid;
if(a<max&&a>min)
 mid=a;
if(c<max&&c>min)
 mid=c;
 if(b<max&&b>min)
 mid=b;
 cout<<"mid="<<mid;
 return 0;
}
 
