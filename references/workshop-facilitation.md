# Behavioral Design Workshop Facilitation Guide

Three workshop formats for different contexts. All share the same principle: diagnosis before solution, evidence before intuition.

---

## Format 1: Behavioral Diagnosis Workshop (2–3 hours)

**Purpose:** Align a cross-functional team on the behavioral problem and identify root causes before touching the design.

**Participants:** Designer, product manager, researcher, data analyst. Optional: engineer, customer success rep.

**Materials:** Whiteboard or digital canvas (Figjam, Miro), sticky notes, drop-off data printed or accessible.

**Agenda:**

| Time | Activity | Description |
|------|----------|-------------|
| 15 min | Frame the behavior | Agree on one specific, observable behavior. Use the definition test: observable, measurable, specific. Don't proceed until it passes. |
| 30 min | Build the behavioral map | Co-create the step-by-step map of what users do. One step at a time. Mark each decision point and friction source. |
| 20 min | Overlay data | Add known drop-off rates, time-on-page data, support ticket themes to each step. Mark the biggest drops in red. |
| 45 min | 3Bs analysis | For each major drop-off: which barrier type? Which motivator is missing? Vote on which to address first. |
| 20 min | How Might We | For the top 1–2 barriers: generate "How Might We..." questions. Don't go to solutions yet. |
| 15 min | Next steps | Assign owners to intervention design tasks. Set a date for a follow-up sprint. |

**Facilitation tips:**
- Insist on behavior specificity before anything else. Teams waste entire sessions arguing about metrics because they haven't agreed on a specific behavior.
- During 3Bs analysis, go one drop-off point at a time. Depth over breadth.
- Separate diagnosis from solution rigorously. If someone jumps to "we should add a tooltip," redirect: "Let's finish diagnosing. What barrier type is that addressing?"
- Include people who talk to users (CS, support, sales) alongside people who build. Their qualitative signal is invaluable.

---

## Format 2: Intervention Design Sprint (half-day)

**Purpose:** Generate and prioritize behavioral interventions for a specific, already-diagnosed drop-off.

**Pre-requisite:** Completed behavioral diagnosis with a clear barrier type and target behavior identified.

**Agenda:**

| Time | Activity |
|------|----------|
| 20 min | Recap the diagnosis: barrier type, affected step, SPARK×WANT×AGAIN×CAN assessment |
| 20 min | Principle mapping: which techniques apply to this barrier? Review the technique library together. |
| 40 min | Crazy 8s: each participant sketches 8 distinct intervention ideas in 8 minutes (quantity over quality) |
| 30 min | Gallery walk: silent review of all sketches, then group discussion - which address the actual root cause? |
| 30 min | Hypothesis writing: write the top 3 interventions in "If... then... because..." format |
| 20 min | Experiment planning: for each hypothesis, what's the minimum viable test? What would we measure? |

**Facilitation tips:**
- Crazy 8s forces quantity and surfaces unexpected ideas. Don't let people explain during the 8 minutes - drawing only.
- During gallery walk, ask: "Does this address the barrier we diagnosed, or a different problem?" This filters solutions looking for problems.
- The hypothesis format is non-negotiable for the output. "We'll add a tooltip" is not testable. The full format ("If [change], then [metric change], because [mechanism]") is.
- End with a prioritized shortlist and clear next steps for testing - not just a list of ideas.

---

## Format 3: Behavioral Audit (90 minutes)

**Purpose:** Evaluate an existing product flow against behavioral design principles to find quick wins.

**Participants:** Designer, PM. Optional: researcher.

**Agenda:**

| Time | Activity |
|------|----------|
| 10 min | Choose the flow and define the target behavior for that flow |
| 60 min | Walk through the live product step by step, applying the behavioral audit checklist |
| 20 min | Prioritize findings by severity (High / Medium / Low) and effort to fix |

Use the audit checklist at [assets/behavioral-audit-template.md](../assets/behavioral-audit-template.md).

**Facilitation tips:**
- Walk through the actual product, not a prototype or description. Real interfaces reveal friction that polished mockups hide.
- For each finding: name the barrier type, which CAN/WANT/SPARK/AGAIN force, and a specific recommended change.
- Don't try to solve problems during the audit. The goal is a prioritized finding list - not a redesign session.
- Separate "quick fixes" (can be changed in days) from "structural changes" (require sprint planning).

---

## General Principles for All Workshop Types

**Behavior specificity first.** Don't proceed until the target behavior is uncomfortably specific. This is the single most common failure mode.

**Evidence over intuition.** Explicitly label the difference between "we know because data shows" and "we believe because." Hypothesis-driven design starts with honest labeling.

**Separate diagnosis from solution.** The best behavioral design thinking happens when teams resist jumping to solutions. Build the full diagnosis before generating interventions.

**Psychological safety for critique.** Behavioral design often reveals that existing design choices have created friction. Create explicit space to name these without blame - this session is about learning, not assigning fault.

**Test everything.** Every workshop output should end with a testing plan, not just a design plan. Behavioral interventions are hypotheses until measured.
