# SEO Strategy & Documentation

> Business: NovaSpark Digital — Digital Marketing Agency, Hyderabad  
> Task: AI SEO Blog & Content Cluster Generator | FUTURE_PE_03

---

## 1. Business Overview

| Field | Details |
|-------|---------|
| Business Name | NovaSpark Digital (fictional) |
| Type | Digital Marketing Agency |
| Location | Hyderabad, Telangana, India |
| Target Customers | SMEs, startups, local businesses in Hyderabad |
| Primary Goal | Generate inbound leads via organic search |

---

## 2. Keyword Strategy

### Primary Keyword
| Keyword | Monthly Searches (est.) | Difficulty | Intent |
|---------|------------------------|------------|--------|
| digital marketing agency in Hyderabad | 2,400–4,400 | High | Transactional |

### Secondary Keywords
| Keyword | Monthly Searches (est.) | Difficulty | Intent |
|---------|------------------------|------------|--------|
| best digital marketing agency Hyderabad | 800–1,600 | High | Transactional |
| digital marketing services Hyderabad | 600–1,200 | Medium | Transactional |
| SEO agency Hyderabad | 400–800 | Medium | Transactional |
| social media marketing Hyderabad | 500–1,000 | Medium | Informational |

### Long-Tail / Cluster Keywords
| Keyword | Intent | Target Blog |
|---------|--------|------------|
| SEO services for small businesses in Hyderabad | Informational → Transactional | Blog 01 |
| Google Ads cost in Hyderabad | Informational | Blog 02 |
| social media marketing for businesses in Hyderabad | Informational | Blog 03 |
| why my website is not getting traffic | Problem-solving | Blog 04 |

---

## 3. Search Intent Mapping

Understanding why someone searches a keyword is as important as the keyword itself.

| Intent Type | What the User Wants | Content Type | CTA |
|------------|-------------------|--------------|-----|
| Informational | Learn / Understand | Educational blog | Soft — "Read more", "Download guide" |
| Transactional | Hire / Buy / Contact | Service page + blog | Direct — "Book now", "Get a quote" |
| Local | Find nearby | Local SEO page | "Call us", "Visit us", "Get directions" |
| Problem-solving | Fix a specific issue | Troubleshooting blog | "Get a free audit" |

**Our content cluster covers all four intent types**, ensuring we capture users at every stage of their decision-making journey.

---

## 4. Content Cluster Map

```
PILLAR BLOG
"Best Digital Marketing Agency in Hyderabad"
(Primary keyword: digital marketing agency in Hyderabad)
        |
        |── BLOG 01: SEO Services for Small Businesses in Hyderabad
        |       ↳ Links back to pillar
        |       ↳ Links to /services/seo
        |
        |── BLOG 02: How Much Does Google Ads Cost in Hyderabad?
        |       ↳ Links back to pillar
        |       ↳ Links to /services/google-ads
        |
        |── BLOG 03: Social Media Marketing for Businesses in Hyderabad
        |       ↳ Links back to pillar
        |       ↳ Links to /services/social-media
        |
        └── BLOG 04: Why Your Website Isn't Getting Traffic
                ↳ Links back to pillar
                ↳ Links to /services/seo
```

---

## 5. Internal Linking Plan

| From | To | Anchor Text | Purpose |
|------|-----|------------|---------|
| Blog 01 | Pillar Blog | "digital marketing agency in Hyderabad" | Pass authority to pillar |
| Blog 02 | Pillar Blog | "digital marketing agency in Hyderabad" | Pass authority to pillar |
| Blog 03 | Pillar Blog | "digital marketing agency in Hyderabad" | Pass authority to pillar |
| Blog 04 | Pillar Blog | "digital marketing agency in Hyderabad" | Pass authority to pillar |
| Blog 01 | /services/seo | "SEO packages for small businesses" | Convert reader to lead |
| Blog 02 | /services/google-ads | "Google Ads management packages" | Convert reader to lead |
| Blog 03 | /services/social-media | "social media marketing packages" | Convert reader to lead |
| Blog 04 | /services/seo | "SEO and website audit services" | Convert reader to lead |
| All blogs | /contact | Various CTAs | Drive contact form submissions |

**Why internal linking matters:** It distributes page authority throughout the site, helps Google understand your content structure, and keeps readers on the site longer — all of which improve rankings.

---

## 6. Local SEO Signals Used

Every blog in this cluster includes these local SEO elements:

- City name (Hyderabad) in H1 and multiple H2s
- Neighbourhood references: Hitech City, Gachibowli, Banjara Hills, Kukatpally, Ameerpet, Secunderabad, LB Nagar, Uppal
- "Serving areas in Hyderabad" section in pillar blog
- Google Maps embed suggestion in pillar
- Local pricing context (INR, Hyderabad market rates)
- References to local business ecosystem and culture

---

## 7. Prompt Engineering Decisions

### Why Use Bracketed Variables?
Every prompt is designed with `[variables]` so the same system can be deployed for any business — dental clinic, coaching institute, salon, SaaS — in any city. This makes the prompt system a scalable agency asset.

### Why Separate Prompts for Each Task?
Breaking the workflow into 4 distinct prompts (pillar, cluster, local adapter, linking planner) mirrors how professional SEO agencies actually work — each step has a specific goal and output format. This prevents the AI from trying to do everything at once and producing generic content.

### Why Informational Content First?
Most business websites only publish transactional content ("hire us", "our services"). This misses 70%+ of search traffic, which is informational. Our cluster includes problem-solving and educational blogs that attract top-of-funnel visitors and build trust before asking for the sale.

### Tone Strategy
- Pillar blog: professional + authoritative (builds trust for transactional queries)
- Cluster blogs: conversational + helpful (meets informational intent)
- Local adapter: adds warmth and familiarity (connects with Hyderabad audience)

---

## 8. How to Reuse This System for Any Client

1. Open `prompts/prompts.md`
2. Run **Prompt 04** first → get the full content cluster map for your client
3. Replace `[Business]` with client name and type
4. Replace `[City]` with client's location
5. Replace `[Primary keyword]` with the main search term for their industry
6. Run **Prompt 01** → pillar blog
7. Run **Prompt 02** for each cluster blog (4–5 times with different long-tail keywords)
8. Run **Prompt 03** on each blog → inject local SEO signals
9. Review, lightly edit, and publish

**Estimated time per client:** 1–2 hours to generate a full content pack  
**Agency value:** SEO content packages typically sell for ₹15,000–₹50,000/month

---

*Part of FUTURE_PE_03 — Future Interns Prompt Engineering Track*
