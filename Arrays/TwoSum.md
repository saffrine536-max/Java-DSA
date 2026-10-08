# Two Sum

## LeetCode
Problem 1 - Two Sum

## Pattern
HashMap

## Approach

1. Traverse the array.
2. Calculate the required number using `target - nums[i]`.
3. Check whether the required number exists in the HashMap.
4. If it exists, return both indices.
5. Otherwise, store the current number and its index.

## Example

Input:
nums = [2,7,11,15]
target = 9

Output:
[0,1]

## Time Complexity
O(n)

## Space Complexity
O(n)
