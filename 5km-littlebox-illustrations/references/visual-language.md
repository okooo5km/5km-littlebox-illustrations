# Visual Language

## One Sentence

Clean editorial marker drawings where a small paper box physically performs the abstract work inside an article, defaulting to a borderless pure-white canvas.

## Must Have

- 16:9 horizontal article illustration by default.
- Flat, clean pure-white background `#FFFFFF` by default. Use a preset alternative or exact user-specified color only when requested.
- Black `#000000` as the dominant line and character color.
- Moderately bold brush-pen / marker strokes: about 10%-15% slimmer than the previous chunky example style, still unmistakably hand-drawn at article size.
- Use a clear line-weight hierarchy: Littlebox and primary objects are medium-bold; props and labels are slightly lighter; arms, motion marks, and distant details are lighter again.
- Dry-brush texture, tiny gaps in ink coverage, rough organic edges.
- Series-consistent rough marker style: all images in one set should share similar line thickness, ink roughness, label style, and Littlebox proportions.
- Imperfect boxes, wobbly folds, uneven flaps, hand-made rhythm.
- A consistent closed Littlebox character model: front-left three-quarter box, dot eyes on front panel, tiny legs, side-seam twig arms when acting, and one amber seam tape with a jagged torn front tab.
- Littlebox always stays closed. The amber seam tape is narrow, centered on the closed top split, and has a small sawtooth/jagged front tab.
- Littlebox body stays white or near-white. Do not color it tan, kraft brown, beige, or realistic cardboard.
- Intentional breathing room around semantic groups. Main subject should usually occupy 30%-45% of the canvas so supporting content can share the composition.
- One core idea per image.
- Content expression comes before minimalism. Use enough supporting detail to make the idea understandable, then remove only repetition and decoration.
- Littlebox must perform the core conceptual action.
- Visible labels are concise, usually 3-6 total, but clarity may justify a few more.

## Palette

- **Black `#000000`**: character, structure, main objects, primary labels.
- **Pure white `#FFFFFF`**: default background; immersive in light interfaces and visually borderless inside articles.
- **Very pale cream `#FFFCF5`**: optional near-white warmth with minimal card-like boundary.
- **Pale sky blue `#E3F2FD`**: optional background for technical, structural, systems, clarity, tools, interfaces, and crisp method explanations.
- **Pale lavender `#E6E6FA`**: optional background for reflective, creative, emotional, abstract, exploratory, uncertainty, narrative, and gentler concept images.
- **Amber `#F59E0B`**: Littlebox's single seam tape and jagged front tab first; path, transformation motion, arrows, and useful flow only when visually separate from the identity tape.
- **Coral `#E85D75`**: warning, stamp, error, result, decisive emphasis.

Use amber and coral sparingly. A strong image can use only black plus one accent.

## Background Selection

- Default every image to pure white `#FFFFFF`, including all images in a set.
- If the user explicitly names a background color, use it exactly and let it override the default and preset pool.
- If the user asks for choices, offer very pale cream `#FFFCF5`, pale sky blue `#E3F2FD`, and pale lavender `#E6E6FA`.
- Use different backgrounds across a set only when the user explicitly asks for variation; then assign them deliberately by theme instead of randomizing.
- Prefer light custom colors so the canonical black linework remains legible. If a requested dark background would require reversing line and label colors, confirm that style change before generating.
- Keep each image on one flat background color. Do not blend, gradient, texture, vignette, or split multiple backgrounds inside one image.

## Texture Words

Use these phrases in prompts when generation quality matters:

- `minimalist hand-drawn illustration`
- `confident hand-drawn marker illustration`
- `medium-bold brush-pen style`
- `moderately thick black outlines, slightly slimmer than chunky poster strokes`
- `firm marker lines with a clear weight hierarchy, never hairline pen strokes`
- `dry brush texture with tiny gaps in ink coverage`
- `organic rough edges`
- `natural line weight variation`
- `imperfect boxes and wobbly folds`
- `warm handmade feel`
- `NOT clean vector, NOT ruler-straight geometry`
- `NOT auto-traced, NOT thresholded, NOT posterized`
- `handwritten marker labels, not typed text`

## Label Style

- Visible labels should feel drawn with the same fat black marker as the illustration.
- CJK labels should be rough, slightly uneven, and handwritten-looking, not clean UI typography.
- Avoid digital sans-serif fonts, bold poster fonts, calligraphy fonts, vector text, perfectly kerned type, or labels that look pasted on after generation.
- If deterministic text repair is needed, match the rough handwritten marker style as closely as possible; do not accept clean typed labels as final article illustrations.
- Keep font weight visually close to the black marker linework. Do not let labels become heavier, cleaner, or more polished than the drawing.

## Avoid

- glossy mascot art
- logistics brand icon
- realistic cardboard rendering
- polished vector infographic
- hairline icon art
- tan cardboard material rendering
- clean geometric box icon
- auto-traced or thresholded bitmap look
- clean digital font labels
- post-processed typography that does not match the hand-drawn linework
- open boxes, half-open boxes, cutaways, raised flaps, or visible box interiors
- formal PPT diagram
- dense course slide with no visual hierarchy
- cute sticker pack
- children's book scene
- 3D object render
- shadows, gradients, paper texture, grainy background
- complex UI screens
- too many arrows or nodes
- top-left diagram titles such as "Workflow", "System", "Roadmap", or "Framework"

## Taste Target

The image should feel like a clever product thinker drew a strange box on a page to explain the one thing that matters.
