---
version: alpha
name: Digital Speed
description: Digital Speed's product design system — engineered clarity paired with controlled energy, built so speed and quality never trade off. All text-bearing components target WCAG AAA contrast.
colors:
  primary: "#FF402D"
  secondary: "#1E1C1F"
  on-secondary: "#FFFFFF"
  tertiary: "#DDF0F6"
  neutral: "#EBEBEB"
  surface: "#FFFFFF"
  on-surface: "#1E1C1F"
typography:
  title:
    fontFamily: RM Neue
    fontSize: 48px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: 0em
  subtitle:
    fontFamily: RM Neue
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.45
    letterSpacing: 0em
  headline-lg:
    fontFamily: RM Neue
    fontSize: 32px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0em
  headline-md:
    fontFamily: RM Neue
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0em
  headline-sm:
    fontFamily: RM Neue
    fontSize: 20px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0em
  body-lg:
    fontFamily: RM Neue
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0em
  body-md:
    fontFamily: RM Neue
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0em
  body-sm:
    fontFamily: RM Neue
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0em
  label:
    fontFamily: RM Neue
    fontSize: 14px
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: 0em
  caption:
    fontFamily: RM Neue
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0em
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 16px
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  xxxl: 64px
components:
  accent:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.none}"
  button-primary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.on-secondary}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.label}"
  button-secondary:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.label}"
  button-tertiary:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.label}"
  input:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.body-md}"
  input-disabled:
    backgroundColor: "{colors.neutral}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.sm}"
    padding: 12px
    typography: "{typography.body-md}"
  card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.md}"
    padding: 24px
    typography: "{typography.body-md}"
  chip:
    backgroundColor: "{colors.tertiary}"
    textColor: "{colors.on-surface}"
    rounded: "{rounded.full}"
    padding: 8px
    typography: "{typography.caption}"
---

# Digital Speed

A single source of truth for Digital Speed's visual identity in UI. Tokens are the normative values; the prose explains why they exist and how to apply them. For voice, tone, and messaging, defer to the `brand-persona` skill.

## Overview

Digital Speed is a product design and development agency that refuses to choose between quality and speed. The UI expresses that combination with two balanced poles: **engineered clarity** — Raisin Black structure, rigid left-aligned sentence case, geometric forms that snap to the underlying grid — and **controlled energy** — a single Scarlet Red accent, deep shadows, precise glow accents carrying the brand's volcanic lava metaphor into motion and state.

Every graphic element earns its place by serving the grid. Decoration is not a substitute for structure. The emotional target is confident, capable, and purposeful — a tool built by practitioners who know what they're doing and who move fast without cutting corners.

## Colors

The palette is a high-contrast core of Raisin Black, Pure White, and Scarlet Red, supported by two calm neutrals — Anti-flash White and Azure — so the single accent keeps its weight on the page.

- **Primary (#FF402D, "Scarlet Red"):** The brand's energetic signature. Reserved exclusively for decorative and non-text contexts — accent blocks, focus rings, active indicators, icons, underlines, and the logotype lockup. Scarlet Red cannot achieve WCAG AAA contrast against any foreground color (the theoretical maximum, pure black, reaches only 6.02:1), so it never sits behind text in this system.
- **Secondary (#1E1C1F, "Raisin Black"):** Structural ink. The default fill for the primary button, navigation, and durable dark surfaces. Also the standard text color on all light surfaces.
- **Tertiary (#DDF0F6, "Azure"):** A soft, slightly-cool blue for pacing dense content. Used on informational surfaces, chips, and quiet callouts.
- **Neutral (#EBEBEB, "Anti-flash White"):** A quiet grey for dividers, disabled states, and secondary surfaces when a second tier of contrast is needed.
- **Surface (#FFFFFF, "Pure White"):** The default canvas. Kept unadorned so hierarchy is established by typography and graphic elements, not by background fill.

**Contrast targets.** All text-bearing components meet **WCAG AAA (7:1 minimum for normal text)**. The actual ratios in this system sit between 14.3:1 and 17.1:1 — well beyond the AAA threshold. AA is treated as the floor, not the ceiling.

**Scarlet Red and text.** Because Scarlet Red cannot reach AAA against any foreground, it is never a text background. The one historical exception the brand allows — Pure White on Scarlet Red for the logotype — sits outside the UI component system and is governed by the brand guidelines, not this spec.

## Typography

The type system uses a single family — **RM Neue** — at two weights: SemiBold for structure, Regular for reading.

- **Title** — RM Neue SemiBold, 48px, 125% line height. One per view for the dominant statement.
- **Subtitle** — RM Neue SemiBold, 28px, 145% line height. Placed directly beneath a title to extend context.
- **Headline lg / md / sm** — RM Neue SemiBold at 32 / 24 / 20px, 150% line height. Structures long-form content and navigational hierarchy.
- **Body lg / md / sm** — RM Neue Regular at 18 / 16 / 14px, 150% line height. The workhorse of the system.
- **Label** — RM Neue SemiBold, 14px, 150% line height. Used on buttons, tags, and interface affordances where voice should feel decisive.
- **Caption** — RM Neue Regular, 12px, 140% line height. Metadata, timestamps, and supporting annotations.

Setting rules are non-negotiable: left-aligned only, sentence case always, tracking at 0%. Never right-align or force-justify.

**Fallback:** When RM Neue is unavailable, substitute **Inter** at the matching weight. Do not substitute any other typeface. If Inter is also unavailable, flag the limitation rather than selecting an unapproved font.

## Layout

The layout uses a **fixed-max-width grid** on desktop (max 1200px) and a **fluid column grid** on mobile. Spacing follows an 8px base scale with a 4px half-step for micro-adjustments, holding the rhythm that keeps dense interfaces calm.

Graphic elements — grid overlays, solid and semi-transparent blocks, directional lines, and geometric insets — extend the layout rather than decorate it. Every element aligns to the underlying grid. A misaligned overlay is a structural defect, not a stylistic choice.

Use `xl` (32px) padding between related groups and `xxxl` (64px) between sections to pace content and signal that the page is engineered, not assembled.

## Elevation & Depth

Depth comes from **tonal layers and controlled glow**, not heavy drop shadows. The brand's volcanic lava metaphor applies: elements rise through contrast shifts, deep shadows in photography, and precise glow accents around active interactive states.

Primary surfaces sit on Pure White. Secondary surfaces shift to Anti-flash White. Informational surfaces use Azure. Modal and overlay scrims use Raisin Black at 72% opacity.

**Interactive state treatments (all use Scarlet Red as accent geometry, never as fill behind text):**

- **Hover:** A 2px Scarlet Red underline reveals beneath the element. Background and text colors do not change, preserving AAA contrast at rest and on hover.
- **Focus:** A 2px Scarlet Red outline is drawn 2px outside the element's boundary.
- **Active / pressed:** The element depresses 1px; a 2px Scarlet Red inset stroke appears along its top edge.

## Shapes

The shape language is **architecturally sharp with measured softening**.

- Interactive elements (buttons, inputs) use a 4px corner radius.
- Cards and grouped surfaces use 8px.
- Pills and chips use a full-radius capsule to read as discrete, tappable affordances.
- Display surfaces (feature cards, modals) scale to 16px when size warrants a softer read.

The logotype rotates only by exactly 90 degrees if rotation is required. Outlined, distorted, image-filled, or low-contrast logo treatments are prohibited.

## Components

All text-bearing components below meet WCAG AAA (7:1) contrast; actual ratios are listed for transparency.

- **accent** — Scarlet Red fill, square corners, no text. The single vehicle for Scarlet Red in the system. Used for decorative blocks, divider stripes, iconography fills, active indicators, and the focus/hover/pressed geometry described in *Elevation & Depth*.
- **button-primary** — Raisin Black fill, Pure White text, 4px radius, 12px padding. Contrast 17.1:1. One per view — the single most important action. Hover adds a 2px Scarlet Red underline; fill and text remain unchanged.
- **button-secondary** — Pure White fill, Raisin Black text, 4px radius. Contrast 17.1:1. Durable structural actions that aren't the primary one. Pair with a 1px Anti-flash White border at render time.
- **button-tertiary** — Azure fill, Raisin Black text, 4px radius. Contrast 14.57:1. Quiet, informational actions.
- **input** — Pure White background, Raisin Black text, 4px radius, 12px padding. Contrast 17.1:1. Pair with a 1px Anti-flash White border; focus state replaces the border with 2px Scarlet Red.
- **input-disabled** — Anti-flash White background, Raisin Black text. Contrast 14.34:1. Text opacity is reduced at render time to communicate non-interactivity.
- **card** — Pure White background, 8px radius, 24px internal padding. Contrast 17.1:1. Group related content; divide internal rows with 1px Anti-flash White.
- **chip** — Azure background, Raisin Black text, full-radius capsule, caption typography. Contrast 14.57:1.

Name variants as `<component>-<state>` (e.g., `input-focus`, `chip-selected`) if a future state requires its own token.

## Do's and Don'ts

- Do target WCAG AAA (7:1) for all text-bearing components — treat AA as the floor, not the ceiling.
- Don't introduce any text-on-color pair below 7:1 without explicit sign-off; document the exception in prose if it's unavoidable.
- Do reserve Scarlet Red for accents — focus rings, underlines, icons, active indicators, and decorative blocks without text.
- Don't use Scarlet Red as a background behind text at any size. Pure White on Scarlet Red fails AA for normal text; no pairing on Scarlet Red can reach AAA.
- Do use Scarlet Red for the single most important *accent* on the view (one primary CTA's underline, one active nav indicator, etc.).
- Don't place more than one Scarlet Red accent in the same view.
- Do keep typography strictly left-aligned and sentence case.
- Don't right-align, force-justify, or set type in ALL CAPS or Title Case as a stylistic choice.
- Do align every graphic element to the underlying grid.
- Don't use graphic elements as decorative filler.
- Do substitute RM Neue with Inter when RM Neue is unavailable.
- Don't substitute with any other typeface — flag the limitation instead.
- Do use volcanic-lava-style photography: macro detail, deep shadows, glow accents, high resolution.
- Don't use stocky, over-retouched, or low-resolution imagery.
- Do rotate the logotype only by exactly 90 degrees if rotation is needed.
- Don't distort, outline, image-fill, or place the logotype on low-contrast backgrounds.
