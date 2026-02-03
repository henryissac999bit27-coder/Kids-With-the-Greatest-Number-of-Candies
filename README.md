# 1431. Kids With the Greatest Number of Candies

**Difficulty:** Easy | **Language:** Java | [LeetCode Link](https://leetcode.com)

## Problem Description
There are `n` kids with candies. You are given an integer array `candies`, where each `candies[i]` represents the number of candies the `i-th` kid has, and an integer `extraCandies`, denoting the number of extra candies that you have.

Return a boolean array `result` of length `n`, where `result[i]` is `true` if, after giving the `i-th` kid all the `extraCandies`, they will have the greatest number of candies among all the kids, or `false` otherwise.

## Example
- **Input:** `candies = [2,3,5,1,3]`, `extraCandies = 3`
- **Output:** `[true,true,true,false,true]`
- **Explanation:** 
  - Kid 1: 2 + 3 = 5 (>= 5) -> True
  - Kid 4: 1 + 3 = 4 (< 5) -> False

## Complexity Analysis
- **Time Complexity:** O(n) — We traverse the array twice (once to find the max, once to compare).
- **Space Complexity:** O(1) — Excluding the space required for the output list.
