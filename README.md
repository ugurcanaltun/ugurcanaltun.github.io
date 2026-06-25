# ugurcanaltun.github.io

Personal academic website for Uğur Can Altun, served via GitHub Pages at
<https://ugurcanaltun.github.io>.

Built on [Jon Barron's website template](https://github.com/jonbarron/jonbarron_website).

## Structure

- `index.html` — the single-page site (header, news, publications, experience, service, teaching).
- `stylesheet.css` — Barron template styles (Lato font, link colors).
- `cv.pdf` — CV linked from the header.
- `images/`
  - `profile.jpg` — circular profile photo (square crop of `amsterdam_bridge_photo.jpeg`).

## Editing notes

- The email link is assembled in JavaScript at page load to deter scrapers; update the
  `_u` / `_d` variables in `index.html` if the address changes.
- To swap the profile photo, drop a square image at `images/profile.jpg`.
