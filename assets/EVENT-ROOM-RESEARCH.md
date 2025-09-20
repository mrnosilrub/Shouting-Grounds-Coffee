# Coffee Shop Private Event Room Research

## Real examples with links

- Mozart’s Coffee Roasters (Austin, TX) — Private Events  
  https://mozartscoffee.com/pages/private-events

- Common Bond (Houston, TX) — Private Dining & Events  
  https://commonbondcafe.com/private-dining

- EL&N London — Private Hire  
  https://www.elnlondon.com/private-hire

- Notes Coffee Roasters & Bars (London) — Private Hire  
  https://notescoffee.shop/pages/private-hire

- Balzac’s Coffee Roasters (Canada) — Private Events  
  https://balzacs.com/pages/private-events

- The Grounds of Alexandria (Sydney) — Weddings & Events  
  https://thegrounds.com.au/weddings-events/

- Optional third‑party listing model: Peerspace (calendar, payments, rules, insurance handled off‑site)  
  Houston coffee shop listings: https://www.peerspace.com/venues/houston--tx/coffee-shop

## Common patterns that work

- Dedicated “Private Events” page in main nav
- Hero image of the space, then quick facts: capacity (seated/standing), square footage, layouts
- Amenities list: Wi‑Fi, AV (screen/projector), sound/mic, parking, accessibility
- Food & beverage details: packages, minimums, outside food policy
- Pricing transparency: at least “starting at” or minimum spend
- Gallery with multiple angles and setups
- FAQs: setup/tear‑down windows, decorations, alcohol policy, deposits/cancellations, cleaning fees
- Prominent inquiry CTA (form) plus direct contact (email/phone)
- Simple inquiry form (name, email, phone, date/time, headcount, event type, notes)
- Location‑specific pages if multiple venues
- Clear terms PDF/section and quick response promise (e.g., “We reply within 1 business day”)

## Recommended page for Shouting Grounds (New Caney, TX)

- URL: /private-events or /events
- Nav: add “Events” between `Gallery` and `Visit`
- Sections: 
  1) Hero: photo of the room; subhead with value proposition
  2) Quick facts: capacity (seated/standing), room size, hours available, parking
  3) Amenities: Wi‑Fi, TV/HDMI/projector, speakers, mic, tables/chairs, decor rules
  4) Packages & pricing: publish rates or “starting at”; coffee/pastry bundles
  5) Gallery: 6–10 images, varied layouts (meetings, showers, workshops)
  6) FAQs: setup/cleanup windows, outside food policy, deposits/cancellations
  7) Inquiry form: embedded; also list phone/email
  8) Trust: short testimonials (re‑use highlights from reviews)

### Form fields

- Name, email, phone
- Preferred date/time, expected headcount, event type, notes

### Calls‑to‑action

- Primary: “Check Availability”  
- Secondary: “Request a Quote” and a tappable phone number

## Content and UX tips

- Photography: daylight and evening shots; various layouts; simple floor plan if possible
- Pricing: if you prefer not to list full rates, use “starting at” and/or a minimum spend
- Response SLA: “We reply within 1 business day” near the form
- Accessibility: note step‑free access, restrooms, and parking
- Local clarity: embed a Google Map; reiterate address and directions

## Technical notes (fit your current stack)

- New page: `/private-events/index.html` using existing Tailwind and components
- Reuse FormSubmit endpoint with a distinct subject and redirect
  - `_subject`: “Private Event Inquiry — Shouting Grounds”
  - `_next`: `https://shoutinggrounds.com/private-events/?sent=1#form`
- Optional: Calendly link for tours; keep direct email/phone prominent
- Add JSON‑LD “LocalBusiness” with amenity features for SEO around “event space”, “private room”, etc.

## Copy starter

- Headline: “Gather Here”
- Subhead: “A cozy private room in New Caney for meetings, showers, workshops, and more.”
- Bullets:
  - “Up to [X] seated / [Y] standing”
  - “Wi‑Fi, TV/HDMI, speakers, and flexible layouts”
  - “Coffee & pastry packages available; outside food welcome by prior arrangement”
- Primary CTA: “Check Availability”

## KPIs to watch

- Form submissions per week
- Response time to inquiries
- Tour‑to‑booking conversion
- Average booking value; most requested time slots


