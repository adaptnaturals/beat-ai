# Beat the AI Challenge Brief
<!-- listing: title="Growth Marketing Manager — Adapt Naturals"; difficulty="Hard" -->

> *All account figures in this challenge are illustrative, created for this exercise, and don't represent Adapt Naturals' actual metrics. Publicly available facts about the company are genuine.*

## Growth Marketing Manager — Adapt Naturals

**Company:** Adapt Naturals
**Role:** Growth Marketing Manager
**Challenge Format:** Final-round take-home
**Estimated Effort:** 6–8 hours
**Deadline:** 7 calendar days from receipt

---

## About This Challenge

At Adapt Naturals, we live by "test, don't guess" — including in hiring.

This challenge is the final round of our process. It's designed to evaluate the exact work you'd do in your first 30 days: read an unfamiliar ad account, find what's actually going on beneath the blended numbers, and turn that into a disciplined testing roadmap.

**Claude (Anthropic's AI) has already completed this exact brief**, with the same data packet, the same instructions, and the same time budget. Its output is our baseline. Three reviewers score every submission blind against Claude's, and the majority decision stands. **Ties don't advance.**

That's not a gimmick. This role requires using AI daily to accelerate your work — so the bar for what you personally add on top of AI is real, and we test for it directly.

---

## About Adapt Naturals

Adapt Naturals is a supplement brand dedicated to helping people feel and perform their best through premium, evidence-based nutritional supplements. Founded by Functional Medicine clinician and bestselling author Chris Kresser, we combine cutting-edge science with the wisdom of nature to create clinician-grade products thoroughly tested for quality, purity, and effectiveness.

We're a lean, remote, async-first team that prioritizes results over schedules and profits over vanity metrics. This role owns paid acquisition execution across Meta, Google, and emerging channels, reports to the Head of Growth, and serves as the analytical hub of the growth team.

---

## The Situation

It's your first Monday as Growth Marketing Manager at Adapt Naturals. The Head of Growth has been running the account alongside two other jobs and hasn't had time to look closely in weeks. Your onboarding message reads:

> *"Data packet attached — last 90 days across Meta and Google, plus our pixel health tracker and a UTM sample. The internal marketing meeting is Monday at 11am ET and I need your read on the account before it. Blended MER looks fine, so leadership thinks everything is fine. I'm not so sure. Tell me what's actually going on, what you'd do about it, and what we should be testing next. Written, async — you won't get a call to talk it through."*

Everything you need is in the **data packet** (`data/growth-marketing-manager/`):

- `meta_daily.csv` — 90 days of ad-level Meta performance
- `google_daily.csv` — 90 days of campaign-level Google performance
- `emq_weekly.csv` — weekly pixel event match quality
- `utm_audit_sample.csv` — live destination URLs from both platforms
- `business_context.md` — unit economics, metric definitions, and current company targets. **Read this first.** Every recommendation you make should tie back to these numbers.

Analyze the data however you like — spreadsheets, Python, AI tools, anything. We're scoring your thinking, not your typing.

---

## Part 0: Operator Note (gate — read first)

**Under 250 words.** Before anything else, tell us:

- The largest Meta budget you've **personally** managed hands-on (monthly spend, brand type, subscription or not)
- The specific result: what happened to nCPA, MER, or scale, over what timeframe
- One decision you got wrong in that account and what it taught you

We read this first. If it doesn't clear our bar, we don't read the rest. If you can't make the case in a few sentences, this isn't your role.

---

## Part 1: Account Diagnosis & the Monday Narrative (30%)

Write the performance narrative you'd deliver to the internal marketing meeting: what's actually going on in this account, and why.

**Your diagnosis must include:**

- **The findings, ranked by revenue impact.** There are real problems and real risks in this data that blended MER hides. Find them. For each: the evidence (show the numbers), why it's happening (your best hypothesis), and what it's costing or risking (rough math is fine — show it).
- **What's genuinely working** that leadership should protect.
- **The "WHY" behind topline movement.** Blended aMER moved over this period. Decompose the movement: how much is mix, how much is creative, how much is measurement? Be careful — at least one thing that looks like a performance problem isn't, and at least one thing that looks fine isn't.
- **Your first five moves**, in order, with expected impact against the company targets in `business_context.md`.

**Format:** This is a written async narrative for a leadership audience — the exact artifact you'd produce weekly in this role. Clear, skimmable, numbers-backed. Charts welcome.

---

## Part 2: Creative Testing Program (20%)

Design the creative testing system you'd run at Adapt Naturals, using the account data to ground it.

**Must cover:**

- **Budget architecture:** how you'd get testing to 20% of spend, and what you'd pull back to fund it. Reference what the data says about current testing investment.
- **Cadence and volume:** weekly launch rhythm to sustain ~20+ new concepts/month with a lean team and a single creative strategist.
- **Winner/loser criteria:** the specific promotion and kill rules (metrics, thresholds, minimum spend/time) tied to aMER — and how you'd avoid promoting a false winner. At least one ad in this account looks like a winner and isn't. Name it and show why.
- **Concentration discipline:** the account has a single-ad concentration rule (see `business_context.md`). Assess the current state and define how you'd manage it — including when the exception should apply and when it shouldn't.
- **Five creative hypotheses** you'd brief next, grounded in either the account data or a review of Adapt Naturals' and 2–3 competitors' live ads in [Meta Ad Library](https://www.facebook.com/ads/library/). Each: hypothesis, format, and the signal that would make it a winner.

---

## Part 3: Tactical Roadmap & Channel Diversification (20%)

**3A — Meta tactical testing roadmap.** Six tests you'd run over the next quarter (think: optimization events, attribution windows, value rules, campaign structure, audience inputs). For each: hypothesis, design, primary metric, success/kill criteria, and sequence — what must run before what, and why. Not a listicle; a roadmap.

**3B — Diversification plan.** Non-Brand SEM + Shopping needs to reach 25% of the media mix at ≥ 0.85 aMER. Using the Google data: where is that channel today, what's in the way, and what's your 90-day ramp plan? Take an explicit position on the Brand Search budget — the data has something to say about it.

**Every recommendation must show the CAC:LTV math.** The unit economics are in `business_context.md`. Tell us how each move affects nCPA, payback, and contribution — not just channel-level ROAS.

---

## Part 4: Martech & Signal Health Audit (10%)

The packet includes `emq_weekly.csv` and `utm_audit_sample.csv`.

- **Diagnose** what happened to signal quality over this period, when, and the most likely cause given the timeline in `business_context.md`.
- **Quantify** the blast radius: what does this do to reported performance, optimization quality, and your ability to trust the rest of the data? Which of your Part 1 findings does it complicate, and how did you disentangle them?
- **Fix plan:** the concrete steps to resolution within 5 business days, and the monitoring you'd put in place so it never takes weeks to notice again.
- **UTM hygiene:** list every problem in the UTM sample and the naming convention you'd enforce instead.

---

## Part 5: AI-Native Workflow (15%)

This role uses AI daily. Show us — **proof, not promises.**

- **Three real examples** of how you use AI in paid acquisition work **today**. For each: the tool, the workflow it accelerates or replaces, and an artifact (screenshot, link, or output sample). Artifacts go in the appendix. If you can't show the artifact, don't list the example.
- **This challenge as evidence:** tell us how you used AI on this brief — what it did well, where it failed you, and what you added that it couldn't.
- **3–5 of your best prompts** for media-buying tasks, with notes on when you use each.
- **A clear point of view** on where AI should *not* replace human judgment in paid acquisition.

---

## Part 6: Presentation & Communication (5%)

- **Clarity:** organized, skimmable, professional. We're an async-written culture — this is a core job skill, not a formality.
- **Commercial framing:** every observation tied to dollars, targets, or risk — not aesthetics.
- **Rigor:** math shown, assumptions stated, thresholds justified.
- **Attention to detail:** typos and sloppy numbers count against you. Media buying is a precision discipline.

---

## What We're Evaluating

| Criteria | Weight |
|----------|--------|
| Account Diagnosis & Monday Narrative | 30% |
| Creative Testing Program | 20% |
| Tactical Roadmap & Channel Diversification | 20% |
| Martech & Signal Health Audit | 10% |
| AI-Native Workflow | 15% |
| Presentation & Communication | 5% |

**Specifically, we're looking for:**

- The instinct to distrust blended metrics and decompose them
- Statistically honest testing discipline — thresholds, minimum volumes, pre-registered kill criteria
- Subscription economics fluency — decisions framed in nCPA, LTV payback, and contribution, not platform ROAS
- Signal-health literacy — most media buyers never check; the good ones check monthly; we check before trusting any number
- AI genuinely embedded in how you work, plus a clear view of its limits
- Written communication a lean leadership team can act on in five minutes

## What We're NOT Looking For

- Generic media-buying playbooks that could apply to any account
- A findings list with no ranking, no math, and no "so what"
- "Scale what's working, cut what isn't" without defining *working* at the right level of the funnel
- Testing roadmaps that ignore sequencing and interaction effects
- A list of AI tools without demonstrated usage
- Hedge-everything analysis. The Head of Growth needs calls, not caveats. Make a call; show what evidence would change your mind.

---

## How to Submit

- **Format:** PDF or Google Slides, **max 10 pages** (plus up to 2 pages of appendix for Part 5 artifacts — appendix doesn't count toward the limit but must contain evidence, not new argument)
- **Email:** `careers@adaptnaturals.com` with subject line: `Beat the AI — GMM — [Your Name]`

**Include in your email:**

- A **Loom video (≤7 minutes)** walking through your Monday narrative and your top three roadmap bets
- Your **expected compensation**

**Ground rules:**

- **Deadline:** 7 calendar days from receipt.
- **No AI ban.** Use whatever tools you'd use on the job. We're scoring your thinking, not your typing.
- **Confidentiality:** all figures in the data packet are illustrative. Treat them as if real; don't share or publish your analysis externally.
- Your submission is used for evaluation only — we will never use candidate work commercially.

---

## Final Note

This challenge mirrors your actual first Monday in the seat. We designed it that way on purpose — we want to see how you read an account, how you rank what matters, and whether your Monday narrative would make a lean team smarter or just longer.

Claude's baseline was generated with the same brief, the same data, and the same deadline pressure you're reading under now. It's good. To advance, yours needs to be better.

**Ties don't advance. Good luck.**

---

*Adapt Naturals · adaptnaturals.com*
