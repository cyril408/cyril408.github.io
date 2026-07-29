---
layout: post
title: "Wiring In the Fourth OSS Scheme: What Implementing Regulation 2026/1869 Actually Changes"
date: 2026-07-29
excerpt: "ViDA's new transfer of own goods scheme just got its OSS plumbing: what Implementing Regulation 2026/1869 changes, article by article."
---

On 28 July 2026, the Official Journal published Commission Implementing Regulation (EU) 2026/1869, amending Implementing Regulation (EU) 2020/194 &mdash; the text that defines the technical plumbing behind the EU's One-Stop-Shop (OSS) VAT schemes: what data gets collected, in what format, and how it moves between Member States.

Nothing in it changes VAT law. What it does is finish wiring in a scheme that VAT law already created but that, until now, had no operational infrastructure to run on.

## ViDA's transfer of own goods scheme: the gap this regulation closes

Council Directive (EU) 2025/516 &mdash; the "ViDA" directive, adopted 11 March 2025 &mdash; extended the existing OSS special schemes and added a genuinely new one: a special scheme for **transfers of own goods**, inserted as a new Section 5 in Title XII, Chapter 6 of the VAT Directive (2006/112/EC), alongside the three that already existed (non-Union scheme, Union scheme, import scheme). It is part of what ViDA's own architecture calls the **Single VAT Registration** pillar &mdash; the strand of the reform aimed at letting businesses use one registration instead of several across the Union.

In plain terms: a business that moves its own inventory from one Member State to another &mdash; without a sale, for example stock repositioning ahead of demand &mdash; currently has to register for VAT locally in the destination Member State to account for that movement. The new scheme is meant to let it report that centrally instead, the same way OSS already lets distance sellers avoid registering in every Member State they sell into.

ViDA gave that scheme its legal basis in March 2025. It did not, however, tell tax administrations what data fields to exchange, what a nil return should look like for that scheme, or which network message carries it. That is exactly what Implementing Regulation (EU) 2020/194 does for the other three schemes &mdash; and what 2026/1869 now extends to the fourth. Without this amendment, the new scheme would have had a legal shell but no functioning back-end.

## Article by article: before and after

The comparison below uses the current official English text of Implementing Regulation (EU) 2020/194 (consolidated version in force, CELEX 32020R0194) as "before," and the text of Implementing Regulation (EU) 2026/1869 (CELEX 32026R1869) as "after." Both are sourced directly from EUR-Lex.

| Provision | Before (Reg. 2020/194, in force) | After (Reg. 2026/1869) |
|---|---|---|
| **Art. 1(2)** — definition of "Union scheme" | Covers intra-Community distance sales, supplies of goods within a Member State made *by electronic interfaces facilitating those supplies under Article 14a(2)*, and cross-border services. | Broadened: covers intra-Community distance sales, *"certain supplies of goods within a Member State made by a taxable person"* (no longer limited to electronic-interface-facilitated supplies), and services. This is a real widening of scope, not just a drafting tidy-up. |
| **Art. 1(4)** — definition of "special schemes" | *"the non-Union scheme, the Union scheme and the import scheme"* (three schemes; no separate "transfer" definition existed). | Point (4) is repurposed to define the new **"transfer of own goods scheme"** (Title XII, Ch. 6, Section 5). A new **point (5)** is added, redefining "special schemes" as *"the non-Union scheme, the Union scheme, the import scheme and the transfer of own goods scheme"* &mdash; four schemes. |
| **Art. 2(a)** — electronic interface functionalities | Must allow saving data pursuant to Art. 361/369p (identification) and Art. 365, 369g or 369t (VAT return). | Same, plus **Article 369xg** added to the VAT-return cross-references — the new scheme's return provision. |
| **Art. 3(1)** — identification data to transmit | Lists categories (a)-(e): non-Union, Union, import, intermediary, identification number. | Adds new **point (e): "information to identify the taxable person using the transfer of own goods scheme."** |
| **Art. 3(2)** — column mapping for identification message | Column B = non-Union; C = Union; D = import (taxable person); E = import (intermediary). | Columns shift down one letter to make room for a fifth: **C** = non-Union; **D** = Union; **E** = import (taxable person); **F** = import (intermediary); **G** (new) = transfer of own goods scheme. |
| **Art. 3(3)** — exclusion/change-of-status notifications | Cross-refers to Arts. 363, 369e, 369r(1)/(3); covers change of MS of identification within Union or import scheme. | Adds cross-reference to new **Art. 369xe**; change-of-identification notice now also covers the **transfer of own goods scheme**. |
| **Art. 3(5)** — automatic exchange of ID data | Limited to exchange of the VAT identification numbers themselves (Art. 369q(1)/(3)). | Substantially expanded: now also covers name, postal address, electronic address, VAT/national tax number, deemed-supplier status under Art. 14a(1), and websites (Art. 369p(1)/(3)) &mdash; a materially richer data set shared between Member States. |
| **Art. 3(6)** — pre-filling of data | *Did not exist.* | **New paragraph**: the Member State of identification must pre-fill known data for taxable persons registering, who remain responsible for its correctness — a data-quality/administrative-burden provision with no prior equivalent. |
| **Art. 4** — VAT return submission | Covers three schemes; nil-return boxes: 1,2,11,24 (non-Union) / 1,2,21,24 (Union) / 1,1a,2,11,24 (import). | **Entire article replaced.** Now covers four schemes with renumbered boxes: 1,2,2a,2b,9,27 (non-Union) / 1,2,2a,2b,23,27 (Union) / 1,1a,2,2a,2b,9,27 (import) / **1,2,2a,2b,4,28 (new: transfer of own goods)**. New paragraphs specify that transfers need only be reported for Member States actually receiving transferred goods in that period. |
| **Art. 5** — transmission of VAT return data | Sent to each Member State of consumption; for the Union scheme, also to dispatch/transport and establishment Member States. | Extends "Member State of consumption" to **"or Member State where goods are transferred to."** New **point (c)**: for the transfer scheme, data goes to each Member State goods are transferred *from*. |
| **Entry into force / application** | N/A | Regulation enters into force 20 days after publication (effective **17 August 2026**). **Article 2** (a minor Annex I wording fix) applies only **1 January 2027 to 30 June 2028**, as a transitional step. **Articles 1 and 3** — the substantive changes above, plus the full Annex I-III replacement — apply from **1 July 2028**. |

## What changes in the Annexes, without reproducing all of it

The three technical Annexes to Regulation 2020/194 — which define, box by box, exactly what identification data and VAT return fields get exchanged — are replaced wholesale by 2026/1869, not just amended line by line. Rather than reprint three dense tables here, the headline points:

Annex I (identification details) gains a full **column G** for the transfer of own goods scheme, alongside restructured boxes covering VAT-group status, prior OSS registrations, electronic-interface status, and — notably — a cross-reference to **Article 284** (the small-enterprise exemption scheme), which did not previously appear anywhere in this regulation.

Annex II (exclusion/status-change codes) is rewritten to spell out reasons in full narrative text rather than numeric footnote codes, and explicitly extends every notification category to the transfer of own goods scheme.

Annex III (the VAT return itself) is restructured around six columns instead of four, drops the separate standard/reduced-rate split in favour of a single generic VAT-rate field, and adds an entirely new **Part 2(g)**: adjustment of deduction on goods that have been transferred, including a capital-goods adjustment period start date — a concept with no equivalent under the current three-scheme structure.

## Why this is worth tracking now, not in 2028

The substantive changes only bite from 1 July 2028, and the timeline could still move. But two things make this worth flagging today rather than waiting:

First, this confirms the "transfer of own goods" scheme is moving from legislative concept to operational reality on a fixed technical timetable, independent of any further political negotiation — the Standing Committee on Administrative Cooperation has already signed off. Second, businesses that currently hold multiple local VAT registrations purely to cover intra-EU stock movements now have a concrete date to plan against for consolidating that reporting through OSS instead.

The precise commercial scope of the new scheme — which stock movements qualify, and how it interacts with existing call-off stock simplifications — sits in Directive (EU) 2025/516 itself rather than in this implementing regulation, and is worth a separate, dedicated look before 2028 planning starts in earnest.

For non-EU sellers already tracking the wider convergence of tax, customs, product-safety, environmental, digital and consumer rules, this sits inside that same tax pillar: see [Seven Regimes, One Trajectory](/blog/2026/07/22/seven-regimes-one-trajectory/) for the broader map it fits into.

---

*Sources: Commission Implementing Regulation (EU) 2026/1869 of 27 July 2026 (OJ L, 2026/1869, 28.7.2026, CELEX 32026R1869); Commission Implementing Regulation (EU) 2020/194 of 12 February 2020, consolidated version (CELEX 32020R0194); Council Directive (EU) 2025/516 of 11 March 2025. All texts accessed via EUR-Lex.*

