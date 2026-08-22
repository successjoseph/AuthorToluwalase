# AuthorToluwalase

![HTML](https://img.shields.io/badge/HTML-Static%20Page-orange)

## Table of Contents
- [About](#about)
- [Visuals](#visuals)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [Authors and License](#authors-and-license)

## About

A single-page static author website for "Toluwalase Famade", a Christian fiction writer — the same page structure and Tailwind/Google Fonts styling as the author's separate `Toluwalase-Writer` repository, but a more filled-in revision: it uses a real author portrait (`authortoluwalase.jpeg`, actually referenced and present in the repo) instead of a placeholder box, and a more personal "The Heart Behind The Pen" testimony ("Growing up the bible was my favorite story book...") plus a different pull-quote ("Moses Parted the Red Sea with the rod in his hands, I write wonders with the pen in mine.") in place of the other repo's generic filler text. Like the sibling repo, it still lists three placeholder book entries (The Redemption of Olasumbo, Shadows of the Altar, Faith in the Valley) with text-only cover art, and the newsletter subscribe form only fakes a "Thank you" confirmation client-side without actually submitting anywhere. There is no build process, framework, or backend — `index.html` is fully self-contained aside from CDN-hosted Tailwind CSS and Google Fonts.

## Visuals

- `authortoluwalase.jpeg` — the author's portrait, displayed in the "About/Testimony" section.

## Prerequisites

None beyond a modern web browser with internet access (Tailwind CSS and Google Fonts load from CDNs at view time).

## Installation

```bash
git clone https://github.com/successjoseph/AuthorToluwalase.git
cd AuthorToluwalase
```

No dependency installation or build tooling is required.

## Configuration

There is no external configuration. All copy and the book list are hardcoded directly in `index.html`.

## Usage

Open `index.html` directly in a browser, or serve it locally:
```bash
python -m http.server 8000
```

## Testing

No automated tests are currently included.

## Contributing

This is a personal/client site for one author, not open to outside contributions. Notes above are for future-you when deciding whether to keep this version or the `Toluwalase-Writer` repo as the canonical site.

## Authors and License

- **Author:** successjoseph ([github.com/successjoseph](https://github.com/successjoseph))
- **License:** No license file included in this repository — all rights reserved by default.
