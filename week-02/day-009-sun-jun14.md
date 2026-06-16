# Sunday, 14 June 2026 · Day 9
**Week 02 · Foundation**

---

## 🔴 11:00 am – 12:00 pm · Block 1 · DSA REVIEW

**Re-solve #8 Valid Sudoku from memory**
→ neetcode.io/practice

Solve without looking at notes. Can you explain the approach in 3 sentences?

### My solution (from memory)
```
class Solution(object):
    def isValidSudoku(self, board):
        rows = collections.defaultdict(set)
        cols = collections.defaultdict(set)
        squares = collections.defaultdict(set)
        for r in range(9):
            for c in range(9):
                if board[r][c] == ".":
                    continue
                if (board[r][c] in rows[r] or board[r][c] in cols[c] or board[r][c] in squares[(r // 3, c // 3)]):
                    return False
                rows[r].add(board[r][c])
                cols[c].add(board[r][c])
                squares[(r // 3, c // 3)].add(board[r][c])
        return True
```

## ⏸️ 12:00 – 12:20 pm · Break
Stretch, water, 20 min.

---

## 🔵 12:20 – 1:20 pm · Block 2 · LEARN

**Watch StatQuest: 'Bias and Variance' (6 min) + 'Regularisation' (12 min).**
→ youtube.com/watch?v=EuBBz3bI-aA

L1 vs L2 geometric explanation. Google interviewers ask exactly this. Sketch the geometry.

### My notes
```
(key takeaways)
```

---

## ⏸️ 1:20 – 2:00 pm · Lunch
Rest, no screens, 40 min.

---

## 🟡 2:00 – 3:00 pm · Block 3 · BUILD

**Read: 'What are Vector Databases?' (20 min). Then LangChain Colab: Lessons 3–4.**
→ pinecone.io/learn/vector-database

What is a vector DB, why FAISS vs Pinecone vs Chroma, cosine similarity intuition. (~20 min read). Then build Q&A chain over a document.

### What I built / practiced
```
```

---

## ⏸️ 3:00 – 3:20 pm · Break
Walk outside, 20 min.

---

## 🟢 3:20 – 4:20 pm · Block 4 · PLAN + GITHUB

1. Push all this week's code to GitHub with a clear commit message
2. Write tomorrow's problem in your notebook: **#10 Valid Palindrome**
3. What will you study next Saturday Block 2? Write it down.

### GitHub commit message
```
(paste here)
```

---

## 🎉 4:20 pm onwards · Free Afternoon
Rest completely. Sleep by 10:30pm.

---
*← [Week 02 README](./README.md)*
