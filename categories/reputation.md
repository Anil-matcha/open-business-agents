# Reputation

| Umbrella repo | Covers | Status |
|---|---|---|
| [`open-ai-reputation-agent`](https://github.com/SamurAIGPT/open-ai-reputation-agent) | Brand monitoring, PR, review mining, sentiment tracking | Blueprint |

Blueprint: the review-mining sub-agent is wired to `ai-seo-agent`'s live Google Business Profile review endpoint (confirmed reachable 2026-09-09), though it's scoped to that one review source — Amazon and app-store reviews are still not wired up. News monitoring is now also Blueprint, wired to Muapi's `news-search` capability (keyword and company-domain news search) — coded but not yet live in production (pending a DB sync), and with no date-range/publication filter once it is. Social sentiment and PR & communications remain Coming Soon: sentiment analysis has no Muapi-provided capability at all (would need to be computed by the host from raw text), and PR & communications depends on all three of news search, review search, and sentiment analysis, only the first two of which are even partially available.
