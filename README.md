# 1395A---Boboniu-Likes-to-Color-Balls
#include <bits/stdc++.h>
using namespace std;

int main() {

    int t;
    cin>>t;
    while(t--){
        int r,g,b,w;
        cin>>r>>g>>b>>w;
        int odd=0,even=0;
        if(w%2==0){
            r%2==0?even++:odd++;
            g%2==0?even++:odd++;
            b%2==0?even++:odd++;
            if(odd==1){
                cout<<"Yes"<<endl;
            }else if(odd==2){
                cout<<"No"<<endl;
            }else{
                cout<<"Yes"<<endl;
            }
        }else{
            r%2==0?even++:odd++;
            g%2==0?even++:odd++;
            b%2==0?even++:odd++;
            if(odd==0){
                cout<<"Yes"<<endl;
            }
            else if(odd==3){
                cout<<"Yes"<<endl;
            }
            else if(odd==2){
                if(r!=0 && g!=0 && b!=0) cout<<"Yes"<<endl;
                else cout<<"No"<<endl;
            }
            else cout<<"No"<<endl;
        }

    }

}

