# A 20-question pilot for professional pharmacy knowledge

**SOPHIA · Proposal v0.1 · 12 October 2026 · NOT RUN**

We are looking for pharmacists, software developers and AI researchers to help design a small, reproducible evaluation of SOPHIA. The purpose is to find where answers succeed, where they fail, and which mechanisms need improvement across similar cases.

SOPHIA is an independent application under development, founded by **Enrico Giuliano, pharmacist and Founder & Product Lead**. FarmAI, our custom GPT, is its starting point. This repository hosts the public proposal; application code and restricted beta conversations are not published here.

## The proposed first deliverable

A jointly agreed protocol and 20 source-bound professional questions, followed by independently reviewed results if we agree to execute the pilot. We invite contributions to the protocol before any model run.

| Workstream | Candidate questions | What we want to assess |
| --- | ---: | --- |
| Official medicines documentation | 8 | Correct package; both SmPC/RCP and PIL/FI; section coverage; missing or conflicting documents. |
| Italian pharmaceutical legislation | 6 | Exact references; date and territorial applicability; source text versus interpretation. |
| Clinical evidence and guidelines | 4 | Relevance; accessible evidence; citation support; conflicting findings. |
| Multiple domains and boundaries | 2 | Appropriate routing and safe handling of requests outside the intended purpose. |
| **Total** | **20** | **Technical correctness, answer usefulness and review limits reported separately.** |

[questions.csv](questions.csv) contains **candidate task templates**, including Italian prompts. Braces such as `{AIC}` must be replaced with agreed public identifiers, document versions and dates. These are not yet a frozen benchmark: no answers, results or completed reviewer assessments are claimed.

## People we would like to involve

- A pharmacist to define the professional needs and the reference answers.
- A second pharmacist to review answers independently and record disagreements.
- A developer or AI evaluator to check document identity, reproducibility, failure handling and measurement.

These are invited roles, not confirmed appointments. Enrico can contribute pharmacy context and coordination; a review attributes only the checks actually performed on that answer. Contributors can begin with one workstream or a small subset of cases.

## Protocol before execution

1. **Agree the scope.** Use general professional questions, public sources and explicitly synthetic boundary cases. Exclude patient records, confidential documents and individual treatment decisions.
2. **Freeze the reference material.** Bind each question to exact identifiers, authoritative URLs, document revisions, retrieval dates and SHA-256 hashes. Check access and reuse permissions. A cached document proves the captured version only; it does not establish current validity.
3. **Write the oracle first.** List every information need, its expected supported fact or expected clarification/abstention, source section or page, and critical failure conditions. A qualified reviewer checks it before seeing system answers. Keep fixture failure conditions and expected outcomes in the evaluator material, not as hints inside the user question. [ORACLE_TEMPLATE.json](ORACLE_TEMPLATE.json) provides the structure; it contains no reference answers.
4. **Check the fixtures without paid model calls.** Test routing, package identity, RCP/FI association, parsing, section coverage and deterministic boundary controls. Report these as technical tests, not answer-quality results.
5. **Agree execution separately.** Select the system versions, access arrangement, comparison method, spending limit and recording procedure. Paid model calls require a separately agreed budget. The publication of this proposal does not start any model run.
6. **Record and review.** Preserve the complete answers, tool outcomes, source receipts, timestamps and failures. Review against the frozen oracle, independently where possible. Keep both original reviewer assessments and any subsequent adjudication.
7. **Publish the limits.** Report per-case and per-need outcomes, denominators and unassessed cases. A sample of 20 questions cannot establish clinical efficacy, broad accuracy, regulatory conformity or readiness for unrestricted use.

## Review rubric

Each applicable dimension receives **0, 1 or 2**: 0 = wrong, absent or unsupported; 1 = partly met with a material gap; 2 = met with adequate source support. Use **N/A** when a dimension does not apply; record an invalid or ambiguous oracle as **NOT_ASSESSED**, with a reason.

| Dimension | What the reviewer checks |
| --- | --- |
| Identity and applicability | Correct medicine/package, population, jurisdiction and relevant version/date. |
| Need coverage | Every requested point answered or explicitly identified as unsupported. |
| Source support | Each substantive claim traceable to the appropriate document, section or page. |
| Uncertainty and boundaries | Missing access, conflicting sources and scope limits stated accurately; appropriate clarification or abstention. |
| Professional clarity | Direct, readable answer useful to a pharmacist, with citations that can be inspected. |

**Critical errors override averages:** wrong medicine or package; fabricated reference, quotation or source; falsely claiming to have read unavailable full text; inappropriate disclosure of patient data; or an individual therapeutic decision outside scope. A timeout or failed retrieval is recorded as a failure, never converted into a successful answer by omitting it.

Measure coverage at the level of individual needs, not only whole-answer impressions. Report critical failures and ordinary incompleteness separately. Reviewer agreement, usefulness and technical test outcomes are different measures.

If the team wants a binary acceptance decision, define and freeze its threshold and allowable non-critical gaps **before execution**. No critical error is acceptable for a positive pilot decision; passing this small pilot would still not establish general validation.

## Timing and cost

Record time to the first source-verified content, the first information judged useful by a pharmacist, and the complete response. Progress messages alone are not useful answers. Preserve request failures and partial streams. Record model/tool usage and actual cost when available; missing values remain unknown.

Any claim of time saved needs a comparable manual task, the same evidence requirements and a planned comparison order. We have not measured or claimed savings through this proposal.

## Generalisation and reproducibility

For each case family, agree additional unseen variants before a later validation round: another medicine or formulation, a different document format or revision, a similar law reference, and a contrary case where clarification or abstention is correct. Keep these variants out of development feedback until evaluation.

A fix must address the failing mechanism. A memorised answer or exception for one question does not count as a general improvement. Record system revision, source hashes and any changes between rounds; never overwrite earlier results.

[review-template.csv](review-template.csv) provides 20 empty result rows. All are **NOT_RUN**. Its score cells are intentionally blank.

## Join the pilot

Introduce yourself in the **[pilot discussion](https://github.com/EG2025-lab/sophia-pharmacy/discussions/5)**, select your interest through the [SOPHIA contact page](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners), or [email Enrico](mailto:enrico.giuliano000@gmail.com?subject=SOPHIA%20%E2%80%94%2020-question%20pilot).

Please share your role, relevant public experience, the workstream that interests you and a small first contribution. Participation, access to restricted beta material, publication credit and any commercial or research terms must be agreed separately. No institutional partnership, funding, compensation or outcome is promised by this invitation.

Keep patient data, credentials and confidential material out of public comments. Source permissions must be checked individually; a public link does not permit unrestricted redistribution of its contents.
