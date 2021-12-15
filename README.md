# cc_GENES

#include <iostream>
#include<bits/stdc++.h>
using namespace std;
int main() {
 char a,b,c;
 cin>>a>>b;
 if(a=='R'||b=='R')
 c='R';
 else
 {
     if(a=='B'||b=='B')
     c='B';
     else
     c='G';
 }
 cout<<c<<"\n\n";
 return 0;
}
