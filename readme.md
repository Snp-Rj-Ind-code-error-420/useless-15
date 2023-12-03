
# UNIVERSITY PROJECT (credit:LUMINAR) 

- THE `15` TASK

> [!warning]
> do not copy the program some update are left for specific purpose. use this as refference for your project to understand the working & basic concept of the program. 

- [x] work completed

## Download links
- [sorce code file](https://github.com/Snp-Rj-Ind-code-error-420/useless-15/releases/download/src15.0.15/assk.cpp)


```

#include <iostream>

using namespace std;
 
void mfc1(){
	double x,dis;
	cout << "enter the prize";
	cin >> x;

	if (x>100){
		dis=x*0.1;
		cout << "original prize " << x <<endl;
		cout<<"discounted prize "<< x-dis << endl;
	}else{
		cout << "original prize " << x <<endl;
	}

}
```
```
void mfc2(){
	int inp;
	cout<< "enter the day in number monday=1"
	cin>> inp;

	switch(inp){
	case 1:
 		cout<<"12 doller ticket prize"<<endl; 
 		break;
 	case 2:
 		cout<<"12 doller ticket prize"<<endl; 
 		break;
 	case 3:
 		cout<<"12 doller ticket prize"<<endl; 
 		break;
 	case 4:
 		cout<<"12 doller ticket prize"<<endl; 
 		break;
 	case 5:
 		cout<<"12 doller ticket prize"<<endl; 
 		break;
 	case 6:
 		cout<<"15 doller ticket prize"<<endl; 
 		break;
 	case 7:
 		cout<<"15 doller ticket prize"<<endl; 
 		break;
 	default:
 		cout<<"moth f error"<<endl;
 		break;
	}
}
```
```
void mfc3(){
	int input;
	cout<<"enter the weather (hot/cold/mild)(1-3)"
	cin>> input;
	switch(input){
	case 1:
		cout<<"go have some ice cream"<<endl;
		break;
	case 2:
		cout<<"go have some tea"<<endl;
		break;
	case 3:
		cout<<"go play outside"<<endl;
		break;
	default:
		cout<<"mfc error"<<endl;
		break;
	}
}
```
```
void mfc4(){
	int input,fee;
	cout<<"enter the withdrawal amount";
	cin>>input;

	if (input>200){
		fee=input*0.02
		cout<<"original amount"<<input<<endl;
		cout <<"fee applied amount"<<input+fee<<endl;
	}else{
		cout<<"original amount"<<input<<endl;
	}
}
```
```

void mfc5(){
	int age;
	cout<<"enter the age";
	cin>>age;

	if (age<30){
		cout<<"premium 200 doller"<<endl;
	}else{
		cout<"premium 200 doller"<<endl;
	}
}
```
```
void mfc6(){
	int num_book;
	double dis,img_prz=2000;
	cout<<"enter the number of books";
	cin>>num_book;

	if(num_book>=3 && num_book<=5){
		dis=img_prz*0.05;
		cout<<"discounted prize"<<img_prz-dis<<endl;
	}else if(num_book>5){
		dis=img_prz*0.1;
		cout<<"discounted prize"<<img_prz-dis<<endl;
	}else{
		cout << "no discount"<<img_prz<<end;
	}
}
```
```
void mfc7(){
	double input;
	cout<<"enter the gpa";
	cin>>input;

	if (input>3.5){
		cout<<"qualified for scolarship"<<endl;
	}else{
		cout<<"disqualified for scolarship"<<endl;
	}

}
```
```
void mfc8(){
	double input;
	cout<<"distance traveled in miles";
	cin>>input;

	if (input>100){
		cout << "reimbursement "<<input*0.50<<endl;
	}else{
		cout<< "reimbursement " <<input*0.40<<endl;
	}

}
```
```
void mfc9(){
	double input,n_day=250,def=0.1;//10%
	cout<<"enter outstanding amount credit card";
	cin>>input;

	if (input>1000){
		cout << "applied interest of 15% "<<(n_day*input*0.14*12)/365<<endl;		
	}
	cout <<"applied interest of 10% "<<(n_day*input*def*12)/365<<endl;		  
}
```
```
void mfc10(){
	int age;
	cout<<"enter the age";
	cin>>age;

	if(age<18){
		cout<<"go for extra screening"<<endl;
	}
}
```
```
void mfc11(){
	char vn;
	cout<<"enter veg[v]/non-veg[n]";
	cin>>vn;

	if (vn=='v'){
		cout<<"eat salad"<<endl;
	}else if(vn=='n'){
		cout<<"eat chicken bryani";
	}else{
		cout<<"why anything else";
	}
}
```
```
void mfc12(){
	int inp,dis,speed_lmt=40;
	cout <<"input speed";
	cin >> inp;
	cout >> "distance traveled";
	cin >> dis;

	if(inp>speed_lmt){		
		cout<<"fine is "<<dis*10;
	}else{
		cout<<"no fine";
	}
}
```
```
void mfc13(){
	double age,height,weight,BMI;
	cout <<"input age";
	cin >> age;
	cout << "input height";
	cin >> height;
	cout <<"input weight"

	BMI=weight/height;
	cout << "your BMI is"<<BMI;
	if(age<40 && BMI<=30){
		cout<<"congrats! you have really maintained yourself well";
	}

}
```
```
void mfc14(){
	int inp;
	cout<<"1.gaming"<<endl
		<<"2.entertainment"<<endl
		<<"3.famly plan"<<endl
		<<"4.streaming"<<endl;

	cout<<"enter the number";
	cin >> inp;
	switch(inp){
	case 1:
		cout<<" 30mbps "<<endl;
		break;
	case 2:
		cout<<" 100mbps "<<endl;
		break;
	case 3:
		cout<<" 500mbps "<<endl;
		break;
	case 4:
		cout<<" 1gbps "<<endl;
		break;
	default:
		cout<<" bug here "<<endl;
		break;
	}
}
```
```
int r(int day,surplus){
	int final,min=50000; //min flight ticket 50 000
	final=min+(surplus*day)
	cout <<"total budget"<< final; 
}
void mfc15(){
	int inp,num_d;
	cout<<"1.France"<<endl
		<<"2.Japan"<<endl
		<<"3.Dubai"<<endl
		<<"4.Hawii"<<endl
		<<"5.Singapore"<<endl
		<<"6.Beijing"<<endl
		<<"7.moscow"<<endl
		<<"8.Rio de Janeiro"<<endl
		<<"9.cairo"<<endl
		<<"10.Amman"<<endl;

	cout<<"enter the number";
	cin >> inp;

	cout<<"enter the number of days";
	cin >> num_d;

	switch(inp){
	case 1:
		r(num_d,5000);
		break;		
	case 2:
		r(num_d,5000);
		break;		
	case 3:
		r(num_d,7000);
		break;
	case 4:
		r(num_d,5000);
		break;		
	case 5:
		r(num_d,4000);
		break;		
	case 6:
		r(num_d,5000);
		break;		
	case 7:
		r(num_d,4000);
		break;		
	case 8:
		r(num_d,3000);
		break;		
	case 9:
		r(num_d,5000);
		break;		
	case 10:
		r(num_d,5000);
		break;		
	default:
		cout <<"probably a bug "<<endl;
		break;		


	}



}```
