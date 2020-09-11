# Reverse-array-in-C-
#include <bits/stdc++.h>

using namespace std;

vector<string> split_string(string);



int main()
{
    int n;
    cin >> n;
    int arr[n];
    int c;
    int d;
    for (int i=0;i<=n-1;i++){
        cin>>c;
        arr[i]=c;
    }
    for(int j=n-1;j>=0;j--){
        d=arr[j];
        cout<<d<<" ";
    }

    return 0;
}

