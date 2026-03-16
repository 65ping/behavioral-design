# Barriers and Benefits Model (3Bs) - Deep Guide

The 3Bs model diagnoses behavioral problems at the level of psychology, not interface. It prevents the most common design mistake: redesigning the surface when the real problem is the user's mental state.

---

## The 4 Barrier Types

### 1. Attention Barriers

The user doesn't see, notice, or remember that the behavior opportunity exists.

**Sub-types:**
- **Memory failure** - User intended to act but forgot. Intention doesn't create automatic reminders.
- **Salience failure** - The prompt exists but doesn't register. It's visually present but not psychologically present.
- **Information avoidance** - User actively ignores the prompt because engaging triggers anxiety or requires effort they'd rather defer.

**Diagnostic signals:** Feature exists but rarely accessed; low notification open rates; user expresses surprise something was available; high impressions, near-zero engagement.

**Diagnostic questions:**
- Does the user know this feature or action exists?
- Is the trigger visible at the moment the user would benefit from it?
- Does the user avoid this because confronting it is uncomfortable?

---

### 2. Cognitive Overload

The decision or action requires more mental effort than the user will expend at that moment.

**Sub-types:**
- **Decision complexity** - Too many options, unclear trade-offs, hard to compare alternatives
- **Choice paralysis** - Options feel equal in value; user can't determine which is right
- **High effort** - Too many steps, fields, or pieces of information required
- **Unfamiliar format** - User encounters a pattern they don't recognize and must figure out how it works

**Diagnostic signals:** Long time-on-page at decision points; high rates of starting but not completing; abandonment on multi-step forms; user leaves to "think about it" and doesn't return.

**Diagnostic questions:**
- How many decisions must the user make on this screen?
- Is there a recommended or default option?
- Is the user being asked for information they don't have ready access to?
- Is each option clearly differentiated, or do they blur together?

---

### 3. Status Quo Bias

The user prefers doing nothing or staying with their current behavior, even when changing would benefit them.

**Sub-types:**
- **Opportunity cost neglect** - User doesn't register what they're missing by not acting
- **Loss aversion** - The cost of switching feels more salient than the benefit of changing
- **Inertia** - No strong reason to change; existing behavior requires no activation energy

**Diagnostic signals:** Low adoption of optional but genuinely beneficial features; users return to old workflows after onboarding to new ones; high activation, low sustained engagement.

**Diagnostic questions:**
- What is the user currently doing instead?
- What would they have to give up or risk to make the change?
- Is the cost of staying the same visible?
- Does the current behavior have emotional or identity attachment?

---

### 4. Mental Model Mismatch

The user's internal understanding of how the product works doesn't match the actual design.

**Sub-types:**
- **Category error** - User believes the product does something fundamentally different than it does
- **Workflow mismatch** - User expects steps in a different order than the actual flow
- **Label confusion** - Terminology means something different to the user than to the team
- **Conceptual gap** - User lacks background knowledge needed to understand how this works

**Diagnostic signals:** High support volume for "how does X work?" questions; users navigating to wrong sections; unexpected usage patterns in analytics; high bounce after viewing a specific screen.

**Diagnostic questions:**
- Can users explain what this feature does in their own words (correctly)?
- Do they expect a different sequence of steps?
- Do key labels mean something different to users than to the team?

---

## The 3 Motivator Types

Every behavior requires not just the absence of barriers, but the presence of motivation.

### Emotional/Hedonic
Immediate pleasure, enjoyment, comfort, or relief. The now-reward.
- Aesthetic delight, playful interactions, satisfying feedback, relief from anxiety
- Strongest at the moment of action; hardest to sustain over time

### Functional
Future outcomes, practical value, efficiency gains. The rational case.
- Progress toward a meaningful goal, time saved, money saved, skill gained
- Strongest in goal-oriented users; weakest when the future feels distant or uncertain

### Psychological
Social belonging, identity expression, reputation, altruism, meaning.
- Social norms, social proof, status signaling, group membership, contribution to something larger
- Often more powerful than functional motivation; harder to make visible

---

## Mapping Barriers to Motivators

| Barrier | Most effective motivator counter |
|---------|--------------------------------|
| Attention | Emotional/hedonic - make the trigger feel rewarding to engage with |
| Cognitive Overload | Functional - show the effort is worth it; also reduce the effort |
| Status Quo Bias | Loss framing (functional via loss aversion) + psychological (social norms, identity) |
| Mental Model | Functional clarity - show how it actually works and why that serves them |

---

## Worked Example

**Scenario:** Project management app sees 70% drop-off when users try to set up automations.

**Barrier diagnosis:**
- Step 1 (choose trigger): Long time-on-page, high exit → **Cognitive overload** (12 trigger types, no recommendation)
- Step 2 (configure action): High abandonment after starting → **Mental model mismatch** ("Action" means different things to different users)
- Overall: Low adoption even among users who reach the end → **Status quo bias** (manual process has low switching cost)

**Motivator gaps:**
- No visible functional benefit at the moment of configuration
- No social norm ("do other teams use automations?")
- No emotional reward for completing setup

**Interventions:**
- CAN: Reduce trigger options; add "recommended for your use case" guidance
- WANT: Show projected time saved before starting; adoption rates from similar teams
- AGAIN: Celebrate first automation run with visible impact ("You just saved 2 hours")
