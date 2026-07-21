# Cross-Model Prompt Benchmarks

This directory documents how prompt frameworks from the AI Design Prompt Library perform across different image-generation models.

The goal is not to declare one model universally better. The goal is to make model-specific prompt adaptations transparent, reproducible where possible, and easy to audit.

## Benchmark principles

- Keep the original prompt unchanged as the baseline.
- Store every model-adapted prompt beside the original.
- Explain every syntax or structural adjustment.
- Record model names, versions, seeds, settings, and generation dates when exposed.
- Mark unavailable information clearly as `Not exposed`.
- Preserve unedited outputs.
- Document reproducibility limitations honestly.
- Evaluate creative-direction fidelity, not only visual attractiveness.

## Required files

Each benchmark should contain:

```text
benchmark-name/
├── original-prompt.md
├── model-name/
│   ├── adapted-prompt.md
│   ├── metadata.md
│   └── output-01.webp
└── second-model/
    ├── adapted-prompt.md
    ├── metadata.md
    └── output-01.webp
