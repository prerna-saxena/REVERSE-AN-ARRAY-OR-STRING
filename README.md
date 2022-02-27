# REVERSE-AN-ARRAY-OR-STRING
REVERSE AN ARRAY OR STRING

#include<bits/stdc++.h>
using namespace std;
void reversearray(int arr[], int start, int end)
{
while(start<end)
{
int temp=arr[start];
arr[start]=arr[end];
arr[end]=temp;
start++;
end--;
}
}
void printarray(int array, int size)
{
for (int i=0; i<size; i++)
{
cout<<arr[i]<<" ";
cout<<endl;
}
