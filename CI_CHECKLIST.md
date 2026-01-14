# CI Checklist
Machines That Talk Too Much

This checklist is a **merge gate**.
All items must pass before content is merged.

---

## Structural Integrity

- [ ] Content belongs to the stated Part, Chapter, and Subchapter
- [ ] No forward references to future parts or chapters
- [ ] No detailed re-explanations of earlier parts
- [ ] Chapter is readable independently within its part

---

## Scope Control

- [ ] Content stays within data, training, evaluation, and inference
- [ ] No speculation about AGI, consciousness, or futures
- [ ] No ethics or philosophy beyond operational impact
- [ ] No vendor or company-specific narratives

---

## Terminology Discipline

- [ ] All terms match TERMINOLOGY_LOCKFILE.md
- [ ] No synonym rotation for locked terms
- [ ] New terms (if any) are defined once and locked
- [ ] “Token” is not used before definition

---

## Tone Enforcement

- [ ] No hype or marketing language
- [ ] No motivational or promotional tone
- [ ] No anthropomorphism
- [ ] No conversational or blog-style writing

---

## Clarity & Audience Fit

- [ ] Paragraphs are short and focused
- [ ] One idea per paragraph
- [ ] Language is understandable without ML background
- [ ] No unnecessary jargon

---

## Review Completion

- [ ] REVIEW_PROMPT.md returns `PASS`
- [ ] All flagged issues resolved or content rejected
- [ ] Chapter conforms to CHAPTER_TEMPLATE.md

---

## Final Rule

If any checkbox fails:
**Do not merge.**
