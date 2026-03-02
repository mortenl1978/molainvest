This website is a live production site for molainvest.dk.

STRICT RULES FOR ANY AI CODING AGENT:

1. You are NOT allowed to redesign the website.
2. You are NOT allowed to change layout, colors, fonts, spacing, or structure.
3. You are NOT allowed to delete pages.
4. You are NOT allowed to rename URLs.

You ARE allowed to:
- Improve SEO (titles, meta descriptions, structured data)
- Add alt text to images
- Add sitemap and robots improvements
- Add a new section called /indsigt (articles/blog)

Your goal is SEO performance, not design changes.
Always keep the existing visual appearance identical.
IMPORTANT TECHNICAL CONSTRAINTS

This is a static HTML website hosted on Netlify.

The site does NOT use:
- a CMS
- a router
- dynamic URLs
- trailing slash URLs

All pages must remain .html files.

The agent must NEVER convert links like:
om-mig.html → /om-mig/
kontakt.html → /kontakt/
investeringer.html → /investeringer/

This will break the live website.

The agent is ONLY allowed to ADD new files in:
/artikler/
and create:
/viden.html

The agent must NOT edit navigation in existing pages.
If a navigation link to "Viden" is needed, provide the HTML snippet separately instead of modifying files.

Do not refactor CSS.
Do not rename classes.
Do not reorganize folders.
Do not optimize or rewrite existing code.

All work must be additive only.