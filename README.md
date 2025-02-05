#include<iostream>
#include<cmath>
using namespace std;
int main(){
    int n,h;
    double a;
    int w=0;
    cin>>n>>h;
    for(int i=0;i<n;i++)
    {
        cin>>a;
        if(a<=h){
            w++;
        }
        else{
            double num=(a/h);
            w+=ceil(num);
        }
    }
cout<<w;
}
