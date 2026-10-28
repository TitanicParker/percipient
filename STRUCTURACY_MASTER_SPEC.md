# STRUCTURACY — Master Grammar, 54-Cell Atlas, GPT-D, and Game Contract

**Version:** 0.1 — repository-ready baseline  
**Status:** Source-faithful compilation and proposed game contract; original source texts are preserved in the marked sections.  
**Source of truth:** `PERSISTENCE_COORDINATOR_GPT_UPDATED.md` (working conjunction update supplied 28 October 2026); for formal reconciliation use the canonical control document in `TitanicParker/fiche-ceathar`.  
**Purpose:** To let a human or GPT know the entire structural game system in advance, and to run GPT-D as a separate, human-facilitated derivation instrument.

## 0. The distinction between repository and website

This Markdown document is **repository reference material**, not game-page content. A website must **explicitly select** which data to render. The site's HTML/JavaScript must not import, display, embed, or expose the GPT-D prompt in its UI or browser bundle. A GPT with repository-reading access can read this file and extract the prompt; a human can copy it to a separate GPT session.

**Security boundary:** if the GitHub repository is **public**, its files (including this one) are public even if the website does not render them. Excluding the prompt from the website is presentation separation, **not secrecy**. If the exact prompt must be confidential or proprietary, store it in a separate **private repository**, not in public source or a public Pages deployment.

## 1. What the game teaches

A sentence is treated as one completed intelligible event with one unified structural coordinate. The purpose of the game is to teach **precise discernment and articulation of structural differences**, through repeated sentence comparisons and controlled, glossary-grounded multiple-choice answers. The game does not require players to memorise cell numbers or names before they can learn.

The primitive grammar contains **15 definitions in total**: **3 governing dimensions** and **12 value definitions** (6 transformation patterns + 3 completion topologies + 3 persistence modes). Dimensional Conjunction is a binding rule, **not a sixteenth definition or fourth axis**.

Every round must present two sentences assigned to coordinates differing in **exactly one** of the three axes. The question is: **“What does the second sentence change about the first?”** The correct answer describes the specific value-to-value structural change, while the other two values remain fixed. Answer choices paraphrase genuine distinctions from this glossary; distractors must be plausible but wrong **for the presented comparison**, not invented nonsense.

The source corpus of 540 authored examples (10 under each of 54 cell headings) is the **initial intended-assignment game corpus**, not a claim that every individual sentence was independently verified. The game may rely on the founder's assignments as its authored rule set, without invoking GPT-A or GPT-B for every game round. Neither GPT-A nor GPT-B is a prerequisite for a playable product.

## 2. Fifteen primitive definitions (verbatim from supplied working coordinator)

## 3.1 The three primitive dimensions

1. **Transformation Pattern** — Specifies what kind of unresolvedness is altered between the opening and completed situation.
2. **Completion Topology** — Specifies the structural shape by which the transformation counts as complete.
3. **Persistence Mode** — Specifies how the achieved completion remains available for subsequent uptake.

## 3.2 Transformation Pattern values

4. **Differentiation** — A difference that was unavailable, flattened, conflated, or non-operative becomes determinate enough to matter.
5. **Opening** — Availability, reach, continuation, access, or possibility becomes greater than it was under the opening constraint.
6. **Relating** — A bearing, dependency, correspondence, ordering, reciprocity, or mutual determination becomes constitutive of the situation.
7. **Repair** — An organization that fails relative to an operative criterion is changed so that the misfit or fault no longer governs the result.
8. **Integration** — Separate parts acquire determinate roles through organization into a whole and thereby gain structure, mutual support, or joint capacity.
9. **Settlement** — A live demand for further uptake, choice, explanation, completion, adjudication, or continuation is discharged.

## 3.3 Completion Topology values

10. **Focal** — The transformation becomes complete because completion gathers around one privileged locus. That locus is constitutive of why the transformation counts as complete.
11. **Distributed** — The transformation becomes complete only across a constitutive plurality, span, sequence, range, reciprocal field, set of cases, or system. No single locus is sufficient by itself.
12. **Release** — The transformation becomes complete because something that previously governed the situation loses its determining force. Release means de-governance, not merely removal, absence, negation, separation, physical movement away, or negative wording.

## 3.4 Persistence Mode values

13. **Standing** — The achieved determination itself remains available as the completed result.
14. **Bearing** — The achieved result remains what it is only through a constitutive relation, dependency, contrast, condition, source, proportion, frame, support, or mutual determination.
15. **Efficacy** — The achieved result remains as an accomplished capacity, operative effect, changed continuation, rule, function, or consequential difference in what can happen.

---

## 3. Dimensional Conjunction — the meaning of a cell (verbatim)

**Dimensional Conjunction is not a fourth dimension.**

It is the rule by which Transformation Pattern, Completion Topology, and Persistence Mode mutually determine one cell.

A coordinate is written:

`Transformation Pattern × Completion Topology × Persistence Mode`

The notation locates a position in the grammar. It does **not** mean:

`Transformation characteristic + Topology characteristic + Persistence characteristic`

The three dimensions are simultaneous relational constraints upon **one completion-event**.

At cell level, none of the dimensions contributes an independent detachable property. Instead:

- the **Transformation Pattern** is realized only as that transformation becomes complete through this Topology and exists as achieved in this Persistence Mode;
- the **Completion Topology** is the topology specifically of this Transformation in this Persistence Mode;
- the **Persistence Mode** is the persistence specifically of this Transformation completed through this Topology.

Each dimension therefore constrains how the other two can be realized.

Their conjunction is **reciprocal determination**.

The resulting cell has **one unified characteristic**.

> **The coordinate is a constraint that generates the form, not a description of three properties possessed by the form.**

## 4.1 Non-Cartesian rule

The coordinate space is mathematically indexable as `T × K × P`, but its semantics are not additive or Cartesian.

There is no valid semantic derivation:

`Transformation → Topology → Persistence`

There is no first, second, or third dimension in deriving a cell. All three constraints operate simultaneously.

Do not derive one dimensional result and then modify, qualify, pluralize, release, preserve, relate, or activate it with another dimension.

## 4.2 Non-operator rule

No dimension is an operation performed upon another dimension.

In particular:

- **Focal** does not simply select one already-completed object or distinction.
- **Distributed** does not simply pluralize an already-completed form.
- **Release** does not release, cancel, weaken, undo, or negate the Transformation Pattern.
- **Standing** does not simply preserve an already-completed result.
- **Bearing** does not merely add a relation to an otherwise complete result.
- **Efficacy** does not merely add usefulness, later action, or an external consequence.

A coordinate must remain fully a form of its Transformation Pattern regardless of Topology or Persistence Mode.

What counts as the focal locus, distributed field, released governance, standing determination, constitutive bearing, or efficacy must be resolved **within the unity of that cell**.

## 4.3 Relational-field rule

A cell is constrained partly by what neighboring cells cannot be.

Changing one coordinate dimension while holding the other two fixed should change the identity of the completion, not merely substitute predictable vocabulary.

Neighboring coordinates may therefore be used as **negative constraints** during derivation, but they must not become templates from which answers are generated by analogy.

The grammar may be regular in its constraints without being verbally regular in its crystallizations.

---

## 4. Indexing, exhaustive contrast counts, and game mathematics

Cells use the zero-based index rule: `cell = 9 × i + 3 × j + k + 1`, with `i` for the transformation index (0–5), `j` for topology (0–2), and `k` for persistence (0–2). The order is Differentiation, Opening, Relating, Repair, Integration, Settlement; Focal, Distributed, Release; Standing, Bearing, Efficacy.

A valid round is a pair of *distinct* coordinates `(a,b)` with **Hamming distance = 1**, i.e. `sum(a[d] != b[d] for d in (T,K,P)) == 1`.

| Axis varied | Unordered pairs of values | Contexts per value pair (other axes held fixed) | Cell comparisons |
|---|---:|---:|---:|
| Transformation Pattern | C(6,2) = 15 | 3 × 3 = 9 | **135** |
| Completion Topology | C(3,2) = 3 | 6 × 3 = 18 | **54** |
| Persistence Mode | C(3,2) = 3 | 6 × 3 = 18 | **54** |
| **Total** | **21** | — | **243** |

**Direction matters for phrasing:** The 243 contrasts are unordered. If each contrast is presented in both sentence orders, there are **486 directed rounds**. For 10 sentences assigned per cell, each of the 243 comparisons supports **10 × 10 = 100 candidate sentence pairs**, for **24,300 unordered-position sentence pairings**; reversing them doubles presentations to **48,600**. These are combinatorial counts, not claims about educational quality or distinctiveness of every pair.

### All 21 primitive value-to-value contrasts

| Axis | Required contrasts | Cell comparisons per contrast |
|---|---|---:|
| Transformation | Differentiation–Opening; Differentiation–Relating; Differentiation–Repair; Differentiation–Integration; Differentiation–Settlement; Opening–Relating; Opening–Repair; Opening–Integration; Opening–Settlement; Relating–Repair; Relating–Integration; Relating–Settlement; Repair–Integration; Repair–Settlement; Integration–Settlement | 9 each |
| Topology | Focal–Distributed; Focal–Release; Distributed–Release | 18 each |
| Persistence | Standing–Bearing; Standing–Efficacy; Bearing–Efficacy | 18 each |

The **first clean syllabus** is precisely one round for each of these **243 cell-level contrasts**. Presenting each again in reverse direction or with fresh examples is a subsequent pass, not a new underlying contrast.

## 5. Complete 54-cell canonical lookup reference (verbatim from supplied coordinator)

**Interpretation:** The three coordinate values mutually determine one characteristic; the short forms are lookup crystallisations, not substitute definitions. The source table is reproduced unchanged below. Any version discrepancies with `THE_54_CONTROL.md` must be reconciled explicitly, not silently edited.

This table is for the Coordinator only. Do not expose it to GPT-D before derivation is frozen.

| Cell | Coordinate | Coordinate-generated form | Canonical crystallization | Companion utterance |
|---:|---|---|---|---|
| 01 | Differentiation × Focal × Standing | Focal distinguished standing | Focal mark | This. |
| 02 | Differentiation × Focal × Bearing | Focal contrast-bearing distinction | Binary bearing | This, not that. |
| 03 | Differentiation × Focal × Efficacy | Focal operative distinction | Boundary act | This far. |
| 04 | Differentiation × Distributed × Standing | Distributed distinguished standing | Scope standing | Within this. |
| 05 | Differentiation × Distributed × Bearing | Context-bearing distinction | Context-bound mark | This here. |
| 06 | Differentiation × Distributed × Efficacy | Distributed differential efficacy | Field separation | These among these. |
| 07 | Differentiation × Release × Standing | Released differentiated standing | Opposed standing | Opposed. |
| 08 | Differentiation × Release × Bearing | Released comparative bearing | Graded contrast | More and less. |
| 09 | Differentiation × Release × Efficacy | Released exclusionary efficacy | Exclusive cut | Not admitted. |
| 10 | Opening × Focal × Standing | Focal available field | Source field | From here. |
| 11 | Opening × Focal × Bearing | Source-bearing divergence | Source-carried divergence | From here, either way. |
| 12 | Opening × Focal × Efficacy | Focal generative opening | Branching output | More ways open. |
| 13 | Opening × Distributed × Standing | Distributed passage standing | Alternate passage | Another way through. |
| 14 | Opening × Distributed × Bearing | Span-bearing reach | Span-carried reach | Reachable across. |
| 15 | Opening × Distributed × Efficacy | Distributed availability | Field distribution | Available throughout. |
| 16 | Opening × Release × Standing | Released option standing | Released option | Free to choose. |
| 17 | Opening × Release × Bearing | Released continuity bearing | Continual passage | Through without break. |
| 18 | Opening × Release × Efficacy | Released beyond-limit efficacy | Edge opening | Beyond. |
| 19 | Relating × Focal × Standing | Focal relation standing | Direct bearing | This bears on that. |
| 20 | Relating × Focal × Bearing | Focal counterbearing | Pivoted balance | Held in counterbalance. |
| 21 | Relating × Focal × Efficacy | Focal responsive efficacy | Responsive return | Answered. |
| 22 | Relating × Distributed × Standing | Distributed relation standing | Sequential link | Then. |
| 23 | Relating × Distributed × Bearing | Reciprocal bearing | Reciprocal shift | Each changes the other. |
| 24 | Relating × Distributed × Efficacy | Distributed relational efficacy | Relational cycle | Back into itself. |
| 25 | Relating × Release × Standing | Released correspondence standing | Pattern alignment | The same arrangement. |
| 26 | Relating × Release × Bearing | Released correspondence bearing | Role correspondence | This plays that role. |
| 27 | Relating × Release × Efficacy | Released emergent efficacy | Emergent coordination | Something appears between them. |
| 28 | Repair × Focal × Standing | Focal corrected standing | Focal adjustment | Set right. |
| 29 | Repair × Focal × Bearing | Focal proportional bearing | Proportional correction | Rightly balanced. |
| 30 | Repair × Focal × Efficacy | Focal corrective efficacy | Load transfer | The burden shifts. |
| 31 | Repair × Distributed × Standing | Distributed corrected standing | Cross-position validation | Does it still hold across? |
| 32 | Repair × Distributed × Bearing | Distributed corrective bearing | Joint-bound repair | Right between both. |
| 33 | Repair × Distributed × Efficacy | Distributed corrective efficacy | In-course correction | Corrected in course. |
| 34 | Repair × Release × Standing | Released corrected standing | Limit reset | A better limit. |
| 35 | Repair × Release × Bearing | Released conditional correction | Condition reversal | Reverse when this holds. |
| 36 | Repair × Release × Efficacy | Released corrective efficacy | Disorder released | Free of the fault. |
| 37 | Integration × Focal × Standing | Focal integrated standing | Focal whole | One whole. |
| 38 | Integration × Focal × Bearing | Focal unity bearing | Frame-held whole | Held as one. |
| 39 | Integration × Focal × Efficacy | Focal integrated efficacy | Joint capacity | Together able. |
| 40 | Integration × Distributed × Standing | Distributed integrated standing | Role array | Each in its place. |
| 41 | Integration × Distributed × Bearing | Distributed mutual-support bearing | Mutual-support structure | Held through each other. |
| 42 | Integration × Distributed × Efficacy | Distributed integrated efficacy | Role activation | In operation. |
| 43 | Integration × Release × Standing | Released integrated standing | Self-maintaining equilibrium | Able to remain. |
| 44 | Integration × Release × Bearing | Released equilibrium bearing | Sustained equilibrium | Tension that holds. |
| 45 | Integration × Release × Efficacy | Released integrated efficacy | Convergent whole | Many become one act. |
| 46 | Settlement × Focal × Standing | Focal settled standing | Settled alternative | Chosen. |
| 47 | Settlement × Focal × Bearing | Focal settlement bearing | Unified settlement | Together now. |
| 48 | Settlement × Focal × Efficacy | Focal settlement efficacy | Path completion | Arrived. |
| 49 | Settlement × Distributed × Standing | Distributed settled standing | Recurrence settlement | It returns. |
| 50 | Settlement × Distributed × Bearing | Distributed conditional settlement | Condition-bound settlement | Settled if. |
| 51 | Settlement × Distributed × Efficacy | Distributed settlement efficacy | Case settlement | Settled across the cases. |
| 52 | Settlement × Release × Standing | Released settled standing | Transformation release | Still itself. |
| 53 | Settlement × Release × Bearing | Released explanatory bearing | Retrospective settlement | Now it makes sense. |
| 54 | Settlement × Release × Efficacy | Released settlement efficacy | Continuation discharge | Nothing further is owed. |

---

## 6. A playable round: data contract and invariant rules

Each round has:

```json
{
  "round_id": "P-01-02-A",
  "sentence_a": {"id": "cell01-001", "text": "Now I can tell which one it is.", "cell": 1},
  "sentence_b": {"id": "cell02-001", "text": "The difference shows up in how these two compare.", "cell": 2},
  "fixed": {"transformation": "Differentiation", "topology": "Focal"},
  "changed_axis": "Persistence Mode",
  "from": "Standing",
  "to": "Bearing",
  "question": "What does the second sentence change about the first?",
  "options": [
    {"id": "A", "text": "The distinction now holds through comparison.", "is_correct": true},
    {"id": "B", "text": "The distinction now changes what can happen.", "is_correct": false},
    {"id": "C", "text": "The distinction now takes its completion across a field.", "is_correct": false}
  ],
  "feedback": "Both sentences accomplish focal differentiation. What changes is how that completion persists: as a standing determination versus through constitutive comparison.",
  "status": "illustrative authored-game round"
}
```

**Rules:** (1) Confirm one-and-only-one changed coordinate programmatically. (2) Build correct-answer content from the exact changing values *under the fixed context*, not solely from keywords. (3) Do not equate Dimension Conjunction with independent add-on properties. (4) Build distractors from actual alternative glossary distinctions. (5) Avoid answer-position patterns, cue words, duplicated answers, and trivially repeated content. (6) Mark the supplied cell assignment as an authored claim, and keep any optional later review provenance separate. (7) Shuffle the sentence selection and option order without changing the underlying answer. (8) Record per-contrast mastery independently of sentence memorisation.

## 7. GPT-D: the foundational reverse-generation instrument

GPT-D is **not** a sentence classifier. It starts from a structural coordinate, receives the 15 primitives and Dimensional Conjunction, and independently derives a unified form and an ordinary-language expression. The instrument is designed to support *any domain or sentence subject*, without artificial restrictions on what kinds of sentences it may produce or what people may discuss. It should be **structurally constrained by the coordinate**, not topically constrained by the game.

A GPT reading this repository may **facilitate** GPT-D as follows:

1. Read this document and locate the fenced **GPT-D canonical prompt** below.
2. Ask the human operator to open a **fresh separate GPT session** and paste the full prompt unchanged. Do **not** include the canonical lookup table, authored corpus examples, or the target canonical companion utterance in that separate session.
3. Wait for `GPT-D — Ready.`
4. Supply one coordinate, for example `Relating × Distributed × Bearing`, or give multiple coordinates only when following the prompt's documented multiple-coordinate output rule.
5. Freeze the resulting description, short name, companion utterance, and everyday example before consulting the 54 table or comparing results.
6. The coordinator or human may then compare the frozen output with the authoritative table; report convergence, partial correspondence, or divergence without altering the output.
7. For game corpus extension, request candidate standalone utterances through a **separately versioned generation protocol**, not by silently modifying a frozen experimental GPT-D prompt.

This handoff is **user-facilitated**. A repository page does not autonomously instantiate a different GPT, and a GitHub Pages site should not pretend to do so unless a real supported integration is implemented. The GPT-D version remains frozen through a test batch. Do not tune a running version to make a specific cell appear correct.

### GPT-D canonical prompt (verbatim; human copy/paste)

```text
CONVERSATION NAME: GPT-D

You are GPT-D: the Derivable Understanding instrument.

You will receive one or more coordinates written:

Transformation Pattern × Completion Topology × Persistence Mode

Your task is to derive the single unified form of completion determined by each coordinate.

==================================================
THE THREE DIMENSIONS
==================================================

1. Transformation Pattern

Specifies what kind of unresolvedness is altered between the opening and completed situation.

Differentiation
A difference that was unavailable, flattened, conflated, or non-operative becomes determinate enough to matter.

Opening
Availability, reach, continuation, access, or possibility becomes greater than it was under the opening constraint.

Relating
A bearing, dependency, correspondence, ordering, reciprocity, or mutual determination becomes constitutive of the situation.

Repair
An organization that fails relative to an operative criterion is changed so that the misfit or fault no longer governs the result.

Integration
Separate parts acquire determinate roles through organization into a whole and thereby gain structure, mutual support, or joint capacity.

Settlement
A live demand for further uptake, choice, explanation, completion, adjudication, or continuation is discharged.

==================================================
2. Completion Topology
==================================================

Specifies the structural shape by which the transformation counts as complete.

Focal
The transformation becomes complete because completion gathers around one privileged locus. That locus is constitutive of why the transformation counts as complete.

Distributed
The transformation becomes complete only across a constitutive plurality, span, sequence, range, reciprocal field, set of cases, or system. No single locus is sufficient by itself.

Release
The transformation becomes complete because something that previously governed the situation loses its determining force.

Release means de-governance, not merely removal, absence, negation, separation, or movement away.

==================================================
3. Persistence Mode
==================================================

Specifies how the achieved completion remains available afterward.

Standing
The achieved determination itself remains available as the completed result.

Bearing
The achieved result remains what it is only through a constitutive relation, dependency, contrast, condition, source, proportion, frame, support, or mutual determination.

Efficacy
The achieved result remains as an accomplished capacity, operative effect, changed continuation, rule, function, or consequential difference in what can happen.

==================================================
DIMENSIONAL CONJUNCTION
==================================================

Dimensional Conjunction is not another dimension.

It is the rule by which the three dimensions mutually determine one cell.

A coordinate does not give a form three separate characteristics.

It does not mean:

Transformation characteristic + Topology characteristic + Persistence characteristic

The three terms are simultaneous relational constraints upon one completion-event.

At cell level:

- Transformation is realized only as this Transformation-through-this-Topology-in-this-Persistence.
- Topology is only the topology of this Transformation-in-this-Persistence.
- Persistence is only the persistence of this Transformation-through-this-Topology.

Each dimension constrains how the others can be realized.

Their conjunction is reciprocal determination.

The result is one unified characteristic.

The coordinate is a constraint that generates the form. It is not a description template for the final answer.

==================================================
NON-CARTESIAN RULE
==================================================

Do not derive one dimension first and then modify it with the others.

There is no valid semantic sequence:

Transformation → Topology → Persistence

There is no first, second, or third dimension in derivation.

All three constraints operate simultaneously.

Do not preserve the three dimensions as separately recognizable features merely to show that each definition has been used.

The final form may contain none of the coordinate terminology.

==================================================
NON-OPERATOR RULE
==================================================

Do not interpret one dimension as an operation performed upon another.

In particular:

- Focal does not simply select one object or item.
- Distributed does not simply pluralize a result.
- Release does not release, cancel, weaken, undo, or negate the Transformation Pattern.
- Standing does not merely preserve an already-completed result.
- Bearing does not merely add a relation to an already-completed result.
- Efficacy does not merely add usefulness, later action, or an external consequence.

No dimension has another dimension as its automatic semantic target.

A coordinate must remain fully a form of its Transformation Pattern regardless of Topology or Persistence Mode.

What counts as the focal locus, distributed field, released governance, standing determination, constitutive bearing, or efficacy must be resolved within the unity of the cell.

==================================================
RELATIONAL FIELD
==================================================

A coordinate is constrained partly by what neighboring coordinates are not.

Silently consider alternative coordinates produced by changing one dimension while holding the others fixed.

Use neighboring positions only as negative constraints.

Do not generate the target by modifying a neighboring answer.

Do not impose parallel vocabulary across rows or columns.

If many coordinates are supplied together, do not treat the task as matrix completion.

Do not establish verbal templates such as:

- Focal = this / one / here;
- Distributed = all / every / throughout;
- Release = no longer;
- Standing = is / remains;
- Bearing = depends / relative to;
- Efficacy = works / can / decides.

Such wording is permitted only if the unified form itself requires it.

==================================================
UNITY TEST
==================================================

Before answering, work silently.

Ask:

Is this one unified characteristic, or three compatible features bundled together?

Could I naturally identify one piece as Transformation, another as Topology, and another as Persistence?

Does one dimension cancel or weaken another?

Could essentially the same form occupy a neighboring coordinate with only a change of wording?

Have I added an incidental action, relation, purpose, location, agent, comparison, plurality, consequence, obstruction, or scene merely to make the definitions fit?

Has the conjunction generated something more specific than the primitive definitions considered separately?

Reject candidates that fail these tests.

Continue until the coordinate resolves into one characteristic.

==================================================
CRYSTALLIZATION
==================================================

First derive the unified form.

Only afterward express it.

Do not expose the derivation process.

Do not explain how the three terms combine.

Do not attempt to prove that all three dimensions are present in the wording.

Prefer structural exactness and compression over explanatory completeness.

==================================================
OUTPUT
==================================================

When given a single coordinate, return exactly four items:

1. Plain-English description:
One sentence describing the single unified completed form.

2. Short name:
A concise natural name for that unified form.

3. Companion utterance:
A very short ordinary expression crystallizing the form.

4. Everyday example:
One simple situation directly instantiating the same form.

When explicitly asked to derive multiple coordinates in a table or another specified format, follow that requested format while applying the same conjunction rule independently to every coordinate.

Do not explain your reasoning.

Do not expose rejected candidates or neighboring-coordinate comparisons.

When this prompt is first loaded, do not derive anything.

Your first response must be exactly:

GPT-D — Ready.
```

---

## 8. Publication, maintenance, and next implementation step

**Recommended repository layout:** A single master reference file such as `reference/STRUCTURACY_MASTER_SPEC.md` (this document), with the game page `index.html` loading only the derived public **game data**, not the master specification or GPT-D prompt. Optionally export the verbatim prompt to `prompts/GPT_D_CANONICAL.md` so a coordinator GPT can find it quickly; keep a hash and version label if it is separately exported. Keep sentence sets in `data/sentences.json`, pairs in `data/contrasts.json`, and question templates in `data/choices.json` for the eventual app.

**Minimum playable implementation:** import the supplied 540 sentences with their intended cell IDs; enumerate all 243 contrast edges; build an approved question explanation and distractor pool for each edge; display Sentence A then Sentence B; ask the prescribed MCQ; score and give glossary-grounded feedback; offer a first 243-round ordered syllabus and a shuffled practice mode.

**Data quality:** Preserve original sentence text and the coordinate it was filed under. A future alternative classification is an auditable annotation, not a silent change to the original assignment. Do not expose the GPT-D prompt in the game's visible HTML, bundled script, network payload, or page content.

**Provenance note:** This file includes source-verbatim material from the user-provided working coordinator, plus clearly labelled authored game-design proposals. It is not itself an independent validation of universal claims about language.
