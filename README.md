# README.md

# What this skill does

This skill turns a defined research need into a **single, high-level research plan** for either **qualitative discovery research** or **qualitative usability testing**. It uses a consistent planning process and structure, while **keeping the requirements of each research type distinct** and developing the research questions, evaluation criteria, and analytical framework **specifically for each study**.

The process has 3 steps:

1. **Intake gate.** The skill does not start drafting until there is clarity on the **research question** and **the decision the research informs**.
2. **Fixed template.** Every plan follows the same sections in the same order, making the output comprehensive by default and legible to people outside research. It should let a PM, engineer, or stakeholder understand **what is being asked, of whom, why, and what will be done with the answer**. The plan therefore also serves as a briefing document.
3. **A self-check.** Before handing over the plan, the skill audits its own draft. When something cannot be resolved from the available information, it flags the gap rather than smoothing it over or inventing an answer.

This skill is deliberately scoped to the high-level research plan only. Discussion guides, recruitment templates, and research synthesis are handled separately.

---

# Why this exists

Research plans are often created from scratch, making it easy for important considerations to vary or get missed and forcing researchers to repeatedly solve the same structural problems.

A generic template only partially solves this: it creates consistency in format, but can produce plans that are structurally complete without adequately addressing the research problem at hand.

This skill provides the middle ground: **consistency in process, specificity in content, and human judgment where it matters**. The structure and quality bar stay fixed, while the substance is derived from the specific research need.

The result is a repeatable, rigorous, and legible planning process that makes research plans **easier to produce, evaluate, and act on**. Researchers can spend less effort reconstructing the planning process and more on the thinking that is specific to the study, while collaborators get a clear and consistent view of what the research will answer and how its findings will inform a decision.

---

# What this skill covers

| In scope ✅ | Out of scope ❌ |
| --- | --- |
| Single-study research plans | Programme or multi-phase plans |
| Qualitative discovery research | Quantitative studies and surveys |
| Qualitative usability testing | 0→1 concept testing |
| Participant tracker scaffolding | Recruitment messages |
| Analysis framework | Discussion guides |
| —  | Synthesis and reporting |

---

# How to use the skill

Describe the study in 1-2 sentences. Include relevant project context and your rough sense of what you want to learn or understand. 

Examples:

> Help me write a UT plan to test my new merchant onboarding flow — I have 3 features, 6 merchants, and the sessions are spread out over 2 weeks between 1 to 15 October 2026.
> 

> I need a discovery plan to understand how campaign organisers currently obtain bank details to set up their voucher campaigns.
> 

What happens next:

1. **Mode.** It picks `discovery` or `usability` and says which, with a flag if the request looks mismatched (e.g. a usability test asked to answer a generative question).
2. **Intake.** It asks for whatever is missing, in one batch.
3. **Alignment.** It proposes the decision to be made, primary/supporting research questions, success criteria, evaluation criteria, and analysis lenses, then works through them with you before drafting.
4. **Draft**. Once the core is agreed, it writes the full plan as **plain text in the conversation**, so it can be read and edited in place.
5. **File.** If you ask, it packages the agreed plan as a markdown file to paste into Notion.

Anything it had to assume is marked `[ASSUMPTION]` and anything unknown is marked `[TBC]`. Both are meant to be searched for and resolved, not left in.

---

# Branching logic + Output template

**Both modes share the same spine:**

> Context → Decision this informs → Research objectives → Methodology → Participants + Tracker → Session structure → Data to be captured → Analysis framework → Success criteria
> 

**They diverge in the second half, then rejoin:**

| Discovery | Usability |
| --- | --- |
| Assumptions going in (optional) | Design intent and expectations (optional) |
| Signal strength (where the study needs it)

Opportunity tagging (O1, O2, O3) (where prioritisation is needed) | Threshold criteria (where there is a basis)

Severity tagging (P1, P2, P3) (where prioritisation is needed) |
- The second half is conditional in both modes. A plan may legitimately run Success criteria → Limitations with nothing in between. Do not add a section to fill the shape.
- Threshold criteria are included only where there is a meaningful basis for them. Where there is none, the section is omitted and the plan says why. Discovery does not use threshold criteria; signal strength plays the equivalent role.
- Opportunity tags cannot exceed what signal strength supports. An opportunity resting on a single participant cannot be O1, however compelling the session was.

**Every plan ends with the following sections:**

> Limitations  → Logistics → Working documents
> 

---

# Analysis framework

The analysis framework is **study-specific. Lenses are derived fresh for each study rather than pulled from a fixed list**; they are agreed before fieldwork but are **not a closed framework**. This gives the team a deliberate starting frame for interpreting the data without limiting what participants can surface.

A lens is **a named angle for reading the data — what is compared or looked for across participants**; for example, “interpretation gaps” is a lens, while “copy” is a topic.

The skill derives a small set of lenses from the **research questions and evaluation criteria**, working backwards from what the study needs to answer. Where established design principles or heuristics exist for the surface, use them as the basis for the relevant lenses and link the source.

Each observation collected under a lens also carries an evidence classification — see the next section.

Meaningful themes that emerge during fieldwork are captured in an emergent themes block, kept separate from the lenses agreed beforehand so the distinction between what the team looked for and what participants surfaced stays visible.

---

# Evidence classification

Lenses are one dimension; evidence classification is the other. **Every observation sits under a lens and carries a classification:**

- ✅ **Reinforcing** — consistent with what the team believed, whether that belief was positive or negative
- ❌ **Disconfirming** — contradicts what the team believed
- ⚠️ **Unexpected** — the team had formed no expectation about this at all

Classification is against the team's stated expectations, not against whether the observation is positive or negative. It applies in both modes, against “Assumptions going in” in discovery and “Design intent and expectations” in usability. Where the plan states no expectations, the classification is omitted rather than guessed at. Discovery runs heavier on ⚠️ than usability does, and that is the mode working as intended.

---

# Participants and the tracker

**Participants are defined for analytical use, not demographic completeness.** Include only characteristics relevant to the research questions or to comparisons the study needs to make.

The tracker follows from that. The skill outputs an empty table with derived column headers and a one-line note on why each column is there. Columns come from the Participants section: an identity field (a name where people are recruited individually, a code like `P01` where they are screened from a wider pool), one column per segmentation variable named in Participants, and the logistics required for tracking.

A variable not in Participants does not get a column to prevent the tracker from collecting demographics with no analytical use. It never populates the table with invented participants.

---

# Files

```
alicia-ux-research-plan/
├── SKILL.md                        the workflow, template and standards
├── references/
│   ├── usability-testing.md        usability-specific sections and guidance
│   └── discovery-research.md       discovery-specific sections and guidance
└── README.md                       this document
```

- **README** → ****explains what the skill is and how it branches
- **SKILL.md** → defines the shared planning machinery and template
- **references/discovery-research.md** → defines what changes when that machinery is applied to discovery
- **references/usability-testing.md** → defines what changes when that machinery is applied to usability testing
- **future discussion-guide skill** → defines how to conduct and probe the session

The reference files are read by the skill, not by you — one at a time, depending on mode. Keeping them separate is what stops a discovery plan arriving with task completion thresholds attached.

---

# Refining it

The parts most likely to need adjustment after real use:

- **Signal strength counts** in discovery mode. The pattern / signal / outlier bands
are set as rules of thumb; they should be tuned to the sample sizes actually run.
- **Severity and opportunity tag actions**, which currently assume a launch and a
roadmap. Continuous delivery needs a different mapping.
- **Session structure proportions**, which are starting points rather than house
standards.
- **The examples in SKILL.md**, which are the fastest lever on output quality. Adding
a paired good and bad example to a section is usually more effective than adding
another rule.

Changes go in `SKILL.md` for anything shared, or the relevant reference file for
anything mode-specific.