# Voltaire

[![][Fontbakery]](https://SorkinType.github.io/Voltaire/fontbakery/fontbakery-report.html)
[![][Universal]](https://SorkinType.github.io/Voltaire/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://SorkinType.github.io/Voltaire/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://SorkinType.github.io/Voltaire/fontbakery/fontbakery-report.html)
[![][Shaping]](https://SorkinType.github.io/Voltaire/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FVoltaire%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FVoltaire%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FVoltaire%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FVoltaire%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FSorkinType%2FVoltaire%2Fgh-pages%2Fbadges%2FUniversal.json

Voltaire is a low-contrast condensed semi-geometric style sans-serif. Voltaire is highly readable and will work from medium text sizes all the way up to larger display settings. Voltaire was inspired by 20th century Swedish posters whose letters have similar forms.

![Sample Image](documentation/image2.png)
![Sample Image](documentation/image1.png)
![Sample Image](documentation/image3.png)

## About

Yvonne Schüttler designed Voltaire.

Eben Sorkin from Sorkin Type Co. art directed, kerned and added languages to Voltaire. 

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.


## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 


**14 October 2022. Version 1.007**
- Glyphset expanded (from 231 to 711 glyphs)

**27 Nov 2022. Version 1.008**
- Glyphset expanded (from 711 to 831 glyphs)
- Revised Kern-on kerning
- Fixed anchors and diacritic issues
- Added old style numbers and arrows
- Now using Glyphs 3 format source

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
