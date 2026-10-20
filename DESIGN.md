---
name: Martinez Construction
description: William Martinez, mason. Calm paper and flyer-navy bands, one gold thing to do.
colors:
  navy: "#16295a"
  deep: "#0a1633"
  ink: "#0a1633"
  gold: "#e3bf66"
  gold-light: "#efd08a"
  gold-ink: "#7a5a12"
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  body-text: "#26324a"
  soft-text: "#4a5568"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c6d0e4"
  focus: "#2b5cab"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  headline-phone:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  title-claim:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  title-link:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(19px, 5.2vw, 22px)"
    fontWeight: 400
    lineHeight: 1.2
  title-row:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(18px, 5vw, 20px)"
    fontWeight: 400
    lineHeight: 1.2
  title-step:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  numeral:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  phone-header:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1
  phone-header-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  who:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(18px, 5vw, 20px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  input:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.4
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1
rounded:
  field: "10px"
  row: "20px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter-phone: "20px"
  gutter-desktop: "40px"
  section-phone: "64px"
  section-desktop: "96px"
  column-gap: "64px"
  tight: "8px"
  control-gap: "10px"
  row-gap: "12px"
  stack: "16px"
  field-gap: "20px"
  item-gap: "24px"
  block-gap: "28px"
components:
  button-primary:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.gold-light}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-line:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "52px"
  header:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    height: "64px"
  meet-card-portrait:
    backgroundColor: "{colors.field}"
    rounded: "{rounded.circle}"
    size: "112px"
  claim-list:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.title-claim}"
    padding: "16px 0"
  service-row:
    textColor: "{colors.on-dark}"
    typography: "{typography.title-row}"
    rounded: "{rounded.row}"
    padding: "12px 14px 12px 22px"
    height: "68px"
  link-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-link}"
    rounded: "{rounded.row}"
    padding: "14px 16px 14px 22px"
    height: "76px"
  row-arrow-hover:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  step-marker:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    typography: "{typography.numeral}"
    rounded: "{rounded.circle}"
    size: "48px"
  form-card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  input:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.input}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  float-text:
    backgroundColor: "{colors.gold}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
---

# Design System: Martinez Construction

## Overview

**Creative North Star: "The Level Course"**

The site is laid like a course of bricks: full-width bands set straight and level, each holding one heading, one quieter line and at most two actions, with nothing out of plumb. It is the calm band style learned from lpmr.co.uk, coloured from William's own profile flyer: an off-white paper ground, the flyer's navy in two depths, and the flyer's gold as the single warm accent. A rounded display face at its one regular weight carries every heading, button, label and phone number; the body is the device's own sans, set loose.

Density is low and the voice is a person, not a company. The one photograph is William's portrait in a small circle right under the hero; there is no job photography, because the flyer's job pictures are illustrations and not his work, so the hero is a plain navy band with a faint diagonal line texture rather than an image. Gold is a fill for the thing to do (buttons, step numerals, the floating text circle, a hovered arrow) and, on dark bands only, the last phrase of a heading. Proof is a plain divided list on paper, and the service list is a grid of quiet translucent rows on navy where only the arrow answers a pointer.

The build rejects the trades-site default (stock-photo hero over a twelve-icon services grid) and any decoration that competes with the words: no illustrations, no divider shapes, no ambient motion beyond the headline's one entrance.

**Key Characteristics:**
- Three grounds: paper, navy and deep navy. The hero and every deep band carry the faint 135° line texture; the services navy is plain.
- Gold as a fill; gold-ink only when gold must be a glyph or text on light.
- Cal Sans (self-hosted, latin subset) at weight 400 for every heading, button, label and phone number; system sans body at 16px/1.7.
- Generous rounding: 24px cards, 20px rows, 999px pills, 10px fields, circles for markers and the portrait.
- Flat DOM with one exception: the floating text circle's soft shadow.
- Straight band edges; the hero is sized to its content, not to the screen.
- Tap targets 44px minimum, buttons 56px, reading text 16px or larger.

## Colors

A cool, calm palette: off-white paper and the flyer's two navies, warmed by a single flyer gold.

### Primary
- **Flyer Navy** (`navy`): ground of the hero (with the line texture) and the services band (plain). The browser `accent-color` and the caret in fields.
- **Deep Navy** (`deep`): ground of the closing band and the footer, always with the line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`). Same hex as Ink, and the ground of the hammer mark's badge; the two names mark the ground role and the text role.

### Secondary
- **Flyer Gold** (`gold`): fill of the primary button, the step numerals, the floating text circle, the row arrow on hover and focus, and `::selection`. On dark bands it is also the accent phrase in a heading ("built right.", "build."), the closing phone glyph and link hovers, and the focus ring colour. It is the hammers-and-bricks colour in the mark.
- **Gold Light** (`gold-light`): primary button hover fill only.
- **Gold Ink** (`gold-ink`): gold when it has to be a glyph or text on light (5.9:1 on paper): the header phone glyph and its hover text, the claim-list icons, an accent on a light band.

### Tertiary
- **Focus Blue** (`focus`): the hover and focus colour for controls on light grounds: 3px rings, the 2px field and chip borders, the 2px outline on the submit and line buttons. Brighter than navy so it reads against the white card and the field fill (5.5:1 on field), and deliberately not gold, so a gold-filled control is never outlined in its own colour.

### Neutral
- **Paper** (`paper`): page ground, header ground, the `theme-color`.
- **Card** (`card`): the white form card on paper and the white Facebook row on navy; selected-chip text.
- **Field** (`field`): text-field and chip fill inside the white form card, and the portrait's placeholder fill.
- **Ink** (`ink`): headings and labels on light, text on gold, the selected-chip fill, the line-button label and border.
- **Body Text** (`body-text`): running text on light.
- **Soft Text** (`soft-text`): ledes, step details, "(optional)" captions, placeholders, the note under the submit button, the wordmark subline, the portrait caption.
- **On-Dark** (`on-dark`): headings, row labels, ghost-button label and footer links on navy; the hero H1 itself is pure white.
- **On-Dark Soft** (`on-dark-soft`): running text, the promise line and ledes on navy and deep.
- **Error Red** (`error-red`): field error border and the error message, on the white form card.

Translucent tints are derived, not tokens: the hairline between claims is ink at 12%; a service row is white at 6% on navy, its arrow well white at 10%; the Facebook row's arrow well is ink at 7%; the ghost border is on-dark at 70% and its hover wash white at 10%; the footer's top hairline is white at 8%. The Facebook glyph keeps Facebook's own blue (`#1877f2`) as a brand mark, not a palette colour.

### Named Rules
**The Gold Is A Fill Rule.** Flyer gold appears as a filled shape or, on navy and deep, as type and glyphs. On paper or white it is never text; use gold-ink there.

**The Accent On Dark Rule.** An accent phrase inside a heading is gold, and only on navy or deep bands. Headings on paper stay all ink.

**The Two Focus Colours Rule.** On light grounds, hover and focus use focus blue; on navy and deep bands the ring turns gold. Gold is never the outline of a gold-filled control on light, and focus blue never sits on a dark ground.

## Typography

**Display Font:** Cal Sans (SIL OFL, self-hosted latin subset, preloaded, `font-display: swap`), falling back to Avenir Next, Segoe UI, system-ui
**Body Font:** system sans stack (-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif)
**Label/Mono Font:** none distinct

**Character:** A rounded, geometric display face at its single regular weight, set in sentence case with a hair of negative tracking, next to a plain native body face set loose and readable. Sturdy and friendly, never shouty.

### Hierarchy
- **Display** (`display`): the hero headline only, white, max 12ch; its accent phrase is gold.
- **Headline** (`headline`): section headings, balanced wrap. The closing phone number runs at `headline-phone`.
- **Title**: claim-list labels (`title-claim`), the Facebook row (`title-link`), the service rows (`title-row`), step titles (`title-step`). William's name in the meet card is a 22px/1.15 Cal Sans title, one step above the step titles.
- **Button / Label / Phone**: Cal Sans at 18px for buttons (17px in the post-submit fallback), 17px for form labels and legends, 17px (20px from 760px) for the header phone number, 20px for step numerals.
- **Promise / Lede / Who** (system face): the hero promise line (max 32ch on phones, unbounded from 760px), the line under a heading (max 38ch), the closing "who" line.
- **Body** (`body`): everything else, including the note under the submit button and error messages; `input` sets field text at 16px/1.4.
- **Caption** (`caption`, 14px): the "(optional)" marker beside a field label, the only reading text under 16px.

### Named Rules
**The One Weight Rule.** Cal Sans is only ever weight 400 and sentence case. Hierarchy comes from size, colour and ground, never from bolding or uppercase. The only bold is a 600-weight name inside body copy (the promise's "William Martinez.").

**The Sixteen Floor Rule.** Reading text and form inputs are 16px or larger (prevents iOS zoom). The 14px caption is the only smaller reading size and is never the main message.

**The Font Waits Rule.** The bounce-in holds its letters (paused, at most 400ms) until Cal Sans has loaded, so the font swap never reflows letters mid-flight.

## Layout

A single centred column (max 1160px) with 20px gutters on phones and 40px from 760px. Bands are padded 64px top and bottom on phones and 96px from 760px. Breakpoints: 760px (desktop gutters, section padding, hero buttons in a row, service rows two-up) and 1024px (two-column meet and form bands with a 64px gap, three-up service rows, the close band beside the big number). Two narrow-phone guards: under 375px the header lockup and number shrink; under 381px chip padding tightens from 18px to 14px.

Band order: paper header, textured navy hero, paper meet, plain navy services, paper estimate, textured deep close, textured deep footer (separated from the close by an 8% white hairline). Bands otherwise meet on straight edges with no dividers.

The hero is sized to its content: 64px top and 72px bottom padding on phones, 96px / 112px from 760px, with 20px between the items. On phones the two hero buttons stack full width with a 12px gap; from 760px they sit in a row at 240px minimum each.

From 1024px the meet band puts the portrait card and intro in the left column and the claim list in the right; the estimate band is 1fr / 1.2fr, with the heading and steps sticking 40px from the top beside the form; the close band sets its copy left and the big number right, bottom-aligned with a 48px gap.

Rhythm inside bands: 16px between heading and lede; 28px between blocks; 32px from a heading block to the service rows and 12px between rows; 24px to the Facebook row; 20px between form fields and 8px from label to field; 16px vertical padding on hairline-divided claims; 24px between steps. The footer pads 48px top and 96px plus the bottom safe area below, clearing the float circle.

### Named Rules
**The Number Top-Right Rule.** On the first screen the phone number appears once, as a tap-to-call link in the header's top-right corner. Under the hero headline there are at most two buttons, and neither is a Call button. The number comes back in the form's fallback and the closing band.

**The One Circle Rule.** The only fixed element is a single 60px gold text circle, bottom-right with 16px plus safe-area insets. It appears after the hero leaves view and hides while the form is on screen. Never a sticky bottom bar, never a call button.

**The Clear Zone Rule.** Nothing runs behind text except the faint 135° lines on the hero and deep grounds. No images, shapes or motion sit behind headings or copy, and bands meet with straight edges, never a divider shape.

## Elevation & Depth

The DOM is flat. Cards lift off their ground by tone (white on paper, white on navy), fields sit into the white card by tone (field blue inside white), service rows lift off navy by a 6% white wash, and the hero and deep grounds get a whisper of texture from the 135° lines. The one shadow is the floating text circle, because it floats over every ground.

### Shadow Vocabulary
- **Float** (`box-shadow: 0 10px 28px rgba(6,14,34,.3)`): the floating text circle only.

### Named Rules
**The Floating Only Rule.** A DOM shadow is reserved for the one element that floats over content. Cards, rows, buttons and fields get tone, never shadow, and hover never adds one.

## Shapes

Soft and generous. The form card takes 24px corners; the service rows and the Facebook row are a slightly tighter 20px because they are single short rows. Buttons, chips and the eyebrow are full pills (999px). Text fields use 10px corners. Circles mark four roles: the portrait (112px), step numerals (48px), the row arrow well (44px) and the floating text circle (60px). The hammer mark sits on the one rounded square, its corner drawn at 14/64 of its size. Borders are 2px where they appear (button outlines, field and chip borders, transparent at rest so focus never shifts layout). Focus rings are 3px with a 3px offset (2px/2px on the submit and line buttons).

Off-system by design: the focus ring's 6px corner, a browser-outline softening rather than a surface radius.

## Components

### Buttons
Big, round and thumb-sized.
- **Shape:** pill, 56px minimum height, 26px side padding, 2px border, Cal Sans 18px label, optional 20px line icon with a 10px gap.
- **Primary:** gold fill and border, ink label. Full width inside the form, where it carries the chat glyph ("Text this to William").
- **Hover / Focus:** hover (pointer devices only) lightens to gold-light over 0.2s; press scales to 0.98 (0.12s). On dark bands focus is the gold ring; inside the form the submit button takes a 2px focus-blue outline at 2px offset on hover and focus.
- **Ghost:** transparent with a 2px on-dark border at 70% and an on-dark label; hover turns the border white and adds a 10% white wash. The hero's second action ("See what I build") on navy, never filled.
- **Line:** transparent with a 2px ink border and ink label, 52px tall, full width, 17px. Only in the post-submit fallback ("Open in Messages", "Copy message"); hover adds the 2px focus-blue outline.

### Navigation (Header)
A paper bar, 64px tall (76px from 760px), respecting the top safe area. Left: the hammer mark (36px; 30px under 375px), William's crossed gold hammers over a course of three gold bricks on a deep-navy rounded square, beside the wordmark lockup (Cal Sans "Martinez" over a small uppercase soft-text "Construction"). The lockup's sizes (21px, 24px from 760px, 19px under 375px; 11px tracked subline) are drawing values for the wordmark, kept off the type ramp; the uppercase subline is not a label style to reuse. Right: the phone number as a tap-to-call link in Cal Sans with an 18px gold-ink phone glyph; hover turns the text gold-ink. No menu.

### Hero
A plain navy band with the line texture, no image. Content in order: the small pill label (see the note under Do's and Don'ts), the H1 with its last phrase in gold, one promise line in on-dark-soft naming William in 600-weight on-dark, then the primary and ghost buttons.

### Hero Headline Bounce-In
The hero H1 only (after lpmr.co.uk, Ellie's pick). JS splits it into letters inside nowrap word wrappers, keeping the gold accent span. Each letter slides in from 50px right and fades from 0 over 1s on `cubic-bezier(.34,1.56,.64,1)` (back-out, the slight overshoot is the bounce), 20ms apart, held until Cal Sans loads (400ms cap). The H1 carries an `aria-label` with the full text and the letter wrappers are `aria-hidden`. When the last letter lands, the plain heading is restored so kerning and selection come back. No JS or reduced motion: the plain heading shows straight away. Never on other headings.

### Meet Card
The first thing under the hero: William's portrait in a 112px circle (field fill behind it while loading) beside his name in 22px Cal Sans ink and "Mason, Martinez Construction" in soft text, 18px gap. It is the only photograph on the site and is not a card surface: no fill, no border, straight on paper.

### Claim List
A quiet list straight on the paper: a 40px gold-ink line icon (stroke 2.4, round caps) and a Cal Sans title label per row, 16px gap, 16px vertical padding, hairline dividers between rows. No card, no fill, so it never reads as tappable.

### Service Rows
The services as a list of links on plain navy: one column on phones, two from 760px, three from 1024px, 12px gaps. Each row is a 6% white wash with 20px corners, 68px minimum height, an on-dark Cal Sans label and a 44px circular arrow well (white at 10%) pushed right. Every row links to the form and pre-selects the matching job chip.
- **Hover:** only the arrow well changes, to a gold fill with an ink arrow (0.2s). The row itself never gets an outline, tint or shadow.
- **Focus:** the row's own ring is suppressed; the arrow well fills gold and takes a 3px gold ring at 3px offset.

### Link Row (Facebook)
Under the service rows, a white row (max 480px, 20px corners, 76px minimum height) with a 30px Facebook glyph in Facebook blue, a Cal Sans `title-link` label and the arrow well at ink 7%. Same hover rule: only the arrow turns gold. Focus fills the arrow gold with a 3px focus-blue ring, because the ring sits on the white row.

### Steps
A numbered list in the estimate band's heading column, on paper. Each item has a 48px gold circle holding a Cal Sans 20px ink numeral, then an ink Cal Sans 21px title and a soft-text detail line, 16px from the numeral, 24px between items. Static; no cards, no connectors.

### Estimate Form
A white card (24px corners, 20–32px padding, max 600px, 20px between fields) that composes a text message to William rather than posting anywhere.
- **Fields:** tinted field-blue fills, ink 16px text, 2px transparent border, 10px corners, 13px/14px padding, 52px minimum height (textarea 120px, vertical resize). Labels sit above in Cal Sans 17px; "(optional)" is a 14px soft caption. Hover and focus turn the border focus blue (0.15s); the border is the focus, no ring.
- **Error:** name and town are required. A missing one turns the border error red, shows a 16px red message below and takes focus; the error clears as soon as the visitor types.
- **Handoff:** submit builds "Hi William, this is …" with the job, town and details. On a phone it opens Messages with the text filled in, then after 900ms shows the fallback in case Messages didn't open. On a computer (fine pointer with hover), which can't send a text, the fallback shows straight away.
- **Fallback:** a status region in 600-weight ink: a line with the tap-to-call number, then two full-width line buttons, "Open in Messages" (the same `sms:` link) and "Copy message" (copies to the clipboard and reads "Copied", or reveals the message selected for manual copy). Without JS a call-or-text line replaces it. A soft 16px note under the button says what submit does.

### Chips (form choices)
The job choice as radio inputs drawn as 48px pills on field fill, 18px padding (14px under 381px), 16px ink system text, 2px transparent border, 10px gaps, wrapping.
- **Selected:** ink fill, white label.
- **Hover / Focus:** focus-blue border on hover; a 3px focus-blue ring at 2px offset on keyboard focus. Chips exist only as real form controls.

### Close Band
Textured deep navy. "Martinez Construction" as the headline, the "who" line in on-dark-soft, a short line inviting a call, and the big phone number in Cal Sans `headline-phone` on-dark with a gold phone glyph at 0.8em, 56px minimum height; hover turns it gold.

### Footer
Textured deep navy with an 8% white top hairline: the copyright line and a Facebook link as a 44px target, on-dark, gold on hover. Bottom padding clears the float circle.

### Floating Text Circle
A 60px gold circle with a 26px ink chat glyph. On phones it opens Messages with "Hi William, I found your website…" prefilled; on a computer (fine pointer with hover) it links to the estimate form instead and is labelled "Get a free estimate". It slides up from 120px below the viewport (0.35s, `cubic-bezier(.2,.8,.2,1)`) once the hero is out of view and slides away while the form is on screen; while hidden it is `tabIndex=-1` and `aria-hidden`. Its focus ring is focus blue and circular. One config switch (`CONFIG.FLOAT`) removes it.

### Fade-Up
The single scroll motion: `.rise` elements that start below the first screen rise 12px and fade in over 400ms ease-out as they enter (8% from the bottom edge). Everything above the fold, without JS and under reduced motion is visible at rest. Smooth anchor scrolling is on, off under reduced motion; reduced motion also removes button, float and fade transitions and the bounce-in. There is no other ambient motion.

## Do's and Don'ts

### Do:
- **Do** alternate paper with navy or deep bands and let them meet on a straight edge; the hero and deep bands carry the faint line texture, the services navy is plain.
- **Do** take the palette from the client's own material (here William's flyer navy and gold and his hammer mark) and keep gold as the one warm accent.
- **Do** use gold as a fill for the primary action, step numerals, the hovered arrow and the float circle, and gold-ink when gold must be a glyph or text on light.
- **Do** set every heading, button, label and phone number in Cal Sans at weight 400, sentence case, self-hosted and preloaded.
- **Do** put the form in a white 24px card on paper, the claims in a plain divided list, and the services in quiet rows where only the arrow answers hover.
- **Do** show hover and focus in focus blue on light grounds and in gold on dark bands, with a 3px ring at a 3px offset.
- **Do** put hover styles inside `@media (hover:hover)` so taps don't leave them stuck, and send desktop visitors to the form wherever a phone would get a text link.
- **Do** keep tap targets at 44px minimum and buttons at 56px, with reading text at 16px or larger.
- **Do** use only the client's real photographs; with none that fit the hero, keep the hero a plain textured navy band and put the portrait under it.
- **Do** keep motion to the hero H1 bounce-in, the below-the-fold fade-up and the float circle, all off under reduced motion.

### Don't:
- **Don't** set flyer gold as text on paper or white.
- **Don't** put a gold accent phrase in a heading on a paper band.
- **Don't** bold or uppercase Cal Sans.
- **Don't** add a box-shadow to cards, rows, buttons or fields; the floating text circle is the only shadowed element.
- **Don't** tint, outline or lift a whole service or link row on hover; only its arrow changes.
- **Don't** show the phone number twice on the first screen, put a Call button under the hero headline, or add a sticky bottom bar.
- **Don't** use the flyer's illustrated job pictures, or any image that isn't William's own work, as if it were his.
- **Don't** let any texture other than the faint lines run behind text, or join bands with divider shapes, curves or images.
- **Don't** style non-interactive labels as chips.
- **Don't** add decorative motion (ambient animation, sheens, particles) or put the bounce-in on any heading but the hero H1.

**Carried, not canonized.** The build has three small pill labels above headings (hero "Masonry and concrete", services, estimate form): 14px/500 system text with a gold dot on a 6% ink tint (12% white on dark). They are in the build by Ellie's house-style decision for this calm style and are kept quiet (no arrow, no hover, no shadow, no gold fill), and they are a craft-floor exception that Ellie keeps on purpose: use them above the hero headline and a few key section headings on new pages too (calm-photo-style.md item 5), never on every heading, and never styled like a button.
