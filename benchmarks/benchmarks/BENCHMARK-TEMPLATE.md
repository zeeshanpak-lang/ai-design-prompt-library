# Benchmark Template

Use this template for every cross-model prompt evaluation.

## Benchmark information

- Benchmark name:
- Prompt collection:
- Framework tested:
- Date started:
- Evaluator:

## Original baseline prompt

Paste the unchanged original framework here.

```text
[ORIGINAL PROMPT]
```

## Models tested

| Provider | Model | Version | Seed exposed? | Output |
|---|---|---|---|---|
|  |  |  | Yes / No |  |
|  |  |  | Yes / No |  |

## Testing rules

- Use the same creative objective across every model.
- Preserve the original prompt as the baseline.
- Record every adaptation.
- Do not silently improve or remove instructions.
- Use no reference image unless the benchmark specifically tests image references.
- Preserve the original generated output without editing.
- Mark unavailable metadata as `Not exposed by the platform`.

## Model adaptation record

### Provider and model

- Provider:
- Model:
- Model version:
- Generation date:
- Seed:
- Seed availability:
- Aspect ratio:
- Resolution:
- Number of outputs generated:
- Selected output:
- Reference images:
- Editing performed:

### Adapted prompt

```text
[MODEL-ADAPTED PROMPT]
```

### Syntax adjustments

| Original instruction | Adapted instruction | Reason |
|---|---|---|
|  |  |  |
|  |  |  |

## Evaluation

Score each criterion from 1 to 5.

| Criterion | Score | Notes |
|---|---:|---|
| Prompt adherence |  |  |
| Composition |  |  |
| Typography |  |  |
| Material rendering |  |  |
| Lighting |  |  |
| Anatomy, if applicable |  |  |
| Creative-direction fidelity |  |  |

## Strengths

- 
- 
- 

## Failures or limitations

- 
- 
- 

## Reproducibility limitations

Document any information that the platform does not expose, including model version, seed, hidden defaults, or generation controls.

## Final observations

Explain what the model handled well, what required adaptation, and whether the syntax changes improved adherence without changing the original creative intent.
