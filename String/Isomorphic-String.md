# Isomorphic Strings

## LeetCode
Problem 205 - Isomorphic Strings

## Pattern
HashMap

## Approach

1. Traverse both strings at the same time.
2. Map each character from the first string to the corresponding character in the second string.
3. Check whether the same character always maps to the same character.
4. Also make sure two different characters do not map to the same character.
5. If all characters follow the same mapping, return true.

## Example

Input:
s = "egg"
t = "add"

Output:
true

## Time Complexity

O(n)

## Space Complexity

O(n)
