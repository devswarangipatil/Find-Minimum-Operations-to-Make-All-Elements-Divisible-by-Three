# Find-Minimum-Operations-to-Make-All-Elements-Divisible-by-Three

You are given an integer array nums. In one operation, you can add or subtract 1 from any element of nums.
Return the minimum number of operations to make all elements of nums divisible by 3.

 class Solution:
 
    def minimumOperations(self, nums: List[int]) -> int:
                return sum(map(lambda x: bool(x %3), nums))
