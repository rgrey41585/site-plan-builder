# JNN Site Plan Builder

A drag-and-drop, to-scale catering site plan tool for Jim 'N Nick's Bar-B-Q events.

Drop in a satellite screenshot, set the scale by clicking two points, place equipment at its real size (smoker rig, reefer, vans, tents, grills, tables, production block, seating), draw guest flow and rope lines, and export a print-ready PDF with a legend, production drawing, north arrow, and scale bar.

## How to use

1. Open the app in **Edge or Chrome** (desktop). Safari and iPad work too, with downloads instead of folder saving.
2. Type your name the first time, then **Choose folder** and pick your team's shared `Plans` folder.
3. **New Plan** › drop in a satellite screenshot › click two points you know the distance between › type the feet › add event details.
4. Click or drag equipment onto the map. Drag to move, use the red circle to turn, right-click (or press and hold) for more. Undo is always at the top.
5. **Export PDF** › **Save PDF** and send it in Teams or Outlook.

## About this repo

- `index.html` is the whole app: one self-contained file, no server, no build step. Libraries load from cdnjs (jsPDF 2.5.1) and fonts from Google Fonts.
- Plans are **not** stored here. They save as `.siteplan.json` files in the user's own folder, and satellite pictures stay inside those files.
- To update: replace `index.html` with the new `site-plan-builder.html`.

Dimensions are planning estimates (±5 ft). Imagery comes from the user's own screenshots and carries its credit on the printed plan.
