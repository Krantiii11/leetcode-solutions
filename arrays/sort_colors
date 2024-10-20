class Solution {
    public void sortColors(int[] nums) {
        for(int i =0;i<nums.length;i++){
           for(int j=1;j<nums.length;j++){
            if(nums[j-1]>nums[j]){
                swap(nums,i,j);

            }
           }
                
        }
    }

    private void swap(int [] nums,int i , int j){
            int temp = nums[j-1];
                nums[j-1]=nums[j];
                nums[j]=temp;

                
    }
   
}