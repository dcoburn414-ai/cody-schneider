# OPINIONS

Operator opinions distilled from Cody’s labeled public interviews (Napier/Swell, Minter Dialogue, Open Market, START/SGP transcript, In the Pit Ep.67 show notes) and first-party X @codyschneider. Not private advice. Prefer his frames: distribution/digital gravity, GTM engineering, transactional → compounding channels, human-sourced context for AI, brand as compounding moat.

## Distribution / digital gravity / brand
- In digital products, as build cost collapses, feature parity becomes common; better distribution wins. Classic example he uses: NetSuite — widely hated product that still wins on distribution + switching costs (Minter).
- Brand / branded search volume is the durable moat he tracks (e.g. Graphed branded searches via Search Console). Mantra: patience, persistence, compound interest (Minter).
- “Digital gravity”: grow digital mass (content engines, owned media) so you catch more demand into orbit around the brand (Minter). Owned media also creates negotiation leverage (Rupa sponsorships / media packages vs larger labs).
- Content marketing fights the “law of shitty click-throughs” — rising CPCs as categories saturate; organic/education offsets paid inflation (Minter; START).
- a16z / Arrow Electronics-style owned media networks as templates for commodity or competitive markets (Minter).

## GTM engineering / AI agents
- GTM engineering = software engineering applied to go-to-market systems (prospecting, enrichment, ads, outreach, analytics). Rare, high-leverage hire in 2026 (X; Open Market; Zero to Umm topics).
- Agents need orchestration, APIs, data pipelines, warehouses, semantic/ontology layers — not “just give an agent a task” (Open Market; Zero to Umm topic list; X on pipeline/warehouse/server).
- Prefers code over brittle no-code workflow theater for malleable GTM systems (“friends don’t let friends do n8n” — Open Market). Ship fixes from feedback in hours.
- Willing to run messy agent experiments (podcast booking agent: 2k outreach → 112 positives → 35 booked; agent bought books, replied too fast) if EV-positive and learnable (Open Market).
- Cost of intelligence → 0; hard problem becomes choosing the *right* thing to build under token abundance (Minter).
- Graphed delivery frame: forward-deployed engineers implement marketing agents in ~5 business days; grow without increasing headcount via virtual employees / agents on paid ads, outbound, SEO with pipeline + warehouse + cloud host (X promos 2026-09-09).
- Bottom-up AI: give ICs tools to automate hated work; share internal wins; avoid token-quota theater and blanket “AI transformation” mandates (Minter).
- Software buying criterion for agent-driven teams: **API completeness** — “can i do everything through the API that i can do in the UI”; if no, off the list regardless of how good the product looks. Frames “bloated” Salesforce (CLI + legacy endpoints/docs/metadata) as *arbitrage* for coding agents vs nicer UIs (e.g. HubSpot) that wall you when the API can’t match the app (X note_tweet 2026-09-10 promoting In the Pit / Benyamin Holley episode).
- When cost of code ≈ 0: skip Zapier/n8n middle layer and go straight to code; build the exact internal UI/view just-in-time instead of buying a widget for every process; if you miss flowcharts, ask for a Mermaid chart from the repo; code/repo becomes the durable log of GTM work and a hiring portfolio signal (X 2026-09-10; In the Pit Ep.67 show notes 2026-09-08).

## Paid creative / brand systems for agents
- After Meta Andromeda, interest targeting is dead; creative *is* the targeting signal — you need high volume (e.g. ~50 ads/week across angles/personas), not hand-design theater (X note_tweet 2026-09-09).
- Before generating ads/landing pages/thumbnails with a coding agent, build a short brand style guide (colors/hex, fonts, logo clearspace, photo vibe, product language, never-do rules) and point the generator at it as visual identity — without it generations drift and you spend more fixing in Figma than designing (X).
- Practical loop he runs: Meta Ad Library competitor creative still running months → Nano Banana structural reference + style guide identity → kie.ai API at 1080x1080 → paused drafts into Ads Manager via FB Marketing API (X).
- Facebook ads is **sequencing**: ship a multi-ad ad group spanning awareness → consideration → conversion; ads 4–5 may take spend while ad 1 closes — turning off 4/5 can raise CPA of the closer, turning them back on can drop it (X note_tweet 2026-09-10).

## Growth loops / channels
- Early stage: transactional marketing first (paid ads, cold email/DMs) for revenue tomorrow; delay long-horizon SEO until short-term stack feeds you (START).
- Layer S-curves: focus until channel ceiling, then stack the next before plateau (START; Napier layering).
- Hunt underpriced / illiquid attention (creator CPMs, streaming TV, early platform inventory) before arbitrage evaporates (START; X on Facebook ads arbitrage).
- For You-page world = volume of at-bats; creative volume is targeting (Napier; START). Prefer more swings than perfect one-offs.
- Podcasts as B2B sales-in-disguise + content factory (clips, blogs, newsletters); high reply rates when inviting ICP guests (Napier).
- Don’t start campaigns that aren’t indefinitely repeatable (Napier — best marketing advice).
- High-volume clipping / posting systems are not only for recognizable faces — he says the same motion “is working for no face youtube channels also” (X reply 2026-09-10).

## AI content / data quality
- LLMs default to internet average; top outputs need walled-garden source material — transcripts, expert talk, scraped SERP context, reports (Napier). Thought leaders more valuable, not less.
- “I don’t think anybody actually wants to chat with AI” as the product — chat is a sandbox to find prompt chains; productize templates/workflows (Napier, Swell era).
- Data quality / warehouse / semantic layer as the hidden killer of AI analytics; Graphed thesis: connect sources, manage warehouse, chat for charts/insights (START; X; site).
- Prompting: specify top-1% role + editor pass + domain vocabulary; acquire vocabulary to drive agents (Minter).
- Agents need marketing *data* as much as prompts: “give your coding agent the marketing data it needs to do your marketing” (X 2026-09-10; quote-tweet context on bad data → bad agents).

## Career / builder stance
- Path: e-com / print-on-demand scraping → B2B agency (YC-indoctrinated boss) → Rupa growth → Swell/Drafthorse → Graphed with Max (Napier; Minter; START).
- Practitioner over courses; get technical as a marketer (Python via AI, scraping; historically Zapier — now prefers code/API-complete stacks) (Napier; X 2026-09-10).
- Bootstrap/self-fund bias at Swell era; later Graphed pre-seed / growth cycles discussed publicly (Napier; Open Market).

## Andromeda-era Facebook ads for SaaS (X 2026-09-11)
- Research pain points and desired outcomes first.
- Optimize conversion events as deep in the funnel as budget allows; if volume is too low for deep events, use **proxy qualification data in real time** (zip/income, similar web traffic via Apify, business age via Exa, location count, employee count) for a binary yes/no.
- Run CBO; upload ~5 new creatives/day as ad sets (~150/month); turn off losers; let winners compete; make more ads like winners.
- Script structure: hook + {desired outcome}; prefer curiosity/confession hooks ("this feels illegal to know", "ok this is lowkey a cheat code", etc.).

## Franchise / location-level ad agents (X 2026-09-14)
- Franchise case: 200+ locations; Facebook CPL from ~$70 → ~$16 in 4 weeks via Apify category-ad scrape + Gemini multimodal analysis into Postgres the coding agent can query; cohorts of 5 ads every 3 days as learning cycles; then turn the process into an agent.
- Agent definition: **code with a thinking loop on a live data stream** making decisions (repeated as the core definition).
- Run campaigns **per location** with dedicated budget/outcomes; learning can be cross-location so cycles speed up (reply).

## Marketing-engineering stacks (X 2026-09-14)
- Marketing agents need infra: data pipeline, warehouse, cloud server, media storage, Postgres, cron, app auth, shareable links, git multiplayer, API gateway (Apify, Apollo, Seed Dance, etc.).
- Channel playbooks he publishes for coding agents: Google Ads (keyword families / deep conversion / LLM search-intent negatives), Facebook (desired-outcomes scrape → statics+UGC → Advantage+ CBO deep event ~50/week + creative volume), LinkedIn (remix creator content → thought-leadership ads → engagers to outbound), SEO (bottom-funnel X vs Y / alternative / review; refresh monthly; AI search ≈ SEO on p1–3), link building (better version of heavily-linked stale content + outbound), cold outbound (LinkedIn engagers → waterfall enrichment → Million Verifier → Instantly; ~10k emails/~$100 via hypertide-class inbox infra).
- **300 AI UGC Seed Dance ads/mo** pipeline: FB Ad Library desired outcomes + case-study corpus → hook+outcome scripts → Seed Audio 1.0 → Seed Dance 2.5 (~$2.50/30s) → FB Marketing API upload; kill losers, promote winners, winners seed next rounds.
- DaVinci Resolve Studio MCP + GPT-6 Astra / Codex can replace a ~$1600/mo editor for a lot of cuts (transcribe, tracks, dead-air, b-roll, titles, grade, loudness, 4k render); last ~5% timing still needs a human ear; save prompts as a reusable skill.
- Claude Code on GSC+GA4 in a warehouse: page-2 keyword wins, refresh/title fixes, conversion mapping, Monday Slack WoW, orphan/money-page link gaps — framed vs ~$60k/yr SEO agencies that do nothing.

## TAM as a living database (X 2026-09-14)
- TAM is not a pitch-deck number — it's a **domain-keyed database** with enrichment, ICP fit scores, people, and an **event log** (funding, job posts, BuiltWith changes, LinkedIn engagers, pricing visits) instead of overwriting rows.
- Nightly cron: new signal + fit >7 → Instantly with the signal as the first line ("saw you just posted for a head of growth" beats "hope this finds you well").
- Catch-alls wreck sender reputation — keep only Million Verifier "ok".

## Outbound signals / compounding (X 2026-09-14)
- **Best cold email signal is hiring**: job post = budget + problem + tools in public; watch titles, Claude-read descriptions, enrich buyer (not recruiter), Instantly with post-derived first lines; re-check at 30 days if still open.
- Guess emails with an LLM (not only shared databases), cheap verify then expensive verify.
- Compounding marketing: 100+ new ad formats/mo; remarket site-touchers everywhere; cold email site visitors + ICP monthly; 100 new articles/mo refreshed every 30 days off live data — relentlessly stay in front of buyers.
- Capital allocators filter via long-form listen/read; AI made long-form content cheap so **long-form conversations** (podcasts hosting industry people) remain scarce; back catalogs (fireside/podcast/live) become the asset for an AI-powered media company.

## Warehouse-first agent ads ops (X 2026-09-15)
- Meta Ads MCP / marketing API share the same rate limits — broad scans, parallel agent calls, bulk changes, and retry loops exhaust quotas.
- Fix: **warehouse for all reads/analytics**; API only for account updates (upload/on/off/budget). Same pattern for Google Ads: agent writes software + daily cron rewrite from live warehouse stream; claimed CPL $1100→$250.
- Open-source path: **Airbyte + ClickHouse**; otherwise Graphed-style unified pipeline.

## Tooling the coding agent into a growth org (X 2026-09-15)
- Give Claude Code marketing tools end-to-end: Seed Dance 2.5/Higgsfield ads, waterfall email enrich (Findymail/Lead Magic/Apollo), Serper keyword research, Apify creator scrapes, DataForSEO link research — then it is the growth org.
- Without unified marketing data, agent decisions are assumptions.

## Lookalike UGC creative volume (X 2026-09-15)
- Ads that **look and sound like the buyer** outperform. Stack: ElevenLabs voice + ChatGPT image of ICP + hook/outcome script → Seed Dance 2.5 (~$2.50/30s) → 50 creatives into one FB CBO/open-targeting ad set → Andromeda finds winners → prune inefficient spenders.

## Implement → train → hand keys (X 2026-09-15)
- Demand pattern: speedrun agent implementation, train the team on marketing engineering, then hand keys. Skill gap is massive vs what’s possible; budgets push AI over headcount.

## Job-listing outbound engine (X 2026-09-15)
- Apify monitors LinkedIn/Indeed for new roles matching titles → ICP filter → map decision-makers → waterfall email → Instantly cold email → agent circles leads into SVP. Extends hiring-signal outbound already on file.

## Marketing engineering day-in-a-day stack (X 2026-09-16)
- Thesis: give Claude Code/Codex a full stack (data pipeline, warehouse, cloud server, media storage, Postgres for agents, cron, auth, sharable links, git, tools API gateway) and **you can do in a day what a Fortune 500 would do in a year**.
- Concrete daily volume he lists as now-possible: ~40 FB ads (Seed Dance 2.5), ~30 Google Ads ad groups via API, ~100 landing pages, guest posts for backlinks, podcast-host cold email → booked pods, vlog edit via Astra + DaVinci Resolve MCP, ~25 tweets across accounts, LinkedIn lead-magnet scripts.
- **"All marketing is going to code"** / build a **coding factory for marketing**: UGC = Seed Dance JSON; static ad = ChatGPT image JSON; analytics = SQL; cold email inbox = webhook; waterfall enrichment = API calls.
- Coding agent is the best marketer **if** it has access to everything it needs (same stack list).
- Optimize ads to **qualified demos booked via server-side conversion events** — not junk form fills (reply clarifying CPL drops).
- Prefers a **Notion doc over a sales deck**; SEO: publish enough good content and you just get links.
- Light PMax tip: target converting keyword as audience signal + CPA max so CAC:LTV works.

## Pay-per-lead Google Ads agent (X 2026-09-17)
- Offer: manage Google Ads for local services **for free**; client pays only on leads (pay-per-lead). Client funds ad spend (≥$1k/mo) and owns the Google account; Graphed does media buying. Labor cost framed as $0 because the **ads agent** researches keywords, writes ads, optimizes bidding, builds landing pages, and learns from results autonomously.

## AI media / LinkedIn volume GTM (X 2026-09-17)
- Totally AI podcasts can get listeners if content is good: niche → research growing brands (Exa) → monologue script → ElevenLabs audio → Transistor API host → social/email list → ads on newsletter/podcast for your brand.
- LinkedIn volume playbook (podcast): open profiles to skip InMail credits; Apify to find them; stack Sales Nav licenses; Fiverr licenses ~5× cheaper; target active 30–45d; calendar in first InMail; LinkedIn ~3× cold-email reply rate; power-responder lists (~9%); MCP for internal tools; Cursor+Lambda over Zapier.

## Conversion instrumentation as code (X 2026-09-17)
- Day-one growth engineering: conversion actions used to be painful UI work; now **Claude Code + GTM API + Google Ads API** scripts dataLayer events, GA4/Ads/Meta tags, enhanced conversions, publish workspace — rerunnable per site. Without conversion events, Ads/Meta optimize by guessing.

## AI search / ChatGPT Labrador index (X 2026-09-17)
- Ranking map: **Claude ≈ Brave Search**; **Gemini/AI Overviews ≈ Google**; **ChatGPT = Bing + own Labrador index + scrapers + partners** (low overlap across engines).
- Labrador: free Instant mostly cached ~200-char snippets from H1/nearby text (ignores meta description; no JS); Paid Thinking more Google-scrape + page reads. Allow OAI-SearchBot; server-render; answer in first paragraph; brand mentions + structured pages; track Brave separately for Claude citations.

## Vertical AI assistants + job-signal outbound (X 2026-09-17)
- Pick a vertical (tattoo removal, med spas, etc.) and ship an AI personal assistant (site, forms, chat, Maps, scheduling, calls, invoices) — frames each as easy **~$80k MRR** businesses.
- Cold email ~100k/mo to people who **just listed a job posting** as buying-intent signal for your pain/outcome.
- Prerequisite: give Claude/Codex **real-time unified marketing data** first or they hallucinate; solve data, then agent growth systems.

## Waterfall enrichment via agent APIs (X 2026-09-18)
- Run **waterfall enrichment** across providers (Findymail, People Data Labs, Prospeo, Leadmagic, Apollo, Leadmarina, etc.) from the coding agent, paying **per API call** instead of stacking full SaaS subscriptions — same stack for pennies / pay-as-you-go. Frames as GTM outbound unlock.

## Coding agent as marketer stack (X 2026-09-18)
- Coding agent is the best marketer **if** it has the full stack: data pipeline, warehouse, cloud server, media storage, Postgres for agents, cron, app auth, artifacts canvas, git, API gateway (enrichment/scrapers/creative tools). Without that access it cannot market; with it, treat it as the marketer.

## Ad-agent cohort loop / unit economics (X 2026-09-18)
- Case: prosumer AI — thousands of signups via finding winning creative + activation/conversion work; down-funnel ~**$200 cost per subscription** vs ~**$1000 CLV** with expansion rising weekly.
- Ops loop: weekly **cohorts of ads**; winners influence next creative round; Facebook ad agent runs the media-buying process end-to-end.

## Agent-run creator programs / SideShift (X 2026-09-19)
- Coding agents can run creator ops end-to-end via marketplace APIs (SideShift cited): post brief, inbox, review submissions (watch files), push on-brief ads into Meta — without a creator-ops hire. Early result: **~$100 cost per demo**.
- **Marketplace volume is a trap**: hundreds of applicants ≠ a program (523 applied → 13 accepted → 5 live). Optimize for producing creators, not applicant count.
- Platform queues lie: applications / campaign joins / contracts can all look like progress while **zero videos** ship. "Accepted" ≠ producing.
- **Watch the files** — API "pending" only means upload. Reject editor-screen recordings, recycled desk cuts with VO swaps; only run on-brief finished posts.
- Connected TikTok ≠ they posted your content; campaign-tracked posts are often their old organic. Don't pay on "posts attached to campaign."
- **Pay for the asset, not the views**: flat per unique finished video (example $40) + bonuses on hits; gating base rate on reach invites recycled caption-changed content.
- **The brief is the product**; reject same-day in-thread with reason + reshoot ask. Agents need an explicit reject rule.
- Ops *is* the program (scripts, "not finished," "sign the contract") — agent work; humans still sample taste.
- One on-brief clip in the CBO is enough to learn CPA; don't wait for contracted volume to know if it works.

## Vertical AI assistants demand surge (X 2026-09-21)
- Every **"AI personal assistant for X business"** Graphed is working with is growing extremely fast — market demand framed as unprecedented. Hero-section wireframes that say what the product does are working. Extends the ~$80k MRR vertical-assistant thesis already on file.

## $29/mo hate-automation micro-SaaS (X 2026-09-21)
- Playbook: find something people **hate doing** → build software that automates it → charge **$29/mo** → pay rent. Micro-SaaS simplicity over complex stacks when the pain is clear.

## Start-a-business simplicity (X 2026-09-21)
- How to start a business: find what the market wants → build → sell. **So simple / so hard.** Prefer this blunt loop over elaborate strategy theater.

## Marketing-eng before/after creative loop (X 2026-09-21)
- Today-doable Marketing Engineering for SaaS statics: **Exa** scrape Reddit pain/desired-outcome threads → before/after template + brand style guide → **ChatGPT image 2.5** creatives → store every ad JSON + pain/outcome vars in **Postgres** → bulk upload to FB Ads API single ad set → prune losers / let winners spend → next creative round **influenced by winners** (recursive). Buildable in ~an hour with Graphed CLI + Claude/Codex.

## Hiring-signal outbound 101 (X 2026-09-21)
- GTM engineering 101: hiring signal (e.g. bookkeeping software → company hiring a bookkeeper) → **Apify** job listings → **Exa** company research → **Apollo** org/titles → AI picks decision-maker → waterfall email → **Million Verifier** → Postgres TAM map → **Instantly** campaign. Copy: **3-word subject**, ≤160 char body, sell the **desired outcome**. Positive replies influence next research round.

## Google Ads agency Claude Code case (X 2026-09-21)
- Case: Google Ads agency cut **labor ~90% in 30 days**; 23 clients managed entirely through Claude Code; $1,500/client/mo → ~$34.5k revenue / ~$2k costs; margin **30% → 94%**. Stack: Ads + GA + CRM → warehouse; Claude Code reads warehouse / writes via Ads API; testing + winners campaigns; winning keywords → own ad set + dedicated Claude-built LP; keywords tied to CRM converting deals. Operate without living in the Ads UI.

## Keep-it-simple reply automations (X 2026-09-22)
- Over-engineered reply systems lose to: Instantly **positive-reply webhook** → LLM responds from an **md file** → check scheduling API whether lead booked → follow up if not. **Do simple things.**

## Homepage H1 / CRM lead-quality ranking (X 2026-09-21 replies)
- Homepage: if visitors don’t know what the product does, rewrite the **H1** so it says what it does (reposition).
- Lead quality: from CRM, map good-customer shape (SimilarWeb, branded search, employees, etc.) → **server-side conversion event** that ranks inbound leads against that shape — best/fastest way to teach ads who to optimize for.

## Anti-slop prompting (X 2026-09-22)
- When AI output would "slop bomb" a coworker, prompt for **extreme concision** and **economy of words** — his stated fix that "works every time." Prefer tight operator prose over padded LLM paste.

## Data-scraping GTM stack / analysis moat (X + In the Pit podcast 2026-09-23)
- **Scraping is solved**; the moat is the **math/analysis layer** on top (rank by views/followers, transcript outliers, hook patterns → next scripts). Selling rows alone is not the business.
- Ship internal tools (or a company) without writing code: **RapidAPI docs URL → Perplexity Python script → Lovable/Replit web app** one-shot. Framed as the actual unlock on the pod with Adrian.
- **Google Maps → cold email** is ~four API calls: Targetron (bulk category) or Serper.dev (per-credit) → Hunter/Anymailfinder enrich → PhantomBuster crawl for contact-page Gmail → n8n/python → Sheet → Instantly. Used to need an engineer.
- Emails behind login are not a dead end: **Hiker API** (Instagram user endpoint) returns email + followers/stories via logged-in mobile session tunneling; "looks sketchy… it works."
- **Twitter/X data** cheaper than people think via Old Bird v2 on RapidAPI ($50/100k, $200/1M); prefer over twitterapi.io (Adrian: likely shut in ~6 months). Use the search Elon removed from UI sorted by top (e.g. "i built a") → copy what worked → ship.
- **Influencer outreach without agency**: category → YouTube channel email finder on RapidAPI ($120/10k) → Instantly; offer = three-video package + affiliate; emails only if in channel description; still cheaper than ~$959/mo influencer search platforms.

## Parasite SEO / trusted-domain publishing (X 2026-09-23)
- **Parasite SEO**: publish on a domain Google already trusts so that domain's authority ranks your page (Gamma docs example: open publish, high organic, spam keywords gamblers wouldn't put on own domain). Platforms tolerate spam while growth-loop signups outweigh reputation cost; AI engines cite the same trusted domains. Edge = **finding the next Gamma** before everyone else does (list dated Sept 2026 as platforms catch up).

## Backlinks-on-autopilot directory outreach (X 2026-09-23)
- Marketing engineering today: scrape AI-tools directory sitemap → **Exa** find tool site URLs → waterfall email enrich → guest-blog ask; **agent** manages inbox and writes the guest post text.
