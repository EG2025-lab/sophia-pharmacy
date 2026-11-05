# Collaboration brief

## Current status — 5 November 2026

SOPHIA **0.7.166-beta** is available with restricted access. With a single explicit PMID, Clinical Evidence reads the named study first, seeks accessible full text, and records whether it was used in the receipt. Drafting, review and receipt verification distinguish study time windows from source currentness. Two targeted checks on 0.7.164 documented full-text use for the same study; one exposed a methodological imprecision that led to subsequent fixes. Checks on 0.7.166 include 2,127 Python tests, 511 bridge checks and 78 interface checks. Three Lantus packs were checked with their SmPC and PIL in a 0.7.158 replay. Payments are disabled; no human clinical validation or overall accuracy estimate.

[Stato e trasparenza / Current status](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence — historical

## Current status — 2 November 2026

Beta 148 unchanged, restricted access and payments inactive. Completed 20 natural real submissions:8 AIFA,6 legal and 6 Clinical Evidence;18 answers,11 useful within internally checked documentary scope,7 partial and 2 withheld by final verification. Engine median about 46 s, maximum 196 s; not time-saving or causal-comparison evidence. AI-assisted appraisal, not independent or professional validation. Cases include shared contexts, with two recorded navigation deviations. Gaps remain in mixed routing, shared leaflets, question coverage, evidence currentness and latency. Sealed report and complete governance candidate 149, NOT DEPLOYED/NO-GO, with no behavioural correction or own real questions.16 scores,19 states and 6 gates retained.

[Stato e trasparenza / Current status](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence — historical

Beta 148 deployed. Waiting steps grow downwards: existing rows stay in place and the active phase is appended at the bottom, including revisited reading. No invented progress or completion claim. Passed 67 UI and 9 version-reference checks, with a graphical simulation and no inference. Engines, server and integrated RCP/PIL reader are byte-identical to 147 except version metadata. The 54,000 cases and 560,100 checks on 147 remain historical evidence for unchanged modules, not new AI answers or a new 148 execution. Zero new real questions. No human clinical validation.

[Current status / Stato corrente](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence (historical)

Beta147 deployed. RCP and PIL are complementary sources for one answer: mandatory declared comparison,separate verdict and standard paragraph removed. Both-source reading,identity,hashes,citations,conditions,gaps and ordinary semantic review remain. Compact navigation and observed progress retained. Passed2,099 Python,64 UI and54,000 internal cases/560,100 checks:43,000 previous plus11,000 integration cases replacing the retired comparison requirement. Synthetic fixtures,not54,000 AI answers or independent paraphrases. Zero new147 real questions. Historical145 report:10submissions,8useful scoped answers,2failed comparisons;not attributed to147. Candidate146 preserved,not deployed,superseded by the new owner requirement. No human clinical validation.

[Current status / Stato corrente](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence (historical)

Beta 145 is deployed: AIFA comparisons with document-bound block selection, reorganized navigation and observed response progress. Passed 54,000 synthetic internal cases, 540,350 checks, 2,090 Python and 64 UI tests. These are not 54,000 independent questions or AI answers. Ten new AIFA-only real tests: 8 answers, 8 useful within scope, 0 partial, 2 failed. Internal AI-assisted documentary assessment; corrective candidate146 is not deployed. No human clinical validation.

[Current status / Stato corrente](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence (historical)

Beta 143 is deployed. Following two focused batches and general RCP/PIL comparison and shared-leaflet heading repairs, 54,000 internal cases and 540,350 checks passed; 2,077 Python and 57 UI. Synthetic protocols and regressions, not 54,000 independent questions or AI answers. Six new grammar errors were fixed and the same 3,000-case corpus now passes unchanged expected outcomes. Ten final real tests: 9 delivered answers; 8 useful within scope, 1 partial and 1 failed, assessed internally with AI assistance. Technical reading, scoped usefulness and professional validation remain distinct. Governance candidate 144 is not deployed; no human clinical validation.

[Current status / Stato corrente](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence (historical)

Beta 139 is live. New 10,000-case AIFA corpus and 180,400 internal checks passed; 2,031 Python and 57 UI. Ten new real AIFA tests: nine delivered answers, six useful within scope, three partial and one API error. Candidate 140 is NOT deployed: mandatory RCP/PIL comparison and EAN product-web path, with 2,050 Python/57 UI and 10,000 boundary cases passed; no own real test. API schema error remains open. No clinical validation.

[Current status / Stato corrente](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency).

---

## Previous documentation and evidence (historical)

The deployed professional beta is **0.7.138-beta**, restricted to owner-approved users; payments and answer charging remain inactive.

137 adds shared recognition of ten medicine-document question families: indications, composition, dosing/duration, administration, storage/expiry, warnings/contraindications, interactions, special populations, adverse effects and missed/excess dose. Context, source-role selection, composition and AI review use the same incomplete cues. They provide no canned answers, identity or clinical evidence. **2,002 offline regressions and58UI checks passed.50natural formulations passed200internal checks, versus83on135using the same final oracle.** This measures technical recognition and routing, not real answer coherence or clinical accuracy.0new real model questions; professional acceptance and previous specific feedback remain open. Bridges, model configuration, access, payments and UI135are retained; clinical-method explanation1.32updated. No model weight training.

**SOPHIA · Public starting points · 12 October 2026**
> Current product reference, 1 November 2026: **133 deployed**, restricted access, payments inactive. 1,988 offline,58 interface and1,150 internal checks; zero own new real questions. Persistent product references and AIFA reader improved; historical provider error cause remains open. [Current status](docs/STATUS.md).


We welcome exploratory conversations with researchers, developers, AI specialists, pharmacists and organisations. The following topics are proposed workstreams, not promises of an existing partnership or validated result.

## Opportunities open now

| Workstream | Bounded first deliverable | Join |
| --- | --- | --- |
| Medicine identity and RCP/FI reading | A fixture specification for at least three different medicines/formulations, with missing-document and ambiguity cases. | [Issue #2](https://github.com/EG2025-lab/sophia-pharmacy/issues/2) |
| Legislative references and versions | Six official-source cases with expected facts, dates and clarification conditions. | [Issue #3](https://github.com/EG2025-lab/sophia-pharmacy/issues/3) |
| Evaluation with professional review | Review the 20-question proposal, source-bound oracle and reviewer rubric before execution. | [Issue #4](https://github.com/EG2025-lab/sophia-pharmacy/issues/4) |

See the [20-question pilot protocol](pilot/README.md), [candidate questions](pilot/questions.csv) and [blank review form](pilot/review-template.csv). Contributors can start with one case family. Initial protocol and fixture work can be done without paid model calls. **[Join the pilot discussion](https://github.com/EG2025-lab/sophia-pharmacy/discussions/5).**

## 1. Reliable retrieval of official medicines documents

**Question:** Can an AI workflow consistently identify the correct medicine and package and use both the SmPC/RCP and PIL/FI?

Possible work includes document identity, parsing across formats, section coverage, source provenance and explicit handling of missing or unreadable documents. An evaluation should include similar products, ambiguous questions and unavailable sources, not only successful examples.

## 2. Legislative retrieval and grounded explanations

**Question:** Can the system retrieve the relevant official text, preserve exact references and explain what the source does and does not establish?

Possible work includes version and date tracking, exact-quotation checks, ambiguous references and separation of source text from interpretation. Professional or legal review must be scoped explicitly.

## 3. Clinical literature and guidelines

**Question:** How can retrieval through tools such as ToolUniverse lead to relevant evidence and answers that are actually supported by their citations?

Possible work includes search coverage, guideline discovery, full-text access where permitted, claim-to-source verification, conflicting findings and abstention when support is insufficient.

## 4. Evaluation and professional review

**Question:** What should a useful and trustworthy answer look like to a practising pharmacist?

Possible work includes a jointly defined rubric, comparison with alternative systems, source accuracy, task completion, response usefulness and reviewer agreement. Software-test success, answer utility and clinical validation should be reported separately.

## 5. Software and AI engineering

**Question:** How can we make the professional workflow reliable, maintainable and responsive?

Possible work includes source adapters, retrieval orchestration, observable failure states, regression testing, latency measurement and progressive answer presentation. Early work can use public documents and local fixtures without requiring paid model calls.

## A practical first step

1. Choose one narrow question and agree on the scope.
2. Define public-source or synthetic examples, expected evidence and failure cases.
3. Agree on the evaluation protocol, reviewer roles and measures before running it.
4. Record source versions, system versions, outcomes and limitations.
5. Review the results together and decide whether a larger collaboration is justified.

This is an invitation to agree a protocol. Candidate question templates are available, but their source bindings and reference answers still need to be frozen and reviewed. No executed benchmark, measured result, institutional endorsement or clinical validation is claimed.

## Contact

**Enrico Giuliano · Pharmacist · Founder & Product Lead**

[Select your collaboration interests](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners) · [Email Enrico](mailto:enrico.giuliano000@gmail.com?subject=SOPHIA%20%E2%80%94%20 collaboration)

For an initial message, please include:

- Your role and organisation, if applicable.
- The workstream or question that interests you.
- Relevant experience or a public project link.
- A small first step you would propose.

Do not send patient data, credentials or confidential third-party documents. Public discussions are suitable for general technical questions; use the email contact route for an initial professional introduction.


**Language and process gate — 1 November 2026: NO-GO.** Beta137: the new language and process gate has not passed.30,000internal combinations,10,000per domain:21,166PASS and8,834FAIL against technical oracles. These combine300formulations with contexts, references and task modes, not30,000AI answers or independent paraphrases. Gaps concern AIFA paraphrases/references, negation, clinical needs and a false block of a legal-document question. Cues are incomplete: a FAIL does not prove a wrong real answer.2,002Python regressions and57UI tests under the new command passed;0new model answers. Next phase held, no new app release or bridge change.


**Version138 ready for real tests.** Beta138: shared causes behind the language/process gate corrected. The same137corpus improves from21,166to30,000passed cases out of30,000:10,000AIFA,10,000legislation,10,000Clinical Evidence;315,600checks passed. These combine300formulations with contexts and task modes,not30,000AI answers or independent paraphrases.2,023Python regressions and57UI tests passed. Negation scope,needs/references,documentary objects and legal-version requests improved. Privacy28and method1.33;same bridges and models. Ready for real tests:0new generated answers,quality and usefulness still need measurement. Technical PASS proves neither every possible variant nor clinical/legal validation.
