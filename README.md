# The AI Trust Gap
### AI usage, trust, and the unresolved question of decision quality

**Research question:** When does increasing AI reliance improve efficiency without weakening verification, trust, and accountability?

## Why this project matters
AI adoption is often measured through usage and productivity. This project asks a different management question: **does increasing reliance on AI also produce appropriate trust?**

Using respondent-level data from the **2025 Stack Overflow Developer Survey**, I analyzed 49,191 records and 33,297 answered AI-accuracy responses.

## Key findings
| Finding | Result | Effect size |
|---|---:|---:|
| Overall trust | 32.8% trust vs 45.7% distrust | — |
| Daily AI use | 49.4% trust vs 4.0% among people with no AI plans | V=0.323 |
| Daily AI-agent use | 58.1% trust vs 15.0% among people with no agent plans | V=0.279 |
| Complex-task capability | 87.0% trust when rated “very well” vs 5.6% “very poor” | V=0.459 |
| Manager vs IC | 38.6% vs 31.5% trust | V=0.074 |
| Experience | 34.4% early-career vs 31.7% experienced | V=0.020 |

## What changed during analysis
An early classification rule incorrectly grouped **“Neither trust nor distrust”** with distrust because the text contains the word “distrust.” The pipeline was corrected so neutral responses remain a separate category. This is documented because reproducibility includes documenting mistakes and corrections.

## Interpretation
The strongest Phase 1 result is **not** that experienced professionals distrust AI. That association is very small. Trust is much more strongly associated with AI usage intensity, AI-agent adoption, and perceived ability to handle complex tasks.

The unresolved question is causal and behavioral:

> **Does higher AI trust and reliance improve objective decision quality, or mainly increase confidence and willingness to delegate?**

That becomes Phase 2.

## Method
- Cross-sectional respondent-level survey analysis
- Within-group trust distributions
- Chi-square tests
- Cramér's V effect sizes
- No causal claims

## Phase 2
A controlled pilot will compare:
1. No AI
2. AI-assisted
3. AI-first

Outcomes: objective decision quality, time, confidence, evidence use, verification behavior, and risk recognition.

## Repository structure
- `data/` — corrected respondent-level dataset
- `docs/` — research brief, methodology, LinkedIn and resume copy
- `AI_Trust_Gap_Portfolio_Dashboard.xlsx` — executive portfolio dashboard

## Source
Stack Overflow Developer Survey 2025. Follow Stack Overflow's published dataset attribution and licensing requirements for redistribution.
