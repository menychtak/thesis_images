# Experiment Results

Each subfolder is one experiment run, named `<date>_<notebook-slug>_<config-hash>`. A run is only added here once its notebook cell has executed successfully end to end.

Each run folder contains:

- `README.md` — human-readable summary of that run (source, config, best result, known caveats).
- `manifest.json` — structured metadata for every generated image (source hash, prompt, model + revision, seed, sampler settings, metric scores, runtime, status).
- `metrics.csv` — the full metrics table for that run.
- `source_original.*` — copy of the input image used.
- one image file per generated variant, named by its target code.

License/source provenance for the underlying reference images is unverified — see the top-level README before any public reuse.
