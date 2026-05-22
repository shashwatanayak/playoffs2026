# IPL 2026 Playoff NRR Calculator

**Built by [Shashwat](https://github.com/shashwatanayak)**

🔗 **[Try it live → shashwatanayak.github.io/playoffs2026](https://shashwatanayak.github.io/playoffs2026/)**

---

## Why this exists

Going into the final match of IPL 2026's league stage, three teams — RCB, GT, and SRH — are locked in a tight playoff race. GT have finished their 14 matches. RCB and SRH play each other in the last game, which means one match decides the entire top-3 order.

The question everyone was asking: *how big does SRH need to win to overtake RCB? What happens to positions if RCB loses narrowly? Can SRH even get above GT?*

Standard points tables don't answer this. So I built a calculator that does.

---

## The situation going in

| Team | Matches | Points | NRR    |
|------|---------|--------|--------|
| RCB  | 13      | 18     | +1.065 |
| GT   | 14      | 18     | +0.695 |
| SRH  | 13      | 16     | +0.350 |

GT are done. Their NRR of **+0.695 is frozen** — they can't play any more matches. RCB and SRH both play this match, so their NRRs shift based on the result. All three teams could end up on 18 points, making NRR the sole decider.

Key finding: **SRH need to win by 93+ runs to overtake RCB on NRR** and steal the Qualifier 1 spot.

---

## How to use it

Open the calculator and you'll see two sections on the left — current standings and the match scenario.

**Current standings** — pre-filled with the actual IPL 2026 numbers. Change any team's matches, points, or NRR to simulate a different scenario entirely.

**Match scenario** — pick who bats first, type in the scores, and drag the overs sliders if you want to simulate a team getting bowled out early or chasing down a target quickly. Everything on the right updates instantly.

---

## How to read the results

**Final Standings** — the 1st / 2nd / 3rd order after the match, with each team's new NRR, how much it changed, their points, and whether they go to Qualifier 1 or the Eliminator.

**Order** — the `RCB › GT › SRH` chain tells you exactly who finishes above whom, decided first by points then by NRR.

**Insight line** — plain English summary. Tells you whether Qualifier 1 changes, who's in it, and if RCB drop to the Eliminator.

**NRR bars** — a quick visual to see how far apart the three teams are after the match.

---

## License

MIT
