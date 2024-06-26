<!--
 * @Description: temp
-->
# 33. Search in Rotated Sorted Array
# 278. [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/description/)
## Problem Description

You are given an integer array `nums` sorted in ascending order (with distinct values), and an integer `target`.

Suppose that `nums` is rotated at some pivot unknown to you beforehand (i.e., `[0,1,2,4,5,6,7]` might become `[4,5,6,7,0,1,2]`).

If `target` is found in the array return its index, otherwise, return `-1`.

**Examples:**

```plaintext
Example 1:
Input: nums = [4,5,6,7,0,1,2], target = 0
Output: 4

Example 2:
Input: nums = [4,5,6,7,0,1,2], target = 3
Output: -1

Example 3:
Input: nums = [1], target = 0
Output: -1
```

**Constraints:**

- `1 <= nums.length <= 5000`
- `-10^4 <= nums[i] <= 10^4`
- All values of `nums` are unique.
- `nums` is guaranteed to be rotated at some pivot.
- `-10^4 <= target <= 10^4`
