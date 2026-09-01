# Jacob C. Kamholz Research Site

Static GitHub Pages site for Jacob C. Kamholz, MPH, NRP.

## Publish on GitHub Pages

1. Upload every file in this folder to the root of the `JacobKamholz` repository.
2. In GitHub, open **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch **main** and folder **/(root)**.
5. Save.

For the repository shown in the original setup, the default project site address should be:

`https://jacob6493.github.io/JacobKamholz/`

All local links use relative paths, so the site works both as a GitHub project site and at a future custom domain.

## Files

- `index.html`: site content
- `styles.css`: complete visual styling
- `script.js`: mobile navigation and automatic footer year
- `404.html`: GitHub Pages error page
- `.nojekyll`: tells GitHub Pages to serve the site directly without Jekyll processing

## Updating publications

Add new publication blocks inside the `publication-list` section of `index.html`. The Google Scholar link is also included as the complete publication record.
