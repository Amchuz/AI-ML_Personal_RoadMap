# Friday, 12 June 2026 · Day 7

**Week 1 · Phase 1 · Foundation**

---

## 🔴 9:30 – 10:30 am · DSA

**Problem:** [Product Except Self](https://leetcode.com/problems/product-of-array-except-self)
**Pattern:** Arrays & Hashmaps

### Steps
1. Open LeetCode
2. Set a **25 min timer** — attempt alone, no hints
3. After timer: watch NeetCode explanation
4. Write your approach in 2–3 lines below

### My Solution Approach
```
class Solution(object):
    def productExceptSelf(self, nums):
        res = [1] * (len(nums))
        prefix = 1
        for i in range(len(nums)):
            res[i] = prefix
            prefix *= nums[i]
        postfix = 1
        for i in range(len(nums) - 1, -1,-1):
            res[i] *= postfix
            postfix *= nums[i]
        return res
        
```

### ✅ Done? Check off in [progress.md](../progress.md)

---

## ⚫ 1:30 – 2:00 pm · Lunch
**Free — eat with colleagues. No study.**

---

*← [Back to Week 1](./README.md)*
