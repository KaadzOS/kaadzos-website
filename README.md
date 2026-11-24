<div align="center">
  <img src="https://raw.githubusercontent.com/KaadzOS/.github/main/assets/kaadzoslogo.png" alt="KaadzOS" width="100%">
</div>

<p align="center">
  <sub>EDITORIAL SITE &nbsp;·&nbsp; REACT / VITE &nbsp;·&nbsp; CLOUDFLARE PAGES</sub>
</p>

<p align="center">
  <strong>The bright side of black.</strong><br>
  The words are the interface. The interface is the words.
</p>

<p align="center">
  <a href="https://kaadzos.pages.dev">Website</a> &nbsp;·&nbsp;
  <a href="https://kaadzos.pages.dev/docs/">Manual</a> &nbsp;·&nbsp;
  <a href="https://github.com/KaadzOS/KaadzOS/tree/main/site">Source tree</a> &nbsp;·&nbsp;
  <a href="https://github.com/KaadzOS/kaadzos-brand">Brand kit</a>
</p>

## Skeleton, on purpose

This is a stable address for the KaadzOS website. The production build still lives in [`site/`](https://github.com/KaadzOS/KaadzOS/tree/main/site) in the main monorepo and deploys from `site/dist/` to Cloudflare Pages. Nothing is duplicated here yet.

| Piece | Where it actually lives |
| --- | --- |
| Landing page | [`site/index.html`](https://github.com/KaadzOS/KaadzOS/blob/main/site/index.html) |
| React accents | [`site/src/`](https://github.com/KaadzOS/KaadzOS/tree/main/site/src) |
| Manual page | [`site/docs/`](https://github.com/KaadzOS/KaadzOS/tree/main/site/docs) |
| Deploy workflow | [`.github/workflows/site.yml`](https://github.com/KaadzOS/KaadzOS/blob/main/.github/workflows/site.yml) |

## Why this repo exists

A fixed home for site-specific issues, a future independent release cycle, and a clean place to point links. If the website ever stops being a monorepo citizen, it starts here.

## Licence

MIT; see [`LICENSE`](LICENSE). Vendored React Bits accents keep their MIT + Commons Clause notice in the source tree.

<sub>Debian is a registered trademark of Software in the Public Interest, Inc. KaadzOS is an independent project.</sub>
