## FontBakery report

fontbakery version: 0.10.8

<details><summary><b>[17] Ojuju-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 276, but got 270 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, old-permic, syriac, coptic, math, tai-le
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
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, caucasian-albanian, cherokee, tifinagh, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, elbasan, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: emoji, math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, math, symbols
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
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, lao, tamil, tifinagh, syriac, math, new-tai-lue, thai, ahom, manichaean, gunjala-gondi, cham, kaithi, caucasian-albanian, balinese, tai-le, phags-pa, oriya, mongolian, music, soyombo, takri, psalter-pahlavi, duployan, kannada, mandaic, tagalog, tagbanwa, gurmukhi, pahawh-hmong, rejang, sinhala, hanifi-rohingya, siddham, nko, malayalam, devanagari, tai-viet, sundanese, sogdian, thaana, bengali, telugu, gujarati, lepcha, masaram-gondi, buginese, meetei-mayek, hebrew, chakma, batak, dogra, javanese, miao, yi, tirhuta, bhaiksuki, old-permic, zanabazar-square, kayah-li, khudawadi, buhid, bassa-vah, hanunoo, osage, symbols, khmer, myanmar, adlam, wancho, mende-kikakui, tibetan, limbu, grantha, syloti-nagri, mahajani, sharada, khojki, newa, elbasan, marchen, coptic, brahmi, modi
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- longstrokecomb

	- shortslashcomb
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 403 among a set of 8 math glyphs.
The following math glyphs have a different width, though:

Width = 438:
plus

Width = 404:
plusminus

Width = 437:
multiply

Width = 509:
divide

Width = 354:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniA78C (U+A78C): L<<156.0,491.0>--<150.0,560.0>> -> L<<150.0,560.0>--<150.0,700.0>>

	* uniA78C (U+A78C): L<<179.0,700.0>--<179.0,560.0>> -> L<<179.0,560.0>--<173.0,491.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni026C (U+026C): B<<124.0,431.5>-<138.0,422.0>-<143.0,402.0>>/B<<143.0,402.0>-<143.0,506.0>-<142.5,565.0>> = 14.036243467926484

	* uniA7AD (U+A7AD): B<<80.0,446.5>-<94.0,437.0>-<99.0,417.0>>/B<<99.0,417.0>-<99.0,439.0>-<98.5,461.5>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* summation (U+2211): L<<55.0,700.0>--<626.0,698.0>>

	* summation (U+2211): L<<626.0,-131.0>--<55.0,-133.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊ i̦̋ i̦̍ i̦̐

Your font fully covers the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Cicipu (Latn, 44,000 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] Ojuju-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 276, but got 270 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, old-permic, syriac, coptic, math, tai-le
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
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, caucasian-albanian, cherokee, tifinagh, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, elbasan, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: emoji, math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, math, symbols
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
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, lao, tamil, tifinagh, syriac, math, new-tai-lue, thai, ahom, manichaean, gunjala-gondi, cham, kaithi, caucasian-albanian, balinese, tai-le, phags-pa, oriya, mongolian, music, soyombo, takri, psalter-pahlavi, duployan, kannada, mandaic, tagalog, tagbanwa, gurmukhi, pahawh-hmong, rejang, sinhala, hanifi-rohingya, siddham, nko, malayalam, devanagari, tai-viet, sundanese, sogdian, thaana, bengali, telugu, gujarati, lepcha, masaram-gondi, buginese, meetei-mayek, hebrew, chakma, batak, dogra, javanese, miao, yi, tirhuta, bhaiksuki, old-permic, zanabazar-square, kayah-li, khudawadi, buhid, bassa-vah, hanunoo, osage, symbols, khmer, myanmar, adlam, wancho, mende-kikakui, tibetan, limbu, grantha, syloti-nagri, mahajani, sharada, khojki, newa, elbasan, marchen, coptic, brahmi, modi
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- longstrokecomb

	- shortslashcomb
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4 or 7

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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

	- Glyph name: uni20A9	Contours detected: 5	Expected: 1, 3, 4 or 7

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 464 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 463:
plus

Width = 465:
greaterequal, less, greater, lessequal

Width = 458:
multiply

Width = 474:
divide

Width = 581:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniA78C (U+A78C): L<<133.0,392.0>--<124.0,527.0>> -> L<<124.0,527.0>--<120.0,716.0>>

	* uniA78C (U+A78C): L<<203.0,716.0>--<199.0,527.0>> -> L<<199.0,527.0>--<190.0,392.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* dong (U+20AB): L<<507.0,740.0>--<506.0,610.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊ i̦̋ i̦̍ i̦̐

Your font fully covers the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Cicipu (Latn, 44,000 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] Ojuju-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 276, but got 270 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, old-permic, syriac, coptic, math, tai-le
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
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, caucasian-albanian, cherokee, tifinagh, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, elbasan, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: emoji, math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, math, symbols
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
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, lao, tamil, tifinagh, syriac, math, new-tai-lue, thai, ahom, manichaean, gunjala-gondi, cham, kaithi, caucasian-albanian, balinese, tai-le, phags-pa, oriya, mongolian, music, soyombo, takri, psalter-pahlavi, duployan, kannada, mandaic, tagalog, tagbanwa, gurmukhi, pahawh-hmong, rejang, sinhala, hanifi-rohingya, siddham, nko, malayalam, devanagari, tai-viet, sundanese, sogdian, thaana, bengali, telugu, gujarati, lepcha, masaram-gondi, buginese, meetei-mayek, hebrew, chakma, batak, dogra, javanese, miao, yi, tirhuta, bhaiksuki, old-permic, zanabazar-square, kayah-li, khudawadi, buhid, bassa-vah, hanunoo, osage, symbols, khmer, myanmar, adlam, wancho, mende-kikakui, tibetan, limbu, grantha, syloti-nagri, mahajani, sharada, khojki, newa, elbasan, marchen, coptic, brahmi, modi
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- longstrokecomb

	- shortslashcomb
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: A	Contours detected: 1	Expected: 2

	- Glyph name: Agrave	Contours detected: 2	Expected: 3

	- Glyph name: Aacute	Contours detected: 2	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Adieresis	Contours detected: 3	Expected: 4

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Amacron	Contours detected: 2	Expected: 3

	- Glyph name: Abreve	Contours detected: 2	Expected: 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01CD	Contours detected: 2	Expected: 3

	- Glyph name: uni01DE	Contours detected: 4	Expected: 5

	- Glyph name: uni01E0	Contours detected: 3	Expected: 4

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0200	Contours detected: 3	Expected: 4

	- Glyph name: uni0202	Contours detected: 2	Expected: 3

	- Glyph name: uni0226	Contours detected: 2	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E00	Contours detected: 3	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 2	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 3	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 3	Expected: 4

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

	- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: A	Contours detected: 1	Expected: 2

	- Glyph name: Aacute	Contours detected: 2	Expected: 3

	- Glyph name: Abreve	Contours detected: 2	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 2	Expected: 3

	- Glyph name: Adieresis	Contours detected: 3	Expected: 4

	- Glyph name: Agrave	Contours detected: 2	Expected: 3

	- Glyph name: Amacron	Contours detected: 2	Expected: 3

	- Glyph name: Atilde	Contours detected: 2	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01CD	Contours detected: 2	Expected: 3

	- Glyph name: uni01DE	Contours detected: 4	Expected: 5

	- Glyph name: uni01E0	Contours detected: 3	Expected: 4

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0226	Contours detected: 2	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 2	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E00	Contours detected: 3	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA0	Contours detected: 2	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 2	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 3	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 3	Expected: 4

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

	- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

	- Glyph name: uni20BD	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 444 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 455:
plus

Width = 445:
greaterequal, less, greater, lessequal

Width = 451:
multiply

Width = 486:
divide

Width = 506:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni2C66 (U+2C66): L<<113.0,191.0>--<113.0,193.0>> -> L<<113.0,193.0>--<113.0,343.0>>

	* uniA78C (U+A78C): L<<141.0,425.0>--<133.0,538.0>> -> L<<133.0,538.0>--<130.0,711.0>>

	* uniA78C (U+A78C): L<<195.0,711.0>--<192.0,538.0>> -> L<<192.0,538.0>--<184.0,425.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* partialdiff (U+2202): L<<107.0,581.0>--<108.0,746.0>>

	* summation (U+2211): L<<46.0,700.0>--<629.0,699.0>>

	* summation (U+2211): L<<629.0,-133.0>--<46.0,-134.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊ i̦̋ i̦̍ i̦̐

Your font fully covers the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Cicipu (Latn, 44,000 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] Ojuju-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 276, but got 270 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, old-permic, syriac, coptic, math, tai-le
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
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, caucasian-albanian, cherokee, tifinagh, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, elbasan, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: emoji, math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, math, symbols
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
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, lao, tamil, tifinagh, syriac, math, new-tai-lue, thai, ahom, manichaean, gunjala-gondi, cham, kaithi, caucasian-albanian, balinese, tai-le, phags-pa, oriya, mongolian, music, soyombo, takri, psalter-pahlavi, duployan, kannada, mandaic, tagalog, tagbanwa, gurmukhi, pahawh-hmong, rejang, sinhala, hanifi-rohingya, siddham, nko, malayalam, devanagari, tai-viet, sundanese, sogdian, thaana, bengali, telugu, gujarati, lepcha, masaram-gondi, buginese, meetei-mayek, hebrew, chakma, batak, dogra, javanese, miao, yi, tirhuta, bhaiksuki, old-permic, zanabazar-square, kayah-li, khudawadi, buhid, bassa-vah, hanunoo, osage, symbols, khmer, myanmar, adlam, wancho, mende-kikakui, tibetan, limbu, grantha, syloti-nagri, mahajani, sharada, khojki, newa, elbasan, marchen, coptic, brahmi, modi
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- longstrokecomb

	- shortslashcomb
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 412 among a set of 8 math glyphs.
The following math glyphs have a different width, though:

Width = 442:
plus

Width = 413:
plusminus

Width = 440:
multiply

Width = 504:
divide

Width = 386:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniA78C (U+A78C): L<<153.0,477.0>--<146.0,555.0>> -> L<<146.0,555.0>--<146.0,702.0>>

	* uniA78C (U+A78C): L<<182.0,702.0>--<182.0,555.0>> -> L<<182.0,555.0>--<175.0,477.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* summation (U+2211): L<<53.0,700.0>--<627.0,698.0>>

	* summation (U+2211): L<<627.0,-131.0>--<53.0,-133.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊ i̦̋ i̦̍ i̦̐

Your font fully covers the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Cicipu (Latn, 44,000 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[17] Ojuju-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 276, but got 270 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, old-permic, syriac, coptic, math, tai-le
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
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, caucasian-albanian, cherokee, tifinagh, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, elbasan, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: emoji, math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, math, symbols
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
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, lao, tamil, tifinagh, syriac, math, new-tai-lue, thai, ahom, manichaean, gunjala-gondi, cham, kaithi, caucasian-albanian, balinese, tai-le, phags-pa, oriya, mongolian, music, soyombo, takri, psalter-pahlavi, duployan, kannada, mandaic, tagalog, tagbanwa, gurmukhi, pahawh-hmong, rejang, sinhala, hanifi-rohingya, siddham, nko, malayalam, devanagari, tai-viet, sundanese, sogdian, thaana, bengali, telugu, gujarati, lepcha, masaram-gondi, buginese, meetei-mayek, hebrew, chakma, batak, dogra, javanese, miao, yi, tirhuta, bhaiksuki, old-permic, zanabazar-square, kayah-li, khudawadi, buhid, bassa-vah, hanunoo, osage, symbols, khmer, myanmar, adlam, wancho, mende-kikakui, tibetan, limbu, grantha, syloti-nagri, mahajani, sharada, khojki, newa, elbasan, marchen, coptic, brahmi, modi
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- longstrokecomb

	- shortslashcomb
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: A	Contours detected: 4	Expected: 2

	- Glyph name: Agrave	Contours detected: 5	Expected: 3

	- Glyph name: Aacute	Contours detected: 5	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 5	Expected: 3

	- Glyph name: Atilde	Contours detected: 5	Expected: 3

	- Glyph name: Adieresis	Contours detected: 6	Expected: 4

	- Glyph name: Aring	Contours detected: 6	Expected: 3 or 4

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Amacron	Contours detected: 5	Expected: 3

	- Glyph name: Abreve	Contours detected: 5	Expected: 3

	- Glyph name: Aogonek	Contours detected: 5	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01CD	Contours detected: 5	Expected: 3

	- Glyph name: uni01DE	Contours detected: 7	Expected: 5

	- Glyph name: uni01E0	Contours detected: 6	Expected: 4

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0200	Contours detected: 6	Expected: 4

	- Glyph name: uni0202	Contours detected: 5	Expected: 3

	- Glyph name: uni0226	Contours detected: 5	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 5	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E00	Contours detected: 6	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA0	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 6	Expected: 4

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

	- Glyph name: A	Contours detected: 4	Expected: 2

	- Glyph name: Aacute	Contours detected: 5	Expected: 3

	- Glyph name: Abreve	Contours detected: 5	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 5	Expected: 3

	- Glyph name: Adieresis	Contours detected: 6	Expected: 4

	- Glyph name: Agrave	Contours detected: 5	Expected: 3

	- Glyph name: Amacron	Contours detected: 5	Expected: 3

	- Glyph name: Aogonek	Contours detected: 5	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 6	Expected: 3 or 4

	- Glyph name: Atilde	Contours detected: 5	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01CD	Contours detected: 5	Expected: 3

	- Glyph name: uni01DE	Contours detected: 7	Expected: 5

	- Glyph name: uni01E0	Contours detected: 6	Expected: 4

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0226	Contours detected: 5	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 5	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E00	Contours detected: 6	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA0	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 5	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 6	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 6	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 6	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 6	Expected: 4

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 430 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 449:
plus

Width = 429:
equal, notequal, logicalnot, minus

Width = 446:
multiply

Width = 494:
divide

Width = 452:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni2C66 (U+2C66): L<<112.0,186.0>--<112.0,192.0>> -> L<<112.0,192.0>--<112.0,380.0>>

	* uniA78C (U+A78C): L<<146.0,448.0>--<139.0,546.0>> -> L<<139.0,546.0>--<137.0,707.0>>

	* uniA78C (U+A78C): L<<189.0,707.0>--<188.0,546.0>> -> L<<188.0,546.0>--<180.0,448.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* A (U+0041): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Aacute (U+00C1): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Abreve (U+0102): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Acircumflex (U+00C2): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Adieresis (U+00C4): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Agrave (U+00C0): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Amacron (U+0100): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Aogonek (U+0104): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Aring (U+00C5): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* Atilde (U+00C3): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni01CD (U+01CD): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni01DE (U+01DE): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni01E0 (U+01E0): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni0200 (U+0200): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni0202 (U+0202): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni0226 (U+0226): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni023A (U+023A): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1E00 (U+1E00): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EA0 (U+1EA0): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EA2 (U+1EA2): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EA4 (U+1EA4): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EA6 (U+1EA6): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EA8 (U+1EA8): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EAA (U+1EAA): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EAC (U+1EAC): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EAE (U+1EAE): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EB0 (U+1EB0): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EB2 (U+1EB2): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EB4 (U+1EB4): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929

	* uni1EB6 (U+1EB6): B<<308.5,488.0>-<307.0,507.0>-<306.0,517.0>>/B<<306.0,517.0>-<305.0,507.0>-<303.0,488.0>> = 11.42118627499929 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* AE (U+00C6): L<<841.0,700.0>--<840.0,572.0>>

	* E (U+0045): L<<523.0,700.0>--<522.0,572.0>>

	* Eacute (U+00C9): L<<523.0,700.0>--<522.0,572.0>>

	* Ecaron (U+011A): L<<523.0,700.0>--<522.0,572.0>>

	* Ecircumflex (U+00CA): L<<523.0,700.0>--<522.0,572.0>>

	* Edieresis (U+00CB): L<<523.0,700.0>--<522.0,572.0>>

	* Edotaccent (U+0116): L<<523.0,700.0>--<522.0,572.0>>

	* Egrave (U+00C8): L<<523.0,700.0>--<522.0,572.0>>

	* Emacron (U+0112): L<<523.0,700.0>--<522.0,572.0>>

	* Eogonek (U+0118): L<<523.0,700.0>--<522.0,572.0>>

	* F (U+0046): L<<515.0,700.0>--<514.0,572.0>>

	* OE (U+0152): L<<936.0,700.0>--<935.0,572.0>>

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* summation (U+2211): L<<49.0,700.0>--<628.0,699.0>>

	* summation (U+2211): L<<628.0,-132.0>--<49.0,-133.0>>

	* uni0191 (U+0191): L<<535.0,700.0>--<534.0,572.0>>

	* uni01E2 (U+01E2): L<<841.0,700.0>--<840.0,572.0>>

	* uni0204 (U+0204): L<<523.0,700.0>--<522.0,572.0>>

	* uni0206 (U+0206): L<<523.0,700.0>--<522.0,572.0>>

	* uni0228 (U+0228): L<<523.0,700.0>--<522.0,572.0>>

	* uni0246 (U+0246): L<<523.0,700.0>--<522.0,572.0>>

	* uni1E14 (U+1E14): L<<523.0,700.0>--<522.0,572.0>>

	* uni1E16 (U+1E16): L<<523.0,700.0>--<522.0,572.0>>

	* uni1E18 (U+1E18): L<<523.0,700.0>--<522.0,572.0>>

	* uni1E1A (U+1E1A): L<<523.0,700.0>--<522.0,572.0>>

	* uni1E1C (U+1E1C): L<<523.0,700.0>--<522.0,572.0>>

	* uni1E1E (U+1E1E): L<<515.0,700.0>--<514.0,572.0>>

	* uni1EB8 (U+1EB8): L<<523.0,700.0>--<522.0,572.0>>

	* uni1EBA (U+1EBA): L<<523.0,700.0>--<522.0,572.0>>

	* uni1EBC (U+1EBC): L<<523.0,700.0>--<522.0,572.0>>

	* uni1EBE (U+1EBE): L<<523.0,700.0>--<522.0,572.0>>

	* uni1EC0 (U+1EC0): L<<523.0,700.0>--<522.0,572.0>>

	* uni1EC2 (U+1EC2): L<<523.0,700.0>--<522.0,572.0>>

	* uni1EC4 (U+1EC4): L<<523.0,700.0>--<522.0,572.0>>

	* uni1EC6 (U+1EC6): L<<523.0,700.0>--<522.0,572.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uniA78C (U+A78C): L<<189.0,707.0>--<188.0,546.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊ i̦̋ i̦̍ i̦̐

Your font fully covers the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Cicipu (Latn, 44,000 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[17] Ojuju-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 276, but got 270 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, old-permic, syriac, coptic, math, tai-le
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
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, caucasian-albanian, cherokee, tifinagh, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, elbasan, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: emoji, math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, math, symbols
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
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, lao, tamil, tifinagh, syriac, math, new-tai-lue, thai, ahom, manichaean, gunjala-gondi, cham, kaithi, caucasian-albanian, balinese, tai-le, phags-pa, oriya, mongolian, music, soyombo, takri, psalter-pahlavi, duployan, kannada, mandaic, tagalog, tagbanwa, gurmukhi, pahawh-hmong, rejang, sinhala, hanifi-rohingya, siddham, nko, malayalam, devanagari, tai-viet, sundanese, sogdian, thaana, bengali, telugu, gujarati, lepcha, masaram-gondi, buginese, meetei-mayek, hebrew, chakma, batak, dogra, javanese, miao, yi, tirhuta, bhaiksuki, old-permic, zanabazar-square, kayah-li, khudawadi, buhid, bassa-vah, hanunoo, osage, symbols, khmer, myanmar, adlam, wancho, mende-kikakui, tibetan, limbu, grantha, syloti-nagri, mahajani, sharada, khojki, newa, elbasan, marchen, coptic, brahmi, modi
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- longstrokecomb

	- shortslashcomb
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 407 among a set of 5 math glyphs.
The following math glyphs have a different width, though:

Width = 439:
plus

Width = 406:
equal, notequal, logicalnot, minus

Width = 438:
multiply

Width = 507:
divide

Width = 367:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uniA78C (U+A78C): L<<155.0,485.0>--<149.0,558.0>> -> L<<149.0,558.0>--<148.0,701.0>>

	* uniA78C (U+A78C): L<<180.0,701.0>--<180.0,558.0>> -> L<<180.0,558.0>--<174.0,485.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni20A9 (U+20A9): B<<810.0,354.0>-<772.0,354.0>-<733.0,355.0>>/L<<733.0,355.0>--<733.0,355.0>> = 1.4688007143857 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* summation (U+2211): L<<54.0,700.0>--<626.0,698.0>>

	* summation (U+2211): L<<626.0,-131.0>--<54.0,-133.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uniA78C (U+A78C): L<<149.0,558.0>--<148.0,701.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊ i̦̋ i̦̍ i̦̐

Your font fully covers the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Cicipu (Latn, 44,000 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] Ojuju-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://openfontlicense.org" Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 276, but got 270 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.10.8, while a newer 0.10.9 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, canadian-aboriginal, tifinagh, old-permic, syriac, coptic, math, tai-le
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
 * U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac
 * U+0331 COMBINING MACRON BELOW: try adding one of: gothic, caucasian-albanian, cherokee, tifinagh, syriac
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: math, elbasan, greek
 * U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
 * U+03C0 GREEK SMALL LETTER PI: try adding one of: math, greek, yi
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
 * U+2126 OHM SIGN: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+2144 TURNED SANS-SERIF CAPITAL Y: not included in any glyphset definition
 * U+2153 VULGAR FRACTION ONE THIRD: not included in any glyphset definition
 * U+2154 VULGAR FRACTION TWO THIRDS: not included in any glyphset definition
 * U+2190 LEFTWARDS ARROW: try adding one of: math, symbols
 * U+2192 RIGHTWARDS ARROW: try adding one of: math, symbols
 * U+2194 LEFT RIGHT ARROW: try adding one of: emoji, math, symbols
 * U+2195 UP DOWN ARROW: try adding one of: emoji, math, symbols
 * U+2196 NORTH WEST ARROW: try adding one of: emoji, math, symbols
 * U+2197 NORTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2198 SOUTH EAST ARROW: try adding one of: emoji, math, symbols
 * U+2199 SOUTH WEST ARROW: try adding one of: emoji, math, symbols
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
 * U+25B3 WHITE UP-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B4 BLACK UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B5 WHITE UP-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B6 BLACK RIGHT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25B7 WHITE RIGHT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25B8 BLACK RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25B9 WHITE RIGHT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols
 * U+25BD WHITE DOWN-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25BE BLACK DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25BF WHITE DOWN-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C0 BLACK LEFT-POINTING TRIANGLE: try adding one of: emoji, symbols
 * U+25C1 WHITE LEFT-POINTING TRIANGLE: try adding one of: math, symbols
 * U+25C2 BLACK LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C3 WHITE LEFT-POINTING SMALL TRIANGLE: try adding symbols
 * U+25C6 BLACK DIAMOND: try adding symbols
 * U+25C7 WHITE DIAMOND: try adding symbols
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CB WHITE CIRCLE: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: kharoshthi, lao, tamil, tifinagh, syriac, math, new-tai-lue, thai, ahom, manichaean, gunjala-gondi, cham, kaithi, caucasian-albanian, balinese, tai-le, phags-pa, oriya, mongolian, music, soyombo, takri, psalter-pahlavi, duployan, kannada, mandaic, tagalog, tagbanwa, gurmukhi, pahawh-hmong, rejang, sinhala, hanifi-rohingya, siddham, nko, malayalam, devanagari, tai-viet, sundanese, sogdian, thaana, bengali, telugu, gujarati, lepcha, masaram-gondi, buginese, meetei-mayek, hebrew, chakma, batak, dogra, javanese, miao, yi, tirhuta, bhaiksuki, old-permic, zanabazar-square, kayah-li, khudawadi, buhid, bassa-vah, hanunoo, osage, symbols, khmer, myanmar, adlam, wancho, mende-kikakui, tibetan, limbu, grantha, syloti-nagri, mahajani, sharada, khojki, newa, elbasan, marchen, coptic, brahmi, modi
 * U+25CF BLACK CIRCLE: try adding symbols
 * U+25E6 WHITE BULLET: try adding symbols
 * U+27E8 MATHEMATICAL LEFT ANGLE BRACKET: try adding math
 * U+27E9 MATHEMATICAL RIGHT ANGLE BRACKET: try adding math
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition
 * U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition
 * U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- dotlessi_ogonek

	- longstrokecomb

	- shortslashcomb
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: Dtail	Contours detected: 3	Expected: 2

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01CD	Contours detected: 4	Expected: 3

	- Glyph name: uni01DE	Contours detected: 6	Expected: 5

	- Glyph name: uni01E0	Contours detected: 5	Expected: 4

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0200	Contours detected: 5	Expected: 4

	- Glyph name: uni0202	Contours detected: 4	Expected: 3

	- Glyph name: uni0226	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E00	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 5	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 5	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 5	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 5	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 5	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 5	Expected: 4

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

	- Glyph name: A	Contours detected: 3	Expected: 2

	- Glyph name: Aacute	Contours detected: 4	Expected: 3

	- Glyph name: Abreve	Contours detected: 4	Expected: 3

	- Glyph name: Acircumflex	Contours detected: 4	Expected: 3

	- Glyph name: Adieresis	Contours detected: 5	Expected: 4

	- Glyph name: Agrave	Contours detected: 4	Expected: 3

	- Glyph name: Amacron	Contours detected: 4	Expected: 3

	- Glyph name: Aogonek	Contours detected: 4	Expected: 2 or 3

	- Glyph name: Aring	Contours detected: 5	Expected: 3 or 4

	- Glyph name: Atilde	Contours detected: 4	Expected: 3

	- Glyph name: Dcroat	Contours detected: 3	Expected: 2

	- Glyph name: Eth	Contours detected: 3	Expected: 2

	- Glyph name: Tbar	Contours detected: 2	Expected: 1

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: fi	Contours detected: 2	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: tbar	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: uni0181	Contours detected: 4	Expected: 3

	- Glyph name: uni0187	Contours detected: 2	Expected: 1

	- Glyph name: uni018A	Contours detected: 3	Expected: 2

	- Glyph name: uni0193	Contours detected: 2	Expected: 1

	- Glyph name: uni0197	Contours detected: 2	Expected: 1

	- Glyph name: uni0198	Contours detected: 2	Expected: 1

	- Glyph name: uni019A	Contours detected: 2	Expected: 1

	- Glyph name: uni01A4	Contours detected: 3	Expected: 2

	- Glyph name: uni01B3	Contours detected: 2	Expected: 1

	- Glyph name: uni01B4	Contours detected: 2	Expected: 1

	- Glyph name: uni01B6	Contours detected: 2	Expected: 1

	- Glyph name: uni01CD	Contours detected: 4	Expected: 3

	- Glyph name: uni01DE	Contours detected: 6	Expected: 5

	- Glyph name: uni01E0	Contours detected: 5	Expected: 4

	- Glyph name: uni01E4	Contours detected: 2	Expected: 1

	- Glyph name: uni0226	Contours detected: 4	Expected: 3

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni023A	Contours detected: 4	Expected: 3

	- Glyph name: uni0246	Contours detected: 2	Expected: 3

	- Glyph name: uni0247	Contours detected: 3	Expected: 4

	- Glyph name: uni0248	Contours detected: 2	Expected: 1

	- Glyph name: uni0249	Contours detected: 3	Expected: 2

	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3 or 5

	- Glyph name: uni1E00	Contours detected: 5	Expected: 4

	- Glyph name: uni1E08	Contours detected: 3	Expected: 2

	- Glyph name: uni1E09	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA0	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA2	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 5	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 5	Expected: 4

	- Glyph name: uni1EA8	Contours detected: 5	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 5	Expected: 4

	- Glyph name: uni1EAC	Contours detected: 5	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB2	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 5	Expected: 4

	- Glyph name: uni1EB6	Contours detected: 5	Expected: 4

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
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 419 among a set of 8 math glyphs.
The following math glyphs have a different width, though:

Width = 445:
plus

Width = 420:
plusminus

Width = 443:
multiply

Width = 500:
divide

Width = 414:
approxequal
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni2C66 (U+2C66): L<<112.0,182.0>--<112.0,191.0>> -> L<<112.0,191.0>--<112.0,406.0>>

	* uniA78C (U+A78C): L<<150.0,465.0>--<143.0,551.0>> -> L<<143.0,551.0>--<142.0,704.0>>

	* uniA78C (U+A78C): L<<185.0,704.0>--<184.0,551.0>> -> L<<184.0,551.0>--<178.0,465.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* filledbox (U+25A0): L<<32.0,65.0>--<30.0,619.0>>

	* filledbox (U+25A0): L<<582.0,619.0>--<584.0,65.0>>

	* summation (U+2211): L<<52.0,700.0>--<627.0,699.0>>

	* summation (U+2211): L<<627.0,-132.0>--<52.0,-133.0>>

	* uni25A1 (U+25A1): L<<32.0,65.0>--<30.0,619.0>>

	* uni25A1 (U+25A1): L<<523.0,126.0>--<522.0,558.0>>

	* uni25A1 (U+25A1): L<<582.0,619.0>--<584.0,65.0>>

	* uni25A1 (U+25A1): L<<91.0,558.0>--<92.0,126.0>>

	* uni25AA (U+25AA): L<<31.0,65.0>--<30.0,366.0>>

	* uni25AA (U+25AA): L<<330.0,366.0>--<331.0,65.0>>

	* uni25AB (U+25AB): L<<31.0,65.0>--<30.0,388.0>>

	* uni25AB (U+25AB): L<<352.0,388.0>--<353.0,65.0>>

	* uniA78C (U+A78C): L<<143.0,551.0>--<142.0,704.0>>

	* uniA78C (U+A78C): L<<185.0,704.0>--<184.0,551.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: i᷆ i᷇ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄

The dot of soft dotted characters _should_ disappear in other cases, for example: i᷄ i᷅ i̛᷄ i̛᷅ i̛᷆ i̛᷇ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥᷄ i̥᷅ i̥᷆ i̥᷇ ĭ̦ i̦̇ i̦̊ i̦̋ i̦̍ i̦̐

Your font fully covers the following languages that require the soft-dotted feature: Zapotec (Latn, 490,000 speakers), Dutch (Latn, 31,709,104 speakers), Southern Kisi (Latn, 360,000 speakers), Lithuanian (Latn, 2,357,094 speakers), Cicipu (Latn, 44,000 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: South Central Banda (Latn, 244,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bafut (Latn, 158,146 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Dan (Latn, 1,099,244 speakers), Basaa (Latn, 332,940 speakers), Aghem (Latn, 38,843 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Avokaya (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Koonzime (Latn, 40,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Gulay (Latn, 250,478 speakers), Dii (Latn, 71,000 speakers), Mundani (Latn, 34,000 speakers), Ma’di (Latn, 584,000 speakers), Ekpeye (Latn, 226,000 speakers), Sar (Latn, 500,000 speakers), Nateni (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 28 | 87 | 849 | 43 | 670 |
| 0% | 0% | 2% | 5% | 51% | 3% | 40% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
