# 2026-07-18_06-flowedit-hyperparameter-sweep-face-only_891b0cc6

Source notebook: `Notebooks/current/06_flowedit_hyperparameter_sweep_face_only.ipynb`
Generated: 2026-07-18T22:38:33.477907+00:00

FlowEdit (FlowEditSD3) hyperparameter sweep over
18 configurations (`T_steps`, target guidance
scale, `n_max`) on one face-only reference image, using the source/target
prompt pair defined in this notebook (code: `caucasian`).
Best-ranked configuration under the notebook's combined privacy/emotion
score: **hp_5** (experiment_id=5,
combined_score=0.902).

Model: `stabilityai/stable-diffusion-3.5-medium` (revision `b940f670f0eda2d07fbb75229e779da1ad11eb80`)
Seed: 42

## Caveats

- Identity evaluation uses InsightFace (ArcFace) cosine similarity,
  validated for face detection and embedding stability, but no calibrated
  accept/reject threshold has been fit; treat scores as relative, not as a
  demonstrated re-identification-risk reduction.
- This is a single source image, single seed, preliminary experiment; the
  ranking above should not be treated as a validated conclusion.
- Embedded outputs created before this source update are not post-update
  evidence until the notebook is cleanly rerun.
- See `manifest.json` for full per-image metadata and `metrics.csv` for the
  raw scores.
