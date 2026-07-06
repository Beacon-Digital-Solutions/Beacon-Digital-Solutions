# Thrive — Zero-Cost Marketing & Rollout Strategy

App Store link (both platforms): **https://apps.apple.com/app/id6779286706**
Everything below costs $0 except your time. Ordered by expected return.

---

## 0. Positioning (the sentence everything else repeats)

> **Thrive is the private budgeting app for Mac and iPhone — every dollar gets a job,
> your data never leaves your own iCloud, and giving comes first.**

Three wedges, in priority order:
1. **Privacy** — no bank linking, no servers, no account, no tracking. This is the
   angle for Hacker News, MacRumors, r/privacy, and Apple-press coverage.
2. **Mac-native zero-based budgeting** — YNAB is web-first, Mint is dead, EveryDollar
   has no real Mac app. "Zero-based budgeting on Mac" is an underserved search.
3. **Christian stewardship** — Giving/Tithe first-class, grace-based reviews. A
   passionate, underserved niche with dense free channels (churches, podcasts, FB groups).

Lead with #1 or #2 in general channels; lead with #3 only in faith channels. Never mix
wedges in one pitch — pick the one the audience cares about.

---

## 1. ASO — App Store Optimization (highest ROI, do first)

The App Store IS the search engine that matters most for app downloads.

- **Name (30 chars):** `Thrive: Budget Tool` — consider `Thrive: Private Budget` or
  `Thrive — Budget & Steward` in a future version; test via ASC product page optimization.
- **Subtitle (30 chars):** use every character on keywords the name misses.
  Recommended: `Private Zero-Based Budgeting`
- **Keyword field (100 chars, no spaces after commas, don't repeat name/subtitle words):**
  `christian,stewardship,tithe,envelope,YNAB,mint,dave,ramsey,retirement,529,privacy,cash,plan`
- **Screenshots:** first two decide the download. Caption them with benefits, not
  features: "Every dollar gets a job" / "Your data never leaves your iCloud" /
  "Plan retirement, college, and payoff". Reuse the website `*_Private.png` set.
- **The "Data Not Collected" screenshot (do this one):** dedicate one App Store
  screenshot frame to the privacy label itself — a shot of Thrive's own App Store
  privacy section reading **"Data Not Collected"**, captioned *"Go ahead — check
  the label."* Competitor labels list "Data Used to Track You / Data Linked to
  You"; ours is Apple-verified proof of the pitch. Same asset works as the
  strongest social/Reddit image.
- **In-app review prompt:** already implemented (`askForReviewOnMilestone`). Ratings
  are the single biggest ranking factor — verify it fires after a genuinely happy
  moment (e.g. completing a monthly review), never after an import error.
- **Apple Small Business Program:** enroll (free, developer.apple.com) → Apple's
  commission drops 30% → **15%** on the $8/mo subscription. This is real money.
- **Promo codes:** ASC gives ~100 free codes per version. Budget them: 30 for
  podcast/blog reviewers, 20 for church pilot families, keep the rest.
- **Pitch Apple editorial:** App Store Connect → "Promote Your App" form. Angle:
  privacy-first finance + universal Mac/iPhone + faith niche. Long shot, costs 20 min.

## 2. SEO (implemented on the site — maintain it)

Done in this pass: canonical + OG/Twitter tags, `SoftwareApplication` + `FAQPage`
JSON-LD on thrive.html, sitemap.xml, robots.txt, honest copy (no household-sharing
promise, 7-day trial).

Remaining one-time setup (free, ~30 min):
1. **Google Search Console** — verify domain, submit sitemap.xml.
2. **Bing Webmaster Tools** — same (also feeds DuckDuckGo/ChatGPT browsing).
3. After the app is live: check `https://apps.apple.com/app/id6779286706` renders
   correctly and add the smart App Banner meta tag to thrive.html:
   `<meta name="apple-itunes-app" content="app-id=6779286706">`

**Content engine (the compounding asset): 1 blog post/week, 500–1200 words.**
Target long-tail searches with buyer intent. Editorial calendar, in order:

| # | Title (target query) |
|---|---|
| 1 | The Best Private Budgeting App for Mac (No Bank Linking Required) |
| 2 | Zero-Based Budgeting: A Complete Beginner's Guide |
| 3 | Thrive vs. YNAB: An Honest Comparison |
| 4 | The Best Christian Budgeting Apps in 2026 (honest roundup incl. competitors) |
| 5 | Mint Is Gone — Private Alternatives That Don't Sell Your Data |
| 6 | How to Budget Without Linking Your Bank Account |
| 7 | Tithing First: How to Build Giving Into a Zero-Based Budget |
| 8 | EveryDollar vs. Thrive for Dave Ramsey Baby Steps |
| 9 | How to Import Bank Transactions From CSV (Chase, USAA, BofA…) |
| 10 | Tracking 529 College Savings Alongside Your Budget |

Rules: answer the query in the first paragraph; one screenshot; one CTA to the App
Store; interlink posts; put each on its own URL under /blog/. Comparison posts (3, 5, 8)
convert best — be genuinely fair to competitors or they backfire.

## 3. Free directories & alternative-to listings (one afternoon, permanent traffic)

- **AlternativeTo.net** — list Thrive as alternative to YNAB, Mint, EveryDollar,
  Monarch, Copilot. Mint refugees search here daily. Highest-value 30 minutes on this list.
- **Product Hunt** — launch once, on a Tue/Wed/Thu. Maker comment = your story
  (built it for my own family, privacy-first, faith-driven). Ask ~10 friends to be
  genuinely active (comments > upvotes). Even a modest launch yields a permanent
  backlink + "As seen on PH".
- Also: SaaSHub, Slant, StackShare-adjacent lists, ToolFinder, privacytools-style
  directories (the privacy angle qualifies).

## 4. Communities (free, but EARN it — 90% help, 10% mention)

Direct self-promo gets you banned; being the helpful person who built a thing works.

- **Reddit:** r/macapps ("I built" posts do well), r/personalfinance (read rules;
  tool mentions only where allowed), r/ynab (people constantly ask for alternatives),
  r/DaveRamsey, r/Christianity + r/Reformed (money threads), r/budgeting, r/iosapps,
  r/privacy (the no-bank-linking story).
- **Hacker News:** one "Show HN: Thrive — budgeting app with no servers, data stays
  in your iCloud" post. Local-first/CloudKit architecture is exactly HN's taste; be
  in the comments all day; expect blunt feedback.
- **MacRumors forums, Apple subreddits** — universal-app + Sonoma-native angle.
- **Facebook groups:** Dave Ramsey Baby Steps groups (millions of members), Christian
  personal finance groups, homeschool/single-income family groups. Same rule: help first.
- **Your church + real life:** offer a free "budget night" workshop (slides = the app).
  5 families using it and telling friends beats 5,000 impressions. Hand out promo codes.

## 5. Press & reviewers (free, slow burn)

Email pitch = 3 sentences + 2 screenshots + promo code. No attachments, no fluff.
- Apple press: MacStories (loves indie + privacy), The Sweet Setup, 9to5Mac,
  MacRumors, Daring Fireball (privacy angle only, one-line email).
- Faith-finance media: Crown Financial, FaithFi (podcast + app audience), Christian
  Personal Finance blog, SeedTime, Art of Manliness (stewardship angle). Podcasts in
  this niche constantly need guests — pitch "why we built a budgeting app where
  giving comes first."
- Indie-dev circuit: Indie Dev Monday newsletter, launched.dev-style showcases.

## 6. Social — pick ONE channel and be consistent

Don't spread across five networks. Recommended: **X/Twitter build-in-public**
(#buildinpublic, #indiedev) — 3–4 posts/week: a real screenshot + what you learned.
Milestones (approved! first 100 downloads! first subscriber!) outperform features.
Optional second: short screen-recording demos (30–60s) posted to YouTube Shorts —
"How I budget without giving an app my bank login." Repurpose per blog post.

## 7. Email list (free tier)

The site already has Buttondown plumbing (`AppConstants.buttondownAPIKey` is empty —
create the free account, paste the key, ship in an update). Until then: Buttondown's
hosted signup form linked from the site/blog. One monthly email: what shipped, one
stewardship tip. The list is the only audience you own.

## 8. Measurement (all free)

- **App Store Connect Analytics** — impressions → product-page views → downloads →
  trial starts → paid conversions. Watch conversion rate per source.
- **Google Search Console** — which queries show/click the site.
- Site analytics: none currently (a privacy selling point — consider keeping it that
  way, or add GoatCounter/Plausible-CE later; if added, disclose in privacy.html).
- Weekly 15-min review: downloads, trial starts, subscriber count, top search queries,
  which channel drove what (ask in review prompt? no — just watch referrers/codes).

---

## Rollout calendar

**T-0 (approval day):**
- Verify the App Store link works on Mac + iPhone.
- Push this site update (badges/links go live). Submit sitemap to Google + Bing.
- Enroll in Apple Small Business Program (if not already).
- Personal announcement: text/email everyone you know with the link; church group.

**Week 1:**
- AlternativeTo + directory listings (one afternoon).
- r/macapps "I built" post + 2–3 helpful community comments/day.
- Blog post #1 live. Start build-in-public posting.
- Email 5 press/podcast pitches with promo codes.

**Week 2:**
- Product Hunt launch (pick a Tue–Thu).
- Blog post #2. Show HN post.
- 5 more pitches (faith-finance podcasts).

**Weeks 3–8 (steady state):**
- 1 blog post/week from the calendar; 1 community touch/day (10 min);
  2 pitches/week; watch ASC analytics; collect testimonials from real users
  (with permission) → add to thrive.html.

**Month 3 checkpoint:** double down on the ONE channel that produced installs;
drop the rest. Ship Household Sharing (v1.1) → that's a whole second launch:
"Thrive now syncs your budget with your spouse — still no servers." Repeat PH/press
cycle with the new hook.

---

## Copy guardrails (protect trust — it's the product)

- Never claim household sharing exists until it ships.
- Never claim "we can't see your data" is false-adjacent — it's literally true (no
  servers); keep saying it exactly that way.
- Trial is **7 days**; price is **$8/mo**; free tier is genuinely free forever.
- In faith channels, be authentic, not performative — this audience detects marketing
  cosplay instantly. You built this for your own family; say that.
