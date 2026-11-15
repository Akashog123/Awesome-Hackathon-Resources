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

Keep entries alphabetical inside a section. Put each tool in exactly one section (the one a builder would look in first).

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
| [Atlassian Design System](https://atlassian.design/design-system) | 1 | 2 | 1 | 2 | 1 | 7 | Add → Design & UI/UX | Only for Atlassian / Forge (Codegeist) builds |
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
| [Stripe test mode](https://docs.stripe.com/testing) | 2 | 2 | 2 | 2 | 2 | 10 | Add → APIs | Demo payments (gap) |
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

## Watchlist

- **[ascii-reveal](https://github.com/quanhoangindex/ascii-reveal)** - Character-grid decode effect for React loading states. Promote once it has more users and releases.
- **[posts.design](https://posts.design)** - Social post and OG image inspiration. Promote if launch or announcement assets get their own section.
- **[The AI Design Guide](https://aidesign.guide)** - Weekly agentic design guides (its Design Systems directory is already listed). Promote if the guides become a free standalone resource.
- **[tldraw](https://www.tldraw.com/)** - Infinite canvas whiteboard. Promote if Excalidraw falls short.
- **[Beeceptor](https://beeceptor.com/)** - Hosted mock API, 50 requests/day free. Promote if a hosted mock is needed beyond Mockoon.
- **[PocketBase](https://pocketbase.io/)** - Single-file backend. Re-check why the repo was archived.
