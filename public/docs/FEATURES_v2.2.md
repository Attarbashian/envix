# Envix v2.2 — Discoverability & Finder

## Homepage discovery
- Prominent Quick Tool Finder directly below the hero.
- Live text search across tool names, descriptions, aliases and tags.
- Filters for specialist collection, environmental domain and tool type.
- Match count, clear-filter action and direct navigation to all matching tools.

## Language consistency
- Explicit `fa-IR` / `en-US` formatting for user-facing numbers and dates.
- English mode no longer depends on the browser locale for digits/date output.
- Language-switch defaults in reports/comparison are translated only while still untouched defaults.

## Public support while source is private
- Homepage support actions use working public routes, email, share and creator-site links.
- Tool suggestions no longer point to private GitHub Issues.
- Header/footer GitHub links target the creator profile.
- Production source maps are disabled.

## Search discovery
- Dynamic route-level title/description/canonical metadata.
- WebSite and WebApplication JSON-LD.
- Generated sitemap covering public tool and collection routes.
- robots.txt explicitly permits OAI-SearchBot.
- `llms.txt` provides a concise supplementary project summary.

## Notes
- Search ranking and inclusion in AI answers cannot be guaranteed.
- Envix avoids keyword stuffing; tool-specific scientific content, references and internal navigation are the primary discovery strategy.
- Separate language-specific URLs with hreflang remain a future SEO phase if stronger bilingual indexing is needed.
