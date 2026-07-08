# Marketing Calculators

Free, self-contained marketing calculators — one HTML file per tool, no framework, no backend. Hosted on GitHub Pages.

## Tools
- `billboard-cost-calculator/` — billboard cost by city, static vs digital, total cost + CPM
- `marketing-roi-calculator/` — ROI, ROAS, cost per lead, CAC (simple + funnel modes)
- `customer-acquisition-cost-calculator/` — CAC, LTV:CAC ratio, payback period

Each page: SEO head (title, meta, canonical, Open Graph) + inline calculator (vanilla JS) + guide/FAQ content + JSON-LD (WebApplication + FAQPage) + Mailchimp email capture.

## Adding a calculator
Copy an existing folder, rename the slug, swap the calculator inputs/JS and the guide content, then add the URL to `sitemap.xml`. Keep the shared `<style>` block for a consistent look.

Pricing/benchmarks compiled from 2026 industry sources (AdQuick, WordStream, LocaliQ, USPS/MailPro, Adams Outdoor, MNTN). Estimates for planning only.
