# A/B Test Aggregation Template
### How to use this template

1. Complete the Scoring Rubric Prompt for all persona variants
2. Collect all scored outputs into the Raw Scores section below
3. Paste the completed template into Claude Code
4. Ask Claude Code to run the aggregation and produce the ranked recommendation
5. Copy the output into your Executive Proposal methodology appendix

---

## Step 1 — Paste your raw scores here

*Copy and paste the formatted output from each Scoring Rubric Prompt below. Include all variants.*

```
[Paste all scored outputs here — one block per variant, in the format produced 
by the Scoring Rubric Prompt]
```

---

## Step 2 — Paste this aggregation prompt into Claude Code

```
I have run a synthetic A/B test of three campaign concepts across [X] persona 
variants representing three archetypes. The raw scores are pasted below.

Please do the following:

1. Parse all scores and build a summary table with the following columns:
   Persona Name | Archetype | Concept A Total | Concept B Total | Concept C Total | Top Pick

2. Calculate average total scores for each concept:
   - Overall average across all variants
   - Average by archetype (Tech Executive / Status Seeker / Special Occasion User)

3. Calculate average scores per dimension for each concept overall:
   - Average Resonance, Trust, Relevance, Distinctiveness

4. Identify:
   - The winning concept overall
   - The runner-up and margin of difference
   - Any concept that performed strongly with one archetype but poorly with another
   - The dimension where the winning concept scored highest
   - The dimension where the winning concept was most vulnerable

5. Produce a ranked recommendation in this format:

RANKED RECOMMENDATION

Winner: [Concept name]
Overall average score: [X / 20]
Strongest dimension: [Dimension name — avg score]
Most vulnerable dimension: [Dimension name — avg score]

Runner-up: [Concept name]
Overall average score: [X / 20]
Margin behind winner: [X points]

Third place: [Concept name]
Overall average score: [X / 20]

Archetype breakdown:
- Tech Executive archetype: favored [concept] (avg [X])
- Status Seeker archetype: favored [concept] (avg [X])
- Special Occasion archetype: favored [concept] (avg [X])

Notable splits: [Any concept that divided archetypes meaningfully]

Confidence level: [High / Medium / Low]
Basis for confidence level: [1-2 sentences — e.g. strong consensus across all 
archetypes, or clear winner but close race in one archetype]

Stated limits of this test:
- [Limit 1 — e.g. synthetic responses may overrepresent rational reasoning vs. 
  emotional reaction]
- [Limit 2 — e.g. panel size of X is directional, not statistically significant]
- [Limit 3 — e.g. concept descriptions were brief; full creative execution may 
  shift results]

RAW SCORES:
[Claude Code will read the raw scores you pasted in Step 1]
```

---

## Step 3 — What to do with the output

Copy the full Ranked Recommendation into:
- **Your Synthetic Persona Research Report** (the A/B test results section)
- **Your Executive Proposal** (the methodology appendix, Section A — Synthetic A/B Test Results)

The winning concept from this test becomes your **campaign creative direction** in the Executive Summary.
