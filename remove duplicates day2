#include <bits/stdc++.h>
using namespace std;
class Solution {
   public:
   int removeDuplicates(vector<int>& nums) {
      int len = 2;
      int n = nums.size();
      if(n <= 2)return n;
      for(int i = 2; i < n; i++){
         if( nums[i] != nums[len - 2] || nums[i] != nums[len - 1]){
            nums[len] = nums[i];
            len++;
         }
      }
      return len;
   }
};
main(){
   Solution ob;
   vector<int> v = {0,0,0,1,1,1,1,2,3,3};
   cout << ob.removeDuplicates(v);
}
