# burhanaddinzm.github.io

Personal portfolio site, served straight off GitHub Pages. Single static
page, no build step, no framework — just HTML, CSS, and vanilla JS.

**Live:** [burhanaddinzm.github.io](https://burhanaddinzm.github.io)

## What's on it

- **About** — background, focus areas, what I'm doing outside of work
- **Skills** — backend, databases, DevOps/sysadmin, self-hosted services
- **Infrastructure** — the homelab: Docker stack, Jellyfin + distributed
  encoding pipeline, Open WebUI, Planka, Dnsmasq, Nginx
- **Projects** — work and government-facing projects
- **Open Source** — repos on [GitHub](https://github.com/Burhanaddinzm),
  pulled in with descriptions and tags
- **Experience** — roles, in reverse-chronological order
- **Off the Clock** — a film-strip photo gallery with a click-to-open
  lightbox (keyboard nav, prev/next, captions)
- **Terminal** — a small shell emulator over a mock filesystem of the
  page's own content. Supports `ls`, `cd`, `cat`, `pwd`, `tree`, `open`,
  `whoami`, `neofetch`, `history`, `clear`, and command history via
  the arrow keys. `open life/<photo>` even scrolls to the gallery and
  pops the matching photo into the lightbox.

## Stack

Plain HTML5 + CSS + JS. No dependencies, no bundler. Fonts pulled from
Google Fonts (Fira Mono). Photos live in `/photos` and are referenced
with relative paths.

## Running locally

Nothing to install — open `index.html` directly in a browser, or serve
the folder if you want relative paths to behave exactly like GitHub
Pages

## Structure

```
.
├── index.html      # everything: markup, styles, and scripts in one file
├── photos/          # images used by the gallery
└── README.md
```

## Contact

- GitHub: [github.com/Burhanaddinzm](https://github.com/Burhanaddinzm)
- LinkedIn: [linkedin.com/in/burhanaddin-mirsadizada](https://www.linkedin.com/in/burhanaddin-mirsadizada/)
- Email: burhaneddinmirsedizade@gmail.com
