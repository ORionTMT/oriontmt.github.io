# Mutian Tong's personal website

A static academic homepage with research publications, teaching, service, and personal interests. No build step or JavaScript dependencies are required.

## Local preview

Run `python3 -m http.server 8000` from this directory, then open http://localhost:8000.

## Editing

- `index.html`: biography and publications. Research entries are ordered newest first by the first arXiv submission date, recorded in each article's `data-date` attribute.
- `stylesheet.css`: typography, layout, mobile styles, and independent video hover previews.
- `images/`: Mutian's photos and research media, including personal assets retained for future use.
- `googleffecce5fc319ceb7.html`: existing site verification file.

New publications should include the title, authors (with Mutian Tong in bold), venue/year, links, a short summary, and preview media with descriptive alt text.

## Credits and asset sources

Adapted from [Jon Barron's academic website template](https://jonbarron.info/).

- `images/unilap.png`: [Lei Yao's homepage](https://rayyoh.github.io/static/images/UniLAP.png), for [UniLAP](https://arxiv.org/abs/2610.16969), first submitted October 12, 2026.
- `images/omnidream.png`: [Zitong Lan's homepage](https://zitonglan.github.io/images/omnidream_teaser.png), for [Enabling Immersive Audio-Visual Experience from Any Video](https://arxiv.org/abs/2609.36295), first submitted September 28, 2026.
- [PointAction](https://arxiv.org/abs/2606.03943), first submitted June 2, 2026.

The cleanup removes assets identical to the inherited Jon Barron template (commit `d03c3e2`), including its unrelated project pages and bibliography. Personal photos, research assets, and site verification are retained. Local `paper_note.*` files are left untouched.
