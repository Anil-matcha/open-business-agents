# Sales & E-commerce

| Umbrella repo | Covers | Status |
|---|---|---|
| [`open-ai-sales-agent`](https://github.com/SamurAIGPT/open-ai-sales-agent) | Lead generation, outreach, enrichment, email verification | Blueprint |
| [`open-ai-ecommerce-agent`](https://github.com/SamurAIGPT/open-ai-ecommerce-agent) | Amazon/marketplace intelligence, CRO, local leads, cross-border e-commerce | Blueprint |

`open-ai-sales-agent`'s four sub-agents moved to Blueprint: their workflow is fully defined against Muapi's `company.enrich`/`people.search`/`email.verify` capabilities, which are now coded server-side (production deploy pending). `open-ai-ecommerce-agent` is Blueprint for a different reason: its local-business-leads sub-agent is wired to `ai-seo-agent`'s live local-SEO endpoints (business listings, profile, reviews). That repo's other three sub-agents (Amazon review mining, Amazon market intelligence, cross-border e-commerce) are still Coming Soon, pending marketplace-data API coverage.
