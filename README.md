# behavioral-design — Claude Skill

A Claude skill that applies **behavioral psychology** and **behavioral economics** to product and UX design challenges.

Install this skill to get structured, testable guidance on:

- Diagnosing why users aren't completing flows or adopting features
- Designing nudges and behavior-change interventions
- Running behavioral design workshops and design sprints
- Auditing existing designs for psychological effectiveness
- Applying principles like loss aversion, social proof, choice architecture, and habit formation

---

## Install

Download [`behavioral-design.skill`](behavioral-design.skill) and open it, or drag it into Claude Code.

---

## What it does

The skill uses a **three-phase behavioral design process**:

### Phase 1 — Behavioral Diagnosis
Define a precise, observable target behavior. Map every step the user takes. Identify where and why users drop off.

### Phase 2 — Barrier Analysis (3Bs Model)
Classify each drop-off using four barrier types:
- **Attention barriers** — user doesn't notice or remember
- **Cognitive overload** — decision is too complex or effortful
- **Status quo bias** — inertia keeps users with current behavior
- **Mental model mismatch** — user's understanding doesn't match the design

### Phase 3 — Intervention Design
Design testable interventions using the **SPARK × WANT × AGAIN × CAN** formula:

| Force | Addresses | Example techniques |
|-------|-----------|-------------------|
| **CAN** | Friction / capability | Smart defaults, chunking, pre-filling, option reduction |
| **WANT** | Motivation | Social proof, loss framing, progress visibility, identity connection |
| **SPARK** | Triggers | Contextual timing, event-based prompts, multiple touchpoints |
| **AGAIN** | Habit formation | Streaks, habit stacking, celebration moments, review loops |

Every intervention is expressed as a testable hypothesis:
> *"If [design change], then [behavior change + metric], because [psychological mechanism]."*

---

## Psychological principles covered

| Principle | Design application |
|-----------|-------------------|
| Present Bias | Add near-term rewards |
| Social Norms | Make norms visible |
| Loss Aversion | Frame around what users lose by NOT acting |
| Choice Overload | Reduce options, use smart defaults |
| Implementation Intentions | Ask users to commit to a specific plan |
| Status Quo Bias | Show cost of inaction, make new behavior the default |
| Hyperbolic Discounting | Connect actions to near-term consequences |
| Intention-Action Gap | Use pre-commitment, reduce activation energy |

---

## Use cases

| Situation | What the skill does |
|-----------|-------------------|
| "Users drop off at step 3 of our onboarding" | Full behavioral diagnosis + prioritized interventions |
| "Our feature has 8% adoption after 6 months" | Four Forces diagnosis + SPARK/WANT fixes |
| "I want to design a nudge for our health app" | Intervention design + ethics review |
| "I need to run a behavioral design workshop" | Agenda + facilitation guide |
| "Audit our checkout flow" | Step-by-step behavioral audit with findings + hypotheses |

---

## Included files

```
behavioral-design/
├── SKILL.md                          # Core skill (mode routing, frameworks, quick reference)
├── references/
│   ├── behavioral-diagnosis.md       # Behavioral mapping deep guide
│   ├── barriers-benefits-model.md    # 4 barrier types × 3 motivator types
│   ├── intervention-techniques.md    # 20+ named techniques with examples
│   ├── behavior-change-formula.md    # SPARK×WANT×AGAIN×CAN diagnostic flow
│   ├── sue-influence-framework.md    # Four Forces (Pains/Gains/Anxieties/Comforts)
│   ├── ethics-checklist.md           # 5-point ethics checklist + dark patterns guide
│   └── workshop-facilitation.md      # 3 workshop formats with full agendas
└── assets/
    ├── diagnosis-report-template.md  # Fillable diagnosis report
    ├── hypothesis-template.md        # Experiment hypothesis template
    └── behavioral-audit-template.md  # CAN/WANT/SPARK/AGAIN/Ethics audit checklist
```

---

## Ethics built in

Every output from this skill includes an ethics check that distinguishes **nudges** (makes a beneficial behavior easier while preserving free choice) from **manipulation** (exploits vulnerabilities or hides intent). The skill surfaces dark patterns and flags when a proposed intervention may cross the line.

---

## Who this is for

- Product designers and UX designers
- Design managers and design leads
- Product managers and product teams
- UX researchers
- Service designers and field service designers
- Cross-functional product teams running design sprints

---

## Keywords

behavioral design, behavioral economics, nudge design, behavior change, UX psychology, product psychology, friction reduction, cognitive load, choice architecture, loss aversion, social proof, habit formation, onboarding optimization, feature adoption, engagement design, conversion optimization, design sprint, behavioral audit, intervention design, mental models, design thinking, product design

---

## License

MIT
