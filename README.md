# Codeforcescpp-25A
#include <bits/stdc++.h>

using namespace std;

int main(){
  int n,ele,tmp1,tmp2,odd(0),even(0);
  cin >> n;
  for(int i=1;i<=n;i++){
    cin >> ele;
    if(ele%2){
      odd++;
      tmp1 = i;
    }
    else{
      even++;
      tmp2 = i;
    }
  }

  cout << (even==1 ? tmp2 : tmp1);
  
  return 0;
}
