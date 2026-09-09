# Research & Data

| Umbrella repo | Covers | Status |
|---|---|---|
| [`open-ai-research-agent`](https://github.com/SamurAIGPT/open-ai-research-agent) | Web research, document ingestion, market/audience research | Coming Soon |
| [`open-ai-analytics-agent`](https://github.com/SamurAIGPT/open-ai-analytics-agent) | Turning enriched/scraped data into client-facing reports and dashboards | Coming Soon |
| [`open-ai-competitor-intelligence-agent`](https://github.com/SamurAIGPT/open-ai-competitor-intelligence-agent) | Cross-cutting competitive audits (SEO + ads + social + reviews) | Blueprint |

`open-ai-research-agent` and `open-ai-analytics-agent` are Coming Soon — pending broader API coverage on Muapi across the categories these agents pull from. `open-ai-competitor-intelligence-agent` moved Coming Soon → Blueprint (2026-09-09): its `ad-library-mining` sub-agent was already Blueprint, and `competitive-audit` is now Blueprint too — its SEO signal (`seo-domain-overview`/`seo-backlinks-history`) and social signal (`social.read_posts`) are live and tested, its reputation signal (`seo-business-reviews`) is live but Google-only. It runs a real, partial audit today rather than waiting on 100% channel coverage.
