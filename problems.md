# 📘 Daily Coding Practice

## Problems Log
### 📅 2026-04-19

- 🧠 Problem: Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
You may assume that each input would have exactly one solution, and you may not use the same element twice.
You can return the answer in any order.

- 💡 Approach:

- Example 1:
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Explanation: Because nums[0] + nums[1] == 9, we return [0, 1].
Example 2:
Input: nums = [3,2,4], target = 6
Output: [1,2]
Example 3:
Input: nums = [3,3], target = 6
Output: [0,1]
 
Constraints:
2 <= nums.length <= 104
-109 <= nums[i] <= 109
-109 <= target <= 109
Only one valid answer exists.

- 💻 Code:
  class Solution:
    def twoSum(self, nums, target):
        seen = {}                  # value -> index
        for i, n in enumerate(nums):
            complement = target - n
            if complement in seen:
                return [seen[complement], i]
            seen[n] = i
  if __name__ == "__main__":
    print(Solution().twoSum([2, 7, 11, 15], 9))  # prints [0, 1]


        

### 📅 2026-04-20
- 🧠 Problem: Solve a DSA question (Array / String / DP)
- 💡 Approach: 
- 💻 Code: 

### 📅 2026-04-21
- 🧠 Problem: Solve a DSA question (Array / String / DP)
- 💡 Approach: 
- 💻 Code: 

### 📅 2026-04-22
- 🧠 Problem: Solve a DSA question (Array / String / DP)
- 💡 Approach: 
- 💻 Code: 

### 📅 2026-04-23
- 🧠 Problem: Solve a DSA question (Array / String / DP)
- 💡 Approach: 
- 💻 Code: 

### 📅 2026-04-24
- 🧠 Problem: Solve a DSA question (Array / String / DP)
- 💡 Approach: 
- 💻 Code: 

### 📅 2026-04-25
- 🧠 Problem: Solve a DSA question (Array / String / DP)
- 💡 Approach: 
- 💻 Code: 

