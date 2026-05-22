# IPL NRR Calculator

A clean, interactive Net Run Rate (NRR) calculator built for the IPL 2026 playoff race — specifically the **SRH vs RCB** match that determines Qualifier 1 positions.

Built by **Shashwat**.

---

## What it does

Lets you tinker with live match scores and instantly see:

- Final standings (1st / 2nd / 3rd) after the match
- Each team's NRR before and after
- Whether RCB stays in Qualifier 1 or drops to the Eliminator
- The exact position order — `RCB › GT › SRH` style

## How to use

No installation. No dependencies. No build step.

Just open `index.html` in any browser.

```
open index.html
```

Or host it anywhere — GitHub Pages, Netlify, Vercel — it's a single HTML file.

## Features

- **Live calculation** — every input updates results instantly
- **Bat first toggle** — switch between SRH or RCB batting first
- **Score inputs** — type in any score
- **Overs sliders** — simulate teams getting bowled out early or chasing fast
- **NRR breakdown** — see before/after NRR and the delta for each team
- **Visual bars** — quick NRR comparison across all three teams
- **Insight line** — plain English summary of what the result means for playoffs

## Context

Going into the final match:

| Team | Matches | Points | NRR    |
|------|---------|--------|--------|
| RCB  | 13      | 18     | +1.065 |
| GT   | 14      | 18     | +0.695 |
| SRH  | 13      | 16     | +0.350 |

GT have played all 14 matches — their NRR is frozen. RCB and SRH both play this match, making it the key tie-breaker scenario.

Key finding: **SRH need to win by 93+ runs to overtake RCB on NRR** and steal the Qualifier 1 spot.

## Tech

Plain HTML + CSS + JavaScript. Zero frameworks. Zero dependencies. One file.

## License

MIT — see `LICENSE`.
