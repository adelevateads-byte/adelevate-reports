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
└── README.md
```

---

## Live URLs (after GitHub Pages enabled)

| Page | URL |
|------|-----|
| Bookit report index | `https://[your-username].github.io/adelevate-reports/bookit/` |
| June 2026 report | `https://[your-username].github.io/adelevate-reports/bookit/june-2026.html` |

---

## How to add a new monthly report

1. Export the new report HTML (e.g. `july-2026.html`)
2. Drop it into the correct client folder (`bookit/`)
3. Open `bookit/index.html` and:
   - Change the `new` badge from June to July
   - Add a new `<a class="report-card">` block for July above the coming-soon placeholder
   - Update the coming-soon placeholder to say "August 2026"
4. Push to `main` — GitHub Pages publishes automatically within ~60 seconds
5. Send the client the direct month link

---

## GitHub Pages Setup (one-time)

1. Go to repo **Settings → Pages**
2. Source: **Deploy from branch**
3. Branch: `main` / `root`
4. Save — your site will be live at `https://[username].github.io/adelevate-reports/`

---

## Clients

| Client | Folder | Index |
|--------|--------|-------|
| Launchit-Bookit | `/bookit/` | `/bookit/index.html` |

---

*Managed by Adelevate Marketing · adelevate.ads@gmail.com*
