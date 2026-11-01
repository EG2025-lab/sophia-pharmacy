# SOPHIA

Beta 143 is deployed. Following two focused batches and general RCP/PIL comparison and shared-leaflet heading repairs, 54,000 internal cases and 540,350 checks passed; 2,077 Python and 57 UI. Synthetic protocols and regressions, not 54,000 independent questions or AI answers. Six new grammar errors were fixed and the same 3,000-case corpus now passes unchanged expected outcomes. Ten final real tests: 9 delivered answers; 8 useful within scope, 1 partial and 1 failed, assessed internally with AI assistance. Technical reading, scoped usefulness and professional validation remain distinct. Governance candidate 144 is not deployed; no human clinical validation.

[Current status / Stato corrente](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence (historical)

Beta 139 is live. New 10,000-case AIFA corpus and 180,400 internal checks passed; 2,031 Python and 57 UI. Ten new real AIFA tests: nine delivered answers, six useful within scope, three partial and one API error. Candidate 140 is NOT deployed: mandatory RCP/PIL comparison and EAN product-web path, with 2,050 Python/57 UI and 10,000 boundary cases passed; no own real test. API schema error remains open. No clinical validation.

[Current status / Stato corrente](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence (historical)

### Pharmacist-led AI for medicine documents, Italian pharmacy law and clinical evidence

The deployed professional beta is **0.7.138-beta**, restricted to owner-approved users; payments and answer charging remain inactive.

137 adds shared recognition of ten medicine-document question families: indications, composition, dosing/duration, administration, storage/expiry, warnings/contraindications, interactions, special populations, adverse effects and missed/excess dose. Context, source-role selection, composition and AI review use the same incomplete cues. They provide no canned answers, identity or clinical evidence. **2,002 offline regressions and58UI checks passed.50natural formulations passed200internal checks, versus83on135using the same final oracle.** This measures technical recognition and routing, not real answer coherence or clinical accuracy.0new real model questions; professional acceptance and previous specific feedback remain open. Bridges, model configuration, access, payments and UI135are retained; clinical-method explanation1.32updated. No model weight training.


## Open collaboration opportunities

Start with one small, reviewable contribution. Each opportunity sets out a first deliverable and criteria to agree before execution.

| Opportunity | First contribution | Details |
| --- | --- | --- |
| Official medicines documents | Fixtures across at least three medicines/formulations; correct identity and both RCP/FI, including missing documents. | [Join the document-reading workstream](https://github.com/EG2025-lab/sophia-pharmacy/issues/2) |
| Italian pharmaceutical legislation | Six source-bound cases covering exact references, dates, applicability and incorrect references. | [Join the legislative-retrieval workstream](https://github.com/EG2025-lab/sophia-pharmacy/issues/3) |
| Pharmacist and AI evaluation | Review a 20-question pilot protocol, citation checks and independent professional review criteria. | [Join the evaluation workstream](https://github.com/EG2025-lab/sophia-pharmacy/issues/4) |

The [pilot proposal](pilot/README.md) includes 20 candidate question templates and blank review forms. It is **not yet frozen or run**. We welcome pharmacists, developers and AI researchers; initial protocol and fixture work does not require paid model calls. **[Introduce yourself in the pilot discussion](https://github.com/EG2025-lab/sophia-pharmacy/discussions/5).**

## From FarmAI to SOPHIA

FarmAI is available as the original custom GPTs and as private Business plugins derived from their copies. The original GPTs are preserved. SOPHIA is a separate application with its own restricted beta, model routing and qualification. [How GPTs, plugins and SOPHIA differ](docs/FARMAI_AND_SOPHIA.md).

The work focuses on connecting three kinds of information while preserving their different meanings:

- **Official medicines information:** identifying the correct medicine and package, and reading both the Summary of Product Characteristics (SmPC/RCP) and Package Leaflet (PIL/FI).
- **Italian pharmaceutical legislation:** finding relevant official provisions, checking their context and applicability, and distinguishing a legal source from an interpretation.
- **Clinical evidence and guidelines:** retrieving relevant literature, checking whether sources support individual claims, and explaining uncertainty and gaps.

Traceable sources and professional judgment are central to the project. An attributed pharmacist review should identify what was checked and its limits; it does not automatically validate an entire system.

## What we could contribute to a collaboration

We would like to combine pharmacy-domain expertise with research and engineering:

- Realistic professional questions and workflow requirements.
- Pharmacist-informed evaluation criteria for source relevance, document identity, citation support and usefulness.
- A practical setting for investigating how AI systems handle uncertainty, incomplete retrieval and changing official information.

A first collaboration could be a small, jointly scoped evaluation using public sources and synthetic questions, with a shared protocol and explicit limits.

## Who we would like to work with

| Area | Questions we would like to investigate |
| --- | --- |
| AI and LLM researchers | Reliable routing, tool use, retrieval, grounded answers and appropriate abstention. |
| Software developers | Robust source adapters, document parsing, reproducible tests and a clear conversational experience. |
| Universities and research groups | Joint evaluation methods, evidence quality and human review. |
| Pharmacists and pharmacy networks | Realistic tasks, usability and professional review. |
| Technology and source partners | Sustainable integrations, source coverage and permitted access to documentation. |

Our development work uses **[ToolUniverse](https://github.com/mims-harvard/ToolUniverse)** to explore scientific-tool orchestration and literature retrieval. We welcome discussion with its research and developer community. Using ToolUniverse does not imply an affiliation, endorsement or partnership with its authors or Harvard.

## Start a conversation

Use **[Let's talk on the SOPHIA website](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners)** to select your areas of interest and prepare an email, or contact **[Enrico Giuliano](mailto:enrico.giuliano000@gmail.com?subject=SOPHIA%20%E2%80%94%20 collaboration)** directly.

Tell us about your expertise, the question you would like to explore and a realistic first contribution. You can also comment on an opportunity above or help refine the [pilot protocol](pilot/README.md).

## Historical project status of80

Restricted beta **0.7.80** replaces proven excessive language and format gates, makes planning optional and preserves reviewed content when follow-up cannot finish safely. Technical checks use synthetic boundaries, with no new paid model questions. Source identity, privacy, evidence support and human review remain required. The three live78 outcomes remain historical; real usefulness and latency of80 are not yet measured. Scores and rollout gates are unchanged. [Status and scope](docs/STATUS.md).

**[Current status and evidence](docs/STATUS.md) · [Transparency and interactive architecture](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency) · [Public roadmap](https://sophia-pharmacy.enricogiuliano.chatgpt.site/roadmap)**

This repository is a **public project overview and collaboration space**. It contains documentation, not the application source code.

SOPHIA is in development. Regulatory assessment and clinical validation are ongoing work, not completed certifications. This repository provides no patient-specific advice and no guarantee of product availability or clinical performance.

Please keep patient data, credentials and confidential material out of public issues, discussions and contributions. The [website privacy notice](https://sophia-pharmacy.enricogiuliano.chatgpt.site/privacy.html) explains contact and waitlist handling.

Operational supervision is maintained separately from the app. The [latest status review](docs/STATUS.md#current-operational-reference) records version binding, alert deduplication and outstanding dated-source review without changing maturity scores.


**Language and process gate — 1 November 2026: NO-GO.** Beta137: the new language and process gate has not passed.30,000internal combinations,10,000per domain:21,166PASS and8,834FAIL against technical oracles. These combine300formulations with contexts, references and task modes, not30,000AI answers or independent paraphrases. Gaps concern AIFA paraphrases/references, negation, clinical needs and a false block of a legal-document question. Cues are incomplete: a FAIL does not prove a wrong real answer.2,002Python regressions and57UI tests under the new command passed;0new model answers. Next phase held, no new app release or bridge change.


**Version138 ready for real tests.** Beta138: shared causes behind the language/process gate corrected. The same137corpus improves from21,166to30,000passed cases out of30,000:10,000AIFA,10,000legislation,10,000Clinical Evidence;315,600checks passed. These combine300formulations with contexts and task modes,not30,000AI answers or independent paraphrases.2,023Python regressions and57UI tests passed. Negation scope,needs/references,documentary objects and legal-version requests improved. Privacy28and method1.33;same bridges and models. Ready for real tests:0new generated answers,quality and usefulness still need measurement. Technical PASS proves neither every possible variant nor clinical/legal validation.
