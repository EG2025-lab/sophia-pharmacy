# SOPHIA
### Pharmacist-led AI for medicine documents, Italian pharmacy law and clinical evidence

The deployed professional beta is **0.7.106-beta**, restricted to people approved by the owner. **Automatic admission, payments and answer charging remain inactive.** The Stealth Home retains its survey and optional waitlist without app-entry buttons. [Current status](docs/STATUS.md).

106 unifies profile, Google contact email, contributions, credit and experience in one personal account, including previously authorized members without a credit account. Already-observed official **RCP/PIL PDF links** take priority over the medicine-identity link; original citations and receipts are preserved. A clearly explained device shortcut and a short, accessible fade improve presentation without generating unchecked text.

Firebase retains each delivered question, answer, sources and receipt in the account’s private archive. An **automatic, idempotent operational journal** now records completed answers, incomplete requests and distinct feedback signals, with pending-record reconciliation. Counters start from105 and do not replace the older chat history. Optional, initially disabled sharing exposes only coarse category totals to the owner; revocation excludes the account on the next query. This summary contains no raw chats, medicine names or per-person rows.

This is **not model-weight training or automatic clinical learning**. Fourteen curated FarmAI method lessons remain distinct from conversations; recent context is limited to the same chat. Signal candidates await review and a versioned release before changing runtime methods. No AI call is added by the journal; it adds database operations. Small-group aggregates are not presented as guaranteed anonymous. 106 passed **1,696 offline checks**, no skips, and **175 runtime files** were checked byte for byte without network. Local UI checks used synthetic data; no real 106 question was submitted.

The last real battery remains the three historical103 UI questions: scoped AIFA AI synthesis in 26.88 s, ordinary prescription law in 14.6 s and clinical synthesis in 76.36 s. Clinical latency, up-to-date evidence coverage, general repeatability and human clinical acceptance remain open;106 claims no speed or accuracy gain. The current Ministry-table gap remains. RCP/PIL Sol low synthesis, independent review, adaptive routing and declared web fallback are retained. FarmAI GPTs and Business plugins retain content **0.7.7.155**, without new tests.

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
