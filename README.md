# 🎯 AI/ML Engineering Journey

> **June 6, 2026 → January 24, 2027 · 34 weeks · 233 days**

---

## 🗺️ What is this repo?

This is my complete, day-by-day study log for landing a MAANG AI/ML engineering role.
Every day has an exact task, the resource to open, and space for my notes and learnings.

**Full coverage of the Tech with Mak 2026 AI/ML Interview Guide (Part 1 + Part 2) and all 93 LLM engineering topics.**

Topics covered:
- **DSA** — 130+ NeetCode 150 problems, sequential, one per weekday + two on Saturdays
- **LLM Architecture** — Karpathy GPT from scratch, Transformers, attention, KV cache, FlashAttention, RoPE
- **LLM Engineering** — fast.ai L1–8, HuggingFace NLP Ch.5–7, LangChain, LangGraph, MCP, A2A
- **Fine-tuning** — LoRA, QLoRA, PEFT, DPO, RLHF, instruction tuning, prompting vs fine-tuning
- **RAG** — FAISS, RAGAS, hybrid search, reranking, GraphRAG, advanced RAG patterns
- **Agents** — LangGraph, MCP server from scratch, A2A protocol, multi-agent patterns, reflection
- **Production ML** — MLflow, FastAPI, Evidently AI, LangSmith, Tenacity, Docker, HF Hub, vLLM
- **Serving & Inference** — quantisation (INT8/INT4/GPTQ), KV cache, speculative decoding, vLLM
- **Observability** — LangSmith tracing, Evidently drift, token monitoring, cost tracking
- **Classical ML** — StatQuest (8 topics), calibration, class imbalance, feature engineering, A/B testing
- **Reasoning Models** — o1, o3, DeepSeek-R1, test-time compute scaling
- **Open-source LLMs** — DeepSeek-R1, Mistral, LLaMA 3, Gemma — when to use vs proprietary
- **Context Engineering** — context compression (LLMLingua), long-term memory (Mem0), dynamic context
- **Prompt Engineering** — zero-shot, few-shot, CoT, structured outputs, role prompting, Promptfoo evals
- **System Design** — 20+ written answers, ByteByteGo, Chip Huyen, Hamel Evals, applied-ml
- **Projects** — 3 live GitHub projects with HuggingFace Spaces demos
- **Mock Interviews** — 8 Pramp sessions + 15 STAR stories + company deep prep
- **Group 3 Topics** — T5/MoE, Mamba/RWKV, SLMs, model distillation, EU AI Act, OpenTelemetry

---

## 📅 Daily Schedule

| Time | Activity |
|------|----------|
| 5:00 – 5:30 am | Wake up + freshen up |
| 5:30 – 6:00 am | Walk to office |
| 6:00 am | Church |
| 8:30 – 9:15 am | Back to PG + breakfast |
| **9:30 – 10:30 am** | **🔴 DSA — solve on NeetCode, submit on LeetCode** |
| 10:30 am | Log into work |
| 1:30 – 2:00 pm | Lunch — FREE (eat with colleagues, no study) |
| 2:00 – 8:30 pm | Work (fixed end 8:30pm) |
| 8:30 – 9:00 pm | Dinner |
| 9:00 – 9:30 pm | Prayer |
| 9:30 – 10:00 pm | Self-care |
| 10:00 – 11:00 pm | Read a book (fiction — not study) |
| 11:00 pm | Sleep |

**Saturday:** 5 blocks × 1 hr — DSA → Learn → Build → Project → Review+GitHub (9:30am–4:15pm)
**Sunday:** 4 blocks × 1 hr — DSA Review → Learn → Build → Plan+GitHub (11am–4:20pm)
**Every 4th weekend (wk 4, 8, 12, 16, 20, 24):** DSA Block 1 only → full free day

---

## 🏗️ Three Projects

| Project | Stack | Status |
|---------|-------|--------|
| [Project 1: RAG Chatbot](./projects/project-1-rag-chatbot/) | LangChain + FAISS + Gradio + RAGAS | ⬜ Building (Week 3–5) |
| [Project 2: Intent Classifier](./projects/project-2-intent-classifier/) | DistilBERT + LoRA + MLflow + FastAPI + Evidently AI | ⬜ Building (Week 6–10) |
| [Project 3: MCP + LangGraph Agent](./projects/project-3-mcp--langgraph-agent/) | LangGraph + MCP + FastAPI + LangSmith + Tenacity | ⬜ Building (Week 11–15) |

---

## 📚 All Free Resources

| Resource | URL | Used In |
|----------|-----|---------|
| NeetCode 150 | neetcode.io/practice | Every day — solve here |
| LeetCode | leetcode.com | Every day — submit for profile |
| fast.ai Practical DL (L1–L8 + Ethics) | course.fast.ai | Weeks 1–3, 6, 13 |
| HuggingFace NLP Course Ch.5–7 | huggingface.co/learn/nlp-course | Weeks 7, 9, 10 |
| Karpathy — Build GPT from Scratch | youtu.be/kCc8FmEb1nY | Weeks 5–6 (Sunday) |
| ELI5 FlashAttention blog | gordicaleksa.medium.com | Week 6 (after Karpathy) |
| StatQuest YouTube (8 topics) | youtube.com/@statquest | Weeks 1–4, 7, 9, 25 |
| DeepLearning.AI LangChain | learn.deeplearning.ai/courses/langchain | Weeks 1–3 |
| DeepLearning.AI LangGraph | learn.deeplearning.ai/courses/ai-agents-in-langgraph | Week 11 |
| HF MCP Course | huggingface.co/learn/mcp-course | Weeks 13–14 |
| Anthropic MCP Coursera | coursera.org/learn/introduction-to-model-context-protocol | Week 15 |
| Microsoft MCP for Beginners | github.com/microsoft/mcp-for-beginners | Week 15 |
| IBM mcp-context-forge | github.com/IBM/mcp-context-forge | Week 19 |
| A2A Protocol (Google Agent2Agent) | a2a-protocol.org | Week 14 |
| HF PEFT (LoRA/QLoRA) | peft.huggingface.co | Week 7 |
| HuggingFace DPO vs RLHF blog | huggingface.co/blog/dpo-trl | Week 10 |
| Anthropic — Building Effective Agents | anthropic.com/research/building-effective-agents | Week 11 |
| Anthropic Prompt Engineering guide | docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview | Week 14 |
| Anthropic Constitutional AI | anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback | Week 27 |
| OpenAI Whisper | github.com/openai/whisper | Week 14 |
| FastAPI | fastapi.tiangolo.com | Week 9 |
| Evidently AI | evidentlyai.com | Week 18 |
| RAGAS | docs.ragas.io | Week 5 |
| LangSmith | smith.langchain.com | Week 15 |
| Tenacity (retries) | tenacity.readthedocs.io | Week 15 |
| LLMLingua (context compression) | llmlingua.github.io | Week 15 |
| Mem0 (long-term agent memory) | github.com/mem0ai/mem0 | Week 16 |
| Instructor (structured outputs) | python.useinstructor.com | Week 9 |
| vLLM (production LLM serving) | docs.vllm.ai | Week 19 |
| HF Quantisation overview | huggingface.co/blog/overview-quantization-transformers | Week 18 |
| Prophet (time-series) | facebook.github.io/prophet | Week 9 |
| ByteByteGo YouTube | youtube.com/@ByteByteGo | Weeks 17–19, 30–31 |
| Chip Huyen Blog | huyenchip.com/blog | Weeks 14, 18, 21, 25 |
| Hamel Husain — LLM Evals | hamel.dev/blog/posts/evals | Week 13 |
| applied-ml repo | github.com/eugeneyan/applied-ml | Week 26 |
| Kaggle Feature Engineering | kaggle.com/learn/feature-engineering | Week 4 |
| Promptfoo (prompt evaluation) | promptfoo.dev | Week 31 |
| Google Colab (free GPU) | colab.research.google.com | All project sessions |
| HuggingFace Spaces | huggingface.co/spaces | All projects |
| Pramp — free mock interviews | pramp.com | Weeks 21–28 |
| Exponent — ML system design | tryexponent.com/courses/ml | Weeks 22–23 |

---

## 📊 34-Week Progress Tracker

| Week | Dates | Phase | DSA | Done |
|------|-------|-------|-----|------|
| Week 01 | Jun 06 – Jun 12 | Phase 1 · Foundation | Arrays & Hashmaps — #1–7 | ✅ |
| Week 02 | Jun 13 – Jun 19 | Phase 1 · Foundation | Arrays + Sliding Window — #8–14 | ⬜ |
| Week 03 | Jun 20 – Jun 26 | Phase 1 · Foundation | Sliding Window + Stack — #15–21 | ⬜ |
| Week 04 | Jun 27 – Jul 03 | Phase 1 · REST 🟢 | REST — #22–24 (DSA only) | ⬜ |
| Week 05 | Jul 04 – Jul 10 | Phase 1 · Foundation | Stack + Linked Lists — #25–28 | ⬜ |
| Week 06 | Jul 11 – Jul 17 | Phase 2 · LLM Engineering | Trees BFS/DFS — #29–35 | ⬜ |
| Week 07 | Jul 18 – Jul 24 | Phase 2 · LLM Engineering | Binary Trees + Graphs — #36–42 | ⬜ |
| Week 08 | Jul 25 – Jul 31 | Phase 2 · REST 🟢 | REST — #43–47 (DSA only) | ⬜ |
| Week 09 | Aug 01 – Aug 07 | Phase 2 · LLM Engineering | Graphs + Backtracking — #48–53 | ⬜ |
| Week 10 | Aug 08 – Aug 14 | Phase 2 · LLM Engineering | Backtracking + Heaps — #54–57 | ⬜ |
| Week 11 | Aug 15 – Aug 21 | Phase 2 · LLM Engineering | Heaps — #58–63 | ⬜ |
| Week 12 | Aug 22 – Aug 28 | Phase 2 · REST 🟢 | REST — #64–65 (DSA only) | ⬜ |
| Week 13 | Aug 29 – Sep 04 | Phase 3 · MCP + System Design | Dynamic Programming — #66–68 | ⬜ |
| Week 14 | Sep 05 – Sep 11 | Phase 3 · MCP + System Design | Dynamic Programming — #69–71 | ⬜ |
| Week 15 | Sep 12 – Sep 18 | Phase 3 · MCP + System Design | Dynamic Programming — #72–74 | ⬜ |
| Week 16 | Sep 19 – Sep 25 | Phase 3 · REST 🟢 | REST — #75–76 (DSA only) | ⬜ |
| Week 17 | Sep 26 – Oct 02 | Phase 3 · MCP + System Design | Intervals — #77–78 | ⬜ |
| Week 18 | Oct 03 – Oct 09 | Phase 3 · MCP + System Design | Math + Review — #79 | ⬜ |
| Week 19 | Oct 10 – Oct 16 | Phase 3 · MCP + System Design | Review — #80 | ⬜ |
| Week 20 | Oct 17 – Oct 23 | Phase 4 · REST 🟢 | REST — #81 (timed) | ⬜ |
| Week 21 | Oct 24 – Oct 30 | Phase 4 · Applications | Timed mocks — #82–83 | ⬜ |
| Week 22 | Oct 31 – Nov 06 | Phase 4 · Applications | Timed mocks — #84–85 | ⬜ |
| Week 23 | Nov 07 – Nov 13 | Phase 4 · Applications | Timed mocks — #86–87 | ⬜ |
| Week 24 | Nov 14 – Nov 20 | Phase 4 · REST 🟢 | REST — #88 (timed) | ⬜ |
| Week 25 | Nov 21 – Nov 27 | Phase 4 · Applications | Timed mocks — #89–90 | ⬜ |
| Week 26 | Nov 28 – Dec 04 | Phase 4 · Applications | Timed mocks — #91–92 | ⬜ |
| Week 27 | Dec 05 – Dec 11 | Phase 4 · Applications | Timed mocks — #93–94 | ⬜ |
| Week 28 | Dec 12 – Dec 18 | Phase 4 · Final | Final review — #95+ | ⬜ |
| Week 29 | Dec 19 – Dec 25 | Phase 4 · Final | Final timed mocks | ⬜ |
| Week 30 | Dec 26 – Jan 01 | Advanced LLM · Group 1+2 | Pattern review | ⬜ |
| Week 31 | Jan 02 – Jan 08 | Advanced LLM · Group 1+2 | Pattern review | ⬜ |
| Week 32 | Jan 09 – Jan 15 | Advanced LLM · Group 3 | Pattern review | ⬜ |
| Week 33 | Jan 16 – Jan 22 | Advanced LLM · Group 3 | Pattern review | ⬜ |
| Week 34 | Jan 23 – Jan 24 | Advanced LLM · Group 3 + Final | Final review | ⬜ |

---

## 📂 Repo Structure

```
AI-ML_Personal_RoadMap/
├── README.md                    ← You are here
├── progress.md                  ← Daily tick-off log (233 days)
├── week-01/ to week-34/         ← Per-week folders
│   ├── README.md                ← Week overview + checklist
│   └── day-XXX-*.md             ← Per-day: exact task + resource + notes
├── projects/
│   ├── project-1-rag-chatbot/
│   ├── project-2-intent-classifier/
│   └── project-3-mcp--langgraph-agent/
├── dsa/
│   ├── patterns-cheatsheet.md   ← Fill as you learn each pattern
│   └── mistakes-log.md          ← Every wrong answer + why
├── system-design/
│   └── answers/                 ← 20+ written answers (template inside)
└── interview-prep/
    ├── star-stories.md           ← 15 STAR stories
    └── company-research/         ← Google, Microsoft, Amazon prep
        ├── google.md
        ├── microsoft.md
        └── amazon.md
```

---


## 🗓️ Phase Overview

| Phase | Weeks | Dates | Focus |
|-------|-------|-------|-------|
| Phase 1 · Foundation | 1–5 | Jun 6 – Jul 10 | fast.ai L1–3, LangChain, RAG Chatbot, Stats |
| Phase 2 · LLM Engineering | 6–12 | Jul 11 – Aug 28 | fast.ai L4+L5, HF NLP, Karpathy, LoRA, Intent Classifier |
| Phase 3 · MCP + System Design | 13–19 | Aug 29 – Oct 16 | fast.ai L8, MCP server, LangGraph Agent, System Design |
| Phase 4 · Applications | 20–29 | Oct 17 – Dec 25 | Mock interviews, STAR stories, applications, final polish |
| Advanced LLM (Group 1+2) | 30–31 | Dec 26 – Jan 8 | A2A, vLLM, GraphRAG, reasoning models, open-source LLMs |
| Advanced LLM (Group 3) | 32–34 | Jan 9 – Jan 24 | T5/MoE, Mamba, SLMs, distillation, EU AI Act, OpenTelemetry |

---

*Started: June 6, 2026 · Target: First MAANG offer by January 24, 2027*
*God's grace and discipline together. 🙏*
