# [Search for a Range](https://leetcode.com/problems/search-for-a-range/)

---

## Description

---

Given a sorted array of integers, find the starting and ending position of a given target value.

Your algorithm's runtime complexity must be in the order of O(log n).

If the target is not found in the array, return [-1, -1].

For example,
Given [5, 7, 7, 8, 8, 10] and target value 8,
return [3, 4].

---

Firstly, find a target in the nums using binary search, then search left and right border respectively.

code: [Search for a Range](./SearchforaRange.py)
	