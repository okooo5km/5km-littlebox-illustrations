# Prompt Template

## Single Image Generation

Replace bracketed fields. Keep prompts specific and short enough to follow.

```text
Generate one standalone 16:9 horizontal article illustration.

Scene: [core idea in one sentence].

Visual language: minimalist hand-drawn illustration on a flat [pale sky-blue background #E3F2FD / pale lavender background #E6E6FA]. Bold marker illustration, chunky brush-pen style, fat-tipped black marker lines, very thick black outlines with heavy stroke weight. Dry brush texture with tiny gaps in ink coverage, organic rough edges, natural line weight variation, imperfect boxes and wobbly folds, warm handmade feel. Series-consistent rough marker style: match the same stroke thickness, ink roughness, handwritten label feel, and Littlebox proportions across the image set. No gradients, no shadows, no paper texture, no polished vector style, no thin pen lines, no ruler-straight geometry, no auto-traced edges, no thresholded/posterized bitmap look.

Recurring IP: Littlebox (小盒), a compact squat paper-box character in consistent front-left three-quarter view. The body is white or near-white negative space, NOT tan cardboard, NOT kraft brown, NOT beige material. The front panel is a simple rectangle slightly wider than tall and is the largest visible face; one narrower side panel is visible; the closed top lid is visible. Two calm black dot eyes always sit centered on the upper-middle front panel; tiny thin legs attach under the front panel roughly below the eyes; no mouth, no smile, no eyebrows. When Littlebox interacts with props, show two small twig arms emerging from the left and right side seams: thin black curved branch-like strokes, no hands, no gloves, no fingers, no sleeves, never from the front face or lid. Littlebox is ALWAYS CLOSED in final images. The top flaps meet cleanly along one central front-to-back seam. Littlebox has exactly one narrow amber tape identity strip #F59E0B, about 10%-15% of top width, aligned with that central closed-lid seam. The tape runs front-to-back across the top seam and has a small front tab hanging over the top front lip with an irregular sawtooth / jagged torn cut, usually 2-3 little teeth. Preserve this jagged front tab as the main tape cue. Littlebox must perform the core conceptual action while staying closed, using side-seam twig arms, external slips, stacks, parcels, stamps, tags, paths, slots, or props. Personality: serious, deadpan, useful, slightly awkward, not cute.

Composition: [composition family]. Elements distributed across the full 16:9 canvas with both horizontal and vertical variation, not compressed into one line. Main Littlebox subject enlarged, taking about 35%-55% of the canvas, while preserving its compact squat body proportions. Littlebox performs the action as an operator; do not stretch the box body into a machine, tray, bridge, tube, long carton, or output object. Use separate props for compression, routing, bridging, or output packages. Flow paths and arrows should be amber, curved, and visually lighter than Littlebox's black outline. [Describe exact positions and actions for Littlebox and 2-4 supporting elements].

Color: black #000000 for main strokes, Littlebox outline, objects, and labels; amber #F59E0B for the single Littlebox seam tape and, separately, for paths/motion only when they are away from the box and do not look like extra tape; coral #E85D75 only for warning, stamp, error, or final emphasis. Use accents sparingly. Do not use black arrows for flow unless they are tiny hand motion marks.

Visible handwritten labels, copied exactly in [language]: [quoted labels]. Keep labels short, legible, separated, and drawn as rough handwritten black marker strokes. Labels must match the illustration's hand-drawn linework; no clean sans-serif font, no bold poster type, no vector text, no calligraphy font, no pasted-on digital typography.

Constraints: one image explains only one core idea. Generous whitespace but well-distributed. Clean, sparse, strange but clear. Do not create a formal PPT diagram, logistics logo, cute mascot poster, realistic cardboard render, clean vector box icon, dense explainer, UI screenshot, or top-left title. Do not fill Littlebox with tan cardboard color or beige shading. Do not move Littlebox's amber tape to the side wall, face panel, back panel, prop, arrow, or random flap. Do not create multiple unrelated tape patches. Do not make the tape cover an entire flap. Do not omit the jagged torn front tab when the front lip is visible. Do not open Littlebox. Do not draw open flaps, raised flaps, half-open lids, cutaways, visible interiors, back-hinged lids, laptop/toolbox/chest/pizza-box lids, tray openings, bucket openings, or mailbox lids. Do not draw thick arms, gloves, fingers, sleeves, or arms coming from the front face. Do not use clean digital font labels or post-processed typography. Do not stretch Littlebox into a long carton, press machine, bridge, tray, or output object.
```

## Planning Output Format

Use this when the user asks for shot lists or illustration strategy:

```text
1. Placement: [where it appears]
   Core idea: [one sentence]
   Littlebox state: closed
   Visual metaphor: [physical box action]
   Background: [pale sky blue #E3F2FD / pale lavender #E6E6FA]
   Elements: [3-5 objects]
   Labels: [short visible labels]
```

## Editing Prompts

### Make Littlebox Active

```text
Regenerate the image with the same core idea, selected background, palette, and sparse marker style, but make Littlebox perform the central conceptual action. Littlebox should physically collect, seal, sort, carry, spill, bridge, or transform the idea. Do not let it stand as decoration. Keep the image clean, 16:9, flat pale sky-blue background #E3F2FD or flat pale lavender background #E6E6FA as already assigned, black chunky marker strokes, amber tape/path accents, and coral only for emphasis.
Preserve the canonical closed Littlebox model: front-left three-quarter view, dot eyes on the front panel, tiny legs under the front panel, two small side-seam twig arms when acting, and exactly one amber seam tape with a jagged torn front tab. Keep the lid closed; express the action through external props, slips, bundles, paths, stamps, or tags.
```

### Fix Label Errors

```text
Edit the image to keep the illustration unchanged, but replace the visible handwritten labels with these exact short labels: [labels]. Preserve the same rough handwritten marker style, spacing, and language. Do not add new objects.
```

### Reduce Diagram Feeling

```text
Regenerate as a loose hand-drawn article illustration instead of a formal diagram. Remove grid-like alignment, excessive arrows, boxes-within-boxes, and title text. Keep one enlarged Littlebox action and only 2-4 supporting elements.
```
