# AI Readiness Discovery

A short, self-scoring questionnaire for small & medium businesses to spot where AI can save time and money, screen for Singapore grant eligibility, and prep for a 1-on-1 with an advisor — all in about 20 minutes.

Built around the **SPARK** framework:

- **S** — Spot the leaks
- **P** — Pilot one small win
- **A** — Apply what works
- **R** — Review the results
- **K** — Keep building

## What's inside

Two formats of the same questionnaire:

| File | What it is | When to use |
|---|---|---|
| `index.html` | Web version — open in any browser. No install, no backend, mobile-friendly. | Share a link, run in a workshop, send as a survey. |
| `AI-Readiness-Discovery.xlsx` | Excel version — same questions, same auto-scoring. | Offline use, save a copy per SME, email back-and-forth. |

Both produce the same result: an AI Readiness score, a SPARK breakdown, top 3 pain points, and detailed write-up of the top 2.

## The 6 parts (≈20 mins)

1. **Business basics** — name, UEN, industry, employee count (local/foreign), advisor.
2. **AI Readiness** — 10 statements rated 1–5.
3. **Problem points (Leaks)** — 8 pain areas rated 1–5.
4. **Top pain points in detail** — auto-picks your top 2 pains from Part 3 and asks: *What does this pain look like? What are your desired outcomes? (e.g. time saved, customers served, errors avoided…)* Plus grant-screening data: number affected, local, employed >12 months, ACRA-linked stakeholders.
5. **Project logistics** — budget, grant awareness (PSG / EDG / ECI / SFEC), hiring plans, project champion / PIC, preferred 1-on-1 slot.
6. **Your results** — overall score (0–100%) with band (*Just starting*, *Getting going*, *Building momentum*, *Well underway*), SPARK breakdown, top 3 pains, and a suggested next step.

## Live questionnaire

👉 Web version: **[Open `index.html` in a browser](./index.html)**

If hosted on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root), the live URL will be:

```
https://YOUR-GITHUB-USERNAME.github.io/REPO-NAME/
```

## Privacy

The web version stores **nothing** on a server. All scoring happens in the browser; refreshing the page clears it. The Excel version is a local file — it lives wherever you save it.

## Editing

- **Web version**: Open `index.html` in any text editor. The `READINESS` and `LEAKS` arrays near the top of the `<script>` block control question wording.
- **Excel version**: Edit question text directly in column B of the *Questionnaire* sheet. Don't move rows — the *Your Results* sheet references specific row numbers.

## License

MIT — see [LICENSE](./LICENSE). Reuse and adapt freely.
