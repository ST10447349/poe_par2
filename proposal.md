This is a short proposal for the POE part 3. It will explain the goals and objectives.

1. Goals & Objectives
- Goal: Build a small, accessible static site that demonstrates HTML, CSS, and JavaScript skills for the assignment.
- Objectives:
  - Implement interactive widgets (dropdown panel, tabs, popup, gallery/lightbox).
  - Add an interactive map.
  - Build enquiry + contact forms with client-side validation and a simulated submission flow.
  - Apply basic SEO: meta tags, robots.txt, sitemap.xml and a short JSON-LD example.
  - Show dynamic content loading (fetching JSON) and a client-side search/filter.

2. Current analysis (short)
- Similar student projects: often static with forms and a small JS file.
- Strengths: simple, clear code; uses well-known libs (Leaflet); focuses on learning outcomes from the brief.
- Limitations: no real backend (forms simulated), demo images and content are fictional.

3. Proposed features & functionality
- Home, Events, Enquiry, Contact pages.
- Accordion for FAQs, tabs for services, popup for CTAs, gallery with lightbox.
- Leaflet map for location.
- Events listing that can be loaded from JSON and filtered on the client.
- Enquiry form that calculates a simple cost estimate and shows availability.
- Contact form that compiles a mail to: and prompts the user.
- robots.txt and sitemap.xml templates for SEO.

4. Design aesthetic
- Simple, and clean 
- Colors: neutral background, blue accent for links/buttons.
- Responsive: layout works on phones through CSS media queries.
- Usability: clear labels, required fields, aria-live region for responses.

5. Wireframes 
- Header:
- Main 
  - Left: content (text, lists)
  - Right: small gallery / map (on large screens)
- Forms pages: form card centered, help text below
- Footer with student note

6. Technical requirements
- Static hosting 
- Files: index.html, events.html, enquiry.html, contact.html, assets/{css,js,images,data}
- Third-party libs: Leaflet.


7. Timeline
- Week 1: Part 1 planning + basic HTML skeleton.
- Week 2: Part 2 functionality + styling + feedback fixes.
- Week 3: Part 3 JS enhancements, map, forms validation, SEO files, testing, documentation.
- Final: polish, run Lighthouse, update README and changelog.

8. Two proposals 
- Proposal A (chosen): Community events hub — pages for events, volunteering, sponsors (this repo).
- Proposal B (alternative): Small e-commerce demo for student clubs (product pages, cart demo) — more JS work and would need at least mock payment flows.

9. Content research & sourcing
- Images: placeholders located in assets/images/ 
- Libraries: Leaflet docs and MDN used for reference.
- SEO: Google Starter Guide.

```