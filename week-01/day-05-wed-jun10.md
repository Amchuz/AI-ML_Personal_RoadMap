# Wednesday, 10 June 2026 · Day 5

**Week 1 · Phase 1 · Foundation**

---

## 🔴 9:30 – 10:30 am · DSA

**Problem:** [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
**Pattern:** Arrays & Hashmaps

### Steps
1. Open LeetCode: `leetcode.com/problems/two-sum`
2. Set a **25 min timer** — attempt alone, no hints
3. After timer: watch NeetCode explanation → `youtu.be/KLlXCFG5TnA`
4. Write your approach in 2–3 lines below

### My Solution Approach
```
class Solution(object):
    def topKFrequent(self, nums, k):
        numCount = {}
        freq = [[] for i in range(len(nums) + 1)]

        for n in nums:
            numCount[n] = numCount.get(n, 0) + 1
        for num, count in numCount.items():
            freq[count].append(num)
        res = []
        for i in range(len(freq)-1, 0, -1):
            for n in freq[i]:
                res.append(n)
                if len(res) == k:
                    return res
```


### ✅ Done? Check off in [progress.md](../progress.md)

---

## ⚫ 1:30 – 2:00 pm · Lunch
**Free — eat with colleagues. No study.**

---

*← [Back to Week 1](./README.md)*
