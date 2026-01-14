# Part <N>: <Part Title>

> Scope of this part (1–2 sentences, factual, no hype):
> Describe what this part covers and what it deliberately does not cover.

---

## Chapter <N>: <Chapter Title>

> Purpose of this chapter (1 sentence):
> What changes in this chapter compared to what the reader already knows.

---

### Context Assumptions (Do Not Write in Final Text)

- All previous parts are complete.
- Concepts introduced in earlier parts may be referenced briefly.
- No concepts from later parts may appear.
- This chapter must be readable independently within this part.

---

## Section <N>.<N>: <Section Title>

> Section intent (internal):
> Why this section exists and what narrow question it answers.

#### Allowed Content
- Facts and explanations that belong strictly to this section’s time period or system layer
- Operational constraints (data, compute, evaluation, inference)
- Trade-offs that were visible at the time

#### Forbidden Content
- Forward references to later sections or chapters
- General summaries of earlier parts
- Philosophical or speculative discussion
- Vendor-specific narratives

---

### Subsection <N>.<N>.<N>: <Subsection Title> (Optional)

> Subsection intent (internal):
> The single idea this subsection is responsible for.

**Rules:**
- Introduce at most ONE new concept.
- If a term is reused from earlier parts, reference it briefly without redefinition.
- If a term is new, define it once and lock it via TERMINOLOGY_LOCKFILE.md.

---

### Writing Rules (Hard Constraints)

- Write in plain paragraphs. No lists unless necessary.
- Short paragraphs (3–5 sentences max).
- One idea per paragraph.
- No rhetorical questions.
- No analogies unless explicitly approved.

---

### Scope Guardrails (Mandatory)

Before writing, check:
- Does this content belong in this part?
- Does it assume knowledge from future parts?
- Does it re-explain something already settled?

If any answer is “yes”, rewrite or remove.

---

### End-of-Chapter Boundary

This chapter may:
- Clarify what has changed since earlier chapters
- State limitations of the current approach

This chapter may NOT:
- Preview future solutions
- Hint at upcoming breakthroughs
- Speculate beyond available evidence

---

### Internal Review Checklist (Before Commit)

- Terminology matches TERMINOLOGY_LOCKFILE.md
- No anthropomorphism
- No hype language
- No scope leakage
- No structural drift

If any item fails, the chapter is not complete.
