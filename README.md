# Adelevate — Client Performance Reports

Monthly Meta Ads performance reports for Adelevate Marketing clients, hosted via GitHub Pages.

---

## Structure

```
adelevate-reports/
│
├── bookit/
│   ├── index.html          ← Client index (share this as the master link)
│   ├── june-2026.html      ← June 2026 report
│   └── july-2026.html      ← (add next month)
│
├── horion/
│   ├── index.html          ← Client index (share this as the master link)
│   ├── q2-2026.html        ← Q2 2026 report (Apr–Jun)
│   └── q3-2026.html        ← (add next quarter)
│
└── README.md
```

---

## Live URLs (after GitHub Pages enabled)

| Page | URL |
|------|-----|
| Bookit report index | `https://[your-username].github.io/adelevate-reports/bookit/` |
| Bookit — June 2026 | `https://[your-username].github.io/adelevate-reports/bookit/june-2026.html` |
| Horion report index | `https://[your-username].github.io/adelevate-reports/horion/` |
| Horion — Q2 2026 | `https://[your-username].github.io/adelevate-reports/horion/q2-2026.html` |

---

## How to add a new report

**Bookit (monthly):**
1. Export the new report HTML (e.g. `july-2026.html`)
2. Drop it into `/bookit/`
3. Open `bookit/index.html` and:
   - Move the `new` badge from June to July
   - Add a new `<a class="report-card">` block for July above the coming-soon placeholder
   - Update the coming-soon placeholder to say "August 2026"
4. Push to `main` — live in ~60 seconds
5. Send client the direct link (e.g. `.../bookit/july-2026.html`)

**Horion (quarterly):**
1. Export the new report HTML (e.g. `q3-2026.html`)
2. Drop it into `/horion/`
3. Open `horion/index.html` and:
   - Move the `new` badge from Q2 to Q3
   - Add a new `<a class="report-card">` block for Q3 above the coming-soon placeholder
   - Update the coming-soon placeholder to say "Q4 2026"
4. Push to `main` — live in ~60 seconds
5. Send client the direct link (e.g. `.../horion/q3-2026.html`)

---

## GitHub Pages Setup (one-time)

1. Go to repo **Settings → Pages**
2. Source: **Deploy from branch**
3. Branch: `main` / `root`
4. Save — your site will be live at `https://[username].github.io/adelevate-reports/`

---

## Clients

| Client | Cadence | Folder | Index |
|--------|---------|--------|-------|
| Launchit-Bookit | Monthly | `/bookit/` | `/bookit/index.html` |
| Horion Malaysia | Quarterly | `/horion/` | `/horion/index.html` |

---

*Managed by Adelevate Marketing · adelevate.ads@gmail.com*
