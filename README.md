# Insurance Research Expert by Spot

Research commercial insurance with Spot's read-only public MCP and two responsible workflows for provider comparison and service-fit assessment.

## Included capabilities

- Search Spot's published commercial-insurance knowledge with citations and qualifications.
- Retrieve canonical provider profiles, comparisons, public pages, and current pricing.
- Compare two providers without treating missing information as a negative fact.
- Assess whether Spot's independent, flat-fee advisory model may fit a company without promising savings, coverage, eligibility, or acceptance.

## Included skills

- `spot-insurance-fit` gathers the decision-relevant company facts, retrieves Spot's current service model and pricing, preserves uncertainty, and offers a consultation only when fit is plausible.
- `spot-provider-comparison` follows a source-first comparison sequence, reports verification dates and undisclosed information, and ends with questions to verify with the provider or broker.

## MCP server

The plugin connects to `https://spot.insure/mcp`. It is public, read-only, and does not require authentication. It cannot access customer accounts, accept documents, obtain quotes, bind coverage, issue certificates, or change policies.

## Example requests

- “Compare Vouch and Embroker for a 75-person SaaS company that needs cyber and technology E&O.”
- “Would Spot's service model fit our 120-person company if we already have a broker and renew in four months?”
- “What does Spot publish about Coalition, and what should I verify before choosing a provider?”

Learn more at [spot.insure](https://spot.insure).
