class Solution {
public:
   bool selfdivide(int n)
   {
        int original=n;
       while(original>0)
       {
        
         int temp=original%10;
         if(temp==0 || n%temp!=0)
         {
            return false;
         }
         else if(n%temp==0)
         {
            original=original/10;
         }
         
       }
         return true;
   }
    vector<int> selfDividingNumbers(int left, int right) {
        vector<int> ans;
        for(int i=left;i<=right;i++)
        {
            if(i>=1 && i<=9)
            {
                ans.push_back(i);
            }
            else if(selfdivide(i))
            {
              ans.push_back(i);
                  
            }
             
        }
        return ans;
        
        }
};
