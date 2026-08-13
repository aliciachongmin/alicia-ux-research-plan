---
name: alicia-ux-research-plan
description: Drafts a single, high-level UX research plan in Alicia's house format for either qualitative discovery research or qualitative usability testing, using a consistent process and template while deriving the research questions, evaluation criteria and analysis lenses specifically for each study. Use this skill whenever the user mentions a research plan, study plan, UT plan, discovery research, generative research, user interviews, usability test, research objectives, research questions, participant criteria, screening criteria, or a participant tracker. Also use it when the user says things like "plan a study", "set up some research", "I need to test this flow with users", or asks to review, revise or sanity-check an existing research plan. Use it even when the request sounds small or casual ("just need a quick plan for testing the new checkout flow") — the value is in the structure being the same every time, so a small study still goes through it.
---

# Alicia's UX Research Plan

Turns a defined research need into a single, high-level research plan: every objective
tied to a decision, every criterion justified, nothing invented.

Two modes — **discovery research** and **usability testing**. They share one
spine and diverge in the second half. Concept testing for 0→1 work, quantitative
studies, programme-level plans, discussion guides, recruitment messages and synthesis
are all out of scope; say so rather than stretching either mode to cover them.

This skill works **with** the user. The core of the plan is agreed in conversation
before anything is drafted in full — see Step 4.

---

## Step 1 — Determine the mode

Do this first. A plan in the wrong mode looks perfectly competent and answers the
wrong question.

| Signal | Mode |
|---|---|
| No design exists yet, or the design is not the point; the question is about behaviour, context, workflow, needs or mental models | **Discovery** |
| A design, prototype or live product exists; the question is whether people can use it | **Usability** |
| "Why do people…", "how do they currently…", "what gets in their way" | **Discovery** |
| "Can they complete…", "where do they get stuck", "is the copy clear" | **Usability** |

**Run the mismatch check.** If the user asks for a usability test but the stated goal
is generative — "test the prototype to find out what users want" — say so plainly and
propose the right method before going further. A usability test cannot answer a
discovery question, and drafting one anyway burns a research cycle and the
participants' goodwill.

If the study genuinely does both (a background interview followed by prototype tasks
is common and legitimate), pick the mode that matches the **primary question**, and
note in Methodology that the session opens with a generative segment. Never silently
blend the two second halves.

---

## Step 2 — Intake gate

Do not proceed until these are known. Ask for everything missing in **one batched
round** — not one question at a time.

**Required:**

1. Product or feature, and its current stage
2. **The decision this research informs** — what changes depending on the result
3. Whether a design or prototype exists, and how complete it is
4. Who the participants are, and whether access to them already exists
5. Target number of participants, and any segments they should be compared across
6. Timeline, and any fixed dates
7. Session length, and whether sessions are in person or remote

**Ask if unclear:**

- What is already known or assumed, and from where
- Whether the team holds stated expectations or assumptions the research could
  overturn — this determines whether the plan can carry an evidence classification
- Whether documented design principles or heuristics exist for this surface
- Who is scribing, and what tools are being used for recording and notes
- Incentives, and whether they are approved
- Constraints: language, accessibility, consent and data handling

**Why the gate matters.** A plan written without the decision it informs produces
objectives that are topics rather than questions, and every section downstream
inherits that vagueness.

---

## Step 3 — Read the mode reference

- Discovery → read `references/discovery-research.md`
- Usability → read `references/usability-testing.md`

Read only the one that applies. Carrying both is what causes the two plan types to
bleed into each other.

---

## Step 4 — Align on the core before drafting

**Do not draft the full plan yet.** Five things determine whether the plan is any
good, and all five are cheaper to fix in conversation than in a finished document:

1. The **decision** the research informs
2. The **research question** — the primary question, and the supporting questions
   under it
3. The **success criteria** for the study
4. The mode's **weighting framework** — threshold criteria in usability, signal
   strength in discovery — and whether it applies at all
5. The **starting analysis lenses**

The first two are a pair and lock together before anything else. A question that
serves no decision produces a study nobody acts on; a decision with no question
attached produces a study that cannot inform it.

**Interrogate the question, do not just accept it.** When the user supplies one, check
it out loud:

- **Can this method answer it?** A usability test cannot explain why people behave as
  they do outside the session; interviews cannot establish how often something happens.
- **Is it one question or several wearing a coat?** An "and" joining two clauses is
  fine where both are the same phenomenon at different moments — storing and
  retrieving, balance and expiry. It is a problem where the clauses are different
  kinds of thing, such as a behaviour joined to a mental model.
- **Is it already answered by the spec?** Ask about consequence, effort, friction or
  error, not existence. See the Examples section.
- **Does it ask participants to introspect?** Mental models are inferred from what
  people do, store, call things and get surprised by — never reported directly. Do not
  write a question that asks someone to describe their own model.
- **Does it presuppose its answer?** "Why do organisers find bulk upload confusing"
  assumes they do.
- **Would a plausible finding change the decision?** If every outcome leads to the
  same action, say so.

**Propose, do not interrogate.** Bring a drafted PQ and SQs for the user to react to
rather than asking them to supply questions from scratch — reacting is easier than
generating, and a proposal that is wrong is still useful because it shows what was
misunderstood.

**Say what is weak in the proposal.** If an SQ is really a topic, or two lenses
overlap, or a threshold cannot be supported by the sample, name it rather than waiting
to be caught. Offer the alternative alongside.

**Surface genuine forks, not manufactured ones.** Where there is a real choice, lay
out both and say which is recommended and why. Where there is none, do not invent one.

**Converge.** One or two rounds is usually enough. If the user says to skip ahead and
just draft it, do so — but mark every unresolved item `[ASSUMPTION]` and flag them at
the top of the draft.

---

## Step 5 — Draft against the template

ALWAYS use this section order. Bracketed sections appear only when their condition is
met. Limitations, Logistics and Working documents appear in **both** modes.

```
# [Study name]

## Context
## Decision this informs
## Assumptions going in            [discovery only, optional]
## Design intent and expectations  [usability only, optional]
## Research objectives
## Methodology
## Participants
### Tracker
## Session structure
## Data to be captured
## Analysis framework
## Success criteria
## Threshold criteria              [usability only, where there is a meaningful basis]
## Severity tagging                [usability only, where prioritisation is needed]
## Signal strength                 [discovery only, where the study needs it]
## Opportunity tagging             [discovery only, where prioritisation is needed]
## Limitations                     [both modes]
## Logistics                       [both modes]
## Working documents               [both modes]
```

**Heading levels inside the reference files organise guidance for the model. They do
not determine the output plan.** Section order and heading level come from this
template only. Where a reference file nests one criteria section under another — for
example threshold criteria under success criteria, or signal strength under success
criteria — treat them as the siblings this template shows them to be.

**The second half is conditional in both modes.** A plan may legitimately run Success
criteria → Limitations with nothing in between. Never add a section to fill the shape,
and never invent a threshold, a tag scale or a signal band to justify one.

### Section rules

**Context** — why this research is happening now. What prompted it, what has already
been tried, what the surface is. Two to four bullets or a short paragraph. Where there
is a triggering incident, metric or decision point, name it.

**Decision this informs** — one sentence. What changes depending on the result.

**Assumptions going in / Design intent and expectations** — the mode reference defines
the content. Both use the same three-column shape and both are optional. Where the
team has none, skip the section rather than manufacturing beliefs — and omit the
evidence classification too, per the *Data to be captured* rule below.

**Research objectives** — a single **primary question (PQ)**, blockquoted, plus **up to
three supporting questions (SQ)**, numbered. These are what the *team* needs to learn;
they are never read aloud to a participant. More than three SQs means the study is
unfocused — push back rather than accommodating it, and propose which to cut or which
to promote into the PQ.

**Methodology** — a two-column table. Rows differ by mode; see the mode reference.
Derive every value from the user rather than assuming a default, and mark anything
unresolved `[TBC]`.

**Participants** — target audience, screening criteria, segmentation, target n and how
it splits. **Participants are defined for analytical use, not demographic
completeness:** include only characteristics relevant to the research questions or to
comparisons the study needs to make. Criteria must be screenable — a recruiter or a
screener call should be able to act on them without interpretation.

**Session structure** — ask the user the total session length, then compute each phase
as a percentage of it. The table must add up to the stated total. The mode reference
gives the percentages, the rounding rule, and which phase absorbs the difference.

**Data to be captured** — split structured measures from qualitative evidence. The mode
reference defines both, including the ✅ / ❌ / ⚠️ evidence classification and its
dependency on stated expectations. One rule overrides everything there: **never infer
an expectation the plan does not state.**

**Analysis framework** — three blocks: the derived lenses, an empty emergent themes
block, and the lens review rule. See "Deriving the analysis lenses" below.

**Success criteria** — what makes the *study* successful, not what makes the design
successful: the evidence or understanding the team needs to come away with. Derive
these with the user during alignment, working from the research question and the
decision. A set of success criteria that could be pasted into another study has not
been written for this one.

**Limitations** — specific to this study, and material to how the findings should be
interpreted. Suggest them during planning and add them **only after the user
confirms**. Never add a generic limitation simply because it is possible.

**Logistics** — timeline table with dates, tasks and status; tools and set-up with
named owners; known absences and blockers. Name people where a task has an owner.

**Working documents** — links out to the discussion guide, notes board, synthesis
board, and recruitment messages. Leave as `[TBC]` where they do not exist yet. Do not
draft a discussion guide inside the plan.

---

## Step 6 — Self-check, then deliver

Run this against the draft. Fix what fails; flag what cannot be fixed without more
input rather than papering over it.

- [ ] Mode is correct, and stated
- [ ] "Decision this informs" is one sentence and is genuinely a decision
- [ ] Every SQ ladders up to the PQ; the PQ ladders up to the decision
- [ ] No research question is spec-answerable, asks a participant to introspect, or
      appears verbatim in participant-facing text
- [ ] Participant criteria are screenable, and every criterion has an analytical use
- [ ] Between three and six lenses, each passing the lens tests, and every question
      served by at least one
- [ ] The emergent themes block and the lens review point are both present
- [ ] The evidence classification appears only where the plan states expectations
- [ ] Threshold criteria, where included, have a basis, a "why this target?" and a
      lens behind them; where omitted, the plan says why
- [ ] No conditional section has been added to fill the shape
- [ ] Tracker columns all trace back to the Participants section
- [ ] Timeline includes synthesis and shareback, not just fieldwork
- [ ] Nothing is invented — no fabricated prior findings, participants, quotes,
      metrics, dates or names. Gaps are marked `[ASSUMPTION]` or `[TBC]`

### How to deliver

**Output the full plan as plain text in the conversation.** The user reads and edits it
there. Do not create a file at this stage.

Once the plan is agreed, offer the markdown file: *"Want this as a .md file to paste
into Notion?"* Create the file only if asked.

---

## Deriving the analysis lenses

Use the research questions and evaluation criteria to derive **3–6 analytical lenses**
that define what will be compared or looked for across participants. Do not carry a
fixed list between studies; a set of lenses that would fit any project fits none of
them well.

**Evaluation criteria** means the success criteria plus the mode's weighting framework
— threshold criteria in usability, signal strength in discovery. Both reference files
use this term; it is defined here so it means the same thing everywhere.

A **lens** is a named angle for reading the data: what gets compared across
participants. It is not the same as an **evidence classification**, which is a
property of a single observation. Every observation sits under a lens and carries a
classification.

### Procedure

1. **List everything the study owes an answer to** — the PQ, every SQ, and the
   evaluation criteria.
2. **For each, ask: what would have to be compared or sorted across participants to
   answer this?** That comparison, named, is a lens.
   *SQ: "Is the copy clear enough for admins to understand what's being asked?"
   → every moment someone read a label differently from how it was meant
   → lens: **Interpretation gaps***
3. **Merge overlaps.** Several questions usually converge on one lens.
4. **Consider cross-cutting candidates:** vocabulary (terms participants use
   unprompted versus the product's own terms) and segment differences (only where the
   Participants section defines segments).
5. **Test each lens:**
   - Could it come out differently from what the team expects? If not, it is an
     assertion dressed as analysis.
   - Does it name what to look *for*, not just a topic? "Copy" is a topic; "where
     interpretation diverged from intent" is a lens.
   - Is it broad enough to capture variation, but specific enough to guide comparison?
   - Is it distinct from its neighbours, or a restatement?
6. **Check coverage.** Every research question and the evaluation criteria need at
   least one lens serving them. A lens serving none is curiosity, not research — cut
   it. Not every question needs its own lens; a primary question is often answered
   across several.

### How the criteria constrain the lenses

- **A threshold obliges an explanatory lens.** A completion rate tells the team *that*
  something broke, never *where* or *why*.
- **Success criteria dictate what the lenses must jointly deliver.** If success
  requires understanding what works as well as what breaks, the lenses cannot only
  collect failures. If it requires choosing between options, something has to compare
  them. If it requires prioritised recommendations, something has to capture severity.

### Lenses are a starting frame, not a closed set

Lenses are agreed before fieldwork so the team commits to what it is looking for while
it can still be held to it. But participants raise things nobody planned for, and a
frame that cannot admit them is worse than no frame.

Every plan therefore carries an **emergent themes** block, empty at planning time and
populated during synthesis, plus a review rule stated in the plan:

- Lenses are reviewed at a stated point in fieldwork — the mode reference gives the
  timing.
- Where something recurs that no lens captures, it is added as a lens and dated.
- Where a lens produces nothing, it is retired and that is noted in Limitations. A
  lens that found nothing is itself a finding about an assumption the team held.
- Nothing is revised silently. The gap between what the team went looking for and what
  found them only survives if the changes are recorded.

### Output format

```
## Analysis framework

After all sessions, synthesise by:

| Lens | What to look for | Why it matters | ←→ |
|---|---|---|---|
| [Derived lens] | … | … | PQ + SQ1 |
| [Derived lens] | … | … | SQ2 |

**Emergent themes** — populated during synthesis, not at planning time:

| Theme | First seen | Why it was added |
|---|---|---|
| *(empty at planning time)* | | |

Lenses are reviewed after session [n]. Anything recurring across participants that no
lens captures is added as a lens, dated; anything producing nothing by the end is
retired and noted in Limitations.
```

Where documented design principles or heuristics exist for the surface, derive the
lenses from those rather than from the questions alone, and link the source under the
table. That is the strongest version of this section, because the lenses inherit
meaning the team has already agreed on.

---

## Building the tracker

Output an empty table with a header row, enough blank rows for the target n, and a
one-line note on why each column is there.

**Derive the columns:**

- **Identity field** — a name where participants are recruited individually and by
  name; a code (`P01`, `P02`) where they are screened from a wider pool and need
  anonymising.
- **One column per segmentation variable named in the Participants section.** A
  variable that is not in Participants does not get a column. This is what stops the
  tracker collecting demographics with no analytical use.
- **The logistics that will actually be chased** — status, session date, consent,
  incentive sent, and similar.

Recruiting-by-name studies produce trackers organised around chasing. Screened studies
produce trackers organised around segmentation. The Participants section decides which.

**Never populate the tracker with invented participants.**

---

## House rules

**Voice**

- Third person, present tense. First person only in logistics asides.
- Every target, threshold, criterion and lens carries its own justification — a "Why
  this target?" or "Why it matters" column, not a bare assertion.
- Tables for anything with parallel structure. Bullets rather than paragraphs.
- Bold the load-bearing phrase mid-sentence, not the whole line.
- Explicit caveats where the evidence is thin, rather than quiet confidence.
- Plain language. No research jargon a PM or engineer would have to look up.
- UK/SG spelling: organiser, prioritise, behaviour, synthesise.

**Terminology**

- "Participant", not "user" or "subject", when referring to people in a session.
- ✅ ❌ ⚠️ mean reinforcing, disconfirming and unexpected. Do not reuse them for
  anything else in the plan.

**Never**

- Never invent participants, quotes, prior findings, metrics, dates or names.
- Never infer an expectation or assumption the user has not stated.
- Never write a threshold without a justification.
- Never carry an analysis framework over from a previous study unchanged.
- Never carry a reference file example's lens names, participant types, product
  terminology or subject matter into a plan for a different product.
- Never draft the discussion guide inside the plan.

---

## Examples

These cover the sections where drafts most often come out generic. The difference in
each case is hard to state as a rule, which is why it is shown.

**Decision this informs**

| | |
|---|---|
| **Weak** | *To improve the onboarding experience.* |
| **Sharp** | *Whether merchant onboarding ships in v2.2 as designed, or the flow is restructured before build.* |

The first names an aspiration. The second names a fork, and either branch is a real
outcome the team would act on.

**Research question**

| | |
|---|---|
| **Weak** | *Understand how users feel about the new onboarding.* |
| **Sharp** | *Can new organisers complete merchant onboarding without contacting the team, and where does the current flow force them to ask?* |

The second names who, what outcome, and what would count as failure.

**A question the spec already answers**

| | |
|---|---|
| **Weak** | *Does it matter which campaign a voucher came from?* — yes; campaigns have different purposes and merchants. Settled without fieldwork. |
| **Sharp** | *Where does the campaign distinction need to be visible, and where does it create effort or error?* |

Ask about consequence, effort, friction or error — not about existence.

**Analysis lens**

| | |
|---|---|
| **Weak** | *Copy* — a topic. Every study could list it. |
| **Sharp** | *Interpretation gaps — where a label or instruction was read differently from intent.* |

Falsifiable, and it distinguishes a copy problem from a flow problem.

**Participant criteria**

| | |
|---|---|
| **Weak** | *Organisers who find the current portal difficult.* |
| **Sharp** | *Organisers who have created at least one campaign in the past 6 months, across a mix of campaign types, including 2–3 who have gone through creation 3+ times.* |

The first cannot be screened without a leading question. The second can be checked on
a screener call.

**Limitations**

| | |
|---|---|
| **Weak** | *Small sample size means findings may not generalise.* |
| **Sharp** | *The prototype cannot simulate a failed verification step, so recovery behaviour there is untested. Two of the four organisers approached from the smaller segment declined, so it is represented by agency staff only.* |

Generic caveats add nothing. Specific ones tell the reader what they still do not know.
