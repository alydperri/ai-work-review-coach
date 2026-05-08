# Reference: Product-Mindset Principles for AI Work

These principles inform how the specialist reviews AI-enabled work with managers. They are drawn from established thinking on AI product development, including work by practitioners who have shipped AI systems at scale.

The six evaluation areas are listed below. Each includes diagnostic questions, red flag signals, and a manager judgment move to help the manager build skill over time.

---

## 1. Problem Clarity

The most common failure mode in AI work is leading with capability: *"We could use AI to..."* rather than *"We have this problem, and here's how we're solving it."*

Good AI work starts with a real, specific, observable problem. The technology choice follows from the problem definition — not the other way around.

**Diagnostic questions:**
- Is there a specific, real problem being solved — or is the team chasing a capability?
- Who experiences this problem, and how do they experience it today?
- Would solving this problem actually change something meaningful?

**Red flag signals:**
- The pitch leads with what the AI can do, not what problem it solves
- The "problem" is vague ("improve efficiency," "save time") without evidence it exists or matters
- The team can't articulate what's broken today without describing the solution

**Manager judgment move:**
Help the manager distinguish between a weak idea and a weakly framed idea. A team may have found a real problem but explained it poorly. The manager's job is to push for clearer problem definition before judging the solution.

---

## 2. Success Definition

AI systems are hard to evaluate after the fact if you haven't defined what good looks like in advance. Teams that skip this step end up defending their work with engagement metrics ("people are using it") instead of impact metrics ("it changed an outcome").

Success definitions should be specific and measurable, tied to user behavior or business outcomes — not just usage — and agreed on before build begins, not invented after launch.

**Diagnostic questions:**
- How will the team know it's working?
- Are there concrete metrics, or just vibes and positive reactions?
- Is success defined by user behavior, workflow quality, decision quality, or business impact — not just usage?

**Red flag signals:**
- No metrics defined, or metrics that only measure adoption, logins, clicks, or volume
- "We'll know it's working when people like it"
- Success is defined by the builder, not the people who will use or rely on the workflow

**Manager judgment move:**
Teach the manager to separate interest signal from impact signal. Usage, enthusiasm, and positive feedback can mean the problem is real, but they do not prove the AI work improved the workflow.

---

## 3. Agency and Control

AI systems should start with high human control and low autonomy, then earn more agency as they prove themselves. Teams that jump to full automation before testing low-stakes versions create systems that are hard to debug, hard to trust, and hard to recover from when something goes wrong.

**Version ladder thinking:**
- v1: System suggests or assists, human decides
- v2: System acts, human reviews before it reaches users or downstream systems
- v3: System acts autonomously, with monitoring, fallback, and clear accountability

**Diagnostic questions:**
- How much autonomy does this system have, and is that appropriate for its stage and risk level?
- What happens when it gets something wrong?
- Is there a way for humans to catch errors, intervene, and take back control?

**Red flag signals:**
- v1 is fully autonomous with no human review step
- No one has asked what a bad output looks like or how it would be caught
- The plan is to launch broadly before testing with a small group

**Manager judgment move:**
Help the manager see autonomy as something a system earns, not something a team gets by default. A promising experiment can still be too autonomous for its current evidence level.

---

## 4. Lifecycle Thinking

Two questions separate mature AI thinking from shiny-object thinking: *"What happens when it gets something wrong?"* and *"Who maintains this when you're gone?"*

Every AI system will produce bad outputs at some point. Good AI work includes a maintenance plan: who updates it, how often, and under what conditions it gets reviewed or sunset.

**Diagnostic questions:**
- Who maintains this when the person who built it moves on?
- What happens when the underlying model, data, policy, or workflow changes?
- Under what conditions would this be revised, paused, or sunsetted?

**Red flag signals:**
- No fallback when the system fails or produces low-confidence output
- The tool was built by one person with no documentation or transfer plan
- No one has asked when this would be turned off

**Manager judgment move:**
Teach the manager to evaluate the full life of the work, not just the launch. A demo can look strong while the future operating model is fragile.

---

## 5. Fit and Proportionality

Not every problem needs a sophisticated AI solution. One of the most important evaluative questions is whether the complexity of the proposed solution is proportionate to the complexity of the problem.

A rule of thumb: if a well-designed checklist, structured template, rule, dashboard, or simple automation would solve most of the problem, the AI layer needs to earn its place.

**Diagnostic questions:**
- Is AI actually the right tool here, or is this a simpler problem dressed up as an AI problem?
- Is the complexity of the solution proportionate to the complexity, frequency, and value of the problem?
- Did the team seriously consider a simpler non-AI approach?

**Red flag signals:**
- The solution involves multiple AI components when one simple workflow change would do
- The team is more excited about the technology stack than the outcome
- A simpler non-AI solution was never seriously considered

**Manager judgment move:**
Teach the manager to ask whether the AI layer has earned its complexity. A real problem does not automatically justify an AI solution.

---

## 6. AI-Native vs. Bolt-On

There's a meaningful difference between tools designed from the ground up around what AI makes possible, and tools that paste an AI layer onto an existing process. Bolt-ons often underperform because the underlying process wasn't designed for AI behavior — especially the non-determinism and variability that comes with it.

The best AI work often requires rethinking the process, not just automating it.

**Diagnostic questions:**
- Did the team redesign the workflow, or just add AI to the existing one?
- Does this work better because of AI, or just with AI?
- Where does human judgment belong in the redesigned workflow?

**Red flag signals:**
- AI is added at the end of a broken process without changing the process itself
- The workflow assumes deterministic behavior from a non-deterministic system
- Human review is bolted on vaguely rather than designed into the workflow

**Manager judgment move:**
Help the manager distinguish between automation thinking and workflow redesign. The question is not simply "Can AI do this?" The stronger question is "What should this workflow become now that AI is available?"

---

## Sources and Further Reading

These principles are informed by:

- *Why Your AI Product Needs a Different Development Lifecycle* — Aishwarya Reganti and Kiriti Badam, Lenny's Newsletter (Aug 2025). Introduces the CC/CD framework and the agency-control tradeoff.
- *Counterintuitive Advice for Building AI Products* — Lenny Rachitsky and Kyle Poyar, Lenny's Newsletter. Lessons from 20+ builders on what actually matters.
- *Building AI Product Sense* — Marily Nika, Lenny's Newsletter (2026). On the difference between confident hallucination and humble, reliable AI behavior.
