# Contributing to SOPHIA
> Current product reference, reviewed 26 October 2026: restricted beta **0.7.88**, with a separate six-answer engineering battery. The public 20-question pilot is still a proposal, not frozen, executed or professionally validated. See [current status](docs/STATUS.md). No new partner commitment or access is implied.


**English and Italian contributions are welcome. / Puoi contribuire in italiano o in inglese.**

This is the public documentation and collaboration repository for SOPHIA. Application source code, credentials and restricted beta conversations are not included. A first contribution can improve public-source metadata, case specifications, documentation or evaluation design; no application access or paid model call is needed.

## Choose a first contribution

| Start here | Scope | Background |
| --- | --- | --- |
| One RCP/FI source pair | Complete the [blank source-pair template](pilot/source-pair-template.json) for one medicine and record ambiguity or missing information. Do not write a clinical reference answer. | A newcomer can prepare metadata; medicine identity still requires pharmacist review. |
| [Medicine-document workstream](https://github.com/EG2025-lab/sophia-pharmacy/issues/2) | Extend fixtures across different medicines, formats and failure conditions. | Document parsing, retrieval or pharmacy knowledge. |
| [Legislative workstream](https://github.com/EG2025-lab/sophia-pharmacy/issues/3) | Bind one candidate case to an exact official provision and date before expanding to six cases. | Italian pharmaceutical legislation or retrieval engineering. |
| [Evaluation workstream](https://github.com/EG2025-lab/sophia-pharmacy/issues/4) | Review one question family or one rubric dimension in the [proposed pilot](pilot/README.md). | Pharmacist review or AI evaluation. |

## A small, reviewable workflow

1. Check existing issues to avoid duplicating work. Comment on the relevant workstream or [propose a collaboration](https://github.com/EG2025-lab/sophia-pharmacy/issues/new?template=collaboration.yml). Describe one deliverable and the time you can realistically offer; agree scope before a substantial contribution.
2. Use public official links and explicitly synthetic examples. If a source is inaccessible or ambiguous, record that limitation rather than guessing. Check source access and reuse conditions; a public URL is not permission to redistribute a document.
3. For a documentation or metadata change, fork this repository, make a small branch and open a pull request. Alternatively, propose the change in the issue and ask for help with GitHub. Include the source/date and the reason for your change.
4. The maintainer checks scope and provenance. Clinical facts and legal applicability need a reviewer with the relevant expertise. A merged contribution does not automatically become an approved oracle or evidence of product performance.

For a source-pair contribution, copy the template into `pilot/proposals/<short-case-name>.json`, retain `CANDIDATE_NOT_REVIEWED`, and leave anything unknown explicitly null. Include URLs and document metadata, not PDF uploads or copied document passages. The maintainer can help a first-time contributor.

## What a useful contribution records

- The professional question or information need it addresses.
- Official source URLs, retrieval date, product or act identity, and revision where available.
- Expected successful behaviour and at least one related ambiguous or contrary case.
- Remaining uncertainties, the checks performed and what still needs professional review.

Do not commit patient data, credentials, private conversations, source code from another project or confidential third-party material. This repository has no open-source application licence; its public availability does not grant rights to the proprietary app or to third-party documents. Any additional research, publication, compensation or commercial terms require separate agreement. You must have the right to share what you submit publicly.

## Communication

Use issues for a concrete proposal or documentation correction and [Discussions](https://github.com/EG2025-lab/sophia-pharmacy/discussions) for general questions. Be respectful, explain evidence and disagreements, and avoid personal clinical cases. No response time, appointment or partnership is promised.

For a private introduction or a security concern, use [Enrico's email](mailto:enrico.giuliano000@gmail.com?subject=SOPHIA%20%E2%80%94%20contact) or the [website contact route](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners). Do not post an exploitable vulnerability publicly.

## In italiano

Scegli un contributo piccolo e verificabile, poi concorda il perimetro in una delle issue. Non serve saper programmare per proporre quesiti, controllare una fonte o migliorare la documentazione. Se vuoi iniziare dai documenti AIFA, prepara solo i metadati di una coppia RCP/FI: l'identità del medicinale e il successivo uso nel pilota devono essere riesaminati. Per un aiuto con GitHub, scrivi nella relativa issue. Il [README italiano](README.it.md) presenta progetto, opportunità e contatti.
