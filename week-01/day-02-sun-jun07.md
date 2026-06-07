# Sunday, 07 June 2026 · Day 2

**Week 1 · Phase 1 · Foundation**

---

## 🔴 11:00 am – 12:00 pm · Block 1 · DSA REVIEW

**Re-solve from memory:** [Contains Duplicate](https://leetcode.com/problems/contains-duplicate)
NeetCode: `youtu.be/3OamzN90kPg`

Solve without looking at your previous notes. Write the approach below.
Can you explain it in 3 sentences to a beginner?

### My solution (from memory)
```
class Solution(object):
    def containsDuplicate(self, nums):
        hset = set()
        for i in nums:
            if i in hset:
                return True
            hset.add(i)
        return False
        
```
### 3-sentence explanation
```
create a hash set
and add eahc number to the set in the while loop
so if the number comes again, the number will already be in hashset
so we will return it as true
```
---

## ⏸️ 12:00 – 12:20 pm · Break
Stretch, water, breathe. 20 minutes.


## 🔵 12:20 – 1:20 pm · Block 2 · LEARN
**Watch StatQuest: Gradient Descent Step-by-Step (21 min)**
**Resource:** youtube.com/watch?v=sDv4f4s2SB8

Why learning rate matters. What overshooting means. Intuition over formula.

### My notes
```
(write key takeaways)
```

---

## ⏸️ 1:20 – 2:00 pm · Lunch
Proper rest. No screens. 40 minutes.

---

## 🟡 2:00 – 3:00 pm · Block 3 · BUILD
**LangChain Colab: install + Lessons 1-2**
**Open:** colab.research.google.com

pip install langchain. Chain 1: prompt→LLM→output. Chain 2: add memory.

### What I built / practiced
```
```

---

## ⏸️ 3:00 – 3:20 pm · Break
Walk outside or around PG. 20 minutes.

---

## 🟢 3:20 – 4:20 pm · Block 4 · PLAN + GITHUB
1. Push all this week's work to GitHub with a commit message.
2. Write tomorrow's problem in your notebook: **Contains Duplicate**
3. What will you study next Saturday Block 2? Write it down.
4. Did you complete this week's checklist? See [Week README](./README.md).

### GitHub commit message
```
(paste here)
```

---

## 🎉 4:20 pm onwards · Free Afternoon
Rest completely. Family, walk, relax. Sleep by 10:30pm.

---

*← [Back to Week 1](./README.md)*
