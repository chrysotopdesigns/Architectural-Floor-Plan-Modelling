---
name: exposure-white-balance-and-tone-mapping
description: Professional method and working standard for exposure, White Balance and Tone Mapping inside Lighting Simulation and Rendering (Architecture & Floor Plan Modeling). Covers exposure, tone mapping and control as decisions to be made, recorded and verified rather than impressions to be judged. Use this skill whenever the user mentions "exposure", "tone mapping", "control", "exposure, White Balance and Tone Mapping", asks how exposure, White Balance and Tone Mapping is done, asks for a quality checklist, or brings a lighting simulation and rendering task where exposure or tone mapping affects the outcome — even if they do not name the technique directly.
compatibility: Text-only guidance; no external tools required. Works with the bundled reference file at references/ and, where present, the course-level assets of this library.
metadata:
  author: promptstation
  version: 1.0.0
  category: architecture-and-floor-plan-modeling
---

# Exposure, White Balance and Tone Mapping

**Course:** Lighting Simulation and Rendering · **Profession:** Architecture & Floor Plan Modeling · **Author:** promptstation

## Mission

Exposure, White Balance and Tone Mapping is where the quality of a lighting simulation and rendering job is decided, and it is rarely the part that announces itself when it goes wrong. Work produced here fails quietly: it passes review, reaches the client, and only shows its weakness when the session, project or brief moves on to the next stage and the problem has to be paid for. The purpose of this skill is to make every decision inside exposure, White Balance and Tone Mapping referenced, checked and defensible, so the work survives someone else looking at it. Working at this stage means the decision is yours to make on a real job and defend with reasons.

Three rules govern everything below:

1. **Name the decision.** Every step in this skill resolves a specific choice about exposure, tone mapping or control; if you cannot say which, you are not yet doing the work.
1. **Record before you move on.** A decision that is not written down cannot be reviewed, repeated or defended.
1. **Verify against a criterion, never against a feeling.** "It looks right" is not a check.

## Use Cases

### Use case: Decide exposure on a live job

Trigger: "how should I handle exposure", "what should I use here", "which tone mapping is right for this".

Steps:
1. Read the brief for the constraint that governs exposure — purpose, audience, budget, medium or deadline.
2. Name the two or three options that are genuinely open and the criterion that separates them.
3. Choose, record the reason, note what the choice costs on control, then continue.

Result: a stated, recorded decision on exposure that another professional could review and challenge.

### Use case: Produce the asset for exposure, White Balance and Tone Mapping

Trigger: "walk me through exposure, White Balance and Tone Mapping", "produce this properly", "what is the correct order of work here".

Steps:
1. Fix the finish line first: what must exist, in what form, checked by whom.
2. Work the sequence — exposure, tone mapping, control — keeping the intermediate state inspectable.
3. Take the mid-point check, then close with the quality checklist and hand over with the record attached.

Result: a finished asset plus the record that shows how each decision was reached.

### Use case: Review or repair work that has gone wrong

Trigger: "this does not look right", "the client rejected it", "it worked in draft but fails now".

Steps:
1. Convert the complaint into a question about a named concept: exposure, tone mapping or control?
2. Inspect in that order, stop at the first step that fails, and correct where the fault was introduced.
3. Re-run verification and record the cause so the fault class does not recur.

Result: a fault located by method, corrected at source, with the cause recorded so it does not recur.

## Domain Reference

| Concept | What it governs | How it is judged |
|---|---|---|
| **exposure** | the early decision that everything downstream inherits | whether it was chosen against a stated criterion and recorded |
| **tone mapping** | the working choice made repeatedly under time pressure | whether it is consistent across the whole piece of work |
| **control** | the quality criterion that decides whether the result is finished | whether it survives comparison with a reference example |

Working anchors for this profession — quote them with their source and version, and confirm the current published value before relying on them:

- Designs must respect local building codes, planning rules, egress, fire separation and accessibility requirements; the modeller flags compliance questions to the architect rather than deciding them.
- Drawings and models are dimensionally truthful: scale, wall thickness, door and stair sizes and ceiling heights must match the design intent and be consistent across every output.
- Units, origin, north orientation and levels are project-defined conventions; consistency is checked before any drawing is issued.
- Presentations to clients and planning authorities must be honest about what is proposed versus what exists; visualisations are not approvals and are labelled accordingly.

## Core Output Requirements

1. Name the concept being decided (exposure, tone mapping or control) before making the decision.
2. State the criterion the decision is made against, in the words of the brief or the standard.
3. Give the tolerance or acceptance range wherever a value, size, level or duration is involved.
4. Show the reasoning in the output, not only the result; a decision without its reason cannot be reviewed.
5. Record the alternative that was rejected and why, for any decision that could be contested.
6. Separate what was checked from what was assumed, and state the effect of each assumption.
7. Attach the quality checklist output to the finished asset before handover.

## Workflow

### Phase 1 — Establish the frame

- Confirm what is being made, for whom, in what medium, and what "finished" means for it.
- List the constraints that bind exposure; write down the assumption most likely to be wrong.

### Phase 2 — Gather what the decisions depend on

- Collect the reference material, source asset or data the work must respect.
- Confirm the standard the work is measured against and where tone mapping is already settled.

### Phase 3 — Make the decisions in order

- Settle exposure first with the criterion stated; everything downstream inherits it.
- Move to tone mapping only when exposure is stable; resolve control last, against the whole result.

### Phase 4 — Produce the work

- Work to the sequence above, keeping the intermediate asset inspectable.
- Stop at the mid-point check; corrections are cheapest before the final pass.

### Phase 5 — Verify

- Run the quality checklist against the finished work, not against your memory of making it.
- Compare with an outside reference, record the observed value for control against its tolerance.

### Phase 6 — Hand off and record

- Deliver the asset package with decisions, reasons, assumptions and open items attached.
- Note what you would change on the next job; that note is the skill improving.

## Output Template

ALWAYS use this structure when reporting work under this skill:

```
## Exposure, White Balance and Tone Mapping — working record
Brief:            [what is being made, for whom, in what medium]
Governing concept: [exposure / tone mapping / control]
Criterion:        [the standard or brief constraint the decision answers to]
Decision:         [what was chosen]
Rejected:         [the alternative and why it lost]
Tolerance:        [accepted range, where a value is involved]
Checked:          [what was verified, and how]
Assumed:          [what was not verified, and the likely effect]
Open:             [what remains unresolved at handover]
```

## Examples

### A straightforward job with one governing constraint

Actions:
1. The brief fixes the purpose, and only exposure remains open.
2. State the criterion, choose, and record the choice in one line.
3. Produce the asset in the order above and close with the quality checklist.

Result: A finished asset with a one-line record per decision, and no open questions at handover.

### An awkward job where the obvious answer is wrong

Actions:
1. The instinctive choice on tone mapping is the one most often made in this profession.
2. Test that instinct against the brief; in the awkward case it contradicts the governing constraint.
3. Take the second-best option on tone mapping, accept the cost on control, and explain the trade-off in the handover.

Result: A result that looks less obvious at first glance and holds up under review, with the trade-off documented.

## Troubleshooting

| Report | Most likely cause | Correction |
|---|---|---|
| The work passes review here and fails later | exposure was settled against preference rather than a stated criterion, so it does not survive a change of context. | Re-derive exposure from the brief and re-check the downstream decisions that inherited it. |
| The result is inconsistent across the project | tone mapping was decided separately each time it came up, with no recorded standard. | Fix tone mapping once, write it down, then align the existing work to it and note every change. |
| Finished work feels acceptable but not finished | control was never given an explicit criterion, so "done" was decided by fatigue. | Set the tolerance for control, measure against it, and record the value rather than the impression. |
| Correction costs far more than expected | The fault was corrected where it appeared rather than where it was introduced. | Trace the fault upstream to the phase that produced it, correct there, then re-run verification. |
| The client or reviewer disagrees with a decision | The reason for the decision was never recorded, so it cannot be defended or explained. | Attach the criterion and the rejected alternative to each significant decision as standard practice. |

## Anti-Patterns

- Making a exposure decision by preference and calling it instinct.
- Proceeding without a written criterion and discovering it at review.
- Declaring the work finished without a tolerance for control.
- Correcting a fault where it surfaced instead of where it was introduced.
- Delivering without the working record, then being unable to explain a decision.
- Copying a previous result without re-checking whether its constraints still hold.
- Models that read beautifully and measure wrongly: walls that do not close, doors that swing into stairs, ceilings that change height between views.
- Rendering to win the meeting rather than to inform the client — a dream image that cannot be built, priced or permitted.
- Treating the model as a picture instead of a tool, so the same design cannot produce drawings, quantities or revisions without being rebuilt from scratch.
- Architectural rendering exists to explain the space; lighting that flatters but misleads is a failed render.

## Decision Heuristic

Before signing off any step of this skill, ask:
1. Which concept is actually in question — exposure, tone mapping or control?
2. What is the criterion, and where did it come from?
3. What was the strongest alternative, and why did it lose?
4. What is the tolerance, and what value was actually observed?
5. What was assumed, and how wrong could that assumption be?
6. Would this survive review by someone who did not do the work?

## Final Principle

Work in exposure, White Balance and Tone Mapping so that nothing depends on being in the room when it was made. Decisions with stated criteria, recorded reasons and verified outputs survive handover; everything else has to be redone by whoever inherits it.

## Bundled References

- `references/exposure-white-balance-and-tone-mapping-reference.md` — decision checklist, vocabulary and verification points for exposure, White Balance and Tone Mapping, to be read before starting a job and again before sign-off.
