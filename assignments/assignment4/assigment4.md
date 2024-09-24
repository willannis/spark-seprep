### Assignment 4:

1. **Pick any easy category question from [LeetCode](https://leetcode.com/):**
    
   **Example**

   **Problem:** *Two Sum*
   
   **Question:** Given an array of integers `nums` and an integer `target`, return indices of the two numbers such that they add up to `target`.

   - Example Input: `nums = [2,7,11,15]`, `target = 9`
   - Example Output: `[0,1]`
   
   **Constraints:**
   - Each input would have exactly one solution.
   - You may not use the same element twice.

1. **Create a Python script addressing the problem:**

   ```python
   def two_sum(nums, target):
       num_map = {}
       for i, num in enumerate(nums):
           diff = target - num
           if diff in num_map:
               return [num_map[diff], i]
           num_map[num] = i

   # Test case
   nums = [2, 7, 11, 15]
   target = 9
   result = two_sum(nums, target)
   print(f"Indices of the two numbers that add up to {target}: {result}")
   ```

2. **Create a directory in GitHub:**

   - Navigate to: `https://github.com/DS219/spark-seprep/tree/main/assignments/assignment4/<your_name>`
   - Replace `<your_name>` with your actual name.
   - Create this directory in the repo if it doesn’t exist yet.

3. **Add the Python file to your directory:**
   
   - Save your Python script as `two_sum.py`.
   - Add this file to the directory you just created.

4. **Write a detailed commit message:**

   When committing your changes, ensure the commit message is clear and concise. An example commit message could be:

   ```
   Added a solution for LeetCode's 'Two Sum' problem

   - Implemented a Python solution to find indices of two numbers in an array that sum to a target value.
   - Used a dictionary to store previously encountered numbers and their indices for O(n) time complexity.
   - Tested the solution with a sample input [2, 7, 11, 15] and target = 9, returning correct indices [0, 1].
   ```
