# Video #3 — Physics Prototypes ("Satisfying Physical Simulations") Report

> **Public Review Mirror:** [https://duyn1412.github.io/doom-builder-reports/gates/video-3-prototypes/index.html](https://duyn1412.github.io/doom-builder-reports/gates/video-3-prototypes/index.html)  
> **Interactive QA Portal:** [https://duyn1412.github.io/doom-builder-reports/index.html](https://duyn1412.github.io/doom-builder-reports/index.html)  

## Executive Summary
- **Status:** **VIDEO #3 PHYSICS PROTOTYPES READY FOR MANUAL QA**
- **4 Motion Grammars Tested:**
  1. `pendulum_smash` (SWING, gravity arc): 90 frames (3.0s)
  2. `rotating_sweeper` (ROTATE, powered pivot): 90 frames (3.0s)
  3. `tilting_platform` (SLIDE, tilt & accumulation): 105 frames (3.5s)
  4. `chain_reaction_collapse` (COLLAPSE, causal cascade): 114 frames (3.8s)
- **Reusable Facial Expression System:** 10 pixel-art states on horizontal sprite sheet (`actor_faces_spritesheet_1280x128.png`).
- **Studio Environment:** $R=4.5$m continuous cyclorama cove, DoF $f/5.6$, 0 raw Cycles noise, crisp foreground.
