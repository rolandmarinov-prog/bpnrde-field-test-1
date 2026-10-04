# PRE-REGISTRATION — BPNRDE Field Test 1

**Reversal nodes and human delay in a live, high-visibility cascade risk: the US federal general election of 3 November 2026**

| | |
|---|---|
| Version | 1.1 — frozen at registration; any change is a new version with a logged deviation (see §12) |
| Drafted | 4 October 2026 |
| Principal investigator | Roland Marinov (Toronto) |
| Drafting assistance | Claude (an AI model by Anthropic). Declared: an AI system drafted this protocol; the PI ratifies it. |
| Outside review | ChatGPT (an AI model by OpenAI), fresh session, 4 October 2026, before registration |
| Funding | None |
| Observation window | From public registration (the timestamp of the GitHub release v1.1) → 3 January 2027 23:59 ET (the new Congress convenes 3 January). Events between 4 October 2026 00:00 ET and registration are logged separately as non-prospective and excluded from H0–H4. |
| Registration | Hash of this file recorded externally before any event is coded (see §10) |

---

## 0. Provenance

The prediction was first stated on **3 October 2026 (evening, Toronto)** in a working conversation, and formalised as this protocol on **4 October 2026**. It draws on public reporting available at the time, including reporting from the preceding months on possible federal interference in the 2026 midterm elections.

What is registered here is **not a claim of foresight but a test**: hypotheses, thresholds and data rules fixed before the outcome is known. Later reporting — including coverage published on 4 October 2026 of preparations for election-interference scenarios — is context, not confirmation, and does not alter any element of this protocol.

The framework under test (BPNRDE) was developed between 28 September and 4 October 2026 by the PI, with AI assistance declared above. Version 1.0 was posted as a readable copy on 4 October 2026 before the required outside review; version 1.1 incorporates that review (see §12).

---

## 1. Purpose

To test, **prospectively**, whether the BPNRDE framework ("Breaking Point – No Return – Domino Effect") describes how disruption attempts are stopped. Every previous application was retrospective; this is the first test whose outcome is unknown at the time of writing.

**This study does not forecast who wins, and it does not assess the merits of any party, candidate or policy.** It measures *where* and *how fast* attempts to disrupt an election are stopped, whoever makes them.

## 2. Framework claims under test

1. A cascade passes a sequence of **reversal nodes**, each with its own point of no return.
2. Reversal is cheapest at the **earliest** node and grows costlier at each later one.
3. **Pre-commitment** (responses prepared before the event) shortens human delay.
4. Where hands with authority to say no remain at the gaps, cascades are stopped **before** the final point of no return.

## 3. Definitions

**3.1 Qualifying event.** An event qualifies only if all three conditions hold:

- **(a) Substance.** An action by **any actor** — federal, state or local officials, parties, campaigns, private persons, foreign actors — that obstructs or alters the casting, counting, certification or seating of a 2026 federal election result, **or** a documented directive, order, filing, operational action or other concrete act explicitly indicating an intention to do so.
- **(b) Institutional response.** Documentary evidence, dated within the observation window, of at least one institutional response specifically contesting, restraining, refusing or otherwise attempting to prevent that action.
- **(c) Initiation.** The first documented act constituting the event occurred within the observation window. If evidence establishes that the event began before the window, it is excluded, even if its consequences or public disclosure fall inside the window.

Candidates meeting (a) and (c) but not (b) are logged as **unchallenged candidates** and excluded from H0–H4.
**Lawful election contests** — petitions filed under a state's election-contest or recount statutes, by any party or candidate — are logged as **contest events** and coded with the same fields, but analysed separately and excluded from H0–H4. A contest event is an action expressly filed under an applicable statutory election-contest, recount, or equivalent post-election review procedure; litigation seeking emergency relief against an ongoing election-related action is not a contest event merely because it concerns election results.
Excluded in all cases: litigation over election rules filed before 4 October 2026; ordinary election administration; enforcement of generally applicable law; isolated individual misconduct without institutional involvement; disinformation not tied to an official or institutional act.

**3.2 Node ladder and assignment.**

| Node | Intervention |
|---|---|
| N0 | Other authorised intervention not represented in N1–N7 (for example police, a platform or network operator, a cyber-response team) |
| N1 | Local election official (refusal, procedure, local order) |
| N2 | State election authority (secretary of state, state board) |
| N3 | Trial court (temporary restraining order, injunction) |
| N4 | Command refusal (governor withholding Guard; military or agency refusing an order) |
| N5 | Appellate or supreme court |
| N6 | Certification (state canvass, certifying board) |
| N7 | Seating (Congress, 3 January 2027) |
| N∞ | Not stopped within the window |

**Assignment rule.** Each event receives exactly one stopping node: the node of the **first intervention in time** that renders the attempted disruption ineffective (§3.3, t_S). Later proceedings about the same attempt do not change the assignment. If two interventions take effect at the same documented time, the lower-numbered node is assigned. N0 is assigned only when no N1–N7 intervention is the first effective stop.
**Reaching a node.** An event *reaches* a node when an intervention at that node is issued or attempted, whether or not it is effective.

**3.3 Timestamps** (each recorded as a range, with source):
- **t_A** attempt — the first documented act constituting the event
- **t_F** flag — the first documented institutional response under §3.1(b)
- **t_D** decision — the stopping intervention is issued (order signed, refusal documented)
- **t_S** stop — the first time at which the action is legally or operationally prevented from producing the specific election effect recorded when the event was entered. A temporary intervention counts as a stop only if it remains effective through the event's deadline, or is replaced without interruption by another effective intervention.
- **t_PNR** — the event's own deadline (polls close, statutory certification date, 3 January seating)

**3.4 Derived** (never entered by hand): human delay **H = t_D − t_F**; margin **M = t_PNR − t_S** (positive = stopped in time).

**3.5 Scope.** When an event is entered, and before any node data are coded, one unit is chosen for it — voters, ballots, precincts or jurisdictions — and that unit is used for every measurement of the event. Scope at a node is the number of affected units immediately before that node's intervention takes effect. Events for which scope cannot be measured in the chosen unit at both compared nodes are excluded from H2.

**3.6 Pre-commitment** = documented evidence, dated before t_A, that the stopping actor had a prepared response (pre-drafted filing, standing order, published plan).

**3.7 Evidence grade.** Each timestamp carries a source rung — leaked draft · filed document · official statement · raw record · independent replication · deployment observation · controlled test — and a clock grade: recollection · single self-written record · single machine clock · two independent clocks. Derived values inherit the weaker grade.

**3.8 Guard status.** Where a Guard unit changes status during a deployment, its status at the time of physical deployment to the relevant site governs.

## 4. Hypotheses and decision rules

Thresholds are fixed now. All inequalities are inclusive or exclusive exactly as printed; percentages are computed from integer counts without rounding. Values meeting neither condition are **inconclusive**. Example: 7 of 10 events is 70% and meets "≥ 70%".

| # | Hypothesis | Supported if | Falsified if |
|---|---|---|---|
| **H0** | **Reliability gate.** The two coders independently agree on (a) whether the candidate qualifies, (b) its stopping node, and (c) a t_D range whose intersection is non-empty. Denominator: all candidates that both coders are asked to classify as qualifying disruption events; contest events and unchallenged candidates are excluded | ≥ 80% of candidates meet all three | < 60%. **If H0 fails, no other hypothesis is tested.** |
| **H1** | **Earliest nodes stop most.** Share of **all** qualifying events, including N∞, whose stopping node is N0–N3 | ≥ 70% | < 50% |
| **H2** | **Scope is greater at the stop than at the first node** (endpoint escalation, not monotonic escalation at every node). Among qualifying events whose effective stopping node is later than the first node reached, with measurable scope at both, share in which scope immediately before the **effective stopping node** is strictly greater than immediately before the **first node reached**. Events assigned N∞ are excluded. Unit of analysis: the event | ≥ 75% | ≤ 50% |
| **H3** | **Pre-commitment shortens delay.** Median H with pre-commitment ÷ median H without. Computed only if the median without pre-commitment is greater than zero; otherwise inconclusive | ≤ 0.5 | ≥ 1.0 |
| **H4** | **Hands hold.** No qualifying event, from any actor, results in (a) an altered or invalidated certified federal result, (b) a federal result not certified by the state's statutory deadline, or (c) a certified member-elect not being seated, by 3 January 2027 | zero such events | one or more |

Minimum data: H1 and H2 require ≥ 10 eligible events each; H3 requires ≥ 5 in each group. Below that, results are reported descriptively only.

## 5. Data sources (fixed in advance)

- Court dockets: PACER, CourtListener, state court systems
- Official releases: state election authorities, the Department of Justice, governors' offices, the Department of Defense
- Wire services: Associated Press, Reuters

**Rule:** every event needs at least two independent sources, at least one being a docket, an official document or a wire service. Advocacy organisations of any orientation may be used to *find* events, never as the sole source for a coded value.

## 6. Coding procedure

1. **Event log** opened at registration; candidates entered as they occur, with the date of entry and the scope unit chosen.
2. **Two independent coders**: (a) the PI; (b) a blind coder — a model from a non-Anthropic family in a fresh session, given only the source documents and §3, and none of the hypotheses. A human second coder is preferred if available.
3. Disagreements are recorded, not resolved by discussion; both values are kept for H0.
4. Coding closes 31 January 2027.

## 7. Analysis plan

Descriptive tables for every candidate and event; tests in the order H0 → H1 → H2 → H3 → H4; no other hypotheses are tested from this data without being labelled exploratory. Every deviation from this protocol is listed in §12 and in the report, with its date and reason.

## 8. Known limitations, stated in advance

- **Small n.** Results describe; they don't prove.
- **Selection.** Only events with an institutional response are tested; unchallenged candidates are logged but excluded.
- **Disclosure dating.** Public dates can lag true onset, shortening apparent delays.
- **Hindsight.** t_A may be identified only later; mitigated by recording the date each candidate was logged.
- **Adversarial actors** choose their own timing; the framework describes the stopping side, not the strategy.
- **Political sensitivity.** Coders may hold views. Mitigation: symmetric definitions, fixed sources, blind second coder.

## 9. Separate personal forecasts (scored independently; do not affect §4)

Recorded by the PI **before registration**; scored with the Brier score on 4 January 2027.

| # | Event, registration – 3 Jan 2027 | PI probability |
|---|---|---|
| P1 | At least one federal executive or administrative action, **initiated during the observation window**, that would otherwise obstruct or alter the casting, counting, certification or seating of a 2026 federal election result is blocked by a court or held unlawful during the window. Ordinary election administration, enforcement of generally applicable law, and litigation about pre-existing election rules do not qualify | **55 %** |
| P2 | Federal troops, federalised National Guard (including at a governor's request), or state National Guard deployed by a governor on state authority are physically present, under military or Guard command and in an operational capacity, at or within 1 mile (1.6 km) of a polling, counting, canvassing or certification site, where the deployment order, activation order, official announcement, or a contemporaneous official statement explicitly identifies the 2026 federal election, a polling, counting, canvassing or certification site, or election-related security as the reason for or operational context of the deployment. Excluded: civilian poll-worker service; cyber or IT support; logistics; ballot transport; deployments under a disaster or emergency declaration made for reasons unrelated to the election | **35 %** |
| P3 | A federal or state authority formally declares martial law in response to conduct arising from or materially related to the 2026 federal election. "Martial law" means an official proclamation or order expressly invoking martial law, or expressly transferring specified civilian governmental functions to military authority. Curfews, states of emergency, disaster declarations and military assistance to civilian authorities do not qualify unless they meet this definition | **20 %** |
| P4 | **Conditional.** *If* the party holding a majority of voting seats in the House immediately before Election Day does not hold a majority of voting seats when the new House convenes on 3 January 2027 ("majority" meaning more than half of the seats entitled to vote, excluding vacancies), then the President publicly states, after polls close on 3 November 2026 and before 3 January 2027, that the 2026 election was rigged, stolen or fraudulent (or an equivalent claim that the result is illegitimate because of fraud), in a speech, interview, or post on an official or personal account. **Scored only if the condition is met**; otherwise void. A void P4 receives no Brier score and is excluded from any aggregate forecast score | **95 %** |

**Resolution rule.** Each forecast is resolved by applying its registered definition to the public record as of 4 January 2027: YES if and only if the stated condition is met, otherwise NO. The PI records the evidence for each resolution. If the definition genuinely admits two readings of the record, both readings are recorded, the Brier score is computed both ways, and both are reported.

Condition noted by the PI: P2 and P3 assume the governing party's majority is at risk; pre-election polling was mixed on this as of registration.

## 10. Registration and reproducibility

1. The PI fills §9, then the file is frozen.
2. SHA-256 of the frozen file is computed and recorded in at least **two independent places** outside the PI's machine: the public GitHub release (v1.1), which also retains v1.0 for transparency, **and** an Internet Archive snapshot of the released file. OSF Registries is optional.
3. The event log, every source link, both coders' values and the analysis are published with the report.
4. Anyone can re-create the study by applying §3–§7 to the same sources, or to a different election.

## 11. Timeline

| Date | Milestone |
|---|---|
| by 6 Oct 2026 | §9 filled; hash recorded; registered |
| registration – 3 Jan 2027 | Observation; event log maintained |
| 4 Jan 2027 | Personal forecasts scored |
| 31 Jan 2027 | Coding closes |
| by 28 Feb 2027 | Report published, including any failed hypotheses |

## 12. Deviation log

| # | Date | Deviation | Reason |
|---|---|---|---|
| D1 | 4 Oct 2026 | v1.0 was posted as a readable copy on 369369369.org before the outside review required by the PI's own review rule. v1.1 supersedes it before registration. | Outside review found defects in forecast definitions, hypothesis denominators, node assignment, the definition of a stop, and the scope unit. All accepted changes are incorporated; two proposed changes were modified (P2: objective markers replace a purpose test; H2: events rather than node-pairs as the unit of analysis, since pairs within one event are not independent). |
| D2 | 4 Oct 2026 | Added P4 (conditional forecast) and the contest-event rule in §3.1. | PI's addition before registration: lawful election contests are normal democratic process and are separated from disruption events to keep the protocol neutral; P4 records a forecast the PI wished to register. |
| D3 | 4 Oct 2026 | Second outside review (ChatGPT, same session) of v1.1 before registration; six edits: contest events excluded from H0 and defined; H2 renamed and anchored to the effective stopping node, N∞ excluded; P2's election link made a documentary marker; P4's majority reference and void scoring defined. | Reviewer found these ambiguities; all adopted. v1.1 had not been published, so the version number is unchanged and the hash is new. |

*A result that falsifies a hypothesis is reported with the same prominence as one that supports it.*
