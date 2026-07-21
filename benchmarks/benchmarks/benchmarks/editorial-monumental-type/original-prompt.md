# Original Baseline Prompt

## Benchmark

- Collection: Editorial Advertising Prompts
- Framework: Monumental Type Campaign
- Test campaign: AERO — fictional performance-footwear brand
- Purpose: Cross-model comparison
- Reference images: None
- Baseline adaptations: None

## Fixed test variables

| Placeholder | Value |
|---|---|
| `[RATIO]` | 4:5 |
| `[BRAND/PRODUCT]` | AERO performance footwear |
| `[WORD]` | MOVE. |
| `[SUPPORTING MESSAGE]` | Engineered for everyday momentum |
| `[CALL TO ACTION]` | Discover AERO |
| `[COLOR 1]` | Deep black |
| `[COLOR 2]` | Warm white |
| `[ACCENT]` | Signal orange |

## Original prompt

The prompt below is the unchanged baseline used before any model-specific syntax adjustments.

```text
Create a vertical 4:5 editorial campaign for AERO performance footwear.

Concept:
The campaign is built around one monumental word: “MOVE.” The typography acts
as architecture rather than decoration, partially framing and obscuring the subject.

Composition:
Use a disciplined magazine grid with a confident young male athlete positioned
off-center, wearing modern black technical sportswear and premium performance
footwear. Allow generous negative space. Add only two supporting information
blocks: “Engineered for everyday momentum” and “Discover AERO.”

Art direction:
Flat, bold sans-serif typography; crisp alignment; restrained deep black,
warm white, and signal orange palette; subtle print texture; no bevels,
fake 3D text, or cluttered dashboard elements.

Photography:
Natural commercial portrait lighting, realistic skin texture, coherent shadows,
and believable depth between the subject and typography.

Final quality:
Global campaign standard, art-directed rather than AI-decorated, readable type,
accurate anatomy, and no generic stock-photo pose.
```

## Baseline rules

- Do not add model-specific parameters here.
- Do not rewrite the creative direction.
- Do not add reference images.
- Do not edit generated outputs.
- Keep this file unchanged after testing begins.
- Record every model-specific adjustment in that model’s `adapted-prompt.md`.
