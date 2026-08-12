# R & V Residential Contractors — Landing Page

A single-page, static landing site for R & V Residential Contractors (general contractor — bathroom remodeling, exterior finishing, home renovations).

## Structure

- `index.html` — the entire site (HTML/CSS/JS, no build step required)

## Editing later

- **Logo:** the header and footer each have a `.badge-mark` div showing an "R&V" monogram placeholder. Replace its contents with `<img src="logo.png" alt="R & V Residential Contractors LLC" style="width:100%;height:100%;border-radius:50%;object-fit:cover;">` once the real logo file is uploaded.
- **Hero photo:** in the hero section, replace the `.ph-fallback` div's contents with `<img src="hero.jpg" alt="R & V Residential Contractors project">`.
- **Gallery photos:** the "Our Work" section (`id="work"`) has 3 photo slots, each marked with an HTML comment (`PHOTO SLOT 1/2/3`). To add a picture, upload the image file to this repo (e.g. `work-1.jpg`) and replace that slot's `<div class="ph-fallback">...</div>` contents with `<img src="work-1.jpg" alt="...">`.
- **Service area:** the "Service Area & Contact" section currently uses generic wording — update it with a specific city/region once known.
- **Reviews:** the Google review link currently points to a generic search query; swap in the real Google Business Profile URL once available.

## Deploying with GitHub Pages

Handled automatically by `.github/workflows/deploy.yml` — every push to `main` builds and deploys the site. Live at `https://conrad1414.github.io/rv-residential-contractors/`.
