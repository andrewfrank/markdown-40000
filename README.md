# Markdown 40,000

## Documents

### Leviathan Tournament Companion Version 1.0

[Rendered Markdown](docs/leviathan-tournament-companion-version-1.0.md) •
[Raw Markdown](https://raw.githubusercontent.com/andrewfrank/markdown-40000/main/docs/leviathan-tournament-companion-version-1.0.md) • 
[Printable PDF](docs/leviathan-tournament-companion-version-1.0.md.pdf)

### Rules Commentary Version 1.0

Markdown • Markdown PDF

## Method

Games Workshop PDFs are first converted to .docx using [Smallpdf](https://smallpdf.com/), which is powered by [Solid Documents](http://solidframework.net/). I've found that Solid Documents has the best text formatting fidelity to the original document. The .docx files are then converted to a draft Markdown file using [pandoc](https://pandoc.org/). The draft is then hand edited to correct and improve formatting to generate a final Markdown file. The final Markdown file is then converted back into HTML using pandoc and then converted into a printer-friendly PDF.
