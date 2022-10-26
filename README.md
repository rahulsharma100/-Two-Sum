# -Two-Sum

class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        for Rahul in range(len(nums)):
            for Sharma in range (Rahul+1, len(nums)):
                if nums[Sharma] == target - nums[Rahul]:
                    return[Rahul,Sharma]
