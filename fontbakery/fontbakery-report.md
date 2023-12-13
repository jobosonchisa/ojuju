## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[19] Ojuju-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0040 (COMMERCIAL AT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "100" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1148, but got 940 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (840) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Tbar	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: lambda	Expected: 1

	- Glyph name: pi	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: minute	Expected: 1

	- Glyph name: second	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: arrowleft	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowright	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: uni2206	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Tbar	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: emptyset	Expected: 3

	- Glyph name: fraction	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lambda	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: pi	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: uni2206	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1 or 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, malayalam, coptic, tifinagh, canadian-aboriginal, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, cherokee, tifinagh, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: tai-viet, wancho, gujarati, bhaiksuki, nko, duployan, tifinagh, hanunoo, soyombo, buginese, newa, hebrew, kayah-li, thai, caucasian-albanian, mongolian, meetei-mayek, gurmukhi, phags-pa, kharoshthi, kannada, malayalam, osage, khmer, modi, yi, mende-kikakui, lepcha, khudawadi, tagalog, zanabazar-square, lao, elbasan, syloti-nagri, chakma, devanagari, tamil, brahmi, kaithi, syriac, music, javanese, bassa-vah, masaram-gondi, symbols, tagbanwa, sinhala, adlam, ahom, tirhuta, coptic, sundanese, grantha, new-tai-lue, myanmar, pahawh-hmong, tibetan, marchen, manichaean, rejang, miao, math, old-permic, mandaic, buhid, sogdian, khojki, sharada, limbu, thaana, balinese, gunjala-gondi, oriya, tai-le, siddham, cham, takri, telugu, mahajani, batak, bengali, dogra, psalter-pahlavi, hanifi-rohingya
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* R (U+0052): L<<83.0,701.0>--<335.0,699.0>>

	* Racute (U+0154): L<<83.0,701.0>--<335.0,699.0>>

	* Rcaron (U+0158): L<<83.0,701.0>--<335.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<83.0,701.0>--<335.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<103.0,367.0>--<101.0,700.0>>

	* uni0156 (U+0156): L<<83.0,701.0>--<335.0,699.0>>

	* uni0210 (U+0210): L<<83.0,701.0>--<335.0,699.0>>

	* uni0212 (U+0212): L<<83.0,701.0>--<335.0,699.0>>

	* uni024C (U+024C): L<<83.0,701.0>--<335.0,699.0>>

	* uni1E58 (U+1E58): L<<83.0,701.0>--<335.0,699.0>>

	* uni1E5A (U+1E5A): L<<83.0,701.0>--<335.0,699.0>>

	* uni1E5C (U+1E5C): L<<83.0,701.0>--<335.0,699.0>>

	* uni2075 (U+2075): L<<103.0,367.0>--<101.0,700.0>>

	* uni2085 (U+2085): L<<103.0,367.0>--<101.0,700.0>>

	* uni20A8 (U+20A8): L<<83.0,701.0>--<335.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Ojuju-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0040 (COMMERCIAL AT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "100" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1148, but got 940 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (840) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Tbar	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: lambda	Expected: 1

	- Glyph name: pi	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: minute	Expected: 1

	- Glyph name: second	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: arrowleft	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowright	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: uni2206	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Tbar	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: emptyset	Expected: 3

	- Glyph name: fraction	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lambda	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: pi	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: uni2206	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1 or 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, malayalam, coptic, tifinagh, canadian-aboriginal, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, cherokee, tifinagh, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: tai-viet, wancho, gujarati, bhaiksuki, nko, duployan, tifinagh, hanunoo, soyombo, buginese, newa, hebrew, kayah-li, thai, caucasian-albanian, mongolian, meetei-mayek, gurmukhi, phags-pa, kharoshthi, kannada, malayalam, osage, khmer, modi, yi, mende-kikakui, lepcha, khudawadi, tagalog, zanabazar-square, lao, elbasan, syloti-nagri, chakma, devanagari, tamil, brahmi, kaithi, syriac, music, javanese, bassa-vah, masaram-gondi, symbols, tagbanwa, sinhala, adlam, ahom, tirhuta, coptic, sundanese, grantha, new-tai-lue, myanmar, pahawh-hmong, tibetan, marchen, manichaean, rejang, miao, math, old-permic, mandaic, buhid, sogdian, khojki, sharada, limbu, thaana, balinese, gunjala-gondi, oriya, tai-le, siddham, cham, takri, telugu, mahajani, batak, bengali, dogra, psalter-pahlavi, hanifi-rohingya
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* P (U+0050): L<<83.0,701.0>--<317.0,699.0>>

	* R (U+0052): L<<82.0,701.0>--<343.0,699.0>>

	* Racute (U+0154): L<<82.0,701.0>--<343.0,699.0>>

	* Rcaron (U+0158): L<<82.0,701.0>--<343.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<82.0,701.0>--<343.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<101.0,366.0>--<99.0,700.0>>

	* uni0156 (U+0156): L<<82.0,701.0>--<343.0,699.0>>

	* uni01A4 (U+01A4): L<<83.0,701.0>--<317.0,699.0>>

	* uni0210 (U+0210): L<<82.0,701.0>--<343.0,699.0>>

	* uni0212 (U+0212): L<<82.0,701.0>--<343.0,699.0>>

	* uni024C (U+024C): L<<82.0,701.0>--<343.0,699.0>>

	* uni1E54 (U+1E54): L<<83.0,701.0>--<317.0,699.0>>

	* uni1E56 (U+1E56): L<<83.0,701.0>--<317.0,699.0>>

	* uni1E58 (U+1E58): L<<82.0,701.0>--<343.0,699.0>>

	* uni1E5A (U+1E5A): L<<82.0,701.0>--<343.0,699.0>>

	* uni1E5C (U+1E5C): L<<82.0,701.0>--<343.0,699.0>>

	* uni2075 (U+2075): L<<101.0,366.0>--<99.0,700.0>>

	* uni2085 (U+2085): L<<101.0,366.0>--<99.0,700.0>>

	* uni20A8 (U+20A8): L<<82.0,701.0>--<343.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Ojuju-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0040 (COMMERCIAL AT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "100" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1148, but got 940 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (840) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Tbar	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: lambda	Expected: 1

	- Glyph name: pi	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: minute	Expected: 1

	- Glyph name: second	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: arrowleft	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowright	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: uni2206	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Tbar	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: emptyset	Expected: 3

	- Glyph name: fraction	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lambda	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: pi	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: uni2206	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, malayalam, coptic, tifinagh, canadian-aboriginal, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, cherokee, tifinagh, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: tai-viet, wancho, gujarati, bhaiksuki, nko, duployan, tifinagh, hanunoo, soyombo, buginese, newa, hebrew, kayah-li, thai, caucasian-albanian, mongolian, meetei-mayek, gurmukhi, phags-pa, kharoshthi, kannada, malayalam, osage, khmer, modi, yi, mende-kikakui, lepcha, khudawadi, tagalog, zanabazar-square, lao, elbasan, syloti-nagri, chakma, devanagari, tamil, brahmi, kaithi, syriac, music, javanese, bassa-vah, masaram-gondi, symbols, tagbanwa, sinhala, adlam, ahom, tirhuta, coptic, sundanese, grantha, new-tai-lue, myanmar, pahawh-hmong, tibetan, marchen, manichaean, rejang, miao, math, old-permic, mandaic, buhid, sogdian, khojki, sharada, limbu, thaana, balinese, gunjala-gondi, oriya, tai-le, siddham, cham, takri, telugu, mahajani, batak, bengali, dogra, psalter-pahlavi, hanifi-rohingya
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<74.0,701.0>--<539.0,699.0>>

	* P (U+0050): L<<75.0,700.0>--<380.0,699.0>>

	* R (U+0052): L<<75.0,700.0>--<390.0,699.0>>

	* Racute (U+0154): L<<75.0,700.0>--<390.0,699.0>>

	* Rcaron (U+0158): L<<75.0,700.0>--<390.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<75.0,700.0>--<390.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<86.0,361.0>--<84.0,700.0>>

	* nine (U+0039): L<<90.0,10.0>--<89.0,162.0>>

	* uni0156 (U+0156): L<<75.0,700.0>--<390.0,699.0>>

	* uni0191 (U+0191): L<<74.0,701.0>--<539.0,699.0>>

	* uni01A4 (U+01A4): L<<75.0,700.0>--<380.0,699.0>>

	* uni0210 (U+0210): L<<75.0,700.0>--<390.0,699.0>>

	* uni0212 (U+0212): L<<75.0,700.0>--<390.0,699.0>>

	* uni024C (U+024C): L<<75.0,700.0>--<390.0,699.0>>

	* uni1E1E (U+1E1E): L<<74.0,701.0>--<539.0,699.0>>

	* uni1E54 (U+1E54): L<<75.0,700.0>--<380.0,699.0>>

	* uni1E56 (U+1E56): L<<75.0,700.0>--<380.0,699.0>>

	* uni1E58 (U+1E58): L<<75.0,700.0>--<390.0,699.0>>

	* uni1E5A (U+1E5A): L<<75.0,700.0>--<390.0,699.0>>

	* uni1E5C (U+1E5C): L<<75.0,700.0>--<390.0,699.0>>

	* uni2075 (U+2075): L<<86.0,361.0>--<84.0,700.0>>

	* uni2079 (U+2079): L<<90.0,10.0>--<89.0,162.0>>

	* uni2085 (U+2085): L<<86.0,361.0>--<84.0,700.0>>

	* uni2089 (U+2089): L<<90.0,10.0>--<89.0,162.0>>

	* uni20A8 (U+20A8): L<<75.0,700.0>--<390.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Ojuju-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0040 (COMMERCIAL AT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "100" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1148, but got 940 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (840) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Tbar	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: lambda	Expected: 1

	- Glyph name: pi	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: minute	Expected: 1

	- Glyph name: second	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: arrowleft	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowright	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: uni2206	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Tbar	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: emptyset	Expected: 3

	- Glyph name: fraction	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lambda	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: pi	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: uni2206	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1 or 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, malayalam, coptic, tifinagh, canadian-aboriginal, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, cherokee, tifinagh, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: tai-viet, wancho, gujarati, bhaiksuki, nko, duployan, tifinagh, hanunoo, soyombo, buginese, newa, hebrew, kayah-li, thai, caucasian-albanian, mongolian, meetei-mayek, gurmukhi, phags-pa, kharoshthi, kannada, malayalam, osage, khmer, modi, yi, mende-kikakui, lepcha, khudawadi, tagalog, zanabazar-square, lao, elbasan, syloti-nagri, chakma, devanagari, tamil, brahmi, kaithi, syriac, music, javanese, bassa-vah, masaram-gondi, symbols, tagbanwa, sinhala, adlam, ahom, tirhuta, coptic, sundanese, grantha, new-tai-lue, myanmar, pahawh-hmong, tibetan, marchen, manichaean, rejang, miao, math, old-permic, mandaic, buhid, sogdian, khojki, sharada, limbu, thaana, balinese, gunjala-gondi, oriya, tai-le, siddham, cham, takri, telugu, mahajani, batak, bengali, dogra, psalter-pahlavi, hanifi-rohingya
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* R (U+0052): L<<84.0,701.0>--<330.0,699.0>>

	* Racute (U+0154): L<<84.0,701.0>--<330.0,699.0>>

	* Rcaron (U+0158): L<<84.0,701.0>--<330.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<84.0,701.0>--<330.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<105.0,368.0>--<103.0,700.0>>

	* uni0156 (U+0156): L<<84.0,701.0>--<330.0,699.0>>

	* uni0210 (U+0210): L<<84.0,701.0>--<330.0,699.0>>

	* uni0212 (U+0212): L<<84.0,701.0>--<330.0,699.0>>

	* uni024C (U+024C): L<<84.0,701.0>--<330.0,699.0>>

	* uni1E58 (U+1E58): L<<84.0,701.0>--<330.0,699.0>>

	* uni1E5A (U+1E5A): L<<84.0,701.0>--<330.0,699.0>>

	* uni1E5C (U+1E5C): L<<84.0,701.0>--<330.0,699.0>>

	* uni2075 (U+2075): L<<105.0,368.0>--<103.0,700.0>>

	* uni2085 (U+2085): L<<105.0,368.0>--<103.0,700.0>>

	* uni20A8 (U+20A8): L<<84.0,701.0>--<330.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Ojuju-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0040 (COMMERCIAL AT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "100" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1148, but got 940 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (840) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Tbar	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: lambda	Expected: 1

	- Glyph name: pi	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: minute	Expected: 1

	- Glyph name: second	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: arrowleft	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowright	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: uni2206	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Tbar	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: emptyset	Expected: 3

	- Glyph name: fraction	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lambda	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: pi	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: uni2206	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, malayalam, coptic, tifinagh, canadian-aboriginal, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, cherokee, tifinagh, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: tai-viet, wancho, gujarati, bhaiksuki, nko, duployan, tifinagh, hanunoo, soyombo, buginese, newa, hebrew, kayah-li, thai, caucasian-albanian, mongolian, meetei-mayek, gurmukhi, phags-pa, kharoshthi, kannada, malayalam, osage, khmer, modi, yi, mende-kikakui, lepcha, khudawadi, tagalog, zanabazar-square, lao, elbasan, syloti-nagri, chakma, devanagari, tamil, brahmi, kaithi, syriac, music, javanese, bassa-vah, masaram-gondi, symbols, tagbanwa, sinhala, adlam, ahom, tirhuta, coptic, sundanese, grantha, new-tai-lue, myanmar, pahawh-hmong, tibetan, marchen, manichaean, rejang, miao, math, old-permic, mandaic, buhid, sogdian, khojki, sharada, limbu, thaana, balinese, gunjala-gondi, oriya, tai-le, siddham, cham, takri, telugu, mahajani, batak, bengali, dogra, psalter-pahlavi, hanifi-rohingya
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<843.0,700.0>--<842.0,572.0>>

	* E (U+0045): L<<525.0,700.0>--<524.0,572.0>>

	* Eacute (U+00C9): L<<525.0,700.0>--<524.0,572.0>>

	* Ecaron (U+011A): L<<525.0,700.0>--<524.0,572.0>>

	* Ecircumflex (U+00CA): L<<525.0,700.0>--<524.0,572.0>>

	* Edieresis (U+00CB): L<<525.0,700.0>--<524.0,572.0>>

	* Edotaccent (U+0116): L<<525.0,700.0>--<524.0,572.0>>

	* Egrave (U+00C8): L<<525.0,700.0>--<524.0,572.0>>

	* Emacron (U+0112): L<<525.0,700.0>--<524.0,572.0>>

	* Eogonek (U+0118): L<<525.0,700.0>--<524.0,572.0>>

	* Eturned (U+018E): L<<48.0,572.0>--<47.0,700.0>>

	* F (U+0046): L<<512.0,700.0>--<511.0,572.0>>

	* P (U+0050): L<<79.0,701.0>--<352.0,699.0>>

	* R (U+0052): L<<78.0,701.0>--<369.0,699.0>>

	* Racute (U+0154): L<<78.0,701.0>--<369.0,699.0>>

	* Rcaron (U+0158): L<<78.0,701.0>--<369.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<78.0,701.0>--<369.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<92.0,363.0>--<90.0,700.0>>

	* four (U+0034): L<<64.0,200.0>--<65.0,346.0>>

	* uni0156 (U+0156): L<<78.0,701.0>--<369.0,699.0>>

	* uni0191 (U+0191): L<<512.0,700.0>--<511.0,572.0>>

	* uni01A4 (U+01A4): L<<79.0,701.0>--<352.0,699.0>>

	* uni01E2 (U+01E2): L<<843.0,700.0>--<842.0,572.0>>

	* uni0204 (U+0204): L<<525.0,700.0>--<524.0,572.0>>

	* uni0206 (U+0206): L<<525.0,700.0>--<524.0,572.0>>

	* uni0210 (U+0210): L<<78.0,701.0>--<369.0,699.0>>

	* uni0212 (U+0212): L<<78.0,701.0>--<369.0,699.0>>

	* uni0228 (U+0228): L<<525.0,700.0>--<524.0,572.0>>

	* uni024C (U+024C): L<<78.0,701.0>--<369.0,699.0>>

	* uni1E14 (U+1E14): L<<525.0,700.0>--<524.0,572.0>>

	* uni1E16 (U+1E16): L<<525.0,700.0>--<524.0,572.0>>

	* uni1E18 (U+1E18): L<<525.0,700.0>--<524.0,572.0>>

	* uni1E1A (U+1E1A): L<<525.0,700.0>--<524.0,572.0>>

	* uni1E1C (U+1E1C): L<<525.0,700.0>--<524.0,572.0>>

	* uni1E1E (U+1E1E): L<<512.0,700.0>--<511.0,572.0>>

	* uni1E54 (U+1E54): L<<79.0,701.0>--<352.0,699.0>>

	* uni1E56 (U+1E56): L<<79.0,701.0>--<352.0,699.0>>

	* uni1E58 (U+1E58): L<<78.0,701.0>--<369.0,699.0>>

	* uni1E5A (U+1E5A): L<<78.0,701.0>--<369.0,699.0>>

	* uni1E5C (U+1E5C): L<<78.0,701.0>--<369.0,699.0>>

	* uni1EB8 (U+1EB8): L<<525.0,700.0>--<524.0,572.0>>

	* uni1EBA (U+1EBA): L<<525.0,700.0>--<524.0,572.0>>

	* uni1EBC (U+1EBC): L<<525.0,700.0>--<524.0,572.0>>

	* uni1EBE (U+1EBE): L<<525.0,700.0>--<524.0,572.0>>

	* uni1EC0 (U+1EC0): L<<525.0,700.0>--<524.0,572.0>>

	* uni1EC2 (U+1EC2): L<<525.0,700.0>--<524.0,572.0>>

	* uni1EC4 (U+1EC4): L<<525.0,700.0>--<524.0,572.0>>

	* uni1EC6 (U+1EC6): L<<525.0,700.0>--<524.0,572.0>>

	* uni2074 (U+2074): L<<64.0,200.0>--<65.0,346.0>>

	* uni2075 (U+2075): L<<92.0,363.0>--<90.0,700.0>>

	* uni2084 (U+2084): L<<64.0,200.0>--<65.0,346.0>>

	* uni2085 (U+2085): L<<92.0,363.0>--<90.0,700.0>>

	* uni20A8 (U+20A8): L<<78.0,701.0>--<369.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Ojuju-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0040 (COMMERCIAL AT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "100" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1148, but got 940 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (840) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Tbar	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: lambda	Expected: 1

	- Glyph name: pi	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: minute	Expected: 1

	- Glyph name: second	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: arrowleft	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowright	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: uni2206	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Tbar	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: emptyset	Expected: 3

	- Glyph name: fraction	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lambda	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: pi	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: uni2206	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1 or 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, malayalam, coptic, tifinagh, canadian-aboriginal, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, cherokee, tifinagh, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: tai-viet, wancho, gujarati, bhaiksuki, nko, duployan, tifinagh, hanunoo, soyombo, buginese, newa, hebrew, kayah-li, thai, caucasian-albanian, mongolian, meetei-mayek, gurmukhi, phags-pa, kharoshthi, kannada, malayalam, osage, khmer, modi, yi, mende-kikakui, lepcha, khudawadi, tagalog, zanabazar-square, lao, elbasan, syloti-nagri, chakma, devanagari, tamil, brahmi, kaithi, syriac, music, javanese, bassa-vah, masaram-gondi, symbols, tagbanwa, sinhala, adlam, ahom, tirhuta, coptic, sundanese, grantha, new-tai-lue, myanmar, pahawh-hmong, tibetan, marchen, manichaean, rejang, miao, math, old-permic, mandaic, buhid, sogdian, khojki, sharada, limbu, thaana, balinese, gunjala-gondi, oriya, tai-le, siddham, cham, takri, telugu, mahajani, batak, bengali, dogra, psalter-pahlavi, hanifi-rohingya
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<69.0,701.0>--<576.0,699.0>>

	* OE (U+0152): L<<991.0,700.0>--<990.0,452.0>>

	* P (U+0050): L<<70.0,700.0>--<420.0,699.0>>

	* R (U+0052): L<<70.0,700.0>--<420.0,699.0>>

	* Racute (U+0154): L<<70.0,700.0>--<420.0,699.0>>

	* Rcaron (U+0158): L<<70.0,700.0>--<420.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<70.0,700.0>--<420.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<76.0,357.0>--<74.0,700.0>>

	* nine (U+0039): L<<89.0,12.0>--<88.0,218.0>>

	* six (U+0036): L<<543.0,683.0>--<544.0,477.0>>

	* uni0156 (U+0156): L<<70.0,700.0>--<420.0,699.0>>

	* uni0191 (U+0191): L<<69.0,701.0>--<576.0,699.0>>

	* uni01A4 (U+01A4): L<<70.0,700.0>--<420.0,699.0>>

	* uni0210 (U+0210): L<<70.0,700.0>--<420.0,699.0>>

	* uni0212 (U+0212): L<<70.0,700.0>--<420.0,699.0>>

	* uni024C (U+024C): L<<70.0,700.0>--<420.0,699.0>>

	* uni1E1E (U+1E1E): L<<69.0,701.0>--<576.0,699.0>>

	* uni1E54 (U+1E54): L<<70.0,700.0>--<420.0,699.0>>

	* uni1E56 (U+1E56): L<<70.0,700.0>--<420.0,699.0>>

	* uni1E58 (U+1E58): L<<70.0,700.0>--<420.0,699.0>>

	* uni1E5A (U+1E5A): L<<70.0,700.0>--<420.0,699.0>>

	* uni1E5C (U+1E5C): L<<70.0,700.0>--<420.0,699.0>>

	* uni2075 (U+2075): L<<76.0,357.0>--<74.0,700.0>>

	* uni2076 (U+2076): L<<543.0,683.0>--<544.0,477.0>>

	* uni2079 (U+2079): L<<89.0,12.0>--<88.0,218.0>>

	* uni2085 (U+2085): L<<76.0,357.0>--<74.0,700.0>>

	* uni2086 (U+2086): L<<543.0,683.0>--<544.0,477.0>>

	* uni2089 (U+2089): L<<89.0,12.0>--<88.0,218.0>>

	* uni20A8 (U+20A8): L<<70.0,700.0>--<420.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[19] Ojuju-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x007C (VERTICAL LINE)


	- 0x002B (PLUS SIGN)


	- 0x00D7 (MULTIPLICATION SIGN)


	- 0x00F7 (DIVISION SIGN)


	- 0x003D (EQUALS SIGN)


	- 0x003E (GREATER-THAN SIGN)


	- 0x003C (LESS-THAN SIGN)


	- 0x0025 (PERCENT SIGN)


	- 0x0040 (COMMERCIAL AT)


	- 0x00B6 (PILCROW SIGN)


	- 0x00A7 (SECTION SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x0024 (DOLLAR SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A5 (YEN SIGN)


	- 0x2212 (MINUS SIGN)


	- 0x007E (TILDE)


	- 0x005E (CIRCUMFLEX ACCENT)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "100" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1148, but got 940 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (840) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.7 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: onehalf	Expected: 3

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: Tbar	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: lambda	Expected: 1

	- Glyph name: pi	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: minute	Expected: 1

	- Glyph name: second	Expected: 2

	- Glyph name: fraction	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: arrowleft	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowright	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: uni2206	Expected: 2

	- Glyph name: product	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: Tbar	Expected: 1

	- Glyph name: approxequal	Expected: 2

	- Glyph name: arrowboth	Expected: 1

	- Glyph name: arrowdown	Expected: 1

	- Glyph name: arrowup	Expected: 1

	- Glyph name: arrowupdn	Expected: 1

	- Glyph name: chi	Expected: 1

	- Glyph name: colonmonetary	Expected: 1 or 3

	- Glyph name: dagger	Expected: 1 or 2

	- Glyph name: daggerdbl	Expected: 1 or 3

	- Glyph name: dong	Expected: 3 or 4

	- Glyph name: emptyset	Expected: 3

	- Glyph name: fraction	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: integral	Expected: 1

	- Glyph name: kgreenlandic	Expected: 1 or 2

	- Glyph name: lambda	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: onehalf	Expected: 3

	- Glyph name: onequarter	Expected: 3 or 4

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: pi	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: product	Expected: 1

	- Glyph name: radical	Expected: 1

	- Glyph name: summation	Expected: 1

	- Glyph name: tbar	Expected: 1

	- Glyph name: threequarters	Expected: 3 or 4

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B3	Expected: 1

	- Glyph name: uni01B4	Expected: 1

	- Glyph name: uni01B5	Expected: 1

	- Glyph name: uni01B6	Expected: 1

	- Glyph name: uni01B7	Expected: 1

	- Glyph name: uni01B8	Expected: 1

	- Glyph name: uni01B9	Expected: 1

	- Glyph name: uni01C0	Expected: 1

	- Glyph name: uni01C1	Expected: 2

	- Glyph name: uni01C2	Expected: 1

	- Glyph name: uni01C3	Expected: 2

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni03A9	Expected: 1

	- Glyph name: uni0E3F	Expected: 3 or 5

	- Glyph name: uni2016	Expected: 2

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20B1	Expected: 1, 2 or 4

	- Glyph name: uni20B2	Expected: 1, 2 or 3

	- Glyph name: uni20B4	Expected: 1 or 2

	- Glyph name: uni20B5	Expected: 1 or 2

	- Glyph name: uni20B8	Expected: 2

	- Glyph name: uni20B9	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: uni20BC	Expected: 1

	- Glyph name: uni20BD	Expected: 2

	- Glyph name: uni20BF	Expected: 3

	- Glyph name: uni2113	Expected: 2

	- Glyph name: uni2126	Expected: 1

	- Glyph name: uni2196	Expected: 1

	- Glyph name: uni2197	Expected: 1

	- Glyph name: uni2198	Expected: 1

	- Glyph name: uni2199	Expected: 1

	- Glyph name: uni2206	Expected: 2

	- Glyph name: uni27E8	Expected: 1

	- Glyph name: uni27E9	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni2153	Contours detected: 2	Expected: 3

	- Glyph name: uni2154	Contours detected: 2	Expected: 1 or 3

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0243	Contours detected: 4	Expected: 3

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDB	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDD	Contours detected: 4	Expected: 3

	- Glyph name: uni1EDF	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE1	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE3	Contours detected: 4	Expected: 3

	- Glyph name: uni1EE8	Contours detected: 3	Expected: 2

	- Glyph name: uni1EE9	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEA	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEB	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEC	Contours detected: 3	Expected: 2

	- Glyph name: uni1EED	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEE	Contours detected: 3	Expected: 2

	- Glyph name: uni1EEF	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF0	Contours detected: 3	Expected: 2

	- Glyph name: uni1EF1	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02B8 MODIFIER LETTER SMALL Y: not included in any glyphset definition
 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, tai-le, malayalam, coptic, tifinagh, canadian-aboriginal, math, old-permic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: syriac, cherokee
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: syriac, cherokee, tifinagh, caucasian-albanian, gothic
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math
 * U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DBF MODIFIER LETTER SMALL THETA: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+2016 DOUBLE VERTICAL LINE: not included in any glyphset definition
 * U+2021 DOUBLE DAGGER: try adding adlam
 * U+2030 PER MILLE SIGN: try adding adlam
 * U+2075 SUPERSCRIPT FIVE: not included in any glyphset definition
 * U+2076 SUPERSCRIPT SIX: not included in any glyphset definition
 * U+2077 SUPERSCRIPT SEVEN: not included in any glyphset definition
 * U+2078 SUPERSCRIPT EIGHT: not included in any glyphset definition
 * U+2079 SUPERSCRIPT NINE: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+2081 SUBSCRIPT ONE: not included in any glyphset definition
 * U+2082 SUBSCRIPT TWO: not included in any glyphset definition
 * U+2083 SUBSCRIPT THREE: not included in any glyphset definition
 * U+2084 SUBSCRIPT FOUR: not included in any glyphset definition
 * U+2085 SUBSCRIPT FIVE: not included in any glyphset definition
 * U+2086 SUBSCRIPT SIX: not included in any glyphset definition
 * U+2087 SUBSCRIPT SEVEN: not included in any glyphset definition
 * U+2088 SUBSCRIPT EIGHT: not included in any glyphset definition
 * U+2089 SUBSCRIPT NINE: not included in any glyphset definition
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: math, symbols
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding symbols
 * U+25AB WHITE SMALL SQUARE: try adding symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: tai-viet, wancho, gujarati, bhaiksuki, nko, duployan, tifinagh, hanunoo, soyombo, buginese, newa, hebrew, kayah-li, thai, caucasian-albanian, mongolian, meetei-mayek, gurmukhi, phags-pa, kharoshthi, kannada, malayalam, osage, khmer, modi, yi, mende-kikakui, lepcha, khudawadi, tagalog, zanabazar-square, lao, elbasan, syloti-nagri, chakma, devanagari, tamil, brahmi, kaithi, syriac, music, javanese, bassa-vah, masaram-gondi, symbols, tagbanwa, sinhala, adlam, ahom, tirhuta, coptic, sundanese, grantha, new-tai-lue, myanmar, pahawh-hmong, tibetan, marchen, manichaean, rejang, miao, math, old-permic, mandaic, buhid, sogdian, khojki, sharada, limbu, thaana, balinese, gunjala-gondi, oriya, tai-le, siddham, cham, takri, telugu, mahajani, batak, bengali, dogra, psalter-pahlavi, hanifi-rohingya
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- eight.dnom

	- eight.numr

	- eight.tf

	- five.dnom

	- five.numr

	- five.tf

	- four.dnom

	- four.numr

	- four.tf

	- i.loclTRK

	- nine.dnom

	- nine.numr

	- nine.tf

	- one.dnom

	- one.numr

	- one.tf

	- seven.dnom

	- seven.numr

	- seven.tf

	- six.dnom

	- six.numr

	- six.tf

	- three.dnom

	- three.numr

	- three.tf

	- two.dnom

	- two.numr

	- two.tf

	- uni004A0301

	- uni006A0301

	- uni03000304

	- uni03010304

	- uni03020300

	- uni03020301

	- uni03020303

	- uni03020309

	- uni03040300

	- uni03040301

	- uni03060300

	- uni03060301

	- uni03060303

	- uni03060309

	- zero.dnom

	- zero.numr

	- zero.tf

	- zero.zero
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* P (U+0050): L<<81.0,701.0>--<332.0,699.0>>

	* R (U+0052): L<<80.0,701.0>--<354.0,699.0>>

	* Racute (U+0154): L<<80.0,701.0>--<354.0,699.0>>

	* Rcaron (U+0158): L<<80.0,701.0>--<354.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<80.0,701.0>--<354.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<97.0,365.0>--<95.0,700.0>>

	* four (U+0034): L<<69.0,209.0>--<70.0,327.0>>

	* uni0156 (U+0156): L<<80.0,701.0>--<354.0,699.0>>

	* uni01A4 (U+01A4): L<<81.0,701.0>--<332.0,699.0>>

	* uni0210 (U+0210): L<<80.0,701.0>--<354.0,699.0>>

	* uni0212 (U+0212): L<<80.0,701.0>--<354.0,699.0>>

	* uni024C (U+024C): L<<80.0,701.0>--<354.0,699.0>>

	* uni1E54 (U+1E54): L<<81.0,701.0>--<332.0,699.0>>

	* uni1E56 (U+1E56): L<<81.0,701.0>--<332.0,699.0>>

	* uni1E58 (U+1E58): L<<80.0,701.0>--<354.0,699.0>>

	* uni1E5A (U+1E5A): L<<80.0,701.0>--<354.0,699.0>>

	* uni1E5C (U+1E5C): L<<80.0,701.0>--<354.0,699.0>>

	* uni2074 (U+2074): L<<69.0,209.0>--<70.0,327.0>>

	* uni2075 (U+2075): L<<97.0,365.0>--<95.0,700.0>>

	* uni2084 (U+2084): L<<69.0,209.0>--<70.0,327.0>>

	* uni2085 (U+2085): L<<97.0,365.0>--<95.0,700.0>>

	* uni20A8 (U+20A8): L<<80.0,701.0>--<354.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 21 | 56 | 56 | 849 | 36 | 623 | 0 |
| 1% | 3% | 3% | 52% | 2% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
