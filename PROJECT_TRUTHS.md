# Plague House — Project Truths

## Pillars
- Browser-first historical simulation: one London street, summer 1665.
- The simulation knows the truth; the player only knows evidence.
- The street is the main character. Familiarity makes change emotionally legible.
- Visual direction: a living Restoration-era engraving; restrained parchment, soot, umber and brick; selective color; no permanent horror filter.
- Arc: alive → anxious → altered → potentially alive again.
- Day 1 must be beautiful enough that the later absence is felt as loss. Horror comes from subtraction, familiarity, and consequence—not gore or a screen filter.
- First-person at human scale. Minimal HUD. Parish ledger as primary interface.
- Doors and windows are social interfaces. Entering a home should feel consequential.
- No omniscient infection percentages and no perfect solution.
- Procedural systems generate history, not procedural filler.

## Vertical slice
- Eight persistent households / roughly 25 residents.
- Fourteen simulated days.
- Hidden infection state, imperfect testimony, limited daily actions.
- Observe, knock, question, deliver relief, quarantine, record.
- Street population, lit windows, doors and quarantine marks react to household state.
- Residents die individually; the ledger retains their names. A house can become permanently still.

## Technical
- Zero-build static web prototype: HTML/CSS/JS, directly deployable to GitHub Pages.
- No external runtime dependencies in the first slice.
- Mobile/touch support is a first-class constraint.
- Favor authored procedural drawing rules over random visual noise: façades should read as inhabited architecture.

## Workflow
Keep this file concise. Add durable decisions and lessons, not changelog noise.
