# Cover the Logo

Would anyone know whose ad this is with the brand removed? Load an ad, drag redaction bars over the brand name and logo, and export a "who made this?" image to show category buyers.

Open `index.html` in any browser. No build step and no dependencies.

- **Load:** drop, paste or choose an image. It stays in your browser. Nothing is uploaded, and the exported PNG carries no metadata from the original.
- **Cover:** drag to draw a bar over each brand name, logo or product mark. Undo, clear, or right click a bar to remove it. A lime tab on each bar is optional.
- **Export:** a PNG of the ad with an optional question strip underneath (editable question and caption, ben.j.ads wordmark).
- **Solid bars, not blur:** the bar replaces the pixels, so nothing under it survives in the file.

You draw the bars yourself. Nothing is detected automatically, so check the export for anything that still gives the brand away (packaging, a web address, a tagline).

To score the answers, count how many people named the brand, named someone else, or did not know, and put the counts into [assetscan](https://github.com/ben-j-ads/assetscan). Method: Romaniuk, *Building Distinctive Brand Assets* (2018). Ask category buyers, not colleagues.

Images are capped at 2400px on the longest edge.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.

Styled to the ben.j.ads brand: paper ground, Bricolage Grotesque Condensed and Archivo, lime as a mark only. No external requests.
