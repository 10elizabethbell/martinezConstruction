# Martinez Construction — handoff at ~60%

**Live:** https://10elizabethbell.github.io/martinezConstruction/ · **Repo:** https://github.com/10elizabethbell/martinezConstruction · **Built:** 2026-10-20 from Muse brief (run 2026-10-20) · On the Call Sheet: yes

## What's built
- One page, phone first, in the calm band style: paper header (hammer-and-bricks mark, wordmark, tap-to-call (704) 685-6486 top right) → plain textured navy hero → "Meet William" on paper → "What I build" (12 service rows) on navy, with the Facebook row under it → free-estimate form on paper (3 steps on the left on desktop) → deep textured close band with the big number → footer.
- Palette from William's own profile flyer: navy #16295a, deep #0a1633, gold #e3bf66 as a fill only (#7a5a12 when gold has to be text on light), paper #f4f6fb. Form hover/focus outline is blue #2b5cab.
- Cal Sans is self-hosted (`cal-sans-latin.woff2`, SIL OFL), with no Google Fonts request.
- The hero H1 bounces in letter by letter. It waits up to 400ms for Cal Sans so the font swap doesn't reflow it. Below the first screen there's a 12px fade-up. Under reduced motion or with no JS, everything shows at once.
- **Floating circle:**
  - On phones it texts William.
  - On computers it goes to the estimate form, since a computer can't send a text.
  - It's hidden on the hero and while the form is on screen.
- **Estimate form:**
  - Job chips (optional), name and town (required), notes (optional).
  - It composes a text to +1 704-685-6486.
  - If no messages app opens (desktop, some in-app browsers), it offers "Open in Messages", "Copy message" and the number.
  - Tapping a service row pre-selects its chip and scrolls to the form.
- The favicon, home-screen icon and header mark are redrawn from his logo badge (crossed hammers over bricks). `og.png` is 1200×630.

## Assumptions I made
- **No hero photo:**
  - The flyer's 12 job pictures are AI-style illustrations, not William's jobs: the lighting is too clean, the people are generic, and the scenes are stock-perfect. Showing them as his work would be dishonest, so none are used.
  - The only real photo is his profile portrait, cropped to his face (flyer graphics and the background truck cropped out). It's used in the Meet card, not the hero: it's 180px of source, far too small for a hero.
- **No place in the H1** (breaks calm item 6 on purpose). The brief says not to publish a location: 704 is the Charlotte area and the flyer says "NC & SC", but he advertised in an NJ/PA group. When Ellie confirms, the swap is ready: "Brick, block and stone, built right in <town>" or "…across the Carolinas".
- **First person ("I", William).** His profile flyer is "William Martinez – Masonry Expert"; the Facebook caption says "call us". Switch to "we" if he works with a crew.
- **Not claimed, though his flyers say them** (the brief says verify first): NC & SC licensed & insured, guaranteed work, "5 star quality", many years of experience.
- **Services** are rebuilt from the flyer image (not the OCR): driveways & slabs, block walls, walls & fences, retaining walls, stone steps, brick & stone patios, fireplaces & chimneys, stone veneer, mailboxes, foundations, house construction, masonry repairs.
- **Copy I wrote in his voice:** "You'll live with this work for years", "straight, level and solid", "done like it's my own home". Ellie, check the tone.

## Placeholders and gaps
- **Texts unknown.** The brief only says "call us". The form and the floating circle both send a text, so confirm William reads texts on 704-685-6486 before handover. If he doesn't, switch the form to "Call me" and the circle to `tel:`.
- No email (the footer has none; add it there only).
- No real job photos, no before/afters, no reviews, no hours, no service area.
- **Facebook link:** it goes to the personal profile `profile.php?id=100095738580830` ("Martinez Construcció"), and its label is "Find me on Facebook". Change it to "Click to see more of my work." once we know that profile shows real jobs.
- The portrait is 260px for a 112px circle, so it's slightly soft on 3x iPhones. A larger original from William would fix it.

## Questions for the owner
1. Can people text you at 704-685-6486?
2. Which towns or counties do you work in?
3. Can you send 6–10 photos of real jobs (before/after if you have them)?
4. Licence and insurance details, so we can say "Licensed & insured" truthfully. Do you guarantee your work, and for how long?
5. Years in the trade? Just you, or a crew?
6. An email for the footer? Hours?
7. Is the business name "Martinez Construction" or "Martinez Construcción"?

## Ideas not built (yours to pick)
- **Signature motion (opt-in):**
  - Runner-up world: **"lay the course"**, where bricks set themselves row by row along the hero's bottom edge with a trowel stroke of mortar, and a drag lays more.
  - Other worlds considered: wet concrete being screeded smooth by a finger drag; a stone wall assembling from irregular stones; mortar joints being struck along a brick panel.
- Once real photos arrive, put one in the hero under the navy overlay (calm style default), and add a 4:5 work-photo card grid above the Facebook row.
- Before/after sliders if he has pairs (repairs are a natural fit).
- Desktop hero right half is empty navy; a portrait-free option is a large hammer-and-bricks mark or, later, a job photo.
- **Impeccable / finish-review findings I left because Ellie chose them:**
  - eyebrow pills (the craft floor bans eyebrows)
  - repeating-stripe band texture (detector advisory; suppressed for this file in `.impeccable/config.json`)
  - letter bounce-in
  - floating circle
  - Cal Sans
- I also suppressed the detector's "flat type hierarchy" finding. It only reads the fixed small UI sizes; the headings use clamp() at 30–80px.

## Not verified
- On real devices: touch, and the SMS handoff from Facebook's in-app browser on iOS and Android. The in-app browser may block `sms:` until it's tapped; the "Open in Messages" fallback covers that.
- Clipboard copy inside Facebook's in-app browser. If it's blocked, the message is shown and selected instead.
- Frame rate on old phones (motion is CSS-only and light).
- The licence claim against the NC/SC registries (not claimed on the page).
