# Open-weight Red-teaming Hackathon

Public landing page for the November 7, 2026 hackathon at Constellation.

Live site: <https://constellation-redteaming-hackathon.github.io/>

This is a static single page using HTML, CSS, and local SVG artwork. It requires no
build step, package installation, JavaScript, or application server.

## Preview locally

From this directory:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open <http://127.0.0.1:8080>.

## GitHub Pages

Publish the root directory of the `main` branch. The `.nojekyll` file lets GitHub
Pages serve the files directly. All page assets use relative paths.

## Expressions of interest

The first draft clearly marks the interest form as coming soon. It does not collect
or store personal information. The calendar download is functional and reserves
the date without assuming event hours.

When a hosted interest form is ready, update the `#interest` section in `index.html`
with a link to that form and revise the coming-soon copy. Keep personal signup data
in the form service, outside this public repository.

## Editing

- `index.html`: public event copy, navigation, and expandable FAQs.
- `style.css`: responsive layout, colors, and print/reduced-motion styles.
- `assets/frontier.svg`: a conceptual illustration, not measured results.
- `assets/mark.svg`: the page icon and wordmark symbol.
- `assets/save-the-date.ics`: the November 7 calendar event.

Only approved public event information belongs in this repository. Review page
copy, metadata, assets, and commit contents before publishing updates.
