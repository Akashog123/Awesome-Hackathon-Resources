# Curation Criteria

How a resource gets into (or out of) this list. Every addition, removal and review uses this rubric.

## 1. Hard gates (fail any → reject)

| Gate | Pass when |
|------|-----------|
| **Live** | URL loads and the product works today |
| **Usable free** | Open source, or a free tier usable without a credit card |
| **Not a duplicate** | Not already listed. A near-clone of a listed tool must state what it does differently |
| **Hackathon-relevant** | Helps someone build, design, demo, or run a time-boxed event |

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

## Watchlist

- **[ascii-reveal](https://github.com/quanhoangindex/ascii-reveal)** - Character-grid decode effect for React loading states. Promote once it has more users and releases.
- **[posts.design](https://posts.design)** - Social post and OG image inspiration. Promote if launch or announcement assets get their own section.
- **[The AI Design Guide](https://aidesign.guide)** - Guides for agentic design workflows. Promote if a free, standalone resource ships.
