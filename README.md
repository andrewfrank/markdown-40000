# Markdown 40,000

## Core Rules

- **Core Rules** - Rendered Markdown • Raw Markdown • Printable PDF
- **Rules Commentary Version 1.0** - Rendered Markdown • Raw Markdown • Printable PDF

## Tournament Play

- **Leviathan Tournament Companion Version 1.0** - [Rendered Markdown](docs/leviathan-tournament-companion-version-1.0.md) • [Raw Markdown](https://raw.githubusercontent.com/andrewfrank/markdown-40000/main/docs/leviathan-tournament-companion-version-1.0.md) • [Printable PDF](docs/leviathan-tournament-companion-version-1.0.md.pdf)

## Missions

- **Fall of Kasr Myrak** - Rendered Markdown • Raw Markdown • Printable PDF

## Additional Modes of Play

- **Combat Patrol** - Rendered Markdown • Raw Markdown • Printable PDF
- **Boarding Actions** - Rendered Markdown • Raw Markdown • Printable PDF
- **Boarding Actions Mustering Rules Version 2.0** - Rendered Markdown • Raw Markdown • Printable PDF

## Method

Original Games Workshop PDFs are downloaded from the [Warhammer Community site downloads page](https://www.warhammer-community.com/warhammer-40000-downloads/). 

PDFs then are converted to .docx using [Smallpdf](https://smallpdf.com/), which is powered by [Solid Documents](http://solidframework.net/). I've found that Solid Documents has the best structural fidelity to the original PDF.

The .docx files are then converted to a draft Markdown file using [pandoc](https://pandoc.org/). The draft is then hand edited to correct and improve formatting to generate a final Markdown file. At this time, the original PDF is converted to a PNG image per page at 300 dpi. Images, diagrams, and other figures from the PDF that would otherwise be absent or poorly represented in Markdown format are then manually extracted from the page PNGs and subsequently embedded in the Markdown file.

The final Markdown file is then converted back into HTML using pandoc and then converted into a printer-friendly PDF, with page breaks equivalent to the original document.

## FAQs

### Why aren't all Games Workshop PDFs featured?

Not all of the Games Workshop documents are amenable to a purely text-based format. For example, the point values found in the Munitorum Field Manual are better stored in data specific formats such as JSONs or CSVs.

### Where can I obtain Games Workshop point values, army specific rules, or unit specific rules that have been publicly released?

For point values found in the Munitorm Field Manual and rules found in the army indicies and their associated errata, see the [BSData Warhammer 40,000 10th edition GitHub repository](https://github.com/BSData/wh40k-10e) or the [Game Datacards datasource repository](https://github.com/game-datacards/datasources).

### Doesn't this duplicate Wahapedia's effort?

While this site's effort is not exactly on firm legal standing, all of the content here is derived from documents that Games Workshop has [made freely available on their website](https://www.warhammer-community.com/warhammer-40000-downloads/). Some of the material that Wahapedia hosts is only found in Games Workshop's paid publications, which is definitely illegal.
