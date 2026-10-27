# Collaboration brief
**SOPHIA · Public starting points · 12 October 2026**
> Current product reference, reviewed27October2026: **0.7.97-beta**, owner-approved access only. Automatic admission, real payments and adaptive routing are disabled.97 preserves the95 engine; candidate96 was not promoted after its sole failed replay. Technical access checks are not professional or clinical validation. The20-question pilot remains a proposal; no tester invitation, partnership or access is implied. [Current status](docs/STATUS.md).


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

[Select your collaboration interests](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners) · [Email Enrico](mailto:enrico.giuliano000@gmail.com?subject=SOPHIA%20%E2%80%94%20collaboration)

For an initial message, please include:

- Your role and organisation, if applicable.
- The workstream or question that interests you.
- Relevant experience or a public project link.
- A small first step you would propose.

Do not send patient data, credentials or confidential third-party documents. Public discussions are suitable for general technical questions; use the email contact route for an initial professional introduction.
