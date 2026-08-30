# Research Project Proposal
### Ad hoc semantic reconciliation between divergent network models, using machine cognition

This repository collects a two-part proposal — a **theory** paper and a **research-programme** paper — together with their companion slide decks and four interactive demonstrations. It is shared for review and comment.

The work starts from a simple observation: the systems now joining the network-management plane increasingly reason for themselves, and they need information structured not merely as form but as **meaning**. It develops that meaning as a *semantic model* — an ontology, including its lexicon, together with pragmatics — argues that two systems holding divergent models can reconcile them *ad hoc* rather than by adopting a universal model in advance, and asks a question that runs through the whole proposal: where the cognition sits relative to the systems being reconciled (the **cognition spectrum**), and what, short of full cognition on both sides, a thin **shared reference** can recover.

An earlier set of materials on this theme is here: **[meaning-across-representations](https://github.com/ChrisFJanz/meaning-across-representations)**.

## Contents

**Papers**

- **[Part I — Structuring Meaning for Machine Cognition](Part_I_Theory.pdf)** — the theory and the terms: the semantic model as completeness for comprehension, the *lift* that produces one, reconciliation at the semantic level, the cognition spectrum, shared references, and four worked demonstrations.
- **[Part II — A Research Programme on Shared References](Part_II_Programme.pdf)** — questions and hypotheses, a two-track method, metrics (including how cognitive effort is measured with language models in the loop), the benchmark and its datasets, a phased plan, and what operating networks could contribute.

**Slide decks** (companions to the papers)

- **[Part I — Theory deck](Part_I_Theory_Deck.pdf)**
- **[Part II — Programme deck](Part_II_Programme_Deck.pdf)**

**Interactive demonstrations** (self-contained HTML — download and open in a browser)

- **[configuration.html](configuration.html)** — two peer models of one transport network (TAPI ↔ IETF TEAS); a false cognate pre-empted by a thin reference, verified by round-trip on invariants.
- **[intent.html](intent.html)** — a declarative, quantitative intent refined to a realisation (TM Forum intent ↔ IETF L1CSM); verified by satisfaction rather than equality.
- **[cross_domain.html](cross_domain.html)** — two bespoke systems in different domains with no standard in common; a minimal shared reference built between them.
- **[anomaly.html](anomaly.html)** — reconciling anomaly semantics across an incumbent fault model and the newer IETF NMOP model, where meaning is carried largely by pragmatics.

> Each demonstration is a single, self-contained page. GitHub displays these files as source; to run one, download it and open it in a browser (or view it through a raw-HTML renderer such as htmlpreview).

## Suggested order

Read **Part I** first for the framing and terms; try one or two **demonstrations** to see the method in action; then read **Part II** for the proposed programme. The decks track the papers section by section if you would rather skim.

## Key references

Standards and models the demonstrations build on:

- **ONF** — [TR-547, Transport API (TAPI) Reference Implementation Agreement](https://opennetworking.org/wp-content/uploads/2022/12/TR-547-TAPI-Reference-Implementation-Agreement_v2.0.pdf)
- **IETF RFCs** — [RFC 8795, YANG Data Model for TE Topologies](https://www.rfc-editor.org/rfc/rfc8795) · [RFC 8342, Network Management Datastore Architecture (NMDA)](https://www.rfc-editor.org/rfc/rfc8342) · [RFC 8632, A YANG Data Model for Alarm Management](https://www.rfc-editor.org/rfc/rfc8632) · [RFC 5424, The Syslog Protocol](https://www.rfc-editor.org/rfc/rfc5424) · [RFC 9232, Network Telemetry Framework](https://www.rfc-editor.org/rfc/rfc9232) · [RFC 9940, Some Key Terms for Network Fault and Problem Management](https://www.rfc-editor.org/rfc/rfc9940)
- **IETF drafts** — [L1 Connectivity Service Model (L1CSM)](https://datatracker.ietf.org/doc/draft-ietf-ccamp-l1csm-yang/) · [TE and Service Mapping](https://datatracker.ietf.org/doc/draft-ietf-teas-te-service-mapping-yang/) · [Network Anomaly Semantics](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-semantics/) · [Network Incident YANG](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-incident-yang/) · [Network Anomaly Architecture](https://datatracker.ietf.org/doc/draft-ietf-nmop-network-anomaly-architecture/)
- **TM Forum** — [TMF921, Intent Management API](https://www.tmforum.org/oda/open-apis/directory/intent-management-api-TMF921/v5.0.0) · [Intent-based Automation (TR290, IG1253)](https://www.tmforum.org/opendigitalframework/intent-based-automation/)

Related and parallel work in the community, on knowledge graphs and AI-assisted modelling for network operations:

- **Network ontology knowledge graphs** (Brad Peters) — [Network-Ontology-Knowledge-Graphs](https://github.com/bradspau/Network-Ontology-Knowledge-Graphs)
- **NAIM** (Chong Feng) — [A Canonical Data Format for AI-Assisted YANG Modeling](https://datatracker.ietf.org/doc/draft-feng-netmod-naim/) · [NAIM operations](https://datatracker.ietf.org/doc/draft-feng-netconf-naim-op/) · [NAIM with the Model Context Protocol](https://datatracker.ietf.org/doc/draft-feng-nmop-naim-mcp/)
- **Knowledge graphs for network operations** — [Knowledge Graph Framework for Network Operations](https://datatracker.ietf.org/doc/draft-mackey-nmop-kg-for-netops/)

Foundational:

- C. W. Morris, *Foundations of the Theory of Signs* (University of Chicago Press, 1938) — the syntax / semantics / pragmatics distinction.
- R. L. Ackoff, "From Data to Wisdom," *Journal of Applied Systems Analysis* 16 (1989) — the data → information → knowledge → wisdom progression.

---

*Christopher Janz*
