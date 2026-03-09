# Requirements: Fleek Careers Page

**Defined:** 2026-03-06
**Core Value:** A candidate who lands on this page understands within 30 seconds that Fleek is building the operating system for a $250B industry that has never been digitized, and feels compelled to apply.

---

## v1 Requirements

### Foundation

- [ ] **FOUND-01**: Page loads from a single HTML file with no build step required
- [ ] **FOUND-02**: Tailwind CSS loaded via CDN (no local installation)
- [ ] **FOUND-03**: Page is fully responsive across mobile, tablet, and desktop
- [ ] **FOUND-04**: Page achieves Lighthouse performance score of 90+ (no heavy dependencies)
- [ ] **FOUND-05**: Page is deployable to Vercel or Netlify by dragging a folder

### Navigation

- [ ] **NAV-01**: Fixed navigation bar with Fleek wordmark/logo on left
- [ ] **NAV-02**: "View open roles" CTA on right anchors to roles section on click
- [ ] **NAV-03**: Nav background transitions from transparent to solid on scroll

### Hero

- [ ] **HERO-01**: Full-viewport hero with bold H1: "Building the operating system for the secondhand economy."
- [ ] **HERO-02**: Subheading: "A $250B industry still runs on WhatsApp. We're changing that."
- [ ] **HERO-03**: Two CTAs: "View open roles" (primary, yellow) and "Our story" (secondary, outline)
- [ ] **HERO-04**: Investor logos row: a16z, Y Combinator, HV Capital, Burda
- [ ] **HERO-05**: Black background, yellow accent typography on key phrases

### Problem Section

- [ ] **PROB-01**: Section headline: "The supply chain that ships your clothes around the world twice."
- [ ] **PROB-02**: Visual three-step supply chain flow (Collection → Sort West → Sort East) using HTML/CSS
- [ ] **PROB-03**: Key stats: 15B items collected annually, 80% shipped overseas, 12% resold back West
- [ ] **PROB-04**: Callout quote/pull stat: "A vintage Levi's jacket that could sell for £50 gets shipped overseas for pennies."
- [ ] **PROB-05**: Section closes with the opportunity setup: "The technology to fix this has never existed — until now."

### Technology Section (FleekSort)

- [ ] **TECH-01**: Section headline: "The world's first LLM fine-tuned on secondhand fashion."
- [ ] **TECH-02**: FleekSort product UI screenshot (from ESG deck) displayed as a hero visual
- [ ] **TECH-03**: Three capability cards: Automated Sorting / Agentic Sourcing / AI Quality Check
- [ ] **TECH-04**: Stats prominently displayed: "6 seconds" and "82% accuracy"
- [ ] **TECH-05**: Data moat callout: "100 tonnes of clothing processed monthly. Every transaction trains the model. No one else has this dataset."

### Traction Section

- [ ] **TRACT-01**: Stats grid with: $68M GMV (2025), 3x annual revenue growth, 9M items saved, 500K+ items/month
- [ ] **TRACT-02**: Environmental impact sub-row: 17,400 tonnes CO2 avoided, 10.8B litres water saved
- [ ] **TRACT-03**: Investor logos with names (not just logos): a16z, Y Combinator, HV Capital, Burda
- [ ] **TRACT-04**: Team stat: 100+ people across London, India, Pakistan

### Why Now Section

- [ ] **NOW-01**: Section headline: "Three forces are converging. Right now."
- [ ] **NOW-02**: Three cards: EU Regulation (Oct 2025 directive), Consumer Demand (58% bought secondhand in 2024), AI Capability (FleekSort in production)
- [ ] **NOW-03**: Timeline urgency: use verified near-term growth projection (~63% growth by 2030, not 3x by 2027 which is a 2050 figure).

### The Opportunity Section

- [ ] **OPP-01**: Bold opener: "Joining Fleek is like joining Shopify before merchants went online, or Stripe before payments went digital."
- [ ] **OPP-02**: Five career reasons as a clean list with brief explanations (from Master Pitch "Why You" section)
- [ ] **OPP-03**: Founder profiles: Abhi Arora (Dubsmash/Reddit, Berkeley/Cambridge) and Sanket Agarwal (Google, Uber)
- [ ] **OPP-04**: CTA: "See open roles"

### Values Section

- [ ] **VAL-01**: Section headline: "How we work."
- [ ] **VAL-02**: All 5 core values displayed as cards with title and one-line description
  - Dream Big and Disrupt Yourself
  - Absolute Ownership
  - Curiosity Leads the Way
  - Talk to the Customer
  - Embrace Diversity

### Open Roles Section

- [ ] **ROLES-01**: Section headline: "Open roles" with live role count
- [ ] **ROLES-02**: Ashby job board embed (JavaScript widget from jobs.ashbyhq.com/fleek)
- [ ] **ROLES-03**: Fallback link: "View all roles on Ashby" if embed fails to load
- [ ] **ROLES-04**: "Don't see your role? We'd still love to hear from you." with speculative application link

### Footer

- [ ] **FOOT-01**: Fleek logo + tagline "Making second-hand first choice."
- [ ] **FOOT-02**: Link to joinfleek.com
- [ ] **FOOT-03**: LinkedIn and relevant social links
- [ ] **FOOT-04**: Copyright line

---

## v2 Requirements

### Enhancements

- **V2-01**: Subtle scroll animations (fade-in sections, stat counters)
- **V2-02**: Photography integration once assets are available (team, London office, Pakistan operations)
- **V2-03**: Embedded video (founder intro Loom or produced culture video)
- **V2-04**: Role filtering by department/team on the careers section
- **V2-05**: Testimonial section — quotes from employees by function (engineering, commercial)
- **V2-06**: Dark/light mode toggle

### Future

- **FUT-01**: CMS layer so non-devs can update stats and copy without touching HTML
- **FUT-02**: Job alert signup (email capture for candidates interested in future roles)

---

## Out of Scope

| Feature | Reason |
|---------|--------|
| Custom application flow | Ashby handles all applications — no duplication needed |
| Hardcoded job listings | Ashby embed keeps listings current automatically |
| Blog / culture articles | Depth can come later; ship the story page first |
| Multiple languages | English only for v1 global launch |
| React/Next.js framework | No build step is a feature for v1 maintainability |
| Perks/benefits section | Fleek competes on mission and opportunity, not perks |
| Salary transparency | Handled at job description level in Ashby |

---

## Traceability

| Requirement | Phase | Status |
|-------------|-------|--------|
| FOUND-01 through FOUND-05 | Phase 1 | Pending |
| NAV-01 through NAV-03 | Phase 1 | Pending |
| HERO-01 through HERO-05 | Phase 1 | Pending |
| PROB-01 through PROB-05 | Phase 2 | Pending |
| TECH-01 through TECH-05 | Phase 2 | Pending |
| TRACT-01 through TRACT-04 | Phase 2 | Pending |
| NOW-01 through NOW-03 | Phase 2 | Pending |
| OPP-01 through OPP-04 | Phase 3 | Pending |
| VAL-01 through VAL-02 | Phase 3 | Pending |
| ROLES-01 through ROLES-04 | Phase 3 | Pending |
| FOOT-01 through FOOT-04 | Phase 3 | Pending |

**Coverage:**
- v1 requirements: 43 total
- Mapped to phases: 43
- Unmapped: 0

---
*Requirements defined: 2026-03-06*
*Last updated: 2026-03-06 after initial definition*
