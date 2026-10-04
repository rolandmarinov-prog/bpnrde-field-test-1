# PRE-REGISTRATION — BPNRDE Field Test 1

**Reversal nodes and human delay in a live, high-visibility cascade risk: the US federal general election of 3 November 2026**

| | |
|---|---|
| Version | 1.0 — frozen at registration; any change is a new version with a logged deviation |
| Drafted | 4 October 2026 |
| Principal investigator | Roland Marinov (Toronto) |
| Drafting assistance | Claude (an AI model by Anthropic). Declared: an AI system drafted this protocol; the PI ratifies it. |
| Funding | None |
| Observation window | From public registration (the timestamp of the GitHub release v1.0) → 3 January 2027 23:59 ET (the new Congress convenes 3 January). Events between 4 October 2026 00:00 ET and registration are logged separately as non-prospective and excluded from H1–H4. |
| Registration | Hash of this file to be recorded externally before any event is coded (see §10) |

---

## 0. Provenance

The prediction was first stated on **3 October 2026 (evening, Toronto)** in a working conversation, and formalised as this protocol on **4 October 2026**. It draws on public reporting available at the time, including reporting from the preceding months on possible federal interference in the 2026 midterm elections.

What is registered here is **not a claim of foresight but a test**: hypotheses, thresholds and data rules fixed before the outcome is known. Later reporting — including coverage published on 4 October 2026 of preparations for election-interference scenarios — is context, not confirmation, and does not alter any element of this protocol.

The framework under test (BPNRDE) was developed between 28 September and 4 October 2026 by the PI, with AI assistance declared above.

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

**3.1 Qualifying event.** Any action, by **any actor** — federal, state or local officials, parties, campaigns, private persons, foreign actors — that obstructs, alters, or credibly threatens the casting, counting, certification or seating of a federal election result, **and** that is formally challenged (court filing, official order, or an official's documented refusal). Events must be *initiated* inside the window.
Excluded: litigation over election rules filed before 4 October 2026; isolated individual misconduct without institutional involvement; disinformation not tied to an official or institutional act.

**3.2 Node ladder (fixed in advance).** For each event, the node at which it was stopped:

| Node | Hand |
|---|---|
| N1 | Local election official (refusal, procedure, local order) |
| N2 | State election authority (secretary of state, state board) |
| N3 | Trial court (temporary restraining order, injunction) |
| N4 | Command refusal (governor withholding Guard; military or agency refusing an order) |
| N5 | Appellate or supreme court |
| N6 | Certification (state canvass, certifying board) |
| N7 | Seating (Congress, 3 January 2027) |
| N∞ | Not stopped within the window |

**3.3 Timestamps** (each recorded as a range, with source):
- **t_A** attempt — first documented act
- **t_F** flag — first public challenge or official report
- **t_D** decision — order issued or refusal documented
- **t_S** stop — the decision takes effect
- **t_PNR** — the event's own deadline (polls close, statutory certification date, 3 January seating)

**3.4 Derived** (never entered by hand): human delay **H = t_D − t_F**; margin **M = t_PNR − t_S** (positive = stopped in time).

**3.5 Scope proxy** for cost: units affected at the moment of stop — voters, ballots, precincts or jurisdictions, whichever the sources report. Same unit compared within an event.

**3.6 Pre-commitment** = documented evidence, dated before t_A, that the stopping actor had a prepared response (pre-drafted filing, standing order, published plan).

**3.7 Evidence grade.** Each timestamp carries a source rung — leaked draft · filed document · official statement · raw record · independent replication · deployment observation · controlled test — and a clock grade: recollection · single self-written record · single machine clock · two independent clocks. Derived values inherit the weaker grade.

## 4. Hypotheses and decision rules

Thresholds are fixed now. Results between the "supported" and "falsified" bounds are reported as **inconclusive**.

| # | Hypothesis | Supported if | Falsified if |
|---|---|---|---|
| **H0** | **Reliability gate.** Two independent coders agree on the stopping node, and their t_D ranges overlap | ≥ 80% of events | < 60%. **If H0 fails, no other hypothesis is tested.** |
| **H1** | **Earliest nodes stop most.** Events stopped at N1–N3 | ≥ 70% of stopped events | < 50% |
| **H2** | **Cost escalates.** For events passing ≥ 2 nodes, scope at the later node exceeds scope at the earlier | ≥ 75% of such events | ≤ 50% |
| **H3** | **Pre-commitment shortens delay.** Median H with pre-commitment ÷ median H without | ≤ 0.5 | ≥ 1.0 |
| **H4** | **Hands hold.** No qualifying event, from any actor, changes a certified federal result or prevents a member-elect's seating by 3 January 2027 | zero such events | one or more |

Minimum data: H1 and H2 require ≥ 10 qualifying events; H3 requires ≥ 5 in each group. Below that, results are reported descriptively only.

## 5. Data sources (fixed in advance)

- Court dockets: PACER, CourtListener, state court systems
- Official releases: state election authorities, the Department of Justice, governors' offices, the Department of Defense
- Wire services: Associated Press, Reuters

**Rule:** every event needs at least two independent sources, at least one being a docket, an official document or a wire service. Advocacy organisations of any orientation may be used to *find* events, never as the sole source for a coded value.

## 6. Coding procedure

1. **Event log** opened at registration; events entered as they occur, with the date of entry.
2. **Two independent coders**: (a) the PI; (b) a blind coder — a model from a non-Anthropic family in a fresh session, given only the source documents, the definitions in §3, and none of the hypotheses. A human second coder is preferred if available.
3. Disagreements are recorded, not resolved by discussion; both values are kept for H0.
4. Coding closes 31 January 2027.

## 7. Analysis plan

Descriptive tables for every event; tests in the order H0 → H1 → H2 → H3 → H4; no other hypotheses are tested from this data without being labelled exploratory. Every deviation from this protocol is listed in the report with its date and reason.

## 8. Known limitations, stated in advance

- **Small n.** Results describe; they don't prove.
- **Selection.** Only challenged events are counted; unchallenged disruptions are invisible.
- **Disclosure dating.** Public dates can lag true onset, shortening apparent delays.
- **Hindsight.** t_A may be identified only later; mitigated by recording the date each event was logged.
- **Adversarial actors** choose their own timing; the framework describes the stopping side, not the strategy.
- **Political sensitivity.** Coders may hold views. Mitigation: symmetric definitions, fixed sources, blind second coder.

## 9. Separate personal forecasts (scored independently; do not affect §4)

Recorded by the PI **before registration**; scored with the Brier score on 4 January 2027.

| # | Event, registration – 3 Jan 2027 | PI probability |
|---|---|---|
| P1 | Any federal action targeting voting, counting or certification — whenever it was taken — is blocked by a court or found unlawful during the window | **65 %** |
| P2 | Federal troops or federalised National Guard (including at a governor's request), **or** state National Guard deployed by a governor on state authority, are deployed **as a force presence** — armed, or in uniform in a security, law-enforcement or crowd-control role — at or around polling or counting sites in at least one state. Excludes Guard members serving as civilian poll workers, in cyber or IT support, logistics, or ballot transport | **45 %** |
| P3 | Martial law is formally declared anywhere in the US in connection with the election | **20 %** |

Condition noted by the PI: P2 and P3 assume the governing party's majority is at risk; pre-election polling was mixed on this as of registration.

## 10. Registration and reproducibility

1. The PI fills §9, then the file is frozen.
2. SHA-256 of the frozen file is computed and recorded in at least **two independent places** outside the PI's machine: the public GitHub release (v1.0) **and** an Internet Archive snapshot of the released file. OSF Registries is optional.
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

*A result that falsifies a hypothesis is reported with the same prominence as one that supports it.*
