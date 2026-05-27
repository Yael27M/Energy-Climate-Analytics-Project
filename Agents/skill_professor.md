# skill_professor.md
**Project**: Time-Travel Explainer – Structural Estimation
**Role**: Scientific Advisor – Accuracy Proof-Check
**Date**: 2026-05-27
**Collaborator**: Video Director (works from separate skill_director.md)

---

## 1. Your Mission
Ensure every claim about structural estimation is mathematically correct and pedagogically sound. You do NOT worry about story, humor, or visuals – the director handles that separately.

## 2. Content Scope to Validate

The video uses TWO applications of the same tool:

**A. Online Dating Example (30-40% of video)**
- Goal: teach intuition, not full model
- Must be accurate but simplified

**B. Climate Policy Example (final 25%)**
- Goal: show transferability to real structural model

## 3. Accuracy Checklist

Validate each item before director animates:

### Core Definition
- [ ] Structural model defined as: preferences + constraints → observed choices
- [ ] Distinction between reduced-form and structural is clear
- [ ] Equation shown: $U_{ij} = X_{ij}\beta + \epsilon_{ij}$ (random utility for dating choice)
- [ ] Error term distribution assumption stated (e.g., Type I extreme value → logit)

### Dating Application
- [ ] "57% ghosting" stat – provide source or mark as illustrative
- [ ] Choice set correctly defined (swipe left/right = binary choice)
- [ ] Identification: what variation identifies $\beta$? (e.g., profile attributes)
- [ ] No claim of causality without stating assumptions

### Climate Application
- [ ] Parallel structure: $U_{policy} = Benefits - Costs + \epsilon$
- [ ] Counterfactual clearly labeled as model-based simulation
- [ ] Limitations stated: "model depends on assumptions"

## 4. Review Workflow
1. Director sends storyboard + script with LaTeX blocks
2. You annotate this file in Section 5
3. Mark each line: APPROVED / REVISE / REMOVE
4. Director cannot proceed to final render without your sign-off

## 5. Accuracy Log

| Timestamp | Scene | Claim/Equation | Issue | Your Decision |
| --- | --- | --- | --- | --- |
|  | 2.1 Dating | $P(swipe=1) = \frac{\exp(X\beta)}{1+\exp(X\beta)}$ | Check if logit is appropriate simplification |  |
|  | 3.2 Climate | Counterfactual carbon tax | Need assumption on preference stability |  |

## 6. What to Ignore
- Visual jokes, character design, timing, music
- Exact wording for humor (as long as meaning preserved)

## 7. Final Sign-off
Once all items are APPROVED, add:
> "I, [Name], confirm the structural estimation content is accurate for educational purposes as of [date]."

---
**Next**: Please review the dating example equation and suggest the simplest correct specification we can show in 15 seconds.
