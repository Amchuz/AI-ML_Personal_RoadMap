# Thursday, 11 June 2026 · Day 6

**Week 1 · Phase 1 · Foundation**

---

## 🔴 9:30 – 10:30 am · DSA

**Problem:** [Encode & Decode Strings](https://neetcode.io/problems/string-encode-and-decode)

### Steps
1. Open NeetCode
2. Set a **25 min timer** — attempt alone, no hints
3. After timer: watch NeetCode explanation
4. Write your approach in 2–3 lines below

### My Solution Approach
```
class Solution:

    def encode(self, strs: List[str]) -> str:
        res = ""
        for s in strs:
            res += str(len(s)) + "#" + s
        return res

    def decode(self, s: str) -> List[str]:
        res = []
        i = 0
        while i < len(s):
            # find the delimiter to read the length
            j = i
            while s[j] != "#":
                j += 1
            length = int(s[i:j])
            # the string starts right after '#'
            res.append(s[j + 1 : j + 1 + length])
            i = j + 1 + length
        return res
```


### ✅ Done? Check off in [progress.md](../progress.md)

---

## ⚫ 1:30 – 2:00 pm · Lunch
**Free — eat with colleagues. No study.**

---

*← [Back to Week 1](./README.md)*
