# Reputation

| Umbrella repo | Covers | Status |
|---|---|---|
| [`open-ai-reputation-agent`](https://github.com/SamurAIGPT/open-ai-reputation-agent) | Brand monitoring, PR, review mining, sentiment tracking | Blueprint |

Blueprint: the review-mining sub-agent is wired to `ai-seo-agent`'s live Google Business Profile review endpoint (confirmed reachable 2026-09-09), though it's scoped to that one review source — Amazon and app-store reviews are still not wired up. The repo's other three sub-agents (news monitoring, social sentiment, PR & communications) are still Coming Soon, pending news/social-data API coverage on Muapi.
