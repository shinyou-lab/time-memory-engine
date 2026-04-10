# Time Memory Engine (TME)

A time-aware memory retrieval system designed for personal AI assistants.

---

## 🧠 Overview

Time Memory Engine (TME) is a memory architecture that enables AI systems to store, retrieve, and prioritize memories based on:

- Temporal distance (when it happened)
- Repetition frequency (how often it is recalled)
- Semantic relevance (what it is about)
- Time-based contextual structures (season, cycle, sequence)

Unlike traditional memory systems that rely only on vector similarity, TME introduces a **time-structured cognitive memory model**.

---

## 🔥 Core Idea

Human memory is not static.

It is:

- Reinforced by repetition
- Faded by time
- Reorganized by context
- Reactivated by recall

TME simulates this behavior computationally.
User Query
↓
Temporal Parser
## 🧩 System Architecture we

Query Structuring
↓
Time Filtering Engine
↓
Semantic Retrieval (Embedding Search)
↓
Time-Aware Scoring Engine
↓
Ranking & Selection
↓
LLM Response Layer

## 🧠 Memory Model

Each memory item contains:

```json
{
  "content": "string",
  "timestamp": "datetime",
  "embedding": "vector",
  "access_count": "int",
  "importance": "float",
  "time_anchor": "string",
  "duration": "float",
  "uncertainty": "float",
  "cycle_tag": {
    "season": "",
    "month": "",
    "weekday": ""
  }
}
Scoring Function

Memory relevance is computed as:
Score =
TimeDecay ×
S-Curve Reinforcement ×
Semantic Similarity ×
Importance Weight ×
Temporal Context Match
⏳ Key Mechanisms

1. Time Decay

Older memories gradually lose weight.

2. Reinforcement Learning (Memory Strengthening)

Repeatedly accessed memories gain higher weight with saturation.

3. Temporal Context Awareness

Memories are influenced by:
	•	Seasons
	•	Cycles
	•	Relative time (before/after events)

4. Memory Reactivation

Previously accessed memories are reinforced again.
🎯 Goal

To build a memory system that behaves closer to human cognition by introducing:
	•	Time-aware retrieval
	•	Dynamic memory weighting
	•	Contextual recall behavior
🚀 Future Work
	•	Graph-based memory linking
	•	Emotional weighting (optional module)
	•	Multi-agent shared memory
	•	Long-term memory compression

Author: Yang Guangfeng (楊光風)
GitHub: shinyou
