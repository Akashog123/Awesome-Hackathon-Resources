# Curation Criteria

How a resource gets into (or out of) this list. Every addition, removal and review uses this rubric.

## 1. Hard gates (fail any → reject)

| Gate | Pass when |
|------|-----------|
| **Live** | URL loads and the product works today |
| **Usable free** | Open source, or a free tier usable without a credit card |
| **Not a duplicate** | Not already listed. A near-clone of a listed tool must state what it does differently |
| **Participant-relevant** | Helps a hackathon participant build, design, or demo within the event. Organizer-only tools are out of scope |

## 2. Score (0–2 each, max 10)

| Criterion | 0 | 1 | 2 |
|-----------|---|---|---|
| **Speed** | Days of setup / learning | Hours to useful | Minutes: copy-paste, one command, or zero-install |
| **Cost** | Paid, or pricing unclear | Freemium with real limits | Fully free / OSS |
| **Demo impact** | Invisible to judges | Helps the build behind the scenes | Visibly lifts the demo, UI, or pitch |
| **Maturity** | Brand new, single maintainer, no users yet | Maintained, documented | Widely used, active releases |
| **Fit** | Crowded category, nothing new | Solid option in its category | Fills a gap the list doesn't cover |

## 3. Decision

| Score | Action |
|-------|--------|
| **8–10** | Add |
| **7** | Add, unless Maturity = 0 |
| **5–6, or 7 with Maturity = 0** | Watchlist below; re-check next review |
| **≤ 4** | Reject |

**Awesome lists / meta-lists** skip the score. They go under *Related Awesome Lists* only if they are actively maintained and link to a section a hackathon builder would use.

## 4. Entry format

```md
- **[Name](https://url)** - What it does, in one line, and why it helps in a hackathon
```

Inside a section, sort entries by score (highest first), then alphabetically. Put each tool in exactly one section (the one a builder would look in first).

## 5. Review cadence

Re-check the list every quarter:
- Re-run the gates. A dead link or a lost free tier → remove.
- Re-score Watchlist entries. 7+ now → promote.
- A newer tool scores higher than a listed duplicate → replace the weaker one.

---

## Evaluation log

### 2026-11-15

| Resource | Speed | Cost | Demo | Maturity | Fit | Total | Decision | Note |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|---|---|
| [Amicro](https://amicro.dev) | 2 | 2 | 2 | 1 | 2 | 9 | Add → UI Libraries | 170+ shadcn motion components |
| [boneyard](https://boneyard.vercel.app) | 2 | 2 | 1 | 2 | 2 | 9 | Add → UI Libraries | Skeletons generated from real UI |
| [Its Hover](https://itshover.com) | 2 | 2 | 2 | 1 | 2 | 9 | Add → Icons | Animated React icons |
| [Taste Skill](https://tasteskill.dev) | 2 | 2 | 2 | 1 | 2 | 9 | Add → AI Development Tools | Design skill for coding agents |
| [Hallmark](https://usehallmark.com) | 2 | 2 | 2 | 1 | 2 | 9 | Add → AI Development Tools | Design skill + slop linter |
| [Thinking Orbs](https://www.thinkingorbs.com) | 2 | 2 | 2 | 1 | 2 | 9 | Add → UI Libraries | AI status indicators, MIT |
| [UploadCN](https://uploadcn.dev) | 2 | 2 | 1 | 1 | 2 | 8 | Add → UI Libraries | shadcn upload components |
| [Transitions.dev](https://transitions.dev) | 2 | 1 | 2 | 1 | 2 | 8 | Add → Generators & Snippets | UI transitions + agent skill |
| [Filee](https://filee.sh) | 2 | 2 | 1 | 1 | 2 | 8 | Add → Design & UI/UX | Offline file converter, OSS |
| [Skullet](https://skullet.lochie.me) | 2 | 2 | 1 | 1 | 1 | 7 | Add → UI Libraries | Overlaps boneyard; differs: runtime, no build step |
| [delphitools](https://delphi.tools) | 2 | 2 | 1 | 1 | 1 | 7 | Add → Generators & Snippets | Small no-login browser tools |
| [Landbook](https://land-book.com) | 1 | 1 | 1 | 2 | 2 | 7 | Add → Inspiration & Ideas | Free gallery, PRO tier |
| [Atlassian Design System](https://atlassian.design/design-system) | 1 | 2 | 1 | 2 | 1 | 7 | Add → Design & UI/UX | Only for apps built on Atlassian products (Forge) |
| [ascii-reveal](https://github.com/quanhoangindex/ascii-reveal) | 2 | 2 | 2 | 0 | 1 | 7 | Watchlist | Weeks old, one maintainer |
| [posts.design](https://posts.design) | 1 | 2 | 1 | 1 | 1 | 6 | Watchlist | Social post inspiration; launch posts |
| [The AI Design Guide](https://aidesign.guide) | 1 | 1 | 1 | 1 | 1 | 5 | Watchlist | Weekly guides, not a tool |
| [iFixAi](https://ifixai.ai) | 0 | 0 | 1 | 1 | 1 | 3 | Reject | Enterprise agent audit, pricing unclear |
| [Saaspo](https://saaspo.com) | – | – | – | – | – | – | Reject | Already listed |
| [awesome-rust § Audio](https://github.com/rust-unofficial/awesome-rust#audio-and-music) | meta | | | | | | Add → Related Awesome Lists | |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | meta | | | | | | Add → Related Awesome Lists | |
| [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) | meta | | | | | | Add → Related Awesome Lists | |

### 2026-11-15 · Link audit and cleanup

All 249 links were checked with curl, and every non-200 result was confirmed in a real browser. Cloudflare challenge pages count as live.

**Fixed (verified working):**
- Renamed or moved: Windsurf → Devin Desktop, Clerk.dev → Clerk, RunwayML → Runway, IBM Watson → IBM watsonx, GameMaker Studio → GameMaker, SCRNSHTS → ScreensDesign
- New URLs: Claude Code, CoinGecko, OpenAI API, Moralis, MetaMask, Notion, BigQuery Sandbox, Draw.io, v0, Radix Icons, React, Paint.NET, Easy Releasy, Google Slides
- ScreenToGif now links to its GitHub repo (still maintained; its website redirects elsewhere)
- Description fixes: Radix Icons, FamiStudio (NES, not SNES), bfxr (now runs in the browser), Unity

**Removed, dead or failing a gate:** Mocky (down), Glitch (hosting ended), InVision Freehand (shut down, redirects to Miro), Geist Icons (page gone), Popsy (DNS error), cgMusic (404), Chronolapse (bad TLS certificate), ZBrush (paid, link 404), Adobe XD (discontinued), PlanetScale (no free tier)

**Removed, not useful to participants:** VPN & Privacy section (1.1.1.1, BrowsecVPN, ProtonVPN, TouchVPN), Toggl Track, Pomofocus, TomatoTimer, YouLearn.AI and its LLM section, Fivetran, Confluent Kafka, LibreOffice, Unarkhive, Evernote Design, Stability.ai

**Removed duplicates (one section per tool):** Unity Personal, plus the second Blender, Figma, GIMP and Miro entries

**Kept, to recheck next review:** pygame.org (temporarily down for maintenance), security and CTF tools (relevant only to security hackathons)

### 2026-11-15 · Alternatives and gap-fillers

Free tiers were checked on each pricing page, and OSS activity via GitHub (all pushed within the last month unless noted).

| Resource | Speed | Cost | Demo | Maturity | Fit | Total | Decision | Replaces / fills |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|---|---|
| [Google AI Studio](https://aistudio.google.com/) | 2 | 2 | 2 | 2 | 2 | 10 | Add → AI & ML | Free LLM API (gap) |
| [Gradio](https://www.gradio.app/) | 2 | 2 | 2 | 2 | 2 | 10 | Add → AI & ML | ML demo UI (gap) |
| [Stripe test mode](https://docs.stripe.com/testing) | 1 | 2 | 1 | 2 | 1 | 7 | Add → APIs | Demo payments; re-scored from 10 (see below) |
| [Groq](https://console.groq.com/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → AI & ML | Free fast inference |
| [OpenRouter](https://openrouter.ai/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → AI & ML | 25+ free models, one API |
| [Ollama](https://ollama.com/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → AI & ML | Offline LLMs |
| [Vercel AI SDK](https://ai-sdk.dev/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → AI & ML | LLM app plumbing |
| [Streamlit](https://streamlit.io/) | 2 | 2 | 2 | 2 | 1 | 9 | Add → AI & ML | Data apps (overlaps Gradio) |
| [Public APIs](https://github.com/public-apis/public-apis) | 2 | 2 | 1 | 2 | 2 | 9 | Add → APIs | API discovery |
| [Convex](https://www.convex.dev/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → Backend | Realtime backend |
| [Neon](https://neon.com/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → Database | PlanetScale |
| [Render](https://render.com/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → Deployment | Glitch |
| [Vite](https://vite.dev/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → Frontend | Fast bundler |
| [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) | 2 | 2 | 1 | 2 | 2 | 9 | Add → MCP | Official servers |
| [OBS Studio](https://obsproject.com/) | 1 | 2 | 2 | 2 | 2 | 9 | Add → Pitch & Demo | Chronolapse, demo recording |
| [Better Auth](https://www.better-auth.com/) | 2 | 2 | 1 | 2 | 1 | 8 | Add → Auth | OSS auth |
| [Turso](https://turso.tech/) | 2 | 2 | 1 | 2 | 1 | 8 | Add → Database | Edge SQLite |
| [Penpot](https://penpot.app/) | 1 | 2 | 1 | 2 | 2 | 8 | Add → Design | Adobe XD |
| [AI Design Guide: Design Systems](https://www.aidesign.guide/design-systems) | 2 | 2 | 1 | 1 | 2 | 8 | Add → Design | Agent-readable UI kits; promoted from watchlist after user review |
| [unDraw](https://undraw.co/) | 2 | 2 | 1 | 2 | 1 | 8 | Add → Illustrations | Popsy |
| [Loom](https://www.loom.com/) | 2 | 1 | 2 | 2 | 1 | 8 | Add → Pitch & Demo | Quick demo videos |
| [Gamma](https://gamma.app/) | 2 | 1 | 2 | 2 | 1 | 8 | Add → Pitch & Demo | AI pitch decks |
| [Replit](https://replit.com/) | 2 | 1 | 1 | 2 | 1 | 7 | Add → AI Dev Tools | Glitch-style in-browser IDE |
| [Playwright](https://playwright.dev/) | 1 | 2 | 0 | 2 | 2 | 7 | Add → Testing | Modern E2E tests |
| [tldraw](https://www.tldraw.com/) | 2 | 2 | 0 | 2 | 0 | 6 | Watchlist | Excalidraw and Miro already cover it |
| [Beeceptor](https://beeceptor.com/) | 2 | 1 | 0 | 2 | 1 | 6 | Watchlist | Mocky; Mockoon/JSONPlaceholder cover it |
| [PocketBase](https://pocketbase.io/) | – | – | – | – | – | – | Hold | GitHub repo archived with no stated move |
| [create-t3-app](https://create.t3.gg/) | 2 | 2 | 1 | 1 | 1 | 7 | Hold | No commits since Dec 2025 |

**Descriptions rewritten** to say what the tool does and what it costs: Cursor, OpenAI API (now marked paid), Firebase Functions (needs Blaze plan), ydata-profiling (renamed from Pandas Profiling), Supabase, AWS Lambda, Cloudflare Workers, v0, Next.js, gbdk-2020, Autodraw, React Native.

### 2026-11-15 · Curator's Picks verification

Every pick was re-checked rather than taken from its score:
- **Open source** (Shadcn UI, Next.js, Tailwind CSS, Supabase, Expo, Excalidraw, Lucide, Magic UI, Godot, Phaser, LDtk, BeepBox, Gradio, Ollama, Public APIs, ScreenToGif, OBS Studio, Hallmark): none archived, all pushed between Aug and Nov 2026, all MIT, ISC, Apache-2.0, GPL-2.0 or MS-PL.
- **Hosted, checked on pricing pages:** Vercel Hobby is free and can deploy without an account; Supabase has a free plan whose projects pause when inactive; Expo SDK is MIT and its free plan includes 15 Android and 15 iOS builds; itch.io lets you set a $0 price; Kaggle Datasets are free; Google AI Studio, OpenRouter and Stripe test mode were verified earlier.
- **Fixes:** Expo moved from "Ship it live" to its own "Go mobile" row; ScreenToGif marked Windows-only; the intro now says the picks are hand-picked from the 9–10 scorers rather than "the highest scorers".

### 2026-11-15 · Content verification and reclassification

Every description written during this review was re-checked against its source page (pricing page, docs or README). 23 were corrected, including two that were wrong:
- **Gradio:** HF Spaces is no longer free for Gradio apps; free accounts get up to 2 Gradio Spaces on ZeroGPU.
- **Groq:** Llama models are now enterprise-only; the public models are GPT-OSS and Whisper.
- **Claims removed because the source page doesn't state them:** "no card" (Neon), "built-in database" (Replit), "built on VS Code" (Cursor), "from a screenshot" (v0), "successor to Watson" (watsonx), the Codegeist mention (Atlassian), "open-licensed" (unDraw, whose license restricts redistribution), "preview URLs" (Vercel).
- **Confirmed:** Google AI Studio free tier without billing, Cloudflare Workers 100k requests/day, AWS Lambda 1M requests/month, Firebase Functions needing Blaze, GameMaker free for non-commercial use, Unity Personal free, Streamlit Community Cloud free, Stripe test mode, MCP reference servers list, Playwright auto-wait and codegen, Penpot self-hosting, Public APIs (1,400 no-auth entries).

**Reclassified** (each entry now sits where a participant would look first):

| Resource | Moved to | Why |
|---|---|---|
| OpenAI API | AI & Machine Learning | LLM API, sits with the other model APIs |
| Swagger UI | Testing & Quality Assurance | API docs/testing tool, not a data source |
| Kaggle Datasets | APIs & Data Sources | a data source |
| Looker Studio | Data Visualization | dashboard/visualization tool |
| DBeaver Community | Database & Storage | database client |
| Draw.io | Design & UI/UX | diagramming, next to Excalidraw |
| v0 | AI Development Tools | AI app builder, next to Bolt |
| Kdenlive | Pitch & Demo | video editor for demo videos |
| ScreenToGif | Pitch & Demo | demo recording, not game marketing |
| Pixilart | Graphics & Art Tools | pixel art editor |
| Lunacy | Design & UI/UX | general design tool (Figma alternative) |
| DeepMotion | Graphics & Art Tools | 3D animation generation |
| Easy Releasy | Game Hosting & Marketing | itch.io page templates |
| APPLORE | Generators & Snippets | app icon generator |

### 2026-11-15 · Stripe re-scored (10 → 7)

Stripe's global availability page lists India as "Preview" with contact-sales signup, and other countries are unsupported, so many teams can't open an account mid-event. Most hackathon projects don't take payments either. Re-scored: Speed 1, Cost 2, Demo 1, Maturity 2, Fit 1 = 7. It stays listed with an availability note but is out of Curator's Picks.

### 2026-11-15 · Font resources

Checked live; licenses from GitHub or the site. Fontshare's site confirms free fonts but not commercial terms, so the entry doesn't claim them.

| Resource | S | C | D | M | F | Total | Decision |
|---|:-:|:-:|:-:|:-:|:-:|:-:|---|
| [Fontpair](https://fontpair.co/) | 2 | 2 | 2 | 1 | 1 | 8 | Add → Fonts |
| [Fontshare](https://www.fontshare.com/) | 2 | 2 | 2 | 2 | 1 | 9 | Add → Fonts |
| [Fontsource](https://fontsource.org/) | 2 | 2 | 1 | 2 | 2 | 9 | Add → Fonts |
| [Google Fonts](https://fonts.google.com/) | 2 | 2 | 2 | 2 | 2 | 10 | Add → Fonts |
| [Inter](https://rsms.me/inter/) | 2 | 2 | 2 | 2 | 1 | 9 | Add → Fonts |
| [Typescale](https://typescale.com/) | 2 | 2 | 1 | 1 | 2 | 8 | Add → Fonts |
| [Fontjoy](https://fontjoy.com/) | 2 | 2 | 2 | 1 | 0 | 7 | Watchlist: Fontpair covers pairing |
| [Font Squirrel](https://www.fontsquirrel.com/) | 2 | 2 | 2 | 2 | 0 | 8 | Watchlist: overlaps Google Fonts and Fontshare |
| [Bunny Fonts](https://fonts.bunny.net/) | 2 | 2 | 1 | 2 | 0 | 7 | Watchlist: GDPR mirror of Google Fonts |
| [Monaspace](https://monaspace.githubnext.com/) | 2 | 2 | 0 | 2 | 0 | 6 | Reject: code font, invisible in demos |
| [JetBrains Mono](https://www.jetbrains.com/lp/mono/) | 2 | 2 | 0 | 2 | 0 | 6 | Reject: code font, invisible in demos |

### 2026-11-15 · Coding agent skills, plugins and MCP servers (from the owner's installed setup)

Candidates came from the owner's installed Claude Code skills, plugins, MCP servers and global CLIs. Only tools with a public source were considered; local or private ones (custom MCP servers, local plugins) and anything outside the hackathon scope (business-ops skill suites) were skipped. Each repo was checked on GitHub for license, stars and activity, and each hosted tool's free plan on its pricing page. Hallmark and Taste Skill moved into the new section.

| Resource | S | C | D | M | F | Total | Decision |
|---|:-:|:-:|:-:|:-:|:-:|:-:|---|
| [Superpowers](https://github.com/obra/superpowers) | 2 | 2 | 1 | 2 | 2 | 9 | Add |
| [Impeccable](https://github.com/pbakaus/impeccable) | 2 | 2 | 2 | 2 | 1 | 9 | Add |
| [skills.sh](https://skills.sh/) | 2 | 2 | 1 | 2 | 2 | 9 | Add |
| [Claude Code Plugins (official)](https://github.com/anthropics/claude-plugins-official) | 2 | 2 | 1 | 2 | 2 | 9 | Add |
| [Hackathon Playbook](https://github.com/SidTheKid-dotcom/hackathon-playbook) | 2 | 2 | 2 | 0 | 2 | 8 | Add |
| [Ponytail](https://github.com/DietrichGebert/ponytail) | 2 | 2 | 1 | 2 | 1 | 8 | Add |
| [Planning with Files](https://github.com/OthmanAdi/planning-with-files) | 2 | 2 | 1 | 2 | 1 | 8 | Add |
| [wshobson/agents](https://github.com/wshobson/agents) | 2 | 2 | 1 | 2 | 1 | 8 | Add |
| [DeepWiki MCP](https://docs.devin.ai/work-with-devin/deepwiki-mcp) | 2 | 2 | 1 | 2 | 2 | 9 | Add |
| [Context7](https://context7.com/) | 2 | 1 | 1 | 2 | 2 | 8 | Add |
| [Pi](https://github.com/earendil-works/pi) | 2 | 2 | 1 | 2 | 1 | 8 | Add |
| [VoltAgent subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) | 2 | 2 | 1 | 2 | 0 | 7 | Watchlist: overlaps wshobson/agents |
| [Agentic Awesome Skills](https://github.com/sickn33/agentic-awesome-skills) | 1 | 2 | 1 | 2 | 1 | 7 | Watchlist: 2,955 skills is a lot to browse mid-event |
| [Codex plugin for Claude Code](https://github.com/openai/codex-plugin-cc) | 2 | 1 | 0 | 2 | 1 | 6 | Watchlist: needs an OpenAI account |
| [Agent-Reach](https://github.com/Panniantong/Agent-Reach) | 1 | 2 | 0 | 2 | 1 | 6 | Watchlist: research tool, not a build tool |
| [Exa MCP](https://github.com/exa-labs/exa-mcp-server) | 2 | 1 | 0 | 2 | 1 | 6 | Watchlist |
| [OpenDia](https://github.com/aeonfun/opendia) | 1 | 2 | 0 | 1 | 1 | 5 | Reject |
| [Stitch](https://stitch.withgoogle.com/) | – | – | – | – | – | – | Hold: free terms could not be confirmed |
| [Anthropic Skills](https://github.com/anthropics/skills) | – | – | – | – | – | – | Hold: no license file at repo root |

Hackathon Playbook scores Maturity 0 (1 star, one maintainer) but totals 8, so it's in by the rubric and its entry says it's new.

## Watchlist

- **[ascii-reveal](https://github.com/quanhoangindex/ascii-reveal)** - Character-grid decode effect for React loading states. Promote once it has more users and releases.
- **[posts.design](https://posts.design)** - Social post and OG image inspiration. Promote if launch or announcement assets get their own section.
- **[The AI Design Guide](https://aidesign.guide)** - Weekly agentic design guides (its Design Systems directory is already listed). Promote if the guides become a free standalone resource.
- **[tldraw](https://www.tldraw.com/)** - Infinite canvas whiteboard. Promote if Excalidraw falls short.
- **[Beeceptor](https://beeceptor.com/)** - Hosted mock API, 50 requests/day free. Promote if a hosted mock is needed beyond Mockoon.
- **[PocketBase](https://pocketbase.io/)** - Single-file backend. Re-check why the repo was archived.


### Moved out of the README · 2026-11-15

88 entries scored under 7 or failed the free-to-use gate. Kept here verbatim so any can be restored by pasting the line back into its section once it re-scores 7+.


**AI & Machine Learning**

- **[IBM watsonx](https://www.ibm.com/products/watsonx)** ⚪ `5` - IBM's enterprise AI portfolio for building AI apps, managing data and governing models
- **[OpenAI API](https://developers.openai.com/api/docs/concepts)** ⚪ `7` - GPT models for text, vision, audio and agents (paid, usage-based)

**AI Development Tools**

- **[Claude Code](https://code.claude.com/docs/en/overview)** ⚪ `7` - Agentic coding tool from Anthropic that operates in the terminal
- **[Devin Desktop (formerly Windsurf)](https://devin.ai/desktop)** ⚪ `5` - Cognition's editor and command center for running coding agents locally or in the cloud

**APIs & Data Sources**

- **[CurlShot](https://curlshot.com/)** ⚪ `5` - Screenshot API: one GET request turns a URL into PNG, JPEG, WebP or PDF (POST for raw HTML), free plan of 100 screenshots/month
- **[RapidAPI](https://rapidapi.com/)** ⚪ `6` - API marketplace to quickly find and test external APIs
- **[SheetDB](https://sheetdb.io/)** ⚪ `6` - Turns Google Sheets into a REST API for quick MVP data handling

**Authentication & User Management**

- **[Auth0](https://auth0.com/)** ⚪ `6` - Authentication service with social and passwordless login support
- **[Firebase Anonymous Auth](https://firebase.google.com/docs/auth/web/anonymous-auth)** ⚪ `6` - Quick setup for user tracking without full sign-up
- **[Magic Link](https://magic.link/)** ⚪ `5` - Passwordless login with email, frictionless user authentication
- **[NextAuth.js](https://next-auth.js.org/)** ⚪ `5` - Authentication for Next.js applications
- **[SuperTokens](https://supertokens.com/)** ⚪ `5` - Open-source authentication with pre-built integrations

**Backend Development**

- **[ASP.NET](https://learn.microsoft.com/en-us/aspnet/core/)** ⚪ `5` - Robust Microsoft framework for modern web applications and APIs
- **[Firebase Functions](https://firebase.google.com/docs/functions)** ⚪ `4` - Serverless functions triggered by Firebase events or HTTP; requires the pay-as-you-go Blaze plan
- **[Manifest](https://manifest.build)** ⚪ `6` - Instant Headless CMS / Micro-backend in 1 file

**Browser Extensions & Dev Tools**

- **[CSSViewer](https://chromewebstore.google.com/detail/cssviewer/ggfgijbpiheegefliciemofobhmofgce)** ⚪ `5` - Simple CSS property viewer
- **[WhatFont](https://chromewebstore.google.com/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm)** ⚪ `6` - Easiest way to identify fonts on web pages

**Collaboration & Communication**

- **[Coda](https://coda.io/)** ⚪ `5` - Document tool blending text and tables for project tracking
- **[Slack](https://slack.com/)** ⚪ `5` - Communication tool with channels for team coordination
- **[Trello](https://trello.com/)** ⚪ `6` - Kanban-style board for task tracking

**Cybersecurity Tools**

- **[Frida](https://frida.re/)** ⚪ `6` - Reverse engineering tool for Android and Windows applications
- **[Metasploit](https://www.metasploit.com/)** ⚪ `6` - Tool for penetration testing by cybersecurity professionals
- **[OWASP ZAP](https://www.zaproxy.org/)** ⚪ `6` - Open-source web application security scanner
- **[Sudomy](https://github.com/Screetsec/Sudomy)** ⚪ `4` - Subdomain enumeration tool for reconnaissance
- **[Wfuzz](https://github.com/xmendez/wfuzz)** ⚪ `4` - Web application fuzz testing CLI tool
- **[Wireshark](https://www.wireshark.org/)** ⚪ `6` - Network protocol analyzer for debugging

**Data Visualization**

- **[ToolKnit CSV Chart Maker](https://toolknit.com/tools/chart-maker.html)** ⚪ `6` - Turn pasted CSV into charts for a demo or pitch, with editable labels and PNG or interactive HTML export

**Database & Storage**

- **[Prisma Postgres](https://www.prisma.io/postgres)** ⚪ `6` - Managed PostgreSQL with free plan and zero cold starts

**Deployment & Hosting**

- **[AWS Lambda Free Tier](https://aws.amazon.com/lambda/pricing/)** ⚪ `3` - Event-driven serverless functions, 1M free requests per month
- **[deed.page](https://deed.page/)** ⚪ `6` - Publish a static demo to a permanent HTTPS URL with one `curl` PUT, no account; free plan, MCP server for AI agents
- **[Google Cloud Functions Free Tier](https://cloud.google.com/functions/pricing)** ⚪ `3` - Serverless functions
- **[Prisma Compute](https://www.prisma.io/compute)** ⚪ `5` - Host TypeScript apps next to Prisma Postgres, 1M requests/month free
- **[Vercel Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions)** ⚪ `6` - Built-in serverless functions

**Design & UI/UX**

- **[GIMP](https://www.gimp.org/)** ⚪ `6` - Open-source image editor comparable to Photoshop
- **[Lunacy](https://icons8.com/lunacy)** ⚪ `5` - Free design alternative to Figma
- **[ProtoPie](https://www.protopie.io/)** ⚪ `4` - Intuitive prototyping tool for interactive mockups
- **[Whimsical](https://whimsical.com/)** ⚪ `6` - Drag-and-drop wireframing tool for quick prototyping

**Fonts**

- **[Onest](https://github.com/simpals/onest)** ⚪ `6` - Geometric and humanistic font blend

**Icons**

- **[FaviconDL](https://favicondl.com/)** ⚪ `5` - Free favicon extractor and no-key API: extract available ICO/PNG/SVG/Apple touch icons and preserve their original size when possible
- **[SVGicons](https://svgicons.com/)** ⚪ `6` - Search and preview open-source SVG icon sets, with copyable SVG and per-set license information

**Illustrations**

- **[404 Illustrations (Error404.fun)](https://error404.fun)** ⚪ `5` - Royalty free illustrations for 404 pages
- **[404 Illustrations (Kapwing)](https://www.kapwing.com/404-illustrations)** ⚪ `6` - Hand-crafted collection for 404 pages
- **[SVG Illustrations](https://lukaszadam.com/illustrations)** ⚪ `6` - Free SVG Illustrations

**Frontend Development**

- **[Parcel](https://parceljs.org/)** ⚪ `5` - Zero-config bundler for quick app setup

**Game Engines**

- **[GameMaker](https://gamemaker.io/en)** ⚪ `6` - 2D game engine, free for non-commercial use
- **[Heaps](https://heaps.io/)** ⚪ `4` - Mature cross platform graphics engine designed for high performance games
- **[Unreal Engine](https://www.unrealengine.com/)** ⚪ `6` - Powerful engine with a steep learning curve, great for high-quality 3D games

**Frameworks**

- **[CraftyJS](https://craftyjs.com/)** ⚪ `4` - Free and lightweight JavaScript framework for 2D games
- **[libGDX](https://libgdx.com/)** ⚪ `6` - Cross-platform Java game development framework based on OpenGL
- **[olcPixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine)** ⚪ `5` - Open source single-file prototyping and game-engine framework in C++
- **[Pixelbox.js](https://pixwlk.itch.io/pixelbox)** ⚪ `5` - Lightweight Javascript engine for browser games

**Game Development Tools**

- **[Clickteam Fusion](https://www.clickteam.com/clickteam-fusion-2-5-free-edition)** ⚪ `4` - Easy to use game engine for beginners
- **[gbdk-2020](https://github.com/gbdk-2020/gbdk-2020)** ⚪ `5` - C toolchain for Game Boy games (plus a few other retro consoles), handy for retro-themed jams

**Online Services**

- **[YogurtTheHorse Leaderboards](https://github.com/YogurtTheHorse/highscores)** ⚪ `4` - Free to use leaderboards with open-source server side

**Audio Tools**

- **[FamiStudio](https://famistudio.org/)** ⚪ `6` - Simple music editor for NES/Famicom chiptunes
- **[LMMS](https://lmms.io/)** ⚪ `5` - Free cross-platform alternative to commercial programs like FL Studio
- **[MuseScore](https://musescore.org/)** ⚪ `6` - Create, play and print beautiful sheet music
- **[Tonnoform](https://nikos1001.github.io/Tonnoform/)** ⚪ `5` - Easy to use open-source 8 bit music making tool
- **[Tracktion Waveform Free](https://www.tracktion.com/products/waveform-free)** ⚪ `5` - Free, cross-platform and intuitive audio workstation

**Graphics & Art Tools**

- **[BulkPicTools](https://bulkpictools.com/)** ⚪ `6` - Free browser-based bulk image processor. Compress, convert (HEIC/WebP/AVIF/PNG/JPG), resize, crop, and watermark 1,000+ images at once — no upload, no account, works offline. Perfect for quickly optimizing demo screenshots and pitch deck assets.
- **[DeepMotion](https://www.deepmotion.com/)** ⚪ `6` - Text to 3D animation and Video to 3D animation app
- **[FireAlpaca](http://firealpaca.com/)** ⚪ `5` - Free digital painting software for Mac and Windows
- **[Pixilart](https://www.pixilart.com/)** ⚪ `6` - Free browser-based pixel art app
- **[Pyxel Edit](https://pyxeledit.com/)** ⚪ `3` - Pixel art drawing application designed for working with tiles

**Color & Design Resources**

- **[Autodraw](https://www.autodraw.com/)** ⚪ `6` - Turns rough doodles into clean drawings using AI
- **[Flat UI Colors 2](https://flatuicolors.com/)** ⚪ `6` - 280 handpicked colors split into 13 palettes
- **[Smart upscaler](https://icons8.com/upscaler)** ⚪ `5` - Enlarge and enhance images automatically using AI
- **[ZzArt](https://zzart.3d2k.com/)** ⚪ `6` - Evolve HD textures for use in your games
- **[ZzSprite](https://killedbyapixel.github.io/ZzSprite/)** ⚪ `6` - Procedurally generate tiny pixel art sprites

**Game Design & Management**

- **[Machinations](https://machinations.io/)** ⚪ `5` - Free online tool to prototype the internal economy of your game

**Game Hosting & Marketing**

- **[Easy Releasy](https://lemoncosmos.itch.io/easy-releasy)** ⚪ `6` - Template pack to create itch.io pages

**Generators & Snippets**

- **[APPLORE](https://applore.app/app-icon-generator)** ⚪ `6` - Free app icon export in every iOS, Android and web size, no sign-up
- **[Gradiently](https://gradienty.codes)** ⚪ `5` - Tailwind Gradient Generator for stunning visuals
- **[Scrollbar.app](https://scrollbar.app)** ⚪ `4` - Simple CSS scrollbar editor

**Inspiration & Ideas**

- **[CodeTrendy](https://codetrendy.com/)** ⚪ `5` - Curated directory of newly launched startups, SaaS and AI tools to browse for project ideas, with a free read-only MCP server
- **[HACKERS](https://hackers.pocketplay.win/en/)** ⚪ `6` - Live Devpost hackathons and Kaggle competitions ranked by a beginner score, with deadlines and first-timer guides
- **[Saaspo](https://saaspo.com/)** ⚪ `6` - Best SaaS web design inspiration
- **[saasui.design](https://saasui.design/)** ⚪ `4` - Top-tier SaaS application designs showcase
- **[ScreensDesign (formerly SCRNSHTS)](https://screensdesign.com/store-screenshots/)** ⚪ `4` - Hand-picked collection of app store design screenshots

**MCP Servers/Tools**

- **[GhidraMCP](https://github.com/LaurieWired/GhidraMCP)** ⚪ `5` - Model Context Protocol server for LLM reverse engineering
- **[MCP-Hydra](https://github.com/HappyHackingSpace/mcp-hydra)** ⚪ `4` - Cybersecurity toolkit connecting AI assistants to security tools
- **[MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan)** ⚪ `6` - MCP Security Scanner

**Mobile Development**

- **[Ionic](https://ionicframework.com/)** ⚪ `6` - Hybrid app framework using web technologies
- **[React Native](https://reactnative.dev/)** ⚪ `6` - Native iOS and Android apps in React; pair with Expo for the fastest setup

**Testing & Quality Assurance**

- **[Cypress](https://www.cypress.io/)** ⚪ `5` - JavaScript end-to-end testing framework
- **[Postman](https://www.postman.com/)** ⚪ `6` - API testing tool with intuitive interface
- **[Selenium IDE](https://www.selenium.dev/selenium-ide/)** ⚪ `5` - Browser extension for creating UI tests
- **[Swagger UI](https://swagger.io/)** ⚪ `6` - Tool for automatically documenting and testing REST APIs

**Removed 2026-11-15 at owner's request** (payments-only use, country-limited signup):

- **[Stripe test mode](https://docs.stripe.com/testing)** 🟡 `7` - Sandbox payments with test cards for demoing a checkout flow without moving money; only for projects that take payments, and signup is limited by country (India is in invite-only preview)

## Full scorecard

Every README entry, scored 2026-11-15 (242 entries). S = Speed, C = Cost, D = Demo impact, M = Maturity, F = Fit.

### Moved to watchlist

88 entries score under 7 or fail the *usable free* gate. Per section 3 they belong on the watchlist or out of the list; they were moved out of the README on 2026-11-15 (see Watchlist).

| Resource | Section | Total | Note |
|---|---|:-:|---|
| [AWS Lambda Free Tier](https://aws.amazon.com/lambda/pricing/) | Deployment & Hosting | 3 | card required |
| [Google Cloud Functions Free Tier](https://cloud.google.com/functions/pricing) | Deployment & Hosting | 3 | card required |
| [Pyxel Edit](https://pyxeledit.com/) | Graphics & Art Tools | 3 | paid |
| [Clickteam Fusion](https://www.clickteam.com/clickteam-fusion-2-5-free-edition) | Game Development Tools | 4 | score below 7 |
| [CraftyJS](https://craftyjs.com/) | Frameworks | 4 | score below 7 |
| [Firebase Functions](https://firebase.google.com/docs/functions) | Backend Development | 4 | card required (Blaze) |
| [Heaps](https://heaps.io/) | Game Engines | 4 | score below 7 |
| [MCP-Hydra](https://github.com/HappyHackingSpace/mcp-hydra) | MCP Servers/Tools | 4 | score below 7 |
| [ProtoPie](https://www.protopie.io/) | Design & UI/UX | 4 | score below 7 |
| [saasui.design](https://saasui.design/) | Inspiration & Ideas | 4 | score below 7 |
| [ScreensDesign (formerly SCRNSHTS)](https://screensdesign.com/store-screenshots/) | Inspiration & Ideas | 4 | score below 7 |
| [Scrollbar.app](https://scrollbar.app) | Generators & Snippets | 4 | score below 7 |
| [Sudomy](https://github.com/Screetsec/Sudomy) | Cybersecurity Tools | 4 | score below 7 |
| [Wfuzz](https://github.com/xmendez/wfuzz) | Cybersecurity Tools | 4 | score below 7 |
| [YogurtTheHorse Leaderboards](https://github.com/YogurtTheHorse/highscores) | Online Services | 4 | score below 7 |
| [404 Illustrations (Error404.fun)](https://error404.fun) | Illustrations | 5 | score below 7 |
| [ASP.NET](https://learn.microsoft.com/en-us/aspnet/core/) | Backend Development | 5 | score below 7 |
| [Coda](https://coda.io/) | Collaboration & Communication | 5 | score below 7 |
| [CodeTrendy](https://codetrendy.com/) | Inspiration & Ideas | 5 | score below 7 |
| [CSSViewer](https://chromewebstore.google.com/detail/cssviewer/ggfgijbpiheegefliciemofobhmofgce) | Browser Extensions & Dev Tools | 5 | score below 7 |
| [CurlShot](https://curlshot.com/) | APIs & Data Sources | 5 | score below 7 |
| [Cypress](https://www.cypress.io/) | Testing & Quality Assurance | 5 | score below 7 |
| [Devin Desktop (formerly Windsurf)](https://devin.ai/desktop) | AI Development Tools | 5 | pricing unclear |
| [FaviconDL](https://favicondl.com/) | Icons | 5 | score below 7 |
| [FireAlpaca](http://firealpaca.com/) | Graphics & Art Tools | 5 | score below 7 |
| [gbdk-2020](https://github.com/gbdk-2020/gbdk-2020) | Game Development Tools | 5 | score below 7 |
| [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | MCP Servers/Tools | 5 | score below 7 |
| [Gradiently](https://gradienty.codes) | Generators & Snippets | 5 | score below 7 |
| [IBM watsonx](https://www.ibm.com/products/watsonx) | AI & Machine Learning | 5 | score below 7 |
| [LMMS](https://lmms.io/) | Audio Tools | 5 | score below 7 |
| [Lunacy](https://icons8.com/lunacy) | Game Design & Management | 5 | score below 7 |
| [Machinations](https://machinations.io/) | Game Design & Management | 5 | score below 7 |
| [Magic Link](https://magic.link/) | Authentication & User Management | 5 | score below 7 |
| [NextAuth.js](https://next-auth.js.org/) | Authentication & User Management | 5 | score below 7 |
| [olcPixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine) | Frameworks | 5 | score below 7 |
| [Parcel](https://parceljs.org/) | Frontend Development | 5 | score below 7 |
| [Pixelbox.js](https://pixwlk.itch.io/pixelbox) | Frameworks | 5 | score below 7 |
| [Prisma Compute](https://www.prisma.io/compute) | Deployment & Hosting | 5 | score below 7 |
| [Selenium IDE](https://www.selenium.dev/selenium-ide/) | Testing & Quality Assurance | 5 | score below 7 |
| [Slack](https://slack.com/) | Collaboration & Communication | 5 | score below 7 |
| [Smart upscaler](https://icons8.com/upscaler) | Color & Design Resources | 5 | score below 7 |
| [SuperTokens](https://supertokens.com/) | Authentication & User Management | 5 | score below 7 |
| [Tonnoform](https://nikos1001.github.io/Tonnoform/) | Audio Tools | 5 | score below 7 |
| [Tracktion Waveform Free](https://www.tracktion.com/products/waveform-free) | Audio Tools | 5 | score below 7 |
| [404 Illustrations (Kapwing)](https://www.kapwing.com/404-illustrations) | Illustrations | 6 | score below 7 |
| [APPLORE](https://applore.app/app-icon-generator) | Design & UI/UX | 6 | score below 7 |
| [Auth0](https://auth0.com/) | Authentication & User Management | 6 | score below 7 |
| [Autodraw](https://www.autodraw.com/) | Color & Design Resources | 6 | score below 7 |
| [BulkPicTools](https://bulkpictools.com/) | Graphics & Art Tools | 6 | score below 7 |
| [deed.page](https://deed.page/) | Deployment & Hosting | 6 | score below 7 |
| [DeepMotion](https://www.deepmotion.com/) | Game Hosting & Marketing | 6 | score below 7 |
| [Easy Releasy](https://lemoncosmos.itch.io/easy-releasy) | Color & Design Resources | 6 | score below 7 |
| [FamiStudio](https://famistudio.org/) | Audio Tools | 6 | score below 7 |
| [Firebase Anonymous Auth](https://firebase.google.com/docs/auth/web/anonymous-auth) | Authentication & User Management | 6 | score below 7 |
| [Flat UI Colors 2](https://flatuicolors.com/) | Color & Design Resources | 6 | score below 7 |
| [Frida](https://frida.re/) | Cybersecurity Tools | 6 | score below 7 |
| [GameMaker](https://gamemaker.io/en) | Game Engines | 6 | score below 7 |
| [GIMP](https://www.gimp.org/) | Design & UI/UX | 6 | score below 7 |
| [HACKERS](https://hackers.pocketplay.win/en/) | Inspiration & Ideas | 6 | score below 7 |
| [Ionic](https://ionicframework.com/) | Mobile Development | 6 | score below 7 |
| [libGDX](https://libgdx.com/) | Frameworks | 6 | score below 7 |
| [Manifest](https://manifest.build) | Backend Development | 6 | score below 7 |
| [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) | MCP Servers/Tools | 6 | score below 7 |
| [Metasploit](https://www.metasploit.com/) | Cybersecurity Tools | 6 | score below 7 |
| [MuseScore](https://musescore.org/) | Audio Tools | 6 | score below 7 |
| [Onest](https://github.com/simpals/onest) | Fonts | 6 | score below 7 |
| [OWASP ZAP](https://www.zaproxy.org/) | Cybersecurity Tools | 6 | score below 7 |
| [Pixilart](https://www.pixilart.com/) | Design & UI/UX | 6 | score below 7 |
| [Postman](https://www.postman.com/) | Testing & Quality Assurance | 6 | score below 7 |
| [Prisma Postgres](https://www.prisma.io/postgres) | Database & Storage | 6 | score below 7 |
| [RapidAPI](https://rapidapi.com/) | APIs & Data Sources | 6 | score below 7 |
| [React Native](https://reactnative.dev/) | Mobile Development | 6 | score below 7 |
| [Saaspo](https://saaspo.com/) | Inspiration & Ideas | 6 | score below 7 |
| [SheetDB](https://sheetdb.io/) | APIs & Data Sources | 6 | score below 7 |
| [SVG Illustrations](https://lukaszadam.com/illustrations) | Illustrations | 6 | score below 7 |
| [SVGicons](https://svgicons.com/) | Icons | 6 | score below 7 |
| [Swagger UI](https://swagger.io/) | APIs & Data Sources | 6 | score below 7 |
| [ToolKnit CSV Chart Maker](https://toolknit.com/tools/chart-maker.html) | Data Visualization | 6 | score below 7 |
| [Trello](https://trello.com/) | Collaboration & Communication | 6 | score below 7 |
| [Unreal Engine](https://www.unrealengine.com/) | Game Engines | 6 | score below 7 |
| [Vercel Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions) | Deployment & Hosting | 6 | score below 7 |
| [WhatFont](https://chromewebstore.google.com/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm) | Browser Extensions & Dev Tools | 6 | score below 7 |
| [Whimsical](https://whimsical.com/) | Design & UI/UX | 6 | score below 7 |
| [Wireshark](https://www.wireshark.org/) | Cybersecurity Tools | 6 | score below 7 |
| [ZzArt](https://zzart.3d2k.com/) | Color & Design Resources | 6 | score below 7 |
| [ZzSprite](https://killedbyapixel.github.io/ZzSprite/) | Color & Design Resources | 6 | score below 7 |
| [Claude Code](https://code.claude.com/docs/en/overview) | AI Development Tools | 7 | paid |
| [OpenAI API](https://developers.openai.com/api/docs/concepts) | APIs & Data Sources | 7 | paid, usage-based |

### All entries


**AI & Machine Learning**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Google AI Studio](https://aistudio.google.com/) | 2 | 2 | 2 | 2 | 2 | 🟢 10 |
| [Google Colab](https://colab.research.google.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Gradio](https://www.gradio.app/) | 2 | 2 | 2 | 2 | 2 | 🟢 10 |
| [Groq](https://console.groq.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Hugging Face Transformers](https://huggingface.co/docs/transformers/) | 1 | 2 | 1 | 2 | 2 | 🟡 8 |
| [IBM watsonx](https://www.ibm.com/products/watsonx) | 0 | 1 | 1 | 2 | 1 | ⚪ 5 |
| [Ollama](https://ollama.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [OpenRouter](https://openrouter.ai/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Replicate](https://replicate.com/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Runway](https://runway.com/) | 2 | 1 | 2 | 1 | 1 | 🟡 7 |
| [Streamlit](https://streamlit.io/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Teachable Machine](https://teachablemachine.withgoogle.com/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Vercel AI SDK](https://ai-sdk.dev/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |

**AI Development Tools**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Bolt](https://bolt.new/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Claude Code](https://code.claude.com/docs/en/overview) | 2 | 0 | 1 | 2 | 2 | 🟡 7 |
| [Cursor](https://www.cursor.com/) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [Devin Desktop (formerly Windsurf)](https://devin.ai/desktop) | 2 | 0 | 1 | 2 | 0 | ⚪ 5 |
| [GitHub Copilot](https://github.com/features/copilot) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [Hallmark](https://usehallmark.com) | 2 | 2 | 2 | 1 | 2 | 🟢 9 |
| [Replit](https://replit.com/) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [Taste Skill](https://tasteskill.dev) | 2 | 2 | 2 | 1 | 2 | 🟢 9 |

**APIs & Data Sources**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [CoinGecko](https://docs.coingecko.com/) | 2 | 2 | 1 | 1 | 1 | 🟡 7 |
| [CurlShot](https://curlshot.com/) | 2 | 1 | 1 | 0 | 1 | ⚪ 5 |
| [JsonPlaceholder](https://jsonplaceholder.typicode.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Mapbox](https://www.mapbox.com/) | 1 | 1 | 2 | 2 | 2 | 🟡 8 |
| [Mockaroo](https://www.mockaroo.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [NewsAPI](https://newsapi.org/) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [OpenAI API](https://developers.openai.com/api/docs/concepts) | 2 | 0 | 1 | 2 | 2 | 🟡 7 |
| [Public APIs](https://github.com/public-apis/public-apis) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [RapidAPI](https://rapidapi.com/) | 2 | 1 | 0 | 2 | 1 | ⚪ 6 |
| [SheetDB](https://sheetdb.io/) | 2 | 1 | 1 | 1 | 1 | ⚪ 6 |
| [Stripe test mode](https://docs.stripe.com/testing) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |
| [Swagger UI](https://swagger.io/) | 1 | 2 | 0 | 2 | 1 | ⚪ 6 |
| [Twilio](https://www.twilio.com/) | 1 | 1 | 2 | 2 | 1 | 🟡 7 |

**Authentication & User Management**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Auth0](https://auth0.com/) | 1 | 2 | 1 | 2 | 0 | ⚪ 6 |
| [Better Auth](https://www.better-auth.com/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Clerk](https://clerk.com/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Firebase Anonymous Auth](https://firebase.google.com/docs/auth/web/anonymous-auth) | 2 | 2 | 0 | 2 | 0 | ⚪ 6 |
| [Firebase Auth](https://firebase.google.com/products/auth) | 2 | 2 | 1 | 2 | 0 | 🟡 7 |
| [Magic Link](https://magic.link/) | 2 | 1 | 1 | 1 | 0 | ⚪ 5 |
| [NextAuth.js](https://next-auth.js.org/) | 1 | 2 | 1 | 1 | 0 | ⚪ 5 |
| [SuperTokens](https://supertokens.com/) | 1 | 2 | 1 | 1 | 0 | ⚪ 5 |

**Backend Development**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [ASP.NET](https://learn.microsoft.com/en-us/aspnet/core/) | 0 | 2 | 0 | 2 | 1 | ⚪ 5 |
| [Convex](https://www.convex.dev/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Express.js](https://expressjs.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [FastAPI](https://fastapi.tiangolo.com/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Firebase Functions](https://firebase.google.com/docs/functions) | 2 | 0 | 0 | 2 | 0 | ⚪ 4 |
| [Flask](https://flask.palletsprojects.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Hasura](https://hasura.io/) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [Manifest](https://manifest.build) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |

**Blockchain & Web3**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Alchemy](https://www.alchemy.com/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Infura](https://infura.io/) | 2 | 2 | 1 | 2 | 0 | 🟡 7 |
| [MetaMask](https://metamask.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Moralis](https://moralis.com/) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [Remix IDE](https://remix.ethereum.org/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |

**Browser Extensions & Dev Tools**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [ColorZilla](https://chromewebstore.google.com/detail/colorzilla/bhlhnicpbhignbdhedgjhgdocnmhomnp) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [CSSViewer](https://chromewebstore.google.com/detail/cssviewer/ggfgijbpiheegefliciemofobhmofgce) | 2 | 2 | 0 | 1 | 0 | ⚪ 5 |
| [React Developer Tools](https://chromewebstore.google.com/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [WhatFont](https://chromewebstore.google.com/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm) | 2 | 2 | 0 | 1 | 1 | ⚪ 6 |

**Collaboration & Communication**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Coda](https://coda.io/) | 2 | 1 | 0 | 1 | 1 | ⚪ 5 |
| [Discord](https://discord.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [HackMD](https://hackmd.io/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Miro](https://miro.com/) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [Notion](https://www.notion.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Slack](https://slack.com/) | 2 | 1 | 0 | 2 | 0 | ⚪ 5 |
| [Trello](https://trello.com/) | 2 | 2 | 0 | 2 | 0 | ⚪ 6 |

**Cybersecurity Tools**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Burp Suite Community](https://portswigger.net/burp) | 1 | 2 | 0 | 2 | 2 | 🟡 7 |
| [Frida](https://frida.re/) | 1 | 2 | 0 | 2 | 1 | ⚪ 6 |
| [Metasploit](https://www.metasploit.com/) | 1 | 2 | 0 | 2 | 1 | ⚪ 6 |
| [Nmap](https://nmap.org/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Nuclei](https://docs.projectdiscovery.io/tools/nuclei/overview) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [OWASP ZAP](https://www.zaproxy.org/) | 1 | 2 | 0 | 2 | 1 | ⚪ 6 |
| [Sqlmap](http://sqlmap.org/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Sudomy](https://github.com/Screetsec/Sudomy) | 1 | 2 | 0 | 1 | 0 | ⚪ 4 |
| [Wfuzz](https://github.com/xmendez/wfuzz) | 1 | 2 | 0 | 1 | 0 | ⚪ 4 |
| [Wireshark](https://www.wireshark.org/) | 1 | 2 | 0 | 2 | 1 | ⚪ 6 |

**Data Engineering & Analytics**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [DBeaver Community](https://dbeaver.io/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Google BigQuery Sandbox](https://docs.cloud.google.com/bigquery/docs/sandbox) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |
| [Kaggle Datasets](https://www.kaggle.com/datasets) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Looker Studio](https://lookerstudio.google.com/) | 1 | 2 | 2 | 2 | 1 | 🟡 8 |
| [ydata-profiling](https://docs.profiling.ydata.ai/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |

**Data Visualization**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Chart.js](https://www.chartjs.org/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Draw.io](https://www.drawio.com/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Google Charts](https://developers.google.com/chart) | 2 | 2 | 2 | 1 | 0 | 🟡 7 |
| [Plotly](https://plotly.com/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Tableau Public](https://public.tableau.com/) | 1 | 2 | 2 | 2 | 1 | 🟡 8 |
| [ToolKnit CSV Chart Maker](https://toolknit.com/tools/chart-maker.html) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |

**Database & Storage**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Airtable](https://airtable.com/) | 2 | 1 | 1 | 2 | 1 | 🟡 7 |
| [Firebase Firestore](https://firebase.google.com/products/firestore) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Neon](https://neon.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Prisma Postgres](https://www.prisma.io/postgres) | 2 | 2 | 1 | 1 | 0 | ⚪ 6 |
| [Supabase](https://supabase.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Turso](https://turso.tech/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |

**Deployment & Hosting**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [AWS Lambda Free Tier](https://aws.amazon.com/lambda/pricing/) | 1 | 0 | 0 | 2 | 0 | ⚪ 3 |
| [Cloudflare Workers](https://developers.cloudflare.com/workers/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [deed.page](https://deed.page/) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |
| [GitHub Pages](https://pages.github.com/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Google Cloud Functions Free Tier](https://cloud.google.com/functions/pricing) | 1 | 0 | 0 | 2 | 0 | ⚪ 3 |
| [Netlify](https://www.netlify.com/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Prisma Compute](https://www.prisma.io/compute) | 2 | 2 | 1 | 0 | 0 | ⚪ 5 |
| [Render](https://render.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Vercel](https://vercel.com/) | 2 | 2 | 2 | 2 | 2 | 🟢 10 |
| [Vercel Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions) | 2 | 2 | 0 | 2 | 0 | ⚪ 6 |

**Design & UI/UX**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [AI Design Guide: Design Systems](https://www.aidesign.guide/design-systems) | 2 | 2 | 1 | 1 | 2 | 🟡 8 |
| [APPLORE](https://applore.app/app-icon-generator) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |
| [Atlassian Design System](https://atlassian.design/design-system) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |
| [Blender](https://www.blender.org/) | 0 | 2 | 2 | 2 | 1 | 🟡 7 |
| [Canva](https://www.canva.com/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Excalidraw](https://excalidraw.com/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Figma](https://www.figma.com/) | 1 | 1 | 2 | 2 | 1 | 🟡 7 |
| [Filee](https://filee.sh) | 2 | 2 | 1 | 1 | 2 | 🟡 8 |
| [GIMP](https://www.gimp.org/) | 1 | 2 | 1 | 2 | 0 | ⚪ 6 |
| [Kdenlive](https://kdenlive.org/) | 1 | 2 | 2 | 2 | 1 | 🟡 8 |
| [Penpot](https://penpot.app/) | 1 | 2 | 1 | 2 | 2 | 🟡 8 |
| [Pixilart](https://www.pixilart.com/) | 2 | 2 | 1 | 1 | 0 | ⚪ 6 |
| [ProtoPie](https://www.protopie.io/) | 1 | 1 | 1 | 1 | 0 | ⚪ 4 |
| [v0](https://v0.app/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Whimsical](https://whimsical.com/) | 2 | 1 | 1 | 2 | 0 | ⚪ 6 |

**Fonts**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Geist Font](https://vercel.com/font) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Onest](https://github.com/simpals/onest) | 2 | 2 | 1 | 1 | 0 | ⚪ 6 |

**Icons**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [FaviconDL](https://favicondl.com/) | 2 | 2 | 0 | 0 | 1 | ⚪ 5 |
| [Its Hover](https://itshover.com) | 2 | 2 | 2 | 1 | 2 | 🟢 9 |
| [Lucide Icons](https://lucide.dev/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Phosphor Icons](https://phosphoricons.com/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Radix Icons](https://www.radix-ui.com/icons) | 2 | 2 | 1 | 2 | 0 | 🟡 7 |
| [SVGicons](https://svgicons.com/) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |

**Illustrations**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [404 Illustrations (Error404.fun)](https://error404.fun) | 2 | 2 | 1 | 0 | 0 | ⚪ 5 |
| [404 Illustrations (Kapwing)](https://www.kapwing.com/404-illustrations) | 2 | 2 | 1 | 1 | 0 | ⚪ 6 |
| [Humaaans](https://www.humaaans.com) | 2 | 2 | 2 | 1 | 1 | 🟡 8 |
| [Open Peeps](https://www.openpeeps.com) | 2 | 2 | 2 | 1 | 1 | 🟡 8 |
| [SVG Illustrations](https://lukaszadam.com/illustrations) | 2 | 2 | 1 | 1 | 0 | ⚪ 6 |
| [unDraw](https://undraw.co/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |

**Frontend Development**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Bootstrap](https://getbootstrap.com/) | 2 | 2 | 1 | 2 | 0 | 🟡 7 |
| [Next.js](https://nextjs.org/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Parcel](https://parceljs.org/) | 2 | 2 | 0 | 1 | 0 | ⚪ 5 |
| [React](https://react.dev/) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |
| [SvelteKit](https://svelte.dev/) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |
| [Tailwind CSS](https://tailwindcss.com/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Vite](https://vite.dev/) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Vue.js](https://vuejs.org/) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |

**UI Libraries**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Amicro](https://amicro.dev) | 2 | 2 | 2 | 1 | 2 | 🟢 9 |
| [boneyard](https://boneyard.vercel.app) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [Cult UI](https://www.cult-ui.com) | 2 | 2 | 2 | 1 | 0 | 🟡 7 |
| [Magic UI](https://magicui.design) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Shadcn UI](https://ui.shadcn.com/) | 2 | 2 | 2 | 2 | 2 | 🟢 10 |
| [Skullet](https://skullet.lochie.me/) | 2 | 2 | 1 | 1 | 1 | 🟡 7 |
| [Thinking Orbs](https://www.thinkingorbs.com/) | 2 | 2 | 2 | 1 | 2 | 🟢 9 |
| [UploadCN](https://uploadcn.dev/) | 2 | 2 | 1 | 1 | 2 | 🟡 8 |

**Game Engines**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Construct 3](https://www.construct.net/en) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [GameMaker](https://gamemaker.io/en) | 1 | 1 | 2 | 2 | 0 | ⚪ 6 |
| [GDevelop](https://gdevelop.io/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Godot](https://godotengine.org/) | 1 | 2 | 2 | 2 | 2 | 🟢 9 |
| [Heaps](https://heaps.io/) | 0 | 2 | 1 | 1 | 0 | ⚪ 4 |
| [PICO-8](https://www.lexaloffle.com/pico-8.php) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Unity](https://unity.com/) | 1 | 2 | 2 | 2 | 1 | 🟡 8 |
| [Unreal Engine](https://www.unrealengine.com/) | 0 | 2 | 2 | 2 | 0 | ⚪ 6 |

**Frameworks**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [CraftyJS](https://craftyjs.com/) | 1 | 2 | 1 | 0 | 0 | ⚪ 4 |
| [libGDX](https://libgdx.com/) | 1 | 2 | 1 | 2 | 0 | ⚪ 6 |
| [LÖVE](https://love2d.org/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [olcPixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine) | 1 | 2 | 1 | 1 | 0 | ⚪ 5 |
| [Phaser](https://phaser.io/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Pixelbox.js](https://pixwlk.itch.io/pixelbox) | 2 | 2 | 1 | 0 | 0 | ⚪ 5 |
| [PyGame](https://www.pygame.org/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |

**Game Development Tools**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Clickteam Fusion](https://www.clickteam.com/clickteam-fusion-2-5-free-edition) | 1 | 1 | 1 | 1 | 0 | ⚪ 4 |
| [gbdk-2020](https://github.com/gbdk-2020/gbdk-2020) | 0 | 2 | 1 | 1 | 1 | ⚪ 5 |
| [LDtk](https://ldtk.io/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Tiled](https://www.mapeditor.org/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |

**Online Services**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Dreamlo](https://dreamlo.com/) | 2 | 2 | 1 | 1 | 1 | 🟡 7 |
| [YogurtTheHorse Leaderboards](https://github.com/YogurtTheHorse/highscores) | 1 | 2 | 1 | 0 | 0 | ⚪ 4 |

**Audio Tools**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Audacity](https://www.audacityteam.org/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [BeepBox](https://www.beepbox.co) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [bfxr](https://www.bfxr.net/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Bosca Ceoil](https://boscaceoil.net/) | 2 | 2 | 2 | 1 | 0 | 🟡 7 |
| [FamiStudio](https://famistudio.org/) | 1 | 2 | 1 | 2 | 0 | ⚪ 6 |
| [LMMS](https://lmms.io/) | 0 | 2 | 1 | 2 | 0 | ⚪ 5 |
| [MuseScore](https://musescore.org/) | 1 | 2 | 1 | 2 | 0 | ⚪ 6 |
| [sfxr](https://sfxr.me/) | 2 | 2 | 2 | 2 | 0 | 🟡 8 |
| [Tonnoform](https://nikos1001.github.io/Tonnoform/) | 2 | 2 | 1 | 0 | 0 | ⚪ 5 |
| [Tracktion Waveform Free](https://www.tracktion.com/products/waveform-free) | 0 | 2 | 1 | 2 | 0 | ⚪ 5 |
| [ZzFX](https://killedbyapixel.github.io/ZzFX/) | 2 | 2 | 2 | 1 | 1 | 🟡 8 |

**Graphics & Art Tools**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Aseprite](https://www.aseprite.org/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [BulkPicTools](https://bulkpictools.com/) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |
| [FireAlpaca](http://firealpaca.com/) | 1 | 2 | 1 | 1 | 0 | ⚪ 5 |
| [Inkscape](https://inkscape.org/) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |
| [Krita](https://krita.org/) | 1 | 2 | 2 | 2 | 1 | 🟡 8 |
| [Lospec Pixel Editor](https://lospec.com/pixel-editor/) | 2 | 2 | 2 | 1 | 0 | 🟡 7 |
| [Magicavoxel](https://www.voxelmade.com/magicavoxel/) | 1 | 2 | 2 | 2 | 1 | 🟡 8 |
| [Paint.NET](https://paint.net/) | 2 | 2 | 1 | 2 | 0 | 🟡 7 |
| [PiskelApp](https://www.piskelapp.com/) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Pixelorama](https://github.com/Orama-Interactive/Pixelorama) | 2 | 2 | 2 | 1 | 0 | 🟡 7 |
| [Pyxel Edit](https://pyxeledit.com/) | 1 | 0 | 1 | 1 | 0 | ⚪ 3 |

**Color & Design Resources**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Autodraw](https://www.autodraw.com/) | 2 | 2 | 1 | 1 | 0 | ⚪ 6 |
| [BitFontMaker2](https://www.pentacom.jp/pentacom/bitfontmaker2/) | 2 | 2 | 1 | 1 | 1 | 🟡 7 |
| [Easy Releasy](https://lemoncosmos.itch.io/easy-releasy) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |
| [Flat UI Colors 2](https://flatuicolors.com/) | 2 | 2 | 1 | 1 | 0 | ⚪ 6 |
| [Lospec Color Palette](https://lospec.com/palette-list) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |
| [Removebg](https://www.remove.bg/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Smart upscaler](https://icons8.com/upscaler) | 2 | 1 | 1 | 1 | 0 | ⚪ 5 |
| [ZzArt](https://zzart.3d2k.com/) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |
| [ZzSprite](https://killedbyapixel.github.io/ZzSprite/) | 2 | 2 | 1 | 0 | 1 | ⚪ 6 |

**Game Design & Management**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Lunacy](https://icons8.com/lunacy) | 1 | 2 | 1 | 1 | 0 | ⚪ 5 |
| [Machinations](https://machinations.io/) | 1 | 1 | 1 | 1 | 1 | ⚪ 5 |
| [PureRef](https://www.pureref.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |

**Game Hosting & Marketing**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [DeepMotion](https://www.deepmotion.com/) | 1 | 1 | 2 | 1 | 1 | ⚪ 6 |
| [itch.io](https://itch.io/) | 2 | 2 | 2 | 2 | 2 | 🟢 10 |
| [ScreenToGif](https://github.com/NickeManarin/ScreenToGif) | 2 | 2 | 2 | 2 | 1 | 🟢 9 |

**Generators & Snippets**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [bg.ibelick](https://bg.ibelick.com) | 2 | 2 | 2 | 1 | 1 | 🟡 8 |
| [delphitools](https://delphi.tools) | 2 | 2 | 1 | 1 | 1 | 🟡 7 |
| [Gradiently](https://gradienty.codes) | 2 | 2 | 1 | 0 | 0 | ⚪ 5 |
| [Haikei](https://app.haikei.app) | 2 | 2 | 2 | 1 | 1 | 🟡 8 |
| [Scrollbar.app](https://scrollbar.app) | 2 | 2 | 0 | 0 | 0 | ⚪ 4 |
| [Tailwind CSS Color Generator](https://uicolors.app/create) | 2 | 2 | 1 | 1 | 1 | 🟡 7 |
| [Transitions.dev](https://transitions.dev/) | 2 | 1 | 2 | 1 | 2 | 🟡 8 |
| [Vercel OG Image Playground](https://og-playground.vercel.app) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |

**Inspiration & Ideas**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [CodeTrendy](https://codetrendy.com/) | 2 | 2 | 0 | 0 | 1 | ⚪ 5 |
| [HACKERS](https://hackers.pocketplay.win/en/) | 2 | 2 | 0 | 0 | 2 | ⚪ 6 |
| [Landbook](https://land-book.com/) | 1 | 1 | 1 | 2 | 2 | 🟡 7 |
| [Saaspo](https://saaspo.com/) | 1 | 1 | 1 | 2 | 1 | ⚪ 6 |
| [saasui.design](https://saasui.design/) | 1 | 1 | 1 | 1 | 0 | ⚪ 4 |
| [ScreensDesign (formerly SCRNSHTS)](https://screensdesign.com/store-screenshots/) | 1 | 1 | 1 | 1 | 0 | ⚪ 4 |

**MCP Servers/Tools**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) | 1 | 2 | 0 | 1 | 1 | ⚪ 5 |
| [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) | 2 | 2 | 1 | 2 | 2 | 🟢 9 |
| [MCP-Hydra](https://github.com/HappyHackingSpace/mcp-hydra) | 1 | 2 | 0 | 0 | 1 | ⚪ 4 |
| [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) | 2 | 2 | 0 | 1 | 1 | ⚪ 6 |

**Mobile Development**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Expo (React Native)](https://expo.dev/) | 2 | 2 | 2 | 2 | 2 | 🟢 10 |
| [Firebase Cloud Messaging](https://firebase.google.com/products/cloud-messaging/) | 1 | 2 | 1 | 2 | 1 | 🟡 7 |
| [Flutter](https://flutter.dev/) | 1 | 2 | 2 | 2 | 1 | 🟡 8 |
| [Ionic](https://ionicframework.com/) | 1 | 2 | 1 | 2 | 0 | ⚪ 6 |
| [React Native](https://reactnative.dev/) | 0 | 2 | 2 | 2 | 0 | ⚪ 6 |

**Pitch & Demo**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [ElevenLabs](https://elevenlabs.io) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Gamma](https://gamma.app/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [Google Slides](https://workspace.google.com/products/slides/) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |
| [Loom](https://www.loom.com/) | 2 | 1 | 2 | 2 | 1 | 🟡 8 |
| [OBS Studio](https://obsproject.com/) | 1 | 2 | 2 | 2 | 2 | 🟢 9 |

**Project Starters & Boilerplates**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Hackathon Starter](https://github.com/sahat/hackathon-starter) | 2 | 2 | 1 | 2 | 1 | 🟡 8 |

**Testing & Quality Assurance**

| Resource | S | C | D | M | F | Total |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| [Cypress](https://www.cypress.io/) | 1 | 2 | 0 | 2 | 0 | ⚪ 5 |
| [Jest](https://jestjs.io/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Mockoon](https://mockoon.com/) | 2 | 2 | 0 | 2 | 1 | 🟡 7 |
| [Playwright](https://playwright.dev/) | 1 | 2 | 0 | 2 | 2 | 🟡 7 |
| [Postman](https://www.postman.com/) | 2 | 1 | 0 | 2 | 1 | ⚪ 6 |
| [Selenium IDE](https://www.selenium.dev/selenium-ide/) | 2 | 2 | 0 | 1 | 0 | ⚪ 5 |
