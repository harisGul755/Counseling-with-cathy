# Site Report — counselingwithcathy.com
**Practice:** Counseling with Cathy (Catherine Becker) — online (telehealth-only) therapy, New York. Specialty: OCD, OCD spectrum, anxiety via ERP. 13+ years' experience, ERP-certified.
**Platform:** Squarespace. **Booking:** Headway. **Email:** connect@counselingwithcathy.com **Phone:** (347) 926-3302

## Pages (5)
| Page | URL | Content |
|---|---|---|
| Home | / | Hero "a safe space for healing & growth / Hi, I'm Cathy"; ERP specialty statement; OCD description; My Approach; services list; quick links; crisis note |
| FAQs | /faqs | 5 Q&As: first session, scheduling, consultation call, insurance (Aetna, Anthem BCBS, Oscar, Oxford, UnitedHealthcare), telehealth only |
| Contact | /contact | Booking link, form, email, phone |
| No Surprises Act | /no-surprises-act | Good Faith Estimate rights ($400 dispute threshold) |
| Crisis Resources | /resources | 12 hotlines (988, Crisis Text Line, Poison Control, DV, Nisa, RAINN, NEDA, NAF, HIV Nightline, Physician Support, Trevor, Trans Lifeline) |

## Issues on the current site
- Home page has no meta title beyond the brand name; FAQs/Contact/Resources have empty meta descriptions.
- No Surprises Act page is titled "Privacy Policy 2" (leftover title).
- Contact page links to a staging domain (point-hyperboloid-bf5p.squarespace.com) for resources.
- Resources page lists NEDA's helpline; verify it is still active.
- Navigation omits No Surprises Act and Resources (footer only); no services section as its own page; no testimonials, no photo captions/alt text visible.

## Brand (from the supplied logo)
Logo colors: dark chocolate brown (#4A2C25), copper (#B8805F), tan (#D9A988), warm cream. These are the CSS variables at the top of style.css. Fonts: Cormorant Garamond (headings) + Manrope (body). Tone: warm, non-judgmental, professional. Logo files are in assets/ (colored for the header, cream version for the dark footer).

## Pages added in the template
Services page (5 services, each with detail text and an illustration). The detail bullets on that page are drafted descriptions, not original site text: have Cathy review them. Home also gains: trust strip, "How to get started" steps, insurance section, background-image call-to-action.

## What the template adds
Scroll progress bar, sticky blur header, hero parallax + masked headline reveal, scroll-pinned "How OCD can show up" sequence (ScrollTrigger), arch image reveals, draggable Services slider with arrows/dots, animated FAQ accordion, mobile menu, reduced-motion support.
Photos hotlink the original Squarespace CDN (hero, Cathy, two section photos); download and host them locally before launch. Service illustrations are SVGs in assets/.
