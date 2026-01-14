# TERMINOLOGY_LOCKFILE.md
Machines That Talk Too Much

This file defines the ONLY approved terminology for the book.
All writing and rewriting must follow this file exactly.

Rule:
One concept → one term → one meaning.
No stylistic variation. No synonym rotation.

---

## 1. Core Model Terms

| Concept | Approved Term | Forbidden |
|------|---------------|-----------|
| General class | language model | AI, intelligence, brain |
| Large modern models | large language model | advanced AI |
| Abbreviation | LLM (after first definition) | LLMs before definition |

---

## 2. Model Behavior

| Concept | Approved Term | Forbidden |
|------|---------------|-----------|
| Core operation | predicting the next word | reasoning, thinking |
| Internal unit | token | symbol unit, word-piece |
| Output | text generation | expression, ideas |

---

## 3. Training

| Concept | Approved Term | Forbidden |
|------|---------------|-----------|
| Learning phase | training | learning like humans |
| Objective | next-token prediction | intention, goal |
| Post-training | fine-tuning | teaching, coaching |
| Alignment | behavior shaping | moral training |

---

## 4. Data

| Concept | Approved Term | Forbidden |
|------|---------------|-----------|
| Input material | training data | knowledge |
| Size | data scale | intelligence scale |
| Selection | filtering | curation (unless defined) |

---

## 5. Evaluation & Testing

| Concept | Approved Term | Forbidden |
|------|---------------|-----------|
| Measurement | evaluation | understanding check |
| Test sets | benchmarks | exams |
| Real-world use | deployment behavior | real intelligence |

---

## 6. Inference & Deployment

| Concept | Approved Term | Forbidden |
|------|---------------|-----------|
| Runtime phase | inference | thinking time |
| Trade-offs | latency vs cost | speed vs smartness |
| Serving models | deployment | release of intelligence |

---

## 7. Anthropomorphism Ban List

The following are NEVER allowed for models:

- understands
- thinks
- knows
- believes
- wants
- decides
- reasons like a human

Required replacements:
- predicts
- produces
- outputs
- selects
- responds with

---

## 8. Scope Control (Hard Boundary)

### Allowed Scope
- Historical evolution of language models
- Data, training, evaluation, inference
- Engineering constraints and trade-offs
- Why simple objectives scale

### Forbidden Scope (unless explicitly approved)
- Consciousness
- AGI
- Philosophy of mind
- Ethics debates (beyond operational impact)
- Sci-fi futures
- Company drama

If mentioned, it must be brief and explicitly marked as out of scope.

---

## 9. General vs Technical Language Rule

| Prefer This | Over This |
|-----------|-----------|
| word | token (until defined) |
| guessing | probabilistic inference |
| scale | orders of magnitude |
| constraints | optimization landscape |

Rule:
Introduce the simple term first.
Introduce the technical term once.
Then lock it.

---

## 10. Rewrite Enforcement Clause

All rewrite prompts MUST include:

“Follow TERMINOLOGY_LOCKFILE.md exactly.
Do not introduce synonyms for locked terms.
Normalize any synonym in the input to the approved term.”
