## FontBakery report

fontbakery version: 0.10.8

<details><summary><b>[19] Ojuju-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0024 (DOLLAR SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1128, but got 840 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 649, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: less	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: emptyset	Expected: 3

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: radical	Expected: 1

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, tifinagh, malayalam, math, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, caucasian-albanian, tifinagh, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: math, greek
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
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: emoji, symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding one of: emoji, symbols
 * U+25AB WHITE SMALL SQUARE: try adding one of: emoji, symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: hanunoo, khojki, dogra, khmer, nko, new-tai-lue, tirhuta, tagalog, modi, old-permic, soyombo, mandaic, tai-viet, music, syloti-nagri, lepcha, gujarati, math, marchen, takri, ahom, hebrew, elbasan, rejang, phags-pa, buginese, sinhala, oriya, siddham, hanifi-rohingya, bhaiksuki, tagbanwa, masaram-gondi, miao, bassa-vah, devanagari, gunjala-gondi, tifinagh, osage, psalter-pahlavi, tamil, mende-kikakui, meetei-mayek, bengali, kannada, thaana, buhid, caucasian-albanian, balinese, duployan, gurmukhi, brahmi, coptic, symbols, telugu, limbu, tai-le, mongolian, batak, sogdian, chakma, manichaean, syriac, kharoshthi, adlam, yi, mahajani, kaithi, cham, javanese, zanabazar-square, newa, sharada, sundanese, tibetan, grantha, malayalam, lao, pahawh-hmong, khudawadi, kayah-li, wancho, myanmar, thai
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- shortbar
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 592:
divide, multiply, plus

Width = 348:
minus, equal

Width = 593:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni01A4 (U+01A4): L<<122.0,701.0>--<162.0,701.0>> -> L<<162.0,701.0>--<162.0,701.0>>

	* uni01A4 (U+01A4): L<<162.0,701.0>--<162.0,701.0>> -> L<<162.0,701.0>--<383.0,699.0>>

	* uniA78B (U+A78B): L<<155.0,204.0>--<148.0,314.0>> -> L<<148.0,314.0>--<148.0,700.0>>

	* uniA78B (U+A78B): L<<182.0,700.0>--<182.0,314.0>> -> L<<182.0,314.0>--<176.0,204.0>>

	* uniA78C (U+A78C): L<<155.0,492.0>--<148.0,562.0>> -> L<<148.0,562.0>--<148.0,700.0>>

	* uniA78C (U+A78C): L<<180.0,700.0>--<180.0,562.0>> -> L<<180.0,562.0>--<174.0,492.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* divide (U+00F7): B<<25.0,377.0>-<112.0,374.0>-<197.0,375.0>>/B<<197.0,375.0>-<176.0,380.0>-<166.5,392.0>> = 14.0665346517356 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* R (U+0052): L<<81.0,701.0>--<333.0,699.0>>

	* Racute (U+0154): L<<81.0,701.0>--<333.0,699.0>>

	* Rcaron (U+0158): L<<81.0,701.0>--<333.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<81.0,701.0>--<333.0,699.0>>

	* Upsilonlatin (U+01B1): L<<294.0,648.0>--<99.0,649.0>>

	* Upsilonlatin (U+01B1): L<<647.0,649.0>--<452.0,648.0>>

	* f (U+0066): L<<100.0,0.0>--<103.0,438.0>>

	* f (U+0066): L<<127.0,438.0>--<130.0,0.0>>

	* fi (U+FB01): L<<100.0,0.0>--<103.0,438.0>>

	* fi (U+FB01): L<<128.0,438.0>--<131.0,0.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<103.0,367.0>--<101.0,700.0>>

	* fl (U+FB02): L<<100.0,0.0>--<103.0,438.0>>

	* fl (U+FB02): L<<127.0,438.0>--<130.0,0.0>>

	* uni0156 (U+0156): L<<81.0,701.0>--<333.0,699.0>>

	* uni01AD (U+01AD): L<<283.0,438.0>--<124.0,437.0>>

	* uni0210 (U+0210): L<<81.0,701.0>--<333.0,699.0>>

	* uni0212 (U+0212): L<<81.0,701.0>--<333.0,699.0>>

	* uni024C (U+024C): L<<81.0,701.0>--<333.0,699.0>>

	* uni028A (U+028A): L<<213.0,435.0>--<82.0,436.0>>

	* uni028A (U+028A): L<<463.0,436.0>--<331.0,435.0>>

	* uni03A9 (U+03A9): L<<452.0,52.0>--<647.0,51.0>>

	* uni03A9 (U+03A9): L<<99.0,51.0>--<294.0,52.0>>

	* uni1E1F (U+1E1F): L<<100.0,0.0>--<103.0,438.0>>

	* uni1E1F (U+1E1F): L<<127.0,438.0>--<130.0,0.0>>

	* uni1E58 (U+1E58): L<<81.0,701.0>--<333.0,699.0>>

	* uni1E5A (U+1E5A): L<<81.0,701.0>--<333.0,699.0>>

	* uni1E5C (U+1E5C): L<<81.0,701.0>--<333.0,699.0>>

	* uni2075 (U+2075): L<<56.0,614.0>--<55.0,794.0>>

	* uni2085 (U+2085): L<<56.0,144.0>--<55.0,324.0>>

	* uni20A6 (U+20A6): L<<197.0,203.0>--<67.0,202.0>>

	* uni20A6 (U+20A6): L<<197.0,233.0>--<198.0,474.0>>

	* uni20A6 (U+20A6): L<<198.0,474.0>--<67.0,473.0>>

	* uni20A6 (U+20A6): L<<198.0,504.0>--<197.0,700.0>>

	* uni20A6 (U+20A6): L<<669.0,203.0>--<670.0,0.0>>

	* uni20A6 (U+20A6): L<<67.0,234.0>--<197.0,233.0>>

	* uni20A6 (U+20A6): L<<67.0,505.0>--<198.0,504.0>>

	* uni20A8 (U+20A8): L<<81.0,701.0>--<333.0,699.0>>

	* uni2126 (U+2126): L<<452.0,52.0>--<647.0,51.0>>

	* uni2126 (U+2126): L<<99.0,51.0>--<294.0,52.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uni2C64 (U+2C64): L<<81.0,701.0>--<333.0,699.0>>

	* uniA727 (U+A727): L<<463.0,-34.0>--<464.0,298.0>>

	* uniA7B5 (U+A7B5): L<<81.0,-151.0>--<85.0,395.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[18] Ojuju-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0024 (DOLLAR SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1128, but got 840 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 649, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: less	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: emptyset	Expected: 3

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: radical	Expected: 1

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, tifinagh, malayalam, math, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, caucasian-albanian, tifinagh, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: math, greek
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
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: emoji, symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding one of: emoji, symbols
 * U+25AB WHITE SMALL SQUARE: try adding one of: emoji, symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: hanunoo, khojki, dogra, khmer, nko, new-tai-lue, tirhuta, tagalog, modi, old-permic, soyombo, mandaic, tai-viet, music, syloti-nagri, lepcha, gujarati, math, marchen, takri, ahom, hebrew, elbasan, rejang, phags-pa, buginese, sinhala, oriya, siddham, hanifi-rohingya, bhaiksuki, tagbanwa, masaram-gondi, miao, bassa-vah, devanagari, gunjala-gondi, tifinagh, osage, psalter-pahlavi, tamil, mende-kikakui, meetei-mayek, bengali, kannada, thaana, buhid, caucasian-albanian, balinese, duployan, gurmukhi, brahmi, coptic, symbols, telugu, limbu, tai-le, mongolian, batak, sogdian, chakma, manichaean, syriac, kharoshthi, adlam, yi, mahajani, kaithi, cham, javanese, zanabazar-square, newa, sharada, sundanese, tibetan, grantha, malayalam, lao, pahawh-hmong, khudawadi, kayah-li, wancho, myanmar, thai
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- shortbar
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 580:
divide, multiply, plus

Width = 361:
minus, equal

Width = 583:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni01A4 (U+01A4): L<<124.0,701.0>--<171.0,701.0>> -> L<<171.0,701.0>--<171.0,701.0>>

	* uni01A4 (U+01A4): L<<171.0,701.0>--<171.0,701.0>> -> L<<171.0,701.0>--<402.0,699.0>>

	* uniA78B (U+A78B): L<<153.0,203.0>--<146.0,316.0>> -> L<<146.0,316.0>--<146.0,700.0>>

	* uniA78B (U+A78B): L<<184.0,700.0>--<184.0,316.0>> -> L<<184.0,316.0>--<177.0,203.0>>

	* uniA78C (U+A78C): L<<153.0,492.0>--<146.0,565.0>> -> L<<146.0,565.0>--<146.0,700.0>>

	* uniA78C (U+A78C): L<<181.0,700.0>--<181.0,565.0>> -> L<<181.0,565.0>--<174.0,492.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Iotalatin (U+0196): L<<153.0,700.0>--<152.0,384.0>>

	* P (U+0050): L<<80.0,701.0>--<314.0,699.0>>

	* R (U+0052): L<<79.0,701.0>--<340.0,699.0>>

	* Racute (U+0154): L<<79.0,701.0>--<340.0,699.0>>

	* Rcaron (U+0158): L<<79.0,701.0>--<340.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<79.0,701.0>--<340.0,699.0>>

	* Upsilonlatin (U+01B1): L<<280.0,629.0>--<93.0,630.0>>

	* Upsilonlatin (U+01B1): L<<649.0,630.0>--<462.0,629.0>>

	* f (U+0066): L<<101.0,0.0>--<104.0,425.0>>

	* f (U+0066): L<<132.0,425.0>--<135.0,0.0>>

	* fi (U+FB01): L<<101.0,0.0>--<104.0,425.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<101.0,366.0>--<99.0,700.0>>

	* fl (U+FB02): L<<101.0,0.0>--<104.0,425.0>>

	* fl (U+FB02): L<<132.0,425.0>--<135.0,0.0>>

	* uni0156 (U+0156): L<<79.0,701.0>--<340.0,699.0>>

	* uni01A4 (U+01A4): L<<171.0,701.0>--<402.0,699.0>>

	* uni01AD (U+01AD): L<<286.0,425.0>--<126.0,424.0>>

	* uni0210 (U+0210): L<<79.0,701.0>--<340.0,699.0>>

	* uni0212 (U+0212): L<<79.0,701.0>--<340.0,699.0>>

	* uni024C (U+024C): L<<79.0,701.0>--<340.0,699.0>>

	* uni028A (U+028A): L<<202.0,424.0>--<77.0,425.0>>

	* uni028A (U+028A): L<<465.0,425.0>--<340.0,424.0>>

	* uni03A9 (U+03A9): L<<462.0,71.0>--<649.0,70.0>>

	* uni03A9 (U+03A9): L<<93.0,70.0>--<280.0,71.0>>

	* uni1E1F (U+1E1F): L<<101.0,0.0>--<104.0,425.0>>

	* uni1E1F (U+1E1F): L<<132.0,425.0>--<135.0,0.0>>

	* uni1E54 (U+1E54): L<<80.0,701.0>--<314.0,699.0>>

	* uni1E56 (U+1E56): L<<80.0,701.0>--<314.0,699.0>>

	* uni1E58 (U+1E58): L<<79.0,701.0>--<340.0,699.0>>

	* uni1E5A (U+1E5A): L<<79.0,701.0>--<340.0,699.0>>

	* uni1E5C (U+1E5C): L<<79.0,701.0>--<340.0,699.0>>

	* uni2075 (U+2075): L<<54.0,614.0>--<53.0,794.0>>

	* uni2085 (U+2085): L<<54.0,144.0>--<53.0,324.0>>

	* uni20A6 (U+20A6): L<<194.0,201.0>--<65.0,200.0>>

	* uni20A6 (U+20A6): L<<194.0,236.0>--<195.0,473.0>>

	* uni20A6 (U+20A6): L<<194.0,508.0>--<193.0,700.0>>

	* uni20A6 (U+20A6): L<<195.0,473.0>--<65.0,472.0>>

	* uni20A6 (U+20A6): L<<65.0,237.0>--<194.0,236.0>>

	* uni20A6 (U+20A6): L<<65.0,509.0>--<194.0,508.0>>

	* uni20A6 (U+20A6): L<<671.0,201.0>--<672.0,0.0>>

	* uni20A8 (U+20A8): L<<79.0,701.0>--<340.0,699.0>>

	* uni20B1 (U+20B1): L<<80.0,701.0>--<314.0,699.0>>

	* uni20BD (U+20BD): L<<80.0,701.0>--<314.0,699.0>>

	* uni2126 (U+2126): L<<462.0,71.0>--<649.0,70.0>>

	* uni2126 (U+2126): L<<93.0,70.0>--<280.0,71.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uni2C63 (U+2C63): L<<80.0,701.0>--<314.0,699.0>>

	* uni2C64 (U+2C64): L<<79.0,701.0>--<340.0,699.0>>

	* uniA727 (U+A727): L<<460.0,-16.0>--<462.0,287.0>>

	* uniA7B5 (U+A7B5): L<<79.0,-150.0>--<83.0,395.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[18] Ojuju-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0024 (DOLLAR SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1128, but got 840 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 649, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: less	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: emptyset	Expected: 3

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: radical	Expected: 1

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, tifinagh, malayalam, math, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, caucasian-albanian, tifinagh, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: math, greek
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
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: emoji, symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding one of: emoji, symbols
 * U+25AB WHITE SMALL SQUARE: try adding one of: emoji, symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: hanunoo, khojki, dogra, khmer, nko, new-tai-lue, tirhuta, tagalog, modi, old-permic, soyombo, mandaic, tai-viet, music, syloti-nagri, lepcha, gujarati, math, marchen, takri, ahom, hebrew, elbasan, rejang, phags-pa, buginese, sinhala, oriya, siddham, hanifi-rohingya, bhaiksuki, tagbanwa, masaram-gondi, miao, bassa-vah, devanagari, gunjala-gondi, tifinagh, osage, psalter-pahlavi, tamil, mende-kikakui, meetei-mayek, bengali, kannada, thaana, buhid, caucasian-albanian, balinese, duployan, gurmukhi, brahmi, coptic, symbols, telugu, limbu, tai-le, mongolian, batak, sogdian, chakma, manichaean, syriac, kharoshthi, adlam, yi, mahajani, kaithi, cham, javanese, zanabazar-square, newa, sharada, sundanese, tibetan, grantha, malayalam, lao, pahawh-hmong, khudawadi, kayah-li, wancho, myanmar, thai
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- shortbar
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 508:
plus

Width = 441:
minus, equal

Width = 507:
multiply

Width = 506:
divide

Width = 521:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni01A4 (U+01A4): L<<141.0,700.0>--<221.0,700.0>> -> L<<221.0,700.0>--<221.0,700.0>>

	* uni01A4 (U+01A4): L<<221.0,700.0>--<221.0,700.0>> -> L<<221.0,700.0>--<518.0,699.0>>

	* uniA78B (U+A78B): L<<141.0,199.0>--<130.0,328.0>> -> L<<130.0,328.0>--<130.0,700.0>>

	* uniA78B (U+A78B): L<<194.0,700.0>--<194.0,328.0>> -> L<<194.0,328.0>--<184.0,199.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<66.0,701.0>--<531.0,699.0>>

	* Iotalatin (U+0196): L<<217.0,700.0>--<216.0,450.0>>

	* P (U+0050): L<<67.0,700.0>--<372.0,699.0>>

	* R (U+0052): L<<67.0,700.0>--<382.0,699.0>>

	* Racute (U+0154): L<<67.0,700.0>--<382.0,699.0>>

	* Rcaron (U+0158): L<<67.0,700.0>--<382.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<67.0,700.0>--<382.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<86.0,361.0>--<84.0,700.0>>

	* fl (U+FB02): L<<522.0,739.0>--<521.0,476.0>>

	* florin (U+0192): L<<1.0,-196.0>--<0.0,-60.0>>

	* florin (U+0192): L<<209.0,343.0>--<208.0,493.0>>

	* nine (U+0039): L<<90.0,10.0>--<89.0,162.0>>

	* uni0156 (U+0156): L<<67.0,700.0>--<382.0,699.0>>

	* uni0191 (U+0191): L<<118.0,701.0>--<583.0,699.0>>

	* uni0191 (U+0191): L<<581.0,522.0>--<343.0,524.0>>

	* uni01A4 (U+01A4): L<<221.0,700.0>--<518.0,699.0>>

	* uni01AD (U+01AD): L<<303.0,343.0>--<135.0,342.0>>

	* uni01AD (U+01AD): L<<87.0,169.0>--<88.0,343.0>>

	* uni0210 (U+0210): L<<67.0,700.0>--<382.0,699.0>>

	* uni0212 (U+0212): L<<67.0,700.0>--<382.0,699.0>>

	* uni024C (U+024C): L<<67.0,700.0>--<382.0,699.0>>

	* uni0269 (U+0269): L<<199.0,493.0>--<198.0,285.0>>

	* uni1E1E (U+1E1E): L<<66.0,701.0>--<531.0,699.0>>

	* uni1E54 (U+1E54): L<<67.0,700.0>--<372.0,699.0>>

	* uni1E56 (U+1E56): L<<67.0,700.0>--<372.0,699.0>>

	* uni1E58 (U+1E58): L<<67.0,700.0>--<382.0,699.0>>

	* uni1E5A (U+1E5A): L<<67.0,700.0>--<382.0,699.0>>

	* uni1E5C (U+1E5C): L<<67.0,700.0>--<382.0,699.0>>

	* uni2075 (U+2075): L<<46.0,611.0>--<45.0,794.0>>

	* uni2085 (U+2085): L<<46.0,141.0>--<45.0,324.0>>

	* uni20A6 (U+20A6): L<<170.0,189.0>--<51.0,188.0>>

	* uni20A6 (U+20A6): L<<170.0,530.0>--<169.0,700.0>>

	* uni20A6 (U+20A6): L<<171.0,464.0>--<51.0,463.0>>

	* uni20A8 (U+20A8): L<<67.0,700.0>--<382.0,699.0>>

	* uni20B1 (U+20B1): L<<67.0,700.0>--<372.0,699.0>>

	* uni20BD (U+20BD): L<<67.0,700.0>--<372.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uni2C63 (U+2C63): L<<67.0,700.0>--<372.0,699.0>>

	* uni2C64 (U+2C64): L<<67.0,700.0>--<383.0,699.0>>

	* uniA7B5 (U+A7B5): L<<66.0,-141.0>--<70.0,395.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[19] Ojuju-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0024 (DOLLAR SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1128, but got 840 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 649, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: less	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: emptyset	Expected: 3

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: radical	Expected: 1

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, tifinagh, malayalam, math, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, caucasian-albanian, tifinagh, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: math, greek
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
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: emoji, symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding one of: emoji, symbols
 * U+25AB WHITE SMALL SQUARE: try adding one of: emoji, symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: hanunoo, khojki, dogra, khmer, nko, new-tai-lue, tirhuta, tagalog, modi, old-permic, soyombo, mandaic, tai-viet, music, syloti-nagri, lepcha, gujarati, math, marchen, takri, ahom, hebrew, elbasan, rejang, phags-pa, buginese, sinhala, oriya, siddham, hanifi-rohingya, bhaiksuki, tagbanwa, masaram-gondi, miao, bassa-vah, devanagari, gunjala-gondi, tifinagh, osage, psalter-pahlavi, tamil, mende-kikakui, meetei-mayek, bengali, kannada, thaana, buhid, caucasian-albanian, balinese, duployan, gurmukhi, brahmi, coptic, symbols, telugu, limbu, tai-le, mongolian, batak, sogdian, chakma, manichaean, syriac, kharoshthi, adlam, yi, mahajani, kaithi, cham, javanese, zanabazar-square, newa, sharada, sundanese, tibetan, grantha, malayalam, lao, pahawh-hmong, khudawadi, kayah-li, wancho, myanmar, thai
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- shortbar
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 11 math glyphs.
The following math glyphs have a different width, though:

Width = 339:
minus, equal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni01A4 (U+01A4): L<<120.0,701.0>--<157.0,701.0>> -> L<<157.0,701.0>--<157.0,701.0>>

	* uni01A4 (U+01A4): L<<157.0,701.0>--<157.0,701.0>> -> L<<157.0,701.0>--<370.0,699.0>>

	* uniA78B (U+A78B): L<<156.0,204.0>--<150.0,313.0>> -> L<<150.0,313.0>--<150.0,700.0>>

	* uniA78B (U+A78B): L<<181.0,700.0>--<181.0,313.0>> -> L<<181.0,313.0>--<175.0,204.0>>

	* uniA78C (U+A78C): L<<156.0,491.0>--<150.0,560.0>> -> L<<150.0,560.0>--<150.0,700.0>>

	* uniA78C (U+A78C): L<<179.0,700.0>--<179.0,560.0>> -> L<<179.0,560.0>--<173.0,491.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* divide (U+00F7): B<<24.0,375.0>-<116.0,372.0>-<206.0,373.0>>/B<<206.0,373.0>-<180.0,377.0>-<168.5,389.5>> = 9.382755838518671

	* divide (U+00F7): B<<307.0,420.0>-<307.0,382.0>-<263.0,374.0>>/B<<263.0,374.0>-<289.0,374.0>-<315.0,375.0>> = 10.304846468766044 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* R (U+0052): L<<82.0,701.0>--<328.0,699.0>>

	* Racute (U+0154): L<<82.0,701.0>--<328.0,699.0>>

	* Rcaron (U+0158): L<<82.0,701.0>--<328.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<82.0,701.0>--<328.0,699.0>>

	* Upsilonlatin (U+01B1): L<<303.0,660.0>--<102.0,661.0>>

	* Upsilonlatin (U+01B1): L<<646.0,661.0>--<445.0,660.0>>

	* f (U+0066): L<<124.0,447.0>--<127.0,0.0>>

	* f (U+0066): L<<99.0,0.0>--<102.0,447.0>>

	* fi (U+FB01): L<<124.0,447.0>--<127.0,0.0>>

	* fi (U+FB01): L<<99.0,0.0>--<102.0,447.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<105.0,368.0>--<103.0,700.0>>

	* fl (U+FB02): L<<124.0,447.0>--<127.0,0.0>>

	* fl (U+FB02): L<<99.0,0.0>--<102.0,447.0>>

	* uni0156 (U+0156): L<<82.0,701.0>--<328.0,699.0>>

	* uni01AD (U+01AD): L<<281.0,447.0>--<123.0,446.0>>

	* uni0210 (U+0210): L<<82.0,701.0>--<328.0,699.0>>

	* uni0212 (U+0212): L<<82.0,701.0>--<328.0,699.0>>

	* uni024C (U+024C): L<<82.0,701.0>--<328.0,699.0>>

	* uni028A (U+028A): L<<220.0,442.0>--<85.0,443.0>>

	* uni028A (U+028A): L<<462.0,443.0>--<326.0,442.0>>

	* uni03A9 (U+03A9): L<<102.0,39.0>--<303.0,40.0>>

	* uni03A9 (U+03A9): L<<445.0,40.0>--<646.0,39.0>>

	* uni1E1F (U+1E1F): L<<124.0,447.0>--<127.0,0.0>>

	* uni1E1F (U+1E1F): L<<99.0,0.0>--<102.0,447.0>>

	* uni1E58 (U+1E58): L<<82.0,701.0>--<328.0,699.0>>

	* uni1E5A (U+1E5A): L<<82.0,701.0>--<328.0,699.0>>

	* uni1E5C (U+1E5C): L<<82.0,701.0>--<328.0,699.0>>

	* uni2075 (U+2075): L<<57.0,615.0>--<56.0,794.0>>

	* uni2085 (U+2085): L<<57.0,145.0>--<56.0,324.0>>

	* uni20A6 (U+20A6): L<<200.0,204.0>--<69.0,203.0>>

	* uni20A6 (U+20A6): L<<200.0,231.0>--<201.0,475.0>>

	* uni20A6 (U+20A6): L<<201.0,475.0>--<69.0,474.0>>

	* uni20A6 (U+20A6): L<<201.0,502.0>--<200.0,700.0>>

	* uni20A6 (U+20A6): L<<667.0,204.0>--<668.0,0.0>>

	* uni20A6 (U+20A6): L<<69.0,232.0>--<200.0,231.0>>

	* uni20A6 (U+20A6): L<<69.0,503.0>--<201.0,502.0>>

	* uni20A8 (U+20A8): L<<82.0,701.0>--<328.0,699.0>>

	* uni2126 (U+2126): L<<102.0,39.0>--<303.0,40.0>>

	* uni2126 (U+2126): L<<445.0,40.0>--<646.0,39.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uni2C64 (U+2C64): L<<82.0,701.0>--<328.0,699.0>>

	* uniA727 (U+A727): L<<464.0,-46.0>--<466.0,305.0>>

	* uniA7B5 (U+A7B5): L<<82.0,-152.0>--<86.0,395.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[18] Ojuju-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0024 (DOLLAR SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1128, but got 840 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 649, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: less	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: emptyset	Expected: 3

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: radical	Expected: 1

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: numbersign	Contours detected: 1	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: numbersign	Contours detected: 1	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, tifinagh, malayalam, math, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, caucasian-albanian, tifinagh, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: math, greek
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
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: emoji, symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding one of: emoji, symbols
 * U+25AB WHITE SMALL SQUARE: try adding one of: emoji, symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: hanunoo, khojki, dogra, khmer, nko, new-tai-lue, tirhuta, tagalog, modi, old-permic, soyombo, mandaic, tai-viet, music, syloti-nagri, lepcha, gujarati, math, marchen, takri, ahom, hebrew, elbasan, rejang, phags-pa, buginese, sinhala, oriya, siddham, hanifi-rohingya, bhaiksuki, tagbanwa, masaram-gondi, miao, bassa-vah, devanagari, gunjala-gondi, tifinagh, osage, psalter-pahlavi, tamil, mende-kikakui, meetei-mayek, bengali, kannada, thaana, buhid, caucasian-albanian, balinese, duployan, gurmukhi, brahmi, coptic, symbols, telugu, limbu, tai-le, mongolian, batak, sogdian, chakma, manichaean, syriac, kharoshthi, adlam, yi, mahajani, kaithi, cham, javanese, zanabazar-square, newa, sharada, sundanese, tibetan, grantha, malayalam, lao, pahawh-hmong, khudawadi, kayah-li, wancho, myanmar, thai
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- shortbar
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 541:
plus

Width = 405:
minus, equal

Width = 540:
multiply

Width = 539:
divide

Width = 549:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni01A4 (U+01A4): L<<133.0,701.0>--<198.0,701.0>> -> L<<198.0,701.0>--<198.0,701.0>>

	* uni01A4 (U+01A4): L<<198.0,701.0>--<198.0,701.0>> -> L<<198.0,701.0>--<466.0,699.0>>

	* uniA78B (U+A78B): L<<146.0,201.0>--<137.0,323.0>> -> L<<137.0,323.0>--<137.0,700.0>>

	* uniA78B (U+A78B): L<<190.0,700.0>--<190.0,323.0>> -> L<<190.0,323.0>--<181.0,201.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<843.0,700.0>--<842.0,572.0>>

	* E (U+0045): L<<514.0,700.0>--<513.0,572.0>>

	* Eacute (U+00C9): L<<514.0,700.0>--<513.0,572.0>>

	* Ecaron (U+011A): L<<514.0,700.0>--<513.0,572.0>>

	* Ecircumflex (U+00CA): L<<514.0,700.0>--<513.0,572.0>>

	* Edieresis (U+00CB): L<<514.0,700.0>--<513.0,572.0>>

	* Edotaccent (U+0116): L<<514.0,700.0>--<513.0,572.0>>

	* Egrave (U+00C8): L<<514.0,700.0>--<513.0,572.0>>

	* Emacron (U+0112): L<<514.0,700.0>--<513.0,572.0>>

	* Eogonek (U+0118): L<<514.0,700.0>--<513.0,572.0>>

	* F (U+0046): L<<506.0,700.0>--<505.0,572.0>>

	* Iotalatin (U+0196): L<<188.0,700.0>--<187.0,420.0>>

	* P (U+0050): L<<73.0,701.0>--<346.0,699.0>>

	* R (U+0052): L<<72.0,701.0>--<363.0,699.0>>

	* Racute (U+0154): L<<72.0,701.0>--<363.0,699.0>>

	* Rcaron (U+0158): L<<72.0,701.0>--<363.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<72.0,701.0>--<363.0,699.0>>

	* Upsilonlatin (U+01B1): L<<235.0,566.0>--<76.0,567.0>>

	* Upsilonlatin (U+01B1): L<<654.0,567.0>--<495.0,566.0>>

	* fi (U+FB01): L<<105.0,0.0>--<108.0,380.0>>

	* fi (U+FB01): L<<153.0,380.0>--<156.0,0.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<92.0,363.0>--<90.0,700.0>>

	* fl (U+FB02): L<<497.0,739.0>--<496.0,437.0>>

	* four (U+0034): L<<64.0,200.0>--<65.0,346.0>>

	* uni0156 (U+0156): L<<72.0,701.0>--<363.0,699.0>>

	* uni018E (U+018E): L<<31.0,572.0>--<30.0,700.0>>

	* uni01A4 (U+01A4): L<<198.0,701.0>--<466.0,699.0>>

	* uni01AD (U+01AD): L<<295.0,380.0>--<131.0,379.0>>

	* uni01AD (U+01AD): L<<92.0,154.0>--<93.0,380.0>>

	* uni01E2 (U+01E2): L<<843.0,700.0>--<842.0,572.0>>

	* uni0204 (U+0204): L<<514.0,700.0>--<513.0,572.0>>

	* uni0206 (U+0206): L<<514.0,700.0>--<513.0,572.0>>

	* uni0210 (U+0210): L<<72.0,701.0>--<363.0,699.0>>

	* uni0212 (U+0212): L<<72.0,701.0>--<363.0,699.0>>

	* uni0228 (U+0228): L<<514.0,700.0>--<513.0,572.0>>

	* uni0246 (U+0246): L<<514.0,700.0>--<513.0,572.0>>

	* uni024C (U+024C): L<<72.0,701.0>--<363.0,699.0>>

	* uni0269 (U+0269): L<<184.0,489.0>--<183.0,281.0>>

	* uni03A9 (U+03A9): L<<495.0,134.0>--<654.0,133.0>>

	* uni03A9 (U+03A9): L<<76.0,133.0>--<235.0,134.0>>

	* uni1E14 (U+1E14): L<<514.0,700.0>--<513.0,572.0>>

	* uni1E16 (U+1E16): L<<514.0,700.0>--<513.0,572.0>>

	* uni1E18 (U+1E18): L<<514.0,700.0>--<513.0,572.0>>

	* uni1E1A (U+1E1A): L<<514.0,700.0>--<513.0,572.0>>

	* uni1E1C (U+1E1C): L<<514.0,700.0>--<513.0,572.0>>

	* uni1E1E (U+1E1E): L<<506.0,700.0>--<505.0,572.0>>

	* uni1E54 (U+1E54): L<<73.0,701.0>--<346.0,699.0>>

	* uni1E56 (U+1E56): L<<73.0,701.0>--<346.0,699.0>>

	* uni1E58 (U+1E58): L<<72.0,701.0>--<363.0,699.0>>

	* uni1E5A (U+1E5A): L<<72.0,701.0>--<363.0,699.0>>

	* uni1E5C (U+1E5C): L<<72.0,701.0>--<363.0,699.0>>

	* uni1EB8 (U+1EB8): L<<514.0,700.0>--<513.0,572.0>>

	* uni1EBA (U+1EBA): L<<514.0,700.0>--<513.0,572.0>>

	* uni1EBC (U+1EBC): L<<514.0,700.0>--<513.0,572.0>>

	* uni1EBE (U+1EBE): L<<514.0,700.0>--<513.0,572.0>>

	* uni1EC0 (U+1EC0): L<<514.0,700.0>--<513.0,572.0>>

	* uni1EC2 (U+1EC2): L<<514.0,700.0>--<513.0,572.0>>

	* uni1EC4 (U+1EC4): L<<514.0,700.0>--<513.0,572.0>>

	* uni1EC6 (U+1EC6): L<<514.0,700.0>--<513.0,572.0>>

	* uni2075 (U+2075): L<<50.0,612.0>--<49.0,794.0>>

	* uni2085 (U+2085): L<<50.0,142.0>--<49.0,324.0>>

	* uni20A6 (U+20A6): L<<181.0,194.0>--<57.0,193.0>>

	* uni20A6 (U+20A6): L<<181.0,247.0>--<182.0,468.0>>

	* uni20A6 (U+20A6): L<<181.0,520.0>--<180.0,700.0>>

	* uni20A6 (U+20A6): L<<182.0,468.0>--<57.0,467.0>>

	* uni20A6 (U+20A6): L<<57.0,248.0>--<181.0,247.0>>

	* uni20A6 (U+20A6): L<<680.0,194.0>--<681.0,0.0>>

	* uni20A8 (U+20A8): L<<72.0,701.0>--<363.0,699.0>>

	* uni20B1 (U+20B1): L<<73.0,701.0>--<346.0,699.0>>

	* uni20BD (U+20BD): L<<73.0,701.0>--<346.0,699.0>>

	* uni2126 (U+2126): L<<495.0,134.0>--<654.0,133.0>>

	* uni2126 (U+2126): L<<76.0,133.0>--<235.0,134.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uni2C63 (U+2C63): L<<73.0,701.0>--<346.0,699.0>>

	* uni2C64 (U+2C64): L<<72.0,701.0>--<363.0,699.0>>

	* uniA727 (U+A727): L<<453.0,46.0>--<454.0,250.0>>

	* uniA7B5 (U+A7B5): L<<72.0,-145.0>--<76.0,395.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[18] Ojuju-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0024 (DOLLAR SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1128, but got 840 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 649, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: less	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: emptyset	Expected: 3

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: radical	Expected: 1

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, tifinagh, malayalam, math, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, caucasian-albanian, tifinagh, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: math, greek
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
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: emoji, symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding one of: emoji, symbols
 * U+25AB WHITE SMALL SQUARE: try adding one of: emoji, symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: hanunoo, khojki, dogra, khmer, nko, new-tai-lue, tirhuta, tagalog, modi, old-permic, soyombo, mandaic, tai-viet, music, syloti-nagri, lepcha, gujarati, math, marchen, takri, ahom, hebrew, elbasan, rejang, phags-pa, buginese, sinhala, oriya, siddham, hanifi-rohingya, bhaiksuki, tagbanwa, masaram-gondi, miao, bassa-vah, devanagari, gunjala-gondi, tifinagh, osage, psalter-pahlavi, tamil, mende-kikakui, meetei-mayek, bengali, kannada, thaana, buhid, caucasian-albanian, balinese, duployan, gurmukhi, brahmi, coptic, symbols, telugu, limbu, tai-le, mongolian, batak, sogdian, chakma, manichaean, syriac, kharoshthi, adlam, yi, mahajani, kaithi, cham, javanese, zanabazar-square, newa, sharada, sundanese, tibetan, grantha, malayalam, lao, pahawh-hmong, khudawadi, kayah-li, wancho, myanmar, thai
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- shortbar
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 463:
plus

Width = 491:
minus, equal

Width = 461:
multiply

Width = 459:
divide

Width = 482:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni01A4 (U+01A4): L<<151.0,700.0>--<252.0,700.0>> -> L<<252.0,700.0>--<252.0,700.0>>

	* uni01A4 (U+01A4): L<<252.0,700.0>--<252.0,700.0>> -> L<<252.0,700.0>--<591.0,699.0>>

	* uniA78B (U+A78B): L<<133.0,196.0>--<120.0,336.0>> -> L<<120.0,336.0>--<120.0,700.0>>

	* uniA78B (U+A78B): L<<201.0,700.0>--<201.0,336.0>> -> L<<201.0,336.0>--<188.0,196.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<58.0,701.0>--<565.0,699.0>>

	* OE (U+0152): L<<991.0,700.0>--<990.0,452.0>>

	* P (U+0050): L<<59.0,700.0>--<409.0,699.0>>

	* R (U+0052): L<<59.0,700.0>--<409.0,699.0>>

	* Racute (U+0154): L<<59.0,700.0>--<409.0,699.0>>

	* Rcaron (U+0158): L<<59.0,700.0>--<409.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<59.0,700.0>--<409.0,699.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<76.0,357.0>--<74.0,700.0>>

	* nine (U+0039): L<<89.0,12.0>--<88.0,218.0>>

	* six (U+0036): L<<543.0,683.0>--<544.0,477.0>>

	* uni0156 (U+0156): L<<59.0,700.0>--<409.0,699.0>>

	* uni0191 (U+0191): L<<114.0,701.0>--<621.0,699.0>>

	* uni01A4 (U+01A4): L<<252.0,700.0>--<591.0,699.0>>

	* uni0210 (U+0210): L<<59.0,700.0>--<409.0,699.0>>

	* uni0212 (U+0212): L<<59.0,700.0>--<409.0,699.0>>

	* uni024C (U+024C): L<<59.0,700.0>--<409.0,699.0>>

	* uni1E1E (U+1E1E): L<<58.0,701.0>--<565.0,699.0>>

	* uni1E54 (U+1E54): L<<59.0,700.0>--<409.0,699.0>>

	* uni1E56 (U+1E56): L<<59.0,700.0>--<409.0,699.0>>

	* uni1E58 (U+1E58): L<<59.0,700.0>--<409.0,699.0>>

	* uni1E5A (U+1E5A): L<<59.0,700.0>--<409.0,699.0>>

	* uni1E5C (U+1E5C): L<<59.0,700.0>--<409.0,699.0>>

	* uni2075 (U+2075): L<<41.0,609.0>--<40.0,794.0>>

	* uni2085 (U+2085): L<<41.0,139.0>--<40.0,324.0>>

	* uni20A8 (U+20A8): L<<59.0,700.0>--<409.0,699.0>>

	* uni20B1 (U+20B1): L<<59.0,700.0>--<409.0,699.0>>

	* uni20BD (U+20BD): L<<59.0,700.0>--<409.0,699.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uni2C63 (U+2C63): L<<59.0,700.0>--<409.0,699.0>>

	* uni2C64 (U+2C64): L<<60.0,700.0>--<410.0,699.0>>

	* uniA7B5 (U+A7B5): L<<125.0,21.0>--<126.0,-135.0>>

	* uniA7B5 (U+A7B5): L<<58.0,-135.0>--<62.0,395.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[18] Ojuju-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0024 (DOLLAR SIGN)


	- 0x00A2 (CENT SIGN)


	- 0x00A3 (POUND SIGN)


	- 0x00A9 (COPYRIGHT SIGN)


	- 0x00AE (REGISTERED SIGN)


	- 0x2122 (TRADE MARK SIGN)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1100 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1128, but got 840 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 649, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: less	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: emptyset	Expected: 3

	- Glyph name: radical	Expected: 1

	- Glyph name: infinity	Expected: 3

	- Glyph name: lessequal	Expected: 2

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: emptyset	Expected: 3

	- Glyph name: greater	Expected: 1

	- Glyph name: greaterequal	Expected: 2

	- Glyph name: infinity	Expected: 3

	- Glyph name: less	Expected: 1

	- Glyph name: lessequal	Expected: 2

	- Glyph name: logicalnot	Expected: 1

	- Glyph name: partialdiff	Expected: 2

	- Glyph name: perthousand	Expected: 6 or 7

	- Glyph name: plusminus	Expected: 1 or 2

	- Glyph name: radical	Expected: 1

	- Glyph name: uni00B5	Expected: 1

	- Glyph name: uni20A9	Expected: 1, 3, 4 or 7

	- Glyph name: uni20AA	Expected: 2

	- Glyph name: uni20AE	Expected: 1

	- Glyph name: uni20BA	Expected: 1

	- Glyph name: yen	Expected: 1 or 2
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni01EB	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: Euro	Contours detected: 3	Expected: 1 or 2

	- Glyph name: Lslash	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: divide	Contours detected: 2	Expected: 3

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: lslash	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni019B	Contours detected: 2	Expected: 1

	- Glyph name: uni01A5	Contours detected: 3	Expected: 2

	- Glyph name: uni01B5	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E5	Contours detected: 3	Expected: 2

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3

	- Glyph name: uni01ED	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni024C	Contours detected: 3	Expected: 2

	- Glyph name: uni024D	Contours detected: 2	Expected: 1

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

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

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 11	Expected: 16 or 12

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
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
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C8 MODIFIER LETTER VERTICAL LINE: not included in any glyphset definition
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, cherokee, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, syriac, tai-le, tifinagh, malayalam, math, old-permic, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+0315 COMBINING COMMA ABOVE RIGHT: not included in any glyphset definition
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, syriac
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, syriac, math
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, syriac, caucasian-albanian, tifinagh, cherokee
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek
 * U+03C7 GREEK SMALL LETTER CHI: try adding one of: math, greek
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
 * U+2116 NUMERO SIGN: try adding cyrillic
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: emoji, symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, symbols, math
 * U+2202 PARTIAL DIFFERENTIAL: try adding math
 * U+2205 EMPTY SET: try adding math
 * U+2206 INCREMENT: try adding math
 * U+220F N-ARY PRODUCT: try adding math
 * U+2211 N-ARY SUMMATION: try adding math
 * U+221A SQUARE ROOT: try adding math
 * U+221E INFINITY: try adding math
 * U+222B INTEGRAL: try adding math
 * U+2248 ALMOST EQUAL TO: try adding math
 * U+2260 NOT EQUAL TO: try adding math
 * U+2264 LESS-THAN OR EQUAL TO: try adding math
 * U+2265 GREATER-THAN OR EQUAL TO: try adding math
 * U+25A0 BLACK SQUARE: try adding symbols
 * U+25A1 WHITE SQUARE: try adding symbols
 * U+25AA BLACK SMALL SQUARE: try adding one of: emoji, symbols
 * U+25AB WHITE SMALL SQUARE: try adding one of: emoji, symbols
 * U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: symbols, math
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: symbols, math
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: hanunoo, khojki, dogra, khmer, nko, new-tai-lue, tirhuta, tagalog, modi, old-permic, soyombo, mandaic, tai-viet, music, syloti-nagri, lepcha, gujarati, math, marchen, takri, ahom, hebrew, elbasan, rejang, phags-pa, buginese, sinhala, oriya, siddham, hanifi-rohingya, bhaiksuki, tagbanwa, masaram-gondi, miao, bassa-vah, devanagari, gunjala-gondi, tifinagh, osage, psalter-pahlavi, tamil, mende-kikakui, meetei-mayek, bengali, kannada, thaana, buhid, caucasian-albanian, balinese, duployan, gurmukhi, brahmi, coptic, symbols, telugu, limbu, tai-le, mongolian, batak, sogdian, chakma, manichaean, syriac, kharoshthi, adlam, yi, mahajani, kaithi, cham, javanese, zanabazar-square, newa, sharada, sundanese, tibetan, grantha, malayalam, lao, pahawh-hmong, khudawadi, kayah-li, wancho, myanmar, thai
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- shortbar
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 600 among a set of 7 math glyphs.
The following math glyphs have a different width, though:

Width = 564:
plus

Width = 379:
minus, equal

Width = 563:
divide, multiply

Width = 569:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni01A4 (U+01A4): L<<128.0,701.0>--<182.0,701.0>> -> L<<182.0,701.0>--<182.0,701.0>>

	* uni01A4 (U+01A4): L<<182.0,701.0>--<182.0,701.0>> -> L<<182.0,701.0>--<429.0,699.0>>

	* uniA78B (U+A78B): L<<150.0,202.0>--<142.0,319.0>> -> L<<142.0,319.0>--<142.0,700.0>>

	* uniA78B (U+A78B): L<<186.0,700.0>--<186.0,319.0>> -> L<<186.0,319.0>--<178.0,202.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* Iotalatin (U+0196): L<<168.0,700.0>--<167.0,399.0>>

	* P (U+0050): L<<77.0,701.0>--<327.0,699.0>>

	* R (U+0052): L<<76.0,701.0>--<349.0,699.0>>

	* Racute (U+0154): L<<76.0,701.0>--<349.0,699.0>>

	* Rcaron (U+0158): L<<76.0,701.0>--<349.0,699.0>>

	* Rmacronbelow (U+1E5E): L<<76.0,701.0>--<349.0,699.0>>

	* Upsilonlatin (U+01B1): L<<261.0,602.0>--<86.0,603.0>>

	* Upsilonlatin (U+01B1): L<<651.0,603.0>--<476.0,602.0>>

	* fi (U+FB01): L<<142.0,406.0>--<145.0,0.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* five (U+0035): L<<97.0,365.0>--<95.0,700.0>>

	* four (U+0034): L<<69.0,209.0>--<70.0,327.0>>

	* uni0156 (U+0156): L<<76.0,701.0>--<349.0,699.0>>

	* uni0191 (U+0191): L<<536.0,608.0>--<328.0,609.0>>

	* uni01A4 (U+01A4): L<<182.0,701.0>--<429.0,699.0>>

	* uni01AD (U+01AD): L<<290.0,406.0>--<128.0,405.0>>

	* uni0210 (U+0210): L<<76.0,701.0>--<349.0,699.0>>

	* uni0212 (U+0212): L<<76.0,701.0>--<349.0,699.0>>

	* uni024C (U+024C): L<<76.0,701.0>--<349.0,699.0>>

	* uni0269 (U+0269): L<<173.0,485.0>--<172.0,279.0>>

	* uni03A9 (U+03A9): L<<476.0,98.0>--<651.0,97.0>>

	* uni03A9 (U+03A9): L<<86.0,97.0>--<261.0,98.0>>

	* uni1E54 (U+1E54): L<<77.0,701.0>--<327.0,699.0>>

	* uni1E56 (U+1E56): L<<77.0,701.0>--<327.0,699.0>>

	* uni1E58 (U+1E58): L<<76.0,701.0>--<349.0,699.0>>

	* uni1E5A (U+1E5A): L<<76.0,701.0>--<349.0,699.0>>

	* uni1E5C (U+1E5C): L<<76.0,701.0>--<349.0,699.0>>

	* uni20A6 (U+20A6): L<<188.0,198.0>--<62.0,197.0>>

	* uni20A6 (U+20A6): L<<188.0,241.0>--<189.0,471.0>>

	* uni20A6 (U+20A6): L<<189.0,513.0>--<188.0,700.0>>

	* uni20A6 (U+20A6): L<<62.0,242.0>--<188.0,241.0>>

	* uni20A6 (U+20A6): L<<62.0,514.0>--<189.0,513.0>>

	* uni20A6 (U+20A6): L<<675.0,198.0>--<676.0,0.0>>

	* uni20A8 (U+20A8): L<<76.0,701.0>--<349.0,699.0>>

	* uni20B1 (U+20B1): L<<77.0,701.0>--<327.0,699.0>>

	* uni20BD (U+20BD): L<<77.0,701.0>--<327.0,699.0>>

	* uni2126 (U+2126): L<<476.0,98.0>--<651.0,97.0>>

	* uni2126 (U+2126): L<<86.0,97.0>--<261.0,98.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uni2C63 (U+2C63): L<<77.0,701.0>--<327.0,699.0>>

	* uni2C64 (U+2C64): L<<76.0,701.0>--<350.0,699.0>>

	* uniA727 (U+A727): L<<457.0,10.0>--<459.0,272.0>>

	* uniA7B5 (U+A7B5): L<<115.0,15.0>--<116.0,-147.0>>

	* uniA7B5 (U+A7B5): L<<76.0,-147.0>--<80.0,395.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ i̦᷄ i̦᷅ i̦᷆ i̦᷇ i̧᷄ i̧᷅

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Zapotec (Latn, 490,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Cicipu (Latn, 44,000 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Yala (Latn, 200,000 speakers), Gulay (Latn, 250,478 speakers), Koonzime (Latn, 40,000 speakers), Ekpeye (Latn, 226,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ejagham (Latn, 120,000 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Bete-Bendi (Latn, 100,000 speakers), South Central Banda (Latn, 244,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Basaa (Latn, 332,940 speakers), Dii (Latn, 71,000 speakers), Bafut (Latn, 158,146 speakers), Lugbara (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Mango (Latn, 77,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Sar (Latn, 500,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 49 | 79 | 849 | 43 | 657 |
| 0% | 0% | 3% | 5% | 51% | 3% | 39% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
