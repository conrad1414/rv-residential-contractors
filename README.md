# R & V Residential Contractors — Landing Page

A single-page, static landing site for R & V Residential Contractors (general contractor — bathroom remodeling, exterior finishing, home renovations).

## Structure

- `index.html` — the entire site (HTML/CSS/JS, no build step required)

## Editing later

- **Logo:** replace the text wordmark in the header (`.logo` element near the top of `index.html`'s `<body>`) with `<img src="logo.png" alt="R & V Residential Contractors">` once a real logo file is available.
- **Photos:** the "Our Work" section (`id="work"`) has 3 photo slots, each marked with an HTML comment (`PHOTO SLOT 1/2/3`). To add a picture, upload the image file to this repo (e.g. `work-1.jpg`) and replace that slot's `<div class="placeholder">...</div>` contents with `<img src="work-1.jpg" alt="...">`.
- **Service area:** the "Service Area & Contact" section currently uses generic wording — update it with a specific city/region once known.
- **Reviews:** the Google review link currently points to a generic search query; swap in the real Google Business Profile URL once available.

## Deploying with GitHub Pages

1. Go to **Settings → Pages** in this repository.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Choose branch `main`, folder `/ (root)`, then click **Save**.
4. The site will be live at `https://conrad1414.github.io/rv-residential-contractors/` within a minute or two.
