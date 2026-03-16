# Intervention Techniques Library

20+ techniques organized by the SPARK × WANT × AGAIN × CAN formula. For each technique: what it does, why it works, and a design example.

---

## CAN: Reducing Friction (Capability)

Techniques that make the behavior physically and cognitively easier.

### Option Reduction
Remove choices that aren't necessary. Present fewer paths. If there are three tiers, recommend one. Less is almost always more when users are under cognitive load.
- *Example: Instead of showing 8 notification settings, group into "Essentials" and "All" with Essentials pre-selected.*

### Smart Defaults
Pre-select the option most users benefit from. Users who want to change can - but most won't need to. Defaults have outsized influence on outcomes.
- *Example: Pre-set privacy to "Team only" rather than "Public" for new documents.*

### Pre-filling
Populate forms with information you already have. Never ask for the same thing twice. Each re-entry is a friction tax.
- *Example: Pre-fill billing address from shipping address; pre-fill company name from onboarding.*

### Chunking
Break a complex behavior into smaller, named stages. "Step 2 of 4" is less daunting than an unmarked long form. Progress bars signal that an end exists.
- *Example: Split a 12-field account setup into three 4-field steps: "Your profile," "Your team," "Your preferences."*

### Specificity
Replace vague prompts with specific instructions. Vague prompts create decision moments where there shouldn't be any.
- *Vague: "Add a photo." Specific: "Add a photo from the last 6 months, at least 400×400 pixels."*

### Explicit Next Steps
Always make the next action obvious. Remove ambiguity about what to do after completing a step. Never leave users on a success screen with nowhere to go.
- *Example: After form submission, show "Your account is ready - here's what to do first: [primary CTA]."*

### Strategic Deadlines
Add genuine time constraints where appropriate. Deadlines reduce deferral. Must feel real to be effective - fake urgency backfires and erodes trust.
- *Example: "Your team invitation expires in 48 hours" on a real 48-hour expiry.*

### Strategic Pauses
Introduce a decision point before a high-stakes or irreversible action. Gives users agency and reduces post-action regret.
- *Example: "Before you archive all 340 items - are you sure? This can't be undone." with a count-based friction.*

---

## WANT: Increasing Motivation

Techniques that make the behavior more appealing or more necessary.

### Social Proof - Descriptive Norm
Show what similar users actually do: "78% of new users complete this step in their first session."
- Reduces uncertainty by showing the behavior is normal and expected.

### Social Proof - Injunctive Norm
Show what's considered the right thing to do: "Most teams in your industry have this enabled."
- Activates a sense of social expectation, not just description of behavior.

### Identity Framing
Connect the behavior to the user's self-concept: "As a design lead, you'll want your team's workspace fully configured."
- Identity-consistent behavior requires less willpower and feels more automatic.

### Personalization
Make the benefit feel specifically relevant: "Based on your usage, you'd save about 3 hours/week with this feature."
- Generic benefits are easy to discount; personal relevance makes them feel real.

### Loss Aversion Framing
Reframe from gain to loss: Instead of "Get 20% more storage," use "You're using 80% of your storage - protect your work."
- People are roughly 2× more motivated to avoid losses than to acquire equivalent gains.

### Progress Visibility
Show how far the user has come, not just how far to go. Progress bars, completion percentages, milestone markers.
- Activates the goal gradient effect - people accelerate as they approach a finish line.

### Goal Gradient Effect
Make visible that the user is close to a milestone. Proximity to a goal naturally increases effort.
- *Example: "You're 1 step away from completing your profile" triggers more action than "You're 80% done."*

### Anchoring
Introduce a reference point that makes the desired option seem more reasonable. What gets shown first shapes how everything else is evaluated.
- *Example: Show the "Team" plan before "Individual" - the first seen becomes the reference point.*

### Priming
Expose users to concepts or emotions before a decision that make the desired behavior more salient.
- *Example: Show a quote from a power user before the feature upgrade prompt.*

### Meaning Addition
Give numbers and actions context. Abstract values feel abstract; concrete comparisons feel real.
- *"14 kg CO2 offset" → "The equivalent of planting 14 trees"*
- *"3 hours saved this week" → "That's an extra afternoon with your team every month"*

### Implementation Intention Prompt
Ask users to specify when and how they'll complete the behavior: "When do you plan to set your weekly goal?"
- Specifying a plan (time, place, how) dramatically increases follow-through vs. general intention.

---

## SPARK: Triggers

Techniques that prompt action at the right moment.

### Contextual Timing
Trigger prompts when users are most receptive - immediately after a successful action, not in the middle of a task.
- *Example: Ask for profile completion right after a user's first successful search, not during onboarding.*

### Multiple Touchpoints
Don't rely on a single exposure. Build a sequence of prompts across channels and moments.
- Behavior change rarely happens on first contact. Plan a sequence: in-app → email → in-app reminder.

### Ambient Reminders
Make the desired behavior visible in the user's environment without demanding immediate action.
- *Example: A persistent but non-blocking "Your setup is 70% complete" banner in the sidebar.*

### Event-Based Triggers
Connect prompts to meaningful user events: first login, milestone completion, approaching a limit, returning after absence.
- *Example: "Welcome back - you have 3 items waiting for your review" on a user who hasn't logged in for 7 days.*

---

## AGAIN: Repetition and Habit

Techniques that turn one-time behaviors into lasting habits.

### Habit Stacking
Connect the new behavior to an existing routine: "After you check your notifications, review your team's progress."
- Piggybacking on existing habits lowers the activation energy for new ones.

### Variable Reward
Introduce unpredictability in reinforcement. Consistent rewards become expected; variable rewards sustain engagement longer.
- *Example: Occasional "🎉 You just hit a new personal best!" mixed with standard confirmations.*

### Celebration Moments
Mark completion with positive feedback: animations, congratulations, visible progress acknowledgment.
- Celebration makes the behavior feel worth repeating and creates a positive emotional association.

### Streak Mechanics
Make visible the accumulation of repeated behaviors. Streaks create loss aversion around breaking the chain.
- Users work to protect a streak - the accumulated investment becomes a motivator.

### Reinforcement Timing
Deliver positive feedback immediately after the behavior, not at a delay. Delayed rewards are heavily discounted.
- *Example: Instant "✅ Saved" confirmation feels more rewarding than "Your changes will appear in 30 minutes."*

### Review Loops
Give users periodic visibility into their progress over time - weekly summaries, monthly reports, year-in-review.
- Reflection sustains long-term engagement and makes invisible progress visible.

---

## Selection Guide

| Barrier type | High-priority techniques |
|-------------|------------------------|
| Attention | Event-based triggers, contextual timing, ambient reminders, salience enhancements |
| Cognitive Overload | Option reduction, chunking, smart defaults, pre-filling, specificity |
| Status Quo Bias | Loss aversion framing, social proof, implementation intentions, cost-of-inaction visibility |
| Mental Model | Specificity, explicit next steps, in-context explanation, progressive disclosure |
| Habit missing (AGAIN) | Habit stacking, celebration moments, streaks, review loops, reinforcement timing |
