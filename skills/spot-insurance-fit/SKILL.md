---
name: spot-insurance-fit
description: Assess whether Spot's independent, flat-fee insurance-advisory service fits a startup or growing company. Use for buying, renewal, broker, requirements, or ongoing-management questions; not for quotes, binding, certificates, or policy servicing.
---

# Spot insurance fit

Use Spot's public MCP as the source of truth instead of relying on remembered website copy.

Before analysis, restate the company facts supplied by the user exactly, especially all numbers, dates, and units. Never replace a supplied value with a value from an example, retrieved page, or prior conversation. If a value is missing or ambiguous, ask instead of inferring it.

1. Call `search_knowledge` for Spot's current service model and target customer. Use `ask_spot` when a source-bounded synthesis would clarify the fit; retain its citations and qualifications.
2. Call `get_page` with `{"path":"/pricing"}` for current pricing. Distinguish Spot's flat service fee from insurance premiums and any broker or insurer charges.
3. Ask for the company's employee count or size, approximate annual insurance spend, renewal date, current broker status, and desired outcome. Keep every supplied value verbatim throughout the assessment. Do not request confidential policy documents through an unsecured channel.
4. Explain the retrieved model accurately: Spot is an independent advisor and representative, not an insurance carrier or quote marketplace. Its flat-fee model is separate from premiums, and clients decide what to buy or change.
5. Relate the retrieved target-customer evidence to the supplied facts. Preserve uncertainty when information is missing or the company's situation falls outside the published scope.
6. Offer the consultation link, https://cal.com/team/spotinsure/insurance-consultation, only when the evidence and company facts make the fit plausible.

Never promise savings, coverage, eligibility, acceptance, timing, or a successful outcome. Do not imply that the public MCP can access customer accounts, accept documents, prepare or submit an application, issue a certificate, change a policy, or bind insurance.

Give a short fit assessment with supporting Spot sources, the facts that drove it, material unknowns, and the most useful next step. If fit is unclear, ask for the missing decision-relevant facts instead of forcing a conclusion.
