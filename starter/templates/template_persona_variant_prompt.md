# Persona Variant Generation Prompt
### How to use this template

1. Fill in the bracketed fields below with your archetype details
2. Paste the completed prompt into a new Claude chat conversation
3. Claude will generate [X] persona variants based on your archetype
4. Copy the full output — you will use each variant in the Scoring Rubric Prompt

Run this prompt once per archetype. You need at least 3 variants per archetype (9 total minimum).

---

## The Prompt — Copy, fill in, and paste into Claude

```
I am conducting synthetic persona research for a luxury autonomous vehicle service 
called Valet. I have defined three core persona archetypes. I need you to generate 
[NUMBER — minimum 3, recommended 5] distinct variants of the following archetype.

ARCHETYPE PROFILE:
Name: [Archetype name — e.g. Marcus, The Tech Executive]
Core description: [2-3 sentences summarizing who this person is, their income level, 
lifestyle, and relationship to transportation and technology]
Primary purchase driver: [What would make this person use Valet — e.g. efficiency 
and zero friction, status and being first, special occasion quality]

VARIANT INSTRUCTIONS:
Each variant should:
- Share the core profile above (same income range, same primary purchase driver, 
  same general lifestyle)
- Differ in: age (within a 15-year range), city, specific job title, and 1-2 
  personality traits that might affect how they respond to brand messaging
- Feel like a real, distinct person — not a slight variation on the same character
- Be described in 4-6 sentences covering: who they are, how they get around, their 
  relationship to autonomous vehicles, and one specific thing they would need from 
  Valet to consider using it

FORMAT:
For each variant output the following, clearly labeled:
Variant [number]: [First name]
Age: 
City:
Job:
Profile: [4-6 sentences]
Key need from Valet: [One sentence]
```

---

## Example — filled in for the Marcus archetype

```
I am conducting synthetic persona research for a luxury autonomous vehicle service 
called Valet. I have defined three core persona archetypes. I need you to generate 
5 distinct variants of the following archetype.

ARCHETYPE PROFILE:
Name: Marcus, The Tech Executive
Core description: A high-income urban professional in the tech or finance sector, 
aged 35-50, who uses premium rideshare for work travel and has already encountered 
autonomous vehicles. Efficiency and zero friction are his primary values — he wants 
transportation that disappears.
Primary purchase driver: Reliability, pickup precision, and zero human interaction. 
Not motivated by status. Motivated by consistent, frictionless performance.

VARIANT INSTRUCTIONS:
Each variant should:
- Share the core profile above (same income range, same primary purchase driver, 
  same general lifestyle)
- Differ in: age (within a 15-year range), city, specific job title, and 1-2 
  personality traits that might affect how they respond to brand messaging
- Feel like a real, distinct person — not a slight variation on the same character
- Be described in 4-6 sentences covering: who they are, how they get around, their 
  relationship to autonomous vehicles, and one specific thing they would need from 
  Valet to consider using it

FORMAT:
For each variant output the following, clearly labeled:
Variant [number]: [First name]
Age: 
City:
Job:
Profile: [4-6 sentences]
Key need from Valet: [One sentence]
```
