# SOPHIA
### Pharmacist-led AI for medicine documents, Italian pharmacy law and clinical evidence

The deployed professional beta is **0.7.104-beta**, restricted to people approved by the owner. Google sign-in identifies the person; professional qualification remains self-declared. **Automatic admission, real payments and answer charging are inactive.** The Stealth Home retains its survey and optional waitlist without app-access buttons. [Current status](docs/STATUS.md).

Exactly **three historical questions were submitted in separate real UI chats on 103**. All were delivered: a concise RCP/PIL AI answer in **26.88 s**, ordinary prescription law in **14.6 s**, and clinical evidence synthesis in **76.36 s**. The first two were useful within the assessed documentary scope. The clinical answer explained conflicting evidence and its limitations, but remained verbose and slow. Eleven model calls had usage records; the conservative estimate was **USD 0.49**, not an invoice or a general per-answer price. No fourth question was submitted.

RCP/PIL questions use verified AIFA acquisition, **GPT-6.1 Sol low synthesis and independent review**, as observed on 103. The 104 correction preserves that route and the adaptive router. It replaces the unnecessary extra-message instruction with the existing app receipt section, deduplicates only identical limitation sentences with matching source coverage, and adds fixed diagnostic codes for rejected reader inputs. Original review declarations and unmatched qualifiers remain intact; paraphrases are not silently treated as equivalent.

Release 104 passed **1,677 offline checks**, with no skips, and exact-byte inspection of **171 runtime files** without network. **No new real question was submitted on 104**, respecting the three-question cap. Its concise-writing instruction and display corrections do not establish measured latency or usefulness. The rejected103 reader input was not retained in enough detail to prove its exact cause; diagnostics improve future observation rather than claiming a repaired source. Human clinical validation is incomplete, general repeatability is unproved and general professional rollout remains **NO-GO**.

The clinical 103 answer used Actions/API, including DREAM full text and smaller-study abstracts; this was not an updated systematic review. Independent web fallback was not exercised in this battery; the earlier 102 declared ISS/NICE web readings remain separate evidence. The current Ministry-table gap also remains open. History, the versioned Clinical Algorithm beta, security boundaries and 14curated FarmAI method lessons are retained. This is not automatic model training. FarmAI originals and Business plugins retain content **0.7.7.155** and were not retested.

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
