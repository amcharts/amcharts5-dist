## amCharts 5: CDN distribution

This repository contains the pre-built browser (`<script>` tag) files of
amCharts 5. Its only purpose is to feed public CDNs, such as
[cdnjs](https://cdnjs.com/), with the same files we serve from
`cdn.amcharts.com/lib/5/`.

It is updated automatically on each amCharts 5 release, with one tag per
library version. **Please do not use it as a source for the library, and do
not open issues or pull requests here.** Nothing in it is edited by hand.


### Where to get amCharts 5 instead

* [NPM package](https://www.npmjs.com/package/@amcharts/amcharts5)
* [GitHub repository](https://github.com/amcharts/amcharts5)
* [ZIP download & CDN info](https://www.amcharts.com/download/)


### Layout

The layout mirrors `https://cdn.amcharts.com/lib/5/`:

* `index.js`, `xy.js`, `map.js`, ... - library files
* `themes/`, `locales/`, `plugins/`, `deps/` - themes, translations, plugins and their dependencies
* `geodata/` - map files (JSON versions are not included)
* `fonts/` - fonts used by the PDF export


### Documentation

[amCharts 5 documentation](https://www.amcharts.com/docs/v5)


### License

amCharts 5 can be used for free, as long as the small amCharts branding
link is shown on the charts. See [LICENSE](LICENSE) for details.

If you have a commercial amCharts 5 license, this software is covered by your
license, which supersedes any other license bundled with this package.
