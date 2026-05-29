# SEO Audit — mirellamanelli.com
**Date:** May 28, 2026

---

## What's Working Well
- Blog word count is strong (2,500–4,200 words per post)
- Internal linking is solid (15–35+ links per post)
- sitemap.xml and robots.txt are properly configured via Yoast
- FAQ sections appearing in some blog posts

---

## Critical Issues — STILL UNRESOLVED

### 1. Meta Descriptions — 0/10 Pages Fixed
Every page is missing a meta description: homepage, about, blog index, all blog posts, shop, podcast. Google writes its own snippets when none are provided, and they're almost never as good as yours.

### 2. Duplicate H1 Tags
"Free Hairstylist Education Starts Here" is the H1 on the homepage, about page, AND blog index. The podcast page has multiple H1s on the same page (SEO violation).

### 3. Schema Markup — Mostly Missing
- Homepage: none
- About: none
- Shop: none (critical — needs Product + Offer schema)
- Podcast: none (PodcastSeries schema would unlock rich results)
- Blog posts: 2 of 5 have partial Article schema — inconsistent

---

## Priority Fix List

| Priority | Fix | Est. Time |
|---|---|---|
| 1 | Write unique meta descriptions for every page (150–160 chars) | 2–3 hrs |
| 2 | Fix duplicate H1s on About, Blog Index, Podcast pages | 30 min |
| 3 | Add schema: Organization + Person on homepage/about | 2 hrs |
| 4 | Add Article + FAQPage schema to all blog posts | 2 hrs |
| 5 | Add Product + Offer schema to Shop | 1–2 hrs |
| 6 | Add PodcastSeries schema to Podcast page | 1 hr |
| 7 | Improve image alt text (currently ~15–20% coverage sitewide) | 3–4 hrs |

---

## Meta Descriptions (Ready to Paste into Yoast)

> Add these in WordPress: go to each page/post, scroll to the Yoast SEO panel, click **Edit snippet**, paste into the **Meta description** field.

**Homepage** *(144 chars)*
```
Free hairstylist education from award-winning educator Mirella Manelli. Learn hair color, business, and extensions from a 20+ year industry pro.
```

**About** *(141 chars)*
```
Meet Mirella Manelli, award-winning hairstylist, salon owner, and founder of Hair B&B University. 20+ years of expertise behind every lesson.
```

**Blog Index** *(147 chars)*
```
Explore Mirella Manelli's blog for expert tips on hair color, salon business, hairstylist burnout, and building a thriving career behind the chair.
```

**The Manelli Method: Highlight Technique** *(137 chars)*
```
Learn the no-tease foil highlight technique created by Mirella Manelli. Get softer roots, more dimension, and cleaner results every time.
```

**Bleach for Dark Hair: Why Most Guides Ignore Hair Integrity** *(145 chars)*
```
Most bleach guides focus only on lift, but hair integrity matters more. Mirella Manelli explains what to look for when bleaching dark hair safely.
```

**The Best Bleach for Box-Dyed Dark Hair** *(145 chars)*
```
Box-dyed dark hair requires a different bleach strategy. Mirella Manelli breaks down the best bleach options for safe, effective color correction.
```

**The Manelli Scale Explained** *(147 chars)*
```
The Manelli Scale is a 100-point system for rating professional bleach. Discover how Mirella scores every bleach so you can choose with confidence.
```

**The Truth About Owning a Hair Salon** *(149 chars)*
```
What does 8 years as a salon owner actually teach you? Mirella Manelli shares the unfiltered truth about running a hair salon and staying profitable.
```

**Hairstylist Burnout Is Real: 10 Salon Systems** *(145 chars)*
```
Hairstylist burnout is real, and these 10 salon systems helped Mirella Manelli save her business and her sanity. Build a salon that works for you.
```

**Shop** *(139 chars)*
```
Shop Mirella Manelli's professional hair education resources, including online courses, highlighting guides, and hairstylist business tools.
```

**Podcast** *(143 chars)*
```
Listen to the Mirella Manelli podcast, with 500+ episodes on hair color, salon business, hairstylist education, and building a career you love.
```

---

## Page-by-Page Audit Summary

| Page | Meta Title | Meta Description | Unique H1 | Schema | Image Alt | Internal Links |
|---|---|---|---|---|---|---|
| Homepage | OK (54 chars) | MISSING | DUPLICATE | None | ~15% | 25+ |
| About | MISSING | MISSING | DUPLICATE | None | ~15% | 12+ |
| Blog Index | OK (20 chars) | MISSING | DUPLICATE | None | ~15% | 30+ |
| Manelli Method post | Incomplete (38 chars) | MISSING | Incomplete (ends with colon) | Basic Article | ~40% | 35+ |
| Bleach for Dark Hair post | OK (84 chars) | MISSING | OK | None | Minimal | 20+ |
| Best Bleach Box-Dyed post | OK (61 chars) | MISSING | OK | None | Minimal | 25–30 |
| Manelli Scale post | OK (47 chars) | MISSING | OK | Partial | ~40% | 25+ |
| Hairstylist Burnout post | OK (108 chars) | MISSING | OK | Partial | ~40% | 15+ |
| Shop | OK (21 chars) | MISSING | Too generic ("Shop") | None | ~15% | — |
| Podcast | DUPLICATE of homepage | MISSING | MULTIPLE H1s | None | ~15% | — |

---

## Technical
- robots.txt: Properly configured, allows all crawlers
- sitemap.xml: Yoast sitemap index with 5 subsitemaps (post, page, tags, author, elementskit)
- Core Web Vitals / PageSpeed: Not tested — run Google PageSpeed Insights separately

---

## E-E-A-T Signals to Weave Into Content
- 20+ years in professional beauty industry
- Owner of Rebel Femme Salon, Mission Viejo CA
- Founder of Hair B&B University
- Founder of Manelli Hair Extensions
- Modern Salon Top 100 (2019)
- 5x Behind the Chair One Shot nominee/winner
- Kenra Professional Artistic Ambassador
- Lead stylist, Bravo TV's Vanderpump Rules (Katie Maloney's wedding)
- 430K+ YouTube subscribers, 500+ podcast episodes

---

## Next Steps
1. Paste all meta descriptions above into Yoast (30–60 min task)
2. Fix duplicate H1s on About, Blog Index, Podcast
3. Add schema markup (Organization, Person, Article, FAQPage, Product, PodcastSeries)
4. Audit image alt text across all pages
