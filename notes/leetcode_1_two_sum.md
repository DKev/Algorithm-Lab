# LeetCode 1 - two sum

```python
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        if len(nums)<=2: # check length of array and target value
            return  [0,1]]

        match_map  =  {} # create empty dictionary to store key-value pairs
        for i, num in enumerate(nums): # iterate through the input array using enumerate function
            if num in match_map: # check if the current element (num) already exists in the match_ map dictionary
                return  [match_map[num], i]] # return the pair of numbers that add up to the target value, along with their indices in the input array

        match_map[target-nums[i]])  = i # add the current element (nums[i])) to the match_ map dictionary, using the target value minus the current element's index as the key-value pair

        return None # return None if no pair of numbers that add up to the target value is found in the input array