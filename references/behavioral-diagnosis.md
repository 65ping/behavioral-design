# Behavioral Diagnosis - Deep Guide

## The Behavior Definition Test

A behavior must pass all three tests before diagnosis begins:

| Test | Question | Fail example | Pass example |
|------|----------|-------------|-------------|
| Observable | Can you watch someone do it and confirm it happened? | "Engage with the app" | "Opens push notification and completes one action" |
| Measurable | Can your analytics track it? | "Feel more confident" | "Submits first transaction within 14 days" |
| Specific | Is it one action, not a cluster? | "Complete onboarding" | "Connects first data source on the integrations screen" |

If the behavior fails any test, rewrite it before proceeding.

---

## Building the Behavioral Map

The behavioral map is a step-by-step trace of everything a user must do, know, and feel to complete the target behavior. It's the foundation of good diagnosis - you can't find barriers you haven't mapped.

### What to Capture at Each Step

| Field | What to capture |
|-------|----------------|
| Step name | Short label for the action |
| User action | What the user must physically do |
| Information needed | What the user must know to act correctly |
| Decision type | Binary, multi-option, open-ended? How many options? |
| Likely emotional state | Curious? Anxious? Impatient? Confused? |
| Environmental context | Device, location, time pressure, distractions? |
| Known drop-off % | From analytics, if available |
| Friction sources | What makes this step hard? (cognitive, physical, emotional) |

### Common Friction Sources

**Cognitive friction**
- Too many options with no guidance
- Terminology the user doesn't recognize
- Information they don't have ready access to
- Steps that require the user to remember something from earlier
- Unclear what happens after they act

**Physical friction**
- Too many taps/clicks to complete
- Small touch targets on mobile
- Required information not copy-pasteable
- Switching between apps or tabs to gather information

**Emotional friction**
- High-stakes decisions (feels permanent, expensive, or hard to undo)
- Requests for sensitive information before trust is established
- Social visibility of an action the user wants to keep private
- Uncertainty about whether they're doing the right thing

---

## Context Factors That Shape Behavior

Behavior is always situated. The same design produces different behaviors in different contexts.

**Timing** - Is the user encountering this at the right moment in their task, day, or product lifecycle? Is this the first session or the fifth? Just after a success or a failure?

**Environment** - Mobile vs. desktop changes attention span, available time, and input method. At home vs. at work affects risk tolerance and social context.

**Prior experience** - First-time users bring assumptions from analogous products. Returning users who abandoned once bring skepticism.

**Social context** - Is the action visible to others? Does that help or hurt? Are they influenced by what they believe their peers do?

**Stakes** - High-consequence decisions (financial, health, public/permanent) trigger more anxiety, more deliberation, more avoidance.

---

## Using Data in Diagnosis

Data tells you *where* behavior breaks down. Qualitative research tells you *why*.

| Signal | What it may indicate |
|--------|---------------------|
| High drop-off at a specific step | Barrier at that exact step |
| Long time-on-page at a decision point | Cognitive overload or anxiety |
| Very short time-on-page | Skipping or dismissing without reading |
| High return rate to a step | Confusion; user backing up to recheck |
| High entry, near-zero completion | Early motivation but late barrier |
| Segment A completes, Segment B doesn't | Context or mental model difference |
| Feature exists but almost never accessed | Attention barrier |

### Qualitative research questions

- "Walk me through the last time you tried to do [X]."
- "What were you thinking when you got to [the problematic step]?"
- "Was there a moment when you considered stopping? What happened?"
- "What would you have needed to feel more confident continuing?"
- "What did you expect would happen when you clicked [Y]?"

Avoid asking: "Why did you stop?" - users construct post-hoc reasons that often don't reflect the actual barrier.

---

## Prioritizing Drop-Off Points

1. **Volume** - Where is the most behavioral loss? (highest absolute drop-off)
2. **Leverage** - Is this step required for the target behavior? (bottleneck steps matter more)
3. **Evidence quality** - Do you have enough signal to diagnose confidently?
4. **Ease of intervention** - Can a design change plausibly fix this?

Start with the highest-volume, highest-leverage drop-off where you have strong diagnostic evidence.
