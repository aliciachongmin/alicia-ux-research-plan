# discovery-research.md

Read this only when the mode is discovery research. Everything here slots into the template in `SKILL.md` — this file does not restate the shared spine.

---

# When this mode applies

Use this mode when the research is about **behaviour, context, workflow, needs, or mental models** — how people currently do something, what gets in their way, what they work around, who else is involved, and what would have to be true for a different approach to fit.

No design (or flow) needs to exist. If the question is really whether an existing artefact is usable, the mode is wrong. Go back to mode selection.

**Discovery does not use threshold criteria.** There is no task outcome or pass/fail condition to benchmark. If a discovery plan contains completion rates or other threshold criteria, re-check the research mode.

---

# Discovery principle

**Discovery should provide structure without pre-specifying the answer.** The plan should make the study comparable and decision-relevant without deciding in advance what participants must reveal. 

Make the team's existing beliefs explicit as assumptions, but do not let them constrain what participants can surface. Prefer concrete accounts of behaviour over hypothetical opinions, and allow unexpected behaviours, needs, constraints, and trade-offs to emerge as fieldwork progresses.

---

# Assumptions going in (optional)

Include this section when the team already holds **beliefs that the research could confirm, challenge, or overturn**. State them upfront so findings are not retrospectively fitted to what the team believed.

Use this framework:

**Assumption → Basis → Evidence to look for**

- **Assumption** — the belief the team currently holds.
- **Basis** — where that belief came from, including existing evidence or an explicit team assumption where no direct evidence exists.
- **Evidence to look for** — what participants might say or do that would support, challenge, or complicate the assumption.
- **Notes (optional)** — only where a specific assumption needs a reading rule, such as how to interpret evidence that could point either way. Leave blank otherwise.

Stated assumptions provide the reference point for the **reinforcing**  ✅ **/ disconfirming** ❌ **/ unexpected** ⚠️ classification in `Data to be captured`. 

**Keep this to 3–6 decision-relevant assumptions.** Include beliefs that could change what the team does if they prove wrong, not every hunch the team holds.

**If the team has no articulated assumptions, skip this section.** Do not manufacture assumptions.

Example:

| Assumption | Basis | Evidence to look for | Notes |
| --- | --- | --- | --- |
| Recipients find it cumbersome to manage vouchers across separate links
 | One-link-per-campaign is legacy UX that has not scaled as the product has grown.

This is also a high-volume support ticket complaint. | **Supports:** Self-built systems for keeping links (pinning, screenshotting, a notes-app list, a vibecoded app for personal use); searching or scrolling to find a link at the point of spending; opening several links to answer one question; asking family or the team to help re-find a link.

**Challenges:** Going straight to a link without searching; treating each campaign as a discrete event with nothing to manage between times; actively preferring separation as a budgeting aid; no vocabulary for the vouchers as a set. | A settled workaround counts as supporting evidence even where the participant does not describe it as painful. Absorbed friction is still friction. Genuine absence looks like no workaround, because none was needed. |

---

# Methodology

Example:

| Row | What goes in it |
| --- | --- |
| Type | Qualitative, semi-structured interviews. Note if it’s contextual, diary-based, or workshop-based. |
| Format |   • In person or remote
  • Moderated
  • Open questions with probes, following the participant's own account |
| Stimulus | Anything shown to prompt discussion — a current workflow, a competitor, a sketch, a card sort.

State that it is a prompt for discussion, not a design under test. Omit the row entirely where there is no stimulus. |
| Notes | During session:
  • Recording, who is scribing, where (Figjam? Notion? Docs?)

After session:
  • Clean up transcripts
  • Affinity mapping
  • Sense making and pattern identification across participants |

Where a stimulus is used, treat reactions as evidence about participants' mental models, expectations, or current behaviour — not as evaluation of the stimulus itself.

---

# Session structure

Ask the user how long the session is, then use that to propose a realistic starting allocation. 

**The allocation is a guide, not a fixed script. Protect the majority of time for concrete accounts of behaviour and the probing that deepens them.** The walk-through establishes context and concrete evidence; probing explores the reasoning, pain points, workarounds, constraints, and things that currently work well.

Where a stimulus is used, take its time from the current-behaviour walk-through rather than probing. Establish the participant's own experience first, so their reaction to the stimulus can be interpreted against that baseline.

| Phase | Duration | What’s happening |
| --- | --- | --- |
| Welcome + Intro | 5% | Context, consent, expectations setting |
| Background interview | 10%  | Role, how they are currently using the product or what other similar products they have used and how they use it |
| Current behaviour | 35% | Walk-throughs of specific recent instances, in sequence |
| Deepening + probing | 35% | Pain points, workarounds, breakdowns, adaptations, trade-offs, and what currently works well |
| Debrief + Wrap | 10%  | Key reflections, anything not covered, final questions, thanks |
| Buffer | 5% | In case of overflow |
| **Total** | **100%** | **Stated session length** |

**The arithmetic:**

1. Apply the percentages.
2. Round each phase to the nearest 5 minutes.
3. Apply the minimums: Welcome + Intro and Buffer are at least 5 minutes each.
4. Reconcile any difference from the stated total against Deepening + probing. Check the total again after adjusting.
5. Discovery sessions are typically 45–60 minutes and conducted remotely, so no break is scheduled. Where a session runs beyond 75 minutes or is held in person, agree a break with the user and subtract it from the total before applying the percentages.

**Example:** For a 60-minute session, the percentages give 3 / 6 / 21 / 21 / 6 / 3. Rounded to the nearest 5 minutes, that is 5 / 5 / 20 / 20 / 5 / 5. Both minimums are already met and the total is 60, so no reconciliation is needed.

If the session is too short to fit the structure, propose what to cut rather than compressing every phase.

---

# Data to be captured

**Capture behaviour in context.** What people do is only meaningful alongside the context in which they do it: what they are trying to achieve, what triggers the behaviour, what constraints they face, what tools or people are involved, and why they make the choices they do.

Where mental models are relevant, capture **how participants describe, categorise, sequence, or explain the system**, not just their opinions about it.

## Structured measures

Discovery is qualitative. Ratings may be used as conversation prompts or for segmentation, but should not be treated as prevalence or outcome measures. Where a scale is used, state what it is measuring and what it will be used for.

## Qualitative evidence

### **Observations to capture (what participants said or did)**

#### Core evidence

- Goals, motivations, and outcomes they’re trying to achieve
- Current behaviours and workflows, in the sequence they actually happen
- Pain points and what triggers them
- Constraints and dependencies that shape what they can do
- Verbatim quotes that capture important evidence or feedback

#### Supporting evidence

Include where relevant:

- Decision points, trade-offs, and priorities
- Workarounds and self-invented processes
- Other people involved and where handoffs occur
- When and where the behaviour occurs
- Language participants use for things the product names differently

#### Evidence classification

Where relevant, classify evidence against the team's stated assumptions:

- **✅ Reinforcing** — consistent with what the team believed, whether that belief was positive or negative
- **❌ Disconfirming** — contradicts what the team believed
- **⚠️ Unexpected** — the team had formed no expectation about this at all

**Classification requires stated assumptions.** Where assumptions are stated but an observation was not anticipated by any of them, classify it ⚠️ Unexpected. Where the plan states no expectations at all, capture observations without classifying them rather than inferring what the team believed.

**The axes are independent.** A workaround the team already suspected is reinforcing; a step everyone assumed was painful turning out to be trivial is disconfirming. Classify observations against the team's stated expectations, not against whether the observation itself is positive or negative.

**Keep observation separate from inference.** Capture what the participant said or did first; record interpretation separately. Where the cause is uncertain, preserve that uncertainty rather than presenting an inference as fact.

**Unexpected evidence is expected in discovery.** Treat it as a candidate for further investigation, not automatically as a finding or a sign of scope failure.

---

# Lens derivation

Use the research questions and evaluation criteria to derive analytical lenses that define what will be compared or looked for across participants. `SKILL.md` sets the count; start at the lower end of that range unless the research questions genuinely require more. A lens should be broad enough to capture variation, but specific enough to guide comparison. 

Lenses are **study-specific scaffolding, not a fixed framework**. Hold them loosely and allow meaningful themes that emerge during fieldwork to supplement or reshape the initial lenses.

In practice:

- **Set the review point explicitly.** State in the plan when the lenses will be reviewed — typically around one-third of the way through fieldwork, leaving enough sessions to adjust probing.
- **Keep the guide aligned.** If a new lens is added, add a corresponding probe to the discussion guide. Record the change in `Working documents` so the lenses and guide stay in sync. If a lens is retired because the evidence challenges an underlying assumption, capture that implication in `Limitations`.

## Worked example — RedeemSG, a government voucher platform

**Research questions**

- **Primary (PQ):** What friction does having separate voucher links for each campaign create for recipients who hold vouchers from more than one campaign?
- **Secondary (SQ1):** How do recipients store their voucher links, and how do they get back to them when they want to spend?
- **Secondary (SQ2):** What do recipients have to do to determine what they have left to spend, and when their vouchers expire?
- **Secondary (SQ3):** What do people do when a new campaign starts while they still have vouchers from an earlier one?

**Lenses**

| Source | What would have to be compared across participants | Lens |
| --- | --- | --- |
| PQ + SQ1 | Where links end up after vouchers are claimed, and how people get back to them when spending | Storage and retrieval |
| PQ + SQ2 | What people have to do to answer “what do I have left, and by when?”, including how many places they check and whether they can answer it at all | Effort to establish state |
| PQ + SQ3 | What changes when campaigns overlap: what gets reorganised, deprioritised, or forgotten | Overlap handling |

The method transfers, not the lens names: **research question → comparison → lens**. Do not carry this example's lens names, participant types, product terminology, or subject matter into a plan for a different product.

- For example: The same move on a hospital shift-handover study: SQ — how do clinicians hand over open cases at shift change? → what would have to be compared is where information is lost between the outgoing and incoming clinician → lens: handover integrity.

---

# Success criteria

> What should we understand about the current state by the end of the study?
> 

**Define the evidence or understanding the study should produce**, rather than what a future design should achieve.

Success criteria should cover both **what works and what doesn’t**, including existing behaviours worth preserving and constraints or trade-offs future designs should account for. 

**Derive these with the user during alignment, not from a formula.** To make them specific:

- **Tie them to the research question and decision i.e. Research question → evidence needed → decision enabled).** Define what evidence the team needs to make or support the decision.
- **Define what the team should be able to do afterwards** — e.g. choose which problem to pursue, size a follow-up quantitative study, or rule an option out.
- **Propose 2 or 3 versions and let the user pick or reshape.** Avoid simply restating the research objectives as success criteria.

## Signal strength

> "How much weight can this finding carry?”
> 

Use this only where the study needs an explicit framework for distinguishing **recurring patterns from isolated observations**.

| Strength | What it means | How it is treated |
| --- | --- | --- |
| **Pattern** | Recurs across [n] of [total] participants, or consistently within a meaningful segment or context | Report as a finding; assess implications |
| **Signal** | Appears in [n] participants, or is strongly evidenced within a relevant segment or context. | Report with scope and confidence |
| **Outlier** | Appears in one participant or one narrow case | Do not generalise; retain if consequential or useful for further research |

Replace [n] and [total] with the actual counts for this study's sample size. Do not leave vague terms such as “most” or “several” in a finalised plan.

**Frequency in a qualitative sample indicates salience, not prevalence; frequency alone also does not determine strategic importance.** A finding can be important because it is widespread, high-impact, consequential to a key segment, or closely tied to the decision the research needs to inform.

---

# Opportunity tagging

**Include this only when the research needs an explicit way to prioritise opportunities.** Do not force opportunity tags onto studies whose output is primarily understanding, mapping, or framing a problem. 

**Where opportunity tagging is used, include signal strength as well.** The Evidence column below refers to pattern / signal / outlier, which are defined there:

| Tag | Evidence | Impact | Meaning | Action |
| --- | --- | --- | --- | --- |
| **O1** | Pattern | High | Well-supported opportunity with meaningful consequences for the primary workflow or research decision | Prioritise |
| **O2** | Pattern / Signal | Moderate | Meaningful opportunity with clear evidence, but lower impact or narrower scope | Explore further |
| **O3** | Signal / Outlier | Low / unclear | Lower-confidence, narrower, or lower-impact opportunity worth retaining | Log for future consideration |

**An opportunity tag cannot exceed what the evidence supports.** A compelling single-participant observation should not be presented as a high-confidence pattern.

**Evidence strength and impact are separate axes.** A rare opportunity can still have high impact. Do not let low frequency alone cause a consequential opportunity to be dismissed.

Adapt the action column to the planning context; do not assume every study produces a roadmap.

---

# Limitations to check for

Check for limitations that materially affect how this particular study's findings should be interpreted. Consider:

- **Sample** — important user segments missing or too few participants to compare them meaningfully
- **Self-report** — participants describing what they do rather than doing it, and what
that is likely to miss
- **Recall** — where the behaviour is infrequent or was last done some time ago
- **Scope** — important parts of the workflow that are not covered by the study
- **Recruitment skew** — participants who agreed to be interviewed differ from those
who did not, particularly on engagement and confidence
- **Salience versus prevalence** — the sample shows what matters to people, not how
common it is