# Unilever Professional Loyalty Programme: Takealot Competition Report

Weekly performance report for the "Win 1 of 5 R1 000 Takealot coupons" campaign, administered by Berelo.

This is a single self-contained file, `index.html`. It has no build step and no dependencies to install. Chart.js and the Montserrat font load from CDNs, and the images are embedded.

## View locally

Open `index.html` in a browser.

## Weekly update workflow

1. Open `index.html` in a browser and select **Edit figures**.
2. Enter the new numbers, then select **Save changes**.
3. Select **Download updated report**. This saves a copy of the page with your figures baked in.
4. Replace `index.html` in this repo with the downloaded file and commit it.

You can also edit the JSON block in `<script id="report-data" type="application/json">` directly. All figures live there.

## Hosting (optional)

`.github/workflows/pages.yml` deploys `index.html` to GitHub Pages on every push to `main`.

**The report is marked confidential.** Keep this repo private. GitHub Pages from a private repo needs a paid GitHub plan, and a published site's URL is reachable by anyone who has it. If you don't want the report public, delete the workflow file and share the HTML file directly instead.
