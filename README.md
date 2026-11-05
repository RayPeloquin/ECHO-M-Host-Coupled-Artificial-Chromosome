# ECHO-M — a proposed host-coupled artificial chromosome design

**Research concept v0.4, 28 October 2026. No ECHO-M construct or experimental results are reported.**

A live reporter would track one defined host-state input in **cultured mammalian cells**. A separate one-bit DNA latch could preserve evidence of exposure after the live signal fades. An external ledger would link the two readouts to their observation unit and window.

**Host-coupled** means the recorder would rely on the cell for energy, gene expression, DNA replication and repair. To test the sensor’s link to host state, measure the input independently and compare it with the live response and later DNA readout in matched exposed and unexposed cells.

The recorder is intended to stay separate from host chromosomes and avoid editing the host genome. Check its physical location, state the detection limits for unintended integration, and measure effects on host growth and viability.

## Read the current design

**[Nine-page v0.4 Court revision: architecture, evidence gates, calculations, source audit and review record](ECHO-M-v0.4-Court-Revision.pdf)**

This is the current saved design brief. The 29 October 2026 publication repair restores it to this repository, which previously contained only a short v0.2 description. Older repository metadata may still name that earlier version.

## What the proposed recorder would mean

| Interpretation | Required distinction |
| --- | --- |
| Recorded | A decoded mark, interpreted with its physical context, tested specificity and error model, supports at least one qualifying event. One event and several can leave the same mark. The bit gives no exact time. |
| Qualified blank | No mark is recovered, and evidence supports the recorder’s ability to write at the declared unit and over the declared window. A qualifying exposure could still have been missed at the tested sensitivity. |
| Unknown | Missing, discordant, silenced, lost or insufficiently qualified outcomes remain visible. Deaths and losses stay in the enrolled denominator. |

To attribute a mark to one exposure window, establish a blank starting state for the stated unit and account for the delay between input and writing. If an exposure outside the window could explain the same mark equally well, the archive’s answer for that window is **unknown**.

The ledger records cell, lineage, clone or cohort scope, assay provenance, uncertainty and observation windows. It does not supply an intracellular governor or a molecular authentication mechanism. A destructive assay on one cell cannot automatically certify another live cell.

## Evidence gates

1. Define one host background, input, recording window and research decision.
2. Qualify physical location, integrity, copy state, maintenance, sensing and recording separately.
3. Recheck the coupled system, shared failure modes, host burden and unknown outcomes.
4. Before expanding scope, demonstrate a useful advantage over a simpler reporter or recorder for the same retrospective decision. Match the host background, input, window and evidence standards. Report correct classifications per enrolled unit, host burden and physical stability for each group.

Production OFF, residual output, DNA persistence or clearance, and host recovery are separate endpoints. The brief's retention, shutoff and confidence calculations are illustrative mathematical examples, not measured ECHO-M performance.

## Relationship to ECHO-Rx

[ECHO-Rx](https://github.com/RayPeloquin/ECHO-Rx-Responsive-Biologic-Production) is a separate therapeutic research branch. Its first proposed scope is contained cell culture and a tissue model. Recorder claims and therapeutic claims require distinct evidence.

## Status and credits

The repository contains a proposed architecture and evidence review. Component precedents do not validate the integrated system; no construct, biological result, clinical readiness or established novelty is claimed.

The March 2026 correction concerns the yeast strain used in the 2024 artificial-chromosome study. A rebuilt construct formed artificial chromosomes in two human cell lines. The follow-up measured formation and left long-term stability untested. [Science erratum](https://pubmed.ncbi.nlm.nih.gov/41818380/) · [Follow-up study, Figure 3](https://link.springer.com/article/10.1007/s10577-025-09788-w)

**Anubis / Ray Peloquin:** concept and design direction. **Asteris Solenne / ChatGPT:** AI-assisted synthesis, source audit, mathematics and documentation. **Grok, Claude, Gemini and Meta AI:** adversarial AI review, checked and selectively adopted. The Court is a critique workflow, not independent experimental replication or institutional peer review.
