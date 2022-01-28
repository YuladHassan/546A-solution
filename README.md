# 546A-solution
#include<bits/stdc++.h>
using namespace std;
int main()
{
    int x,y,z,p;
    int cost=0;
    cin>>x>>y>>z;
    p=x;
    for(int i=1;i<=z;i++)
    {
        x=i*x;
        cost=cost+x;
        x=p;

    }
    if(cost<=y)
    {
       
         cout<<"0"<<endl;
    }
    else
    {
         int br=cost-y;
     cout<<br<<endl;
    }
    return 0;
}
