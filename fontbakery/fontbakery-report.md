## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[21] Ojuju-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 271, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: zero	Expected: 2 or 3

	- Glyph name: one	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: three	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: five	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: agrave	Expected: 3

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: atilde	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: egrave	Expected: 3

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: ograve	Expected: 3

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: endash	Expected: 1

	- Glyph name: emdash	Expected: 1

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: bullet	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: minus	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: agrave	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: atilde	Expected: 3

	- Glyph name: backslash	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: egrave	Expected: 3

	- Glyph name: eight	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: emdash	Expected: 1

	- Glyph name: endash	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: five	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: one	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: percent	Expected: 5

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: plus	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: three	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: underscore	Expected: 1

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: zero	Expected: 2 or 3
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- E.a

	- K.ss10

	- R.alt

	- a.001

	- i.loclTRK

	- l.001

	- m.alt

	- n.alt

	- n.ss01

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=81.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=273.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=89.0,Y=0.5 (should be at baseline 0?)

	* exclam (U+0021): X=264.0,Y=0.5 (should be at baseline 0?)

	* period (U+002E): X=86.5,Y=0.5 (should be at baseline 0?)

	* period (U+002E): X=261.5,Y=0.5 (should be at baseline 0?)

	* B (U+0042): X=72.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=391.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=480.0,Y=698.5 (should be at cap-height 700?)

	* F (U+0046): X=71.0,Y=701.0 (should be at cap-height 700?)

	* F (U+0046): X=553.0,Y=699.0 (should be at cap-height 700?)

	* G (U+0047): X=463.5,Y=702.0 (should be at cap-height 700?)

	* G (U+0047): X=457.5,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=47.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=402.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=71.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=152.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=74.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=400.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=479.5,Y=-259.0 (should be at descender -260?)

	* R (U+0052): X=74.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=398.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=29.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=602.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=378.5,Y=493.5 (should be at x-height 493?)

	* b (U+0062): X=66.5,Y=491.0 (should be at x-height 493?)

	* d (U+0064): X=562.0,Y=491.0 (should be at x-height 493?)

	* f (U+0066): X=378.0,Y=742.0 (should be at ascender 740?)

	* g (U+0067): X=378.5,Y=493.5 (should be at x-height 493?)

	* h (U+0068): X=248.0,Y=493.5 (should be at x-height 493?)

	* m (U+006D): X=234.5,Y=492.5 (should be at x-height 493?)

	* n (U+006E): X=248.0,Y=493.5 (should be at x-height 493?)

	* r (U+0072): X=243.5,Y=494.0 (should be at x-height 493?)

	* s (U+0073): X=440.0,Y=495.0 (should be at x-height 493?)

	* x (U+0078): X=37.0,Y=495.0 (should be at x-height 493?)

	* x (U+0078): X=101.0,Y=495.0 (should be at x-height 493?)

	* x (U+0078): X=359.0,Y=495.0 (should be at x-height 493?)

	* x (U+0078): X=491.0,Y=495.0 (should be at x-height 493?)

	* y (U+0079): X=340.0,Y=-2.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=480.0,Y=698.5 (should be at cap-height 700?)

	* uni1EF9 (U+1EF9): X=340.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=86.5,Y=0.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=261.5,Y=0.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=86.5,Y=0.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=261.5,Y=0.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=86.5,Y=0.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=261.5,Y=0.5 (should be at baseline 0?)

	* trademark (U+2122): X=29.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=602.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<156.0,380.0>-<164.0,373.0>-<176.5,369.5>>

	* K (U+004B) contains a short segment B<<230.0,272.0>-<225.0,281.0>-<218.0,285.0>>

	* K (U+004B) contains a short segment B<<161.0,286.0>-<150.0,283.0>-<146.0,273.0>>

	* M (U+004D) contains a short segment B<<376.5,321.0>-<383.0,302.0>-<391.0,297.5>>

	* M (U+004D) contains a short segment B<<391.0,297.5>-<399.0,293.0>-<411.0,293.0>>

	* M (U+004D) contains a short segment B<<411.0,293.0>-<422.0,293.0>-<430.0,297.5>>

	* M (U+004D) contains a short segment B<<430.0,297.5>-<438.0,302.0>-<444.5,321.0>>

	* M (U+004D) contains a short segment B<<672.0,420.0>-<665.0,432.0>-<652.0,435.5>>

	* M (U+004D) contains a short segment B<<562.0,434.0>-<547.0,429.0>-<538.0,418.0>>

	* M (U+004D) contains a short segment B<<283.0,418.0>-<275.0,429.0>-<259.5,434.0>>

	* M (U+004D) contains a short segment B<<169.5,436.0>-<156.0,433.0>-<150.0,420.0>>

	* W (U+0057) contains a short segment B<<162.0,280.0>-<168.0,268.0>-<181.0,264.5>>

	* W (U+0057) contains a short segment B<<251.5,266.0>-<263.0,271.0>-<271.0,282.0>>

	* W (U+0057) contains a short segment B<<530.0,282.0>-<538.0,271.0>-<549.5,266.0>>

	* W (U+0057) contains a short segment B<<620.0,264.5>-<633.0,268.0>-<639.0,280.0>>

	* W (U+0057) contains a short segment B<<433.0,379.0>-<427.0,398.0>-<419.0,402.5>>

	* W (U+0057) contains a short segment B<<419.0,402.5>-<411.0,407.0>-<399.0,407.0>>

	* W (U+0057) contains a short segment B<<399.0,407.0>-<387.0,407.0>-<379.0,402.5>>

	* W (U+0057) contains a short segment B<<379.0,402.5>-<371.0,398.0>-<364.5,379.0>>

	* X (U+0058) contains a short segment B<<179.0,361.0>-<179.0,370.0>-<176.5,380.0>>

	* X (U+0058) contains a short segment B<<497.0,380.0>-<495.0,370.0>-<495.0,361.0>>

	* Z (U+005A) contains a short segment B<<214.0,193.0>-<206.0,180.0>-<211.0,175.5>>

	* Z (U+005A) contains a short segment B<<236.0,161.0>-<242.0,154.0>-<253.0,151.0>>

	* f (U+0066) contains a short segment B<<110.0,493.0>-<115.0,493.0>-<119.5,496.5>>

	* f (U+0066) contains a short segment B<<178.0,510.0>-<174.0,499.0>-<178.0,496.0>>

	* f (U+0066) contains a short segment B<<178.0,496.0>-<182.0,493.0>-<187.0,493.0>>

	* h (U+0068) contains a short segment B<<135.5,413.0>-<138.0,404.0>-<143.0,404.0>>

	* m (U+006D) contains a short segment B<<481.5,413.5>-<488.0,403.0>-<497.0,403.0>>

	* m (U+006D) contains a short segment B<<497.0,403.0>-<507.0,403.0>-<515.0,413.5>>

	* n (U+006E) contains a short segment B<<134.0,409.0>-<137.0,404.0>-<143.0,404.0>>

	* p (U+0070) contains a short segment B<<131.0,411.0>-<133.0,404.0>-<140.0,404.0>>

	* t (U+0074) contains a short segment B<<112.0,327.5>-<108.0,331.0>-<102.0,331.0>>

	* t (U+0074) contains a short segment B<<179.0,331.0>-<174.0,331.0>-<170.0,328.5>>

	* w (U+0077) contains a short segment B<<383.0,306.5>-<376.0,315.0>-<364.0,315.0>>

	* w (U+0077) contains a short segment B<<364.0,315.0>-<353.0,315.0>-<346.0,306.0>>

	* y (U+0079) contains a short segment B<<347.0,-9.0>-<347.0,-4.0>-<340.0,-2.0>>

	* z (U+007A) contains a short segment B<<166.0,116.0>-<166.0,110.0>-<176.0,107.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<156.0,380.0>-<164.0,373.0>-<176.5,369.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<156.0,380.0>-<164.0,373.0>-<176.5,369.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<156.0,380.0>-<164.0,373.0>-<176.5,369.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<347.0,-9.0>-<347.0,-4.0>-<340.0,-2.0>>

	* trademark (U+2122) contains a short segment B<<1028.5,321.0>-<1035.0,302.0>-<1043.0,297.5>>

	* trademark (U+2122) contains a short segment B<<1043.0,297.5>-<1051.0,293.0>-<1063.0,293.0>>

	* trademark (U+2122) contains a short segment B<<1063.0,293.0>-<1074.0,293.0>-<1082.0,297.5>>

	* trademark (U+2122) contains a short segment B<<1082.0,297.5>-<1090.0,302.0>-<1096.5,321.0>>

	* trademark (U+2122) contains a short segment B<<1324.0,420.0>-<1317.0,432.0>-<1304.0,435.5>>

	* trademark (U+2122) contains a short segment B<<1214.0,434.0>-<1199.0,429.0>-<1190.0,418.0>>

	* trademark (U+2122) contains a short segment B<<935.0,418.0>-<927.0,429.0>-<911.5,434.0>>

	* trademark (U+2122) contains a short segment B<<821.5,436.0>-<808.0,433.0>-<802.0,420.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<553.0,699.0>--<552.0,514.0>>

	* F (U+0046): L<<71.0,701.0>--<553.0,699.0>>

	* G (U+0047): L<<526.0,681.0>--<525.0,430.0>>

	* P (U+0050): L<<74.0,701.0>--<400.0,699.0>>

	* P (U+0050): L<<77.0,350.0>--<74.0,701.0>>

	* R (U+0052): L<<74.0,701.0>--<398.0,699.0>>

	* R (U+0052): L<<77.0,350.0>--<74.0,701.0>>

	* S (U+0053): L<<55.0,10.0>--<54.0,176.0>>

	* U (U+0055): L<<48.0,307.0>--<47.0,700.0>>

	* U (U+0055): L<<567.0,700.0>--<565.0,302.0>>

	* Z (U+005A): L<<569.0,700.0>--<567.0,410.0>>

	* i (U+0069): L<<57.0,323.0>--<56.0,493.0>>

	* t (U+0074): L<<356.0,160.0>--<355.0,15.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[20] Ojuju-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 271, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: zero	Expected: 2 or 3

	- Glyph name: one	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: three	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: five	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: agrave	Expected: 3

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: atilde	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: egrave	Expected: 3

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: ograve	Expected: 3

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: endash	Expected: 1

	- Glyph name: emdash	Expected: 1

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: bullet	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: minus	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: agrave	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: atilde	Expected: 3

	- Glyph name: backslash	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: egrave	Expected: 3

	- Glyph name: eight	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: emdash	Expected: 1

	- Glyph name: endash	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: five	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: one	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: percent	Expected: 5

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: plus	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: three	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: underscore	Expected: 1

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: zero	Expected: 2 or 3
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- E.a

	- K.ss10

	- R.alt

	- a.001

	- i.loclTRK

	- l.001

	- m.alt

	- n.alt

	- n.ss01

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* B (U+0042): X=165.0,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=217.5,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=270.0,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=344.0,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=313.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=218.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=90.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=416.5,Y=1.5 (should be at baseline 0?)

	* I (U+0049): X=57.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=336.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=233.0,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=90.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=120.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=93.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=373.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=548.0,Y=-261.0 (should be at descender -260?)

	* Q (U+0051): X=548.0,Y=-261.0 (should be at descender -260?)

	* R (U+0052): X=93.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=369.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=579.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=359.0,Y=480.5 (should be at x-height 480?)

	* a (U+0061): X=359.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=234.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=234.0,Y=480.5 (should be at x-height 480?)

	* d (U+0064): X=359.0,Y=480.5 (should be at x-height 480?)

	* d (U+0064): X=359.0,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=261.0,Y=741.0 (should be at ascender 740?)

	* g (U+0067): X=359.0,Y=480.5 (should be at x-height 480?)

	* g (U+0067): X=359.5,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=235.5,Y=480.5 (should be at x-height 480?)

	* l (U+006C): X=184.0,Y=-0.5 (should be at baseline 0?)

	* m (U+006D): X=216.5,Y=479.0 (should be at x-height 480?)

	* n (U+006E): X=235.5,Y=480.5 (should be at x-height 480?)

	* p (U+0070): X=234.0,Y=-0.5 (should be at baseline 0?)

	* p (U+0070): X=234.0,Y=480.5 (should be at x-height 480?)

	* q (U+0071): X=359.0,Y=480.5 (should be at x-height 480?)

	* q (U+0071): X=359.0,Y=-0.5 (should be at baseline 0?)

	* r (U+0072): X=233.5,Y=481.0 (should be at x-height 480?)

	* u (U+0075): X=62.0,Y=479.0 (should be at x-height 480?)

	* u (U+0075): X=91.0,Y=479.0 (should be at x-height 480?)

	* u (U+0075): X=429.0,Y=479.0 (should be at x-height 480?)

	* u (U+0075): X=458.0,Y=479.0 (should be at x-height 480?)

	* v (U+0076): X=212.5,Y=1.0 (should be at baseline 0?)

	* v (U+0076): X=359.5,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=212.5,Y=1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=212.5,Y=1.0 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=579.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<90.0,701.0>--<497.0,700.0>>

	* H (U+0048): L<<117.0,700.0>--<115.0,399.0>>

	* H (U+0048): L<<515.0,399.0>--<513.0,700.0>>

	* P (U+0050): L<<93.0,701.0>--<373.0,699.0>>

	* P (U+0050): L<<95.0,350.0>--<93.0,701.0>>

	* R (U+0052): L<<93.0,701.0>--<369.0,699.0>>

	* R (U+0052): L<<96.0,350.0>--<93.0,701.0>>

	* U (U+0055): L<<479.0,180.0>--<477.0,700.0>>

	* U (U+0055): L<<503.0,700.0>--<501.0,302.0>>

	* U (U+0055): L<<59.0,302.0>--<57.0,700.0>>

	* U (U+0055): L<<83.0,700.0>--<81.0,180.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] Ojuju-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 271, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: zero	Expected: 2 or 3

	- Glyph name: one	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: three	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: five	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: agrave	Expected: 3

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: atilde	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: egrave	Expected: 3

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: ograve	Expected: 3

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: endash	Expected: 1

	- Glyph name: emdash	Expected: 1

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: bullet	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: minus	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: agrave	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: atilde	Expected: 3

	- Glyph name: backslash	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: egrave	Expected: 3

	- Glyph name: eight	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: emdash	Expected: 1

	- Glyph name: endash	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: five	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: one	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: percent	Expected: 5

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: plus	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: three	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: underscore	Expected: 1

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: zero	Expected: 2 or 3
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- E.a

	- K.ss10

	- R.alt

	- a.001

	- i.loclTRK

	- l.001

	- m.alt

	- n.alt

	- n.ss01

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* B (U+0042): X=164.0,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=219.0,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=273.5,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=348.0,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=313.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=217.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=88.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=420.0,Y=1.5 (should be at baseline 0?)

	* I (U+0049): X=56.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=342.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=237.5,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=88.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=123.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=91.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=375.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=548.0,Y=-262.0 (should be at descender -260?)

	* Q (U+0051): X=578.5,Y=-258.0 (should be at descender -260?)

	* Q (U+0051): X=548.0,Y=-262.0 (should be at descender -260?)

	* R (U+0052): X=91.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=372.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=39.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=581.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=361.0,Y=481.5 (should be at x-height 481?)

	* a (U+0061): X=361.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=235.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=235.0,Y=481.5 (should be at x-height 481?)

	* d (U+0064): X=361.0,Y=481.5 (should be at x-height 481?)

	* d (U+0064): X=361.0,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=316.5,Y=738.5 (should be at ascender 740?)

	* f (U+0066): X=316.5,Y=702.0 (should be at cap-height 700?)

	* g (U+0067): X=361.0,Y=481.5 (should be at x-height 481?)

	* g (U+0067): X=361.5,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=236.5,Y=481.5 (should be at x-height 481?)

	* l (U+006C): X=184.5,Y=0.5 (should be at baseline 0?)

	* m (U+006D): X=218.0,Y=480.0 (should be at x-height 481?)

	* n (U+006E): X=236.5,Y=481.5 (should be at x-height 481?)

	* p (U+0070): X=235.0,Y=-0.5 (should be at baseline 0?)

	* p (U+0070): X=235.0,Y=481.5 (should be at x-height 481?)

	* q (U+0071): X=361.0,Y=481.5 (should be at x-height 481?)

	* q (U+0071): X=515.0,Y=-259.0 (should be at descender -260?)

	* q (U+0071): X=481.0,Y=-259.0 (should be at descender -260?)

	* q (U+0071): X=361.0,Y=-0.5 (should be at baseline 0?)

	* r (U+0072): X=235.0,Y=482.0 (should be at x-height 481?)

	* u (U+0075): X=61.0,Y=480.0 (should be at x-height 481?)

	* u (U+0075): X=92.0,Y=480.0 (should be at x-height 481?)

	* u (U+0075): X=430.0,Y=480.0 (should be at x-height 481?)

	* u (U+0075): X=462.0,Y=480.0 (should be at x-height 481?)

	* v (U+0076): X=209.5,Y=1.5 (should be at baseline 0?)

	* v (U+0076): X=362.0,Y=1.5 (should be at baseline 0?)

	* y (U+0079): X=209.5,Y=1.5 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=209.5,Y=1.5 (should be at baseline 0?)

	* trademark (U+2122): X=39.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=581.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<145.5,646.5>-<131.0,644.0>-<126.5,638.0>>

	* E (U+0045) contains a short segment B<<126.5,638.0>-<122.0,632.0>-<119.0,621.0>>

	* E (U+0045) contains a short segment B<<119.0,406.0>-<122.0,395.0>-<126.5,389.0>>

	* E (U+0045) contains a short segment B<<126.5,389.0>-<131.0,383.0>-<145.0,380.5>>

	* E (U+0045) contains a short segment B<<145.0,339.5>-<130.0,337.0>-<125.0,331.0>>

	* E (U+0045) contains a short segment B<<125.0,331.0>-<120.0,325.0>-<117.0,313.0>>

	* E (U+0045) contains a short segment B<<117.0,74.0>-<120.0,63.0>-<125.0,57.0>>

	* E (U+0045) contains a short segment B<<125.0,57.0>-<130.0,51.0>-<144.5,48.5>>

	* F (U+0046) contains a short segment B<<126.5,635.0>-<121.0,630.0>-<118.0,624.0>>

	* F (U+0046) contains a short segment B<<120.0,378.0>-<122.0,370.0>-<127.0,365.0>>

	* H (U+0048) contains a short segment B<<118.0,409.0>-<117.0,397.0>-<122.5,390.5>>

	* H (U+0048) contains a short segment B<<513.0,390.5>-<518.0,397.0>-<518.0,409.0>>

	* K (U+004B) contains a short segment B<<233.0,323.0>-<229.0,338.0>-<222.0,341.5>>

	* K (U+004B) contains a short segment B<<258.5,345.0>-<254.0,340.0>-<257.0,330.0>>

	* L (U+004C) contains a short segment B<<402.0,30.0>-<402.0,25.0>-<402.0,20.5>>

	* M (U+004D) contains a short segment B<<363.5,201.0>-<370.0,187.0>-<376.5,184.0>>

	* M (U+004D) contains a short segment B<<376.5,184.0>-<383.0,181.0>-<392.0,181.0>>

	* M (U+004D) contains a short segment B<<392.0,181.0>-<401.0,181.0>-<407.5,184.0>>

	* M (U+004D) contains a short segment B<<407.5,184.0>-<414.0,187.0>-<420.5,201.0>>

	* M (U+004D) contains a short segment B<<664.0,614.0>-<659.0,633.0>-<646.5,638.0>>

	* M (U+004D) contains a short segment B<<550.0,636.5>-<538.0,630.0>-<533.0,614.0>>

	* M (U+004D) contains a short segment B<<250.0,614.0>-<246.0,630.0>-<234.0,636.5>>

	* M (U+004D) contains a short segment B<<137.0,639.0>-<124.0,635.0>-<120.0,614.0>>

	* W (U+0057) contains a short segment B<<135.0,86.0>-<140.0,67.0>-<152.5,62.0>>

	* W (U+0057) contains a short segment B<<152.5,62.0>-<165.0,57.0>-<180.0,57.0>>

	* W (U+0057) contains a short segment B<<220.0,63.5>-<232.0,70.0>-<236.0,86.0>>

	* W (U+0057) contains a short segment B<<521.0,86.0>-<525.0,70.0>-<537.0,63.5>>

	* W (U+0057) contains a short segment B<<577.0,57.0>-<592.0,57.0>-<604.5,62.0>>

	* W (U+0057) contains a short segment B<<604.5,62.0>-<617.0,67.0>-<622.0,86.0>>

	* W (U+0057) contains a short segment B<<407.5,499.0>-<401.0,513.0>-<394.0,516.0>>

	* W (U+0057) contains a short segment B<<394.0,516.0>-<387.0,519.0>-<378.0,519.0>>

	* W (U+0057) contains a short segment B<<378.0,519.0>-<369.0,519.0>-<362.5,516.0>>

	* W (U+0057) contains a short segment B<<362.5,516.0>-<356.0,513.0>-<349.5,499.0>>

	* X (U+0058) contains a short segment B<<186.0,361.0>-<186.0,370.0>-<184.0,380.5>>

	* X (U+0058) contains a short segment B<<368.5,389.5>-<376.0,392.0>-<381.0,398.0>>

	* X (U+0058) contains a short segment B<<418.5,380.5>-<416.0,370.0>-<416.0,361.0>>

	* X (U+0058) contains a short segment B<<390.0,322.0>-<384.0,328.0>-<376.5,330.5>>

	* X (U+0058) contains a short segment B<<231.0,330.5>-<224.0,328.0>-<218.0,322.0>>

	* Z (U+005A) contains a short segment B<<470.0,496.0>-<474.0,500.0>-<476.5,505.0>>

	* Z (U+005A) contains a short segment B<<101.0,132.0>-<95.0,124.0>-<94.5,114.5>>

	* f (U+0066) contains a short segment B<<93.0,481.0>-<100.0,481.0>-<102.5,484.0>>

	* f (U+0066) contains a short segment B<<127.0,494.0>-<127.0,486.0>-<130.0,483.5>>

	* f (U+0066) contains a short segment B<<130.0,483.5>-<133.0,481.0>-<138.0,481.0>>

	* g (U+0067) contains a short segment B<<480.5,76.5>-<478.0,87.0>-<472.0,87.0>>

	* h (U+0068) contains a short segment B<<121.0,398.5>-<123.0,394.0>-<126.0,394.0>>

	* i (U+0069) contains a short segment B<<68.5,29.0>-<76.0,29.0>-<78.5,28.5>>

	* i (U+0069) contains a short segment B<<78.5,28.5>-<81.0,28.0>-<88.5,28.0>>

	* k (U+006B) contains a short segment B<<283.0,275.0>-<274.0,273.0>-<271.0,271.5>>

	* k (U+006B) contains a short segment B<<271.0,271.5>-<268.0,270.0>-<268.0,265.0>>

	* l (U+006C) contains a short segment B<<62.0,697.0>-<57.0,697.0>-<52.0,697.0>>

	* m (U+006D) contains a short segment B<<107.0,400.5>-<108.0,385.0>-<115.0,385.0>>

	* n (U+006E) contains a short segment B<<119.0,398.5>-<121.0,394.0>-<126.0,394.0>>

	* r (U+0072) contains a short segment B<<119.0,380.5>-<121.0,375.0>-<126.0,375.0>>

	* t (U+0074) contains a short segment B<<106.0,434.5>-<104.0,437.0>-<97.0,437.0>>

	* t (U+0074) contains a short segment B<<141.0,437.0>-<137.0,437.0>-<133.5,434.5>>

	* t (U+0074) contains a short segment B<<133.5,434.5>-<130.0,432.0>-<131.0,424.0>>

	* v (U+0076) contains a short segment B<<201.0,61.0>-<203.0,54.0>-<208.5,51.0>>

	* v (U+0076) contains a short segment B<<363.0,51.0>-<369.0,54.0>-<371.0,61.0>>

	* w (U+0077) contains a short segment B<<369.0,429.5>-<365.0,438.0>-<361.0,438.0>>

	* w (U+0077) contains a short segment B<<361.0,438.0>-<357.0,438.0>-<352.0,422.5>>

	* y (U+0079) contains a short segment B<<204.0,58.0>-<206.0,51.0>-<211.5,47.5>>

	* y (U+0079) contains a short segment B<<360.5,47.5>-<366.0,51.0>-<368.0,58.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<145.5,646.5>-<131.0,644.0>-<126.5,638.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<126.5,638.0>-<122.0,632.0>-<119.0,621.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<119.0,406.0>-<122.0,395.0>-<126.5,389.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<126.5,389.0>-<131.0,383.0>-<145.0,380.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<145.0,339.5>-<130.0,337.0>-<125.0,331.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<125.0,331.0>-<120.0,325.0>-<117.0,313.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<117.0,74.0>-<120.0,63.0>-<125.0,57.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<125.0,57.0>-<130.0,51.0>-<144.5,48.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<145.5,646.5>-<131.0,644.0>-<126.5,638.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<126.5,638.0>-<122.0,632.0>-<119.0,621.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<119.0,406.0>-<122.0,395.0>-<126.5,389.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<126.5,389.0>-<131.0,383.0>-<145.0,380.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<145.0,339.5>-<130.0,337.0>-<125.0,331.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<125.0,331.0>-<120.0,325.0>-<117.0,313.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<117.0,74.0>-<120.0,63.0>-<125.0,57.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<125.0,57.0>-<130.0,51.0>-<144.5,48.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<145.5,646.5>-<131.0,644.0>-<126.5,638.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<126.5,638.0>-<122.0,632.0>-<119.0,621.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<119.0,406.0>-<122.0,395.0>-<126.5,389.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<126.5,389.0>-<131.0,383.0>-<145.0,380.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<145.0,339.5>-<130.0,337.0>-<125.0,331.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<125.0,331.0>-<120.0,325.0>-<117.0,313.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<117.0,74.0>-<120.0,63.0>-<125.0,57.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<125.0,57.0>-<130.0,51.0>-<144.5,48.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<204.0,58.0>-<206.0,51.0>-<211.5,47.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<360.5,47.5>-<366.0,51.0>-<368.0,58.0>>

	* trademark (U+2122) contains a short segment B<<985.5,201.0>-<992.0,187.0>-<998.5,184.0>>

	* trademark (U+2122) contains a short segment B<<998.5,184.0>-<1005.0,181.0>-<1014.0,181.0>>

	* trademark (U+2122) contains a short segment B<<1014.0,181.0>-<1023.0,181.0>-<1029.5,184.0>>

	* trademark (U+2122) contains a short segment B<<1029.5,184.0>-<1036.0,187.0>-<1042.5,201.0>>

	* trademark (U+2122) contains a short segment B<<1286.0,614.0>-<1281.0,633.0>-<1268.5,638.0>>

	* trademark (U+2122) contains a short segment B<<1172.0,636.5>-<1160.0,630.0>-<1155.0,614.0>>

	* trademark (U+2122) contains a short segment B<<872.0,614.0>-<868.0,630.0>-<856.0,636.5>>

	* trademark (U+2122) contains a short segment B<<759.0,639.0>-<746.0,635.0>-<742.0,614.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<88.0,701.0>--<502.0,700.0>>

	* H (U+0048): L<<120.0,700.0>--<118.0,409.0>>

	* H (U+0048): L<<518.0,409.0>--<516.0,700.0>>

	* P (U+0050): L<<91.0,701.0>--<375.0,699.0>>

	* P (U+0050): L<<93.0,350.0>--<91.0,701.0>>

	* R (U+0052): L<<91.0,701.0>--<372.0,699.0>>

	* R (U+0052): L<<94.0,350.0>--<91.0,701.0>>

	* U (U+0055): L<<480.0,194.0>--<478.0,700.0>>

	* U (U+0055): L<<508.0,700.0>--<506.0,302.0>>

	* U (U+0055): L<<58.0,302.0>--<56.0,700.0>>

	* U (U+0055): L<<87.0,700.0>--<85.0,194.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] Ojuju-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 271, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: zero	Expected: 2 or 3

	- Glyph name: one	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: three	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: five	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: agrave	Expected: 3

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: atilde	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: egrave	Expected: 3

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: ograve	Expected: 3

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: endash	Expected: 1

	- Glyph name: emdash	Expected: 1

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: bullet	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: minus	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: agrave	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: atilde	Expected: 3

	- Glyph name: backslash	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: egrave	Expected: 3

	- Glyph name: eight	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: emdash	Expected: 1

	- Glyph name: endash	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: five	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: one	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: percent	Expected: 5

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: plus	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: three	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: underscore	Expected: 1

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: zero	Expected: 2 or 3
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- E.a

	- K.ss10

	- R.alt

	- a.001

	- i.loclTRK

	- l.001

	- m.alt

	- n.alt

	- n.ss01

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* B (U+0042): X=163.0,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=220.5,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=278.0,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=354.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=453.5,Y=699.5 (should be at cap-height 700?)

	* D (U+0044): X=314.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=217.0,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=86.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=425.0,Y=1.5 (should be at baseline 0?)

	* I (U+0049): X=55.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=350.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=244.0,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=86.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=127.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=89.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=379.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=548.0,Y=-262.0 (should be at descender -260?)

	* Q (U+0051): X=581.5,Y=-259.0 (should be at descender -260?)

	* Q (U+0051): X=548.0,Y=-262.0 (should be at descender -260?)

	* R (U+0052): X=89.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=375.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=38.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=584.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=363.5,Y=483.5 (should be at x-height 483?)

	* a (U+0061): X=363.5,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=236.5,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=236.5,Y=483.5 (should be at x-height 483?)

	* d (U+0064): X=363.5,Y=483.5 (should be at x-height 483?)

	* d (U+0064): X=363.5,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=318.5,Y=741.5 (should be at ascender 740?)

	* g (U+0067): X=363.5,Y=483.5 (should be at x-height 483?)

	* g (U+0067): X=363.0,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=238.0,Y=483.5 (should be at x-height 483?)

	* l (U+006C): X=185.5,Y=1.0 (should be at baseline 0?)

	* m (U+006D): X=220.0,Y=482.0 (should be at x-height 483?)

	* n (U+006E): X=238.0,Y=483.5 (should be at x-height 483?)

	* p (U+0070): X=236.5,Y=-0.5 (should be at baseline 0?)

	* p (U+0070): X=236.5,Y=483.5 (should be at x-height 483?)

	* q (U+0071): X=363.5,Y=483.5 (should be at x-height 483?)

	* q (U+0071): X=363.5,Y=-0.5 (should be at baseline 0?)

	* r (U+0072): X=235.5,Y=483.5 (should be at x-height 483?)

	* u (U+0075): X=58.0,Y=482.0 (should be at x-height 483?)

	* u (U+0075): X=94.0,Y=482.0 (should be at x-height 483?)

	* u (U+0075): X=431.0,Y=482.0 (should be at x-height 483?)

	* u (U+0075): X=467.0,Y=482.0 (should be at x-height 483?)

	* ordfeminine (U+00AA): X=363.5,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=453.5,Y=699.5 (should be at cap-height 700?)

	* uni1EA5 (U+1EA5): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=363.5,Y=-0.5 (should be at baseline 0?)

	* trademark (U+2122): X=38.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=584.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<152.5,627.5>-<138.0,625.0>-<133.0,619.5>>

	* E (U+0045) contains a short segment B<<133.0,619.5>-<128.0,614.0>-<124.0,604.0>>

	* E (U+0045) contains a short segment B<<125.0,402.0>-<128.0,392.0>-<133.0,386.5>>

	* E (U+0045) contains a short segment B<<133.0,386.5>-<138.0,381.0>-<152.0,378.5>>

	* E (U+0045) contains a short segment B<<132.0,326.0>-<126.0,320.0>-<122.0,310.0>>

	* E (U+0045) contains a short segment B<<122.0,85.0>-<126.0,75.0>-<131.5,69.5>>

	* E (U+0045) contains a short segment B<<131.5,69.5>-<137.0,64.0>-<152.0,61.5>>

	* F (U+0046) contains a short segment B<<125.0,376.0>-<128.0,368.0>-<133.0,364.0>>

	* H (U+0048) contains a short segment B<<121.0,425.0>-<121.0,412.0>-<126.5,405.0>>

	* H (U+0048) contains a short segment B<<517.5,405.0>-<523.0,412.0>-<523.0,425.0>>

	* K (U+004B) contains a short segment B<<232.0,316.0>-<228.0,330.0>-<221.0,333.5>>

	* M (U+004D) contains a short segment B<<366.0,216.5>-<372.0,203.0>-<378.5,200.0>>

	* M (U+004D) contains a short segment B<<378.5,200.0>-<385.0,197.0>-<394.0,197.0>>

	* M (U+004D) contains a short segment B<<394.0,197.0>-<403.0,197.0>-<410.0,200.0>>

	* M (U+004D) contains a short segment B<<410.0,200.0>-<417.0,203.0>-<423.0,216.5>>

	* M (U+004D) contains a short segment B<<665.0,587.0>-<660.0,605.0>-<647.0,609.5>>

	* M (U+004D) contains a short segment B<<551.5,608.0>-<539.0,602.0>-<534.0,586.0>>

	* M (U+004D) contains a short segment B<<255.0,586.0>-<250.0,602.0>-<237.5,608.0>>

	* M (U+004D) contains a short segment B<<141.5,610.5>-<129.0,607.0>-<124.0,587.0>>

	* W (U+0057) contains a short segment B<<139.0,113.0>-<144.0,95.0>-<157.0,90.5>>

	* W (U+0057) contains a short segment B<<157.0,90.5>-<170.0,86.0>-<184.0,86.0>>

	* W (U+0057) contains a short segment B<<224.5,92.0>-<236.0,98.0>-<241.0,114.0>>

	* W (U+0057) contains a short segment B<<522.0,114.0>-<527.0,98.0>-<538.5,92.0>>

	* W (U+0057) contains a short segment B<<579.0,86.0>-<594.0,86.0>-<606.5,90.5>>

	* W (U+0057) contains a short segment B<<606.5,90.5>-<619.0,95.0>-<624.0,113.0>>

	* W (U+0057) contains a short segment B<<410.0,483.5>-<404.0,497.0>-<397.0,500.0>>

	* W (U+0057) contains a short segment B<<397.0,500.0>-<390.0,503.0>-<381.0,503.0>>

	* W (U+0057) contains a short segment B<<381.0,503.0>-<372.0,503.0>-<365.0,500.0>>

	* W (U+0057) contains a short segment B<<365.0,500.0>-<358.0,497.0>-<352.0,483.5>>

	* X (U+0058) contains a short segment B<<185.0,361.0>-<185.0,370.0>-<183.0,380.5>>

	* X (U+0058) contains a short segment B<<429.5,380.5>-<427.0,370.0>-<427.0,361.0>>

	* Z (U+005A) contains a short segment B<<463.0,486.0>-<468.0,490.0>-<471.0,495.0>>

	* Z (U+005A) contains a short segment B<<471.0,495.0>-<474.0,500.0>-<475.5,515.5>>

	* Z (U+005A) contains a short segment B<<116.0,138.5>-<111.0,131.0>-<111.5,122.5>>

	* f (U+0066) contains a short segment B<<95.0,483.0>-<102.0,483.0>-<105.0,485.5>>

	* f (U+0066) contains a short segment B<<134.0,497.0>-<134.0,488.0>-<137.0,485.5>>

	* f (U+0066) contains a short segment B<<137.0,485.5>-<140.0,483.0>-<144.0,483.0>>

	* h (U+0068) contains a short segment B<<123.0,400.0>-<125.0,395.0>-<128.0,395.0>>

	* i (U+0069) contains a short segment B<<81.0,34.0>-<85.0,34.0>-<92.5,34.0>>

	* k (U+006B) contains a short segment B<<279.0,275.0>-<270.0,272.0>-<267.5,270.5>>

	* k (U+006B) contains a short segment B<<267.5,270.5>-<265.0,269.0>-<265.0,264.0>>

	* l (U+006C) contains a short segment B<<62.0,679.5>-<57.0,679.0>-<51.5,679.0>>

	* m (U+006D) contains a short segment B<<109.0,402.0>-<110.0,388.0>-<117.0,388.0>>

	* n (U+006E) contains a short segment B<<121.0,399.5>-<123.0,395.0>-<128.0,395.0>>

	* t (U+0074) contains a short segment B<<106.5,419.5>-<104.0,422.0>-<97.0,422.0>>

	* t (U+0074) contains a short segment B<<147.0,422.0>-<142.0,422.0>-<138.5,419.5>>

	* t (U+0074) contains a short segment B<<138.5,419.5>-<135.0,417.0>-<136.0,409.0>>

	* w (U+0077) contains a short segment B<<371.0,413.0>-<367.0,421.0>-<362.0,421.0>>

	* w (U+0077) contains a short segment B<<362.0,421.0>-<356.0,421.0>-<351.0,406.5>>

	* y (U+0079) contains a short segment B<<198.0,81.0>-<200.0,73.0>-<206.0,69.5>>

	* y (U+0079) contains a short segment B<<366.0,69.5>-<372.0,73.0>-<374.0,81.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<152.5,627.5>-<138.0,625.0>-<133.0,619.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<133.0,619.5>-<128.0,614.0>-<124.0,604.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<125.0,402.0>-<128.0,392.0>-<133.0,386.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<133.0,386.5>-<138.0,381.0>-<152.0,378.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<132.0,326.0>-<126.0,320.0>-<122.0,310.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<122.0,85.0>-<126.0,75.0>-<131.5,69.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<131.5,69.5>-<137.0,64.0>-<152.0,61.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<152.5,627.5>-<138.0,625.0>-<133.0,619.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<133.0,619.5>-<128.0,614.0>-<124.0,604.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<125.0,402.0>-<128.0,392.0>-<133.0,386.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<133.0,386.5>-<138.0,381.0>-<152.0,378.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<132.0,326.0>-<126.0,320.0>-<122.0,310.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<122.0,85.0>-<126.0,75.0>-<131.5,69.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<131.5,69.5>-<137.0,64.0>-<152.0,61.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<152.5,627.5>-<138.0,625.0>-<133.0,619.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<133.0,619.5>-<128.0,614.0>-<124.0,604.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<125.0,402.0>-<128.0,392.0>-<133.0,386.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<133.0,386.5>-<138.0,381.0>-<152.0,378.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<132.0,326.0>-<126.0,320.0>-<122.0,310.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<122.0,85.0>-<126.0,75.0>-<131.5,69.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<131.5,69.5>-<137.0,64.0>-<152.0,61.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<198.0,81.0>-<200.0,73.0>-<206.0,69.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<366.0,69.5>-<372.0,73.0>-<374.0,81.0>>

	* trademark (U+2122) contains a short segment B<<992.0,216.5>-<998.0,203.0>-<1004.5,200.0>>

	* trademark (U+2122) contains a short segment B<<1004.5,200.0>-<1011.0,197.0>-<1020.0,197.0>>

	* trademark (U+2122) contains a short segment B<<1020.0,197.0>-<1029.0,197.0>-<1036.0,200.0>>

	* trademark (U+2122) contains a short segment B<<1036.0,200.0>-<1043.0,203.0>-<1049.0,216.5>>

	* trademark (U+2122) contains a short segment B<<1291.0,587.0>-<1286.0,605.0>-<1273.0,609.5>>

	* trademark (U+2122) contains a short segment B<<1177.5,608.0>-<1165.0,602.0>-<1160.0,586.0>>

	* trademark (U+2122) contains a short segment B<<881.0,586.0>-<876.0,602.0>-<863.5,608.0>>

	* trademark (U+2122) contains a short segment B<<767.5,610.5>-<755.0,607.0>-<750.0,587.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<86.0,701.0>--<509.0,700.0>>

	* H (U+0048): L<<523.0,425.0>--<521.0,700.0>>

	* P (U+0050): L<<89.0,701.0>--<379.0,699.0>>

	* P (U+0050): L<<91.0,350.0>--<89.0,701.0>>

	* R (U+0052): L<<89.0,701.0>--<375.0,699.0>>

	* R (U+0052): L<<92.0,350.0>--<89.0,701.0>>

	* U (U+0055): L<<481.0,215.0>--<478.0,700.0>>

	* U (U+0055): L<<517.0,700.0>--<515.0,302.0>>

	* U (U+0055): L<<57.0,303.0>--<55.0,700.0>>

	* U (U+0055): L<<93.0,700.0>--<90.0,215.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] Ojuju-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 271, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: zero	Expected: 2 or 3

	- Glyph name: one	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: three	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: five	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: agrave	Expected: 3

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: atilde	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: egrave	Expected: 3

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: ograve	Expected: 3

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: endash	Expected: 1

	- Glyph name: emdash	Expected: 1

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: bullet	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: minus	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: agrave	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: atilde	Expected: 3

	- Glyph name: backslash	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: egrave	Expected: 3

	- Glyph name: eight	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: emdash	Expected: 1

	- Glyph name: endash	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: five	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: one	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: percent	Expected: 5

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: plus	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: three	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: underscore	Expected: 1

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: zero	Expected: 2 or 3
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- E.a

	- K.ss10

	- R.alt

	- a.001

	- i.loclTRK

	- l.001

	- m.alt

	- n.alt

	- n.ss01

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=106.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=256.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=98.0,Y=-1.5 (should be at baseline 0?)

	* exclam (U+0021): X=264.0,Y=-1.5 (should be at baseline 0?)

	* period (U+002E): X=97.0,Y=-1.5 (should be at baseline 0?)

	* period (U+002E): X=262.0,Y=-1.5 (should be at baseline 0?)

	* B (U+0042): X=293.5,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=374.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=468.0,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=315.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=213.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=78.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=443.0,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=51.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=379.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=78.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=141.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=81.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=390.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=591.5,Y=-262.0 (should be at descender -260?)

	* R (U+0052): X=81.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=388.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=33.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=594.0,Y=699.0 (should be at cap-height 700?)

	* i (U+0069): X=211.0,Y=738.0 (should be at ascender 740?)

	* j (U+006A): X=207.0,Y=738.0 (should be at ascender 740?)

	* k (U+006B): X=415.0,Y=1.0 (should be at baseline 0?)

	* m (U+006D): X=228.0,Y=487.5 (should be at x-height 489?)

	* m (U+006D): X=593.0,Y=488.0 (should be at x-height 489?)

	* s (U+0073): X=425.0,Y=490.0 (should be at x-height 489?)

	* u (U+0075): X=51.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=101.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=435.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=486.0,Y=488.0 (should be at x-height 489?)

	* x (U+0078): X=36.0,Y=490.0 (should be at x-height 489?)

	* x (U+0078): X=88.0,Y=490.0 (should be at x-height 489?)

	* x (U+0078): X=394.0,Y=490.0 (should be at x-height 489?)

	* x (U+0078): X=492.0,Y=490.0 (should be at x-height 489?)

	* Cdotaccent (U+010A): X=468.0,Y=699.0 (should be at cap-height 700?)

	* ellipsis (U+2026): X=97.0,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=262.0,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=97.0,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=262.0,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=97.0,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=262.0,Y=-1.5 (should be at baseline 0?)

	* trademark (U+2122): X=33.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=594.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<142.0,546.0>-<137.0,541.0>-<133.5,526.0>>

	* E (U+0045) contains a short segment B<<133.5,410.0>-<137.0,395.0>-<142.0,390.0>>

	* E (U+0045) contains a short segment B<<142.0,390.0>-<148.0,380.0>-<159.0,375.5>>

	* K (U+004B) contains a short segment B<<231.0,292.0>-<227.0,303.0>-<219.5,307.0>>

	* M (U+004D) contains a short segment B<<369.0,280.0>-<376.0,259.0>-<384.0,254.5>>

	* M (U+004D) contains a short segment B<<384.0,254.5>-<392.0,250.0>-<403.0,250.0>>

	* M (U+004D) contains a short segment B<<403.0,250.0>-<415.0,250.0>-<422.5,254.5>>

	* M (U+004D) contains a short segment B<<422.5,254.5>-<430.0,259.0>-<437.0,280.0>>

	* M (U+004D) contains a short segment B<<669.0,495.0>-<663.0,510.0>-<650.0,514.0>>

	* M (U+004D) contains a short segment B<<557.0,512.5>-<543.0,507.0>-<536.0,494.0>>

	* M (U+004D) contains a short segment B<<270.0,494.0>-<264.0,507.0>-<249.5,512.5>>

	* M (U+004D) contains a short segment B<<157.0,514.5>-<144.0,511.0>-<138.0,495.0>>

	* W (U+0057) contains a short segment B<<152.0,205.0>-<157.0,190.0>-<170.0,186.0>>

	* W (U+0057) contains a short segment B<<170.0,186.0>-<183.0,182.0>-<199.0,182.0>>

	* W (U+0057) contains a short segment B<<239.5,187.5>-<251.0,193.0>-<258.0,206.0>>

	* W (U+0057) contains a short segment B<<526.0,206.0>-<533.0,193.0>-<544.5,187.5>>

	* W (U+0057) contains a short segment B<<585.0,182.0>-<601.0,182.0>-<614.0,186.0>>

	* W (U+0057) contains a short segment B<<614.0,186.0>-<627.0,190.0>-<633.0,205.0>>

	* W (U+0057) contains a short segment B<<425.0,420.0>-<418.0,441.0>-<410.0,445.5>>

	* W (U+0057) contains a short segment B<<410.0,445.5>-<402.0,450.0>-<391.0,450.0>>

	* W (U+0057) contains a short segment B<<391.0,450.0>-<379.0,450.0>-<371.5,445.5>>

	* W (U+0057) contains a short segment B<<371.5,445.5>-<364.0,441.0>-<357.0,420.0>>

	* X (U+0058) contains a short segment B<<182.0,361.0>-<182.0,370.0>-<179.5,380.0>>

	* X (U+0058) contains a short segment B<<466.5,380.0>-<464.0,370.0>-<464.0,361.0>>

	* f (U+0066) contains a short segment B<<103.0,489.0>-<109.0,489.0>-<113.0,492.0>>

	* f (U+0066) contains a short segment B<<158.0,504.0>-<156.0,494.0>-<159.5,491.5>>

	* f (U+0066) contains a short segment B<<159.5,491.5>-<163.0,489.0>-<168.0,489.0>>

	* h (U+0068) contains a short segment B<<130.5,405.0>-<133.0,400.0>-<136.0,400.0>>

	* k (U+006B) contains a short segment B<<266.0,272.0>-<257.0,269.0>-<254.5,267.0>>

	* k (U+006B) contains a short segment B<<254.5,267.0>-<252.0,265.0>-<252.0,261.0>>

	* m (U+006D) contains a short segment B<<471.5,409.5>-<478.0,399.0>-<487.0,399.0>>

	* n (U+006E) contains a short segment B<<128.5,405.0>-<131.0,400.0>-<136.0,400.0>>

	* t (U+0074) contains a short segment B<<109.5,369.0>-<106.0,372.0>-<100.0,372.0>>

	* t (U+0074) contains a short segment B<<164.0,372.0>-<160.0,372.0>-<156.0,369.5>>

	* w (U+0077) contains a short segment B<<375.5,356.5>-<370.0,363.0>-<363.0,363.0>>

	* w (U+0077) contains a short segment B<<363.0,363.0>-<354.0,363.0>-<348.0,351.0>>

	* y (U+0079) contains a short segment B<<383.5,144.5>-<391.0,150.0>-<393.0,160.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<142.0,546.0>-<137.0,541.0>-<133.5,526.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<133.5,410.0>-<137.0,395.0>-<142.0,390.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<142.0,390.0>-<148.0,380.0>-<159.0,375.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<142.0,546.0>-<137.0,541.0>-<133.5,526.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<133.5,410.0>-<137.0,395.0>-<142.0,390.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<142.0,390.0>-<148.0,380.0>-<159.0,375.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<142.0,546.0>-<137.0,541.0>-<133.5,526.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<133.5,410.0>-<137.0,395.0>-<142.0,390.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<142.0,390.0>-<148.0,380.0>-<159.0,375.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<383.5,144.5>-<391.0,150.0>-<393.0,160.0>>

	* trademark (U+2122) contains a short segment B<<1010.0,280.0>-<1017.0,259.0>-<1025.0,254.5>>

	* trademark (U+2122) contains a short segment B<<1025.0,254.5>-<1033.0,250.0>-<1044.0,250.0>>

	* trademark (U+2122) contains a short segment B<<1044.0,250.0>-<1056.0,250.0>-<1063.5,254.5>>

	* trademark (U+2122) contains a short segment B<<1063.5,254.5>-<1071.0,259.0>-<1078.0,280.0>>

	* trademark (U+2122) contains a short segment B<<1310.0,495.0>-<1304.0,510.0>-<1291.0,514.0>>

	* trademark (U+2122) contains a short segment B<<1198.0,512.5>-<1184.0,507.0>-<1177.0,494.0>>

	* trademark (U+2122) contains a short segment B<<911.0,494.0>-<905.0,507.0>-<890.5,512.5>>

	* trademark (U+2122) contains a short segment B<<798.0,514.5>-<785.0,511.0>-<779.0,495.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<533.0,700.0>--<532.0,567.0>>

	* F (U+0046): L<<78.0,701.0>--<533.0,700.0>>

	* P (U+0050): L<<81.0,701.0>--<390.0,699.0>>

	* P (U+0050): L<<83.0,350.0>--<81.0,701.0>>

	* R (U+0052): L<<81.0,701.0>--<388.0,699.0>>

	* R (U+0052): L<<84.0,350.0>--<81.0,701.0>>

	* S (U+0053): L<<56.0,12.0>--<55.0,135.0>>

	* U (U+0055): L<<113.0,700.0>--<110.0,286.0>>

	* U (U+0055): L<<52.0,305.0>--<51.0,700.0>>

	* U (U+0055): L<<545.0,700.0>--<542.0,302.0>>

	* Z (U+005A): L<<549.0,700.0>--<547.0,438.0>>

	* r (U+0072): L<<377.0,502.0>--<376.0,360.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] Ojuju-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 271, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: zero	Expected: 2 or 3

	- Glyph name: one	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: three	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: five	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: agrave	Expected: 3

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: atilde	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: egrave	Expected: 3

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: ograve	Expected: 3

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: endash	Expected: 1

	- Glyph name: emdash	Expected: 1

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: bullet	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: minus	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: agrave	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: atilde	Expected: 3

	- Glyph name: backslash	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: egrave	Expected: 3

	- Glyph name: eight	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: emdash	Expected: 1

	- Glyph name: endash	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: five	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: one	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: percent	Expected: 5

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: plus	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: three	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: underscore	Expected: 1

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: zero	Expected: 2 or 3
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- E.a

	- K.ss10

	- R.alt

	- a.001

	- i.loclTRK

	- l.001

	- m.alt

	- n.alt

	- n.ss01

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=124.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=245.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=284.5,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=363.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=460.0,Y=699.5 (should be at cap-height 700?)

	* D (U+0044): X=314.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=215.0,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=83.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=432.5,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=53.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=362.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=83.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=133.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=86.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=384.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=586.0,Y=-261.0 (should be at descender -260?)

	* R (U+0052): X=86.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=381.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=36.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=588.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=366.5,Y=485.5 (should be at x-height 485?)

	* a (U+0061): X=366.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=239.5,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=239.5,Y=485.5 (should be at x-height 485?)

	* d (U+0064): X=368.0,Y=485.5 (should be at x-height 485?)

	* d (U+0064): X=368.0,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=366.5,Y=485.5 (should be at x-height 485?)

	* g (U+0067): X=366.5,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=240.0,Y=485.5 (should be at x-height 485?)

	* m (U+006D): X=223.5,Y=484.5 (should be at x-height 485?)

	* n (U+006E): X=240.0,Y=485.5 (should be at x-height 485?)

	* p (U+0070): X=239.5,Y=-0.5 (should be at baseline 0?)

	* p (U+0070): X=239.5,Y=485.5 (should be at x-height 485?)

	* q (U+0071): X=368.0,Y=485.5 (should be at x-height 485?)

	* q (U+0071): X=368.0,Y=-0.5 (should be at baseline 0?)

	* r (U+0072): X=238.0,Y=486.0 (should be at x-height 485?)

	* s (U+0073): X=414.0,Y=486.0 (should be at x-height 485?)

	* x (U+0078): X=36.0,Y=486.0 (should be at x-height 485?)

	* x (U+0078): X=80.0,Y=486.0 (should be at x-height 485?)

	* x (U+0078): X=419.0,Y=486.0 (should be at x-height 485?)

	* x (U+0078): X=492.0,Y=486.0 (should be at x-height 485?)

	* ordfeminine (U+00AA): X=366.0,Y=-0.5 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=460.0,Y=699.5 (should be at cap-height 700?)

	* uni1EA5 (U+1EA5): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=366.0,Y=-0.5 (should be at baseline 0?)

	* trademark (U+2122): X=36.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=588.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<130.0,102.0>-<134.0,93.0>-<141.0,88.0>>

	* K (U+004B) contains a short segment B<<232.0,306.0>-<228.0,319.0>-<220.5,322.5>>

	* M (U+004D) contains a short segment B<<364.5,251.0>-<372.0,229.0>-<379.5,224.0>>

	* M (U+004D) contains a short segment B<<379.5,224.0>-<387.0,219.0>-<398.0,219.0>>

	* M (U+004D) contains a short segment B<<398.0,219.0>-<409.0,219.0>-<417.0,224.0>>

	* M (U+004D) contains a short segment B<<417.0,224.0>-<425.0,229.0>-<432.5,251.0>>

	* M (U+004D) contains a short segment B<<666.0,548.0>-<661.0,564.0>-<648.0,569.0>>

	* M (U+004D) contains a short segment B<<554.0,568.0>-<541.0,562.0>-<535.0,547.0>>

	* M (U+004D) contains a short segment B<<261.0,547.0>-<256.0,562.0>-<242.5,568.0>>

	* M (U+004D) contains a short segment B<<148.0,570.0>-<135.0,566.0>-<130.0,548.0>>

	* W (U+0057) contains a short segment B<<144.0,152.0>-<150.0,136.0>-<162.5,131.0>>

	* W (U+0057) contains a short segment B<<162.5,131.0>-<175.0,126.0>-<191.0,126.0>>

	* W (U+0057) contains a short segment B<<231.0,132.0>-<243.0,138.0>-<248.0,153.0>>

	* W (U+0057) contains a short segment B<<524.0,153.0>-<530.0,138.0>-<541.5,132.0>>

	* W (U+0057) contains a short segment B<<582.0,126.0>-<597.0,126.0>-<609.5,131.0>>

	* W (U+0057) contains a short segment B<<609.5,131.0>-<622.0,136.0>-<628.0,152.0>>

	* W (U+0057) contains a short segment B<<404.0,476.0>-<396.0,481.0>-<385.0,481.0>>

	* W (U+0057) contains a short segment B<<385.0,481.0>-<374.0,481.0>-<366.0,476.0>>

	* X (U+0058) contains a short segment B<<184.0,361.0>-<184.0,370.0>-<181.5,380.0>>

	* X (U+0058) contains a short segment B<<445.0,380.0>-<443.0,370.0>-<443.0,361.0>>

	* Z (U+005A) contains a short segment B<<453.0,471.0>-<459.0,475.0>-<462.0,480.5>>

	* Z (U+005A) contains a short segment B<<462.0,480.5>-<465.0,486.0>-<467.0,499.5>>

	* Z (U+005A) contains a short segment B<<137.5,148.5>-<134.0,142.0>-<136.0,134.0>>

	* Z (U+005A) contains a short segment B<<143.0,111.0>-<145.0,99.0>-<149.5,92.0>>

	* f (U+0066) contains a short segment B<<98.0,485.0>-<105.0,485.0>-<108.5,488.0>>

	* f (U+0066) contains a short segment B<<144.0,500.0>-<143.0,490.0>-<146.5,487.5>>

	* f (U+0066) contains a short segment B<<146.5,487.5>-<150.0,485.0>-<154.0,485.0>>

	* h (U+0068) contains a short segment B<<126.0,402.5>-<128.0,398.0>-<131.0,398.0>>

	* k (U+006B) contains a short segment B<<274.0,274.0>-<264.0,271.0>-<261.5,269.0>>

	* k (U+006B) contains a short segment B<<261.5,269.0>-<259.0,267.0>-<259.0,263.0>>

	* n (U+006E) contains a short segment B<<124.0,402.5>-<126.0,398.0>-<131.0,398.0>>

	* t (U+0074) contains a short segment B<<108.0,398.0>-<105.0,401.0>-<98.0,401.0>>

	* t (U+0074) contains a short segment B<<154.0,401.0>-<150.0,401.0>-<146.0,398.5>>

	* w (U+0077) contains a short segment B<<372.5,389.0>-<368.0,396.0>-<362.0,396.0>>

	* w (U+0077) contains a short segment B<<362.0,396.0>-<355.0,396.0>-<349.5,383.0>>

	* y (U+0079) contains a short segment B<<190.0,114.0>-<192.0,106.0>-<198.5,101.0>>

	* y (U+0079) contains a short segment B<<373.5,101.0>-<380.0,106.0>-<382.0,114.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<130.0,102.0>-<134.0,93.0>-<141.0,88.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<130.0,102.0>-<134.0,93.0>-<141.0,88.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<130.0,102.0>-<134.0,93.0>-<141.0,88.0>>

	* uni1EF9 (U+1EF9) contains a short segment B<<190.0,114.0>-<192.0,106.0>-<198.5,101.0>>

	* uni1EF9 (U+1EF9) contains a short segment B<<373.5,101.0>-<380.0,106.0>-<382.0,114.0>>

	* trademark (U+2122) contains a short segment B<<996.5,251.0>-<1004.0,229.0>-<1011.5,224.0>>

	* trademark (U+2122) contains a short segment B<<1011.5,224.0>-<1019.0,219.0>-<1030.0,219.0>>

	* trademark (U+2122) contains a short segment B<<1030.0,219.0>-<1041.0,219.0>-<1049.0,224.0>>

	* trademark (U+2122) contains a short segment B<<1049.0,224.0>-<1057.0,229.0>-<1064.5,251.0>>

	* trademark (U+2122) contains a short segment B<<1298.0,548.0>-<1293.0,564.0>-<1280.0,569.0>>

	* trademark (U+2122) contains a short segment B<<1186.0,568.0>-<1173.0,562.0>-<1167.0,547.0>>

	* trademark (U+2122) contains a short segment B<<893.0,547.0>-<888.0,562.0>-<874.5,568.0>>

	* trademark (U+2122) contains a short segment B<<780.0,570.0>-<767.0,566.0>-<762.0,548.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<83.0,701.0>--<519.0,700.0>>

	* G (U+0047): L<<505.0,681.0>--<504.0,552.0>>

	* H (U+0048): L<<129.0,700.0>--<127.0,447.0>>

	* H (U+0048): L<<530.0,447.0>--<528.0,700.0>>

	* P (U+0050): L<<86.0,701.0>--<384.0,699.0>>

	* P (U+0050): L<<88.0,350.0>--<86.0,701.0>>

	* R (U+0052): L<<86.0,701.0>--<381.0,699.0>>

	* R (U+0052): L<<89.0,350.0>--<86.0,701.0>>

	* U (U+0055): L<<102.0,700.0>--<99.0,245.0>>

	* U (U+0055): L<<482.0,245.0>--<480.0,700.0>>

	* U (U+0055): L<<528.0,700.0>--<526.0,302.0>>

	* U (U+0055): L<<55.0,304.0>--<53.0,700.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[21] Ojuju-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0308 (COMBINING DIAERESIS)


	- 0x0300 (COMBINING GRAVE ACCENT)


	- 0x0301 (COMBINING ACUTE ACCENT)


	- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


	- 0x0304 (COMBINING MACRON)


	- 0x02D9 (DOT ABOVE)


	- 0x0307 (COMBINING DOT ABOVE)


	- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


	- 0x030C (COMBINING CARON)


	- 0x0306 (COMBINING BREVE)


	- 0x030A (COMBINING RING ABOVE)


	- 0x0303 (COMBINING TILDE)


	- 0x0312 (COMBINING TURNED COMMA ABOVE)


	- 0x0326 (COMBINING COMMA BELOW)


	- 0x0327 (COMBINING CEDILLA)


	- 0x0328 (COMBINING OGONEK)


	- 0x00A8 (DIAERESIS)


	- 0x0060 (GRAVE ACCENT)


	- 0x00B4 (ACUTE ACCENT)


	- 0x02DD (DOUBLE ACUTE ACCENT)


	- 0x02C6 (MODIFIER LETTER CIRCUMFLEX ACCENT)


	- 0x02C7 (CARON)


	- 0x02D8 (BREVE)


	- 0x02DA (RING ABOVE)


	- 0x02DC (SMALL TILDE)


	- 0x00AF (MACRON)


	- 0x00B8 (CEDILLA)


	- 0x02DB (OGONEK)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 the ojuju typeface project chisaokwu joboson (https://github.com/jobosonchisa/ojuju)"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "200" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 271, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.3 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* 🔥 **FAIL** The '.notdef' glyph should contain a drawing, but it is blank. [code: notdef-is-blank]
</div></details><details><summary>🔥 <b>FAIL:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have no contours even though they were expected to have some:

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: percent	Expected: 5

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: plus	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: zero	Expected: 2 or 3

	- Glyph name: one	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: three	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: five	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: equal	Expected: 2

	- Glyph name: greater	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: at	Expected: 2

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: degree	Expected: 2

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: AE	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Eth	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: multiply	Expected: 1

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: germandbls	Expected: 1

	- Glyph name: agrave	Expected: 3

	- Glyph name: aacute	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: atilde	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: aring	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: egrave	Expected: 3

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: igrave	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: eth	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: ograve	Expected: 3

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: divide	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uacute	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: yacute	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: Cacute	Expected: 2

	- Glyph name: cacute	Expected: 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: dcroat	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: emacron	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: eogonek	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: ecaron	Expected: 3

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: Hbar	Expected: 2

	- Glyph name: hbar	Expected: 1

	- Glyph name: Imacron	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: Lacute	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: nacute	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: Omacron	Expected: 3

	- Glyph name: omacron	Expected: 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: OE	Expected: 2

	- Glyph name: oe	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: racute	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: rcaron	Expected: 2

	- Glyph name: Sacute	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: Scedilla	Expected: 1 or 2

	- Glyph name: scedilla	Expected: 1 or 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: Umacron	Expected: 2

	- Glyph name: umacron	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: Uring	Expected: 3

	- Glyph name: uring	Expected: 3

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Zacute	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: endash	Expected: 1

	- Glyph name: emdash	Expected: 1

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: bullet	Expected: 1

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: minus	Expected: 1

	- Glyph name: AE	Expected: 2

	- Glyph name: Aacute	Expected: 3

	- Glyph name: Abreve	Expected: 3

	- Glyph name: Acircumflex	Expected: 3

	- Glyph name: Adieresis	Expected: 4

	- Glyph name: Agrave	Expected: 3

	- Glyph name: Amacron	Expected: 3

	- Glyph name: Aogonek	Expected: 2 or 3

	- Glyph name: Aring	Expected: 3 or 4

	- Glyph name: Atilde	Expected: 3

	- Glyph name: Cacute	Expected: 2

	- Glyph name: Ccaron	Expected: 2

	- Glyph name: Ccedilla	Expected: 1 or 2

	- Glyph name: Dcaron	Expected: 3

	- Glyph name: Dcroat	Expected: 2

	- Glyph name: Eacute	Expected: 2

	- Glyph name: Ecaron	Expected: 2

	- Glyph name: Ecircumflex	Expected: 2

	- Glyph name: Edieresis	Expected: 3

	- Glyph name: Edotaccent	Expected: 2

	- Glyph name: Egrave	Expected: 2

	- Glyph name: Emacron	Expected: 2

	- Glyph name: Eng	Expected: 1

	- Glyph name: Eogonek	Expected: 1 or 2

	- Glyph name: Eth	Expected: 2

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: Gbreve	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Lacute	Expected: 2

	- Glyph name: Lcaron	Expected: 2

	- Glyph name: Lslash	Expected: 1

	- Glyph name: Nacute	Expected: 2

	- Glyph name: Ncaron	Expected: 2

	- Glyph name: Ntilde	Expected: 2

	- Glyph name: OE	Expected: 2

	- Glyph name: Oacute	Expected: 3

	- Glyph name: Ocircumflex	Expected: 3

	- Glyph name: Odieresis	Expected: 4

	- Glyph name: Ograve	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: Ohungarumlaut	Expected: 4

	- Glyph name: Omacron	Expected: 3

	- Glyph name: Oslash	Expected: 2 or 3

	- Glyph name: Otilde	Expected: 3

	- Glyph name: Racute	Expected: 3

	- Glyph name: Rcaron	Expected: 3

	- Glyph name: Sacute	Expected: 2

	- Glyph name: Scaron	Expected: 2

	- Glyph name: Tcaron	Expected: 2

	- Glyph name: Thorn	Expected: 1 or 2

	- Glyph name: Uacute	Expected: 2

	- Glyph name: Ubreve	Expected: 2

	- Glyph name: Ucircumflex	Expected: 2

	- Glyph name: Udieresis	Expected: 3

	- Glyph name: Ugrave	Expected: 2

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: Uhungarumlaut	Expected: 3

	- Glyph name: Umacron	Expected: 2

	- Glyph name: Uogonek	Expected: 1

	- Glyph name: Uring	Expected: 3

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Zacute	Expected: 2

	- Glyph name: Zcaron	Expected: 2

	- Glyph name: Zdotaccent	Expected: 2

	- Glyph name: aacute	Expected: 3

	- Glyph name: abreve	Expected: 3

	- Glyph name: acircumflex	Expected: 3

	- Glyph name: adieresis	Expected: 4

	- Glyph name: ae	Expected: 3

	- Glyph name: agrave	Expected: 3

	- Glyph name: amacron	Expected: 3

	- Glyph name: ampersand	Expected: 1, 2 or 3

	- Glyph name: aogonek	Expected: 2

	- Glyph name: aring	Expected: 4

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: asterisk	Expected: 1 or 4

	- Glyph name: at	Expected: 2

	- Glyph name: atilde	Expected: 3

	- Glyph name: backslash	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: colon	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotlessi	Expected: 1

	- Glyph name: eacute	Expected: 3

	- Glyph name: ecaron	Expected: 3

	- Glyph name: ecircumflex	Expected: 3

	- Glyph name: edieresis	Expected: 4

	- Glyph name: edotaccent	Expected: 3

	- Glyph name: egrave	Expected: 3

	- Glyph name: eight	Expected: 3

	- Glyph name: emacron	Expected: 3

	- Glyph name: emdash	Expected: 1

	- Glyph name: endash	Expected: 1

	- Glyph name: eng	Expected: 1

	- Glyph name: eogonek	Expected: 2

	- Glyph name: equal	Expected: 2

	- Glyph name: eth	Expected: 2

	- Glyph name: exclamdown	Expected: 2

	- Glyph name: five	Expected: 1

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: nine	Expected: 1 or 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: one	Expected: 1

	- Glyph name: oslash	Expected: 3

	- Glyph name: otilde	Expected: 3

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: parenleft	Expected: 1

	- Glyph name: parenright	Expected: 1

	- Glyph name: percent	Expected: 5

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: plus	Expected: 1

	- Glyph name: question	Expected: 2

	- Glyph name: questiondown	Expected: 2

	- Glyph name: quotedbl	Expected: 2

	- Glyph name: quotedblleft	Expected: 2

	- Glyph name: quotedblright	Expected: 2

	- Glyph name: quoteleft	Expected: 1

	- Glyph name: quoteright	Expected: 1

	- Glyph name: quotesinglbase	Expected: 1

	- Glyph name: quotesingle	Expected: 1

	- Glyph name: racute	Expected: 2

	- Glyph name: rcaron	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: semicolon	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: six	Expected: 1 or 2

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: three	Expected: 1

	- Glyph name: two	Expected: 1

	- Glyph name: uacute	Expected: 2

	- Glyph name: ubreve	Expected: 2

	- Glyph name: ucircumflex	Expected: 2

	- Glyph name: udieresis	Expected: 3

	- Glyph name: ugrave	Expected: 2

	- Glyph name: uhorn	Expected: 1

	- Glyph name: uhungarumlaut	Expected: 3

	- Glyph name: umacron	Expected: 2

	- Glyph name: underscore	Expected: 1

	- Glyph name: uni0122	Expected: 2

	- Glyph name: uni0123	Expected: 3 or 4

	- Glyph name: uni0136	Expected: 2 or 3

	- Glyph name: uni0137	Expected: 2 or 3

	- Glyph name: uni013B	Expected: 2

	- Glyph name: uni013C	Expected: 2

	- Glyph name: uni0145	Expected: 2

	- Glyph name: uni0146	Expected: 2

	- Glyph name: uni0156	Expected: 3

	- Glyph name: uni0157	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1EDA	Expected: 3 or 4

	- Glyph name: uni1EDB	Expected: 3

	- Glyph name: uni1EDC	Expected: 3 or 4

	- Glyph name: uni1EDD	Expected: 3

	- Glyph name: uni1EDE	Expected: 3 or 4

	- Glyph name: uni1EDF	Expected: 3

	- Glyph name: uni1EE0	Expected: 3 or 4

	- Glyph name: uni1EE1	Expected: 3

	- Glyph name: uni1EE2	Expected: 3 or 4

	- Glyph name: uni1EE3	Expected: 3

	- Glyph name: uni1EE6	Expected: 2

	- Glyph name: uni1EE7	Expected: 2

	- Glyph name: uni1EE8	Expected: 2

	- Glyph name: uni1EE9	Expected: 2

	- Glyph name: uni1EEA	Expected: 2

	- Glyph name: uni1EEB	Expected: 2

	- Glyph name: uni1EEC	Expected: 2

	- Glyph name: uni1EED	Expected: 2

	- Glyph name: uni1EEE	Expected: 2

	- Glyph name: uni1EEF	Expected: 2

	- Glyph name: uni1EF0	Expected: 2

	- Glyph name: uni1EF1	Expected: 2

	- Glyph name: uni1EF4	Expected: 2

	- Glyph name: uni1EF5	Expected: 2

	- Glyph name: uni1EF6	Expected: 2

	- Glyph name: uni1EF7	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: zacute	Expected: 2

	- Glyph name: zcaron	Expected: 2

	- Glyph name: zdotaccent	Expected: 2

	- Glyph name: zero	Expected: 2 or 3
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EF8	Contours detected: 1	Expected: 2

	- Glyph name: uni1EF9	Contours detected: 1	Expected: 2
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0}
	* {'glyph': 'ellipsis', 'component': 'period', 'x': 0, 'y': 0} and {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- E.a

	- K.ss10

	- R.alt

	- a.001

	- i.loclTRK

	- l.001

	- m.alt

	- n.alt

	- n.ss01

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=45.0,Y=702.0 (should be at cap-height 700?)

	* exclam (U+0021): X=296.0,Y=702.0 (should be at cap-height 700?)

	* B (U+0042): X=62.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=238.0,Y=700.5 (should be at cap-height 700?)

	* B (U+0042): X=414.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=497.0,Y=698.0 (should be at cap-height 700?)

	* C (U+0043): X=449.5,Y=-2.0 (should be at baseline 0?)

	* F (U+0046): X=62.0,Y=701.0 (should be at cap-height 700?)

	* F (U+0046): X=580.0,Y=699.0 (should be at cap-height 700?)

	* G (U+0047): X=481.0,Y=702.0 (should be at cap-height 700?)

	* I (U+0049): X=42.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=435.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=75.0,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=62.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=168.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=65.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=413.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=65.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=413.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=24.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=613.0,Y=699.0 (should be at cap-height 700?)

	* Y (U+0059): X=350.5,Y=1.5 (should be at baseline 0?)

	* e (U+0065): X=504.0,Y=2.0 (should be at baseline 0?)

	* h (U+0068): X=452.0,Y=501.0 (should be at x-height 500?)

	* k (U+006B): X=141.0,Y=501.0 (should be at x-height 500?)

	* l (U+006C): X=139.5,Y=500.5 (should be at x-height 500?)

	* l (U+006C): X=21.0,Y=501.0 (should be at x-height 500?)

	* m (U+006D): X=243.5,Y=499.0 (should be at x-height 500?)

	* n (U+006E): X=452.0,Y=501.0 (should be at x-height 500?)

	* s (U+0073): X=460.0,Y=502.0 (should be at x-height 500?)

	* Cdotaccent (U+010A): X=497.0,Y=698.0 (should be at cap-height 700?)

	* Cdotaccent (U+010A): X=449.5,Y=-2.0 (should be at baseline 0?)

	* uni1EBF (U+1EBF): X=504.0,Y=2.0 (should be at baseline 0?)

	* uni1EC1 (U+1EC1): X=504.0,Y=2.0 (should be at baseline 0?)

	* uni1EC5 (U+1EC5): X=504.0,Y=2.0 (should be at baseline 0?)

	* uni1EF8 (U+1EF8): X=350.5,Y=1.5 (should be at baseline 0?)

	* trademark (U+2122): X=24.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=613.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* G (U+0047) contains a short segment B<<452.0,210.0>-<455.0,211.0>-<455.0,225.5>>

	* K (U+004B) contains a short segment B<<238.5,224.5>-<235.0,236.0>-<228.0,244.0>>

	* K (U+004B) contains a short segment B<<299.0,349.0>-<299.0,343.0>-<306.0,334.5>>

	* M (U+004D) contains a short segment B<<387.0,378.0>-<392.0,361.0>-<400.5,357.0>>

	* M (U+004D) contains a short segment B<<400.5,357.0>-<409.0,353.0>-<421.0,353.0>>

	* M (U+004D) contains a short segment B<<421.0,353.0>-<433.0,353.0>-<441.5,357.0>>

	* M (U+004D) contains a short segment B<<441.5,357.0>-<450.0,361.0>-<455.0,378.0>>

	* M (U+004D) contains a short segment B<<676.0,316.0>-<669.0,324.0>-<655.0,326.5>>

	* M (U+004D) contains a short segment B<<187.5,326.5>-<174.0,324.0>-<166.0,316.0>>

	* W (U+0057) contains a short segment B<<176.0,384.0>-<184.0,377.0>-<197.0,374.0>>

	* W (U+0057) contains a short segment B<<268.5,375.0>-<280.0,379.0>-<290.0,388.0>>

	* W (U+0057) contains a short segment B<<535.0,388.0>-<546.0,379.0>-<557.0,375.0>>

	* W (U+0057) contains a short segment B<<628.5,374.0>-<642.0,377.0>-<649.0,384.0>>

	* W (U+0057) contains a short segment B<<444.5,322.0>-<439.0,339.0>-<431.0,343.0>>

	* W (U+0057) contains a short segment B<<431.0,343.0>-<423.0,347.0>-<410.0,347.0>>

	* W (U+0057) contains a short segment B<<410.0,347.0>-<397.0,347.0>-<389.0,343.0>>

	* W (U+0057) contains a short segment B<<389.0,343.0>-<381.0,339.0>-<375.5,322.0>>

	* X (U+0058) contains a short segment B<<172.5,341.5>-<175.0,352.0>-<175.0,361.0>>

	* X (U+0058) contains a short segment B<<175.0,361.0>-<175.0,370.0>-<172.5,380.0>>

	* X (U+0058) contains a short segment B<<539.0,380.0>-<537.0,370.0>-<537.0,361.0>>

	* X (U+0058) contains a short segment B<<537.0,361.0>-<537.0,352.0>-<539.5,341.5>>

	* Y (U+0059) contains a short segment B<<512.0,297.0>-<511.0,310.0>-<500.0,310.0>>

	* Z (U+005A) contains a short segment B<<264.0,214.0>-<264.0,207.0>-<273.0,204.5>>

	* b (U+0062) contains a short segment B<<141.5,421.5>-<144.0,410.0>-<150.0,410.0>>

	* d (U+0064) contains a short segment B<<496.0,410.0>-<502.0,410.0>-<504.5,421.5>>

	* f (U+0066) contains a short segment B<<119.0,500.0>-<124.0,500.0>-<129.5,504.0>>

	* f (U+0066) contains a short segment B<<204.0,503.0>-<209.0,500.0>-<213.0,500.0>>

	* g (U+0067) contains a short segment B<<499.5,81.0>-<497.0,90.0>-<488.0,90.0>>

	* h (U+0068) contains a short segment B<<144.0,419.5>-<147.0,410.0>-<152.0,410.0>>

	* k (U+006B) contains a short segment B<<226.0,254.0>-<226.0,249.0>-<234.5,240.5>>

	* m (U+006D) contains a short segment B<<135.0,416.0>-<137.0,410.0>-<141.0,410.0>>

	* m (U+006D) contains a short segment B<<495.5,419.5>-<501.0,409.0>-<511.0,409.0>>

	* m (U+006D) contains a short segment B<<511.0,409.0>-<521.0,409.0>-<529.0,419.5>>

	* m (U+006D) contains a short segment B<<825.5,123.0>-<826.0,136.0>-<826.0,145.0>>

	* n (U+006E) contains a short segment B<<142.0,415.0>-<145.0,410.0>-<152.0,410.0>>

	* p (U+0070) contains a short segment B<<140.0,416.5>-<142.0,410.0>-<150.0,410.0>>

	* q (U+0071) contains a short segment B<<496.0,410.0>-<505.0,410.0>-<506.5,416.5>>

	* t (U+0074) contains a short segment B<<115.5,270.0>-<110.0,274.0>-<105.0,274.0>>

	* t (U+0074) contains a short segment B<<199.0,274.0>-<195.0,274.0>-<190.0,271.0>>

	* y (U+0079) contains a short segment B<<346.0,-10.0>-<346.0,-5.0>-<338.5,-2.5>>

	* z (U+007A) contains a short segment B<<212.0,153.0>-<212.0,148.0>-<218.5,146.0>>

	* uni1EF8 (U+1EF8) contains a short segment B<<512.0,297.0>-<511.0,310.0>-<500.0,310.0>>

	* uni1EF9 (U+1EF9) contains a short segment B<<346.0,-10.0>-<346.0,-5.0>-<338.5,-2.5>>

	* trademark (U+2122) contains a short segment B<<1056.0,378.0>-<1061.0,361.0>-<1069.5,357.0>>

	* trademark (U+2122) contains a short segment B<<1069.5,357.0>-<1078.0,353.0>-<1090.0,353.0>>

	* trademark (U+2122) contains a short segment B<<1090.0,353.0>-<1102.0,353.0>-<1110.5,357.0>>

	* trademark (U+2122) contains a short segment B<<1110.5,357.0>-<1119.0,361.0>-<1124.0,378.0>>

	* trademark (U+2122) contains a short segment B<<1345.0,316.0>-<1338.0,324.0>-<1324.0,326.5>>

	* trademark (U+2122) contains a short segment B<<856.5,326.5>-<843.0,324.0>-<835.0,316.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<62.0,701.0>--<580.0,699.0>>

	* P (U+0050): L<<65.0,701.0>--<413.0,699.0>>

	* P (U+0050): L<<68.0,350.0>--<65.0,701.0>>

	* R (U+0052): L<<65.0,701.0>--<413.0,699.0>>

	* R (U+0052): L<<68.0,350.0>--<65.0,701.0>>

	* S (U+0053): L<<53.0,7.0>--<52.0,234.0>>

	* U (U+0055): L<<43.0,310.0>--<42.0,700.0>>

	* U (U+0055): L<<599.0,700.0>--<596.0,302.0>>

	* i (U+0069): L<<61.0,261.0>--<60.0,500.0>>

	* l (U+006C): L<<21.0,501.0>--<20.0,740.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 14 | 70 | 62 | 863 | 36 | 596 | 0 |
| 1% | 4% | 4% | 53% | 2% | 36% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
