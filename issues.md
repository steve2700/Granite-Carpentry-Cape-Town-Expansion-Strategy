# Technical SEO Report: Granite Carpentry Website Indexing Issues

**Date:** November 6, 2025  
**Website:** granitecarpentry.co.za  
**Critical Issues:** 12 pages wasting crawl budget

---

## 🚨 EXECUTIVE SUMMARY

- **4 Soft 404 errors** - Thin content perceived as empty pages
- **2 Hard 404 errors** - Pages not found
- **1 Redirect error** - Broken redirect chain
- **5 Crawled not indexed** - Low quality content rejected by Google

**Impact:** Wasting crawl budget, zero SEO value, ranking potential lost

---

## 1️⃣ SOFT 404 ERRORS (4 Pages)

### Affected URLs:
1. `/blog/granite-vs-quartz-kitchen-countertops`
2. `/blog/kitchen-renovation-trends-2025-johannesburg`
3. `/blog/built-in-cupboard-design-ideas`
4. `/blog/drywall-installation-professional-tips`

### Problem:
Google sees these as empty/thin content despite 200 status code

### Fix Required:

**Expand each to 1,800-2,500 words minimum**

#### granite-vs-quartz-kitchen-countertops
**Target keywords:** granite vs quartz johannesburg, granite countertops pros cons, quartz vs granite cost south africa, best countertop material kitchen
**Add:**
- Detailed 15-point comparison table
- SA pricing (granite R1,800-4,500/m² vs quartz R2,200-5,000/m²)
- Climate considerations Gauteng
- 10+ FAQs with schema
- 8-10 images
- **Internal links:** Granite surfaces page, kitchen renovation, worktops service, bathroom vanities, contact (5+ links)

#### kitchen-renovation-trends-2025-johannesburg
**Target keywords:** kitchen renovation trends 2025, johannesburg kitchen design, modern kitchen ideas south africa, kitchen remodel gauteng
**Add:**
- 12-15 specific trends with detailed explanations
- Budget breakdowns (realistic SA pricing)
- Sandton/Fourways/Randburg specific examples
- Client testimonials with photos
- **Internal links:** Custom cabinets, granite countertops, kitchen package, service areas, gallery, contact (6+ links)

#### built-in-cupboard-design-ideas
**Target keywords:** built in cupboard ideas, bedroom cupboard designs south africa, custom wardrobe johannesburg, fitted cupboards gauteng
**Add:**
- 15-20 design ideas with descriptions
- Room-by-room breakdown
- Material pricing (melamine R4,500, solid wood R8,500+)
- Space optimization for SA homes
- Downloadable planning worksheet
- **Internal links:** Custom wardrobe, cabinet construction, bedroom content, pricing, gallery, consultation (6+ links)

#### drywall-installation-professional-tips
**Target keywords:** drywall installation tips, how to install drywall, drywall repair johannesburg, gypsum ceiling installation
**Add:**
- Step-by-step guide with 20+ images
- Tools required (SA availability/pricing)
- DIY vs professional comparison
- Safety and building codes (Johannesburg)
- 12+ FAQs
- Downloadable installation checklist
- **Internal links:** Drywall installation service, drywall repair, ceiling installation, renovations, quote (5+ links)

---

## 2️⃣ HARD 404 ERRORS (2 Pages)

### `/search?q={search_term_string}`
**Fix:**
```
Add to robots.txt:
Disallow: /search?*
Disallow: /*?q=*

Add noindex meta:
<meta name="robots" content="noindex, follow">
```

### `/areas/bedfordview`
**Fix Option A (Recommended):** Create proper page
- 1,500+ words
- Target: carpenter bedfordview, granite countertops bedfordview, kitchen renovation bedfordview
- Include local suburbs, pricing, testimonials, project photos
- **Internal links:** All service pages, Johannesburg areas, contact (8-10 links)

**Fix Option B:** 301 redirect to `/areas/johannesburg-east`

---

## 3️⃣ REDIRECT ERROR (1 Page)

### `/blog/built-in-cupboards-design-ideas-2025/`

**Fix:**
```
Implement clean 301 redirect:
/built-in-cupboards-design-ideas-2025/ → /built-in-cupboard-design-ideas

- No redirect chains
- Update all internal links to final destination
- Remove from sitemap
- Update canonical tags
```

---

## 4️⃣ CRAWLED NOT INDEXED (5 Pages) - HIGHEST PRIORITY

### 1. `/ceiling-repairs-pretoria`

**Expand to 2,000+ words**

**Target keywords:** ceiling repairs pretoria, gypsum ceiling repair pretoria, ceiling installation pretoria, water damaged ceiling repair, professional ceiling contractors pretoria

**Required content:**
- Common ceiling problems in Pretoria (water damage, sagging, cracks) - 300 words
- Service list with pricing (minor repairs R350-800, water damage R1,200-4,500, full replacement R95-180/m²) - 400 words
- 20+ Pretoria suburbs served (Centurion, Menlyn, Waterkloof, Brooklyn, Hatfield, etc.) - 150 words
- Repair process breakdown - 250 words
- Emergency services availability - 150 words
- 15+ FAQs with schema - 300 words
- 20+ before/after images
- **Internal links:** Main services, drywall installation, water damage, painting, maintenance, gallery, contact, emergency services (10+ links)
- LocalBusiness schema with Pretoria address
- Mention "Pretoria" 25-30 times naturally

---

### 2. `/blog/complete-guide-outdoor-decking-south-africa`

**Expand to 2,500+ words**

**Target keywords:** outdoor decking south africa, deck building johannesburg, timber decking prices south africa, composite decking south africa, best wood for decks south africa

**Required content:**
- Best materials for SA climate (Balau R850-1,200/m², Pine R450-650/m², Composite R950-1,500/m²) - 500 words
- Deck design ideas (pool decks, braai areas, entertainment) - 400 words
- Construction process with timeline - 350 words
- Maintenance for SA climate (harsh sun, termites, rain) - 400 words
- Gauteng building regulations - 200 words
- Cost breakdown (small 12m² R10-18k, medium 24m² R20-35k, large 40m² R35-65k) - 300 words
- DIY vs professional - 250 words
- 20+ FAQs with schema - 400 words
- 25-30 images, infographics
- Downloadable planning checklist PDF
- **Internal links:** Deck construction, deck repair, fencing, outdoor carpentry, painting, gallery, service areas, quotes, testimonials (12+ links)

---

### 3. `/services/carpentry-training`

**RECOMMENDED: DELETE THIS PAGE**

If not a core service:
```
- Remove page completely
- 301 redirect to /services
- Remove from sitemap
- Update all internal links
- Add to robots.txt: Disallow: /services/carpentry-training
```

**OR expand to 2,000+ words if you offer training:**
- Training programs with curriculum - 400 words
- Certification details - 200 words
- Pricing and schedule - 300 words
- Instructor credentials - 200 words
- Success stories - 200 words
- 10+ FAQs - 300 words

---

### 4. `/areas/krugersdorp`

**Expand to 1,800+ words**

**Target keywords:** carpenter krugersdorp, granite countertops krugersdorp, kitchen renovation krugersdorp, plumber krugersdorp, home renovation west rand

**Required content:**
- All services with pricing (carpentry, granite, plumbing) - 500 words
- 15+ Krugersdorp suburbs (Central, Monument, Mindalore, Silverfields, Kenmare, Noordheuwel, Wilro Park, etc.) - 200 words
- Why locals trust us - 300 words
- Popular local projects with case studies - 300 words
- 15+ location-specific FAQs - 400 words
- 15-20 local project images
- Mention "Krugersdorp" 30-40 times, "West Rand" 5-8 times
- Reference local landmarks (Walter Sisulu Garden, Krugersdorp Game Reserve)
- Google Map embedded
- **Internal links:** All service pages, other area pages (Roodepoort, Randfontein), blog posts, gallery, testimonials, contact (10+ links)
- LocalBusiness schema with Krugersdorp service area

---

### 5. `/areas/nigel`

**Expand to 1,800+ words**

**Target keywords:** carpenter nigel, granite countertops nigel, kitchen renovation nigel, plumber nigel east rand, home improvement nigel

**Required content:**
- All services with pricing - 500 words
- Nigel + surrounding areas (Nigel Central, Estates, Duduza, Heidelberg, Springs) - 200 words
- Nigel's unique renovation needs (older homes, mining area challenges, water quality) - 300 words
- Service commitment to East Rand clients - 250 words
- Recent local projects - 300 words
- 15+ FAQs - 400 words
- 15-20 local images
- Mention "Nigel" 30-40 times, "East Rand" 8-10 times
- Google Map with service radius
- **Internal links:** All services, area pages, blog, gallery, testimonials, contact (10+ links)
- LocalBusiness schema with Nigel service area

---

## 🎯 UNIVERSAL FIXES FOR ALL PAGES

### Content Quality Checklist:
- ✅ Minimum 1,800-2,500 words per page
- ✅ Proper heading hierarchy (H1, H2, H3)
- ✅ 15-30 high-quality images with ALT text
- ✅ 10-20 internal links per page
- ✅ 10+ FAQs with FAQ schema
- ✅ Local keywords mentioned 25-40 times naturally
- ✅ Specific pricing with rand amounts
- ✅ Before/after photos
- ✅ Customer testimonials

### Technical SEO:
- ✅ Article/LocalBusiness schema markup
- ✅ FAQ schema for all FAQ sections
- ✅ Service schema where applicable
- ✅ Meta description (155 chars)
- ✅ Title tag (60 chars)
- ✅ Image compression (WebP, <200KB)
- ✅ Mobile responsive
- ✅ Page speed <3 seconds
- ✅ Breadcrumb navigation
- ✅ Social sharing buttons

### E-E-A-T Signals:
- ✅ Author credentials: "Written by [Name], Licensed Carpenter with 15+ years in Johannesburg"
- ✅ Project portfolio images
- ✅ Client testimonials specific to topic
- ✅ GMB review links
- ✅ Certification badges
- ✅ Years established + projects completed
- ✅ Industry standard references

---

## 📊 KEYWORD STRATEGY

### High-Authority Keywords to Target:

**Local Service Keywords:**
- [service] + johannesburg/pretoria/sandton/fourways
- [service] + near me
- [service] + gauteng
- best [service] + area name
- affordable [service] + area name

**Money Keywords:**
- [service] + cost/price/pricing
- [service] + installation
- [service] + repair
- how much does [service] cost in south africa

**Long-tail Keywords:**
- granite vs quartz kitchen countertops johannesburg
- best wood for outdoor decking south africa
- ceiling repair cost pretoria
- custom kitchen cabinets prices johannesburg
- built in wardrobe ideas for small bedrooms

---

## 🔗 INTERNAL LINKING STRATEGY

### Every page must link to:
1. Homepage
2. Main services page
3. Related service pages (3-5)
4. Area pages (2-3)
5. Blog posts (2-3 related)
6. Gallery/portfolio
7. Testimonials
8. Contact/quote page
9. FAQ page (if separate)
10. About page

### Link from other pages:
- Homepage → All key pages
- Service pages → Related blogs and areas
- Area pages → All services and related areas
- Blog posts → Services, areas, other blogs

---

## 🚀 RANKING IMPROVEMENT TACTICS

### On-Page SEO:
1. **Title tags:** Include location + service + year
   - Example: "Granite Countertops Johannesburg | Expert Installation 2025"

2. **Meta descriptions:** Include CTA + pricing + location
   - Example: "Premium granite countertops in Johannesburg from R1,800/m². Free quotes. 100+ projects completed. Call today!"

3. **H1 tags:** Primary keyword + location
   - Example: "Professional Ceiling Repairs in Pretoria | Expert Services"

4. **URL structure:** Keep short, keyword-rich
   - Good: `/granite-countertops-johannesburg`
   - Bad: `/services/stone-work/granite-and-marble-installation-page`

### Content Optimization:
- First 100 words must contain primary keyword + location
- Use variations naturally throughout (granite countertops, granite worktops, granite surfaces)
- Include specific suburbs/areas 15-20 times
- Add pricing in rand (builds local relevance)
- Include local landmarks and references
- Answer "People Also Ask" questions from Google

### Technical Optimization:
- Compress all images to <200KB
- Use WebP format
- Add lazy loading for images
- Minify CSS/JS
- Enable browser caching
- Use CDN if possible
- Mobile-first design
- Core Web Vitals optimization

### Authority Building:
- Get backlinks from local directories
- Listed on HelloPeter, Snupit, Cylex
- GMB posts 2-3x weekly
- Facebook business page active
- Instagram with local hashtags
- Customer reviews (ask after every job)
- Case studies with before/after

---

## ⏰ IMPLEMENTATION PRIORITY

### Week 1 (URGENT):
1. Fix all 404 errors and redirects
2. Expand "Crawled not indexed" pages (ceiling-repairs-pretoria, areas/krugersdorp, areas/nigel)
3. Add robots.txt rules for search pages

### Week 2:
4. Expand Soft 404 blog posts (granite-vs-quartz, kitchen-trends, built-in-cupboards, drywall-tips)
5. Add comprehensive internal linking
6. Implement schema markup on all pages

### Week 3:
7. Optimize all images (compress, ALT text, WebP)
8. Create/update area pages (Bedfordview)
9. Add FAQ sections with schema

### Week 4:
10. Request Google re-indexing via Search Console
11. Submit updated sitemap
12. Monitor rankings and adjust

---

## 📈 SUCCESS METRICS

Track weekly:
- Pages indexed (target: 100% of quality pages)
- Crawl errors (target: 0)
- Average position for target keywords
- Organic traffic growth
- Quote requests from organic search
- GMB views and actions

---

## ✅ VALIDATION CHECKLIST

After fixes, validate each page:
- [ ] 1,800+ words of unique content
- [ ] 10+ internal links added
- [ ] 10+ FAQs with schema
- [ ] 15+ images with ALT text
- [ ] Location mentioned 25+ times
- [ ] Pricing in rand included
- [ ] Mobile responsive
- [ ] Page speed <3 seconds
- [ ] Schema markup implemented
- [ ] Meta title/description optimized
- [ ] Submitted for re-indexing in Search Console

---

**Next Steps:** Prioritize Week 1 tasks immediately. These fixes will recover crawl budget and improve indexing within 2-4 weeks.
