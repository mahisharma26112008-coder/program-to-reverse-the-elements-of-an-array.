# program-to-reverse-the-elements-of-an-array.

#include<iostream>
  using namespace std;
    int main(){
      int n;
      cout<<"enter the size of array ";
      cin>>n;
      
      int arr[n];
      for(int i=0;i<n;i++){
          cout<<"enter the elements of array"<<i+1<<" ";
          cin>>arr[i];
      }
      
      cout<<"elements are :"<<"\n";
      for(int i=0;i<n;i++){
          cout<<arr[i]<<" "<<"\n";
      }
      
      
          cout<<"reversed array  "<<"\n";
          for(int i=n-1;i>=0;i--){
              cout<<arr[i]<<" ";
          }
      
      
      return 0;
      
    }
