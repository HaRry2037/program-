# program for fibonacci in c++-
code:
#include<iostream>
  using namespace std;
  int main()
  {
  int i,n,a=0,b=1,c;  // required variables
  cout<<"Enter the limit"<<endl;
  cin>>n;   //input part
  cout<<0;
  cout<<1;
  cout<<"";
  for(i=2;i<n;i++)
                   {
  c=a+b;
   a=b;
        b=c;
         cout<<c;
            cout<<" "; 
  }     //fibnacci series part in which printing and all is performed
   int k=c;
   a=3 ,b=5 ,c=0;
  while(k>=c)   //this loop is for intialization part for missing series
  {
  a=3, b=5, c=0;
  for(i=a+1;i<b;i++)
                     {
                     cout<<i<<"   ";
                     }
                    c=a+b;
                    a=b;
                    b=c;
                     }
       return 0;
                               }
