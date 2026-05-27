Build a premium investor-focused virtual walkthrough experience for Ridgewood Mansion at 54 Ridgewood Place, Springfield, MA 01105.

This is a SINGLE-FILE HTML application (index.html) with all CSS and JS inline. No build system, no npm, no dependencies to install. It should work by opening index.html directly in a browser.

USE THESE CDN LINKS (no local installs):
- Tailwind CSS: https://cdn.tailwindcss.com
- Alpine.js: https://unpkg.com/alpinejs@3.x.x/dist/cdn.min.js
- Google Fonts: Playfair Display + Inter
- Icons: inline SVG only

==================================================
PROPERTY FACTS
==================================================
- Address: 54 Ridgewood Pl, Springfield, MA 01105
- 12 rooms total
- 6 bathrooms
- Large parking area
- Adjacent lot (expansion potential)
- Updated electrical
- Roof updates done
- Current revenue: $7,900/mo (8/12 rooms occupied)
- Full potential: $12,200/mo (all 12 rooms)
- Shared housing / workforce housing model
- Traveling nurse / traveling professional model
- Group housing opportunity
- 3 floors (basement income area, 1st floor, 2nd floor, attic)

==================================================
DESIGN REQUIREMENTS
==================================================
- Color scheme: charcoal (#1a1a1a), black (#0d0d0d), gold (#c9a84c), soft white (#f5f5f5)
- Cinematic, luxury investor presentation feel
- Dark theme throughout
- Gold accent lines, borders, highlights
- Clean modern typography
- Smooth CSS transitions and animations
- Mobile first, fully responsive

==================================================
SECTION 1 — HERO
==================================================
- Full-screen dark hero
- Property name: "Ridgewood Mansion"
- Subtitle: "54 Ridgewood Place, Springfield, MA | Investor Opportunity"
- 4 CTA buttons: "Begin Tour", "Download Package", "Request Showing", "Contact Seller"
- Animated gold divider line
- Key stats bar: 12 Rooms | $7,900/mo Current | $12,200/mo Potential | 6 Baths | 3 Floors

==================================================
SECTION 2 — INVESTMENT SNAPSHOT
==================================================
Cards showing:
- Current Cash Flow: $7,900/mo
- Full Potential: $12,200/mo
- Upside: $4,300/mo
- Rooms: 12
- Bathrooms: 6
- Occupancy: 8/12 (67%)
- Strategy: Shared Housing / Traveling Professional
Gold card borders, dark backgrounds, numbers in large gold text.

==================================================
SECTION 3 — GUIDED WALKTHROUGH
==================================================
Tab navigation: Exterior | Entry | 1st Floor | 2nd Floor | Basement | Bathrooms | Parking | Adjacent Lot

Each section has:
- Large placeholder image (CSS gradient, 600x400 ratio, no external images)
- Room title
- Compelling investor-focused description
- Income Overlay badge
- Key features list

Copy for each tab:
EXTERIOR: A commanding 3-story Victorian-era mansion with modern updates. Updated roof, ample parking, adjacent lot for future expansion. First impressions convey scale, permanence, and income potential.
ENTRY: Grand entry sets the tone for discerning residents. High ceilings, natural light, and architectural character that justify premium room rates.
1ST FLOOR: Three private rooms with direct access. Ideal for traveling professionals seeking ground-floor convenience. Includes shared common areas and kitchen access.
2ND FLOOR: Upper-level rooms with balcony access. Premium positioning for long-term residents or corporate housing placements. Privacy and natural light.
BASEMENT: A fully functional income unit with private entrance potential. Currently generating revenue as 4 separate rooms. Unique value-add asset within the property.
BATHROOMS: 6 full bathrooms serving 12 rooms — a key differentiator for shared housing models. Low friction for resident satisfaction and retention.
PARKING: Private off-street parking for multiple vehicles. A premium amenity in Springfield's urban core. Adds value for tenants and operational flexibility for the owner.
ADJACENT LOT: The adjacent lot presents a rare expansion opportunity — ADU construction, additional parking, or future development. A value multiplier that very few comparable properties offer.

==================================================
SECTION 4 — INCOME OPPORTUNITY
==================================================
Heading: "Why Ridgewood Mansion Is a Cash Flow Machine"
3 income model cards:
a) Standard Shared Housing: 12 rooms x $800-$1,000/mo avg = $9,600-$12,000/mo
b) Traveling Professional Model: 12 rooms x $1,200-$1,500/mo avg = $14,400-$18,000/mo
c) Hybrid Strategy: Mix of long-term + mid-term = $11,000-$15,000/mo
Gold border cards, income numbers in large gold text.

==================================================
SECTION 5 — PROPERTY HIGHLIGHTS
==================================================
Icon grid (6 items, use inline SVG or emoji):
- 12 Income Rooms
- 6 Full Bathrooms
- Private Parking
- Updated Electrical
- Adjacent Lot
- 3-Floor Layout
Each card: title, description, gold accent.

==================================================
SECTION 6 — INVESTMENT MODELS
==================================================
Cards for buyer personas:
- House Hacker: Live in one unit, rent the rest
- Workforce Housing Operator: Contract with employers, place workers
- Traveling Nurse Operator: 30-90 day furnished placements
- Traditional Landlord: Long-term room rentals, steady cash flow
- Group Home Operator: Licensed group home potential

==================================================
SECTION 7 — INTERACTIVE FLOORPLAN
==================================================
Build a CSS/HTML floorplan visualization (no external lib).
4 floor tabs: Basement | 1st Floor | 2nd Floor | Attic

Each floor: grid of room boxes with room label, monthly rate, and colored status dot.
Click a room to show a details modal.

Room data:
BASEMENT (all occupied - green):
- Room 1: $1,400/mo — Basement Apartment
- Room 2: $1,000/mo — Basement Kitchenette
- Room 3: $900/mo — Basement Walk-In
- Room 4: $800/mo — Basement TV Room

1ST FLOOR (all vacant - yellow):
- Room 5: $1,000/mo — Large Room (AVAILABLE)
- Room 6: $1,500/mo — Apartment Suite (AVAILABLE)
- Room 7: $1,200/mo — Standard Room (AVAILABLE)

2ND FLOOR (all occupied - green):
- Room 8: $1,000/mo — Balcony Room
- Room 9: $800/mo — Small Room
- Room 10: $800/mo — Very Small Room

ATTIC (all vacant - yellow):
- Room 11: $900/mo — Attic Loft (AVAILABLE)
- Room 12: $900/mo — Attic Loft (AVAILABLE)

==================================================
SECTION 8 — LEAD CAPTURE FORM
==================================================
Heading: "Request Investor Access"
Subheading: "Get the full investor package, schedule a showing, or connect with the seller."
Fields:
- Full Name (required)
- Email (required)
- Phone
- Investor Type dropdown: Individual Investor | Real Estate Syndicator | Family Office | Operator/Buyer | Other
- Message / Notes textarea
- Checkbox: "I want to schedule a showing"
- Checkbox: "Send me the Investor Package PDF"
- Submit button: "Request Access" (gold)
On submit: show thank you message (JS only, no backend needed).

==================================================
SECTION 9 — FOOTER
==================================================
- "Ridgewood Mansion — A Dortch Enterprises Property"
- Gold divider line
- Copyright 2026 Dortch Enterprises LLC

==================================================
JS FEATURES
==================================================
- Smooth scroll navigation
- Walkthrough tab switching
- Floor tab switching for floorplan
- Room modal on click (show room details)
- Form validation + success message
- Scroll-triggered fade-in animations (Intersection Observer)
- Mobile nav menu toggle

==================================================
IMAGE PLACEHOLDERS
==================================================
Use CSS gradients only — no external image services.
- Exterior: warm amber/brown gradient suggesting brick
- Rooms: cool blue-gray gradient
- Basement: deeper charcoal gradient
- Parking/Lot: gray-green gradient
Add room name as text overlay on each placeholder.

==================================================
QUALITY BAR
==================================================
This must look like a $50,000 real estate marketing site.
Every section intentional and premium.
Excellent typography hierarchy.
Generous whitespace.
Gold accents tasteful, not gaudy.
Fast loading.

==================================================
OUTPUT
==================================================
Save as: /Users/thomas/Projects/ridgewood-investor/index.html

When completely finished, run this exact command:
openclaw system event --text "Done: Ridgewood Investor Walkthrough built at /Users/thomas/Projects/ridgewood-investor/index.html" --mode now
