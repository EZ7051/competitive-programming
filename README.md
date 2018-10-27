#include<bits/stdc++.h>
using namespace std;
int main()
 {
	//code
	int t;
	cin>>t;
	while(t--)
	{
	    string s;
	    cin>>s;
	    long long int ans=s[0]-'0',sum=s[0]-'0';
	    for(int i=1;i<s.size();i++)
	    {
	        ans=ans*10+(i+1)*(s[i]-'0');
	        sum+=ans;
	    }
	    cout<<sum<<endl;
	}
	return 0;
}
