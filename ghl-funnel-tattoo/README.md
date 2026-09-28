# NewWave $49 Laser Tattoo Removal funnel: GHL sections

Nine standalone blocks. Each one carries its own styles and animations, so paste them in order and they won't affect each other.

| # | File | What it is |
|---|------|------------|
| 1 | `sections/01-hero.html` | Offer headline, 3 pills and a "Claim My $49 Voucher" button |
| 2 | `sections/02-voucher.html` | Voucher card with your GHL form and a "Good to Know" tattoo-size card |
| 3 | `sections/03-whats-included.html` | The 3 included services and a CTA button |
| 4 | `sections/04-video.html` | Video frame (empty for now), a Rohrer Spectrum note and a CTA button |
| 5 | `sections/05-about.html` | "Get Hope, Help & Answers" text, 2 photo slots, Dr. Matthew Wilson and a CTA button |
| 6 | `sections/06-reviews.html` | 8 Google reviews as cards and a "Read More Reviews on Google" button |
| 7 | `sections/07-location.html` | Address, phone, office hours and the map |
| 8 | `sections/08-final-cta.html` | Closing offer recap and a CTA button |
| 9 | `sections/09-footer.html` | Address, phone, disclaimer, copyright and privacy link |

`preview.html` shows all nine together, for viewing only. Don't paste it into GHL.

## How to paste into GHL

For each file, in order:

1. Add a **Section**. In its settings, set width to **Full Width** and padding to **0** (top, bottom, left and right).
2. Add a **1-column Row**. Set it to full width with padding 0 as well.
3. Drag in a **Custom JS/HTML** element and paste the **entire** file contents into it.

## Things to fill in

Your GHL form ("Laser Tattoo Removal Treatment Special") is already embedded in `02-voucher.html`.

1. **Video** (`04-video.html`): find the line that says `VIDEO PLACEHOLDER`. Replace that whole `<div class="nwm-vid-placeholder">...</div>` line with your YouTube, Vimeo or `<video>` embed.
2. **Photos** (`05-about.html`): replace each `PHOTO PLACEHOLDER` line with `<img src="YOUR-IMAGE-URL" alt="Laser tattoo removal treatment">`. Upload the photos to GHL's Media Library to get their URLs. They fill the rounded frame on their own.
3. **Privacy Policy link** (`09-footer.html`): change `href="#"` to your policy page URL.

All the "Claim / Send Me the Voucher" buttons scroll to the voucher section (`#nwm-book`), so keep section 2 on the same page.

## Reviews

The 8 reviews are copied word for word from the practice's Google reviews. Review dates are left off so they don't go stale. To add, remove or swap one, copy a `<div class="nwm-rev-card ...">...</div>` line in `06-reviews.html` and change the initial, avatar color, name and text.

## If the page shows CSS as plain text

That means GHL didn't apply the `<style>` block. Check that each file went into a **Custom JS/HTML** element (not a Text or Paragraph element), that you pasted the **whole** file from the first line to the last, and that you clicked **Save** in the code editor.
