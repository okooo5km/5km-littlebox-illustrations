---
name: 5km-littlebox-illustrations
description: Create minimalist hand-drawn Littlebox (小盒) article illustrations and illustration plans for essays, posts, blogs, docs, product thinking, workflows, methods, comparisons, abstract concepts, and visual metaphors. Use when the user asks for Littlebox, 小盒, paper-box/carton IP illustrations, article visuals, body illustrations, shot lists, visual metaphor ideas, hand-drawn explainers, or regeneration/editing of this style. Default to 16:9 sparse marker illustrations with Littlebox as the active conceptual operator, using a closed-only box IP, balanced pale sky-blue or pale lavender backgrounds, black chunky strokes, side-seam twig arms, jagged amber tape/path accents, and coral warning/stamp accents. Supports multilingual users by writing prompts in English while keeping visible labels in the user's language.
metadata:
  version: "1.6.0"
---

# 5km Littlebox Illustrations

Create clean, strange, hand-drawn article illustrations built around **Littlebox (小盒)**: a small paper-box character that turns messy ideas into structure. Littlebox must do the conceptual work, not decorate the margin.

## Read References As Needed

- `references/visual-language.md`: style, palette, density, and hard bans.
- `references/littlebox-ip.md`: closed-only Littlebox form, action vocabulary, and failure modes.
- `references/composition-methods.md`: composition families and metaphor invention rules.
- `references/language-and-labels.md`: multilingual output and in-image label handling.
- `references/prompt-template.md`: generation and editing prompt templates.
- `references/quality-gate.md`: checks before delivery or regeneration.
- `references/examples.md`: realistic invocation examples and forward-test cases.

## Workflow

### 1. Understand the Source

Read the user's article, notes, screenshot, file, link, or pasted idea. Identify:

- the single strongest insight
- any cognitive turn, contrast, bottleneck, loop, handoff, or failure point
- which parts deserve images and which should stay text-only
- the likely language for visible labels

Do not illustrate every paragraph. Prefer high-leverage moments: decision points, before/after states, intake-to-output systems, evidence accumulation, scattered-to-structured transformations, hidden bottlenecks, recurring mistakes, and final handoff.

### 2. Plan Before Generating When Asked

If the user asks for planning, analysis, "where should I add images", or a shot list, return a concise shot list before creating images. For each proposed image include:

- placement in the source
- core idea
- Littlebox state: always `closed`
- visual metaphor
- background: pale sky blue `#E3F2FD` or pale lavender `#E6E6FA`
- suggested objects
- short visible labels

Default to 4-7 images for a normal article, 1-3 for short text, and no more than 9 unless the user explicitly wants a full visual series.

When planning multiple images, pre-assign backgrounds from the two-color background pool and keep the counts balanced: even-numbered sets should use equal sky-blue and lavender counts; odd-numbered sets should differ by at most one. Choose by theme first, then lightly randomize when both colors fit.

### 3. Generate When Asked

If the user asks to generate, draw, make, or output images, use the available image generation tool. Generate each image separately; never pack multiple article illustrations into one image unless the user asks for a comparison board.

For each image:

- use one core idea only
- make Littlebox perform the central action
- keep Littlebox closed in every final image; express intake, sorting, filtering, and transformation with external slips, stacks, paths, stamps, props, and side-seam twig arms
- keep Littlebox anatomically canonical: exactly two possible twig arms total, one from each side seam; never add a third arm to handle extra categories
- choose or preserve the assigned background from the planning step: pale sky blue `#E3F2FD` or pale lavender `#E6E6FA`
- keep 3-5 supporting elements total
- use short visible labels in the user's language
- preserve large, well-distributed whitespace

Use `references/prompt-template.md` for the final prompt wording.

### 4. Review And Iterate

After generation, inspect the image against `references/quality-gate.md`. Regenerate or edit if:

- Littlebox is passive
- labels are too long or unreadable
- the result looks like a formal slide, glossy mascot, vector infographic, or logistics icon
- Littlebox is open, half-open, cutaway, or using raised flaps
- color is overused
- the image explains too much

### 5. Save Deliverables

When working inside a project workspace, save final images under:

```text
assets/<article-slug>-littlebox/
```

Name files in order:

```text
01-topic-name.png
02-topic-name.png
```

Keep generated source files unless the user asks to delete them. Report saved paths and identify which images are final, optional, or need one more iteration.

## Output Style

Keep responses compact. Use the user's language for planning and delivery notes. Use English for image-generation prompts, with exact visible labels quoted in the user's language.
