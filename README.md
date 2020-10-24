# calculator
calculator example

#include<iostream>
#include<cmath>

using std:: cout;
using std:: cin;
using namespace std;

int aa,a,b;
void no();
int main(){

	
	
	cout<<"[1 Addition]\n";
	cout<<"[2 Subtraction]\n";
	cout<<"[3 Divition]\n";
	cout<<"[4 Multiplication]\n";
	
	cout<<"Enter a Number: ";
	cin>>aa;
	
	switch(aa){

		case 1:{
		cout<<"Enter Firstnumber\n";
		cin>>a;
		cout<<"Enter Secondnumber\n";
		cin>>b;
		
		aa=a+b;
		cout<<"Sum = "<<aa;
		
		cout<<"\n\nwoud you like go in operator again?\n 1[yes] 2[no]\n";
		cin>>aa;
		system("cls");
		if (aa==1){
			
			main();
		}
		else if(aa==2){ 
	
		no();
	}
		break;
	}
	case 2: {

	
		cout<<"Enter Firstnumber\n";
		cin>>a;
		cout<<"Enter Secondnumber\n";
		cin>>b;
		
		aa=a-b;
		cout<<"Subtract = "<<aa;
		
		cout<<"\n\n you like go in operator again? 1[yes] 2[no]\n";
		cin>>aa;
		system("cls");
		if (aa==1){
			
			main();
		}
		else if(aa==2){ 
	
		no();
	}
	break;
	}
	case 3: {

	
		cout<<"Enter Firstnumber\n";
		cin>>a;
		cout<<"Enter Secondnumber\n";
		if (aa==1){
			
			main();
		}
		
		aa=a/b;
		cout<<"Divide = "<<aa;
		
		cout<<"\n\nwoud you like go in operator again? 1[yes] 2[no]\n";
		cin>>aa;
		system("cls");
			
		if (aa==1){
			
			main();
		}
		else if(aa==2){ 
	
		no();
	}
	break;
	}
	case 4: {

	
		cout<<"Enter Firstnumber\n";
		cin>>a;
		cout<<"Enter Secondnumber\n";
		cin>>b;
		
		aa=a*b;
		cout<<"Multiply = "<<aa;
		
		cout<<"\n\nwoud you like go in operator again? 1[Yes] 2[no]\n";
		cin>>aa;
		system("cls");
	if (aa==1){
			
			main();
		}
	else if(aa==2){ 
	
		no();
	}
	break;
	}

}
}
void no()
{
	cout<<"thankyou for using me.";
}
