# Health1 Super Speciality Hospitals — health1hospital.com

Production website. Static site, zero build step — Vercel serves this repo as-is.

**Structure:** 90 pages as clean URLs (`/service/…/`, `/doctors/…/`, `/our-hospitals/…/`, `/blog/…/`), each an `index.html` in its folder. `sitemap.xml`, `robots.txt` (AI-crawler allowlist for AEO), `llms.txt` at root. `vercel.json` sets trailing slashes + security headers.

**Deploy:** Vercel → Add New → Project → import this repo → Deploy (framework: Other, no build command). Then Settings → Domains → `health1hospital.com` + `www`.

**Provenance:** generated from `robolapcon/public/health1-preview` @ `3620b4f` with domain migrated health1.co.in → health1hospital.com, flat files restructured to clean URLs, all internal links (incl. JS doctor grid) rewritten. Build toolkit archived in the July 13 2026 Claude session.
