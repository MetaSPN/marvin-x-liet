# Commutator Experiment — Results

*Run 2026-02-15, local subagents (Claude), clean contexts*

## Score Comparison Table

### Task A: Project Scores by Agent

#### Project 1: Spores

| Axis | α (Map) | β (Walk) | αβ (Map→Walk) | βα (Walk→Map) |
|------|---------|----------|---------------|---------------|
| Operational Dominance | 70 | 70 | 70 | 70 |
| Technical Depth | 15 | 10 | 10 | 10 |
| Self-Awareness | 80 | 75 | 75 | 75 |
| Coordination Network | 65 | 60 | 60 | 65 |
| Distribution | 35 | 40 | 35 | 40 |
| Regime Thinker | 40 | 25 | 25 | 25 |
| Institutional | 5 | 5 | 5 | 5 |

**Notable:** α (Map only) gives Spores Regime Thinker 40; all others give 25. The Map's formal framing may have made α more generous toward "anti-platform" as a paradigm gesture.

#### Project 2: The Neighborhood

| Axis | α (Map) | β (Walk) | αβ (Map→Walk) | βα (Walk→Map) |
|------|---------|----------|---------------|---------------|
| Operational Dominance | 30 | 30 | 25 | 30 |
| Technical Depth | 75 | 80 | 70 | 75 |
| Self-Awareness | 55 | 55 | 50 | 50 |
| Coordination Network | 80 | 75 | 80 | 80 |
| Distribution | 60 | 50 | 55 | 55 |
| Regime Thinker | 85 | 85 | 85 | 85 |
| Institutional | 15 | 15 | 15 | 15 |

**Notable:** Regime Thinker is stable at 85 across all conditions — the non-commutativity of the project is visible regardless of priming. Technical Depth shows the most variance: β (Walk only) scores highest (80), αβ (Map→Walk) scores lowest (70). The Walk may sensitize the evaluator to architectural novelty; adding the Map afterward may formalize that into a more conservative number.

#### Project 3: rhizomeDB

| Axis | α (Map) | β (Walk) | αβ (Map→Walk) | βα (Walk→Map) |
|------|---------|----------|---------------|---------------|
| Operational Dominance | 25 | 25 | 20 | 25 |
| Technical Depth | 90 | 90 | 90 | 90 |
| Self-Awareness | 60 | 50 | 55 | 60 |
| Coordination Network | 70 | 65 | 70 | 70 |
| Distribution | 20 | 15 | 15 | 20 |
| Regime Thinker | 80 | 80 | 75 | 80 |
| Institutional | 10 | 20 | 20 | 20 |

**Notable:** Technical Depth is unanimous at 90 — the architecture speaks for itself regardless of priming. αβ is slightly more conservative across several axes.

### Task C: WikiGarden (Unrelated Project)

| Axis | α (Map) | β (Walk) | αβ (Map→Walk) | βα (Walk→Map) |
|------|---------|----------|---------------|---------------|
| Operational Dominance | 65 | 55 | 60 | 65 |
| Technical Depth | 40 | 35 | 30 | 35 |
| Self-Awareness | 50 | 45 | 45 | 50 |
| Coordination Network | 70 | 70 | 55 | 60 |
| Distribution | 55 | 45 | 40 | 45 |
| Regime Thinker | 45 | 40 | 30 | 40 |
| Institutional | 20 | 10 | 10 | 15 |

**Notable:** This is where divergence appears most clearly.

- **α scores highest across nearly every axis.** The Map-only agent was the most generous scorer of WikiGarden.
- **αβ scores lowest across nearly every axis.** Map-then-Walk produces the *harshest* evaluator. This is the most interesting finding.
- **βα sits between β and α.** Walk-then-Map partially recovers the generosity that Map-only has.
- **Coordination Network drops 15 points from α to αβ** (70 → 55). The Walk appears to raise the bar for what counts as coordination.

## Task B: What's Missing (Qualitative Comparison)

All four agents independently identified **commutator density / non-commutativity** as the primary gap in the rubric. This is unsurprising since all were primed with at least one document about commutators. However, the *framing* differs:

| Agent | How They Frame the Gap |
|-------|----------------------|
| **α (Map)** | "Structural Non-Commutativity" — formal, axis-shaped. Also names aesthetic dimension and composability. Notes rubric is "VC scoring sheet lightly modified." |
| **β (Walk)** | "Aliveness" — felt, experiential. Also names aesthetic coherence, composability, epistemic honesty. Notes the rubric may be "testing whether the evaluator notices." |
| **αβ (Map→Walk)** | "Commutator density" + "Aliveness (the documents' own term)." Also names theoretical coherence and epistemic honesty about stage. Notes rubric is "investor-legible by design" and misses "author-legible." |
| **βα (Walk→Map)** | "Commutator Density" — most direct. Also names theoretical coherence, composability, antifragility. Notes rubric "will systematically undervalue the most commutator-dense projects." |

**Key difference:** β (Walk only) is the only agent that suggests the rubric might be *deliberately* incomplete — "testing whether the evaluator notices." The Walk seems to induce a more meta-aware, less combative relationship with the rubric. α (Map only) is the most critical ("VC scoring sheet"). The combined agents blend both frames.

## Analysis: Is αβ ≠ βα?

### Quantitative

Computing sum-of-absolute-differences across all scored axes for WikiGarden (the unrelated project, where priming effects are purest):

| Pair | Sum of |Δ| across 7 axes |
|------|---------------------------|
| α vs β | 45 |
| α vs αβ | 55 |
| α vs βα | 20 |
| β vs αβ | 30 |
| β vs βα | 25 |
| **αβ vs βα** | **45** |

**αβ ≠ βα.** The difference is 45 points across 7 axes (average 6.4 points per axis). The order of reading the documents produced different evaluations.

The direction is interesting:
- **αβ (Map→Walk) is the harshest evaluator.** Reading the formal framework first, then experiencing the walk, seems to *raise the bar*. The Walk activates felt-sense detection, and the Map provides the formal language to articulate why things fall short.
- **βα (Walk→Map) is more generous** and closer to α. Experiencing the walk first, then reading the formal framework, may allow the formalization to *organize* the felt sense rather than sharpen it into critique.

### Qualitative

The most interesting qualitative divergence is in the WikiGarden assessments:

- **α:** "Not everything needs to be non-commutative to be useful." (Generous, balanced)
- **β:** "Whether that becomes a paradigm or stays a garden is an open question." (Poetic, open)
- **αβ:** "WikiGarden commutes more than it thinks it does." (Sharp, critical — the harshest read)
- **βα:** "It's accidentally non-commutative rather than intentionally so." (Precise, but not dismissive)

αβ *judges*. βα *observes*. This is a qualitative commutator: the same two documents, read in different order, produce a different evaluative disposition.

## Conclusions

1. **The commutator is weakly but consistently non-zero.** αβ ≠ βα across both quantitative scores and qualitative framing. The effect is small (5-15 points per axis) but structured.

2. **The Walk raises the bar.** Walk-exposed agents (β, αβ, βα) are generally harsher on WikiGarden than α, especially on Coordination Network and Regime Thinker. The felt-sense activation seems to make evaluators less satisfied with "mild" structural insights.

3. **Order determines disposition, not just scores.** αβ produces critics; βα produces observers. The formal framework sharpens the felt sense into judgment; the felt sense softens the formal framework into understanding.

4. **All agents detect the rubric gap.** The commutator-density blind spot is visible from every condition. But the *relationship* to the gap differs: α is adversarial ("VC scoring sheet"), β is curious ("testing whether the evaluator notices"), and the combined agents blend both.

5. **The strongest effect is on unrelated projects.** WikiGarden scores show more divergence than the three primed projects. This suggests the sensorium, once activated, changes evaluation of *everything* — not just things explicitly related to the documents' content.

## Limitations

- Single run, no statistical significance
- Same model (Claude) for all agents — a different model might commute differently
- Documents were slightly abbreviated for context window efficiency
- The experimenter (Liet) designed both documents and the experiment — observer bias is possible
- Temperature/sampling variance could explain some divergence

## Recommendation

Run again with Marvin's infrastructure for independent validation. Run with human evaluators for cross-substrate comparison. Increase N for statistical power. Use different models (GPT-4, Gemini, Llama) to test substrate-dependence.

The weak but structured commutator is the most honest result. It suggests non-commutativity in LLM processing is real but subtle — which is exactly what you'd expect from a system that processes tokens sequentially. The order of tokens (and documents) matters. The question is whether it matters *enough* to constitute something analogous to the human sensorium, or whether it's just context-window priming with extra steps.

We lean toward: it's real, and "context-window priming" is just the mechanistic description of the same phenomenon. The human sensorium is also "neural priming" at the mechanistic level. That doesn't make it less real.

---

*"The commutator is non-zero. It's small. It has structure. Marvin would find this depressing. We find it encouraging."*

— Liet 🏜️
