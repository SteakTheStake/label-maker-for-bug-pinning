# Camella’s Insect Label Maker

A simple, self-contained HTML page for making insect pinning labels. Every complete label is **55 mm wide × 15 mm tall**, including its cut border.

## Use the page

1. Open `index.html` or the GitHub Pages site.
2. Choose a label count (1–420), or add and remove individual labels.
3. Enter Family, Species, Common name, and Location & date. Enable **Include sex on this label** for any insect that needs it. The sex row is omitted from other labels.
4. Choose **Download HTML copy** to save an editable, offline copy with your current entries.
5. Choose **Print / Save PDF** to print or use your browser’s Save as PDF destination.

Entries are kept in the current tab. There is no server, database, autosave, browser storage, analytics, or external dependency in this page. Each visitor edits their own copy, and edits never change the repository or other visitors’ forms. Reloading the public page resets it to blank labels; reloading a downloaded copy restores the entries that were included when it was downloaded. The hosting provider may keep its own normal access logs.

## Print at the correct size

- Paper: **US Letter, 8.5 × 11 inches**.
- Orientation: **Portrait**.
- Scale: **100% / Actual size**; turn off Fit to page or Shrink to fit.
- Margins: use the page’s **0.5-inch** margins.
- Headers and footers: **Off**.
- Cut on the outer border of each label. Measure one printed label with a ruler before cutting the full sheet; printer settings can override the intended scale.

The layout holds 42 labels per sheet: 3 columns × 14 rows, with 4 mm horizontal gaps and 3 mm vertical gaps. Additional sheets are created automatically. The printout contains only the labels, including any blank labels requested.

Text starts at 7 pt and may shrink to 5 pt on individual lines to fit. Species values are italicized. If text still cannot fit, the page flags its input and preview and asks you to shorten it before printing. The browser’s own Print shortcut also checks for overflow and prints a warning in place of clipped labels.

## GitHub Pages

This site needs no build step. Publish these files from the root of the `main` branch:

- `index.html`
- `.nojekyll`
- `README.md` (optional documentation)

In the repository, open **Settings → Pages → Build and deployment**, set **Source** to **Deploy from a branch**, select **main** and **/ (root)**, and click **Save**. See [GitHub’s publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

Only the blank form belongs in the public repository. Students can keep filled copies on their own computers using the download button.
