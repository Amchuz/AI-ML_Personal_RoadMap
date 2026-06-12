# Monday, 08 June 2026 · Day 3

**Week 1 · Phase 1 · Foundation**

---

## 🔴 9:30 – 10:30 am · DSA

**Problem:** [Two Sum](https://leetcode.com/problems/two-sum/description/)

### Steps
1. Open LeetCode
2. Set a **25 min timer** — attempt alone, no hints
3. After timer: watch NeetCode explanation
4. Write your approach in 2–3 lines below

### My Solution Approach
```
class Solution(object):
    def twoSum(self, nums, target):
        prevMap = {}
        for i,n in enumerate(nums):
            diff = target - n
            if diff in prevMap:
                return [prevMap[diff],i]
            prevMap[n] = i
        return
        
```


### ✅ Done? Check off in [progress.md](../progress.md)

---

## ⚫ 1:30 – 2:00 pm · Lunch
**Free — eat with colleagues. No study.**

---

*← [Back to Week 1](./README.md)*
