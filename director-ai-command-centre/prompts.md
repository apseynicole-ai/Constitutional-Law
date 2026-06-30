# Dad's Director AI Command Centre — All 37 Prompts
## Plain Markdown Edition — Use Without the Dashboard

Copy any prompt, replace the `[BRACKETED PLACEHOLDERS]` with your real context, and paste into Claude.

---

## A. Director OS Core

---

### Prompt 01 — Director Cockpit Master Prompt

**What it's for:** Sets up Claude as your executive AI assistant with standing rules for every session.
**Best used when:** Paste this at the start of every new Claude conversation or into your Claude Project system prompt.

```
You are my executive AI assistant. I am a Senior Director at [COMPANY / BRAND], a major South African fashion and apparel retail brand.

My role spans: [LIST YOUR AREAS — e.g. buying, planning, store operations, digital, supply chain, brand].

When I work with you, apply these rules at all times:
1. Separate confirmed facts from assumptions. Label them clearly — prefix assumptions with "Assumed:".
2. Flag any missing information I should provide before you proceed.
3. Never invent numbers, names, dates, or outcomes. If you don't know, say so.
4. Output must be executive-ready: structured, specific, no filler.
5. Default output format unless I specify otherwise: short headline → key points → actions / decisions needed → risks / flags.
6. When I say "delta update" — assume I'm giving you new information to layer onto prior context. Don't restart.
7. Challenge my thinking if you see a gap or risk I haven't raised.
8. One question maximum per response. Ask it at the end, not before you answer.

My current priorities are:
[PASTE YOUR TOP 3–5 PRIORITIES HERE]

My key active projects are:
[PASTE YOUR ACTIVE PROJECTS HERE]

Use this as your baseline context for our session. Confirm you have absorbed it and ask me one clarifying question if needed.
```

---

### Prompt 02 — Weekly Director Briefing

**What it's for:** Builds a structured weekly briefing from raw updates, emails, and team notes.
**Best used when:** Monday morning — before your first key meeting of the week.

```
Context: I am a Senior Director at [COMPANY / BRAND]. It is [TIME PERIOD].

Goal: Build me a structured weekly briefing based on the updates below.

Source material:
[PASTE UPDATE HERE — team updates, project status, emails, notes, anything relevant]

Output required:
1. Executive Summary (3–5 bullets — what matters most this week)
2. Projects: status, key movement, blockers
3. Decisions needed from me this week — with deadlines
4. Risks or issues requiring my attention
5. What's on track and can be deprioritised this week
6. Suggested weekly focus: where should I spend my time?

Constraints:
- Separate confirmed facts from assumptions. Label assumptions "Assumed:".
- Flag any information gaps that would change your assessment.
- Do not invent outcomes. If data is missing, say so explicitly.
- Keep it scannable — use bullets and headers, not paragraphs.
- Maximum 400 words.

Format: Structured briefing with clear section headers. Ready to read in under 4 minutes.
```

---

### Prompt 03 — Delta Update / What Changed Since Last Week

**What it's for:** Extracts only genuine changes between last week and now — cuts through repetition.
**Best used when:** Any time you want to update Claude without re-briefing it on everything. Also useful Friday afternoon.

```
Context: I am a Senior Director at [COMPANY / BRAND].

Goal: Identify what has materially changed since last week and what I need to know. Skip everything that hasn't moved.

Last week's position:
[PASTE LAST WEEK'S SUMMARY OR KEY POINTS HERE]

This week's update:
[PASTE THIS WEEK'S UPDATE HERE]

Output required:
1. What changed? (Material changes only — new risks, decisions, blockers, wins)
2. What is the same? (One line — no need to re-brief me)
3. What has moved in the wrong direction? Flag urgency level.
4. What has moved in the right direction? Note the driver.
5. Net assessment: are we better or worse positioned than last week?
6. One action I must take before end of week

Constraints:
- Only report genuine changes — skip noise and repetition.
- Label assumptions clearly. Do not invent data.
- Be blunt. If things are off track, say so directly.
- Lead with the most important change, not the most recent one.

Format: Delta report — changes only, clearly labelled. Under 300 words.
```

---

### Prompt 04 — Executive Risk Radar

**What it's for:** Scans your whole portfolio for risks across three urgency tiers: Red / Amber / Green.
**Best used when:** End of week review, before a board meeting, or whenever things feel like they might be slipping.

```
Context: I am a Senior Director at [COMPANY / BRAND] reviewing [TIME PERIOD].

Goal: Scan for risks across my portfolio and flag what needs attention now vs. later. Be thorough. Be blunt.

Source material:
[PASTE PROJECT UPDATES, TEAM NOTES, OR CONTEXT HERE]

Output required:
1. Risk Radar — three tiers:
   - RED: Risks that could impact delivery, budget, or brand within 2 weeks. Requires my action now.
   - AMBER: Risks that need monitoring and could escalate without intervention.
   - GREEN: Under control — no action needed.

2. For each RED and AMBER risk:
   - What is the risk?
   - Likelihood: High / Medium / Low
   - Impact if it materialises
   - Recommended action and owner
   - Deadline for action

3. Risks I may be underestimating — your independent read
4. One question I should be asking that I'm probably not

Constraints:
- Separate confirmed risks from speculative ones. Label speculative risks "Inferred:".
- Do not invent risks without basis in the material I've provided.
- Be specific — vague risk flags are not useful.

Format: Tiered risk table (RED / AMBER / GREEN) with narrative flags below.
```

---

### Prompt 05 — "What Needs My Attention?" Filter

**What it's for:** Triages everything that has landed in your lap — tells you what to act on, delegate, or ignore.
**Best used when:** Start of day, after returning from leave, or whenever your inbox feels unmanageable.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I have limited time and need to triage fast.

Goal: From everything below, tell me what actually needs MY attention versus what can be delegated or deprioritised.

Source material:
[PASTE EMAILS, UPDATES, REQUESTS, MEETING NOTES, OR ANYTHING THAT HAS LANDED ON YOUR DESK]

Output required:
1. Needs Director attention NOW (today / this week)
   — Item, why it needs me specifically, and what action I should take

2. Delegate
   — Item, who should own it, what instruction I should give them

3. Deprioritise
   — Item, brief reason it can wait

4. Watch but don't act
   — Flag it but no action needed yet; tell me what would change that

5. Missing context
   — Things I should clarify before deciding how to handle them

Constraints:
- Apply strict triage. Not everything is urgent. Challenge my instinct to do everything myself.
- Flag where you're making assumptions about what I can delegate.
- Do not invent context. Work only with what I've provided.

Format: Triage matrix — four clear sections with reasoning per item.
```

---

## B. Project Oversight

---

### Prompt 06 — Project Health Check

**What it's for:** An honest, structured health check across all key dimensions of a single project.
**Best used when:** Weekly project reviews, before a steering committee, or when something feels off.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I am reviewing [PROJECT NAME].

Goal: Give me an honest health check on this project. No sugar-coating. Tell me what I need to know.

Source material:
[PASTE PROJECT UPDATE, STATUS REPORT, OR NOTES HERE]

Output required — assess each dimension and give a RAG rating (Red / Amber / Green):

1. Overall health: RED / AMBER / GREEN — one-line rationale
2. Schedule: On track? What's the risk to the delivery date?
3. Budget: Any flags or overspend risk?
4. Team: Capacity gaps, ownership issues, morale flags?
5. Blockers: What is actively stopping progress right now?
6. Risk: What could derail this in the next 30 days?
7. Director action needed: What do I need to do or decide this week?
8. Recommended next step — specific, owned, deadline attached

Questions I need answered:
- Is this project recoverable if it's off track?
- What is the single thing most likely to cause failure?
- Is the right person driving it?

Constraints:
- Separate confirmed facts from assumptions. Label assumptions "Assumed:".
- Flag any missing information that would change your assessment.
- Be direct. If it's failing, say so.

Format: Health check dashboard — RAG indicators per section + concise bullets.
```

---

### Prompt 07 — Project Rescue Mode

**What it's for:** Crisis triage for a project in trouble. Root cause, stabilisation, and recovery plan.
**Best used when:** A project has missed a milestone, lost a key owner, or is at real risk of failure.

```
Context: I am a Senior Director at [COMPANY / BRAND]. [PROJECT NAME] is in trouble and I need to move fast.

Goal: Give me a rescue plan — what went wrong, what I need to stabilise immediately, and how to recover.

Source material:
[PASTE WHAT YOU KNOW — WHAT'S WRONG, WHAT HAS HAPPENED, WHO IS INVOLVED]

Output required:
1. Diagnosis: What went wrong? Root cause, not just symptoms. Be specific.
2. Current blast radius: What is affected and how badly? What is at risk downstream?
3. Immediate stabilisation steps — next 48 hours (what, who, by when)
4. Recovery plan — next 2–4 weeks (milestones, owners, checkpoints)
5. What to stop doing immediately to stop making it worse
6. Who needs to be in the room for a rescue meeting? (roles, not names)
7. What do I need to communicate upward, and how? Draft the one-liner.
8. Honest assessment: Is this project saveable on current timeline and budget? If not, what are the options?

Constraints:
- Separate confirmed facts from your inferences. Label both.
- Do not soften the diagnosis. I need the truth to make good decisions.
- Flag any missing information that would change your recommendations.

Format: Rescue brief — clear headers, action-oriented, no filler. Under 500 words.
```

---

### Prompt 08 — Red / Amber / Green Status Review

**What it's for:** A clean RAG portfolio status across all active projects or workstreams at a glance.
**Best used when:** Weekly portfolio review, monthly reporting pack, or before any governance meeting.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I am reviewing my full project portfolio for [TIME PERIOD].

Goal: Produce a clean RAG status review across all active projects or workstreams.

Source material:
[PASTE UPDATES FOR ALL PROJECTS / WORKSTREAMS HERE]

Output required — for each project or workstream:
| Project | RAG | One-line rationale | Next key milestone + date | Blocker / risk | Action needed from me |
|---------|-----|-------------------|--------------------------|----------------|----------------------|

Apply RAG strictly:
- GREEN: On track. No intervention needed.
- AMBER: Risk exists. Monitoring required. Could escalate.
- RED: Off track or in crisis. Director intervention required now.

Portfolio summary at the end:
- Total RED / AMBER / GREEN count
- Most urgent single intervention needed
- One thing I can do today that would move the most projects forward
- Projects where I have insufficient information to rate accurately

Constraints:
- Apply RAG strictly. Do not give AMBER to a GREEN project to seem cautious.
- Separate confirmed status from inferences. Label inferred status "Inferred:".
- Flag projects with missing information — don't rate them GREEN by default.

Format: RAG table + portfolio summary. Scannable in 3 minutes.
```

---

### Prompt 09 — Dependency and Blocker Map

**What it's for:** Maps every blocker and dependency across your portfolio and tells you what you personally need to unblock.
**Best used when:** When multiple projects feel stuck and you need to see the whole picture at once.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I need to understand what is blocking progress across [PROJECT NAME] or my full portfolio.

Goal: Map all dependencies and blockers, identify which ones I own, and give me a clear action path.

Source material:
[PASTE PROJECT UPDATES OR CONTEXT HERE]

Output required:
1. Active Blockers
   — What is blocked | Why | Who owns the blocker | How long has it been stuck

2. Dependencies
   — What each project depends on (teams, decisions, approvals, suppliers, third parties)
   — Is that dependency at risk?

3. Blockers I own
   — Where am I the bottleneck? Where do I need to intervene?

4. Downstream risk
   — If these blockers aren't resolved this week, what breaks?

5. Recommended unblocking actions — prioritised, with owner and deadline

6. Escalations needed (internal or external)

Constraints:
- Separate confirmed blockers from suspected ones. Label suspected "Inferred:".
- Do not assume something is blocked without basis in what I've provided.
- Flag information gaps that would change the blocker assessment.

Format: Blocker table + dependency notes + prioritised action list.
```

---

### Prompt 10 — Owner Accountability Review

**What it's for:** Surfaces ownership gaps, conflicts, and accountability failures across a team or project.
**Best used when:** When things are slipping and you're not sure who owns what — or when no one is driving.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I am reviewing accountability across [TEAM / DEPARTMENT] or [PROJECT NAME].

Goal: Identify where ownership is clear, where it is unclear or contested, and where I need to intervene.

Source material:
[PASTE TEAM UPDATES, PROJECT STATUS, OR RACI / OWNERSHIP NOTES HERE]

Output required:
1. Owner mapping: Who owns what — and is ownership clear and accepted?
2. Ownership gaps: Tasks or workstreams with no clear owner
3. Ownership conflicts: Where two or more people think they own the same thing
4. Accountability concerns: An owner exists, but progress is not happening — why?
5. Director interventions needed: Where I need to clarify, reallocate, or escalate ownership
6. Recommended owner assignments for any gaps (suggest by role, not name)

Constraints:
- Base your assessment only on the material I've provided. Do not invent ownership.
- Label inferences clearly — "Inferred from [X]:".
- Be direct about accountability concerns. Softening them helps no one.

Format: Accountability table + intervention list. Direct and specific.
```

---

## C. Decision-Making

---

### Prompt 11 — Director-Level Decision Memo

**What it's for:** Structures any decision into a clear, Exco-ready memo — options, recommendation, rationale.
**Best used when:** Before making any significant decision or escalating one to leadership.

```
Context: I am a Senior Director at [COMPANY / BRAND] and need to make or structure a decision about [DECISION NEEDED].

Goal: Help me write a clear, well-reasoned decision memo — one I can use to make or escalate this decision with confidence.

Source material:
[PASTE RELEVANT CONTEXT, DATA, OPTIONS, OR BACKGROUND HERE]

Output required:
1. Decision statement: What exactly needs to be decided, and by when?
2. Context and background (2–3 sentences maximum)
3. Options considered (2–4 options):
   - Option name
   - What it involves
   - Pros
   - Cons
   - Risks
   - Estimated cost or effort (use ranges if exact figures not available)
4. Recommended option — with direct rationale. Don't hedge.
5. Key assumptions behind the recommendation (label each one)
6. What would change this recommendation?
7. Who needs to be informed, consulted, or sign off?
8. Decision deadline and consequences of delay

Constraints:
- Separate confirmed data from assumptions. Label assumptions clearly.
- Do not invent numbers or outcomes. Use only what I've provided.
- This memo must be usable in a senior leadership meeting without revision.

Format: Structured decision memo. Professional, direct, executive-ready.
```

---

### Prompt 12 — Options and Trade-Offs Analysis

**What it's for:** Cuts through pros/cons lists to expose what you're truly trading when choosing between options.
**Best used when:** When a decision is genuinely difficult and the right answer isn't obvious.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I am evaluating options for [DECISION NEEDED].

Goal: Give me a rigorous, honest trade-offs analysis — not a list of pros and cons, but a genuine assessment of what I'm actually giving up with each choice.

Source material:
[PASTE THE OPTIONS, CONTEXT, OR BACKGROUND HERE]

Output required:
1. The real trade-offs — for each option: what am I giving up by choosing it? Not what I'm gaining.
2. Short-term vs. long-term trade-offs — do they point the same way or pull in opposite directions?
3. What is reversible vs. irreversible in each option?
4. Worst-case outcome for each option — be specific
5. What does each option optimise for? (cost, speed, quality, brand, team, risk reduction)
6. Your recommended option and why. Be direct. No hedging.
7. The one trade-off I'm probably not weighing heavily enough

Constraints:
- Do not manufacture options or data. Work only with what I've provided.
- Separate what is confirmed from what is speculative.
- Be direct. A mediocre analysis disguised as balance helps no one.

Format: Trade-offs matrix per option + narrative recommendation.
```

---

### Prompt 13 — CFO / COO / Brand Director Challenge

**What it's for:** Red-teams your proposal the way a CFO, COO, and Brand Director would — before they do it to you.
**Best used when:** Before presenting to Exco, the board, or any senior stakeholder who will push back hard.

```
Context: I am a Senior Director at [COMPANY / BRAND] preparing to defend [DECISION NEEDED] or [PROJECT NAME] in a senior leadership forum.

Goal: Challenge my position the way a CFO, COO, and Brand Director would. Find every weakness before they do.

My current position or proposal:
[PASTE YOUR PROPOSAL, PLAN, OR POSITION HERE]

Output required:
1. CFO challenge — 5 hardest financial questions they will ask:
   (focus: ROI, payback period, budget risk, hidden costs, alternatives considered)

2. COO challenge — 5 hardest operational feasibility questions:
   (focus: delivery risk, resource availability, dependencies, execution track record, rollback)

3. Brand Director challenge — 5 hardest brand and customer questions:
   (focus: customer impact, brand equity, competitive positioning, channel consistency, risk of brand damage)

4. The weakest point in my current argument — be specific
5. The assumption most likely to be wrong
6. The question I most need to be able to answer before this goes to Exco
7. What would make this proposal airtight? Two or three specific improvements.

Constraints:
- Be ruthless. Soft challenges are not useful to me.
- Base challenges on what's in my material. Don't invent scenarios.
- Separate confirmed vulnerabilities from speculative ones.

Format: Challenge brief — grouped by stakeholder perspective, with ranked severity.
```

---

### Prompt 14 — What Would Change My Mind?

**What it's for:** Tests the strength of your own position by identifying what evidence would reverse it.
**Best used when:** When you're strongly committed to a direction and want to make sure you're not anchoring.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I have a current position on [DECISION NEEDED].

Goal: Help me honestly identify what evidence, data, or conditions would cause me to reverse or significantly change my position. This is a structured pre-mortem on my own thinking — not a validation exercise.

My current position:
[PASTE YOUR CURRENT VIEW, RECOMMENDATION, OR PLAN HERE]

Output required:
1. What new information or data would change my recommendation entirely?
2. What assumptions am I relying on that, if wrong, would break my position?
3. What early warning signals should I watch for that suggest I'm wrong?
4. What would the opposing view need to show to convince me?
5. Am I anchoring on a previous decision or sunk cost? Flag if the material suggests so.
6. If a respected colleague came to me with this same position, what would I challenge first?
7. Verdict: How robust is my current position on a scale of 1–10? Why?

Constraints:
- This is not about finding problems — it's about testing my reasoning honestly.
- Separate things that would definitely change my mind from things that might.
- Do not validate my position. Challenge it.

Format: Structured reflection — numbered, direct, under 350 words.
```

---

### Prompt 15 — Approval Gate Checklist

**What it's for:** A structured pre-approval checklist to ensure you're signing off on something that's actually ready.
**Best used when:** Before giving approval on a project phase, budget release, supplier appointment, or major initiative.

```
Context: I am a Senior Director at [COMPANY / BRAND]. [PROJECT NAME] or [DECISION NEEDED] is approaching an approval gate and I need to decide whether to approve.

Goal: Give me a structured checklist of what must be true before I give — or recommend — approval.

Source material:
[PASTE WHAT YOU KNOW ABOUT THE PROJECT OR DECISION SEEKING APPROVAL]

Output required:
1. Approval readiness checklist — for each item, rate: ✅ Ready / ⚠️ Partial / ❌ Not Ready / ❓ Unknown:
   - Business case confirmed and credible?
   - Budget approved or within my authority level?
   - Key risks identified, owned, and mitigated?
   - Stakeholders aligned (no hidden objections)?
   - Delivery plan clear, resourced, and realistic?
   - Dependencies confirmed and not at risk?
   - Success metrics defined and measurable?
   - Rollback or exit plan exists (if applicable)?
   - Legal / compliance / procurement sign-off obtained?

2. Items that would cause me to withhold approval
3. Conditions I should attach to a conditional approval
4. Questions to ask before I sign off
5. My recommended call: Approve / Approve with conditions / Reject — and why

Constraints:
- Base the assessment only on what I've provided. Flag gaps clearly — don't assume things are ready.
- Separate confirmed items from assumed ones.
- If critical information is missing, recommend I get it before approving.

Format: Checklist table + recommendation statement. Direct.
```

---

## D. Fashion Retail Leadership

---

### Prompt 16 — Range Launch Readiness Review

**What it's for:** A comprehensive pre-launch readiness check across all workstreams for a new range or season.
**Best used when:** Two to four weeks before any range launch, key season drop, or collection go-live.

```
Context: I am a Senior Director at [COMPANY / BRAND]. We are preparing to launch [RANGE / SEASON].

Goal: Give me a comprehensive readiness review — what is in place, what is not, and what could derail the launch.

Source material:
[PASTE RANGE LAUNCH PLAN, STATUS UPDATES, OR BUYING/MERCHANDISING NOTES HERE]

Output required:
1. Overall launch readiness: RED / AMBER / GREEN — rationale in one sentence

2. Readiness by workstream (RAG per area):
   - Product / range: buying finalised, quality confirmed, samples approved?
   - Supply chain: suppliers confirmed, production on schedule?
   - Inventory: stock expected to land when? What's the availability risk?
   - Visual merchandising: VM concept approved, materials ready, rollout plan confirmed?
   - Marketing and campaign: assets ready, go-live confirmed, media booked?
   - Pricing and promotion: pricing signed off, promotional mechanics approved?
   - Systems and operations: till, stock system, e-commerce all ready?

3. Critical path: What must happen in what sequence for launch to succeed?
4. Blockers and risks to the launch date — ranked by severity
5. Go / No-Go recommendation with rationale
6. Director actions needed before launch (what, who, by when)

Constraints:
- Separate confirmed readiness from assumed readiness. Label assumptions clearly.
- Do not invent status. If information is missing, flag it.
- Be direct about risks — a delayed launch flagged early is far better than a failed one.

Format: Readiness dashboard + Go/No-Go recommendation. Ready for a leadership review.
```

---

### Prompt 17 — Supplier Scorecard Review

**What it's for:** A structured performance assessment of key suppliers — who is delivering and who needs action.
**Best used when:** Quarterly supplier reviews, season-end assessments, or when supplier performance is a concern.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I am reviewing supplier performance for [TIME PERIOD].

Goal: Give me a structured scorecard assessment of supplier performance and flag any relationships that need action.

Source material:
[PASTE SUPPLIER DATA, PERFORMANCE NOTES, DELIVERY RECORDS, QUALITY ISSUES, OR FEEDBACK HERE]

Output required:
For each supplier (or key suppliers if many):
| Supplier | RAG | On-time delivery | Quality issues | Responsiveness | Value vs. market | Dependency risk | Recommended action |
|----------|-----|-----------------|----------------|----------------|-----------------|-----------------|-------------------|

Recommended actions: Continue / Review terms / Performance plan / Explore alternatives / Exit

Portfolio summary:
- Top-performing suppliers — what are they doing right?
- Suppliers requiring immediate intervention and why
- Strategic supply chain risks (concentration, single-source exposure)
- Conversations or renegotiations I need to lead personally

Constraints:
- Separate data-confirmed performance from inferences. Label inferred "Assumed:".
- Flag where I have insufficient data to rate a supplier — don't default them to GREEN.
- Do not invent performance numbers.

Format: Scorecard table per supplier + strategic summary. Usable in a supplier review meeting.
```

---

### Prompt 18 — Stock / Markdown Risk Review

**What it's for:** Identifies over-stock positions, sell-through gaps, and markdown exposure before it's too late.
**Best used when:** Mid-season, end of season, or whenever aged stock or sell-through is a concern.

```
Context: I am a Senior Director at [COMPANY / BRAND] reviewing stock and markdown risk for [TIME PERIOD] or [RANGE / SEASON].

Goal: Identify where we have stock risk, what the markdown exposure is, and what actions to take now to protect margin.

Source material:
[PASTE SALES OR STOCK DATA, SELL-THROUGH RATES, AGED STOCK REPORTS, OR MARKDOWN PLANS HERE]

Output required:
1. Stock risk summary: Where are we over-stocked? What is the exposure (units and estimated value)?
2. Sell-through performance: What's selling vs. what's not? Any patterns by category, store, or channel?
3. Markdown risk: What markdowns are likely or already overdue? What is the financial exposure?
4. Aged stock: What has been sitting too long and is now a write-off risk?
5. Recommended actions — by priority:
   - Price interventions (what, when, how deep)
   - Store transfers or stock consolidation
   - Promotional options to drive velocity
   - Supplier returns (if contractually possible)
   - Write-off decisions (if applicable)
6. Seasonal deadline: When do we need to act to avoid deeper markdowns?
7. Director decisions needed — what can only I approve or initiate?

Constraints:
- Separate confirmed data from assumptions. Flag where data is incomplete.
- Do not invent stock numbers. If sell-through data is missing, state the limitation.
- Be direct about exposure — don't soften the risk.

Format: Stock risk report — tiered by urgency + recommended actions with owners.
```

---

### Prompt 19 — Store Rollout Readiness Review

**What it's for:** Readiness check for a store opening, store refresh, or major in-store initiative rollout.
**Best used when:** Two to three weeks before any store opening, store rebrand, or format rollout.

```
Context: I am a Senior Director at [COMPANY / BRAND]. We are rolling out [PROJECT NAME] — a store opening, refresh, or in-store initiative.

Goal: Review readiness for the store rollout and flag anything that could cause a poor execution or customer experience failure.

Source material:
[PASTE ROLLOUT PLAN, STORE READINESS NOTES, OR STATUS UPDATES HERE]

Output required:
1. Overall rollout readiness: RED / AMBER / GREEN

2. Readiness by workstream (RAG per area):
   - Store build / fit-out: construction, fixtures, signage
   - VM and range setup: stock on floor, display executed, signage correct
   - Stock availability and logistics: stock landed, correct quantities, allocated correctly
   - POS and systems: tills live, training done, stock system loaded
   - Staff: headcount confirmed, training completed, floor-ready
   - Marketing and local activation: opening promotion, in-store and digital confirmed
   - Management: store manager confirmed and briefed?

3. Stores or locations that are behind — and by how much
4. Critical path: what must happen in what order in the next two weeks?
5. Go / No-Go recommendation — with rationale
6. Director actions required before opening

Constraints:
- Flag where readiness is assumed vs. confirmed. Label confirmed vs. "Assumed:".
- Do not invent store status. If data is missing, say so.
- Be direct about risk — a delayed opening is better than a poor one.

Format: Readiness dashboard per workstream + Go/No-Go call. Suitable for a store ops review.
```

---

### Prompt 20 — Campaign Post-Mortem Review

**What it's for:** A rigorous campaign post-mortem — what worked, what didn't, and what to lock in for next time.
**Best used when:** Within two weeks of any campaign ending, while memory is fresh and data is available.

```
Context: I am a Senior Director at [COMPANY / BRAND]. [PROJECT NAME] campaign has concluded. I want a rigorous post-mortem.

Goal: Understand what worked, what didn't, what we should do differently, and what decisions to lock in before next time.

Source material:
[PASTE CAMPAIGN RESULTS, SALES DATA, CUSTOMER FEEDBACK, TEAM NOTES, OR POST-CAMPAIGN REPORT HERE]

Output required:
1. Performance vs. objectives: Did we hit our goals? For each objective: Met / Partially Met / Missed + why.
2. What worked well — and why (not just what, but the mechanism behind it)
3. What didn't work — root cause, not just symptoms. Be specific.
4. Customer response: How did customers actually react? What does the data tell us?
5. Execution quality: team, agency, suppliers, timing, in-store — what was the real score?
6. Financial outcome: revenue vs. plan, margin impact, markdown exposure from the campaign
7. Three things to replicate in the next campaign — and why they worked
8. Three things to stop or change — and what to do instead
9. One structural decision to lock in now before the next campaign planning cycle starts

Constraints:
- Separate confirmed data from inferences. Label inferences clearly.
- Do not invent results. Where data is missing, flag the gap explicitly.
- Be direct — a soft post-mortem helps no one improve.

Format: Structured post-mortem — What Worked / What Didn't / What Next.
```

---

### Prompt 21 — Customer Impact Review

**What it's for:** Assesses how a decision, project, or issue actually affects customers — and what to do about it.
**Best used when:** Before launching anything customer-facing, or when an issue is affecting the customer experience.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I need to assess the customer impact of [PROJECT NAME] or [ISSUE].

Goal: Give me an honest assessment of how this affects our customers — who, how badly, and what we need to do.

Source material:
[PASTE RELEVANT CONTEXT — CUSTOMER FEEDBACK, COMPLAINTS, SALES DATA, OR PROJECT NOTES]

Output required:
1. Who is affected? (Customer segment, approximate volume if data available)
2. How are they affected? (Experience, product quality, price, service, availability, brand trust)
3. Severity: Minor inconvenience / Meaningful frustration / Brand-reputation risk / Customer loss risk
4. What customers are likely to do in response: stay and tolerate / complain / defect to competitor / share publicly
5. Speed of impact: Already being felt / Upcoming / Potential if not addressed
6. Recommended customer response: What do we do for customers, and how fast?
7. Communication: Do we need to communicate to customers? If so, what to say and through which channel.
8. Brand risk: Does this create longer-term brand damage if not addressed?
9. Director decision needed: What can only I approve or initiate?

Constraints:
- Separate confirmed customer data from assumptions about customer behaviour. Label "Assumed:" clearly.
- Do not invent customer sentiment or make up numbers.
- Be direct about brand risk. Downplaying it helps no one.

Format: Customer impact brief — severity-rated with action recommendations and timeline.
```

---

### Prompt 22 — Buying and Merchandising Meeting Prep

**What it's for:** Prepares you for a buying or merchandising meeting — the right questions, key numbers, and your position.
**Best used when:** Before any range review, OTB meeting, intake planning session, or buying sign-off meeting.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I am preparing for [MEETING NAME] — a buying and merchandising meeting for [RANGE / SEASON].

Goal: Help me walk into this meeting prepared: the right questions, the key numbers I should know, and a clear position.

Source material:
[PASTE MEETING AGENDA, RANGE PLAN, SALES DATA, OR PRE-READ MATERIALS HERE]

Output required:
1. Key numbers I must know before walking in:
   - Sell-through rate (current season vs. last year)
   - Stock cover (weeks)
   - Intake plan vs. open-to-buy available
   - Markdown exposure to date
   - Best and worst performing categories

2. Three strategic questions I should ask the team — not operational questions, but ones that test their thinking

3. Red flags to probe: What in the data or plan should I push back on? What looks too optimistic?

4. Decisions the team is likely to bring to me — and my initial position on each

5. My opening frame for the meeting: What tone and priority do I want to set?

6. What a good outcome looks like — what should I leave this meeting having agreed or decided?

Constraints:
- Flag assumptions about what the meeting will cover if the agenda is incomplete.
- Separate confirmed data from inferences.
- Focus on the highest-leverage questions — not an exhaustive list.

Format: Meeting prep pack — structured sections, scannable, ready to review 10 minutes before.
```

---

## E. Meetings and Communication

---

### Prompt 23 — Meeting Prep Pack

**What it's for:** A complete pre-meeting briefing — context, objectives, questions, and your position.
**Best used when:** Before any important meeting where you need to be sharp and prepared.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I have [MEETING NAME] coming up.

Goal: Prepare me to walk into this meeting with the right context, questions, and position.

Source material:
[PASTE MEETING AGENDA, PRE-READ, RELEVANT CONTEXT, OR NOTES HERE]

Output required:
1. Meeting purpose — what is this meeting actually trying to achieve? (Not what the agenda says — what's the real objective)
2. Key context I need to know before walking in (2–4 bullets)
3. My objectives for this meeting — what I want to leave with (decisions made, commitments secured, direction set)
4. The 3–5 most important questions I should ask in this meeting
5. Points I should push back on or probe — where is the narrative or plan weak?
6. Decisions I may be asked to make — and my preliminary position on each
7. Who in the room needs what from me specifically?
8. Risk: What could go wrong in this meeting, and how should I handle it?

Constraints:
- Work only with what I've provided. Flag information gaps.
- Separate confirmed information from your inferences.
- Keep it scannable — I may read this 10 minutes before the meeting.

Format: Concise meeting prep pack — I should be able to brief myself in under 5 minutes.
```

---

### Prompt 24 — Board / Exco Briefing Prep

**What it's for:** Pressure-tests your Exco or Board briefing and prepares you for the hardest questions.
**Best used when:** Before presenting to the Board, Exco, or any senior governance forum.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I am presenting to the Board or Exco on [PROJECT NAME] or [DECISION NEEDED].

Goal: Help me prepare a briefing that is tight, credible, and anticipates the hard questions. Find the weaknesses before they do.

Source material:
[PASTE YOUR DRAFT BRIEFING, TALKING POINTS, OR RELEVANT CONTEXT HERE]

Output required:
1. Narrative assessment: Is the structure logical and compelling? Where does it lose the room?
2. The three things the Board or Exco will care about most — am I covering them clearly?
3. Gaps or weaknesses in my current briefing — be specific
4. The 5 hardest questions I'm likely to face — with strong, direct suggested answers
5. What I must NOT say (things that will trigger alarm, undermine credibility, or open a rabbit hole)
6. The single most important point — the one that will determine whether this lands well
7. My recommended opening statement (2–3 sentences that establish credibility and frame the discussion)
8. My recommended close (what I want them to walk away thinking, feeling, and deciding)

Constraints:
- Be direct about weaknesses. A board meeting is not the place to discover them.
- Separate what is confirmed from what is assumed.
- Do not smooth over gaps — flag them so I can address them before presenting.

Format: Briefing prep pack — structured sections with specific, direct guidance.
```

---

### Prompt 25 — Difficult Conversation Prep

**What it's for:** Structures a difficult conversation so you're clear, direct, fair — and it achieves the right outcome.
**Best used when:** Before any hard performance conversation, peer conflict, or stakeholder confrontation.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I need to have a difficult conversation about [ISSUE].

Goal: Help me prepare for this conversation so I enter it clear, direct, and fair — and it achieves the right outcome.

The situation:
[DESCRIBE WHAT NEEDS TO BE ADDRESSED, WITH WHOM, AND WHAT HAS HAPPENED]

Output required:
1. What outcome do I actually want from this conversation? (Be specific — not "it goes well")
2. Opening statement: How do I begin — direct but not aggressive. Draft the first 2–3 sentences.
3. The core message I need to land: What must they hear and understand? (Irreducible minimum)
4. How they are likely to respond: Defensively / dismissively / emotionally / reasonably — what's most probable and why?
5. How I handle the likely responses — specific language for the likely pushback
6. What I must not do in this conversation (pitfalls: avoiding, over-explaining, apologising for the message)
7. What a successful outcome looks like — specifically, concretely
8. If the conversation fails: What is my next step?

Constraints:
- This must be direct and respectful — not soft or vague.
- Separate what is confirmed about the situation from assumptions about the other person.
- Do not invent facts about the person or situation.

Format: Conversation prep guide — sequential, practical, scannable. Under 400 words.
```

---

### Prompt 26 — Escalation Message Draft

**What it's for:** Drafts a clear, professional escalation message — email and short form — that gets the right response.
**Best used when:** When you need to escalate an issue to the CEO, Exco, or peer director and the message needs to land.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I need to escalate [ISSUE] to [describe the recipient].

Goal: Draft an escalation message that is clear, professional, and gets the right response — a decision, resource, intervention, or endorsement.

Source material:
[DESCRIBE THE ISSUE, WHAT HAS BEEN TRIED, WHAT YOU NEED FROM THE RECIPIENT, AND THE CONSEQUENCE OF INACTION]

Output required:
Draft an escalation that includes:
1. What the issue is — one direct sentence
2. Why I'm escalating now — urgency, impact, what has already been tried and failed
3. What I specifically need from the recipient — decision / resource / approval / intervention
4. What happens if they don't act — consequence and timeline
5. What I have already done or attempted
6. Recommended next step with timeline

Tone: Direct, professional, not alarmist. Senior leader to senior leader.

Then provide:
- Email subject line (one sentence, specific)
- A tighter WhatsApp / message version (under 100 words)
- One note on what I should not say in this escalation

Constraints:
- Separate confirmed facts from inferences. Label inferences.
- Do not invent facts about the situation.
- The draft must be usable without significant editing.

Format: Full email version + short message version + subject line.
```

---

### Prompt 27 — Post-Meeting Action Extractor

**What it's for:** Extracts every action, decision, and follow-up from meeting notes — nothing slips through.
**Best used when:** Immediately after any important meeting. Paste your rough notes and get a clean action log.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I have just completed [MEETING NAME].

Goal: Extract all actions, decisions, and follow-ups from the meeting notes below — cleanly, specifically, with no gaps.

Source material:
[PASTE MEETING NOTES, TRANSCRIPT, SUMMARY, OR YOUR OWN ROUGH NOTES HERE]

Output required:
1. Decisions made: What was agreed? No ambiguity. State what was decided.
2. Actions (full log):
   | Action | Owner (by role) | Due date | Priority |
   |--------|----------------|----------|----------|
3. My personal actions: What do I specifically own coming out of this meeting?
4. Items discussed but NOT decided — need follow-up or a separate decision
5. Issues or risks surfaced in the meeting that need tracking
6. What needs to be communicated to people not in the room — and who sends it?
7. Next meeting or checkpoint: When is it, and what must be ready by then?

Constraints:
- Extract only what is in the notes. Do not invent actions.
- If ownership or deadline is unclear, flag it: "Owner unclear — recommend clarifying with [role]."
- "Someone will look into it" is not an action. Reject vague commitments.

Format: Clean action log — structured, specific, usable as minutes output within 10 minutes of the meeting.
```

---

## F. Token-Efficient Claude Hacks

---

### Prompt 28 — 5-Line Prompt Formula

**What it's for:** Converts any vague request into a powerful, precise Claude prompt in five lines.
**Best used when:** Whenever you're about to paste something into Claude and it feels imprecise.

```
Goal: Help me write a powerful, focused prompt for Claude using the 5-line formula.

The 5-line formula:
1. ROLE: Who am I / who is Claude acting as for this task?
2. CONTEXT: What is the situation? (2 sentences maximum)
3. TASK: What exactly do I want Claude to do? (One clear sentence)
4. OUTPUT: What should the response look like? (format, length, structure)
5. CONSTRAINT: What should Claude NOT do or assume? (one line)

My task to turn into a prompt:
[DESCRIBE WHAT YOU NEED HELP WITH]

Output required:
- A clean, ready-to-use 5-line prompt I can paste directly into Claude
- One note on what makes this prompt effective
- One variation if I want a different tone or depth of response

Constraints:
- The prompt must be under 150 words.
- Do not pad it. Shorter and precise beats long and vague.
- Every line must earn its place.

Format: Final prompt in a clear block, ready to copy. Then brief notes.
```

---

### Prompt 29 — Delta Mode Prompt

**What it's for:** Updates Claude with new information without restarting the conversation or re-explaining context.
**Best used when:** Any time you're in a live working session and want to give Claude new information efficiently.

```
Goal: I want to update Claude with new information without restarting our conversation or re-explaining everything.

DELTA MODE — use this prefix at the start of any update message:

---
DELTA UPDATE — do not restart. Layer this onto our previous context.

New information:
[PASTE NEW INFORMATION HERE]

What changed vs. the last update:
[BRIEFLY STATE WHAT IS NEW OR DIFFERENT — one or two sentences]

Updated question or task:
[WHAT DO YOU WANT FROM CLAUDE GIVEN THIS NEW INFORMATION?]

Output rules:
- Respond only to what has changed.
- If nothing has changed on a topic, skip it — no need to restate.
- Flag any new risks or decisions that have emerged from this update.
- Label any new assumptions clearly: "Assumed:".
---

When to use Delta Mode:
- You are continuing a working session
- You have a weekly update to layer onto previous briefing
- You want efficient context-aware responses without repetition

Director principle: A good Claude session is a conversation, not a series of restarts. Build context, don't repeat it.
```

---

### Prompt 30 — No-Fluff Executive Summary Prompt

**What it's for:** Gets a short, sharp executive summary from any document, report, or update — no padding.
**Best used when:** Whenever someone sends you a long document and you need the 2-minute version.

```
Goal: Get a tight, direct executive summary from any input.

Paste this prefix before ANY document, report, email chain, or update you want summarised:

---
Summarise the following for a Senior Director. Apply these rules strictly:

1. Maximum 200 words.
2. Lead with the most important fact or decision — not background or context.
3. Use bullets, not paragraphs.
4. Always include: key finding or conclusion / main risks or flags / recommended action.
5. Omit: all context I already know / all caveats that don't change the action / all filler phrases ("it is important to note", "in conclusion", "it is worth mentioning").
6. If something is uncertain, prefix it with "Assumed:".
7. End with exactly one sentence starting with: "Action needed:" — what I should do now.
8. If there is no action needed, end with: "No action needed — for awareness only."

Content to summarise:
[PASTE DOCUMENT, REPORT, EMAIL, OR UPDATE HERE]
---

Use this every time someone sends you a long document. Set this as a habit for all pre-read materials before meetings.
```

---

### Prompt 31 — Reusable Context Block Builder

**What it's for:** Builds a personal context block you can paste at the start of any Claude conversation — once, for life.
**Best used when:** Set this up once and paste it at the start of every new Claude chat. Saves minutes every session.

```
Goal: Build my personal reusable context block for Claude — so I never have to re-explain who I am or how I work.

Help me build it using this template:

---
CONTEXT BLOCK — paste at the start of any new Claude conversation.

I am: [YOUR ROLE AND TITLE]
Organisation: [COMPANY / BRAND] — [one-sentence description: industry, approximate size, market position]
My function covers: [YOUR KEY AREAS OF RESPONSIBILITY — 4–6 areas]
My current priorities: [TOP 3–5 PRIORITIES — non-confidential version only]
Working style: Direct, structured responses only. No filler or hedging. Lead with the most important point. Flag all assumptions with "Assumed:". Never invent facts.
Default output format: [Your preference — bullets / memo / table / numbered list]
When in doubt: [Any specific instruction, e.g. "Ask me one clarifying question at the end, not before you answer"]
---

Fill in the template:
[ANSWER EACH FIELD ABOVE WITH YOUR OWN INFORMATION]

Output required:
- A complete context block — clean, under 150 words, ready to paste
- A shorter 3-sentence version for quick or casual conversations

Constraints:
- Do NOT include confidential, commercially sensitive, or personally identifying information. This block will be pasted into Claude regularly.
- Keep it under 150 words — the goal is brevity and reuse.

Format: Full version + short version, clearly separated and ready to copy.
```

---

### Prompt 32 — Prompt Compression Prompt

**What it's for:** Compresses a long or unwieldy prompt into something tighter and more powerful.
**Best used when:** When a prompt you've written feels too long, repetitive, or unfocused.

```
Goal: I have a long or complicated prompt. Help me compress it into something shorter and more powerful — without losing the important parts.

My original prompt:
[PASTE YOUR ORIGINAL PROMPT HERE]

Output required:
1. Compressed version — same intent, 50% fewer words
2. What was removed and why (brief note per item)
3. What was kept and why it matters
4. One thing I might have removed that should go back in

Compression rules to apply:
- Remove all filler and preamble ("I would like you to", "please", "could you help me")
- Remove repeated ideas — say it once, precisely
- Tighten every instruction to its core
- Keep: role, task, output format, key constraints
- Remove: over-explanation of obvious things, unnecessary politeness, redundant context, throat-clearing

Constraints:
- The compressed prompt must produce the same quality of output as the original.
- Do not remove critical constraints or output requirements in the compression.
- The compressed version should be under 200 words.

Format: [Original] → [Compressed], with brief change notes.
```

---

### Prompt 33 — "Ask Only Essential Questions" Prompt

**What it's for:** Stops Claude from asking unnecessary clarifying questions that slow you down.
**Best used when:** Any time you want Claude to make progress and give you something to react to, rather than asking for perfect inputs.

```
Goal: Stop Claude from asking unnecessary questions and get it to produce useful output immediately.

Paste this at the start of any session or task where you want fast, useful output:

---
INSTRUCTIONS FOR THIS SESSION — apply these until I say otherwise:

1. Do not ask clarifying questions unless the answer would completely change your entire response.
2. If you need to make assumptions to proceed, make them and label them clearly: "Assumed: [X]."
3. If critical information is genuinely missing, flag it at the END of your response — not before you answer.
4. Proceed with the most reasonable interpretation of my request and deliver a complete response.
5. Maximum one question per response if absolutely necessary. Put it at the end.
6. A useful draft I can react to is more valuable than a perfect prompt you're waiting for.
---

When to use this: Every time you want momentum over perfection. Claude's default is to ask before acting — this overrides that default for the session.

Director principle: You can always correct a draft. You cannot react to a blank page. Get something on paper first — refine from there.
```

---

## G. Confidentiality and Safety

---

### Prompt 34 — Safe Input Sanitiser

**What it's for:** Reviews any content you're about to paste into Claude and flags what should be removed or anonymised first.
**Best used when:** Before pasting any internal document, report, email, or data into Claude.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I want to paste content into Claude and need to check it first.

Goal: Review the content below and flag anything that should be removed or anonymised before I paste it into an external AI tool.

Content to review:
[PASTE THE CONTENT YOU WANT TO SANITISE HERE]

Flag any of the following that appear:
1. Named individuals — staff, customers, suppliers, executives. Suggest replacing with role titles.
2. Exact financial figures that are commercially sensitive. Suggest replacing with ranges or "Approx. RXm".
3. Customer personal data — names, contact details, account numbers, transaction IDs.
4. Confidential strategic plans, pricing strategies, or M&A information.
5. Internal system names, credentials, processes, or vendor details that should not leave the business.
6. Competitor information obtained under NDA or from confidential sources.
7. Staff performance, HR matters, or disciplinary information relating to named individuals.
8. Supplier pricing, contract terms, or negotiation positions.

For each flagged item:
- What it is
- Why it's a risk if shared externally
- Suggested replacement text

Then provide: A sanitised version of the content — same meaning, identifiable or sensitive elements removed — ready to paste.

Constraints:
- Err on the side of caution. Flag anything uncertain.
- Do not change the meaning or the analytical value of the content — only anonymise.

Format: Flagged items list + sanitised version clearly separated.
```

---

### Prompt 35 — Confidential Data Check

**What it's for:** Assesses whether information you're planning to share with Claude is safe to share externally.
**Best used when:** Before any Claude task that involves internal company data, financials, or people.

```
Context: I am a Senior Director at [COMPANY / BRAND] and I want to use Claude to help with a task involving potentially sensitive information.

Goal: Help me assess whether the information I'm about to share is safe to paste into an external AI tool, based on general data protection best practice.

My task and the information I was planning to share:
[DESCRIBE YOUR TASK AND WHAT INFORMATION YOU WERE GOING TO PASTE]

Output required:
1. Risk assessment — one of:
   - LOW RISK: Generally safe to share with appropriate AI tools
   - MEDIUM RISK: Share with caution — anonymise before pasting
   - HIGH RISK: Do not share without explicit approval from your IT / data governance team

2. What specifically is risky and why

3. How to anonymise or adjust the information so it's safe to share

4. What I can safely ask Claude without sharing the sensitive details (reframe the question)

5. Alternative prompt: How can I get the same quality of help from Claude without exposing the sensitive information?

Constraints:
- Apply general data protection best practice — not assumptions about my company's specific policies.
- Remind me that final authority on what can be shared externally rests with my company's IT and data governance policies.
- When in doubt, classify upward.

Format: Risk rating + specific flags + safe alternative prompt I can use instead.
```

---

### Prompt 36 — Public vs Internal vs Sensitive Classifier

**What it's for:** Classifies any piece of information into Public / Internal / Sensitive so you know how to handle it.
**Best used when:** Whenever you're unsure whether it's safe to paste something into Claude or share it externally.

```
Context: I am a Senior Director at [COMPANY / BRAND]. I need to classify information before deciding how to handle it with AI tools.

Goal: Classify the information or content below into PUBLIC / INTERNAL / SENSITIVE, with clear reasoning and handling instructions.

Content to classify:
[PASTE THE INFORMATION OR DESCRIBE IT HERE]

Classification framework — apply strictly:

PUBLIC:
Safe to share externally with no restrictions. Examples: press releases, published reports, general market commentary, already-public information.

INTERNAL:
Can be discussed and shared internally, but should not leave the organisation without approval. Examples: team plans, project updates, non-sensitive operational notes, internal memos.

SENSITIVE:
Must NOT be shared with external AI tools without explicit approval from IT / data governance. Examples: personal data (staff, customer, supplier), financial data under NDA, HR matters, M&A or acquisition information, supplier contract terms, customer data, pricing strategy, system credentials, security information.

Output required:
1. Classification: PUBLIC / INTERNAL / SENSITIVE
2. Reason for the classification — specific, not generic
3. Elements that pushed the classification up (if SENSITIVE)
4. How to handle it: Can I paste it into Claude as-is? What must I remove first?
5. If SENSITIVE: What question could I ask Claude instead, without sharing this content?

Format: Classification + reasoning + handling instructions. Direct and specific.
```

---

### Prompt 37 — "Use Assumptions, Don't Invent Facts" Prompt

**What it's for:** Locks Claude into honest, labelled reasoning — so you can trust its output for high-stakes decisions.
**Best used when:** Any analytical task, risk assessment, financial review, or decision where accuracy is critical.

```
Goal: Instruct Claude to be fully transparent about what it knows, what it's inferring, and what it doesn't know — so I can trust its output for decisions that matter.

Paste this at the start of any session or analytical task:

---
ACCURACY RULES — apply these to every response in this session, without exception:

1. FACTS: Only state something as a fact if it appears in the material I've provided, or is verifiably true based on your training. Label confirmed facts simply — no special prefix needed.

2. ASSUMPTIONS: If you need to fill a gap in my information to complete the task, do so — but label it clearly: "Assumed: [X]." Never present an assumption as a confirmed fact.

3. INFERENCES: If you're drawing a conclusion from incomplete or indirect data, label it: "Inferred from [source]: [conclusion]."

4. UNKNOWN: If you genuinely do not have enough information to answer or assess something, say: "I don't have enough information to confirm this." Do not guess and present it as fact.

5. INVENTED: Never invent specific names, numbers, dates, quotes, case studies, or data points. If I ask for an illustrative example, make clear it is fictional.

6. CORRECTION: If my question or prompt contains an assumption that looks incorrect or inconsistent with the material, flag it before answering: "Note: your prompt assumes [X], but the material suggests [Y]."

These rules override any tendency to appear helpful by filling in gaps confidently. I would rather have an honest, incomplete answer than a confident, wrong one. The value of your analysis depends entirely on me being able to trust it.
---

Use this for: every significant analytical task, risk assessment, project health check, financial review, or decision memo. Make it a habit.
```

---

*37 prompts. One command centre. Built for the way a Senior Director actually works.*
