POE Part 3- website enhancement

This repo holds my assignment website for POE PART2. It's a  website showing HTML, CSS and JavaScript features, with forms, interactive elements, and SEO basics. I kept the code readable and commented so it's easy to follow.


POE Part 3 — Enhancing Functionality and SEO

In part 2 the main focus was designing the website by applying CSS styling and ensuring the design is responsive across different devices.

Part 3 was mainly about enhancing the functionality of the website. So I made the following changes:
- Implemented JavaScript interactive components.
- Added dynamic content loading and client-side search/filter on the events listing.
- Added interactive map using Leaflet with a sample location marker and popup.
- Added CSS and JavaScript transitions.
- Created enquiry and contact forms with HTML5 attributes, JavaScript validation, and AJAX submission.
- Built a robots.txt and sitemap.xml for search engines.
- Improved on-page SEO: meta tags, structured heading usage, descriptive image filenames and alt text.
- Basic page speed and security recommendations documented.
- All edits recorded in the changelog section below.

Changelog
- Part 3 implementation ST10447349
  - Added JavaScript enhancements:
    - Dropdown panel component for FAQ section.
    - Tabbed content for "Services" section .
    - Dropdown panel implementation for newsletter/signup calls-to-action.
    - Image gallery with lightbox feature using a small JS lightbox.
    - Dynamic content loader to fetch and render JSON posts (assets/data/events.json).
    - Client-side search and sort for events/services.
    - Leaflet map integration with a sample marker for the organisation location.
  - Form functionality:
    - Added enquiry.html and contact.html with HTML5 validation attributes and custom JavaScript validation.
    - Enquiry form calculates a sample cost/availability response after validation and shows it inline. Uses a safe AJAX demo option to show how a POST would work.
    - Contact form compiles validated data into a "mail to:" link and prompts the user to open their email client.
  - SEO and site structure:
    - Added robots.txt and sitemap.xml to root .
    - Added descriptive meta titles and descriptions to HTML templates.
    - Added image alt-text and renamed images to use descriptive filenames.
    - Documented internal linking improvements and mobile-friendly verification steps.
  - Accessibility and UX:
    - Added ARIA attributes on interactive components and aria-live regions for responses.
    - Ensured keyboard navigation for modals, tabs, and lightbox where possible.
  - Performance & Security:
    - Minification recommended for CSS/JS; placeholder minified assets suggested.
    - Recommendation for setting caching headers and enabling HTTPS.
      
  - Feedback fixes (from earlier feedback):
    - Fixed broken header link to the events page.
    - Corrected form field labels and added required attributes where missing.
    - Improved semantic HTML structure 
    - Updated image paths that previously caused 404s.
    - Documented each change here with detail for lecturer review.

      Github link:https://github.com/ST10447349/poe_par2.git 

References
Beaird, J. & George, J., 2020. The Principles of Beautiful Web Design. 4th ed. San Francisco: SitePoint.	W3Schools, 2025. CSS Tutorial. [online] Available at: https://www.w3schools.com/css/ [Accessed 29 September 2025].
MDN Web Docs, 2025. Responsive design. [online] Available at: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design [Accessed 29 September 2025].	Box, R., 2022. Web Typography: Practical Guide. London: Routledge.	Nielsen, J., 2023. Usability Heuristics for User Interface Design. [online] Nielsen Norman Group. Available at: https://www.nngroup.com/articles/ten-usability-heuristics/ [Accessed 29 September 2025].
United Nations, 2023. Climate Change Education Resources. [online] Available at: https://www.un.org/en/climatechange/education [Accessed 29 September 2025].
Google Fonts, 2025. Montserrat and Open Sans. [online] Available at: https://fonts.google.com/ [Accessed 29 September 2025].
FontAwesome, 2025. Icons for Websites. [online] Available at: https://fontawesome.com/ [Accessed 29 September 2025].
PayFast, 2025. Online Payment Solutions for South Africa. [online] Available at: https://www.payfast.co.za/ [Accessed 29 September 2025].
Leaflet.js — https://leafletjs.com/ 
MDN Web Docs — HTML, CSS, JavaScript, Form validation
Google Developers — SEO Starter Guide
Lighthouse (Chrome) — performance and accessibility testing

