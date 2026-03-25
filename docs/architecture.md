# Architecture

## Overview

Penmark is a Next.js application.

## NEW SECTION ADDED VIA PENMARK

This was added by the E2E test.

## Components

The editor is built on Tiptap.

- Hello
- Really
- Neat-o
- I love this.

Execution at Speed

## The Problem

Execution that works at small scale breaks at larger scale. This has always been true — but AI has changed *what* breaks and *when*.

In the old world, the bottleneck was delivery capacity. Teams couldn't build fast enough. The execution challenge was: can we reliably ship what we promised, on time?

In the AI-accelerated world, delivery capacity is less often the constraint. Teams can build almost anything in weeks. The execution challenge has shifted: **are we building the right things, making good decisions fast, and keeping each other informed as we move?**

Speed amplifies everything. Good prioritization compounds faster. Bad prioritization wastes more. A dead-end pursued for two weeks is recoverable; a dead-end pursued for two months because nobody raised the flag is not.

## The Cultural Virtue

**"We make big bets deliberately and move fast."**

This means:

- We aim high — safe, incremental work is the real risk when you can build anything in a month

- We choose what to work on with intention, not inertia

- We size our bets based on expected impact, not habit or comfort

- We move quickly, but we know when to slow down

- We read signals early and act on them — doubling down or killing without hesitation

- We keep each other in the loop, especially when plans change

## Three Skills

To live this virtue, teams need three skills:

### 1. Prioritize Ruthlessly

The most important skill in an AI-accelerated org. When you can build almost anything in a month, the cost of building the wrong thing is enormous. Every week spent on a P2 while a P1 exists is a week of compounding waste.

This skill has three components:

**Bet Selection** — choosing *what* to work on:

- Knowing what matters most to the business, the product, and the user — not just what's interesting or comfortable

- Saying no to good ideas in favor of great ones

- Dropping lower-priority work eagerly when higher-priority work demands it — not finishing something just because you started it

- Having the ambition to take on the big, high-leverage bet rather than the safe, incremental one

**Impact Estimation** — sizing *how much* it matters:

- Estimating expected impact: how much upside, how confident are we?

- Assessing the cost to find out — a high-upside, low-confidence bet is worth taking if you can learn cheaply

- Calibrating over time — comparing what you *predicted* would matter vs. what *actually* mattered, and getting better at it

- Understanding second-order effects: what does this unlock if it works? What does it block if it doesn't?

**Investment Calibration** — knowing the right level of commitment:

- Distinguishing between bets and experiments. A bet is a meaningful commitment of resources — you're choosing this *over* something else. An experiment is cheap, fast, and disposable — the goal is to generate signal, not to ship.

- Defaulting to experiments when uncertainty is high. Instead of "should we bet on A or B?" ask "can we try A, B, and C this week and bet on whichever shows the strongest signal?"

- Not over-investing in experiments — a prototype that took a month was actually a bet you didn't plan for

- Not under-investing in bets — once you have signal and commit, go all in

- Knowing when an experiment has generated enough signal to become a bet, or to be killed

**How it's taught:** Monthly planning forces teams to propose and defend their bets — "why this, why not that, how did you size it, what's the expected impact? Could you have validated this cheaper first?" Monthly review closes the loop — "did your impact thesis hold up? Did this matter as much as you thought? Should this have been an experiment before it was a bet?" Over 12 cycles per year, calibration improves fast.

### 2. Make Good Calls Fast 

The speed of an organization is determined by its decision-making speed. In an AI-accelerated org, the work between decisions is compressed — which means decisions become the bottleneck.

This skill means:

- Defining what success looks like *before* starting — not after, when it's easy to rationalize

- Reading signals early: instrumenting, measuring, paying attention to what the data is telling you

- Making the call to kill or double down when the signal is clear — not waiting for more data to confirm what you already know

- Distinguishing reversible from irreversible decisions — moving fast on the former, being deliberate on the latter

**How it's taught:** Weekly execution review. The leader asks: "What signal are you seeing? What does it tell you? What's your call?" When teams bring ambiguous data and no recommendation, the leader coaches them toward a decision in real time. When teams kill a bet cleanly based on signal, it's celebrated. Over time, teams internalize that fast, honest calls are valued more than clinging to a plan.

### 3. Keep Everyone in the Loop

Speed without communication is chaos. The faster teams move, the more important it is that pivots, blockers, and decisions are broadcast proactively. In a slow-moving org, you can rely on scheduled meetings to propagate information. In a fast-moving org, a decision made Monday that isn't communicated until Friday's standup has already caused downstream damage.

This skill means:

- Broadcasting pivots and decisions immediately, not waiting to be asked

- Raising blockers within hours, not days — there is no "let me try one more thing first" at this speed

- Telling the teams that depend on you when something changes, before they find out the hard way

- Asking for help early — this is a strength, not a weakness

**How it's taught:** Weekly execution review is the communication ritual. The leader asks: "Who else needs to know? Did you tell the team that depends on this? When did you raise this?" Failures in communication are surfaced in real time. The review also serves as the escalation forum — a safe, structured place to raise issues that need leadership support.

## Five Rituals

### 1. Quarterly Business Review

Monthly rituals handle tactics. Quarterly handles high level strategy.

- Where do we want to be in 3 months? Discuss and review 3 high level measurable outcomes for the team. Example for Product:

1. 20+ enterprise companies are successfully onboarded and using the product

2. 50k+ DAU

3. Team velocity 2x from start of quarter

- Roll up 3 months of bets and outcomes into a narrative for the board and stakeholders

- Review quarterly objectives: are they still the right direction?

- Set or adjust objectives for the next quarter

- Identify company-level bets that need cross-functional coordination

The quarterly cadence exists for stakeholder alignment and strategic direction. The monthly cadence is where the real work is managed.

**Template Quarterly:** 

[<u>https://docs.google.com/document/d/1OuUEUGfzuXuQfnWd_j62cp8q4YM7QojiscOAMjf927U/edit?tab=t.0#heading=h.gexf75tvkpnf</u>](https://docs.google.com/document/d/1OuUEUGfzuXuQfnWd_j62cp8q4YM7QojiscOAMjf927U/edit?tab=t.0#heading=h.gexf75tvkpnf)

### 2. Monthly Planning (last 2-3 days of each month)

**Intent:** Each team makes deliberate bets for the coming month, informed by strategy, data, and what they just learned.

How it works:

Each team proposes 2-4 goals with priorities (P1/P2/P3)

- **P1** This is our highest-conviction bet. We're going all in.

- **P2** Important and we want to get here. Will drop for P1 if needed.

- **P3** Stretch. We'll get here if everything goes well.

Each goal has:

- A clear definition of done — unambiguous, no room for goalpost movement

- An impact thesis — why this matters, how we sized it

- Success criteria — what signals will tell us it's working (or not)

- Known risks and dependencies

Not everything lands on month boundaries. Goals can span months — what matters is that each month has clear milestones and that progress is unambiguous. A multi-month effort should have a monthly deliverable that demonstrates meaningful progress, not just "still working on it."

Planning should take hours, not days. Teams already know the quarterly direction; they're scoping the next month's slice.

Goals are shared across all teams for full transparency.

**What the leader looks for:**

- Is the team focused on the highest-leverage work, or playing it safe?

- Can they articulate *why* this bet over alternatives?

- Are success criteria defined up front, or vague?

- Are dependencies identified and confirmed with the other team?

**Template for Monthly:** 

1. Quarterly Objectives (to know what team is driving towards): 

   1. 20+ enterprise companies are successfully onboarded and using the product

   2. 50k+ DAU

   3. Team velocity 2x from start of quarter

2. Monthly Goals to get to towards the Quarterly Objectives: 

- Goal #1: \[5 enterprise companies are successfully onboarded and using the product\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

- Goal #2: \[20K DAU\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

- Goal #3: \[Team velocity at 1.3x vs today\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

  - Bet on … \[P1 / P2 / P3\]

### 3. Weekly Execution Review (first day of new month, combined with planning)

**Intent:** Teach skills in real time, maintain situational awareness, surface issues fast.

How it works:

- Weekly, \~10 min per team

- Each team presents status on each goal (on track or at risk) and what signals they're seeing. The leader drives the conversation from there — probing, challenging, coaching. This is not a status dump. The team doesn't run through a template; the leader asks the hard questions.

- When a goal goes red: increase cadence (daily check-ins) until resolved

**Teaching Prioritize Ruthlessly — example questions:**

- "You have 3 engineers on this P2 and your P1 is at risk. Walk me through that decision."

- "You started this goal 2 weeks ago and haven't touched your P1 yet. Why?"

- "This feels incremental. What's the biggest, scariest thing you could be doing instead?"

- "You have 4 goals in flight. If you could only finish one this month, which one moves the needle most?"

- "You said this was high-impact in planning. Now that you're two weeks in, do you still believe that? What's changed?"

- "Could you have validated this with a 2-day experiment before committing the whole team?"

**Teaching Make Good Calls Fast — example questions:**

- "You said you'd know by week 2 whether this approach works. It's week 3. What's your call?"

- "What signal would tell you to kill this? Have you seen it?"

- "You've been stuck on this for a week. What are you waiting for to make a decision?"

- "Is this a reversible decision? Then why are we still debating it — just pick one and go."

- "The data is ambiguous — but you still need to make a call. What's your recommendation?"

- "You're building this to production quality. Is that the right call right now, or should this be a prototype first?"

**Teaching Keep Everyone in the Loop — example questions:**

- "Team B is planning against your old timeline. When did you tell them it changed?"

- "You've known about this blocker since Tuesday. Why am I hearing about it on Friday?"

- "Who else is affected by this pivot? Have you told them?"

- "You said you need help — did you ask the team that has the expertise, or did you wait for this meeting?"

- "If this slips, who gets surprised? Have you warned them?"

**Template:** 

Use the Monthly template &gt; break down week by week what you need to do to reach the goal and use red-light system for visualizing how we are tracking versus goal. 

### 4. Monthly Review (first day of new month, combined with planning)

**Intent:** Evaluate bets, learn, recalibrate, and immediately plan the next month.

How it works:

- \~5 min per goal. Every goal gets a real discussion — not just "done/not done" but "what did we learn?"

- Each team reviews their goals: delivered or not delivered. Binary.

- Partial delivery = not delivered. Hold the line.

- "Almost done" = not done. Carry forward if it still matters.

- For each goal, whether it landed or not:

- Did our impact thesis hold up? Did this matter as much as we thought?

- Were our success criteria right? Did we read signals well?

- What does this unlock? What did it teach us?

- What did we learn that changes what we should bet on next?

- Celebrate: teams that made great bets, teams that killed bad bets fast, teams that delivered and re-upped

- Immediately flows into planning for the next month

**What the leader looks for:**

- Are teams honest about what worked and what didn't?

- Are they learning and recalibrating, or repeating the same mistakes?

- Is anyone moving the goalposts or claiming credit for accidental outcomes?

- Are the right lessons feeding into next month's bets?

### 5. Quarterly Review (last day of quarter, combined with last month planning and learning)

**Intent:** Evaluate bets, learn, recalibrate, and immediately plan the quarter.

How it works:

- \~10 min per goal. Every goal gets a real discussion — not just "done/not done" but "what did we learn?"

- Each team reviews their goals: delivered or not delivered. Binary.

- Partial delivery = not delivered. Hold the line.

- "Almost done" = not done. Carry forward if it still matters.

- For each goal, whether it landed or not:

- Did our impact thesis hold up? Did this matter as much as we thought?

- Were our success criteria right? Did we read signals well? When could we have known we were on the right or wrong track? 

- What does this unlock? What did it teach us?

- What did we learn that changes what we should bet on next?

- Celebrate: teams that made great bets, teams that killed bad bets fast, teams that delivered and re-upped

- Immediately flows into planning for the next quarter &gt; what have we learned about how we set goals? Based on what we achieved this quarter, how does this set us up for the next? 

**What the leader looks for:**

- Are teams honest about what worked and what didn't?

- Are they learning and recalibrating, or repeating the same mistakes?

- Is anyone moving the goalposts or claiming credit for accidental outcomes?

- Are the right lessons feeding into next month's bets?

## Visualized Rituals

<table style="min-width: 573px;">
<colgroup><col style="min-width: 25px;"><col style="width: 40px;"><col style="width: 40px;"><col style="width: 48px;"><col style="width: 49px;"><col style="width: 39px;"><col style="width: 53px;"><col style="width: 39px;"><col style="width: 48px;"><col style="width: 48px;"><col style="width: 48px;"><col style="width: 48px;"><col style="width: 48px;"></colgroup><tbody><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="4" rowspan="1" colwidth="40,40,48,49"><p>Month 1</p></td><td colspan="4" rowspan="1" colwidth="39,53,39,48"><p>Month 2</p></td><td colspan="4" rowspan="1" colwidth="48,48,48,48"><p>Month 3</p></td></tr><tr><td colspan="1" rowspan="1"><p></p></td><td colspan="1" rowspan="1" colwidth="40"><p>W1</p></td><td colspan="1" rowspan="1" colwidth="40"><p>W2</p></td><td colspan="1" rowspan="1" colwidth="48"><p>W3</p></td><td colspan="1" rowspan="1" colwidth="49"><p>W4</p></td><td colspan="1" rowspan="1" colwidth="39"><p>W5</p></td><td colspan="1" rowspan="1" colwidth="53"><p>W6</p></td><td colspan="1" rowspan="1" colwidth="39"><p>W7</p></td><td colspan="1" rowspan="1" colwidth="48"><p>W8</p></td><td colspan="1" rowspan="1" colwidth="48"><p>W9</p></td><td colspan="1" rowspan="1" colwidth="48"><p>W10</p></td><td colspan="1" rowspan="1" colwidth="48"><p>W11</p></td><td colspan="1" rowspan="1" colwidth="48"><p>W12</p></td></tr><tr><td colspan="1" rowspan="1"><p>Quarter</p></td><td colspan="1" rowspan="1" colwidth="40"><p></p></td><td colspan="1" rowspan="1" colwidth="40"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="49"><p></p></td><td colspan="1" rowspan="1" colwidth="39"><p></p></td><td colspan="1" rowspan="1" colwidth="53"><p></p></td><td colspan="1" rowspan="1" colwidth="39"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p>E&amp;P</p></td></tr><tr><td colspan="1" rowspan="1"><p>Month</p></td><td colspan="1" rowspan="1" colwidth="40"><p></p></td><td colspan="1" rowspan="1" colwidth="40"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="49"><p>E&amp;P</p></td><td colspan="1" rowspan="1" colwidth="39"><p></p></td><td colspan="1" rowspan="1" colwidth="53"><p></p></td><td colspan="1" rowspan="1" colwidth="39"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p>E&amp;P</p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p></p></td><td colspan="1" rowspan="1" colwidth="48"><p>E&amp;P</p></td></tr><tr><td colspan="1" rowspan="1"><p>Week</p></td><td colspan="1" rowspan="1" colwidth="40"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="40"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="48"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="49"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="39"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="53"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="39"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="48"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="48"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="48"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="48"><p>ER</p></td><td colspan="1" rowspan="1" colwidth="48"><p>ER</p></td></tr></tbody>
</table>

## Holding the Line

The hardest part of this system is maintaining standards. Teams will try to:

- Redefine "done" after the fact

- Claim partial credit

- Blame external factors instead of examining their own decisions

- Inflate impact estimates to make bets look better in retrospect

The leader must hold the line — not to punish, but to maintain the integrity of the system. If the bar is fuzzy, the skills don't develop. If "not delivered" has no weight, prioritization doesn't matter. If bad bets aren't acknowledged, kill discipline never develops.

This is not about blame. It's about honest evaluation so that the team gets better every month. The question is always: **what did we learn, and what will we do differently?**

## What This Looks Like When It's Working

- Teams make sharp, well-reasoned bets and can explain why

- Dead-end work gets killed in weeks, not months

- When plans change, everyone who needs to know finds out immediately

- Monthly reviews are honest — misses are acknowledged and learned from

- The org gets measurably better at predicting what will matter and delivering against it

- People work hard but sustainably — the system creates focus, not pressure

## Appendix: Goal Maturity Levels

Most teams new to goal-setting will default to "ship a feature" or "launch a model." That's a task, not a goal — it says nothing about whether the work mattered. But jumping straight to outcome-based goals requires instrumentation, baselines, and a measurement culture that takes time to build.

Meet teams where they are and ratchet up over time:

### Level 1: Clear Deliverable

*"Ship X, with an unambiguous definition of done."*

- Not "work on search" — that's an activity with no endpoint

- Instead: "Search is live in production for all users by end of month"

- The bar is low but it teaches the foundational discipline: write something down that's crisp enough that everyone agrees whether it happened or not

- This is where most teams will start

### Level 2: Deliverable + Success Criteria

*"Ship X, and here's how we'll know it's working."*

- "Search is live in production. We'll know it's working if query latency is under 200ms and 20% of users try it in the first week."

- Forces teams to think about what success looks like *before* they build

- Creates a natural feedback loop in the monthly review: "You shipped it — did it meet your success criteria? Why or why not?"

- Starts building the measurement muscle

### Level 3: Outcome-Driven

*"Achieve Y — we believe X is the lever."*

- "Increase user retention by 5%. We believe search is the key lever and plan to ship it this month."

- The team owns the outcome, not just the output

- If search ships but retention doesn't move, that's a miss — and a valuable learning moment about bet selection and impact estimation

- Requires real instrumentation and baseline metrics to evaluate

### How to Ratchet Up

- Start every team at the level they can credibly execute

- The monthly review is the ratcheting mechanism: when a team says "we shipped it," ask "did it matter? How do you know?" Do that enough times and teams start building the measurement into the goal themselves

- Push teams to the next level individually as they're ready — don't force the whole org to level 3 at once

- Some goals will naturally stay at Level 1 (infrastructure work, migrations) and that's fine — not everything has a user-facing outcome metric