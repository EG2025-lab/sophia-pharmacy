# SOPHIA
### Pharmacist-led AI for medicine documents, Italian pharmacy law and clinical evidence

The deployed professional beta is **0.7.101-beta**, restricted to people approved by the owner. Google sign-in identifies the person; new applications wait for approval. Professional qualification remains self-declared. **Automatic admission, real payments and answer charging are inactive.** The public Stealth website retains the survey and optional waitlist without app-access buttons. [Current status](docs/STATUS.md).

Releases 99–101 improve PIL ingredient-quantity parsing, package/channel qualification, clinical Action-first retrieval and documentary review. The corrective 101 release adds lossless storage encoding for nested source-data arrays, private minimized failed-call usage records and no-model delivery for narrowly matched natural exact-AIC identity questions. **1,539 offline Python checks** passed, including 13 new checks, and 159 runtime files were compared inside the container. These are technical checks; **no new real question was submitted on 101**, following the owner’s four-question cap.

On parent version **100, exactly four new questions were submitted in separate real UI chats**: medicine identity, repeatable-prescription law, PIL excipients and adult clinical evidence. Three responses completed in **22.06 s, 8.04 s and 59.74 s** backend. The PIL response failed during final persistence after the engine had completed its checks; it remains a failed delivery, not a pass. Twelve model calls were observed, including web discovery. The correction was checked offline and published without another real replay. These observations are not a controlled speed comparison, an SLA or evidence of general repeatability.

The storage correction preserves the original source data and hashes after reading; it does not approve a claim or bypass a source check. The incomplete 100 delivery is not relabelled as a successful 101 response. Chemical/salt reconciliation, broader document coverage and independent professional acceptance retain their separate limits. Human clinical validation remains incomplete.

**Adaptive routing is active:** Luna with no reasoning for observed bounded extractions, Terra with no reasoning for bounded documentary composition, and Sol low or controlled medium for unbounded context, clinical work, conflicts and independent review. All three models were observed on 100. The clinical case attempted Actions and API reading before declared independent web recovery; access challenges prevented new readable web bodies, so the answer used Action-read abstracts and stated its full-text and currency limits. Cache savings, broader continuity and general FarmAI parity are not established.

The historical 0.7.88 second battery retains **six answers to three general documentary questions, each repeated twice**: medicines storage, the complete text of an Italian statutory article, and general institutional dry-eye information. Technical and AI-assisted documentary checks passed within those questions; the essential content agrees within each pair, with detail and wording variations. Observed end-to-end times: medicines **11–18 s**, legislation **10–12 s**, clinical web recovery **32–35 s**. These are selected observations, not an SLA, a controlled speed comparison, general repeatability or human clinical validation. The clinical answers declare partial coverage and unverified currency/retraction status. General professional rollout remains **NO-GO**. [Status and limits](docs/STATUS.md).

**Less information fragmentation. More room for the pharmacist's work.**

SOPHIA is an independent project founded by **Enrico Giuliano, pharmacist and Founder & Product Lead**, in Italy. We are developing an AI application that brings official medicines documentation, Italian pharmaceutical legislation, clinical research and guidelines into a single professional conversation.

Our aim is to reduce pharmacists' information burden, help reduce errors and improve pharmacy service. These are development goals; their impact still needs to be measured.

**[Explore SOPHIA](https://sophia-pharmacy.enricogiuliano.chatgpt.site/) · [Collaboration brief](COLLABORATION.md) · [20-question pilot proposal](pilot/README.md) · [Discussions](https://github.com/EG2025-lab/sophia-pharmacy/discussions)**

[Share your professional needs](docs/PROFESSIONAL_NEEDS_RESEARCH.md): the survey and waitlist choice are independent. The waitlist checkbox is optional and initially selected; it can be cleared to submit only the survey. Email is required only for the waitlist or a separately chosen interview. Pharmacist roles distinguish employees, owners and freelance professionals. Earlier records retain their original purposes. Developers and AI experts retain a collaboration path.

**[Leggi in italiano](README.it.md) · [Make a first contribution](CONTRIBUTING.md) · [Propose a collaboration](https://github.com/EG2025-lab/sophia-pharmacy/issues/new?template=collaboration.yml)**

Developers and AI researchers can begin with public-source metadata, retrieval failure cases and evaluation design. Pharmacists can help define realistic tasks and review criteria. Start small: [prepare one official RCP/FI source pair](pilot/source-pair-template.json), without writing a clinical answer or calling a paid model.

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
