# KMT Medical Website - SEO Guidelines

## Business Name Strategy

| Context | Name to Use | Reason |
|---------|-------------|--------|
| Legal/Official | KMT Medical and Allied Health Group | Full legal name |
| Homepage H1/Title | KMT Medical and Allied Health Group | Brand authority |
| Other Page Titles | KMT Medical | Shorter, better for SEO |
| Footer | KMT Medical & Allied Health | Consistent branding |

---

## Target Keywords by Page

### Homepage (index.html)
**Primary Keywords:**
- Multidisciplinary health clinic Oakville
- Mental health services Oakville
- Psychotherapy Oakville
- Psychological assessments Oakville

**Secondary Keywords:**
- Naturopathy Oakville
- IV therapy Oakville
- Holistic wellness clinic
- Registered psychologist Oakville

**Long-tail Keywords:**
- ADHD assessment Oakville Ontario
- Couples therapy near me Oakville
- Naturopathic doctor Oakville
- Stress management clinic GTA

---

### Assessments Page (assessments.html)
**Primary Keywords:**
- Psychological assessment Oakville
- Neuropsychological testing Ontario
- ADHD assessment Oakville
- Psychoeducational evaluation

**Secondary Keywords:**
- Learning disability assessment
- Cognitive testing Oakville
- WSIB psychological assessment
- MVA psychological evaluation

---

### Naturopathy Page (naturopathy.html) - NEW
**Primary Keywords:**
- Naturopathic medicine Oakville
- Naturopathic doctor Oakville
- Holistic health clinic Oakville
- Natural hormone therapy

**Secondary Keywords:**
- PCOS naturopathic treatment
- Fertility naturopath Oakville
- Thyroid naturopathic care
- Digestive health naturopath

**Long-tail Keywords:**
- Naturopathic treatment for hormonal imbalance Oakville
- Natural fertility support clinic Ontario
- Menopause naturopathic care GTA
- Acupuncture for stress Oakville

---

### Psychotherapy Page (psychotherapy.html)
**Primary Keywords:**
- Psychotherapy Oakville
- Registered psychotherapist Oakville
- Counselling services Oakville
- EMDR therapy Ontario

**Secondary Keywords:**
- Couples therapy Oakville
- Family counselling Oakville
- Teen therapy Oakville
- Trauma therapy EMDR

**Long-tail Keywords:**
- EMDR therapist near me Oakville
- Couples counselling Oakville Ontario
- Anxiety therapist accepting new clients
- Depression counselling Oakville

---

### Holistic Wellness Page (holistic.html)
**Primary Keywords:**
- IV therapy Oakville
- Vitamin infusion therapy
- Registered massage therapy Oakville
- Wellness clinic Oakville

**Secondary Keywords:**
- Vitamin D IV therapy
- Iron infusion clinic
- Sports recovery IV
- RMT Oakville

**Long-tail Keywords:**
- IV vitamin therapy for energy Oakville
- Migraine IV treatment clinic
- Athletic recovery IV infusion
- Medical wellness clinic GTA

---

## Meta Tag Templates

### Title Tag Format
```
[Primary Keyword] | [Secondary Keyword] | KMT Medical
```
**Character limit:** 50-60 characters

### Meta Description Format
```
[Compelling benefit statement]. [Service details]. [Call to action]. Serving Oakville, Ajax & Maple.
```
**Character limit:** 150-160 characters

---

## Page-Specific Meta Tags

### Homepage
```html
<title>Multidisciplinary Health Clinic Oakville | Psychotherapy & Wellness | KMT Medical</title>
<meta name="description" content="KMT Medical offers psychotherapy, psychological assessments, naturopathy, and IV therapy in Oakville, Ajax & Maple. Book your consultation today. (905) 829-5686">
```

### Assessments
```html
<title>Psychological Assessments Oakville | ADHD & Neuropsychological Testing | KMT Medical</title>
<meta name="description" content="Expert psychological assessments including ADHD testing, neuropsychological evaluations, and psychoeducational assessments in Oakville. WSIB & insurance accepted.">
```

### Naturopathy (NEW)
```html
<title>Naturopathic Medicine Oakville | Hormone & Fertility Support | KMT Medical</title>
<meta name="description" content="Naturopathic doctors specializing in hormonal health, fertility, digestive issues, and stress management. Natural, evidence-based care in Oakville, Ajax & Maple.">
```

### Psychotherapy
```html
<title>Psychotherapy & EMDR Therapy Oakville | Couples & Individual Counselling | KMT Medical</title>
<meta name="description" content="Licensed psychotherapists offering EMDR, couples therapy, individual counselling, and family therapy in Oakville. Evening & weekend appointments available.">
```

### Holistic Wellness
```html
<title>IV Therapy & Wellness Services Oakville | Vitamin Infusions | KMT Medical</title>
<meta name="description" content="Medical-grade IV therapy for energy, recovery, and wellness. Vitamin D, iron infusions, migraine relief, and sports recovery. RMT services available.">
```

---

## Heading Structure (H1-H6)

Each page should have ONE H1 tag containing the primary keyword.

### Example Structure:
```
H1: Primary Keyword + Location (one per page)
  H2: Section headings (services, about, etc.)
    H3: Sub-section headings
      H4: Individual items if needed
```

### Homepage H1:
```html
<h1>Integrated Mental Health & Wellness Services in Oakville</h1>
```
*Note: Remove "Women's" from current H1*

### Naturopathy H1:
```html
<h1>Naturopathic Medicine & Holistic Health in Oakville</h1>
```

---

## Local SEO Requirements

### Location Pages/Sections
Include location-specific content for all 3 locations:
- Oakville (primary)
- Ajax
- Maple (Woodbridge area)

### Schema Markup (Recommended)
Add LocalBusiness schema for each location:
```json
{
  "@context": "https://schema.org",
  "@type": "MedicalBusiness",
  "name": "KMT Medical and Allied Health Group",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "1939 Ironoak Way, Unit A204",
    "addressLocality": "Oakville",
    "addressRegion": "ON",
    "postalCode": "L6H 3V8",
    "addressCountry": "CA"
  },
  "telephone": "+1-905-829-5686",
  "email": "reception@kmthealth.com"
}
```

### Google Business Profile
Ensure consistency across:
- Website NAP (Name, Address, Phone)
- Google Business Profile
- Social media profiles

---

## Content Guidelines for SEO

### Word Count Targets
| Page Type | Minimum Words |
|-----------|---------------|
| Homepage | 800-1200 |
| Service Pages | 1000-1500 |
| Blog Posts | 1500-2500 |

### Keyword Density
- Primary keyword: 1-2% of content
- Secondary keywords: 0.5-1% each
- Natural placement in:
  - H1 tag
  - First 100 words
  - H2 subheadings
  - Image alt text
  - Meta description

### Internal Linking Strategy
- Link between related services
- Use descriptive anchor text
- Link to Assessments page frequently (approved structure)
- Ensure all pages are 2-3 clicks from homepage

---

## Image SEO

### File Naming Convention
```
service-keyword-location.avif
Example: naturopathy-hormone-health-oakville.avif
```

### Alt Text Format
```
[Descriptive text] at KMT Medical [Location]
Example: "Naturopathic consultation for hormone health at KMT Medical Oakville"
```

### Image Optimization
- Use AVIF or WebP formats
- Compress images < 100KB where possible
- Include width/height attributes
- Lazy load below-fold images

---

## URL Structure

### Clean URL Format
```
https://kmthealth.com/[service-name]
```

### Examples
| Page | URL |
|------|-----|
| Homepage | / |
| Assessments | /assessments |
| Naturopathy | /naturopathy |
| Psychotherapy | /psychotherapy |
| Holistic Wellness | /holistic-wellness |
| Contact | /contact |

---

## Technical SEO Checklist

- [ ] Mobile-responsive design
- [ ] Page load speed < 3 seconds
- [ ] SSL certificate (HTTPS)
- [ ] XML sitemap
- [ ] robots.txt file
- [ ] Canonical URLs
- [ ] 404 error page
- [ ] Schema markup (LocalBusiness)
- [ ] Open Graph tags for social sharing
- [ ] Google Analytics tracking
- [ ] Google Search Console setup
