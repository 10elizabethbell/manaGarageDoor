---
name: MANA Garage Door Services LLC
description: Calm, phone-first trust site for a garage door repair and installation company in DE, MD, PA and NJ.
colors:
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  ink: "#122b4a"
  body: "#2a3a4c"
  soft: "#4a5868"
  navy: "#1a3d66"
  deep: "#0e2340"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d7ea"
  amber: "#f5a623"
  amber-2: "#ffbb48"
  amber-ink: "#8a5300"
  focus: "#1f6fd1"
  error: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(40px, 11.4vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(19px, 5.2vw, 22px)"
    fontWeight: 400
    lineHeight: 1.2
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
rounded:
  field: "10px"
  card: "24px"
  pill: "999px"
spacing:
  gutter: "20px"
  gutter-desktop: "40px"
  band: "64px"
  band-desktop: "96px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.amber-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  input-text:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  service-row:
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    height: "68px"
  step-number:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.amber}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: MANA Garage Door Services LLC

## Overview

**Creative North Star: "The Calm Service Call"**

The site behaves like a good tradesperson on the phone: unhurried, plain, and clear about what happens next. It is Ellie's house calm band style applied to a garage-door company: an off-white paper ground, garage-door navy and deep navy bands, and one safety-amber accent that only ever appears as a fill or as a dedicated darker ink. Full-bleed bands alternate light and dark so each section is obvious on a phone, and nothing on the page competes with the two actions that matter, calling and texting.

Density is low and phone-first. Each band carries one heading, at most one short lede, and one job (the care promise, the service list, three steps, the form, the number). Shapes are soft and borderless; depth comes from band colour, not shadow. Motion is limited to three owner-chosen devices: the hero H1 letter bounce-in, a single 12px fade-up for content below the first screen, and the floating text circle sliding in.

No logo exists, so the palette is chosen rather than extracted: navy for the door, amber for the safety-yellow of a garage door's warning label.

**Key Characteristics:**
- Paper, navy, deep navy, one amber accent; the ground is never black.
- Full-bleed alternating bands (paper, navy, deep-with-texture) as the only structural device.
- One display webfont (Cal Sans, weight 400) over the system body stack at 16/1.7.
- Soft borderless forms: 24px cards, 10px fields, full pills.
- Flat surfaces; the only shadow belongs to the floating text circle.

## Colors

A cool two-navy palette on off-white paper with a single warm safety-amber accent.

### Primary
- **Safety Amber** (`amber`): the one warm accent. Fills only: primary buttons, the step-number discs, the floating text circle, the eyebrow dot, the hover fill of arrow circles, and the accented last phrase of headings on dark bands. Text on it is always Door Ink.
- **Bright Amber** (`amber-2`): hover state of amber fills on pointer devices. Never used at rest.
- **Amber Ink** (`amber-ink`): amber when it must be text or an icon on a light ground (5.9:1 on paper): the accented phrase in light-band headings, the header phone icon and phone hover.

### Secondary
- **Garage-Door Navy** (`navy`): the mid-dark band (services, close) and the Facebook icon on the white row.
- **Night Navy** (`deep`): the hero ground under its photo overlay, the "how it works" band and the footer, always with the diagonal line texture outside the hero.

### Neutral
- **Paper** (`paper`): page ground, header, light bands, `theme-color`.
- **Card White** (`card`): form card and the Facebook row on paper.
- **Field Mist** (`field`): input and chip fill on white cards, and the image placeholder behind the care photo.
- **Door Ink** (`ink`): headings on light, text on amber, selected chip fill.
- **Body Slate** (`body`): running text on light.
- **Soft Slate** (`soft`): ledes, helper text, placeholders, the wordmark subline.
- **Dark-band White** (`on-dark`) and **Dark-band Mist** (`on-dark-soft`): headings and body text on navy and deep bands.
- **Focus Blue** (`focus`): hover and focus outlines for form controls and focus rings on light grounds; amber replaces it as the focus colour on dark bands.
- **Error Red** (`error`): inline error sentences and the invalid field border.

### Named Rules
**The Fill-Only Amber Rule.** Amber is a fill. Text on amber is Door Ink, never white; amber as text on a light ground switches to Amber Ink. Plain amber text appears only on navy, deep or the hero overlay.

**The Two-Navy Band Rule.** Dark bands use exactly two navies: Garage-Door Navy plain, Night Navy with the diagonal line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`). The texture stays at about 3.5% white so it never reads as lines through text.

**The Separate Focus Rule.** Focus and form-hover outlines use Focus Blue on light grounds, distinct from the amber fill, so a focused amber button still shows a ring. On dark grounds the ring turns amber.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** system stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A friendly geometric display face at a single weight (400) does all the speaking in headings, buttons, service rows, field labels and phone numbers; the system body stack stays out of the way for reading.

### Hierarchy
- **Display** (400, clamp(40px, 11.4vw, 80px), 1.02): the hero H1 only, max 13ch, white on the overlay.
- **Headline** (400, clamp(30px, 7.6vw, 48px), 1.08): band headings (h2), balanced wrap.
- **Title** (400, 18-22px Cal Sans, 1.2): service rows, step titles (21-22px), the Facebook row, buttons (18px, line-height 1).
- **Lede** (400, clamp(17px, 4.6vw, 19px), 1.55, max 40ch): the one supporting paragraph under a heading; the hero promise is its sibling at clamp(17px, 4.7vw, 20px) and 30ch.
- **Body** (400, 16px, 1.7): running text; inputs are 16px so iOS does not zoom.
- **Label** (400, 17px Cal Sans, 1.2): form labels and legends; helper `small` text is 14px system in Soft Slate.
- **Phone display** (400, clamp(30px, 9vw, 52px), 1): the closing-band number.

### Named Rules
**The One Weight Rule.** Cal Sans is always weight 400; hierarchy comes from size and band colour, never from bolding the display face. Bold (600) is reserved for short emphasis inside body text.

**The Accent Phrase Rule.** A heading may set its last phrase in the accent colour ("What we fix.", "How it works.", the hero's "Fixed in DE, MD, PA & NJ."): amber on dark, Amber Ink on light. One phrase per heading, at the end.

## Layout

A single centred container (max 1160px) with a 20px phone gutter that widens to 40px at 760px. Bands are full-bleed with 64px vertical padding on phones and 96px from 760px. Section heads are a left-aligned grid (16px gap, max 640px). Phones stack everything in one column; at 760px the hero buttons sit side by side (min 240px each); at 1024px the care band becomes text-left / 4:5 photo-right (1.1fr / .9fr, 72px gap), service rows split into two columns (56px gap), the form band becomes copy-left / card-right (1fr / 1.2fr, 64px gap), the three steps sit in a row, and the close band puts the big phone number bottom-right.

All tap targets are 44px or taller (header links, footer links, rows at 68px, chips at 48px, buttons at 56px).

## Elevation & Depth

Flat. Depth is carried by band colour changes and by white cards sitting on paper, not by shadows. The single shadow in the system belongs to the floating text circle, because it is the only element that floats above content.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,24,46,.3)`): the floating text circle only.

### Named Rules
**The Flat Band Rule.** Cards, rows, buttons and fields carry no shadow at rest or on hover. If something needs separation, change the ground colour.

## Shapes

Soft and borderless. Three radii only: 10px for fields, 24px for cards and the care photo, full pill (999px) for buttons, chips and eyebrows; circles for arrow badges (44px), step discs (48px) and the floating text circle (60px). Borders appear only as hairline row rules on navy (`1px solid rgba(255,255,255,.14)`), the ghost button outline, and the transparent 2px border on fields and chips that turns Focus Blue or Error Red on state.

## Components

### Buttons
Pill-shaped, tall, set in Cal Sans; confident without being loud.
- **Shape:** full pill, 56px tall, 26px side padding, 2px border.
- **Primary:** Safety Amber fill and border, Door Ink text. Full width inside the form card.
- **Hover / Focus:** Bright Amber on hover (pointer devices only); `scale(.98)` on press; inside the form the hover and focus add a 2px Focus Blue outline offset 2px.
- **Ghost:** transparent with a 70%-white outline and Dark-band White text, for dark grounds only; hover firms the border to white over a 10% white wash.
- At most two buttons per group (one primary, one ghost).

### Chips
- **Style:** Field Mist pill, 48px tall, 18px side padding, 16px system text in Door Ink, visually hidden native checkbox or radio behind it.
- **State:** hover gives a Focus Blue border; selected fills Door Ink with white text; focus and selected-hover use an offset outline (not a border) so they stay visible on the ink fill.

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** Card White on paper.
- **Shadow Strategy:** none (Flat Band Rule).
- **Border:** none.
- **Internal Padding:** clamp(20px, 5vw, 32px); fields inside sit 22px apart.

### Inputs / Fields
- **Style:** Field Mist fill, 10px radius, transparent 2px border, 16px system text, 52px min height (textarea 110px, vertical resize).
- **Focus:** border turns Focus Blue; hover does the same on pointer devices.
- **Error:** border turns Error Red and stays red while focused; a plain-sentence error appears below in Error Red at 15px.

### Navigation
A slim paper header: the MANA wordmark (Cal Sans 22-25px, .04em tracking) over an uppercase 11.5-12px "Garage Door Services" subline at left, the tap-to-call number in Cal Sans 17-20px with an Amber Ink phone icon at right. 64px tall, 76px from 760px. No menu. The footer is Night Navy with the texture, holding the name and a Facebook link.

### Service Rows (signature)
On Garage-Door Navy, each service is a full-width link row (68px, Cal Sans clamp(19px, 5.2vw, 22px)) between hairline rules, ending in a 44px arrow circle (10% white). On hover only the arrow changes, filling amber with ink arrow; focus fills the arrow and rings it in amber. Tapping a row pre-selects its chip in the form. One column on phones, two from 1024px.

### Link Row on Paper
The same arrow-circle pattern as a white rounded row on paper (72px, 20px radius, 28px navy icon): used for the Facebook link.

### Numbered Steps
On Night Navy, a counter-driven list: 48px amber disc with an ink numeral in Cal Sans, a 21-22px Cal Sans title in Dark-band White and one line of body below.

### Eyebrow Pill (owner exception)
Ellie chose these on 2026-10-19 (calm band style item 5), against Impeccable's general rule. A quiet 14px label pill (500 weight, 9px 14px padding) with a 7px amber dot: 6% ink wash on paper, 12% white wash on dark. Above the hero H1 and a few section heads only, marked up as `<p>`, never a heading. No arrow, no hover, no shadow, never a full amber fill, so it can't read as a button.

### Hero
The Night Navy hero holds a photo with `object-fit: cover` under a navy overlay (vertical 86/78/90% on phones; horizontal 94% to 55% from 760px so the copy side stays dark). It carries the eyebrow, the H1, one promise line, and the two-button group. The H1 bounces in letter by letter (opacity 0, 50px right, `1s cubic-bezier(.34,1.56,.64,1)`, 20ms stagger), JS-only, skipped under reduced motion, and the plain heading is restored after the last letter lands. No other heading animates.

### Floating Text Circle
A 60px amber circle with an ink chat icon, fixed bottom right (16px plus safe-area inset), opening a pre-filled `sms:`. It slides up (`.35s cubic-bezier(.2,.8,.2,1)`) once the hero leaves view and hides while the form is on screen; when hidden it is `tabIndex=-1` and `aria-hidden`. Always a single circle, never a bottom bar.

## Do's and Don'ts

### Do:
- **Do** alternate full-bleed bands (paper, navy, deep-with-texture) so every new section is obvious on a phone.
- **Do** put text on amber in Door Ink, and switch to Amber Ink whenever amber must be text on a light ground.
- **Do** set every heading, button, row and label in Cal Sans 400, and body in the system stack at 16/1.7.
- **Do** keep fields on Field Mist inside white cards, and keep the invalid border red even when focused.
- **Do** outline form controls in Focus Blue on hover and focus; use offset outlines (not borders) on filled chips.
- **Do** use the 12px, 400ms fade-up only for elements that start below the first screen, and leave everything visible without JS or under reduced motion.
- **Do** keep tap targets at 44px or more.

### Don't:
- **Don't** put white text on amber, or plain amber text on paper or white.
- **Don't** add shadows to cards, rows, buttons or fields; the floating text circle is the only lifted element.
- **Don't** animate any heading other than the hero H1.
- **Don't** add a second accent colour, a second body font, or a bold Cal Sans weight.
- **Don't** let an eyebrow pill take a hover state, an arrow, a shadow or a full amber fill.
- **Don't** put two controls that do the same thing in view at once (the floating circle hides over the form).
- **Don't** raise the diagonal band texture above about 4% white.
