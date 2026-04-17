---
title: "Voluntary Disclosure and ESG — What the Evidence Says So Far"
date: 2026-04-17
categories: [Accounting, Reading Notes]
tags: [Voluntary Disclosure, ESG, Information Disclosure, Corporate Governance, Empirical Accounting, Capital Markets, Reading Notes]
author: ruoxikong
description: A research note on voluntary corporate disclosure and ESG, grounded in the peer-reviewed empirical literature — motivating the open questions I care about from three years of continuous-supervision practice.
toc: true
---

## Why I'm Reading This Literature

Three years of continuous-supervision and disclosure-review work have sharpened, rather than satisfied, my curiosity about a fairly narrow question: **when firms disclose more than they have to — especially about ESG — what actually changes?**

In practice, I sit with issuers who ask variants of the same question every quarter: *"Do we really need to say this?"* The answer I give is usually shaped by compliance calendars and regulator expectations. The answer I wish I could give is shaped by evidence. This note is my attempt to organize what that evidence looks like so far, and to articulate the open questions that I'd want to carry into a PhD.

I restrict myself here to peer-reviewed empirical accounting and finance papers. Theoretical and normative work on ESG is huge; my cut is on what capital-market and archival studies have actually documented.

---

## A Minimal Theoretical Anchor

Before the empirics, two ideas keep recurring:

1. **Disclosure reduces information asymmetry.** Verrecchia's (2001, *JAE*) survey and Beyer, Cohen, Lys, and Walther's (2010, *JAE*) review formalize the intuition: if disclosure is credible and relevant to pricing, it should compress bid-ask spreads, lower estimation risk, and reduce the cost of capital.
2. **Disclosure is costly.** Verrecchia (1983) introduces the idea of **proprietary costs** — competitive, litigation, or political costs that push firms to withhold information. This is why voluntary disclosure equilibria are partial: firms disclose when the capital-markets benefit exceeds the proprietary cost.

ESG disclosure is an unusually clean testing ground for these models, because for most of the last two decades it has been *partially mandatory, partially voluntary, and very heterogeneous across jurisdictions.* That heterogeneity is exactly what empiricists need.

---

## The Empirical Landscape

### 1. Voluntary CSR/ESG reporting and the cost of equity

The canonical reference is **Dhaliwal, Li, Tsang, and Yang (2011, *The Accounting Review*)**, *"Voluntary Nonfinancial Disclosure and the Cost of Equity Capital: The Initiation of Corporate Social Responsibility Reporting."* They find that firms initiating stand-alone CSR reports experience a **subsequent reduction in the implied cost of equity capital**, and that the reduction is concentrated in firms with high CSR performance. The effect is consistent with the information-asymmetry story: CSR disclosure reduces estimation risk for investors who care about nonfinancial performance.

A natural follow-up, **Dhaliwal, Radhakrishnan, Tsang, and Yang (2012, *TAR*)**, extends the evidence internationally and finds that CSR disclosure is associated with **higher analyst forecast accuracy**, especially in countries where stakeholder orientation is stronger.

These two papers jointly ground the claim that voluntary nonfinancial disclosure has measurable capital-markets consequences — but *they do not yet tell us which parts of that disclosure are doing the work.*

### 2. Materiality matters more than volume

**Khan, Serafeim, and Yoon (2016, *TAR*)**, *"Corporate Sustainability: First Evidence on Materiality,"* is the paper I find most practically useful. Using the SASB materiality map, they separate **material** ESG issues from **immaterial** ones for each industry. Firms that score high on *material* issues outperform on future accounting and stock-market performance; firms that score high on *immaterial* issues do not. Volume of ESG disclosure is not what predicts value — *the match between disclosure and industry-specific materiality is.*

From a practitioner's perspective this is exactly the right finding: issuers who pad sustainability reports with generic commitments are not doing what the evidence rewards.

### 3. Mandatory vs. voluntary regimes

**Grewal, Riedl, and Serafeim (2019, *Management Science*)**, *"Market Reaction to Mandatory Nonfinancial Disclosure,"* exploit the 2014 EU Directive on nonfinancial reporting as a shock. They find, on average, **negative market reactions**, *but* the reaction is less negative (or positive) for firms with *ex ante* weaker ESG disclosure and stronger ESG performance — i.e., firms for whom mandatory disclosure plausibly compressed an information gap.

**Christensen, Hail, and Leuz (2021, *Review of Accounting Studies*)**, *"Mandatory CSR and Sustainability Reporting: Economic Analysis and Literature Review,"* is the most comprehensive synthesis I've read. Their core message for anyone considering research in this space: (i) mandates change the *quantity* of disclosure but the evidence on *comparability, reliability, and real-effects* is mixed; (ii) most of the capital-markets benefits in existing studies come from firms where disclosure was otherwise absent; (iii) we still know relatively little about **real effects** — whether mandatory ESG disclosure actually changes corporate behavior, as opposed to reporting behavior.

### 4. Voluntary disclosure and enforcement

A strand I'm increasingly interested in: **Leuz and Wysocki (2016, *JAR*)**, *"The Economics of Disclosure and Financial Reporting Regulation,"* argues that the effectiveness of disclosure regulation depends heavily on enforcement institutions. This matters enormously for emerging markets, including China, where disclosure mandates have expanded rapidly but enforcement capacity is uneven.

---

## What Practice Suggests the Literature Under-explores

Reviewing prospectuses, inquiry-letter responses, and continuous-supervision filings at close range leaves me with three concrete conjectures that I don't see fully resolved in the papers above.

**(a) Voluntary disclosure in response to regulatory signaling.**
In mainland A-share practice, a large share of "voluntary" ESG disclosure is in fact reactive to *soft* regulatory signals — exchange guidance, industry-association templates, inquiry-letter language. This sits in an awkward place between mandatory and voluntary that most empirical papers treat as a clean binary. A research question I'd want to pursue: **does the capital-markets benefit of voluntary ESG disclosure differ when the disclosure is regulator-nudged versus firm-initiated?** The Dhaliwal et al. (2011) result may weaken, disappear, or reverse when disclosure is driven by supervisory pressure rather than by a credible firm choice.

**(b) Inquiry-letter responses as disclosure events.**
Exchange inquiry-letter responses are a structured, public, and heavily regulated form of disclosure, yet most of the literature on disclosure informativeness focuses on earnings announcements, 8-K/临时公告, or MD&A. **Heese, Khan, and Ramanna (2017, *JAE*)** and **Brochet, Miller, Naranjo, Yu (2019, *JAR*)** have started to look at regulator–firm disclosure interactions, but the inquiry-letter setting is distinctive: the topics are chosen by the regulator, the answer is on the record, and the market has time to price the exchange. I think this setting can identify disclosure effects more cleanly than the typical voluntary-disclosure design.

**(c) Materiality is learned, not given.**
Khan, Serafeim, and Yoon (2016) uses the SASB map as an *exogenous* materiality classification. In practice, issuers, auditors, and regulators negotiate materiality iteratively — what counts as material for a 2024 new-energy-vehicle IPO is not what counted in 2021. I'd want to study **how disclosure choices co-evolve with regulator learning and industry precedent**, which is closer in spirit to Dye and Sridhar's signaling/competition literature but empirically closer to archival text work (e.g., Hoberg and Phillips 2016 on text-based industry classification).

---

## What I'd Want to Test

If I had to narrow to one dissertation-size question today, it would be:

> **Do firms whose ESG disclosures are driven by regulator inquiry (rather than firm initiative) earn the same capital-markets benefits documented in the voluntary-disclosure literature?**

A clean version of this design would combine (i) hand-collected or API-scraped inquiry-letter mentions of ESG topics, (ii) firm-initiated ESG disclosure measures from existing data (e.g., MSCI, Bloomberg, Wind ESG), and (iii) standard cost-of-equity and forecast-dispersion outcomes. The identification relies on the fact that the inquiry-letter treatment is partly assigned by the exchange on grounds plausibly orthogonal to firm value.

That is the kind of project I would like to develop further under doctoral supervision.

---

## Caveats

This is a reading note, not a literature review. I've deliberately left out large bodies of work — the CSR–firm value debate (Margolis, Elfenbein, Walsh 2009 meta-analysis; Krüger 2015, *JFE*), ESG and green-washing (Raghunandan and Rajgopal 2022), ESG and credit markets (Seltzer, Starks, Zhu 2022), and the accounting-quality consequences of mandatory sustainability assurance. If you want pushback on anything above, or think I'm missing a paper that would change my mind — I'd welcome the message.

---

## References

- Beyer, A., Cohen, D. A., Lys, T. Z., & Walther, B. R. (2010). The financial reporting environment: Review of the recent literature. *Journal of Accounting and Economics*, 50(2–3), 296–343.
- Brochet, F., Miller, G. S., Naranjo, P., & Yu, G. (2019). Managers' cultural background and disclosure attributes. *Journal of Accounting Research*, 57(5), 1179–1225.
- Christensen, H. B., Hail, L., & Leuz, C. (2021). Mandatory CSR and sustainability reporting: Economic analysis and literature review. *Review of Accounting Studies*, 26(3), 1176–1248.
- Dhaliwal, D. S., Li, O. Z., Tsang, A., & Yang, Y. G. (2011). Voluntary nonfinancial disclosure and the cost of equity capital: The initiation of corporate social responsibility reporting. *The Accounting Review*, 86(1), 59–100.
- Dhaliwal, D. S., Radhakrishnan, S., Tsang, A., & Yang, Y. G. (2012). Nonfinancial disclosure and analyst forecast accuracy: International evidence on corporate social responsibility disclosure. *The Accounting Review*, 87(3), 723–759.
- Grewal, J., Riedl, E. J., & Serafeim, G. (2019). Market reaction to mandatory nonfinancial disclosure. *Management Science*, 65(7), 3061–3084.
- Heese, J., Khan, M., & Ramanna, K. (2017). Is the SEC captured? Evidence from comment-letter reviews. *Journal of Accounting and Economics*, 64(1), 98–122.
- Khan, M., Serafeim, G., & Yoon, A. (2016). Corporate sustainability: First evidence on materiality. *The Accounting Review*, 91(6), 1697–1724.
- Leuz, C., & Wysocki, P. D. (2016). The economics of disclosure and financial reporting regulation: Evidence and suggestions for future research. *Journal of Accounting Research*, 54(2), 525–622.
- Verrecchia, R. E. (1983). Discretionary disclosure. *Journal of Accounting and Economics*, 5, 179–194.
- Verrecchia, R. E. (2001). Essays on disclosure. *Journal of Accounting and Economics*, 32(1–3), 97–180.
