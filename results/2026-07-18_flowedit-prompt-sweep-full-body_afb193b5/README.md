# 2026-07-18_flowedit-prompt-sweep-full-body_afb193b5

Source notebook: `Notebooks/current/04_flowedit_prompt_sweep_full_body.ipynb`
Generated: 2026-07-18T10:50:53.905356+00:00

FlowEdit (FlowEditSD3) prompt sweep over
8 target prompts on one full-body reference
image. Best-ranked prompt under the notebook's combined privacy/emotion
score: **caucasian** (combined_score=0.631).

Model: `stabilityai/stable-diffusion-3.5-medium` (revision `b940f670f0eda2d07fbb75229e779da1ad11eb80`)
Seed: 42
Steps: 50, src_guidance=3.5, tar_guidance=13.5

## Caveats

- DINOv2 is a general visual-feature proxy, not a calibrated biometric
  re-identification metric.
- This is a single source image, single seed, preliminary experiment; the
  ranking above should not be treated as a validated conclusion.
- See `manifest.json` for full per-image metadata and `metrics.csv` for the
  raw scores.
