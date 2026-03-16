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

## Prompt Examples

The most effective way to use this skill is to describe your problem, the data you have, and what you need. Claude handles the rest.

---

### Simple - Single diagnosis or intervention

**Diagnose a drop-off:**
```
Users complete our onboarding but only 12% set up a savings goal
in the first 7 days. What's likely causing this and where do I start?
```
-> Claude identifies the most probable barrier type (attention, cognitive overload, status quo bias, or mental model mismatch), surfaces the missing motivator, and recommends where to focus first.

**Design a nudge:**
```
I want to nudge users to log their meals daily in a health app.
What technique should I use?
```
-> Claude recommends a specific technique (e.g. implementation intention prompt or habit stacking), explains the psychological mechanism, and returns a hypothesis statement ready to test.

**Run an ethics check:**
```
We're planning to use a countdown timer on our upgrade screen
to create urgency. Is this ethical?
```
-> Claude runs the 4-point ethics check - user benefit, transparency, autonomy, and manipulation vs. nudge - and flags if the design crosses the line.

**Explain a principle:**
```
How does loss aversion apply to feature adoption?
Give me a concrete example I can use in my design.
```
-> Claude explains the principle, shows how it appears in real product contexts, and gives a specific, testable design application.

**Write a hypothesis:**
```
I want to test showing users how many people in their city
completed profile setup in their first week.
Write me a hypothesis statement for this experiment.
```
-> Claude returns a formatted hypothesis: "If [change], then [behavior + metric], because [mechanism]" - with measurement plan and ethics note.

---

### Intermediate - Full diagnosis or multi-step work

**Full behavioral diagnosis:**
```
Our collaboration feature has 8% adoption after 6 months.
We've tried in-app tooltips and an email campaign.
Walk me through a full behavioral diagnosis.
```
-> Claude maps the adoption path, applies the SUE Four Forces (Pains, Gains, Anxieties, Comforts), identifies whether this is a CAN, WANT, or SPARK failure, and returns prioritized interventions with hypotheses.

**Behavioral audit of a flow:**
```
Run a behavioral audit on our e-commerce checkout.
Users add to cart but 68% abandon before completing payment.
Here's the flow: (1) Cart review (2) Email entry (3) Shipping address (4) Payment (5) Confirm.
```
-> Claude reviews each step against CAN / WANT / SPARK / AGAIN and Ethics, rates each for psychological effectiveness, flags the highest-risk drop-off points, and returns a prioritized intervention list.

**Onboarding redesign:**
```
We're redesigning our onboarding for a B2B SaaS tool.
The goal is to get users to connect their first integration
before their second session. Where do we start?
```
-> Claude defines the precise target behavior, maps the activation path, identifies barriers by type, and produces a prioritized set of interventions with hypothesis statements and a measurement plan.

**Workshop agenda:**
```
I need to run a behavioral design workshop with my product team next week.
We're focused on reducing churn in the first 30 days.
Give me a full agenda with facilitation notes.
```
-> Claude returns a complete workshop format - session goal, timing, activities, facilitation instructions per phase, outputs, and what to do if the team gets stuck.

**Intervention prioritization:**
```
Here are 6 interventions we're considering for our activation flow.
Which should we test first and why?
[paste list]
```
-> Claude evaluates each against effort, expected impact, and the SPARK x WANT x AGAIN x CAN model, then returns a ranked priority order with rationale.

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
