/*
   Time complexity :O(N)
   space complexity:O(1)
   where N is the length of the array .
*/
#include<stdio.h>
long long maxSubarraySum(int arr[],int n )
{
   long long maxSum=0,curSum=0;
   for(int i=0; i<n; i++)
   {
      curSum=max(011,curSum+arr[i]);
      maxSum=max(maxSum,curSum);
    }
}

   
   
