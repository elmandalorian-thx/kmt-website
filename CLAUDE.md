# KMT Medical Website Project

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
├── index.html          # Homepage
├── assessments.html    # Psychological Assessments (APPROVED)
├── empowerher.html     # EmpowerHer Program (one program, not identity)
├── naturopathy.html    # NEW - Naturopathic Medicine
├── holistic.html       # NEW - Holistic Wellness
├── psychotherapy.html  # NEW - Psychotherapy services
├── shop.html           # NEW - Coming Soon placeholder
├── contact.html        # NEW - Contact Us
├── css/
│   └── styles.css      # Main stylesheet
├── images/
│   ├── kmtlogo.avif    # KMT Logo
│   ├── doc1.avif       # Karen M. Thornton photo
│   ├── doc2.avif       # Team member photo
│   ├── doc3.avif       # Team member photo
│   └── doc4.avif       # Team member photo
└── docs/
    └── requirements.md # Detailed requirements
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

## Reference Documents

- `/Issues/KMT Site Updates - 2026-01-12.docx` - Original client feedback document
- `/docs/requirements.md` - Detailed implementation requirements
