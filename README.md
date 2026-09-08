# Doom Builder QA Reports (Public Review Mirror)

This repository is a **dedicated public review mirror** hosting generated QA reports, real-Minecraft visual proofs, contact sheets, and verification JSON evidence for the **Doom Builder** programmatic architecture pipeline.

> **DOOM BUILDER SOURCE CODE IS NOT INCLUDED IN THIS REPOSITORY.**  
> This mirror contains only generated evaluation dossiers, screenshots, and review artifacts.

---

## 🌐 Public Live Review URLs

- **QA Portal Root:**  
  [https://duyn1412.github.io/doom-builder-reports/index.html](https://duyn1412.github.io/doom-builder-reports/index.html)

- **Gate 8.7B Visual Review Dossier (HTML):**  
  [https://duyn1412.github.io/doom-builder-reports/gates/gate-8.7b/index.html](https://duyn1412.github.io/doom-builder-reports/gates/gate-8.7b/index.html)

- **Gate 8.7B Markdown Report:**  
  [https://duyn1412.github.io/doom-builder-reports/gates/gate-8.7b/report.md](https://duyn1412.github.io/doom-builder-reports/gates/gate-8.7b/report.md)

- **Gate 8.7B QA Audit JSON:**  
  [https://duyn1412.github.io/doom-builder-reports/gates/gate-8.7b/qa-report.json](https://duyn1412.github.io/doom-builder-reports/gates/gate-8.7b/qa-report.json)

---

## 📁 Repository Structure

```
doom-builder-reports/
├── .nojekyll                # Disables Jekyll processing on GitHub Pages
├── README.md                # Mirror documentation
├── index.html               # Multi-Gate QA Portal Root
└── gates/
    └── gate-8.7b/
        ├── index.html       # Full Gate 8.7B Visual Review Dossier with Lightbox
        ├── report.md        # Comprehensive Markdown audit & visual notes
        ├── qa-report.json   # Machine-readable audit evidence
        └── assets/
            ├── images/      # 21 Real-Minecraft screenshots & contact sheets
            ├── qa/          # 17 Sanitized JSON spec & test fixtures
            └── videos/      # Web-optimized 360p preview video streams
```

---

## 🔍 Gate 8.7B Current Review Status

- **Status:** **FINAL PASS / FROZEN**
- **House (`house-large-seed103`):** **PASS WITH KNOWN LIMITATIONS** (2,010 blocks)
- **Tower (`tower-keep-seed202`):** **PASS WITH KNOWN LIMITATIONS** (1,326 blocks)
- **Bridge (`bridge-viaduct-seed302`):** **PASS** (1,010 blocks)
- **Exact World Readback:** **100.000% across all structures**
- **Automated Technical QA:** **10/10 PASS**
\n- [Gate 8.8A — 3D Viral Effects Runtime](gates/gate-8.8a/index.html) — **TECHNICAL PASS / PENDING VISUAL REVIEW** (38/38 PASS, Ball Rain simulation, video players, contact sheet)
- [Video #3 — Full Preview](gates/video-3-full-preview/index.html) — **READY FOR MANUAL QA** (18.63s / 559 frames, 6 physics traps, opening hook at 0.47s, 6-slot hotbar, safe area PASS)
- [Video #3 — Physics Prototypes](gates/video-3-prototypes/index.html) — **READY FOR MANUAL QA** (4 motion grammars, 10-state facial system, 4 video players & contact sheets)
- [Gate 8.8 — YouTube Shorts Safe-Area Remediation](gates/gate-8.8-safe-area/index.html) — **SAFE-AREA TECHNICAL PASS / READY FOR MANUAL REVIEW** (45/45 PASS, +261px bottom clearance, +32px right clearance, video players & before/after visual)
- [Gate 8.8B — Viral Audio & Impact Sync](gates/gate-8.8b/index.html) — **TECHNICAL PASS / READY FOR MANUAL AUDIO REVIEW** (32/32 PASS, 100% procedural SFX, AAC 191.9 kbps, sample-accurate sync, EBU R128 loudness -14.6 LUFS / -2.2 dBTP, video players & 5 review clips)