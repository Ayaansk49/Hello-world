#include<iostream>
using namespace std;
int main()
{
	
	int n1,n2,sum,operat;
	
	cout<<"Enter the two numbers:"<<endl;
	cin>>n1>>n2;
	
	cout<<"Enter the operator(+,-,*,/)"<<endl;
	cin>>operat;
	
    switch(operat)
	
	case '+':
	cout<<"The sum is "<<n1+n2<<endl;
	
	case  '-':
	cout<<"The difference is"<<n1-n2<<endl;
	
	case  '*':
	cout<<"The product is"<<n1*n2<<endl;
	
	case '/':
	cout<<"The division  is"<<n1/n2<<endl;
	
	
	return 0;
	
}
