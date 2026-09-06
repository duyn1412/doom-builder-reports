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
            ├── qa/          # 15 Sanitized JSON spec & test fixtures
            └── videos/      # Web-optimized 360p preview video streams
```

---

## 🔍 Gate 8.7B Current Review Status

- **Status:** **HOLD — Pending Direct Visual Review of Tower & Bridge**
- **House (`house-large-seed103`):** **APPROVED (VISUAL PASS)** (2,010 blocks)
- **Tower (`tower-keep-seed202`):** **PENDING DIRECT REVIEW** (1,326 blocks)
- **Bridge (`bridge-viaduct-seed302`):** **PENDING DIRECT REVIEW** (1,010 blocks)
- **Exact World Readback:** **100.000% across all structures**
- **Automated Technical QA:** **10/10 PASS**
