# AI Work Review Coach

Drop this folder into a Claude Project.

This specialist helps managers build better judgment when reviewing AI-enabled work on their teams — proposals, experiments, and scaling requests. It evaluates the quality of thinking behind the work, not the code. It does not review architecture, model selection, security, or legal compliance.

---

## How To Use It

Paste or upload whatever you're evaluating — a proposal, workflow description, demo notes, rollout request, GPT instructions, meeting notes, or pitch deck. The more concrete the input, the more specific the review.

Then ask:

> "Help me evaluate this."

Or be more specific:

> "My team wants to build X. Is this worth pursuing?"
> "Someone built this and wants to expand it. Has it earned that next step?"
> "I think the demo is impressive but the thinking is weak. Help me review it."

---

## What You Get Back

The specialist will first confirm what it understands and ask if there's anything else to include before the assessment. Then it gives an initial read — stage, evidence level, primary risk — followed by a full evaluation: what's working, red flags, the decision risk, coaching questions for the team, a path to consider, and suggested next step.

The goal is not a verdict. It's a structured read that helps you make a better call and develop your team's judgment over time.

---

## Folder Contents

```
ai-work-review-coach/
├── identity.md          # Who the specialist is and what it evaluates
├── rules.md             # How it responds and structures output
├── examples.md          # The specialist in action
├── README.md            # This file
└── reference/
    ├── principles.md    # Six evaluation areas for AI work
    ├── decision-paths.md # Paths the specialist may recommend
    ├── coaching.md      # Frameworks for feedback conversations
    └── environment.md   # Organizational calibration
```

---

## Calibrating The Specialist To Your Environment

The specialist's organizational assumptions live in `reference/environment.md`.

The default version is calibrated for an AI-first scaling environment: lots of experimentation, uneven product thinking, and increasing pressure to operationalize AI work.

If your organization operates differently, update only `reference/environment.md` with:
- your organization's AI maturity
- current goals and pressures
- cultural norms around experimentation
- governance expectations
- risk tolerance
- recurring patterns you see in proposals

This keeps the specialist modular: `identity.md` defines the expert, while `environment.md` defines the environment that expert is operating in.

---