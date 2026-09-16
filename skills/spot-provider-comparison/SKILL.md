---
name: spot-provider-comparison
description: Compare two commercial-insurance providers using Spot's published, source-qualified research. Use for provider differences and fit questions; not for live quotes, current eligibility, or unsourced rankings.
---

# Spot provider comparison

Use Spot's public MCP as a bounded research source and preserve the scope of its evidence.

1. Ask which two providers the user wants to compare and what requirements matter to the decision when those details are not already clear.
2. Call `compare_providers` first with the two provider names.
3. If no direct comparison exists, call `search_knowledge` separately for each provider. Identify the canonical published profile paths from the results, then call `get_page` for both profiles.
4. Report sourced similarities and differences relevant to the user's stated requirements. Include the canonical Spot links and the published update or verification dates.
5. Keep company-reported claims attributed. Identify information that Spot marks as not found, not publicly disclosed, stale, conflicting, or otherwise uncertain.
6. End with the unanswered questions that the user should verify with the provider, broker, proposed insurer, quote, or policy documents.

Never turn missing information into a negative fact. Do not imply that Spot's research is live, exhaustive, or a substitute for current quotes and policy wording. Do not recommend a provider unless the recommendation is explicitly tied to user-supplied requirements and the supporting evidence; when the evidence is insufficient, say so.

The public MCP is read-only. It cannot obtain quotes, confirm account-specific eligibility, buy or bind coverage, access customer records, issue certificates, or change policies.
