# ARCHITECTURE.md
Machines That Talk Too Much

This document defines the structural architecture of the book.
It exists to prevent scope creep, narrative drift, and accidental reordering.

This is a control document, not reader-facing content.

---

## Global Design Principles

- The book is divided into **five independent parts**.
- Each part is readable on its own.
- Parts are chronological, but not interdependent.
- Concepts are introduced once, then referenced briefly.
- No part assumes knowledge of future parts.

Progression is based on:
data → training → evaluation → inference → constraints

Not on hype cycles or company timelines.

---

## Part-Level Architecture

### Part I — Before Scale
**Responsibility**
- Establish what language modeling looked like before modern scale.
- Show limits of rules and small statistics.

**May introduce**
- Rules
- N-grams
- Early statistical ideas
- Small datasets
- Manual feature design

**Must NOT introduce**
- Neural networks
- Transformers
- Large-scale training
- Modern inference constraints

---

### Part II — Learning from Data
**Responsibility**
- Explain why learning from data replaced rules.
- Show the transition to trainable models.

**May introduce**
- Early neural networks
- Sequence models
- Training as optimization
- Larger datasets

**Must NOT introduce**
- Transformers
- Attention
- Scaling laws
- Modern LLM behavior

---

### Part III — Scaling Changes Everything
**Responsibility**
- Explain why scale altered behavior without changing objectives.
- Ground “surprising behavior” in mechanics.

**May introduce**
- Transformers
- Self-attention
- Large-scale training
- Emergent-seeming effects

**Must NOT introduce**
- Agents
- Tool use
- Productized chat systems
- Deployment economics

---

### Part IV — Testing and Reality
**Responsibility**
- Separate benchmark success from real-world behavior.
- Explain evaluation limits.

**May introduce**
- Benchmarks
- Overfitting to tests
- Distribution shift
- Failure modes

**Must NOT introduce**
- Philosophical claims
- AGI discussions
- Ethics beyond operational impact

---

### Part V — Inference Is the Product
**Responsibility**
- Explain why inference constraints define usefulness.
- Show trade-offs between cost, latency, and quality.

**May introduce**
- Inference optimization
- Deployment
- Cost trade-offs
- Serving constraints

**Must NOT introduce**
- Future speculation
- Consciousness
- Predictions about intelligence trajectories

---

## Chapter Responsibilities

Each chapter must answer:
1. What changed?
2. Why did it change?
3. What constraint forced the change?

Each chapter owns:
- One historical transition
- One dominant constraint

If a chapter does not clearly own a transition, it does not belong.

---

## Forbidden Structural Patterns

- “This will be important later”
- “As we will see”
- “This sets the stage for”
- Circular explanations across parts
- Re-teaching previously settled concepts

---

## Enforcement

All content must:
- Conform to CHAPTER_TEMPLATE.md
- Pass CI_CHECKLIST.md
- Pass REVIEW_PROMPT.md

If structure and tone disagree, structure wins.
