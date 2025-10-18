#include<iostream>
using namespace std;

 int  binarysearch(int arr[], int target,int s,int e){
         while(s<=e){
        int mid=s+(e-s)/2;
        if(nums[mid]==target){
            return mid;
        }
        if(nums[mid]>target){
            e=mid-1;
        }
        else{
            s=mid+1;
        }
       }
       return -1;
    }

int main() {
int n;
int arr[];
cout<<"enter size of array:";
cin>>n;
cout<<endl;
cout<<enter element of array:";
for(int i=0;i<n;i++)
{
cin>>arr[i];
}
  int target;
  cout<<"enter target element:";
  cin>>target;
  cout<<endl;
  int s=0;
int e=n-1;
       int ans=binarysearch(arr,target,s,e);
    if(ans!=-1){
    cout<<"target element found at position:"<<ans<<endl;
    }
    else{
    cout<<"target
   
}
