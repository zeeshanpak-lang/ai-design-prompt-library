# ChatGPT Image Adaptation

## Model target

- Provider: OpenAI
- Product interface: ChatGPT image generation
- Exact model/version: Record after generation if exposed
- Baseline: [Original prompt](../original-prompt.md)

## Adapted prompt

```text
Create a vertical 4:5 editorial advertising campaign for the fictional performance-footwear brand AERO.

Render the main headline exactly as:

MOVE.

The headline must be monumental, flat, bold, and readable. It should behave like architecture within the composition, passing partly behind and partly in front of the subject without becoming distorted.

Subject:
A confident young male athlete positioned off-center, wearing modern black technical sportswear and premium performance footwear. Use a natural editorial pose rather than a generic stock-photo running pose.

Composition:
Use a disciplined magazine grid with generous negative space. Maintain a clear hierarchy between the monumental headline, athlete, footwear, and supporting copy.

Render only these two supporting text blocks:

“Engineered for everyday momentum”

“Discover AERO”

Art direction:
Use flat, bold sans-serif typography with crisp alignment. Restrict the palette to deep black, warm white, and signal orange. Add subtle print texture.

Do not use beveled text, fake 3D typography, dashboard panels, decorative UI elements, excessive glow, or unrelated text.

Photography:
Use natural commercial portrait lighting, realistic skin texture, coherent shadows, believable anatomy, accurate hands, and convincing depth between the athlete and typography.

Final result:
A premium global sportswear campaign that feels deliberately art-directed rather than AI-decorated. Preserve readable typography and avoid misspelled or additional text.
```

## Adjustments from the baseline

| Original instruction | Adaptation | Reason |
|---|---|---|
| Monumental word: “MOVE.” | Asked for the headline to be rendered exactly as `MOVE.` | Reduces ambiguity and makes typography adherence easier to evaluate |
| Two supporting information blocks | Provided the exact permitted copy and prohibited unrelated text | Image models may invent additional text |
| Typography acts as architecture | Explained the intended front-and-back spatial relationship | Makes the composition requirement more explicit |
| Accurate anatomy | Added accurate hands and natural pose requirements | Provides clearer evaluation criteria for human rendering |
| No cluttered dashboard elements | Expanded the restriction to decorative UI and unrelated text | Prevents common generative-design clutter |

## Audit rule

The original prompt remains unchanged. Every addition made for this model is documented above.
