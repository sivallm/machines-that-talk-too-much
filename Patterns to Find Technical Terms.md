# Patterns to Find Technical Terms

## Pattern 1 — Find the term
> "What is the term for [behavior/property] in [domain]?"

- "What is the term for a service that automatically restarts when it crashes, in Linux?"
- "What is the term for a port that is assigned temporarily by the OS, in networking?"
- "What is the term for a node that coordinates all writes, in distributed databases?"

---

## Pattern 2 — Situation to term
> "I have [situation]. What is this called?"

- "I have a container that loses all data when it stops. What is this called?"
- "I have a service that queues requests when it is overloaded instead of rejecting them. What is this called?"
- "I have a token that is valid for 15 minutes only. What is this called?"

---

## Pattern 3 — Behavior to term
> "What do you call something that [does X]?"

- "What do you call something that intercepts all outgoing network requests?"
- "What do you call something that checks if a service is alive before sending traffic to it?"
- "What do you call something that stores the result of an expensive calculation to reuse later?"

---

## Pattern 4 — Problem to term
> "What is the term for the problem where [describe the problem]?"

- "What is the term for the problem where two processes wait for each other and neither continues?"
- "What is the term for the problem where a service waits forever for a response that never comes?"
- "What is the term for the problem where old data is read because the cache was not updated?"

---

## Pattern 5 — Opposite/contrast
> "What is the opposite of [known term] in [domain]?"

- "What is the opposite of stateless, in services?"
- "What is the opposite of horizontal scaling, in infrastructure?"
- "What is the opposite of blocking, in I/O operations?"

---

## Fallback — Unknown domain
> "I have [situation]. Which domain does this belong to and what is the term?"

- "I have a system where one slow part causes everything else to stop. Which domain does this belong to and what is the term?"
- "I have data that is duplicated across two places and they go out of sync. Which domain does this belong to and what is the term?"