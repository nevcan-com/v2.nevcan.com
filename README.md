# nevcan.com v2 (2013)

The second version of nevcan.com, live in spring and summer 2013: "Projelerim & Ben" (My Projects
& Me), a one-page portfolio in Turkish and English with a sidebar menu: about me, career, website
work, album covers, digital design, software and contact.

Online at **[v2.nevcan.com](https://v2.nevcan.com)** as part of the nevcan.com version archive,
hidden from search engines. The current site is [www.nevcan.com](https://www.nevcan.com).

| Path | Page |
| --- | --- |
| `/` | Opens the Turkish page |
| `/tr/` | Turkish page |
| `/en/` | English page |

## Source

There was no copy of this version. Only its three pages survived, in the Internet Archive's
Wayback Machine (captures of 6 May, 7 May and 21 June 2013); none of its CSS, JavaScript or images
were archived. The first three commits are those pages exactly as captured; the tag `2013.06`
marks them.

The next commit makes it run again:

- **Template.** The page was generated with [Documenter 1.5](http://rxa.li/documenter) by Xaver
  Birsak. Documenter's CSS and JavaScript are the same for every page it generates, so they come
  from another Documenter 1.5 output, and jQuery 1.5.1 from code.jquery.com. The site's own
  colours were inside the page and are original.
- **Stand-ins, not the original files:**
  - `images/logos/*_logo.png`: ten of the social icons, drawn from the
    [Zocial](https://github.com/smcllns/css-social-buttons) 1.1.1 icon font (2012, MIT).
  - `images/tr.gif`, `images/en.gif`: the TR and GB flags from the
    [famfamfam flag icons](https://github.com/legacy-icons/famfamfam-flags) (free to use).
  - `images/logo.png`: an illustration of mine from the period. It may originally have been
    `char.png` or `nevcan-helper.png` rather than the logo.
- **Missing.** Every other image shows its file name instead.
- **Archive changes.** A `noindex` meta tag and a `robots.txt` that disallows everything, and
  Google Analytics removed. The Turkish contact form was never archived; `tr/form/` only says so.

## Missing files

If any of these turn up in an old backup, add the file at the same path and push; the pages
already point there.

- `images/char.png`
- `images/doad.jpg`
- `images/erdemkinay-proje.jpg`
- `images/inanc-yapiskanli-bantlar-ambalaj-iml-san-ve-tic-ltdsti.jpg`
- `images/logos/500px_logo.png`
- `images/logos/armut_logo.png`
- `images/logos/freelancer_logo.png`
- `images/logos/movescount_logo.png`
- `images/nevcan-helper.png`
- `images/nevcan.jpg`
- `images/nevcanuludasCV2013TR.pdf` (the 2013 CV)
- `images/tezhantezcan-kalbimonunla.jpg`
- `js/rightclick.js`
- `tr/form/` (the original contact form)

## Stack

HTML5, CSS and jQuery 1.5.1 (scrollTo, easing), generated with Documenter 1.5. Hosted on GitHub
Pages.
