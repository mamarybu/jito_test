# Cellar — Calorie & Nutrition App

A design case study for **Cellar**, a mobile calorie and nutrition companion built around two core jobs: calculate the calories in a dish or product, and find a recipe that fits your diet and remaining calorie budget.

**Video walkthrough:** [ADD LINK]

This project was designed with an **AI-native workflow**: branding, the design system, and every screen were produced through an iterative conversation with Claude rather than a traditional design tool — from initial brand exploration through a structured usability pass against Jakob Nielsen's ten heuristics.

---

## 1. Branding & Visual Identity

Three genuinely different stylescape directions were explored first — a technical/instrument aesthetic, a bold poster/scoreboard aesthetic, and a warm editorial cookbook aesthetic — before converging on the final direction: **Cellar**, a deep aubergine-and-goldenrod palette on newsprint, paired with Space Grotesk (headings) and IBM Plex Mono (body and every number). The name itself changed mid-project after the working name "Larder" turned out to already belong to two existing recipe apps.

The brand foundations board finalizes the name, a ten-token color palette, the confirmed type pairing, the app icon concept, and core UI fragments, with the rationale for each decision.

![Branding preview](./branding.png)

---

## 2. Design System

A developer-facing reference sheet translating the brand into implementation-ready tokens: color (light and dark), the full typography scale, the 4/8pt spacing and grid, corner-radius and elevation tokens, a base icon set, and eight core components — buttons, input, food/recipe card, bottom tab bar, top nav, filter chip, calorie progress ring, and list row — each shown in its default, pressed, and disabled states.

![Design system preview](./design-system.png)

### Design Tokens

```
<!-- ADD / FINALIZE YOUR DESIGN TOKENS HERE -->

```

---

## 3. Key Screens — Two User Flows

Seven screens at true iPhone size (375×812), built entirely from the design system above, connected on one canvas with labeled navigation arrows:

- **Flow 1 — Calculate Calories:** Home / Dashboard → Add Food → Product Detail → Food Diary
- **Flow 2 — Find a Recipe:** Recipe Discovery → Recipe Filters → Recipe Detail

The screens went through two rounds of revision. **v2** applied Jakob Nielsen's ten usability heuristics across the board — clearer portion and calorie information, stronger visual hierarchy, unambiguous icons, consistent terminology and button states, and previously-missing loading, empty, error, success, and undo states. **v3** followed with a narrower, targeted pass on top of that: consumed/goal macro labels instead of bare numbers, a smaller Quick Add control, per-item macros wherever calories are shown, a decluttered Food Diary, search and a favorites toggle added to Recipe Discovery, right-sized filter controls, a cleaner calorie block and checkable steps on Recipe Detail, and the standalone Saved Recipes screen folded into Recipe Discovery's in-context favorites instead of a separate tab. Every screen carries a short change log tagged to the heuristic it addresses.

![Key screens preview](./key-screens.png)

---

## Process & Prompts

This case study was built through an iterative, AI-native workflow — every deliverable started as a written prompt. Add your prompt history for each stage below.

**Branding & Visual Identity**

```
<!-- ADD PROMPT HERE -->
```

**Design System**

```
<!-- ADD PROMPT HERE -->
```

**Key Screens**

```
<!-- ADD PROMPT HERE -->
```
