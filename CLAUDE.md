# KMT Medical Website Project

**Last Updated:** 2026-01-13

## Current Status

### Completed
- [x] Homepage rebrand (Women's Wellness → Holistic Wellness for all ages)
- [x] New navigation structure implemented across all pages
- [x] Naturopathy page created (8 service cards using Assessments template)
- [x] Shop "Coming Soon" placeholder page created
- [x] 3 locations section added (Oakville, Ajax, Maple)
- [x] IV Therapy repositioned (medical wellness, not med spa)
- [x] EmpowerHer de-emphasized as one program among many
- [x] Footer updated with all 3 locations on all pages
- [x] assessments.html updated with new nav/footer
- [x] empowerher.html updated with new nav/footer
- [x] **Header redesigned**: Logo now positioned above navigation menu (vertical layout)
- [x] **Footer enhanced**: All 3 clinic locations prominently displayed with location cards, proper SVG social icons, business hours, and "Book Now" CTA button
- [x] All 5 pages updated with consistent header and footer branding (index.html, assessments.html, empowerher.html, naturopathy.html, shop.html)

### Pending
- [ ] Dedicated Psychotherapy page (currently dropdown only)
- [ ] Dedicated Holistic Wellness page (currently dropdown only)
- [ ] Dedicated Contact Us page (currently dropdown only)
- [ ] Ajax and Maple location addresses (TBD from client)

---

## Client Overview

**Business Name:** KMT Medical and Allied Health Group
**Owner:** Karen M. Thornton
**Industry:** Healthcare / Mental Health / Holistic Wellness
**Website:** https://kmthealth.com

## Project Context

This is a website redesign/update project for KMT Medical, a multidisciplinary health clinic. The client has provided specific feedback requiring a significant repositioning of the brand and website content.

## Critical Business Rules

### Identity Positioning (CRITICAL)
- **NOT a Women's Clinic** - serves all ages and all genders
- Remove ALL woman-focused imagery and branding
- EmpowerHer is ONE program among many, not the clinic identity
- Position as a **Multidisciplinary Health Clinic**
- Services include: Psychotherapy, Assessments, Naturopathy, IV Therapy, Acupuncture, RMT, Supplements

### Locations (3 Total)
1. **Oakville (Main)** - 1939 Ironoak Way, Unit A204, Oakville, ON L6H 3V8
2. **Ajax** - Address TBD
3. **Maple (Woodbridge area)** - Address TBD

Footer and site must represent all three locations.

### Business Name Usage (SEO)
- **Legal name:** KMT Medical and Allied Health Group
- **Homepage:** Use full name "KMT Medical and Allied Health Group"
- **Other pages:** Use "KMT Medical" (shorter for SEO optimization)

## Approved Navigation Structure

```
Menu:
├── Psychotherapy (includes EMDR, Couples Therapy)
├── Assessments (current structure approved - Karen loved it)
├── Naturopathy (NEW PAGE NEEDED)
├── Holistic Wellness (IV Therapy, RMT, Aesthetics)
├── Shop (Coming Soon placeholder)
└── Contact Us

Header Layout: Logo at top, menu underneath (more room)
```

## Page Templates

### Assessments Page (APPROVED TEMPLATE)
Karen loved the Assessments page structure. Use this as the template for:
- New Naturopathy page
- Any other service pages

Key features of the approved format:
- Hero section with badge
- Value strip with 3 key points
- Card-based service listings (featured + regular)
- Comparison/quick guide table
- FAQ accordion section
- CTA section

## IV Therapy Positioning (CRITICAL)

**Karen does NOT want to be perceived as a med spa.**

### Primary Focus (Evidence-Based) - Feature prominently:
- Vitamin D supplementation
- Iron deficiency treatment
- Headaches/migraines
- Stress management
- Sports recovery
- Hangover recovery
- Jet lag
- Marathon prep/recovery

### De-emphasize (Additional Services) - Move to bottom:
- PRP (Platelet-Rich Plasma)
- Microneedling
- Botox/Fillers
- Facials

## New Pages Required

### 1. Naturopathy Page
Focus areas (use Assessments page format):
- Hormonal Health (PCOS, menopause, endometriosis, thyroid)
- Fertility and Reproductive Health
- Stress Management and Emotional Well-being
- Weight Management and Nutrition
- Digestive Health
- Immune System Support
- Skin and Aesthetics
- Acupuncture

### 2. Shop Page
- Simple "Coming Soon" placeholder
- Links to placeholder page

### 3. Psychotherapy Page (Enhanced)
Add to existing content:
- EMDR (Eye Movement Desensitization Reprocessing)
- Couples Therapy

### 4. Holistic Wellness Page (Updated)
- IV Therapy info (reference: https://kmthealth.com/iv-therapy)
- RMT (Registered Massage Therapy)
- Aesthetics (de-emphasized)

## Technical Notes

### File Structure
```
/
├── index.html          # Homepage (UPDATED - rebranded)
├── assessments.html    # Psychological Assessments (APPROVED TEMPLATE)
├── empowerher.html     # EmpowerHer Program (UPDATED - new nav/footer)
├── naturopathy.html    # Naturopathic Medicine (CREATED)
├── shop.html           # Shop Coming Soon (CREATED)
├── css/
│   └── styles.css      # Main stylesheet
├── images/
│   ├── kmtlogo.avif    # KMT Logo
│   ├── doc1.avif       # Karen M. Thornton photo
│   ├── doc2.avif       # Team member photo
│   ├── doc3.avif       # Team member photo
│   └── doc4.avif       # Team member photo
├── docs/
│   ├── requirements.md # Detailed requirements
│   ├── site-structure.md # Navigation and page hierarchy
│   └── seo-guidelines.md # SEO strategy and keywords
├── Issues/
│   └── KMT Site Updates - 2026-01-12.docx # Client feedback
└── CLAUDE.md           # This file - project context
```

### Pages Still Needed
```
├── holistic.html       # Holistic Wellness (IV Therapy, RMT)
├── psychotherapy.html  # Psychotherapy services
└── contact.html        # Contact Us with all locations
```

### Design System
- Primary font: Playfair Display (headings)
- Secondary font: Inter (body)
- Primary color: --kmt-teal (#2A7B9B)
- Accent color: --kmt-coral
- Light background: --kmt-light

### Contact Information
- Phone: (905) 829-5686
- Email: reception@kmthealth.com
- Social: Facebook, Instagram, LinkedIn (@KMT.health, @KMT.alliedhealth)

## Development Guidelines

1. Always use the Assessments page as the template reference for new pages
2. Ensure all pages have consistent navigation and footer
3. Footer must show all 3 locations
4. Use semantic HTML and accessible markup
5. Mobile-responsive design is required
6. Keep aesthetics/med-spa services de-emphasized throughout

## Git Workflow

**IMPORTANT: Update CLAUDE.md before any commit or git push.**

Before committing changes:
1. Update the "Current Status" section with completed/pending items
2. Update the "Last Updated" date
3. Update file structure if new files were added
4. Document any new patterns or decisions made

This ensures project context is always current for future development sessions.

## Reference Documents

- `/Issues/KMT Site Updates - 2026-01-12.docx` - Original client feedback document
- `/docs/requirements.md` - Detailed implementation requirements
