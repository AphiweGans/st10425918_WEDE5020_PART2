# ST10425918_WEDE5020_PART3
## PART 3 README
Reference
Screenshots
Overview "What did you do and add on this file"
# ST10425918_AphiweGans_WEDE5020_PART3


Youth Empowerment & Business Solutions Hub. 2025. Home - Youth Empowerment & Business Solutions Hub. [online]. Available at: file:///C:/Users/RC_Student_lab/OneDrive/css/index.html[Accessed 21 August 2025].

Youth Empowerment & Business Solutions Hub. 2025. About - Youth Empowerment & Business Solutions Hub. [online]. Available at: file:///C:/Users/RC_Student_lab/OneDrive/css/about.html [Accessed 21 August 2025].

Youth Empowerment & Business Solutions Hub. 2025. Contact - Youth Empowerment & Business Solutions Hub. [online]. file:///C:/Users/RC_Student_lab/OneDrive/css/contact.html [Accessed 21 August 2025].

Youth Empowerment & Business Solutions Hub. 2025. Enquiry - Youth Empowerment & Business Solutions Hub. [online]. Available at: file:///C:/Users/RC_Student_lab/OneDrive/css/enquiry.html [Accessed 21 August 2025].

Youth Empowerment & Business Solutions Hub. 2025. Services - Youth Empowerment & Business Solutions Hub. [online]. Available at: file:///C:/Users/RC_Student_lab/OneDrive/css/services.html [Accessed 21 August 2025].



## Part 1 Entries
2025-09-22 - Added wireframe in the proposal.
2025-09-22 - Improved the content research and sourcing to be highly relevant, comprehensive and well-detailed.
2025-09-22 - Improved the website structure and planning to be more detailed.
2025-09-22 - Added changelog.
2025-09-22 - Improved website structure and planning to be more detailed.


## References:

Krug, S. 2014. Don’t make me think: A common sense approach to web usability. 3rd ed. San Francisco: New Riders.
Laudon, K.C. and Traver, C.G. 2021. E-commerce 2021: Business, technology, society. 16th ed. Harlow: Pearson.
Lidwell, W., Holden, K. and Butler, J. 2010. Universal principles of design. 2nd ed. Beverly: Rockport.
OECD. 2021. Entrepreneurship policies for youth in South Africa. [Online]. Available at: https://www.oecd.org [Accessed 26 August 2025].

# Youth Empowerment & Business Solutions Hub

## Overview
This project is a multi-page responsive website built for WEDE5020 POE Part 2. It showcases Youth Empowerment & Business Solutions Hub, including Home, About Us, Services, Enquiry, and Contact Us pages.

## Part 2 Summary
- External stylesheet (`css/style.css`) linked to all pages
- Base styles and CSS reset implemented
- Typography scaled with rem/em and responsive adjustments
- Layout uses CSS Grid and Flexbox
- Buttons, headings, and links styled with pseudo-classes
- Responsive design with breakpoints at 600px and 900px
- Navigation adapts for mobile
- Images are responsive with alt text
- Accessibility features: focus outlines, semantic HTML, labeled forms

## Screenshots
Desktop view screenshot - C:\Users\RC_Student_lab\OneDrive\css\css\Screenshots\Desktop.png

Tablet view screenshot - C:\Users\RC_Student_lab\OneDrive\css\css\Screenshots\Tablet.png

Mobile view screenshot - C:\Users\RC_Student_lab\OneDrive\css\css\Screenshots\Mobile.png


Tested on:
- Chrome
- Firefox
- Edge

## Breakpoints
- Mobile: ≤600px
- Tablet: 601px–900px
- Desktop: ≥901px

  <img width="1366" height="768" alt="Desktop" src="https://github.com/user-attachments/assets/a4291bf3-d13b-4ead-9dc2-1fe021be8760" />
  <img width="250" height="571" alt="Mobile" src="https://github.com/user-attachments/assets/d6b9d5f5-327b-431e-b06b-10b7c2e2e634" />

<img width="381" height="557" alt="Tablet" src="https://github.com/user-attachments/assets/1cdb2320-c5cf-4f8a-becb-b8f02853bc9d" />

## Part 3 Entries
## Part 3 — Enhancements (2025-11-12)
This section documents the Part 3 additions: interactivity, UX polish, forms integration, and SEO aids.

### Summary of features added
- Lightbox gallery: Clickable gallery images open in an overlay for larger view. Implemented with minimal JS/CSS for accessibility and performance.
- Service filter: Dropdown on `services.html` to filter service articles by category (training, mentorship, networking, resources, consulting).
- Responsive Google Maps embeds: Added to `contact.html` and `enquiry.html` using a responsive iframe wrapper.
- Form improvements: Both enquiry and contact forms now require a Message Type (Sponsor, Personal, Other). Inline validation and response messaging added. `contact.html` and `enquiry.html` post to Formspree (placeholder/public endpoint) for easy email handling.
- CSS polish: Gallery grid, lightbox styles, responsive map container, form response styling, and small UI improvements.
- SEO / crawl: Added `robots.txt` and `sitemap.xml` (basic templates) to the site folder.

### Files changed / added (key)
- css/js/scripts.js — Added lightbox, gallery filter, form validation/submit handlers, and message-type validation.
- css/services.html — Added `data-service` attributes to articles, fixed markup, and wired gallery/filter.
- css/contact.html — Added responsive Google Maps iframe, message-type select, contact response div, Formspree action.
- css/enquiry.html — Added message-type select, enquiry response div, Formspree action, same map embed.
- css/css/style.css — Added gallery grid, lightbox styles, responsive map styles, response message styling, and small UI tweaks.
- css/robots.txt — New: basic robots file.
- css/sitemap.xml — New: basic sitemap template.
- css/ST10425918_AphiweGans_WEDE5020_PART2/README.md — Updated Part 3 notes and testing instructions.

### Design decisions & notes
- Progressive enhancement: Forms include native `action` attributes so they work when JS is disabled; JS adds inline validation and optionally submits via fetch for a smoother UX.
- Accessibility: Response regions use `role="status"` and `aria-live="polite"`. Lightbox can be closed by clicking outside the image. (I can add Esc-to-close keyboard support if desired.)
- Formspree: `contact.html` and `enquiry.html` use a Formspree endpoint. Replace `https://formspree.io/f/mpwkzgwd` with your own endpoint if needed.



