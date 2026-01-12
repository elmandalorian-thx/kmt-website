# KMT Medical Website - Site Structure

## Navigation Map

```
┌─────────────────────────────────────────────────────────────────────┐
│                           HEADER                                     │
│  ┌─────────────────────────────────────────────────────────────────┐│
│  │                    KMT LOGO (Top Section)                       ││
│  │         KMT Medical and Allied Health Group                     ││
│  └─────────────────────────────────────────────────────────────────┘│
│  ┌─────────────────────────────────────────────────────────────────┐│
│  │ Psychotherapy │ Assessments │ Naturopathy │ Holistic │ Shop │ Contact │ [Book] ││
│  └─────────────────────────────────────────────────────────────────┘│
└─────────────────────────────────────────────────────────────────────┘
```

## Page Hierarchy

### Current Pages (Existing)
```
/
├── index.html              ← Homepage (needs updates)
├── assessments.html        ← APPROVED TEMPLATE
└── empowerher.html         ← Keep as one program
```

### New Pages (To Create)
```
/
├── naturopathy.html        ← HIGH PRIORITY - New service page
├── holistic.html           ← Holistic Wellness services
├── psychotherapy.html      ← Enhanced psychotherapy page
├── shop.html               ← Coming Soon placeholder
└── contact.html            ← Contact & Locations
```

## Detailed Navigation Structure

### 1. Psychotherapy (psychotherapy.html)
```
Psychotherapy ▼
├── Individual Therapy
├── Couples Therapy      ← NEW
├── Family Therapy
├── Teen Counseling
└── EMDR                 ← NEW
```

### 2. Assessments (assessments.html) - APPROVED
```
Assessments ▼
├── All Assessments
├── Neuropsychological
├── Psychoeducational
├── Psychodiagnostic
└── Rehabilitation
```

### 3. Naturopathy (naturopathy.html) - NEW PAGE
```
Naturopathy ▼
├── Hormonal Health
├── Fertility & Reproductive Health
├── Stress Management
├── Weight Management & Nutrition
├── Digestive Health
├── Immune System Support
├── Skin & Aesthetics
└── Acupuncture
```

### 4. Holistic Wellness (holistic.html)
```
Holistic Wellness ▼
├── IV Therapy           ← PRIMARY FOCUS
├── RMT                  ← NEW
└── Additional Services  ← Aesthetics (de-emphasized)
```

### 5. Shop (shop.html) - NEW
```
Shop → Coming Soon placeholder page
```

### 6. Contact Us (contact.html)
```
Contact Us ▼
├── Book Appointment
├── Our Locations (3)
└── FAQs
```

## Footer Structure

```
┌─────────────────────────────────────────────────────────────────────┐
│                            FOOTER                                    │
├─────────────────┬─────────────────┬─────────────────┬───────────────┤
│     BRAND       │    SERVICES     │   LOCATIONS     │   CONTACT     │
├─────────────────┼─────────────────┼─────────────────┼───────────────┤
│ KMT Medical     │ Psychotherapy   │ OAKVILLE (Main) │ (905)829-5686 │
│                 │ Assessments     │ 1939 Ironoak Wy │ reception@    │
│ [Description]   │ Naturopathy     │ Unit A204       │ kmthealth.com │
│                 │ Holistic        │ L6H 3V8         │               │
│ [Social Icons]  │ Wellness        │                 │               │
│  f  ig  in      │ Shop            │ AJAX            │               │
│                 │                 │ [Address TBD]   │               │
│                 │                 │                 │               │
│                 │                 │ MAPLE           │               │
│                 │                 │ [Address TBD]   │               │
├─────────────────┴─────────────────┴─────────────────┴───────────────┤
│ © 2025 KMT Medical & Allied Health. All rights reserved.            │
│ Privacy Policy | Terms of Service                                    │
└─────────────────────────────────────────────────────────────────────┘
```

## Page Template Structure

Based on the APPROVED Assessments page, all new pages should follow this structure:

```
┌─────────────────────────────────────────┐
│              HEADER/NAV                 │
├─────────────────────────────────────────┤
│                                         │
│              HERO SECTION               │
│         [Badge] [Title] [CTA]           │
│                                         │
├─────────────────────────────────────────┤
│                                         │
│            VALUE STRIP                  │
│      [Icon+Text] [Icon+Text] [Icon+Text]│
│                                         │
├─────────────────────────────────────────┤
│                                         │
│          SERVICES SECTION               │
│    [Featured Card - Full Width]         │
│    [Card] [Card]                        │
│    [Card] [Card]                        │
│                                         │
├─────────────────────────────────────────┤
│                                         │
│         COMPARISON/GUIDE                │
│           (if applicable)               │
│                                         │
├─────────────────────────────────────────┤
│                                         │
│           FAQ SECTION                   │
│         [Accordion Items]               │
│                                         │
├─────────────────────────────────────────┤
│                                         │
│           CTA SECTION                   │
│        [Book Now] [Phone]               │
│                                         │
├─────────────────────────────────────────┤
│              FOOTER                     │
│     [3 Locations] [Links] [Social]      │
└─────────────────────────────────────────┘
```

## File Naming Convention

| Page | Filename | Status |
|------|----------|--------|
| Homepage | `index.html` | Existing - Update |
| Assessments | `assessments.html` | Existing - Approved |
| EmpowerHer | `empowerher.html` | Existing - Keep |
| Naturopathy | `naturopathy.html` | **Create** |
| Holistic Wellness | `holistic.html` | **Create** |
| Psychotherapy | `psychotherapy.html` | **Create** |
| Shop | `shop.html` | **Create** |
| Contact | `contact.html` | **Create** |

## CSS Structure

```
/css/
└── styles.css          ← Main stylesheet (all pages)
```

All pages use the same stylesheet with consistent:
- Color variables (--kmt-teal, --kmt-coral, etc.)
- Typography (Playfair Display, Inter)
- Component classes (.card, .btn, .hero, etc.)
- Responsive breakpoints
