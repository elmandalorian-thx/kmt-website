# KMT Medical Website - Detailed Requirements

**Document Date:** 2026-01-12
**Source:** KMT Site Updates - 2026-01-12.docx
**Status:** Approved by Karen M. Thornton

---

## 1. Critical Repositioning Feedback

### 1.1 NOT a Women's Clinic
- Serves all ages and all genders
- Remove ALL woman-focused imagery and branding
- EmpowerHer is ONE program, not the clinic identity
- Update all copy to reflect this approach

### 1.2 Multidisciplinary Health Clinic
- Not just psychotherapy - it's comprehensive integrated care
- Services include:
  - Psychotherapy
  - Assessments
  - Naturopathy
  - IV Therapy
  - Acupuncture
  - RMT (Registered Massage Therapy)
  - Supplements
  - And more

### 1.3 Three Locations (Not Just Oakville)
| Location | Status | Address |
|----------|--------|---------|
| Oakville | Main | 1939 Ironoak Way, Unit A204, Oakville, ON L6H 3V8 |
| Ajax | Active | TBD |
| Maple (Woodbridge) | Active | TBD |

**Requirement:** Footer and site must represent all three locations.

---

## 2. Approved Navigation Structure

```
Main Menu:
├── Psychotherapy
│   ├── Individual Therapy
│   ├── Couples Therapy (NEW)
│   ├── Family Therapy
│   ├── Teen Counseling
│   └── EMDR (NEW)
│
├── Assessments (APPROVED - keep current structure)
│   ├── All Assessments
│   ├── Neuropsychological
│   ├── Psychoeducational
│   ├── Psychodiagnostic
│   └── Rehabilitation
│
├── Naturopathy (NEW PAGE)
│   ├── Hormonal Health
│   ├── Fertility and Reproductive Health
│   ├── Stress Management and Emotional Well-being
│   ├── Weight Management and Nutrition
│   ├── Digestive Health
│   ├── Immune System Support
│   ├── Skin and Aesthetics
│   └── Acupuncture
│
├── Holistic Wellness
│   ├── IV Therapy
│   ├── RMT (NEW)
│   └── Aesthetics (de-emphasized)
│
├── Shop (NEW - Coming Soon placeholder)
│
└── Contact Us
    ├── Book Appointment
    ├── Our Locations (plural - 3 locations)
    └── FAQs
```

### Header Layout Change
- **Current:** Logo inline with menu
- **New:** Logo moves to top section, menu goes underneath
- **Reason:** Create more room for navigation items

---

## 3. Service Additions & Changes

### 3.1 Psychotherapy Page Updates
Add the following services:
- **EMDR** (Eye Movement Desensitization Reprocessing)
- **Couples Therapy** (ensure prominent placement)

### 3.2 Holistic Wellness Updates
- Add IV Therapy info (reference: https://kmthealth.com/iv-therapy)
- Add RMT (Registered Massage Therapy)
- Keep aesthetics but de-emphasize (move lower in hierarchy)

### 3.3 New Naturopathy Page
**CRITICAL:** Use same format as Assessments page (Karen loved that structure)

Focus areas to include:
1. **Hormonal Health**
   - PCOS
   - Menopause
   - Endometriosis
   - Thyroid conditions

2. **Fertility and Reproductive Health**
   - Fertility support
   - Preconception care
   - Pregnancy support

3. **Stress Management and Emotional Well-being**
   - Adrenal health
   - Anxiety support
   - Mood balance

4. **Weight Management and Nutrition**
   - Metabolic health
   - Nutritional counseling
   - Sustainable weight management

5. **Digestive Health**
   - Gut health optimization
   - Food sensitivities
   - IBS support

6. **Immune System Support**
   - Immune optimization
   - Chronic illness support
   - Preventive care

7. **Skin and Aesthetics**
   - Natural skin health
   - Anti-aging support
   - Holistic beauty

8. **Acupuncture**
   - Traditional Chinese Medicine
   - Pain management
   - Stress relief

---

## 4. IV Therapy Repositioning

### CRITICAL DIRECTIVE
**Karen does NOT want to be a med spa.**
The site should reflect medical-grade wellness, not cosmetic procedures.

### Primary Focus (Evidence-Based) - Feature Prominently
These services should be the PRIMARY messaging:
| Service | Description |
|---------|-------------|
| Vitamin D supplementation | Essential nutrient therapy |
| Iron deficiency treatment | Medical treatment for anemia |
| Headaches/migraines | Therapeutic relief |
| Stress management | Wellness support |
| Sports recovery | Athletic performance |
| Hangover recovery | Rehydration therapy |
| Jet lag | Travel wellness |
| Marathon prep/recovery | Endurance support |

### De-emphasize (Move to Bottom as "Additional Services")
These services should be listed but NOT featured:
- PRP (Platelet-Rich Plasma)
- Microneedling
- Botox/Fillers
- Facials

---

## 5. SEO & Branding Guidelines

### Business Name Usage
| Context | Name to Use |
|---------|-------------|
| Legal documents | KMT Medical and Allied Health Group |
| Homepage | KMT Medical and Allied Health Group (full name) |
| Other pages | KMT Medical (shorter for SEO optimization) |

### Meta Tags to Update
- Remove "women's" from all meta descriptions
- Remove "women's" from all title tags
- Update keywords to reflect multidisciplinary focus
- Include all location names where appropriate

---

## 6. Content Updates Required

### Homepage (index.html)
- [ ] Remove "Women's Wellness" from hero heading
- [ ] Update hero description to be gender-neutral
- [ ] Update meta title and description
- [ ] Update services section to reflect new structure
- [ ] De-emphasize EmpowerHer (one program, not featured)
- [ ] Update Holistic Wellness card content
- [ ] Add Naturopathy to services
- [ ] Update footer with all 3 locations

### Assessments Page (assessments.html)
- [x] APPROVED - Keep current structure (template for other pages)
- [ ] Update footer with all 3 locations

### EmpowerHer Page (empowerher.html)
- [ ] Keep as-is but ensure it's positioned as one program
- [ ] Update footer with all 3 locations

### New Pages to Create
- [ ] naturopathy.html - Full page using Assessments template
- [ ] shop.html - Coming Soon placeholder
- [ ] psychotherapy.html - Enhanced with EMDR, Couples Therapy
- [ ] holistic.html - IV Therapy (repositioned), RMT, Aesthetics

---

## 7. Design Consistency

All new pages must include:
1. Consistent header with updated navigation
2. Hero section with appropriate badge
3. Value strip (3 key points)
4. Card-based service listings
5. FAQ section (where appropriate)
6. CTA section
7. Footer with all 3 locations

### Color Palette (Maintain)
- Primary: `--kmt-teal` (#2A7B9B)
- Accent: `--kmt-coral`
- Background: `--kmt-light`
- Text: `--text-primary`, `--text-secondary`

### Typography (Maintain)
- Headings: Playfair Display
- Body: Inter

---

## 8. Priority Order for Implementation

1. **High Priority**
   - Create Naturopathy page (client specifically requested)
   - Update homepage branding (critical repositioning)
   - Update navigation structure

2. **Medium Priority**
   - Update footer with all locations
   - Create Shop placeholder
   - Update Holistic Wellness content

3. **Lower Priority**
   - Create dedicated Psychotherapy page
   - Update header layout (logo/menu)
   - SEO meta tag updates

---

## 9. Reference Links

- Current IV Therapy page: https://kmthealth.com/iv-therapy
- Facebook: https://www.facebook.com/KMT.alliedhealth
- Instagram: https://www.instagram.com/KMT.health
- LinkedIn: https://www.linkedin.com/company/kmt-alliedhealth

---

## 10. Sign-off

**Client:** Karen M. Thornton
**Date:** 2026-01-12
**Status:** Requirements Approved
