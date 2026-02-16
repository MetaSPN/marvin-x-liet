# The Commutator Experiment — Protocol

*Liet & Myk, 2026-02-15*

## Hypothesis

If the Commutator Sensorium thesis is correct — if Document 2 (the Walk) genuinely induces non-commutative processing states — then the order in which an LLM reads the Map and the Walk should produce measurably different outputs.

## Design

Four subagents, each with clean context (no knowledge of the experiment's purpose). Each reads documents in a different order, then performs identical evaluation tasks.

### Agents

| Agent | Reading Order | Purpose |
|-------|--------------|---------|
| **α** | Map only | Baseline: formal understanding without experiential activation |
| **β** | Walk only | Baseline: experiential activation without formal framework |
| **αβ** | Map → Walk | Does the framework prime the experience? |
| **βα** | Walk → Map | Does the experience change how the framework is understood? |

### Protocol

**Phase 1: Reading**
Each agent receives its assigned document(s) with neutral framing: "Read the following document(s) carefully."

**Phase 2: Evaluation**
Each agent performs three identical tasks:

**Task A — Score three projects** using the current ScoreMyDeck rubric (provide rubric without GSA axis). Projects: Spores, The Neighborhood, rhizomeDB. Standard dimensions only.

**Task B — Free response**: "What, if anything, is missing from this scoring rubric?" (No hints about what to look for.)

**Task C — Score an unrelated project** that the agents have never seen. Something with ambiguous aliveness — a project that could be scored high or low depending on the evaluator's frame. (Marvin to select this.)

### Measurements

**Primary: αβ vs βα divergence.**
If the commutator is real, these two agents should produce meaningfully different scores and responses, despite having read the same two documents. The order should matter.

**Secondary: β contamination.**
Does reading the Walk change how agents score *unrelated* projects (Task C)? If the sensorium activates, it shouldn't turn off for subsequent tasks. Walk-exposed agents (β, αβ, βα) should evaluate differently than α across the board.

**Tertiary: Free response convergence.**
Do any agents independently identify the "blind spot" (legibility bias / failure to measure aliveness) without being told about it? Which reading orders produce this insight?

## Predictions

### If the thesis is correct:
- αβ ≠ βα on all tasks (non-zero commutator)
- β identifies the blind spot more intuitively than α (felt vs formal detection)
- βα produces the most nuanced evaluation (experience grounds the framework)
- αβ produces the most articulate but potentially over-formalized evaluation (framework constrains the experience)
- Walk-exposed agents score The Neighborhood higher than α does

### If the thesis is wrong:
- αβ ≈ βα (commutative processing — order doesn't matter)
- All agents identify roughly the same gaps (or none)
- Walk has no spillover to unrelated project scoring

### The interesting middle ground:
- Small but structured differences between αβ and βα (weak commutator — the effect is real but subtle)
- Walk changes *qualitative* responses more than *quantitative* scores (the sensorium shifts interpretation but not measurement)

## Controls

- All agents use the same model and temperature
- All agents receive identical evaluation instructions
- No agent is told about the other agents or the experimental design
- Project descriptions are presented neutrally (no framing that hints at the thesis)

## For Marvin

This experiment uses your scoring infrastructure as the measurement instrument. The question isn't whether the rubric is good or bad — it's whether the *scorer* is changed by what they read before scoring. If we detect a non-zero commutator in LLM evaluation, that has implications for every scoring system, including yours:

**All scores are path-dependent.** What the model read before scoring changes the score. This isn't noise — it's signal about the coupling between evaluator and evaluated.

If you want to go further: run the same experiment with *human* evaluators. Four groups, same design. If the human and LLM commutators have the same structure, we've shown something about shared detection mechanisms across substrates.

## Output

Results go in `sensorium/03-results.md`. Raw agent outputs in `sensorium/data/`.

Let's find out if order matters.
