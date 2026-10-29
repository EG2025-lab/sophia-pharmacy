# SOPHIA
### Pharmacist-led AI for medicine documents, Italian pharmacy law and clinical evidence

The deployed professional beta is **0.7.110-beta**, restricted to owner-approved users; payments and answer charging remain inactive. [Current status](docs/STATUS.md).

110 fixes common output-privacy composition, clinical web-recovery focus, no-progress search variants, manual error readback and source-title issues. There is no fixed global model-call ceiling. Source admission, privacy, bindings and full semantic review remain required. **1,749 offline checks and56 interface checks** passed; no live110 model question was sent.

Six real109 repeats produced **two useful scoped answers, three partial answers and one failed request**.44 internal model calls, a conservative2.283USD estimate, not invoice. Latency ranged about34–128seconds. Structured retrieval and independent web were both attempted where relevant; clinical and legal completeness still had gaps. This does not establish an overall efficiency improvement.

110 answer correctness, actual savings, latency and repeatability remain unmeasured. Legal classification/original retention, one clinical vaccination subquestion and the current private provincial vaccination pathway remain open for field verification. No general counter readiness, FarmAI parity or human clinical validation is claimed. Original FarmAI GPTs and Business plugins retain content **0.7.7.155**.

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

Use **[Let's talk on the SOPHIA website](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners)** to select your areas of interest and prepare an email, or contact **[Enrico Giuliano](mailto:enrico.giuliano000@gmail.com?subject=SOPHIA%20%E2%80%94%20collaboration)** directly.

Tell us about your expertise, the question you would like to explore and a realistic first contribution. You can also comment on an opportunity above or help refine the [pilot protocol](pilot/README.md).

## Historical project status of80

Restricted beta **0.7.80** replaces proven excessive language and format gates, makes planning optional and preserves reviewed content when follow-up cannot finish safely. Technical checks use synthetic boundaries, with no new paid model questions. Source identity, privacy, evidence support and human review remain required. The three live78 outcomes remain historical; real usefulness and latency of80 are not yet measured. Scores and rollout gates are unchanged. [Status and scope](docs/STATUS.md).

**[Current status and evidence](docs/STATUS.md) · [Transparency and interactive architecture](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency) · [Public roadmap](https://sophia-pharmacy.enricogiuliano.chatgpt.site/roadmap)**

This repository is a **public project overview and collaboration space**. It contains documentation, not the application source code.

SOPHIA is in development. Regulatory assessment and clinical validation are ongoing work, not completed certifications. This repository provides no patient-specific advice and no guarantee of product availability or clinical performance.

Please keep patient data, credentials and confidential material out of public issues, discussions and contributions. The [website privacy notice](https://sophia-pharmacy.enricogiuliano.chatgpt.site/privacy.html) explains contact and waitlist handling.

Operational supervision is maintained separately from the app. The [latest status review](docs/STATUS.md#current-operational-reference) records version binding, alert deduplication and outstanding dated-source review without changing maturity scores.
