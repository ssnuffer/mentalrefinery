# Mental Refinery Website — Netlify-Ready Build

## What's in here
- `index.html` — the full site
- `styles.css` — all styling
- `script.js` — mobile menu + scroll animations (no dependencies)
- `images/office-banner.jpg`, `images/bio-photo.jpg` — pulled out of your old file and saved as real image files (your old site had these embedded as base64 text, which is part of what made it so heavy)

## Deploying to Netlify
1. Go to https://app.netlify.com/drop
2. Drag the **whole folder** (not a zip, just the folder itself — Netlify Drop accepts folders) onto the page.
3. Netlify gives you a live URL immediately. You can rename the site and connect a custom domain from the site settings.

If you'd rather use Netlify's dashboard "Add new site → Deploy manually" flow, that also accepts a drag-and-dropped folder or a zip — either works.

## Two files you'll need to add back in
Your original page linked to a few files by name that weren't embedded in what you sent me — they were just referenced as relative links, presumably sitting next to your old HTML file on your host. Drop these into this same folder (same names, so the links keep working) before you deploy:

- `Raising_Connected_Kids_Flyer_with_registration.png` (the parenting group flyer image)
- `Raising-Connected-Kids-Flyer-Sept-2026 QR.pdf`
- `Nonviolent Communication.pdf`
- `Values Clarification.pdf`
- `Journaling Prompts.pdf`
- `Dopamine Release.pdf`
- `Effects of Dopamine.pdf`

If any of those have since changed names or you want to drop one, just edit the matching `href` in `index.html` (search for the filename).

## Working contact & newsletter forms
Both forms (`#contact` and `#newsletter`) are already wired for **Netlify Forms** (`data-netlify="true"`) — once deployed on Netlify, submissions will show up under your site's **Forms** tab automatically, no backend needed. You can set up email notifications for new submissions in Site settings → Forms → Notifications.

## What changed from the old version
- Lighter, airier color palette (cream/sage/clay instead of heavy dark green and charcoal blocks)
- New **Coaching Packages** section (Starter/Momentum/Transformation/Maintenance) with a 3-session minimum, linked to your shared coaching agreement as an expandable policy list
- FAQ and policies now use native accordions (click to expand) instead of one long wall of text
- Subtle scroll-in animations and better hover states on buttons/cards for a more dynamic feel
- Mobile menu added (the old nav links just disappeared on small screens)
- All original content preserved — services, expertise, approaches, fees, testimonial, parenting group enrollment, newsletter signup, and contact form
