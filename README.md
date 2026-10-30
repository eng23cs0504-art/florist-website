# My Rose Florist n Decorators: website

Static site. No build step, no dependencies.

    index.html      the whole site (HTML, CSS, JS)
    images/         all photographs (WebP, three sizes each)
    fonts/          Bodoni Moda + Hanken Grotesk (self-hosted, SIL OFL)
    vercel.json     long-term caching for fonts only

## Deploy on Vercel
1. Push this folder to a GitHub repository (index.html must be at the repository root).
2. vercel.com > Add New > Project > import the repository.
3. Framework Preset: **Other**. Build Command: *(leave empty)*. Output Directory: *(leave empty)*. Install Command: *(leave empty)*.
4. Deploy.

## Contact details live in two places
- Static links in index.html (search for `917798678403`).
- The `CONFIG` block at the top of the script at the bottom of index.html.

## When the street address arrives
Set `addressText` in `CONFIG`. "Get Directions" will then build a Google Maps directions link from it.
Until then it opens the Google link the business supplied.
