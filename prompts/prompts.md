# Structured SEO Prompts — Digital Marketing Agency Content Cluster

> All prompts use `[bracketed variables]` — swap values to reuse for any business niche.

---

## Prompt 01 — Pillar Blog Generator

**Purpose:** Generate a complete long-form SEO pillar article targeting a primary keyword.

```
You are an expert SEO content writer working for a digital marketing agency.

Write a long-form SEO blog post for [Business: NovaSpark Digital, a digital marketing agency in Hyderabad].

Primary keyword: [digital marketing agency in Hyderabad]
Secondary keywords: [best digital marketing agency Hyderabad, digital marketing services Hyderabad, SEO agency Hyderabad]

Blog title: "Best Digital Marketing Agency in Hyderabad – Services, Pricing & What to Expect"

Requirements:
- Length: 1200–1500 words
- Structure: H1 (title) → H2 sections → H3 sub-sections
- Include: introduction, services overview, why choose us, pricing guide, FAQs, conclusion with CTA
- Tone: professional but approachable, helpful first, sales second
- Naturally include the primary keyword 4–6 times
- Add 3 internal linking suggestions [marked as: INTERNAL LINK: anchor text → target page]
- End with a strong CTA to contact the agency
- Do NOT use keyword stuffing. Write for humans first, search engines second.
```

**Variables to swap:**
- `[Business]` → any business name and type
- `[Primary keyword]` → main search term you want to rank for
- `[Secondary keywords]` → 2–4 related terms
- Blog title → adjust based on business

---

## Prompt 02 — Cluster/Supporting Blog Generator

**Purpose:** Generate a shorter supporting blog that targets a specific long-tail keyword and links back to the pillar.

```
You are an SEO content writer creating a supporting blog for a content cluster.

Business: [NovaSpark Digital — digital marketing agency in Hyderabad]
Pillar blog topic: [Best Digital Marketing Agency in Hyderabad]

Write a supporting blog post for this long-tail keyword: [SEO services for small businesses in Hyderabad]

Requirements:
- Length: 600–800 words
- Structure: H1 → H2 sections → short H3s where needed
- Tone: helpful, informative, problem-solving
- Include the long-tail keyword naturally 3–4 times
- Add 1 internal link back to the pillar blog [marked as: INTERNAL LINK → pillar blog]
- Add 1 internal link to a relevant service page [marked as: INTERNAL LINK → service page]
- End with a soft CTA (e.g., "Book a free consultation")
- Focus on search intent: [informational / transactional] — explain the topic, then pitch the service
```

**Variables to swap:**
- `[Long-tail keyword]` → specific topic for each cluster blog
- `[Search intent]` → informational (explain), transactional (sell), navigational (find)
- Adjust length for depth needed

---

## Prompt 03 — Local SEO Adapter

**Purpose:** Take any existing blog and adapt it for local SEO by adding city, location, and regional signals.

```
Here is an existing blog post:
[Paste blog content here]

Adapt this blog for local SEO targeting [City: Hyderabad, State: Telangana, India].

Make these specific changes:
1. Add the city name naturally in the H1 and at least 2 H2 headings
2. Include one paragraph about the local business landscape in [Hyderabad] and why [digital marketing] matters there
3. Add area/neighbourhood references where relevant (e.g., Hitech City, Banjara Hills, Gachibowli)
4. Include a "Serving areas in Hyderabad" section listing 6–8 localities
5. Add a Google Maps embed suggestion: [marked as: EMBED: Google Maps for business location]
6. Keep the original content structure — only add local signals, do not rewrite the whole article

Output the full adapted blog.
```

**Variables to swap:**
- `[City]` → any city (Bangalore, Mumbai, Chennai, Delhi, Pune)
- `[State]` → corresponding state
- Local area references → update to match the city
- `[Service]` → the business service type

---

## Prompt 04 — Internal Linking & SEO Structure Planner

**Purpose:** Generate an internal linking plan and content cluster map for an entire website.

```
You are an SEO strategist building a content cluster for [Business: NovaSpark Digital — digital marketing agency in Hyderabad].

Primary pillar topic: [Digital Marketing Agency in Hyderabad]

Based on this pillar, generate:

1. A content cluster map with:
   - 1 pillar blog (main topic)
   - 4–5 supporting blogs (long-tail topics)
   - For each blog: target keyword, search intent, suggested title, word count

2. An internal linking plan showing:
   - Which supporting blogs link to the pillar
   - Which supporting blogs link to each other
   - Which pages on the website each blog should link to (services, contact, about)

3. A keyword intent table:
   - Column 1: Keyword
   - Column 2: Search Intent (informational/transactional/local)
   - Column 3: Target Blog
   - Column 4: CTA Type (contact form / free audit / call now)

Format as clearly structured markdown tables and lists.
```

**Variables to swap:**
- `[Business]` → any business
- `[Primary pillar topic]` → the main keyword/topic you want to dominate
- Adjust CTA types based on business model

---

## How to Use These Prompts

1. Copy the prompt block
2. Replace all `[bracketed]` values with your client's details
3. Run Prompt 04 first → get your full content cluster map
4. Run Prompt 01 → generate the pillar blog
5. Run Prompt 02 for each supporting blog (change the long-tail keyword each time)
6. Run Prompt 03 on each blog → add local SEO signals
7. Document all outputs in your GitHub repo

**Time estimate:** Full content pack for one business = ~45–60 minutes using AI.

---

*Part of FUTURE_PE_03 — Future Interns Prompt Engineering Track*
