# Tuesday, 09 June 2026 · Day 4

**Week 1 · Phase 1 · Foundation**

---

## 🔴 9:30 – 10:30 am · DSA

**Problem:** [Group Anagrams](https://leetcode.com/problems/group-anagrams/)
**Pattern:** Arrays & Hashmaps

### Steps
1. Open LeetCode: `leetcode.com/problems/valid-anagram`
2. Set a **25 min timer** — attempt alone, no hints
3. After timer: watch NeetCode explanation → `youtu.be/9UtInBqnCgA`
4. Write your approach in 2–3 lines below

### My Solution Approach
```
class Solution(object):
    def groupAnagrams(self, strs):
        res = defaultdict(list)
        for s in strs:
            count = [0] * 26
            for c in s:
                count[ord(c) - ord("a")] += 1
            res[tuple(count)].append(s)
        return list(res.values())
        
```

### ✅ Done? Check off in [progress.md](../progress.md)

---

## ⚫ 1:30 – 2:00 pm · Lunch
**Free — eat with colleagues. No study.**

---

*← [Back to Week 1](./README.md)*
