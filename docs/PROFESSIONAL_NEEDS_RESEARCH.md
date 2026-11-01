# Professional-needs research

The deployed professional beta is **0.7.137-beta**, restricted to owner-approved users; payments and answer charging remain inactive.

137 adds shared recognition of ten medicine-document question families: indications, composition, dosing/duration, administration, storage/expiry, warnings/contraindications, interactions, special populations, adverse effects and missed/excess dose. Context, source-role selection, composition and AI review use the same incomplete cues. They provide no canned answers, identity or clinical evidence. **2,002 offline regressions and58UI checks passed.50natural formulations passed200internal checks, versus83on135using the same final oracle.** This measures technical recognition and routing, not real answer coherence or clinical accuracy.0new real model questions; professional acceptance and previous specific feedback remain open. Bridges, model configuration, access, payments and UI135are retained; clinical-method explanation1.32updated. No model weight training.


> Current product reference, 1 November 2026: **133 deployed**, restricted access, payments inactive. 1,988 offline,58 interface and1,150 internal checks; zero own new real questions. Persistent product references and AIFA reader improved; historical provider error cause remains open. [Current status](STATUS.md).

Reviewed **26 October 2026** against restricted beta **0.7.88** and the actual website flow. This is exploratory, self-selected research, not clinical or market validation.

## Current website flow

On the [public website](https://sophia-pharmacy.enricogiuliano.chatgpt.site/), the survey and waitlist are independent choices. The optional waitlist checkbox is initially selected; participants may clear it and submit only their survey. Role and at least one information priority are required. **Email is required only if the participant chooses the waitlist or a separate interview.** Survey-only records do not acquire an email merely because one was typed in an unrelated field.

Pharmacist roles distinguish employee, pharmacy owner and freelance pharmacist. Older generic role codes remain historical rather than being relabelled. Pharmacy networks and other professional interests retain their applicable choices; developers, AI specialists and researchers have a separate collaboration path. Detail is required for “materials/procedures” or “another need”; other work context, hypothetical budget, payment preference, name, organisation and declared region are optional within their displayed conditions.

Current notice: `sophia-public-2026-10-18-05`. Actions are `survey_only` with `professional_needs` scope, or `survey_and_waitlist` with `early_access_needs` scope. Interview availability is a separate explicit choice. Earlier notices and already-open forms retain their own requirements and purposes; no historical consent is widened.

Submission is acknowledged only after a valid server receipt. Errors retain the form answers. The flow does not automatically send email, open beta access or reserve a paid product. An email alternative prepares a draft for the participant to send and does not itself create a website record. Collaboration messages do not automatically join a waitlist.

## Interpreting the findings

The owner dashboard counts surveys, waitlist choices and interviews separately; a response can have more than one purpose. Submissions are not necessarily unique people, verified pharmacists, paid reservations, active app users or demonstrated willingness to pay. Budget ranges are exploratory questions, not prices or offers. No new market findings are claimed by this documentation update.

Navigation statistics are separate, enabled by default with footer opt-out and explicit owner/test-profile exclusions. Visits are not automatically joined to named survey responses. Region from a survey is self-declared; visit geography is an indicative estimate with a separately stated source. Unknown geography and uncollected history are not reconstructed. Collection is not guaranteed for every visitor.

Owner access uses ChatGPT sign-in, not a separate SOPHIA password. The private dashboard and exports require server-side owner authorisation. Survey records and contact details are not public files. See the [current privacy notice](https://sophia-pharmacy.enricogiuliano.chatgpt.site/privacy).

Do not submit patient data, credentials or confidential third-party material. Public findings require appropriately aggregated, non-identifying reporting. The 20-question professional evaluation remains a separate proposal; technical engineering batteries do not complete it. [Status and limits](STATUS.md).


**Language and process gate — 1 November 2026: NO-GO.** Beta137: the new language and process gate has not passed.30,000internal combinations,10,000per domain:21,166PASS and8,834FAIL against technical oracles. These combine300formulations with contexts, references and task modes, not30,000AI answers or independent paraphrases. Gaps concern AIFA paraphrases/references, negation, clinical needs and a false block of a legal-document question. Cues are incomplete: a FAIL does not prove a wrong real answer.2,002Python regressions and57UI tests under the new command passed;0new model answers. Next phase held, no new app release or bridge change.
