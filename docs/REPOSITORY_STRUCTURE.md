# Submission structure

```text
README.md                  Complete research introduction, methods, results and discussion
planning.md                English translation of the detailed frozen study baseline
docs/                      Current guide, rubric, scope, contributions and frozen contracts
materials/                 Current App prompt, study descriptions and two-file case uploads
configs/                   Parameters, seeds, case index and current submission scope
src/                       Main offline implementation and historical baseline extractor
verification/              Independent numerical implementation and fixtures
scripts/                   Offline source programs and public package validator
tests/                     Original offline unit tests
datasets/public/           12 selected numerical datasets
results/tables/            Six-model summary, 72 grades, methods, 36 pairs and optional error
results/evaluations/       Six model explanations and per-model scores
results/submissions/       72 byte-identical final reports, code, outputs and available logs
results/calibration/       Compact calibration evidence
results/qualification/     Qualification navigation
results/quality_checks/    Compact baseline evidence and all 60 public candidate datasets
manifests/                 Package hashes, source mapping and baseline registrations
```

The original project retains development tests, earlier revisions, full private controller records and original ZIP archives. This folder contains the final submission-facing materials and evidence rather than the full working history. Frozen filenames and compatibility material paths are retained where the original offline code depends on them. Current navigation does not require historical versioned result directories.

The canonical original specification is archived as `manifests/frozen_protocol.md.gz`. `manifests/translation.json` distinguishes original and translated hashes.
