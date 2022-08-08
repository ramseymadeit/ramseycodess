#ramseycodess
#include <iostream>
using namespace std;

int main()
{
    int i,num,eSum=0,eCount=0;  
double eAvg;                     
    cout<<"Enter the value for num: ";     
    cin>>num;

    for(i=1; i<=num; i++){           
    if(i % 2==0){               
        eSum=eSum+i;
        eCount++;
    }

    } 
eAvg=eSum/eCount;                      
cout<<"Average of even numbers are: "<<eAvg;
    return 0;
}
