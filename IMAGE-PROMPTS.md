# Image prompts for heybhuvan.com

## Direction

Risograph-style technical illustration. Flat, printed, slightly imperfect. Two or three ink colours over warm paper. Geometric and diagrammatic rather than pictorial. No people, no faces, no literal computers.

Avoid the default AI-portfolio look entirely: no glowing brains, humanoid robots, blue circuit boards, neural network meshes, or purple gradients. For a researcher whose position is that they evaluate AI critically, that imagery undercuts the message.

## Palette

Two inks, held constant across every image. Suggested: deep ink blue for structure, warm ochre for the one element being highlighted, over off-white paper. If the site has an existing accent colour, use it as ink one.

## Consistency workflow

1. Generate the hero image first.
2. Once you have one you like, copy its image URL.
3. Append `--sref <that url>` to every subsequent prompt.

The style suffix alone will drift across fourteen images. The `--sref` is what actually holds a set together.

## Shared style suffix

Append to every prompt:

```
risograph print illustration, two-colour ink over warm off-white paper, visible paper grain and slight misregistration, flat geometric shapes, thin precise linework, no text, no people, no faces, generous negative space, editorial technical diagram aesthetic --ar 3:2 --style raw --v 7
```

## Hero

```
an abstract diagram of scattered evidence being drawn into a single ordered channel, small irregular marks converging into one clean line, deep ink blue and warm ochre, risograph print illustration, two-colour ink over warm off-white paper, visible paper grain and slight misregistration, flat geometric shapes, thin precise linework, no text, no people, no faces, generous negative space, editorial technical diagram aesthetic --ar 16:9 --style raw --v 7
```

## Strand icons

Generate at `--ar 1:1`. Must read at 64 pixels.

**Evaluating AI**
```
a minimal icon of small squares being sorted into pass and fail columns by a tick and a cross, extremely simple, deep ink blue and warm ochre, risograph print illustration over warm off-white paper, paper grain, flat geometric shapes, thin linework, no text, no people, centred composition --ar 1:1 --style raw --v 7
```

**Research systems and operations**
```
a minimal icon of interlocking pipes and valves forming a closed loop, extremely simple, deep ink blue and warm ochre, risograph print illustration over warm off-white paper, paper grain, flat geometric shapes, thin linework, no text, no people, centred composition --ar 1:1 --style raw --v 7
```

**Research into product and strategy**
```
a minimal icon of a branching path with one route marked by a small filled marker, extremely simple, deep ink blue and warm ochre, risograph print illustration over warm off-white paper, paper grain, flat geometric shapes, thin linework, no text, no people, centred composition --ar 1:1 --style raw --v 7
```

**Earlier research**
```
a minimal icon of stacked layered planes seen in isometric projection, extremely simple, deep ink blue and warm ochre, risograph print illustration over warm off-white paper, paper grain, flat geometric shapes, thin linework, no text, no people, centred composition --ar 1:1 --style raw --v 7
```

## Case study images

Each takes the shared style suffix. Filenames match the `<img>` slots in the HTML.

| File | Prompt subject |
|---|---|
| `img/vsa-copilot.png` | an abstract grid of small rectangular cards, most in blue and a scattered minority in ochre, arranged in neat columns as if being graded, one card lifted slightly out of the grid |
| `img/research-buddy.png` | six separate irregular shapes on the left connected by thin converging lines into a single clean rounded form on the right, like tributaries joining a river |
| `img/ifd-readiness.png` | a six by five grid rising in stepped tiers from lower left to upper right, like a maturity staircase drawn as an architectural elevation |
| `img/ai-readiness.png` | a scattered constellation of small circles of varying size arranged in five loose bands, with thin measuring lines between the bands |
| `img/progress-trail.png` | a winding path drawn as a technical route diagram with four marked waypoints, small friction marks clustered around two of them |
| `img/knowledge-management.png` | nested rectangular containers in an isometric tree structure, some open and some closed, with thin access lines running between levels |
| `img/connected-strategy.png` | two separate loops linked by a feedback arrow forming a figure of eight, drawn as a control system schematic |
| `img/feature-releases.png` | a repeating sequence of identical shapes along a horizontal track, the first few irregular and the later ones perfectly aligned |
| `img/nalabheem.png` | a set of measuring marks and tolerance bands around a central form, like a calibration diagram |
| `img/vr-dance.png` | overlapping motion arcs and rotational paths suggesting a figure in movement, drawn purely as geometric trajectory lines with no body |

## Do not generate

Do not use Midjourney to produce anything that could be mistaken for a real dashboard, screenshot, or dataset. Keep generated images abstract and clearly decorative. Where a real artefact matters, redraw the actual thing rather than generating a plausible-looking fake.
