# 📝 Prompt 03 — Local SEO Adaptation Prompt

> **Type:** Reusable SEO Prompt
> **Purpose:** Adapt any existing blog or article for a new city / local market
> **Works With:** Claude, ChatGPT, Gemini

---

## Why Local SEO Adaptation Matters

A blog written generically ("best digital marketing agency") does not rank for local searches ("best digital marketing agency in Hyderabad").

Google's local search algorithm rewards:
- **Proximity** — content mentioning the city and local landmarks
- **Relevance** — service + city keyword combinations
- **Authority** — local citations, case studies, and references

This prompt lets you take **any existing blog** and inject local SEO signals properly — without making it feel forced or spammy.

---

## Use Case 1: Adapt an Existing Blog for a New City

### 🔧 Variables

| Variable | Example |
|---|---|
| `[ORIGINAL CITY]` | Bangalore |
| `[NEW CITY]` | Hyderabad |
| `[STATE]` | Telangana |
| `[BUSINESS TYPE]` | Digital Marketing Agency |
| `[LOCAL HUBS]` | Hitech City, Gachibowli, Kondapur, Banjara Hills, Madhapur |
| `[LOCAL INDUSTRIES]` | IT companies, pharma, real estate developers, restaurants, hospitals |

### 🤖 The Prompt

```
I have an existing SEO blog written for [ORIGINAL CITY]. I need you to adapt it for [NEW CITY], [STATE], India.

Here is the original blog:
[PASTE BLOG CONTENT HERE]

Your task:
1. Replace all mentions of [ORIGINAL CITY] with [NEW CITY]
2. Naturally insert references to these [NEW CITY] business hubs and areas: [LOCAL HUBS]
3. Reference local industries common in [NEW CITY]: [LOCAL INDUSTRIES]
4. Update the meta description and title tag to include [NEW CITY]
5. Update the H1 to include [NEW CITY]
6. In the introduction, add 1–2 sentences that make [NEW CITY] feel specific and relevant
7. In the FAQ section, update any city-specific questions to reference [NEW CITY]
8. Keep the word count roughly the same — do not pad or remove core content
9. Maintain the same tone and structure throughout
10. At the end, list every location keyword you naturally inserted (for SEO audit purposes)

Return the full adapted blog.
```

---

## Use Case 2: Write a New Blog Targeting Multiple City Variants

Use this to produce city-specific versions of the same article — efficient for agencies covering multiple markets.

### 🤖 The Prompt

```
You are writing an SEO supporting blog for a [BUSINESS TYPE] targeting multiple Indian cities.

Write ONE blog post about [TOPIC] that:
- Has a primary focus on [CITY 1]
- Naturally mentions [CITY 2] and [CITY 3] as comparison or alternative references
- Uses local business districts for each city where mentioned
- Targets the keyword: "[KEYWORD] in [CITY 1]"

The blog should feel locally relevant to [CITY 1] readers while also signaling multi-city expertise.

Tone: [TONE]
Word count: [WORD COUNT]
Include: Meta description, Title tag, H1–H3 structure, FAQ, CTA
```

---

## Use Case 3: Local SEO Audit Checklist Prompt

Run this on any finished blog before publishing to check local SEO quality.

### 🤖 The Prompt

```
Please perform a local SEO audit on the following blog post intended to rank for "[TARGET KEYWORD]" in [CITY], India.

[PASTE BLOG CONTENT HERE]

Audit for the following:

1. KEYWORD USAGE
   - Is the primary keyword in the H1?
   - Is it in the meta description?
   - How many times does it appear? (target: 4–6 times per 1000 words)
   - Does it appear in at least one H2?

2. LOCAL SIGNALS
   - Is the city mentioned enough? (minimum 5 times in 1000 words)
   - Are any local areas/business hubs mentioned?
   - Is there any local industry context?

3. CONTENT QUALITY
   - Does the introduction clearly state what the reader will learn?
   - Are there any generic/vague claims that could be made specific?
   - Is there a clear CTA?

4. STRUCTURE
   - Are H2 and H3 headings descriptive and keyword-inclusive?
   - Is there an FAQ section?
   - Are there internal link suggestions?

Return a scored report (pass/fail per item) and a list of specific improvements.
```

---

## 📍 Hyderabad-Specific Local SEO Reference Sheet

Use these naturally in content — don't force all of them:

### Business Hubs & Areas
- Hitech City (HITEC City) — IT & tech companies
- Gachibowli — startups, IT companies, financial district
- Kondapur — mid-size businesses, agencies
- Banjara Hills — premium retail, clinics, lifestyle brands
- Madhapur — co-working spaces, digital agencies
- Secunderabad — traditional businesses, manufacturing
- Jubilee Hills — media, entertainment, premium services
- Kukatpally — SMBs, education, retail

### Local Industries to Reference
- IT & Software companies (Hyderabad is India's 2nd largest IT hub)
- Pharma (bulk drug capital of India — Dr. Reddy's, Aurobindo)
- Real estate development
- Hospitals and healthcare chains (Apollo, Yashoda, Care)
- Restaurant & food delivery businesses
- Education & coaching institutes
- E-commerce and D2C brands

### City-Specific Phrases That Feel Local
- "businesses in HITEC City and Gachibowli"
- "Hyderabad's growing startup ecosystem"
- "IT companies along the ORR (Outer Ring Road)"
- "local SMBs in Kondapur and Kukatpally"

---

*Part of the FUTURE_PE_02 SEO Prompt Engineering System*
