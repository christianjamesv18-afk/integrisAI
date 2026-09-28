# NewWave $49 Spinal Decompression funnel: GHL sections

Five standalone blocks. Each one carries its own styles, so you can paste them in any order and they won't affect each other or the rest of your GHL page.

| # | File | What it is |
|---|------|------------|
| 1 | `sections/01-hero.html` | Offer headline, subheadline and a button that jumps to booking |
| 2 | `sections/02-booking.html` | Booking card (where your calendar goes) plus the location card and map |
| 3 | `sections/03-whats-included.html` | The 6 included services and a CTA button |
| 4 | `sections/04-video.html` | Video frame (empty for now) and a CTA button |
| 5 | `sections/05-footer.html` | Address, phone, disclaimer, copyright and privacy link |

`preview.html` shows all five together, for viewing only. Don't paste it into GHL.

## How to paste into GHL

For each file, in order:

1. Add a **Section**. In its settings, set width to **Full Width** and padding to **0** (top, bottom, left and right).
2. Add a **1-column Row**. Set it to full width with padding 0 as well.
3. Drag in a **Custom JS/HTML** element and paste the **entire** file contents into it.

## Three things to fill in

1. **Calendar** (`02-booking.html`): find the line that says `CALENDAR PLACEHOLDER`. Replace that whole `<div class="nwm-book-placeholder">...</div>` line with your GHL calendar embed code. You get the embed code from Calendars → Calendar Settings → your calendar → **Embed Code**.
2. **Video** (`04-video.html`): find the line that says `VIDEO PLACEHOLDER`. Replace that whole `<div class="nwm-vid-placeholder">...</div>` line with your YouTube, Vimeo or `<video>` embed. It fills the 16:9 frame on its own.
3. **Privacy Policy link** (`05-footer.html`): change `href="#"` to your policy page URL.

## If the page shows CSS as plain text

That means GHL didn't apply the `<style>` block. Check that each file went into a **Custom JS/HTML** element (not a Text or Paragraph element), that you pasted the **whole** file from the first line to the last, and that you clicked **Save** in the code editor.

All the "Book / Claim" buttons scroll to the booking section (`#nwm-book`), so keep section 2 on the same page.
