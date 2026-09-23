# VIDEO SCRIPT #002 — Pillar 1: Free Tool Drop [LAUNCH VIDEO #001]
# Topic: 9Router — never hit Claude Code limits again ($0 setup, 29.7K stars)
# Format: Faceless long-form, ~7 min (~950 words) → cut 4 Shorts from it
# Status: DRAFT — all claims verified against primary source (GitHub README, read 2026-09-23)
# Virality score: 92/100 (see scorecard at bottom)

## TITLE OPTIONS (pick 1)
1. Claude Code Limits? This Free Tool Makes Them Disappear
2. I Stopped Paying for AI Coding — 29,000 Devs Did Too
3. Never See "Rate Limit" Again — Free 3-Tier AI Router

## THUMBNAIL TEXT OPTIONS (pick 1, max 4 words)
1. LIMITS = GONE
2. $0 AI CODING
3. 29K DEVS SWITCHED

## DESCRIPTION DRAFT
Hit a Claude Code rate limit mid-project? 9Router is a free, open-source router (29.7K GitHub stars) that auto-switches you to cheap and free models when limits hit — plus cuts token use 20-40%. Links below.
- 9Router (free, GitHub): https://github.com/decolua/9router
- 9Router docs: https://9router.github.io/en/
- 9Router site: https://9router.com

---

## SCRIPT

### BEAT 1 — HOOK (0:00–0:30)
[SCREEN: screen-record the actual Claude "rate limit" / quota-exhausted error mid-coding session]
[CAPTION, big, first 3 seconds: "RATE LIMITED MID-PROJECT?"]

"You know this screen. Mid-project, deep in flow — and Claude Code stops. Rate limit. Quota exhausted. Come back in five hours. Meanwhile twenty-nine thousand developers stopped seeing this screen entirely. Same Claude Code. Same Cursor. Same Codex. The difference is one free tool sitting between their editor and the AI — and when their limit hits, it silently switches them to another model in seconds. No subscriptions added. No work lost. It's called 9Router. Open source. Free forever. Twenty-nine thousand stars on GitHub. And in the next six minutes I'll show you the exact setup."

### BEAT 2 — PAIN MATH (0:30–1:30)
[SCREEN: simple cost graphic — "$20/mo subscription + dead hours waiting"]
[BROLL: developer staring at loading spinner, clock]

"Let's do the math nobody does. A Claude Pro subscription is twenty dollars a month. But the real price is the hours you lose staring at that limit screen during a deadline. Or worse — the overage bills when you panic-switch to pay-per-token APIs at two in the morning. Git diffs, grep output, file listings — boring tool outputs eat thirty to fifty percent of your prompt budget before the AI even thinks. You're paying full price for tokens spent on your own file listings. That's the firewall your money keeps hitting. 9Router attacks both problems at once."

### BEAT 3 — THE REVEAL + PROOF (1:30–3:00)
[SCREEN: https://github.com/decolua/9router — scroll hero: stars 29.7K, forks 5.6K, MIT license badge]
[CAPTION: "29.7K STARS — FREE FOREVER — MIT"]

"This is the repo. Twenty-nine thousand stars, fifty-six hundred forks, MIT license — free forever, and the dashboard itself tells you the software never charges anything. Two weapons inside. Weapon one: RTK Token Saver. It compresses tool outputs — git diffs, grep, ls — before they reach the model. Their own example: forty-seven thousand tokens in, twenty-eight thousand out. Forty percent saved. Same context. Same answer. Weapon two: three-tier fallback. Tier one is your subscription. Quota dies — it drops to tier two, cheap models at twenty to sixty cents per million tokens. Budget cap hits — tier three, free models. You never stop coding. Zero downtime."

### BEAT 4 — THE $0 STACK (3:00–4:30)
[SCREEN: README pricing table scroll — Kiro / OpenCode Free / Vertex rows]
[CAPTION: "$0/MONTH — REAL MODELS"]

"Here's the stack that costs zero. Kiro AI: Claude 4.5 plus GLM-5 free, around fifty credits a month, login with GitHub. OpenCode Free: no login at all, models auto-fetched. Vertex AI: three hundred dollars in credits on a new Google Cloud account. These are production models — Claude 4.5, Gemini 3 Pro — not toys. And the README's own pro tip says it plainly: RTK plus Kiro plus OpenCode Free equals zero cost with twenty to forty percent token savings. Their words, not mine."

### BEAT 5 — SETUP, LIVE (4:30–6:00)
[SCREEN: record YOUR OWN terminal + browser doing this — commands below are verbatim from the README]
"Setup is three steps, all from their README. Step one — install globally: `npm install -g 9router`, then run `9router`. Dashboard opens at localhost:20128. Step two — connect a free provider in the dashboard: Kiro or OpenCode Free, no signup needed for OpenCode. Step three — point your tool at it: in Claude Code set the endpoint to http://localhost:20128/v1 with the API key from your dashboard; Codex and Cursor take the same endpoint as an OpenAI-compatible base URL. Done. Your editor now has three fuel tanks instead of one. [EDITOR NOTE: re-verify the Quick Start block at https://github.com/decolua/9router on recording day — UI labels drift, commands quoted here are README-verbatim as of 2026-09-23.]"

### BEAT 6 — THE BACKLINK HACK + CTA (6:00–6:50)
[SCREEN: README "Video Guides" section — wall of creator videos + "Submit a PR" line]
[CAPTION: "COMMENT: ROUTER"]

"One more thing — look at this. The repo has an entire wall of creator videos, in Vietnamese, Hindi, Indonesian, Persian, English. Global demand, proven. And it literally invites you: made a video about 9Router? Submit a pull request and they'll merge it. Meaning this video can live inside a twenty-nine-thousand-star repo as a backlink. So comment ROUTER and I'll send you the direct link. Subscribe — next week I test whether the free tier models actually match paid quality, with receipts. You want that data before you switch."

---

## EDITOR SOURCE LIST (exact)
1. PRIMARY — repo homepage, hero scroll, stars/forks/license, Quick Start block: https://github.com/decolua/9router
2. PRIMARY — setup details per tool (Claude/Codex/Cursor endpoint + key flow): same page, "CLI Integration" section
3. PRIMARY — $0 stack + pricing table (Kiro/OpenCode Free/Vertex rows): same page, "Pricing at a Glance" + "FREE Providers" sections
4. PRIMARY — RTK 47K→28K example: same page, "RTK Token Saver" section
5. PRIMARY — Video Guides wall + "Submit a PR" line (BEAT 6 screen): same page, "Video Guides" section
6. Docs (backup if README restructures): https://9router.github.io/en/
7. Site (logo assets): https://9router.com
8. BROLL keywords: "rate limit error screen", "developer deadline stress", "fuel tanks switching", "token counter dropping", "globe creators map"

## SHORTS CUTS (4)
- Short 1: BEAT 1 hook only → "full setup on channel" (0:30)
- Short 2: "47K tokens → 28K, same answer" RTK proof (0:30)
- Short 3: "$0 stack: Claude 4.5 free" pricing table scroll (0:35)
- Short 4: "29.7K stars + merge-your-video-here" repo wall (0:30)

## FACT-CHECK LOG (verified 2026-09-23, primary source = GitHub README)
- "29.7K stars, 5.6K forks, MIT" → repo header ✔
- "npm install -g 9router / dashboard localhost:20128" → Quick Start ✔
- "3-tier: subscription → cheap → free" → How It Works diagram ✔
- "RTK 47K→28K, 40%" → RTK section ✔
- "Kiro ~50 credits/mo, OpenCode Free no-auth, Vertex $300" → Providers + FAQ ✔
- "GLM $0.6/1M, MiniMax $0.20/1M" → Pricing table ✔
- "Free forever, never charges" → Billing Reality section ✔
- "Video Guides wall + submit PR" → Video Guides section ✔
- Endpoint http://localhost:20128/v1 → CLI Integration ✔

## VIRALITY SCORECARD (10 params, vs Script #001 V3Code in brackets)
1. Timing — Sept 2026 coverage wave, stars climbing daily (9) [V3Code: 4 — covered Aug 12]
2. Pain intensity × breadth — #1 complaint (limits mid-work) + money out of pocket (10) [7]
3. Novelty — FB mention only, no flagship video from model channel; we own it (8) [3]
4. Money leverage — concrete $0 setups + 40% token math (10) [5]
5. Social proof on tap — 29.7K stars, 5.6K forks, multilingual creator wave (10) [6]
6. Packaging — error-screen hook, 4 title options, open loop to next video (9) [8]
7. Retention design — payoff every ~90s (proof → $0 stack → setup → backlink hack) (8) [7]
8. Shareability — "send to every dev paying for Claude" identity share (9) [6]
9. Search+browse — evergreen ("claude code limits") + trending push (9) [6]
10. Credibility — every claim primary-sourced, install verbatim from README (10) [9]
TOTAL: 92/100 [V3Code: 63/100] → 9Router launches first. V3Code becomes video #003 with a fresh angle.
