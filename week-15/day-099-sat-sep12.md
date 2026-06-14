# Saturday, 12 September 2026 · Day 99
**Week 15 · Phase 3 · MCP + System Design**

---

## 🔴 9:30 – 10:30 am · Block 1 · DSA

**#99 Power of Two** + **#100 Power of Two**

1. Open NeetCode → neetcode.io/practice
2. **#99 Power of Two** — 30 min timer, attempt alone, watch explanation, submit: leetcode.com/problems/power-of-two
3. **#100 Power of Two** — 30 min timer, attempt alone, watch explanation, submit: leetcode.com/problems/power-of-two

### #99 — my approach
```
```
### #100 — my approach
```
```

---

## ⏸️ 10:30 – 10:45 am · Break

---

## 🔵 10:45 – 11:45 am · Block 2 · LEARN

**Read Microsoft MCP for Beginners — Modules 1 and 2.**
→ github.com/microsoft/mcp-for-beginners

Python MCP server patterns, security, tool definitions. Take notes.

### My notes
```
```

---

## ⏸️ 11:45 am – 12:15 pm · Break

---

## 🟡 12:15 – 1:15 pm · Block 3 · BUILD

**Project 3: full agent flow + Tavily web search tool.**
→ colab.research.google.com

pip install tavily-python. Add Tavily web search as a LangGraph tool. Agent can now search the internet in real time. Test: query → web search → MCP tool → synthesised response. Free tier: tavily.com. This makes your live demo far more impressive.

**Tavily setup:**
```python
pip install tavily-python
from tavily import TavilyClient
client = TavilyClient(api_key="tvly-...")  # free tier at tavily.com
results = client.search("your query here")
# Add as a LangGraph tool node
```

### What I built
```
```

---

## ⏸️ 1:15 – 2:00 pm · Lunch

---

## 🟠 2:00 – 3:00 pm · Block 4 · PROJECT

**Add retry logic + LangSmith tracing to Project 3.**
→ smith.langchain.com

pip install tenacity. @retry on all MCP tool calls. Set up LangSmith tracing. Screenshot dashboard for README.

### Progress
```
```

---

## ⏸️ 3:00 – 3:15 pm · Break

---

## 🟢 3:15 – 4:15 pm · Block 5 · REVIEW + GITHUB

**Push Project 3 to GitHub. LangSmith screenshot in README.**
→ github.com

Commit: 'Project 3 — MCP + LangGraph agent, production-grade'. Test demo from phone.

### GitHub commit message
```
Week 15 — Project 3 MCP+LangGraph agent with Tavily web search deployed
```

---

## 🎉 4:15 pm onwards · Free

---
*← [Week 15 README](./README.md)*
