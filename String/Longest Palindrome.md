# Longest Palindromic Substring

## LeetCode
Problem 5 - Longest Palindromic Substring

## Pattern
Two Pointers / Expand Around Center

## Approach

1. Consider every character as the center of a palindrome.
2. Expand to the left and right from the center.
3. Check whether the characters on both sides are equal.
4. Continue expanding while they are equal.
5. Find the longest palindrome.
6. Return the longest palindromic substring.

## Example

Input:
s = "babad"

Output:
"bab"

## Time Complexity

O(n²)

## Space Complexity

O(1)
