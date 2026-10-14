# Visual style for my projects

Every chart, diagram, GIF and cover image in my repositories follows this file, so the projects look like one body of work.

## Colours

Two colours do the work. Everything else is neutral.

| Role | Light | Dark | Use |
| --- | --- | --- | --- |
| Violet (primary) | `#6941E6` | `#A48BFF` | Main chart series, links, the main path in a diagram |
| Mint (highlight) | `#0F8F7A` | `#3CCFB5` | The one number, bar or box that matters. Nothing else. |
| Ink | `#1F1D2B` | `#EDEBF7` | Text and labels |
| Muted | `#5E5A72` | `#A9A5BE` | Secondary text, arrows, axis labels, captions |
| Border | `#E3E0F5` | `#2E2B40` | Box outlines, gridlines, table rules |
| Background | `#F7F6FF` | `#12111A` | Image and slide background |
| Surface | `#FFFFFF` | `#1C1A28` | Boxes and cards on the background |

When a chart needs more than two series, continue with orange `#E07A2E`, rose `#D14D8A`, blue `#3B82C4` and grey `#8C8899`, in that order. Status colours (success `#1E7F52`, warning `#A35F00`, error `#C23434`) always come with a word or an icon.

## Type

- Inter for all text. JetBrains Mono for code, commands and file names.
- Titles 20 to 28 px, weight 600. Labels 13 to 14 px. Captions 12 px in muted.
- Sentence case everywhere.

## Charts

- Bar charts by default. Use a line only for change over time.
- One series: violet bars, with the key bar in mint.
- Label values directly on the bars. No legend for a single series.
- Light gridlines in border colour, no chart border, no 3D, no gradients.
- Every chart has a caption line with the source or dataset, in muted.
- A results chart always shows the baseline next to the result.

## Diagrams

- Boxes on the surface colour, 1.5 px border, 12 px corner radius, 16 px padding.
- Arrows in muted, 1.5 px, with plain arrowheads.
- The main path in violet. The step a reader should notice in mint.
- Mark model judgment and scripted steps differently: scripts in plain boxes, model steps with a violet outline.
- Flow reads left to right, or top to bottom when it has more than five steps.
- Export as SVG with both light and dark versions where GitHub shows them.

## GIFs and screenshots

- 1280 by 720, under 5 MB, 8 to 12 seconds, no looping cursor wiggle.
- Show one task from start to result. End on the result for at least two seconds.
- Crop to the app. No browser bookmarks bar, no personal tabs.
- Frame screenshots with a 16 px corner radius on the background colour.

## Writing in visuals

- No em dashes and no contractions.
- Numbers carry units: `0.018 USD per denial`, `99.1%`, `100 claims`.
- No emoji, stock photos or mascots.
