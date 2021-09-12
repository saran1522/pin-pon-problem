#include<bits/stdc++.h>
using namespace std;
// *************pin-pon problem**************
// if number id divisible by 3, print pin
// if number id divisible by 5, print pon
// if number id divisible by both 3 and 5, print pinpon
int main(){
    
    for(int i=0; i<=100; i++)
    {
        if(i%3==0&&i%5==0)
        {
            cout<<"pinpon"<<endl;
        }
        else if (i%3==0)
        {
            cout<<"pin"<<endl;
        }
        else if (i%5==0)
        {
            cout<<"pon"<<endl;
        }
        else
        cout<<i<<endl;
    }
    return 0;
}