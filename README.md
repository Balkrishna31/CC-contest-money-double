# CC-contest-money-double
#include <bits/stdc++.h>
using namespace std;

int main() {
	// your code goes here
	int T;
	cin>>T;
	for(int i=0;i<T; i++)
	{
	    int X,Y;
	    cin>>X>>Y;
	    int doubleSum=0;
	    int addSum=0;
	   // addSum=X+(Y*1000);
	    for(int j=0; j<Y; j++)
	    {
	       // 
	       doubleSum=X*2;
	       addSum=X+1000;
	        if(doubleSum>addSum)
	        {
	            X=doubleSum;
	        }
	        else
	           X=addSum;
	    }
	    cout<<X<<endl;
	    
	}
	return 0;

}
