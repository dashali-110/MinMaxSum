
#include <iostream>
#include <limits>
using namespace std;

int main()
{
    int number;
    int nummax=INT_MIN;
    int nummin=INT_MAX;
    int count;
    int sumnumber=0;
    

    cout<<"please enter count:"<<endl;
    cin>>count;

    cout<<"please enter"<<"  "<<count<<"  "<<"number:"<<endl;

    for(int i=0 ; i<count ; i++)
    {

        cin>>number;
        if(number>nummax)
        {
            nummax=number;
        }
        if(number<nummin)
        {
            nummin=number;
        }
         sumnumber +=number;
    }

    cout<<"it is number big="<<nummax<<"and"<<"it is number small="<<nummin<<endl;

        cout<<"sum is number enter ="<<sumnumber<<endl;


    return 0;
}
