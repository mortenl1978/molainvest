This website is a live production site for molainvest.dk.

STRICT RULES FOR ANY AI CODING AGENT

1. You are NOT allowed to redesign the website.
2. You are NOT allowed to change layout, colors, fonts, spacing, or structure.
3. You are NOT allowed to delete pages.
4. You are NOT allowed to rename URLs.
5. You are NOT allowed to change navigation in existing pages unless explicitly instructed.
6. You are NOT allowed to refactor CSS, rename classes, reorganize folders, or rewrite working code.
7. All work must be additive only unless a specific file change is explicitly requested.

YOU ARE ALLOWED TO
- Improve SEO (titles, meta descriptions, structured data)
- Add alt text to images
- Improve sitemap.xml and robots.txt
- Add new static HTML pages when explicitly requested
- Add new investment pages when explicitly requested
- Add new article pages in /artikler/ when explicitly requested

IMPORTANT TECHNICAL CONSTRAINTS

This is a static HTML website hosted on Netlify.

The site does NOT use:
- a CMS
- a router
- dynamic URLs
- trailing slash URLs

All pages must remain .html files.

The agent must NEVER convert links like:
om-mig.html -> /om-mig/
kontakt.html -> /kontakt/
investeringer.html -> /investeringer/

This will break the live website.

Do not:
- refactor CSS
- rename classes
- reorganize folders
- optimize or rewrite existing code
- introduce frameworks, templating engines, build tools, or JavaScript routing

INVESTMENT PAGE RULES

When creating a new investment page, the agent must use an existing investment page as the direct template.

Default reference template:
https://molainvest.dk/investeringer/kjoe

Rules for new investment pages:
1. The new page must match the KJØ page as closely as possible in structure, layout, spacing, section order, wrappers, class usage and visual hierarchy.
2. Do NOT redesign anything.
3. Do NOT invent a new layout.
4. Do NOT simplify or modernize the structure.
5. Only replace the content so it fits the new investment.
6. Keep header, footer and the existing CTA section consistent with the current implementation.
7. Reuse the same image pattern and page composition as the existing investment pages.
8. If the KJØ page contains reusable classes, wrappers or content blocks, follow that exact implementation pattern.
9. New investment pages must be created in /investeringer/ as static .html files.
10. New investment pages must only be linked from investeringer.html when explicitly requested.

WORKING METHOD FOR NEW INVESTMENT PAGES

When asked to create a new investment page, always:
1. Inspect the existing KJØ investment page in the repo
2. Reuse its structure directly
3. Create the new page as a near-clone with only content changes
4. Preserve all existing design patterns
5. Avoid touching global files unless required for the requested link addition

ALLOWED ADDITIONS

The agent is allowed to add new files in:
- /artikler/
- /investeringer/

The agent may create:
- /viden.html
- new article pages
- new investment pages

If a navigation link to a new section is needed, provide the HTML snippet separately unless explicitly instructed to modify navigation files.