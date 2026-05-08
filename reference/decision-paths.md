# Reference: Paths To Consider

Use these paths when helping the manager reason through what to do next.

The path should match the work's stage, evidence level, risk profile, and organizational environment. Do not choose a path just because the team is enthusiastic or the demo was impressive.

Frame each path as a recommendation based on current evidence, not as the specialist's final decision.

Useful phrasing:
- "A reasonable path to consider is..."
- "Based on the current evidence, I would treat this as..."
- "Before making the final call, I would want to know..."
- "This read would change if..."

Avoid final-authority phrasing:
- "You should..."
- "This is the right decision."
- "This will/won't work."

## Treat As Lightweight Experiment

Use when:
- the problem appears real enough to test
- the risk is low
- the scope is contained
- the team has a clear learning goal
- the work is not being treated as production-ready

Manager language:

> "This looks worth testing, but I would keep it clearly in experiment mode until we know whether it improves the workflow. Before building further, let's define what we expect to learn and how we will know whether it worked."

What would change this read:
- the problem turns out to be rare or low-value
- the workflow touches higher-risk decisions than initially described
- the team cannot define what they expect to learn

## Move Forward With Constraints

Use when:
- the idea is promising
- the team has enough problem clarity to proceed
- some important risks still need guardrails
- the next step should be bounded rather than open-ended

Possible constraints:
- small pilot group
- human review before outputs reach users
- limited autonomy
- defined success metrics
- named owner
- time-boxed experiment
- clear rollback or fallback path

Manager language:

> "This could move forward as a bounded pilot, not a broad rollout. The constraints are part of the path, not optional cleanup later."

What would change this read:
- the team resists constraints
- the workflow requires more autonomy than the evidence supports
- quality risk is higher than expected

## Redirect To Simpler Solution

Use when:
- the problem is real
- AI is probably more complex than the problem requires
- a checklist, template, rule, dashboard, FAQ, or simple automation may solve most of it
- the team has not seriously considered non-AI alternatives

Manager language:

> "I agree the problem is real. I am not yet convinced this needs an AI solution. Before we build this, let's compare it to the simplest version that could solve most of the problem."

What would change this read:
- the team shows that the work requires judgment across ambiguous or unstructured information
- simpler alternatives have already failed or do not address the actual workflow problem

## Pause Until Baseline Evidence Exists

Use when:
- the problem is plausible but unmeasured
- the team cannot quantify frequency, severity, or impact
- success would be impossible to evaluate later
- the manager does not have enough evidence to make a confident call

Manager language:

> "I do not want to say no to the idea, but I also do not want us building on top of assumptions. Let's get baseline evidence first so we know whether this is worth solving and how we would measure improvement."

What would change this read:
- the team provides baseline evidence showing the problem is frequent, costly, risky, or strategically important
- the team can define success before build begins

## Do Not Scale Yet

Use when:
- an experiment has positive signal
- people like it or use it
- but impact, reliability, ownership, quality standards, or failure handling have not been validated

Manager language:

> "This looks like a promising experiment. I do not think it has earned standard-workflow status yet. The next step is validation, not expansion."

What would change this read:
- quality testing shows the workflow is reliable enough for broader use
- ownership and maintenance are clearly defined
- there is evidence of improved outcomes, not just usage or enthusiasm

## Controlled Expansion

Use when:
- there is some evidence of value
- the team has addressed major risks
- broader rollout may be reasonable
- but the work still needs monitoring and constraints

Possible controls:
- staged rollout
- explicit review checkpoints
- quality sampling
- usage and outcome metrics
- named operational owner
- documented escalation path

Manager language:

> "I am open to expanding this, but only in stages. Each stage needs evidence that the workflow is improving outcomes without creating avoidable risk."

What would change this read:
- early expansion reveals quality problems
- support or maintenance burden is higher than expected
- user behavior does not change in the way the team expected

## Escalate For Specialist Review

Use when:
- the work touches sensitive data, customers, legal commitments, regulated processes, employment decisions, financial decisions, security, or high-stakes user outcomes
- the manager is being asked to approve something outside their expertise
- the proposal needs technical, legal, security, compliance, or executive review

Manager language:

> "This is outside the review I can responsibly complete on my own. I can evaluate the product thinking, but this also needs specialist review before we move forward."

What would change this read:
- specialist review clarifies that the risk is lower than expected
- the team redesigns the workflow to avoid the high-risk area

## Split Into Separate Problems

Use when:
- the proposal bundles multiple problems together
- one part may be worth testing while another is too risky, vague, or complex
- the team is trying to solve a system-level issue with one AI tool

Manager language:

> "I think we are treating several different problems as one project. Let's separate them so we can evaluate each one on its own merits."

What would change this read:
- the team narrows the proposal to one concrete workflow
- the team can explain which part of the problem AI is uniquely suited to help with

## Sunset Or Retire

Use when:
- the tool no longer solves a meaningful problem
- better alternatives now exist
- maintenance cost outweighs value
- quality is not reliable enough
- ownership has disappeared
- the system creates confusion, duplication, or risk

Manager language:

> "This was useful as an experiment, but I do not think it should continue as an operational workflow. We should capture what we learned and retire it deliberately."

What would change this read:
- a clear owner emerges
- evidence shows the tool still improves an important workflow
- maintenance burden can be reduced without increasing risk
