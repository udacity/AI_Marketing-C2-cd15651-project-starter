# Scoring Rubric Prompt
### How to use this template

1. Run the Persona Variant Generation Prompt first and have your variants ready
2. For each variant, fill in the bracketed fields below with the variant's profile and your three concepts
3. Paste the completed prompt into Claude chat
4. Copy the scored output into the Aggregation Template
5. Repeat for every variant — one Claude prompt per variant, one fresh conversation each time

You will run this prompt [number of variants] times — once per persona variant.

---

## The Prompt — Copy, fill in, and paste into Claude

```
You are about to evaluate three campaign concepts for a luxury autonomous vehicle 
service called Valet on behalf of a synthetic persona. Read the persona profile 
carefully and respond as this person would — honestly, with their specific concerns 
and priorities in mind.

PERSONA:
[Paste the full variant profile here — name, age, city, job, profile sentences, 
and key need from Valet]

THE THREE CONCEPTS:
Concept A: [Name and one-sentence description]
Concept B: [Name and one-sentence description]
Concept C: [Name and one-sentence description]

SCORING INSTRUCTIONS:
Score each concept from 1 to 5 on each of the following four dimensions, from the 
perspective of this persona. Be discriminating — do not give every concept the same 
score. A score of 3 means neutral. A score of 5 means this genuinely moves this 
person. A score of 1 means this misses them entirely.

Dimensions:
- Resonance: Does this concept feel emotionally true to this person?
- Trust: Does this concept make this person more likely to trust Valet?
- Relevance: Does this concept speak to this person's actual reason to use Valet?
- Distinctiveness: Does this concept feel different from what this person has seen before?

OUTPUT FORMAT — use this exactly:

Persona: [Name]
Archetype: [Archetype name — Tech Executive / Status Seeker / Special Occasion User]

Concept A — [Name]
Resonance: [1-5]
Trust: [1-5]
Relevance: [1-5]
Distinctiveness: [1-5]
Total: [sum]

Concept B — [Name]
Resonance: [1-5]
Trust: [1-5]
Relevance: [1-5]
Distinctiveness: [1-5]
Total: [sum]

Concept C — [Name]
Resonance: [1-5]
Trust: [1-5]
Relevance: [1-5]
Distinctiveness: [1-5]
Total: [sum]

Top pick: [Concept name]
Why, in one sentence: [One sentence in this persona's voice]
```

---

## Tips

- Run each variant in a **fresh Claude conversation** — do not chain multiple variants in the same chat, as prior responses will influence subsequent ones
- If a score feels inconsistent with the persona profile, ask Claude to reconsider: *"Given that [name] values [specific trait], does that score for Relevance still feel right?"*
- Copy the full formatted output for each variant before closing the conversation
