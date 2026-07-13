# Prompt Template

## Single Image Generation

Replace bracketed fields. Keep prompts specific and short enough to follow.

```text
Generate one standalone 16:9 horizontal article illustration.

Scene: [core idea in one sentence].

Visual language: hand-drawn editorial illustration on a perfectly flat [pure-white background #FFFFFF by default / very pale cream #FFFCF5 / pale sky blue #E3F2FD / pale lavender #E6E6FA / exact user-specified background color]. Confident medium-bold brush-pen style, with black outlines about 10%-15% slimmer than chunky poster-marker strokes. Keep Littlebox and primary objects medium-bold; draw props and labels slightly lighter; make twig arms, motion marks, and distant details lighter again. Preserve dry-brush texture with tiny gaps in ink coverage, organic rough edges, natural line weight variation, imperfect boxes and wobbly folds, and a warm handmade feel. Series-consistent rough marker style: match stroke hierarchy, ink roughness, handwritten label feel, and Littlebox proportions across the image set. No gradients, no shadows, no paper texture, no polished vector style, no hairline pen strokes, no ruler-straight geometry, no auto-traced edges, no thresholded/posterized bitmap look.

Recurring IP: Littlebox (小盒), a compact squat paper-box character in consistent front-left three-quarter view. The body is white or near-white negative space, NOT tan cardboard, NOT kraft brown, NOT beige material. The front panel is a simple rectangle slightly wider than tall and is the largest visible face; one narrower side panel is visible; the closed top lid is visible. Two calm black dot eyes always sit centered on the upper-middle front panel; tiny thin legs attach under the front panel roughly below the eyes; no mouth, no smile, no eyebrows. When Littlebox interacts with props, show exactly two possible twig arms total: one left side-seam twig arm and one right side-seam twig arm. Arms are thin black curved branch-like strokes, no hands, no gloves, no fingers, no sleeves, never from the front face, lower body, lid, or eyes. Never draw a third arm, spare lower arm, tail-like helper line, or extra limb attached to Littlebox; if the scene has three or more targets, use external trays, slots, tags, falling slips, or amber paths for the extra targets instead of extra limbs. Littlebox is ALWAYS CLOSED in final images. The top flaps meet cleanly along one central front-to-back seam. Littlebox has exactly one narrow amber tape identity strip #F59E0B, about 10%-15% of top width, aligned with that central closed-lid seam. The tape runs front-to-back across the top seam and has a small front tab hanging over the top front lip with an irregular sawtooth / jagged torn cut, usually 2-3 little teeth. Preserve this jagged front tab as the main tape cue. Littlebox must perform the core conceptual action while staying closed, using side-seam twig arms, external slips, stacks, parcels, stamps, tags, paths, slots, or props. Personality: serious, deadpan, useful, slightly awkward, not cute.

Composition: [orbit / diagonal tension / triangular balance / staggered clusters / field composition / asymmetric counterweight]. Build a coordinated visual center of gravity across 3-5 zones of the 16:9 canvas. Vary element height, scale, depth, and orientation; balance one large form with smaller counterweights; do not compress the scene into one horizontal row or a left-to-right pipeline. Main Littlebox subject takes about 30%-45% of the canvas while preserving compact squat proportions. Littlebox performs the action as an operator; do not stretch the box body into a machine, tray, bridge, tube, long carton, or output object. Use separate props for compression, routing, bridging, or output packages. Flow paths and arrows should be amber, curved, and visually lighter than Littlebox's black outline. [Describe exact positions, visual counterweights, and actions for Littlebox and the supporting elements].

Color: black #000000 for main strokes, Littlebox outline, objects, and labels; amber #F59E0B for the single Littlebox seam tape and, separately, for paths/motion only when they are away from the box and do not look like extra tape; coral #E85D75 only for warning, stamp, error, or final emphasis. Use accents sparingly. Do not use black arrows for flow unless they are tiny hand motion marks.

Visible handwritten labels, copied exactly in [language]: [quoted labels]. Keep labels short, legible, separated, and drawn as rough handwritten black marker strokes. Labels must match the illustration's hand-drawn linework; no clean sans-serif font, no bold poster type, no vector text, no calligraphy font, no pasted-on digital typography.

Constraints: one image explains one core idea with enough supporting content to make it fully understandable. Simplify repetition and decoration, not meaning. Keep clear hierarchy and breathing room around semantic groups. Coordinated, strange, and clear. Do not create a formal PPT diagram, logistics logo, cute mascot poster, realistic cardboard render, clean vector box icon, dense explainer with no hierarchy, UI screenshot, or top-left title. Do not fill Littlebox with tan cardboard color or beige shading. Do not move Littlebox's amber tape to the side wall, face panel, back panel, prop, arrow, or random flap. Do not create multiple unrelated tape patches. Do not make the tape cover an entire flap. Do not omit the jagged torn front tab when the front lip is visible. Do not open Littlebox. Do not draw open flaps, raised flaps, half-open lids, cutaways, visible interiors, back-hinged lids, laptop/toolbox/chest/pizza-box lids, tray openings, bucket openings, or mailbox lids. Do not draw thick arms, gloves, fingers, sleeves, or arms coming from the front face. Do not draw more than two arms; no third arm, no lower arm, no tail-like helper line attached to Littlebox, no extra limb-like strokes. Do not use clean digital font labels or post-processed typography. Do not stretch Littlebox into a long carton, press machine, bridge, tray, or output object.
```

## Planning Output Format

Use this when the user asks for shot lists or illustration strategy:

```text
1. Placement: [where it appears]
   Core idea: [one sentence]
   Littlebox state: closed
   Visual metaphor: [physical box action]
   Background: [pure white #FFFFFF by default / exact requested color]
   Composition: [structure, zones, and counterweights]
   Elements: [objects required to express the idea, usually 3-7]
   Labels: [short visible labels]
```

## Editing Prompts

### Make Littlebox Active

```text
Regenerate the image with the same core idea, selected background, palette, and hand-drawn marker style, but make Littlebox perform the central conceptual action. Littlebox should physically collect, seal, sort, carry, brace an external spill, bridge, or transform the idea. Do not let it stand as decoration. Keep the image clean, 16:9, preserve the already assigned flat background color or use pure white #FFFFFF when none was assigned, moderately bold black marker strokes with lighter secondary details, amber tape/path accents, and coral only for emphasis.
Preserve the canonical closed Littlebox model: front-left three-quarter view, dot eyes on the front panel, tiny legs under the front panel, two small side-seam twig arms when acting, and exactly one amber seam tape with a jagged torn front tab. Keep the lid closed; express the action through external props, slips, bundles, paths, stamps, or tags.
```

### Fix Label Errors

```text
Edit the image to keep the illustration unchanged, but replace the visible handwritten labels with these exact short labels: [labels]. Preserve the same rough handwritten marker style, spacing, and language. Do not add new objects.
```

### Reduce Diagram Feeling

```text
Regenerate as a loose hand-drawn article illustration instead of a formal diagram. Remove grid-like alignment, excessive arrows, boxes-within-boxes, and title text. Recompose the necessary content using orbit, diagonal tension, triangular balance, staggered clusters, or asymmetric counterweight. Preserve every element needed to explain the idea; remove only repetition and decoration.
```
