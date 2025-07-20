# Longest Subarray of 1's After Deleting One Element

## Problem Description

Given a **binary array** `nums`, you must **delete one element** from it.

Return the **size of the longest non-empty subarray** containing only `1`'s in the resulting array.  
Return `0` if there is no such subarray.

## Examples

### Example 1:
**Input:**  
`nums = [1,1,0,1]`  
**Output:**  
`3`  

**Explanation:**  
After deleting the element at index `2`, the array becomes `[1,1,1]`.

---

### Example 2:
**Input:**  
`nums = [0,1,1,1,0,1,1,0,1]`  
**Output:**  
`5`  

**Explanation:**  
After deleting the `0` at index `4`, the longest subarray of 1's is `[1,1,1,1,1]`.

---

### Example 3:
**Input:**  
`nums = [1,1,1]`  
**Output:**  
`2`  

**Explanation:**  
You must delete one element, so the longest subarray becomes `[1,1]`.

---

## Constraints
- `1 <= nums.length <= 10⁵`
- `nums[i]` is either `0` or `1`
