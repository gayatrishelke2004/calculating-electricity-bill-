#include<iostream>
using namespace std;

int main(){ 
    int bill;
    int units;

cout<<"enter number of units : ";
cin>>units;

if(units<=0){
    cout << "0";
    return 0;
}
if(units<=50)
   bill = units*1;
else if(units<=150)
   bill=(50*1)+((units-50)*2);
else
   bill=(50*1)+(2*100)+((units-150)*5);

bill += 50;
cout<< "total bill is : "<<bill;
return 0;
}
