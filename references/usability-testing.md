# usability-testing.md

Read this only when the mode is usability testing. Everything here slots into the template in `SKILL.md` — this file does not restate the shared spine.

---

# When this mode applies

A design, prototype, or live product exists, and the question is whether people can use it — whether they can complete tasks, find what they need, understand and navigate the interface, interpret the copy, know what to do next, where they struggle or stall the most, and/or which version works better.

If no artefact exists to react to, the mode is wrong. Go back to mode selection.

---

# Design intent and expectations (optional)

Include this section where the team already holds **beliefs about how the design should perform**. State them upfront so findings are not retrospectively fitted to what the team believed. 

Use this framework:

**Expectation → Basis → Evidence to look for**

- **Expectation** — what the team believes about the design: what it was meant to fix, which screens or steps are risky, what should feel straightforward.
- **Basis** — where that belief came from, including existing evidence or an explicit team assumption where no direct evidence exists.
- **Evidence to look for** — what participants might say or do that would support, challenge, or complicate the expectation.

**Keep this to 3–6 decision-relevant expectations.** 

Stated expectations provide the reference point for the **reinforcing**  ✅ **/ disconfirming** ❌ **/ unexpected** ⚠️ classification in `Data to be captured`. 

**If the team has no articulated expectations, skip this section.** Do not manufacture expectations.

Example:

| Expectation | Basis | Evidence to look for | Notes |
| --- | --- | --- | --- |
| Campaign organisers can find every setting for their campaign from the top-level navigation tabs, without being told where to look | The new IA flattens everything to one layer of navigation. The old portal had two — a side nav plus a second level buried inside each tab. | **Supports:** Organisers move to the right tab on the first attempt; they can say what they expect to find in each tab before opening it; they locate a setting they have not used before without prompting.

**Challenges:** Opening two or three tabs to find one setting; asking where something lives; expecting a setting in a tab that does not hold it; finding it only via search or a link elsewhere in the flow. | Getting there eventually is not the same as findability. Note whether the first move was correct, not just whether the task was completed.

Organisers familiar with the old portal may succeed by transferring a mental model rather than reading the new IA — check against prior-experience segment. |

---

# Methodology

Prototype fidelity constrains what the study can claim, so do not assume what the artefact can support.

Example:

| Row | What goes in it |
| --- | --- |
| Type | Qualitative, semi-structured usability test. Note if it’s comparative. |
| Format |   • In person or remote
  • Moderated
  • Think-aloud, targeted probing at specific screens |
| Prototype | What it is, how complete is the prototype, what it cannot simulate.

Say whether participants can enter their own data, and what the fallback is if not or why it might not be necessary. |
| Notes | During session:
  • Recording, who is scribing, where (Figjam? Notion? Docs?)

After session:
  • Clean up transcripts
  • Affinity mapping
  • Sense making and pattern identification across participants |

Where the prototype is customised per participant, say so and name the fallback.

---

# Session structure

**Ask the user how long the session is**, then compute the phases from that total. 

Use the session length to propose a realistic allocation across background, testing, debrief, and buffer. Prioritise testing time; don’t remove background context entirely, as it helps interpret participant behaviour. Also, don’t compress every phase just to fit a fixed formula.

| Phase | Duration | What’s happening |
| --- | --- | --- |
| Welcome + Intro | 5%  | Context, consent, expectations setting |
| Background interview | 25% | Current workflow, prior experience, pain points |
| Break (for in-person sessions over 60 minutes) | TBD | — |
| Prototype testing | 55%  | Factor in for number of tasks, including pausing to probe on specific screens |
| Debrief + Wrap | 10% | Key reflections, overall ratings, anything not covered, final questions, thanks |
| Buffer | 5% | In case of overflow |
| **Total** | **100%** | **Stated session length (excluding breaks)** |

**The arithmetic:**

1. Where the session is in person and runs longer than 60 minutes, add a break. Agree its duration with the user, then subtract it from the total before applying the percentages.
2. Apply the percentages.
3. Round each phase to the nearest 5 minutes.
4. Apply the minimums: Welcome + Intro and Buffer are at least 5 minutes each.
5. Reconcile any difference from the stated total against Background interview. Check the total again after adjusting.

**Example:** For a 90-minute in-person session with a 5-minute break, 85 minutes remain, giving 4.25 / 21.25 / 46.75 / 8.5 / 4.25. Rounded and reconciled, this becomes 5 / 20 / 45 / 10 / 5, plus the 5-minute break — 90 minutes in total.

If the session is too short to fit the structure, propose what to cut rather than compressing every phase.

---

# Data to be captured

## Structured measures

- Task completion, with completion defined as completing without moderator intervention
    - Moderator intervention is when the moderator **steps in to help a participant recover from being stuck, clarify what to do next, or get back on track**. Neutral probing or clarification that the participant can act on independently does not count, but should be noted as uncertainty or potential confusion.
- Post-task confidence and ease (1–5)
- Overall confidence and ease (1–5)
- Comparative ratings, where relevant

Anchor every rating scale in the plan (1 = very uncertain → 5 = very confident; 1 = very difficult → 5 = very easy)

## Qualitative evidence

### **Observations to capture (what participants said or did)**

- Positive signals — things that worked or prompted a confident reaction
- Pain points and hesitation
- Misinterpretation or unclear moments
- Help-seeking and recovery behaviour
- Verbatim quotes

### **Classify each observation against what the team expected going in**

- **✅ Reinforcing** — consistent with what the team believed, whether that
belief was positive or negative
- **❌ Disconfirming** — contradicts what the team believed
- **⚠️ Unexpected** — the team had formed no expectation about this at all

**Classification requires stated expectations.** Where expectations are stated but an observation was not anticipated by any of them, classify it ⚠️ Unexpected. Where the plan states no expectations at all, capture observations without classifying them rather than inferring what the team believed.

**Keep observation separate from interpretation.** Capture what participants did or said before assigning a cause or implication. Where the cause is uncertain, preserve that uncertainty rather than presenting an inference as a finding.

The two axes are independent: **a predicted pain point is reinforcing, while a smooth flow where the team expected trouble is disconfirming.** This classification helps surface what the evidence changes or reinforces, rather than reducing synthesis to a list of things that happened.

---

# Lens derivation

Use the research questions and evaluation criteria to derive analytical lenses that define what will be compared or looked for across participants. `SKILL.md` sets the count. Where established design heuristics exist, prefer those as the basis for the lenses.

## Worked example — RedeemSG, a government voucher platform

**Research questions**

- **Primary (PQ):** Can campaign organisers create and manage a campaign end-to-end on the new admin portal without support from the team?
- **Secondary (SQ1):** Are the portal’s information architecture, navigation, and flow logic intuitive enough for users to orientate themselves and complete tasks without prompting?
- **Secondary (SQ2):** Are the copy and terminology clear and consistent enough for users to correctly understand what is being asked at each step?
- **Secondary (SQ3):** Do users know where to find help when they are uncertain, and do the available affordances give them enough confidence to course-correct?

**Lenses**

| Evaluative question | Source | What would have to be compared across participants | Lens |
| --- | --- | --- | --- |
|   • Can they complete the task? 
  • Where do they struggle or stall the most? | PQ | Where in the sequence people stall, backtrack, take an unintended path or fail to finish, and where those points cluster | Stage-of-flow breakdown |
|   • Can they find what they need to find?
  • Can they understand how to navigate and interact? | SQ1 | Whether entry and exit points are located without prompting, and whether controls are recognised and behave as expected when used | Findability and interaction legibility |
| Is the copy clear? | SQ2 | Every moment a label or instruction was read differently from intent | Interpretation gaps |
| Do they know what to do next? | SQ3 | Whether people can state the next step unprompted, and what they do when they cannot | Next step certainty and help-seeking |
| Does one version work better than the other? | — | NA; this study is not comparative | —  |

The method transfers, not the lens names: **research question → comparison → lens**. Do not carry this example's lens names, participant types, product terminology, or subject matter into a plan for a different product.

- For example: the same move on an airline seat-selection flow: **SQ** — do travellers understand which seats cost extra, and why? → what would have to be compared is *what travellers believe about each seat's price and restrictions before they commit, versus what is actually true* → lens: **pricing comprehension**.

---

# Success criteria

> “What do we need to learn for this study to be useful?”
> 

Define the **evidence or understanding the study should produce**, rather than what the design itself should achieve.

Success criteria should cover both **what works and what doesn’t**, so the research identifies strengths to preserve as well as issues to address.

**Derive these with the user during alignment, not from a formula.** To make them specific:

- **Tie them to the research question and decision.** Define what evidence the team needs to make or support the decision.
- **Define what the team should be able to do afterwards** — e.g. prioritise fixes, choose between options, or decide whether another round is needed.
- **Propose two or three versions and let the user pick or reshape.** Avoid simply restating the research objectives as success criteria.

## Threshold criteria

> “What evidence would change or reinforce our decision?”
> 

Define **specific benchmarks for interpreting findings and informing decisions**. These might include task completion, confidence, comprehension, or other study-specific outcomes.

Thresholds should be grounded in the **decision they inform** and realistic for the study design. With small samples, treat numerical thresholds as **directional signals, not statistical pass/fail gates**: they indicate the direction of evidence rather than precisely quantify user behaviour, and state this caveat in the plan itself.

**Do not invent thresholds simply to make the plan more quantitative.** If there is no meaningful basis, omit it and explain why.

When thresholds are included: 

- One row per criterion, with the columns: **Criteria | Target | Why this target?**
- The **“why”** must be grounded in the flow’s complexity and participants’ familiarity, not convention.
- **Tie every threshold to an analytical lens.** A number tells you that something happened; the lens helps explain why.

---

# Severity tagging

Include a prioritisation framework for findings. Use P1/P2/P3 when appropriate.

| Tag | Severity | Meaning | Action |
| --- | --- | --- | --- |
| **P1** | High | Blocker — participant cannot proceed or completes task incorrectly | Must fix before launch |
| **P2** | Moderate | Significant friction — causes confusion or hesitation, but participant recovers | Should fix before launch |
| **P3** | Low / unclear | Minor — a small rough edge that does not impede the task; nice to fix but need not be a priority | Nice to have or log for a later iteration |

A single-participant observation should not be tagged P1 on frequency alone; be explicit about how many participants had a particular observation.

**Evidence strength and severity are separate axes.** A rare issue can still have severe consequences. Do not let low frequency alone cause a consequential issue to be dismissed.

**Adapt the action column to the release context** — e.g. “before launch” for a launch-based release or sprint priority for continuous delivery.

---

# Limitations to check for

Check for limitations that materially affect how this particular study's findings should be interpreted. Consider:

- **Sample** — important user segments missing or too few participants to compare them meaningfully
- **Prototype / product fidelity** — important behaviours or flows that cannot be tested as they will work in the real product
- **Scope** — important parts of the experience that are not covered by the study
- **Prior familiarity** — participants' existing knowledge or experience could materially affect their behaviour