# STARS (Safety Training and Response Strategies) — Website Audit Report
**Date:** March 7, 2026
**URL:** https://www.starstrain.com
**Platform:** Wix
**Prepared for:** Luke Kroeplin

---

## Executive Summary

The STARS website is essentially a 2017-era Wix brochure that has received minimal updates since launch. It's non-functional as a lead generation tool — no calls to action, no contact form, no service detail pages, no SEO, and no structured data. The site is virtually invisible to search engines and AI tools. For a B2B safety training company that serves railroads, pipelines, and government agencies, this site undermines credibility with every visit.

**Severity: This site is doing more harm than good.** A prospective railroad safety manager finding this site would question whether the company is still in business.

---

## Critical Issues (Blockers)

### 1. ZERO Meta Description on ANY Page
- **Impact:** Google generates its own snippets from page content, which is sparse. AI search tools have nothing to work with. The homepage title is the generic "Safety Training and Response Strategies" — no location, no differentiator.
- **Fix:** Add unique, keyword-rich meta descriptions for every page.

### 2. NO Structured Data Whatsoever
- **Impact:** No LocalBusiness schema, no Organization schema, no Service schema, no FAQ schema. Google has zero structured understanding of what this business is, where it is, or what it does. Zero rich snippet eligibility.
- **Fix:** Add comprehensive LocalBusiness + ProfessionalService + FAQ schema.

### 3. NO Open Graph Tags — Zero Social Sharing
- **Impact:** Sharing this site on LinkedIn (where B2B clients are) produces no preview image, no title, no description. For a B2B company, LinkedIn sharing is a primary referral channel.
- **Fix:** Add OG tags on all pages.

### 4. Homepage Has ONE Sentence of Content
- **Impact:** The entire homepage body text is: *"Safety Training and Response Strategies provides innovative training, exercise design and response plan creation for relevant, integrated response readiness."* That's 21 words. Google needs 300-1000+ words to understand and rank a page. AI search can't extract anything useful.
- **Fix:** Complete homepage rebuild with comprehensive service descriptions, credentials, and calls to action.

### 5. NO Contact Form Anywhere on the Site
- **Impact:** The only way to contact STARS is to find the email address in the footer (mstokes@starstrain.com) or call. There's no contact page, no form, no easy way to request a quote. This kills lead conversion.
- **Fix:** Add a prominent contact/quote request form.

### 6. Copyright Says "2017" — Nine Years Outdated
- **Impact:** Immediate credibility killer. Tells visitors (and Google) this site is abandoned.
- **Fix:** Auto-updating year.

---

## High Severity Issues

### 7. URL Structure is Broken — `/about2`, `/projects-1`
- **Impact:** The About page URL is `/about2` (suggesting the original was deleted/recreated). The Projects page is `/projects-1`. These look unprofessional and waste SEO equity.
- **Fix:** Clean URLs: `/about`, `/services`, `/projects`, `/contact`.

### 8. Page Titles Are Generic or Wrong
- **Impact:**
  - Homepage: "Safety Training and Response Strategies" (no location, no keywords)
  - About: "ABOUT | Starstrain" (wrong — "Starstrain" is the domain, not the business name)
  - Services: "Safety Training and Response Strategies" (same as homepage)
  - Projects: "PROJECTS | Starstrain"
- **Fix:** Unique, descriptive titles with location keywords.

### 9. Heading Hierarchy is Chaotic
- **Impact:** The About page has duplicate H1 content ("ABOUT OUR BUSINESS" appears twice in the raw HTML). Team member names are H5 tags (skipping H2, H3, H4). Services page has no H1.
- **Fix:** Clean H1→H2→H3 hierarchy on every page.

### 10. Team Bios Reference Outdated Information
- **Impact:** Jordan Soderman's bio says "over 10 years" of fire service and references the "934th Airlift Wing" — this is now the 934th ARW/CES. The bio also says "Chief of Training" which may or may not be current. Copyright is 2017.
- **Fix:** Update all bios to current. (Needs input from Matt Stokes.)

### 11. No Mobile Optimization
- **Impact:** While Wix provides basic responsive layout, the site's content structure doesn't work on mobile — the hero slideshow takes up the entire viewport, service images are cramped, and the team section is unreadable.
- **Fix:** Mobile-first responsive design in rebuild.

### 12. Images Have No Meaningful Alt Text
- **Impact:** Alt texts are filenames like "thumbnail_IMG_5044.jpg" and "BIO PIC.jpg". This is an accessibility violation and an SEO failure — these images show real training operations that should be indexed by Google Images.
- **Fix:** Descriptive alt text on all images.

---

## Medium Severity Issues

### 13. No Service Detail Pages
- **Impact:** Each service (OSHA, HSEEP, Contingency Planning, CPR/First Aid, Water Response) has only a paragraph of description. No detail pages, no pricing indicators, no "what to expect" content. Competitors with detailed service pages will outrank STARS.
- **Fix:** Expanded service descriptions on the single page (or individual service sections with anchor links).

### 14. Projects Section Has No Dates or Outcomes
- **Impact:** The six projects listed have no dates, no measurable outcomes, and no client testimonials. "The Red Wing Full-Scale Exercise involved over 150 participants" is good but needs context — when? for whom? what was the result?
- **Fix:** Add dates and outcomes where possible.

### 15. No Credentialing/Certification Badges
- **Impact:** For a safety training company, certifications matter. The AHA CPR/First Aid logo is shown but there are no OSHA, DOT, HSEEP, or other certification badges. These build instant credibility.
- **Fix:** Add certification/credential section with proper logos.

### 16. Wix Chat Widget is Misplaced
- **Impact:** A "Let's Chat!" Wix widget appears in the corner but has no context — it's unclear if it connects to a person or a bot. For a B2B company, this feels unprofessional.
- **Fix:** Remove Wix chat widget. Replace with a proper contact CTA.

### 17. Videos Section on Projects Page Has No Content
- **Impact:** There's a "Videos" heading at the bottom of the Projects page but the embedded videos aren't crawlable and may not load. No descriptions or context.
- **Fix:** If videos exist, embed with proper titles and descriptions. If not, remove the section.

---

## Low Severity Issues

### 18. No Favicon
- **Impact:** Browser tab shows generic Wix icon.
- **Fix:** Add STARS logo as favicon.

### 19. Footer Has No Social Links
- **Impact:** No LinkedIn, no Facebook, no social proof. For a B2B company, LinkedIn presence is important.
- **Fix:** Add social links if they exist.

### 20. "More" Nav Item Has No Visible Purpose
- **Impact:** The navigation has a "More" dropdown that appears empty or redundant. Confusing UX.
- **Fix:** Remove unused nav items.

---

## AI Search Readiness Assessment

| Signal | Status | Impact |
|--------|--------|--------|
| Clear entity identification | ❌ No schema, generic title | Critical |
| Service offerings defined | ❌ No structured service data | Critical |
| Location clearly stated | ⚠️ In footer only, no schema | High |
| Team/credentials visible | ⚠️ Present but unstructured | Medium |
| Industry keywords in content | ❌ Minimal content to index | Critical |
| FAQ content | ❌ None | High |
| Project/case study detail | ❌ Minimal, no dates/outcomes | High |
| Certifications/affiliations | ❌ Only AHA logo shown | Medium |

**AI Search Score: 1/10** — An AI search tool asked "safety training companies in Minnesota for railroad compliance" would never surface STARS. The site provides almost no indexable, structured content about what the company does.

---

## Recommendation

Complete rebuild from scratch:
- Single-page professional design with clear service sections
- Comprehensive structured data (ProfessionalService + LocalBusiness)
- Industry-keyword-rich content targeting railroad, pipeline, and government safety training
- Prominent contact/quote request form
- Team section with updated bios and credentials
- Project showcase with dates and outcomes
- FAQ section for AI search readiness
- Mobile-first responsive design
- Cloudflare Pages deployment for 90+ PageSpeed
