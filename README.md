# CR8IVE Tools website

Public marketing website for CR8IVE Tools, hosted with GitHub Pages.

The published files are `index.html` and the original brand image in `assets/`.
The enquiry form opens an email draft addressed to marcin@cr8ivetools.com; it does not submit to a backend.

## Updating

The authoring source is maintained in the local CR8IVE workspace at `src/domain/landingPageRenderer.js`. Run `npm run landing` there, copy the regenerated `site/index.html` into this repository and push to `main`. GitHub Pages publishes from the repository root.

Keep `.nojekyll` and the custom-domain `CNAME` file when updating the page.

Brand artwork remains the property of CR8IVE Tools.
