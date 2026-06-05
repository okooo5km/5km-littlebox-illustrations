# Language And Labels

## Response Language

Use the user's language for planning, delivery notes, and image descriptions. If the user writes in multiple languages, use the language of the request unless they specify otherwise.

## Prompt Language

Write image-generation prompts in English for model consistency. Put visible labels in quoted exact text using the user's language.

Example:

```text
Visible handwritten labels, copied exactly: "原始材料", "判断", "输出".
```

## Visible Label Rules

- Use 3-6 labels for most images.
- Prefer 1-4 words per label.
- Use nouns or short verb phrases.
- Avoid full sentences inside the image.
- Avoid bilingual labels unless the user asks.
- For CJK labels, reduce label count rather than using tiny text.
- For non-Latin scripts, explicitly say: `copy the label text exactly, preserve the script, do not translate it`.
- Labels must look handwritten with a rough black marker and belong to the drawing.
- Do not use clean sans-serif fonts, bold poster fonts, calligraphy fonts, vector text, or pasted-on digital typography.
- Across an image set, keep label stroke weight and handwriting roughness consistent with the other Littlebox images.

## Multilingual Consistency

The visual metaphor should stay the same across languages:

- Littlebox always stays closed; only the external action and labels change with the concept.
- Prompt remains English.
- Labels follow the user's language.
- If generated text accuracy is critical, plan the labels first and keep them extremely short.

## When Text Fails

If generated labels are unreadable or wrong:

1. Regenerate with fewer labels.
2. Use shorter words.
3. Move labels farther apart.
4. If needed, produce a version with blank label spaces and add text with deterministic tooling outside image generation, but only if the final labels still look like rough handwritten marker text. Do not accept clean digital font labels as final.
