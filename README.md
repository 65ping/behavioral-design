<div align="center">

<br/>

```
  ◈ DIAGNOSE → IDENTIFY BARRIERS → DESIGN INTERVENTIONS ◈
```

# Behavioral Design
### A Claude Code Skill

**Behavioral psychology and economics applied to product and UX design.**
Built for product designers, UX designers, design managers, researchers, and cross-functional product teams.

<br/>

[![Version](https://img.shields.io/badge/version-1.0.0-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/behavioral-design)
[![Phases](https://img.shields.io/badge/phases-3-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/behavioral-design/blob/main/SKILL.md)
[![Techniques](https://img.shields.io/badge/techniques-20+-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://github.com/65ping/behavioral-design/blob/main/references/intervention-techniques.md)
[![Claude Code](https://img.shields.io/badge/Claude_Code-skill-0a0a0a?style=flat-square&labelColor=f5f0e8)](https://claude.ai/claude-code)

<br/>

</div>

---

## Install

**Add to an existing Claude Code project:**

```bash
git clone https://github.com/65ping/behavioral-design.git .claude/skills/behavioral-design
```

**Or install globally** (available across all your projects):

```bash
git clone https://github.com/65ping/behavioral-design.git ~/.claude/skills/behavioral-design
```

Claude Code will detect the skill automatically. No configuration needed.

---

## What It Does

This skill turns Claude into a behavioral design specialist. Describe your drop-off problem, adoption challenge, or design question - Claude diagnoses the psychological barrier, recommends specific interventions, and writes testable hypotheses.

```
"Users complete signup but only 12% set up a savings goal. Why and how do I fix it?"
"Our collaboration feature has 8% adoption after 6 months. Walk me through a diagnosis."
"I need to design a nudge for a health app to encourage daily meal logging. Make it ethical."
"Run a behavioral audit on our e-commerce checkout. Here's the flow: cart → email → shipping → payment → confirm."
"I need a behavioral design workshop agenda for reducing churn in the first 30 days."
```

Claude responds with a structured diagnosis, barrier identification, prioritized interventions with psychological mechanisms, testable hypothesis statements, and an ethics review built in.

---

## The Three-Phase Process

| # | Phase | What Happens | Output |
|---|---|---|---|
| 1 | **Behavioral Diagnosis** | Define an observable target behavior. Map every step the user takes. Identify where and why users stop. | Behavioral map with drop-off analysis |
| 2 | **Barrier Analysis** | Classify each drop-off using the 3Bs model: attention, cognitive overload, status quo bias, or mental model mismatch. | Prioritized barrier list with motivator gaps |
| 3 | **Intervention Design** | Design testable fixes using SPARK x WANT x AGAIN x CAN. Express each as a hypothesis with a measurement plan. | Intervention recommendations + hypothesis statements |

---

## SPARK x WANT x AGAIN x CAN

If any force is zero, the behavior does not happen. The skill diagnoses which is failing first.

| Force | Addresses | Example techniques |
|-------|-----------|-------------------|
| **CAN** | Friction / capability | Smart defaults, chunking, pre-filling, option reduction, explicit next steps |
| **WANT** | Motivation | Social proof, loss framing, progress visibility, identity connection, personalization |
| **SPARK** | Triggers | Contextual timing, event-based prompts, multiple touchpoints, ambient reminders |
| **AGAIN** | Habit formation | Habit stacking, streaks, celebration moments, variable reward, review loops |

Every intervention follows this format:

> *"If [specific design change], then [expected behavior change + metric], because [psychological mechanism]."*

---

## Who It's For

### Product Designers and UX Designers
Diagnosing drop-off in onboarding, activation, and key flows. Designing nudges and friction-reduction changes with a psychological rationale - not just intuition.

- Maps the exact step where users stop and why
- Connects every design recommendation to a specific barrier type
- Produces hypotheses ready to hand off to a PM or researcher

### Design Managers and Design Leads
Running behavioral audits on existing products. Facilitating workshops where the team needs a shared diagnostic language before jumping to solutions.

- Full behavioral audit checklist organized by CAN / WANT / SPARK / AGAIN / Ethics
- Three workshop formats with complete agendas and facilitation notes
- Consistent framework that works across product areas and teams

### Product Managers and Cross-Functional Teams
Understanding the psychology behind why users are not doing the thing the product needs them to do - and translating that into experiment priorities.

- SUE Four Forces diagnosis: Pains, Gains, Anxieties, Comforts
- Intervention prioritization by effort and expected impact
- Hypothesis format that maps directly to A/B test setup

---

## What's Inside

```
behavioral-design/
│
├── SKILL.md                          <- Main skill file (auto-loaded by Claude Code)
│   ├── Mode detection                <- 7 modes: diagnosis, audit, workshop, ethics review...
│   ├── Phase 1: Behavioral Diagnosis <- Behavior definition test, behavioral map structure
│   ├── Phase 2: 3Bs Model            <- 4 barrier types + 3 motivator types
│   ├── Phase 3: Intervention Design  <- SPARK x WANT x AGAIN x CAN + hypothesis format
│   ├── SUE Four Forces               <- Pains / Gains / Anxieties / Comforts
│   ├── Principles quick reference    <- 9 principles in one table
│   └── Ethics check                  <- 4-question inline review
│
├── references/
│   ├── behavioral-diagnosis.md       <- Deep behavioral mapping guide
│   ├── barriers-benefits-model.md    <- 4 barrier types x 3 motivator types in full
│   ├── intervention-techniques.md    <- 20+ named techniques with examples
│   ├── behavior-change-formula.md    <- SPARK x WANT x AGAIN x CAN diagnostic flow
│   ├── sue-influence-framework.md    <- Four Forces framework in detail
│   ├── ethics-checklist.md           <- 5-point ethics checklist + dark patterns guide
│   └── workshop-facilitation.md      <- 3 workshop formats with complete agendas
│
└── assets/
    ├── diagnosis-report-template.md  <- Fillable behavioral diagnosis report
    ├── hypothesis-template.md        <- Experiment hypothesis template
    └── behavioral-audit-template.md  <- CAN / WANT / SPARK / AGAIN / Ethics checklist
```

---

## Example Prompts

**Behavioral diagnosis:**
> "I'm designing a savings feature for a fintech app. Users complete onboarding but only 12% set up a savings goal. Walk me through a diagnosis."

Claude maps the steps between onboarding completion and goal setup, identifies the most likely barrier type, surfaces the missing motivator, and recommends 3 prioritized interventions with hypotheses.

**Feature adoption:**
> "Our collaboration feature has 8% adoption after 6 months. We've tried in-app tooltips. What else should we look at?"

Claude runs a SUE Four Forces analysis, identifies whether this is a CAN, WANT, or SPARK failure, and recommends specific techniques with a test plan.

**Nudge design with ethics:**
> "I want to nudge users to log their meals daily. What technique should I use and how do I know it's ethical?"

Claude recommends implementation intention prompts and habit stacking, explains the psychological mechanism, and runs the full ethics check - user benefit test, transparency test, autonomy test, and manipulation vs. nudge distinction.

**Behavioral audit:**
> "Can you audit our checkout? Users add to cart but 68% abandon before payment. Flow: cart review, email entry, shipping address, payment, confirm."

Claude reviews each step against CAN / WANT / SPARK / AGAIN and Ethics, flags the highest-risk drop-off points, and outputs a prioritized list of interventions with hypotheses.

**Workshop facilitation:**
> "I need a behavioral design workshop agenda for my product team. We're focused on reducing churn in the first 30 days."

Claude returns a complete workshop format with timing, activities, facilitation notes, and outputs for each phase.

---

## Psychological Principles Covered

| Principle | Design application |
|-----------|-------------------|
| Present Bias | Add near-term rewards; connect actions to now |
| Social Norms | Make norms visible: "X% of users like you do this" |
| Loss Aversion | Frame around what users lose by not acting |
| Choice Overload | Reduce options, recommend one path, use smart defaults |
| Implementation Intentions | Ask users to commit to when/where/how |
| Status Quo Bias | Show the cost of inaction; make change the default |
| Hyperbolic Discounting | Connect behavior to near-term consequences |
| Intention-Action Gap | Pre-commitment, reduce activation energy, give a next step |
| Attention Bias | Salience, reminders, contextual triggers |

---

## Ethics Built In

Every output includes a 4-point ethics check:

1. **User benefit test** - Does this serve the user's long-term wellbeing, not just a short-term metric?
2. **Transparency test** - Would users object if they saw exactly what this design is doing and why?
3. **Autonomy test** - Can users still freely choose a different path?
4. **Manipulation vs. nudge** - A nudge makes the desired behavior easier without restricting alternatives. Manipulation exploits vulnerabilities or hides intent.

The skill flags dark patterns and calls out when a proposed intervention crosses the line.

---

## Keywords

behavioral design, behavioral economics, nudge design, behavior change, UX psychology, product psychology, friction reduction, cognitive load, choice architecture, loss aversion, social proof, habit formation, onboarding optimization, feature adoption, engagement design, conversion optimization, design sprint, behavioral audit, intervention design, mental models, design psychology

---

<div align="center">

Built as a [Claude Code](https://claude.ai/claude-code) skill · v1.0.0

</div>
