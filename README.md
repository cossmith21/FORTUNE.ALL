# FORTUNE.ALL

Fortune's brand kit and reusable assets, captured from [fortunesales.com](https://fortunesales.com/) on November 13, 2026.

![Fortune wordmark](marks/fortune-wordmark-ink.png)

## Brand kits

- [Light PDF](pdf/Fortune-Brand-Kit-Light-Mode-Storyboard.pdf) uses warm ivory backgrounds, dark type and gold accents. This is a proposed light adaptation.
- [Dark PDF](pdf/Fortune-Brand-Kit-Dark-Mode-Storyboard.pdf) follows the site's dark palette.

Each six-page PDF includes the message, logo family, color values, font specimens, recruiting storyboard and source notes. Each also contains an attached ZIP of the original asset collection. The folders here provide direct access to the files.

## For AI platforms

Start with [brand.json](brand.json) for the brand facts, typography, mark variants and file locations. Read [colors.json](colors.json) for exact CSS colors and proposed light-theme roles. [asset-manifest.json](asset-manifest.json) lists the files with source URLs, raw download URLs, byte sizes and SHA-256 checksums.

- [Raw brand data](https://raw.githubusercontent.com/cossmith21/FORTUNE.ALL/main/brand.json)
- [Raw color data](https://raw.githubusercontent.com/cossmith21/FORTUNE.ALL/main/colors.json)
- [Raw asset manifest](https://raw.githubusercontent.com/cossmith21/FORTUNE.ALL/main/asset-manifest.json)
- [Download the repository](https://github.com/cossmith21/FORTUNE.ALL/archive/refs/heads/main.zip)

Paths inside the JSON files are relative to the repository root. Site statements and editorial interpretation have separate fields. The PDFs' storyboard frames are creative compositions based on the recruiting flow.

## Asset folders

| Location | Contents |
| --- | --- |
| pdf/ | Light and dark brand kits |
| marks/ | Wordmark, F monogram, laurel and globe in gold, bone and ink, as SVG and transparent PNG |
| site-svg/ | Original favicon and wordmark, emblem-strip, lattice, grain and photo-noise textures |
| fonts/ | All 15 original WOFF/WOFF2 files and a local fonts.css |
| fonts/ttf/ | Installable Latin TTF versions, preserving the variable axes where present |
| fonts/licenses/ | Upstream SIL Open Font License notices |
| images/ | Founder portraits, hero stills and social share image |
| css/ | Original root tokens, readable color variables and proposed light-theme variables |
| sources/site.css | Captured site stylesheet |

## Using the brand

Fortune recruits reps for door-to-door sales of home service agreements. Its site emphasizes tiered commissions, skill development and an earned ownership path for qualifying reps. Earnings examples are illustrative and ownership has qualification requirements. [Homepage](https://fortunesales.com/)

The site pairs Fraunces Variable display type with Montserrat Variable body type and Pirata One blackletter accents. The logo is vector artwork. The gold, bone and ink SVG variants preserve the extracted paths. [Source stylesheet](https://fortunesales.com/_astro/MarkStrip.BPKrYiJp.css)

Use fonts/fonts.css to load the original webfont family names. The TTF folder contains Latin versions for design applications. The WOFF/WOFF2 collection contains every subset referenced by the captured stylesheet. Font license notices travel with the files.

## Sources and provenance

[SOURCES.txt](SOURCES.txt) records the original asset URLs. The homepage and linked application page were inspected. The tested sitemap URLs returned 404. Source filenames and paths reflect the capture date.

The light kit assigns existing site colors to a proposed light presentation. colors.json records that choice explicitly. The source site's root palette and the light theme each retain their own values.
