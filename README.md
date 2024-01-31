


# Ojuju

[![][Fontbakery]](https://jobosonchisa.github.io/googlefonts-ojuju/fontbakery/fontbakery-report.html)
[![][Universal]](https://jobosonchisa.github.io/googlefonts-ojuju/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://jobosonchisa.github.io/googlefonts-ojuju/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://jobosonchisa.github.io/googlefonts-ojuju/fontbakery/fontbakery-report.html)
[![][Shaping]](https://jobosonchisa.github.io/googlefonts-ojuju/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjobosonchisa%2Fgooglefonts-ojuju%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjobosonchisa%2Fgooglefonts-ojuju%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjobosonchisa%2Fgooglefonts-ojuju%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjobosonchisa%2Fgooglefonts-ojuju%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fjobosonchisa%2Fgooglefonts-ojuju%2Fgh-pages%2Fbadges%2FUniversal.json

Ojuju is a reverse contrast Weight axis variable font inspired by African Masquerades. Ojuju draws inspiration from a variety of African traditional dance costumes to inform the design decisions. The masks worn by the Dogon dancers from Mali inspired the aperture shaping, and counterform placement within many of the letterforms. Additionally African movie poster lettering from the 1970's was referenced to round out the design space. Ojuju covers all of the Google's SSA(sub-saharan-african) latin glyphs.
![Sample Image](https://github.com/jobosonchisa/ojuju/blob/main/documentation/Dogon.JPG)

![Sample Image](https://github.com/jobosonchisa/ojuju/blob/main/documentation/image1.png)

![Sample Image](https://github.com/jobosonchisa/ojuju/blob/main/documentation/image2.png)

## About

Udi Foundry is a type foundry founded by brand and type designer Chisaokwu Joboson. Its mission is to create contemporary typefaces inspired by African culture.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://jobosonchisa.github.io/googlefonts-ojuju.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:

**26 May 2021. Version 2.13**
- MAJOR Font turned to a variable font.
- SIGNIFICANT New Stylistic sets added.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
