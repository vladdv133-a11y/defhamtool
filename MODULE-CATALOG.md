# HamTool Pro — 5,000 Search Modules

The application builds a catalogue of exactly **5,000 uniquely named source-plus-recipe modules** from **190 curated public source entries** and **27 search recipes** (5,130 possible combinations). All 190 source entries are represented; 26 recipes are applied to all 190 sources (4,940 modules), and the final recipe is applied to 60 sources (60 modules).

Each module generates a Google `site:` search link with one transparent query recipe. Recipes include general query, exact phrase, page title, URL keywords, PDF/DOCX/XLSX/CSV/PPTX, page text, public contact/about pages, documentation, policies, press/news, careers, GitHub mentions, recent/historical mentions, exclusions, definitions, JSON/XML/TXT/Markdown. Query operators are search-engine features and may behave differently over time.

**Important:** these are 5,000 search recipes, not 5,000 independent websites or live API connectors. The curated seed list is maintained in `Services/SourceCatalogService.cs`; direct live APIs are implemented separately in `Services/PublicSearchService.cs`. Search results are not guaranteed and should be verified at the original source. Use public information responsibly and respect source terms, privacy, and applicable law.

## Catalogue counts
- Generated modules: 5,000
- Curated source entries: 190
- Query recipes: 27
- Possible combinations: 5,130

The in-app category filter uses the source/category metadata. The app does not bypass access controls, CAPTCHA, logins, or rate limits.
