// Encapusaltion Example 

#include<bits/stdc++.h>
using namespace std;


 class A {
    int p;
      int q;
     public :
      void set (int input){
         p=input;
         q=p/2;
          cout<<q;
    }
};
int main(){
   A obj;
obj.set(8);
}

