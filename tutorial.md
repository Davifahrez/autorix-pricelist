# Markdown layout tutorial

Use this guide to control the layout (accordion vs grid) and bundle styles directly from the Markdown you host on GitHub.

## 1) Section layout (grid / accordion)
Add a layout tag to your section headers:

```md
## Main Story & Episodes [layout: accordion]
## Logistik Berkala [layout: grid]
## Story Bundles [layout: grid-featured]
```

Supported layouts:
- `grid`
- `grid-featured`
- `accordion`

If no layout is provided, the section defaults to `grid`.

## 2) Categories and items
Each section contains categories and items.

```md
## Farming & Exploration [layout: grid]
### Weekly Resource Pack
- Daily Check-in: 10k
- Weekly Materials: 25k
```

## 3) Accordion categories
Accordion sections show categories as dropdowns.

```md
## Story & Quests [layout: accordion]
### Archon Quest
- Prologue: 15k
- Act I: 20k
```

## 4) Bundle prices
Use a bundle tag in the category line:

```md
## Story Bundles [layout: grid-featured]
### BUNDLE: Full Chapter [Bundle: 120k -> 99k]
- Act I: 40k
- Act II: 40k
- Act III: 40k
```

## 5) Sub-sections inside categories
Add `####` to create a sub-group:

```md
### Materials Rush
#### Weekdays
- Monday: 10k
- Tuesday: 10k
#### Weekend
- Saturday: 15k
```