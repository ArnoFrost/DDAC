---
title: DDAC - Core Concepts
created: 2025-10-18
updated: 2025-10-18
tags: [DDAC, Concepts]
---

# DDAC - Core Concepts

Languages: [中文](01-核心概念.md) | English

---

## What is DDAC?
DDAC is a Document-Driven AI Collaboration system that uses structured specification documents to guide AI understanding, execution, and continuous collaboration.

- Persistent context via documents
- Declarative collaboration (describe "what", AI derives "how")
- Reusable chains of thought
- Continuous improvement loop

---

## Why DDAC
- Consistency through explicit standards
- Cross-session continuity
- Faster onboarding and reuse

---

## Differences from traditional AI chat

```
Traditional dialog-style AI:
User ←→ AI
(Each session restarts; context is easily lost)

Document-driven AI collaboration:
User ←→ [Specification Documents] ←→ AI
         ↑
     (Persistent "program")
```

**Key differences**

| Dimension | Traditional dialog | Document-driven collaboration |
|----------|--------------------|-------------------------------|
| Context  | Ephemeral          | Persistent                    |
| Consistency | Memory-dependent | Specification-backed         |
| Reusability | Low             | High                          |
| Scalability | Hard            | Easy                          |
| Collaboration efficiency | Repeated explanations | Auto-understanding |

---

## Theoretical foundations
1. Metaprogramming: specifications act as a "meta-program" that generates AI behavior
2. Persistent chain-of-thought: externalize CoT into documents
3. Declarative collaboration: tell AI "what it should be" rather than "how to do"
4. RAG: retrieve specs → augment context → generate execution
5. Lightweight knowledge graph: Markdown + bidirectional links instead of a graph DB

---

## Applicable scenarios

✅ Suitable when you:
- Need long-term knowledge accumulation
- Need continuous AI collaboration
- Pursue systematization and standardization
- Are willing to invest in building the specs

❌ Not suitable when you:
- Do temporary/simple one-off tasks
- Don’t need knowledge accumulation
- Only want immediate results
- Are unwilling to maintain specifications

---

## Core values
1. Persistent context: specs become AI’s "long-term memory"
2. Reusable chains of thought: solidified reasoning can be reused
3. Declarative collaboration: focus on "what" rather than "how"
4. Extensible architecture: supports ongoing optimization and feature growth
5. Transferable pattern: works across multiple collaboration scenarios

---

## Metrics (Placeholders)

> Note: The following is a placeholder template. Please fill in with measured data. See [Methodology](./methodology.en.md) for definitions and calculation methods.

```yaml
# Metrics placeholder (to be filled with real measurements)
Efficiency:
  - AI reading efficiency: <before> → <after> (improved by <improvement>%)
  - Information lookup speed: <before> → <after> (improved by <improvement>%)
  - Task handoff time: <before> → <after> (improved by <improvement>%)
  - Execution consistency: <before>% → <after>% (improved by <improvement>%)

Quality:
  - Tag completeness: <before>% → <after>% (improved by <improvement>%)
  - Bi-directional link coverage: <before>% → <after>% (improved by <improvement>%)
  - Knowledge island rate: <before>% → <after>% (reduced by <improvement>%)
  - Documentation conformance: <before>% → <after>% (improved by <improvement>%)

Collaboration:
  - Cross-session success rate: <before>% → <after>% (improved by <improvement>%)
  - AI understanding accuracy: <before>% → <after>% (improved by <improvement>%)
  - Automation level: <before>% → <after>% (improved by <improvement>%)
```

---

## Qualitative assessment

Success signals:
- AI can understand and execute tasks independently
- Seamless cross-session handoff
- High consistency with specifications
- A clear and connected knowledge network
- A continuous improvement loop is in place

Needs improvement when:
- AI frequently asks about specification details
- Inconsistent execution results
- Hard to continue tasks across sessions
- Specifications are overly complex
- Optimization suggestions are not actionable

---

## Quick Navigation
- Architecture: [02-Architecture.en.md](02-Architecture.en.md)
- Getting Started: [03-Getting-Started.en.md](03-Getting-Started.en.md)
- Advanced: [04-Advanced.en.md](04-Advanced.en.md)
- FAQ: [05-FAQ.en.md](05-FAQ.en.md)
