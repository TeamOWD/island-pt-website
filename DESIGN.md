---
name: Island PT
description: Editorial-clinical specimen sheet for a one-to-one physical therapy practice in Kīhei, Maui.
colors:
  paper-00: "oklch(98.4% 0.008 82)"
  paper-05: "oklch(96.2% 0.012 82)"
  paper-10: "oklch(93.4% 0.018 82)"
  paper-15: "oklch(89.6% 0.022 82)"
  paper-25: "oklch(82.0% 0.026 82)"
  ink-20:   "oklch(78.0% 0.012 82)"
  ink-40:   "oklch(64.0% 0.014 82)"
  ink-60:   "oklch(46.0% 0.016 82)"
  ink-80:   "oklch(28.0% 0.014 82)"
  ink-95:   "oklch(16.0% 0.012 82)"
  ocean-90: "oklch(20.0% 0.038 145)"
  ocean-70: "oklch(34.0% 0.060 142)"
  ocean-55: "oklch(46.0% 0.072 140)"
  coral-55: "oklch(56.0% 0.150 38)"
  coral-65: "oklch(64.0% 0.140 40)"
  sun-70:   "oklch(78.0% 0.130 82)"
  sun-55:   "oklch(64.0% 0.150 70)"
  bone:     "oklch(98.8% 0.006 82)"
typography:
  display:
    fontFamily: "Instrument Serif, Times New Roman, serif"
    fontSize: "clamp(64px, 9vw, 128px)"
    fontWeight: 400
    lineHeight: 0.96
    letterSpacing: "-0.028em"
  headline:
    fontFamily: "Instrument Serif, Times New Roman, serif"
    fontSize: "52px"
    fontWeight: 400
    lineHeight: 1.04
    letterSpacing: "-0.022em"
  title:
    fontFamily: "Instrument Serif, Times New Roman, serif"
    fontSize: "34px"
    fontWeight: 400
    lineHeight: 1.12
    letterSpacing: "-0.016em"
  subtitle:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "24px"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.005em"
  lead:
    fontFamily: "Instrument Serif, Times New Roman, serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: "normal"
  body:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.5
  micro:
    fontFamily: "JetBrains Mono, ui-monospace, monospace"
    fontSize: "13px"
    fontWeight: 600
    lineHeight: 1.6
    letterSpacing: "0.18em"
  caption:
    fontFamily: "Inter, system-ui, sans-serif"
    fontSize: "12px"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  flat: "2px"
  soft: "6px"
  arc:  "18px"
  pill: "999px"
spacing:
  xs: "8px"
  s:  "14px"
  m:  "24px"
  l:  "44px"
  xl: "72px"
  2x: "120px"
components:
  button-primary:
    backgroundColor: "{colors.ocean-70}"
    textColor: "{colors.bone}"
    rounded: "{rounded.soft}"
    padding: "14px 22px"
  button-primary-hover:
    backgroundColor: "{colors.ocean-90}"
    textColor: "{colors.bone}"
    rounded: "{rounded.soft}"
    padding: "14px 22px"
  button-secondary:
    backgroundColor: "{colors.paper-00}"
    textColor: "{colors.ink-95}"
    rounded: "{rounded.soft}"
    padding: "14px 22px"
  button-secondary-hover:
    backgroundColor: "{colors.ink-95}"
    textColor: "{colors.bone}"
    rounded: "{rounded.soft}"
    padding: "14px 22px"
  button-outline:
    backgroundColor: "transparent"
    textColor: "{colors.ocean-70}"
    rounded: "{rounded.soft}"
    padding: "14px 22px"
  button-outline-hover:
    backgroundColor: "{colors.ocean-70}"
    textColor: "{colors.bone}"
    rounded: "{rounded.soft}"
    padding: "14px 22px"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.ink-95}"
    rounded: "{rounded.soft}"
    padding: "14px 6px"
  card-service:
    backgroundColor: "{colors.paper-00}"
    textColor: "{colors.ink-80}"
    rounded: "{rounded.soft}"
    padding: "36px 32px 40px"
  card-testimonial:
    backgroundColor: "{colors.ocean-90}"
    textColor: "{colors.bone}"
    rounded: "{rounded.arc}"
    padding: "48px 44px"
  card-feature:
    backgroundColor: "{colors.paper-05}"
    textColor: "{colors.ink-80}"
    rounded: "{rounded.soft}"
    padding: "26px 28px"
  input-field:
    backgroundColor: "{colors.paper-00}"
    textColor: "{colors.ink-95}"
    rounded: "{rounded.flat}"
    padding: "14px 16px"
  input-field-focus:
    backgroundColor: "{colors.bone}"
    textColor: "{colors.ink-95}"
    rounded: "{rounded.flat}"
    padding: "14px 16px"
  nav-bar:
    backgroundColor: "{colors.paper-00}"
    textColor: "{colors.ink-95}"
    rounded: "{rounded.flat}"
    padding: "18px 28px"
  nav-bar-dark:
    backgroundColor: "{colors.ocean-90}"
    textColor: "{colors.bone}"
    rounded: "{rounded.flat}"
    padding: "18px 28px"
---

# Design System: Island PT

## 1. Overview

**Creative North Star: "The Honest Specimen"**

Island PT presents itself the way a clinician would present a typed specimen sheet: numbered, labeled, calmly forensic. Every component is a named species; every token is annotated; every rule is stated out loud. The voice of the system is the voice of a quietly competent practitioner, not a salesperson. Warmth comes from the paper, not from decoration.

The aesthetic is editorial-clinical, not spa-wellness and not corporate-medical. A warm tinted-paper canvas (hue 82°, the same hue across every neutral) carries deep ocean-green brand color and a single coral spark used sparingly. Instrument Serif italics provide the emotional cadence — they punctuate headlines like a pull-quote in a magazine, never sprinkled at random. JetBrains Mono labels carry the specimen-sheet rhythm: tight tracking, uppercase, used as eyebrows and index tags. Inter handles every block of running prose at 17px on a 65–75ch measure.

This system explicitly rejects: gym/CrossFit aggression (no red-on-black, no shouting type), generic spa wellness (no lavender, no script fonts, no "holistic journey" pastels), big-tech SaaS minimalism (no purple gradients, no hero-metric template, no identical card grids), and the stock-medical reflex (no corporate blue, no white-coats stock photography, no medical-iconography clip art).

**Key Characteristics:**
- Warm-paper ground tinted at hue 82°, never `#fff` or `#000`.
- Three card species, never repeated in a uniform grid.
- Four heroes (editorial, split, drenched, photographic) — each chosen for content, not for rotation.
- Italic-serif accents scoped to display headlines and brand lockup, never per heading.
- Six gap steps so no two components share the same vertical breathing room by default.
- A single motion language: `cubic-bezier(0.22, 1, 0.36, 1)`, 140ms fast and 240ms mid.

## 2. Colors

OKLCH throughout. Every neutral is tinted toward the same warm hue (82°), so paper and ink belong to one family. Brand greens sit in the 140–145° band; the coral and sun-gold accents balance the cool brand with warm sparks. Chroma drops at lightness extremes to avoid garish whites and blacks.

### Primary

- **Ocean Primary** (`oklch(34% 0.060 142)`): the brand voice. Backgrounds for CTAs, primary button fill, italic-serif accents inside body copy, hover-state navigation underlines. The clinical signal of the system.
- **Ocean Deep** (`oklch(20% 0.038 145)`): drenched hero backgrounds, testimonial card, dark navigation. Used when a section should feel like the brand swallowed the surface.
- **Ocean Soft** (`oklch(46% 0.072 140)`): mid-tone for gradients and split-hero photo panels. Rarely a flat fill.

### Secondary

- **Coral Spark** (`oklch(56% 0.150 38)`): the focus-ring color. Used on `:focus-visible` outlines, error states, and exactly one accent moment per long page. The system's only true alarm color.
- **Coral Warm** (`oklch(64% 0.140 40)`): softer coral for gradient compositions and avatar fills. Never as a button background.

### Tertiary

- **Sun Gold** (`oklch(78% 0.130 82)`): italic emphasis on dark backgrounds (e.g. the drenched hero's `<em>`), pull-quote marks, signoff rules. The "gold leaf" of the system.
- **Sun Amber** (`oklch(64% 0.150 70)`): warmer companion to Sun Gold, used in gradient compositions and the split-hero photo panel.

### Neutral (paper)

- **Paper 00** (`oklch(98.4% 0.008 82)`): lightest paper. Card surfaces, focus-state input backgrounds.
- **Paper 05** (`oklch(96.2% 0.012 82)`): feature-card surface, alternate panel tone.
- **Paper 10** (`oklch(93.4% 0.018 82)`): page background, default canvas.
- **Paper 15** (`oklch(89.6% 0.022 82)`): tonal panels for callouts and asides.
- **Paper 25** (`oklch(82.0% 0.026 82)`): hairline-on-paper rules and subtle borders.

### Neutral (ink)

- **Ink 95** (`oklch(16% 0.012 82)`): primary text and high-contrast borders. The "black" of the system; never `#000`.
- **Ink 80** (`oklch(28% 0.014 82)`): body copy.
- **Ink 60** (`oklch(46% 0.016 82)`): muted text, captions, eyebrow color on light.
- **Ink 40** (`oklch(64% 0.014 82)`): placeholder text.
- **Ink 20** (`oklch(78% 0.012 82)`): divider rules and default input borders.
- **Bone** (`oklch(98.8% 0.006 82)`): the "white" replacement. Used on dark surfaces for type and CTAs.

### Named Rules

**The One Hue Rule.** Every neutral lives at hue 82°. Paper and ink are the same family at different lightnesses. Never introduce a cool grey, never a true neutral. The warmth of the page is non-negotiable.

**The Coral Reserve Rule.** Coral exists for focus rings, error states, and one deliberate accent moment per page. It is forbidden as a button fill, a background, or a heading color. Its rarity is the alarm.

**The No-Black-No-White Rule.** `#000` and `#fff` are banned. Ink 95 and Bone replace them. The audit catches this on every commit.

## 3. Typography

**Display Font:** Instrument Serif (with Times New Roman, serif fallback)
**Body Font:** Inter (with system-ui, sans-serif fallback)
**Label/Mono Font:** JetBrains Mono (with ui-monospace fallback)

**Character:** Instrument Serif provides the editorial cadence — italics for emotional emphasis, regular for clinical statement. Inter handles every paragraph and UI label that isn't an eyebrow. JetBrains Mono carries the "specimen sheet" voice: tracked-out uppercase, index numbers, signoffs. The pairing reads like a quarterly journal, not a marketing landing.

### Hierarchy

- **Display** (Instrument Serif, 400, `clamp(64px, 9vw, 128px)`, line-height 0.96, letter-spacing −0.028em): hero headlines only. One per page.
- **Headline** (Instrument Serif, 400, 52px, line-height 1.04, letter-spacing −0.022em): section openers (`Care that listens. Treatment that lasts.`).
- **Title** (Instrument Serif, 400, 34px, line-height 1.12, letter-spacing −0.016em): subsection openers and card headings.
- **Subtitle** (Inter, 600, 24px, line-height 1.2): UI titles where sans is more legible than serif (forms, dense modules).
- **Lead** (Instrument Serif italic, 400, 22px, line-height 1.3, color Ocean Primary): hero sub-headlines and editorial pull-text. Always italic, always Ocean-tinted on light.
- **Body** (Inter, 400, 17px, line-height 1.5, color Ink 80): all running prose. Measure capped at 65–75ch.
- **Micro / Eyebrow** (JetBrains Mono, 600, 13px, letter-spacing 0.18em, uppercase): section labels, index tags, signoffs. The specimen-sheet voice.
- **Caption** (Inter, 400, 12px, color Ink 60): image captions, footnotes, opt-in labels.

### Named Rules

**The Italic Accent Rule.** Italic serif is reserved for display headlines (`Perform your <em>best.</em>`) and the brand lockup (`Island <em>PT.</em>`). Forbidden inside running body copy and inside subtitle/body roles. The italic earns its weight by being rare.

**The Specimen Eyebrow Rule.** Every section gets a mono micro-label (e.g. `01 / APPROACH`). It is the closest thing this system has to a logo for the section. Never skip it; never replace it with a sans uppercase.

**The 65–75ch Rule.** Body copy never exceeds 75 characters per line. The page is a journal, not a billboard.

## 4. Elevation

This system is flat by default. Depth is conveyed through **tonal layering** (Paper 00 cards on Paper 10 page) and through **2px ink borders** (`border: 2px solid Ink 95`) on cards that need to feel like cut paper. No drop shadows on cards, no soft glows, no glassmorphism.

Two state-only motion responses replace shadow: a 3px vertical lift on hover (`transform: translateY(-3px)`) for service cards, and a focus ring (Coral Spark, 2px outline, 3px offset) for any interactive element. Motion is the shadow.

### Named Rules

**The Cut-Paper Rule.** Cards rest on the page like sheets cut from heavier stock: a 2px Ink 95 border, a 6px radius, and a tonal lift in fill color. No shadow, no blur. If you reach for `box-shadow`, you are designing the wrong card species.

**The Motion-As-Elevation Rule.** Hover lifts a card 3px; that is the entire elevation language. No scale, no shadow bloom, no halo. Easing is always `cubic-bezier(0.22, 1, 0.36, 1)` at 140ms fast or 240ms mid.

## 5. Components

### Buttons

- **Shape:** soft radius (6px). Pill and arc radii exist in the system but never on buttons.
- **Primary:** Ocean Primary fill, Bone text, 14px × 22px padding, Inter 600 at 16px. Hover deepens to Ocean Deep.
- **Secondary:** Paper 00 fill, Ink 95 text, Ink 95 1.5px border. Hover inverts to Ink 95 fill with Bone text.
- **Outline:** transparent fill, Ocean Primary text and 1.5px border. Hover floods to Ocean Primary fill with Bone text.
- **Ghost:** no border, Ink 95 text, tight horizontal padding (6px). Hover shifts text color to Ocean Primary.
- **Focus:** Coral Spark 2px outline at 3px offset on every variant. Universal.
- **Arrow affordance:** any button with a trailing `.arrow` glyph translates that glyph 3px on hover. Subtle directional cue, never used decoratively.

### Cards (three species, never uniform)

- **Service card** — Paper 00 on Paper 10. 2px Ink 95 border, 6px radius, 36px × 32px × 40px padding. Italic Ocean serif number (56px) as the visual anchor, serif title (28px), Ink 80 body, mono link with arrow. Max-width 360px. Hover: `translateY(-3px)`.
- **Testimonial card** — Ocean Deep fill, Bone text, 18px arc radius, 48px × 44px padding, no border. Sun Gold italic quote-mark (96px) as the anchor. Italic serif blockquote at 28px. Mono figcaption with avatar gradient. Max-width 580px.
- **Feature card** — Paper 05 fill, no border, 6px radius, 26px × 28px padding. 36px Ocean Primary icon tile (2px radius) on the left, Inter 600 17px title, Ink 60 14px body. Max-width 460px.

Never grid these three side-by-side at the same width. The system fails the moment they line up uniformly.

### Inputs / Fields

- **Style:** Paper 00 fill, 1.5px Ink 20 border, flat radius (2px), 14px × 16px padding, Inter 16px Ink 95.
- **Label:** mono eyebrow above the field, uppercase 11px at 0.18em tracking. Optional badge `(opt)` in sans, 11px, Ink 60.
- **Hover:** border tightens to Ink 60.
- **Focus:** border becomes Ocean Primary, background becomes Bone. No focus glow.
- **Error:** border becomes Coral Spark; error message appears in Coral Spark mono 11px below.
- **Select:** appearance-none, custom chevron drawn from two linear gradients in Ink 60.
- **Textarea:** same treatment, min-height 130px, vertical-resize only, sans font (never serif).

### Navigation

- **Light bar:** Paper 00 fill, 2px Ink 95 bottom border, 18px × 28px padding. Serif brand lockup at 28px with italic accent in Ocean Primary. Inter 15px nav links, no underline at rest, Ocean Primary 1.5px underline on hover and `aria-current="page"`. Primary CTA: Ocean Primary fill, Bone text, flat radius (2px), 12px × 18px.
- **Dark bar:** Ocean Deep fill, Bone text, Sun Gold italic accent in brand lockup. CTA inverts: Bone fill, Ocean Deep text. Same geometry.
- **Mobile (≤720px):** nav list hides, brand and CTA remain.

### Heroes (four variants, content-selected)

- **Editorial** (type-led, no photo) — Paper 00 background, 2px Ink 95 border, grid `1fr 220px`. Display serif at clamp(44px, 7.5vw, 96px), italic Ocean Primary accent. Right rail shows mono index labels with hairline rules.
- **Split** (asymmetric copy + image) — Ocean Deep fill, Bone text, grid `1.2fr 1fr`. Sun Gold italic accent. Right panel is photo or Ocean→Sun gradient with a mono `01 / SPECIMEN` corner tag.
- **Drenched** — full Ocean Deep surface, Bone display serif, Sun Gold italic. Used for declarative moments (`Know how your body moves.`).
- **Photographic** — full-bleed photo, 18px arc radius, gradient scrim from Ocean Deep at 45–85% opacity. Mono eyebrow with Bone-on-Bone 1.5px border at 55% opacity. Reserved for RunEasi-style assessment moments.

### Eyebrows (section labels)

Mono uppercase, 13px, 0.18em tracking, Ink 60 on light surfaces / Bone at 70% on dark. Often paired with an index number (`01 / APPROACH`) and a hairline rule. The signature of every section opener.

### Signature: The Specimen Header

Every page section opens with the same three-element rhythm: (1) a mono index eyebrow, (2) a serif title with italic accent, (3) one lead paragraph in italic serif at 22px in Ocean Primary. This triad is the system's most recognizable pattern; it carries the "specimen sheet" character through every section without needing a literal frame around it.

## 6. Do's and Don'ts

### Do:

- **Do** tint every neutral toward hue 82°. Paper and ink belong to the same warm family.
- **Do** use Coral Spark only for focus rings, error states, and one deliberate accent moment per long page.
- **Do** scope italic serif to display headlines and the brand lockup. Anywhere else, italics are forbidden.
- **Do** open every section with the Specimen Header triad: mono index eyebrow, serif title with italic accent, italic-serif lead in Ocean Primary.
- **Do** use the 2px Ink 95 border to give cards "cut-paper" weight. Tonal layering carries depth from there.
- **Do** vary card species: Service, Testimonial, and Feature exist precisely so the page never feels grid-uniform.
- **Do** cap body copy at 65–75ch. Long lines break the journal voice.
- **Do** animate state only, with `cubic-bezier(0.22, 1, 0.36, 1)` at 140ms fast or 240ms mid. Never animate layout properties.
- **Do** respect `prefers-reduced-motion`: every transform-based affordance gets a no-motion fallback.

### Don't:

- **Don't** use `#000` or `#fff`. Ever. Use Ink 95 and Bone instead.
- **Don't** use Coral Spark as a button fill, a section background, or a heading color. It is the alarm color; rarity is the point.
- **Don't** sprinkle italic-serif accents on every heading. The italic earns its weight by being rare.
- **Don't** grid the three card species at uniform width. The system fails the moment Service + Testimonial + Feature line up identically.
- **Don't** ship the hero-metric template (big number, small label, supporting stats, gradient accent). Banned across the system.
- **Don't** use side-stripe borders (`border-left` greater than 1px as a colored stripe). Use full borders, leading numbers, or tonal panels.
- **Don't** reach for gradient text (`background-clip: text` on a gradient). Use a single solid Ocean Primary or Sun Gold; emphasis through weight or size.
- **Don't** use glassmorphism or backdrop blur. The only acceptable scrim is the Ocean Deep gradient on photographic heroes.
- **Don't** drift toward gym/CrossFit aesthetics: no red-on-black, no shouting type, no high-energy slogan stacks.
- **Don't** drift toward spa-wellness: no lavender, no script fonts, no "holistic journey" pastels, no river-stone iconography.
- **Don't** drift toward big-tech SaaS: no purple gradients, no isometric illustrations, no identical icon-and-heading card grids.
- **Don't** drift toward stock-medical: no corporate blue, no white-coat stock photography, no medical-iconography clip art.
- **Don't** add `!important` to any CSS rule. The audit explicitly catches and fails on this.
- **Don't** use em dashes (`—` or `--`) in copy. Use commas, colons, periods, or parentheses.
