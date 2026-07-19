# 2026-07-19_03-fer2013-methods-a-to-g-fer-pilot_a92f59d4

Source notebook: `Notebooks/current/03_fer2013_methods_a_to_g_fer_pilot.ipynb`
Generated: 2026-07-19T11:27:00.783855+00:00

FER-2013 partial pilot (methods A-G) covering
16 completed source
images x 7 methods
(112 successful
rows). Execution was interrupted before the intended 146-image prepared
candidate pool completed; this is a development/debugging pilot, not a
final dataset-scale evaluation.

Identity evaluation: DINOv2 face-crop cosine similarity (temporary
visual-similarity proxy, not a calibrated biometric recognizer). Current
FlowEdit notebooks (05, 06) use InsightFace (ArcFace) instead; this pilot
notebook is intentionally not migrated.

## Caveats

- Only five source images completed all seven methods; not statistically
  meaningful.
- Not the final FER-2013 evaluation and not the AffectNet evaluation, which
  remains the intended main evaluation dataset for this thesis.
- Per-method anonymized images from this pilot were not persisted to disk;
  only metrics CSVs and this manifest are published here.
- See `manifest.json` for run metadata and the CSV files for per-row scores.
