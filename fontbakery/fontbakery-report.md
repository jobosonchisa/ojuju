## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[23] Ojuju-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
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
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Ojuju-Bold.ttf', 'fonts/ttf/Ojuju-ExtraLight.ttf', 'fonts/ttf/Ojuju-Light.ttf', 'fonts/ttf/Ojuju-Regular.ttf', 'fonts/ttf/Ojuju-SemiBold.ttf', 'fonts/ttf/Ojuju-Medium.ttf', 'fonts/ttf/Ojuju-ExtraBold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 224, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
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

	- Glyph name: hyphen	Expected: 1

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Z	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: k	Expected: 1 or 2

	- Glyph name: w	Expected: 1

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: z	Expected: 1

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Z	Expected: 1

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

	- Glyph name: hyphen	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: k	Expected: 1 or 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: w	Expected: 1

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: z	Expected: 1

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

	- R.alt

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

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

	* exclam (U+0021): X=64.0,Y=702.0 (should be at cap-height 700?)

	* exclam (U+0021): X=284.0,Y=702.0 (should be at cap-height 700?)

	* exclam (U+0021): X=82.5,Y=1.0 (should be at baseline 0?)

	* exclam (U+0021): X=264.5,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=79.5,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=260.5,Y=1.0 (should be at baseline 0?)

	* B (U+0042): X=68.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=399.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=488.5,Y=698.5 (should be at cap-height 700?)

	* C (U+0043): X=442.5,Y=-2.0 (should be at baseline 0?)

	* F (U+0046): X=67.0,Y=701.0 (should be at cap-height 700?)

	* F (U+0046): X=566.0,Y=699.0 (should be at cap-height 700?)

	* G (U+0047): X=472.0,Y=702.0 (should be at cap-height 700?)

	* I (U+0049): X=67.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=441.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=77.5,Y=0.5 (should be at baseline 0?)

	* K (U+004B): X=644.0,Y=-1.0 (should be at baseline 0?)

	* L (U+004C): X=67.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=152.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=70.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=406.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=70.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=406.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=620.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=483.0,Y=498.0 (should be at x-height 497?)

	* a (U+0061): X=553.0,Y=498.0 (should be at x-height 497?)

	* d (U+0064): X=396.0,Y=498.0 (should be at x-height 497?)

	* f (U+0066): X=33.0,Y=499.0 (should be at x-height 497?)

	* f (U+0066): X=323.0,Y=799.0 (should be at ascender 800?)

	* f (U+0066): X=178.0,Y=499.0 (should be at x-height 497?)

	* f (U+0066): X=516.0,Y=499.0 (should be at x-height 497?)

	* g (U+0067): X=389.5,Y=-1.5 (should be at baseline 0?)

	* g (U+0067): X=394.0,Y=495.0 (should be at x-height 497?)

	* g (U+0067): X=486.0,Y=498.0 (should be at x-height 497?)

	* g (U+0067): X=556.0,Y=498.0 (should be at x-height 497?)

	* i (U+0069): X=116.0,Y=698.0 (should be at cap-height 700?)

	* i (U+0069): X=333.0,Y=698.0 (should be at cap-height 700?)

	* n (U+006E): X=281.5,Y=499.0 (should be at x-height 497?)

	* s (U+0073): X=57.0,Y=2.0 (should be at baseline 0?)

	* t (U+0074): X=28.0,Y=499.0 (should be at x-height 497?)

	* t (U+0074): X=105.0,Y=499.0 (should be at x-height 497?)

	* t (U+0074): X=173.0,Y=499.0 (should be at x-height 497?)

	* t (U+0074): X=511.0,Y=499.0 (should be at x-height 497?)

	* t (U+0074): X=415.0,Y=-0.5 (should be at baseline 0?)

	* u (U+0075): X=53.0,Y=496.0 (should be at x-height 497?)

	* u (U+0075): X=122.0,Y=496.0 (should be at x-height 497?)

	* u (U+0075): X=462.0,Y=496.0 (should be at x-height 497?)

	* u (U+0075): X=531.0,Y=496.0 (should be at x-height 497?)

	* ellipsis (U+2026): X=79.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=260.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=79.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=260.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=79.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=260.5,Y=1.0 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=620.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* B (U+0042) contains a short segment B<<477.0,368.0>-<477.0,368.0>-<490.5,364.0>>

	* K (U+004B) contains a short segment B<<167.5,271.0>-<158.0,267.0>-<154.0,259.0>>

	* M (U+004D) contains a short segment B<<382.0,349.0>-<388.0,331.0>-<396.0,326.5>>

	* M (U+004D) contains a short segment B<<396.0,326.5>-<404.0,322.0>-<416.0,322.0>>

	* M (U+004D) contains a short segment B<<416.0,322.0>-<428.0,322.0>-<436.0,326.5>>

	* M (U+004D) contains a short segment B<<436.0,326.5>-<444.0,331.0>-<450.0,349.0>>

	* M (U+004D) contains a short segment B<<674.0,370.0>-<667.0,380.0>-<653.5,383.0>>

	* M (U+004D) contains a short segment B<<178.5,383.0>-<165.0,380.0>-<158.0,370.0>>

	* n (U+006E) contains a short segment B<<145.0,416.5>-<148.0,411.0>-<155.0,411.0>>

	* trademark (U+2122) contains a short segment B<<1042.0,349.0>-<1048.0,331.0>-<1056.0,326.5>>

	* trademark (U+2122) contains a short segment B<<1056.0,326.5>-<1064.0,322.0>-<1076.0,322.0>>

	* trademark (U+2122) contains a short segment B<<1076.0,322.0>-<1088.0,322.0>-<1096.0,326.5>>

	* trademark (U+2122) contains a short segment B<<1096.0,326.5>-<1104.0,331.0>-<1110.0,349.0>>

	* trademark (U+2122) contains a short segment B<<1334.0,370.0>-<1327.0,380.0>-<1313.5,383.0>>

	* trademark (U+2122) contains a short segment B<<838.5,383.0>-<825.0,380.0>-<818.0,370.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<67.0,701.0>--<566.0,699.0>>

	* G (U+0047): L<<535.0,680.0>--<534.0,382.0>>

	* P (U+0050): L<<70.0,701.0>--<406.0,699.0>>

	* P (U+0050): L<<73.0,350.0>--<70.0,701.0>>

	* R (U+0052): L<<70.0,701.0>--<406.0,699.0>>

	* R (U+0052): L<<73.0,350.0>--<70.0,701.0>>

	* S (U+0053): L<<511.0,693.0>--<510.0,479.0>>

	* S (U+0053): L<<59.0,9.0>--<58.0,204.0>>

	* U (U+0055): L<<604.0,700.0>--<602.0,302.0>>

	* U (U+0055): L<<68.0,309.0>--<67.0,700.0>>

	* f (U+0066): L<<110.0,0.0>--<111.0,320.0>>

	* u (U+0075): L<<531.0,496.0>--<529.0,224.0>>

	* u (U+0075): L<<54.0,229.0>--<53.0,496.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Ojuju-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
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
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Ojuju-Bold.ttf', 'fonts/ttf/Ojuju-ExtraLight.ttf', 'fonts/ttf/Ojuju-Light.ttf', 'fonts/ttf/Ojuju-Regular.ttf', 'fonts/ttf/Ojuju-SemiBold.ttf', 'fonts/ttf/Ojuju-Medium.ttf', 'fonts/ttf/Ojuju-ExtraBold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 224, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
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

	- Glyph name: hyphen	Expected: 1

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Z	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: k	Expected: 1 or 2

	- Glyph name: w	Expected: 1

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: z	Expected: 1

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Z	Expected: 1

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

	- Glyph name: hyphen	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: k	Expected: 1 or 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: w	Expected: 1

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: z	Expected: 1

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

	- R.alt

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

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

	* B (U+0042): X=168.5,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=220.5,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=272.5,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=346.0,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=317.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=222.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=94.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=419.5,Y=1.5 (should be at baseline 0?)

	* I (U+0049): X=94.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=373.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=236.0,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=94.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=124.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=97.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=373.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=97.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=373.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=579.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=515.0,Y=-1.0 (should be at baseline 0?)

	* b (U+0062): X=84.0,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=394.5,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=314.0,Y=798.0 (should be at ascender 800?)

	* u (U+0075): X=68.0,Y=479.0 (should be at x-height 480?)

	* u (U+0075): X=93.0,Y=479.0 (should be at x-height 480?)

	* u (U+0075): X=479.0,Y=479.0 (should be at x-height 480?)

	* u (U+0075): X=504.0,Y=479.0 (should be at x-height 480?)

	* v (U+0076): X=186.5,Y=1.0 (should be at baseline 0?)

	* v (U+0076): X=352.5,Y=1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=515.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=515.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=515.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=515.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=515.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=515.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=515.0,Y=-1.0 (should be at baseline 0?)

	* uni1EBF (U+1EBF): X=394.5,Y=-0.5 (should be at baseline 0?)

	* uni1EC1 (U+1EC1): X=394.5,Y=-0.5 (should be at baseline 0?)

	* uni1EC5 (U+1EC5): X=394.5,Y=-0.5 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=579.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<141.5,659.5>-<127.0,657.0>-<123.0,650.5>>

	* E (U+0045) contains a short segment B<<123.0,650.5>-<119.0,644.0>-<117.0,633.0>>

	* E (U+0045) contains a short segment B<<117.0,408.0>-<119.0,397.0>-<123.0,390.5>>

	* E (U+0045) contains a short segment B<<123.0,390.5>-<127.0,384.0>-<141.5,381.5>>

	* E (U+0045) contains a short segment B<<140.5,342.5>-<126.0,340.0>-<122.0,334.0>>

	* E (U+0045) contains a short segment B<<122.0,334.0>-<118.0,328.0>-<115.0,316.0>>

	* E (U+0045) contains a short segment B<<115.0,66.0>-<117.0,55.0>-<121.0,48.5>>

	* E (U+0045) contains a short segment B<<121.0,48.5>-<125.0,42.0>-<139.5,39.5>>

	* F (U+0046) contains a short segment B<<124.5,640.0>-<119.0,635.0>-<117.0,629.0>>

	* F (U+0046) contains a short segment B<<119.0,379.0>-<121.0,370.0>-<125.0,365.5>>

	* H (U+0048) contains a short segment B<<115.0,399.0>-<115.0,387.0>-<120.5,380.5>>

	* H (U+0048) contains a short segment B<<509.5,380.5>-<515.0,387.0>-<515.0,399.0>>

	* H (U+0048) contains a short segment B<<515.0,296.0>-<515.0,308.0>-<509.5,314.5>>

	* H (U+0048) contains a short segment B<<120.5,314.5>-<115.0,308.0>-<115.0,296.0>>

	* K (U+004B) contains a short segment L<<578.0,-7.0>--<571.0,-7.0>>

	* L (U+004C) contains a short segment B<<401.5,21.5>-<401.0,19.0>-<401.5,16.5>>

	* M (U+004D) contains a short segment B<<362.5,191.0>-<369.0,177.0>-<375.5,174.0>>

	* M (U+004D) contains a short segment B<<375.5,174.0>-<382.0,171.0>-<391.0,171.0>>

	* M (U+004D) contains a short segment B<<391.0,171.0>-<400.0,171.0>-<406.5,174.0>>

	* M (U+004D) contains a short segment B<<406.5,174.0>-<413.0,177.0>-<419.5,191.0>>

	* M (U+004D) contains a short segment B<<664.0,632.0>-<660.0,652.0>-<647.0,657.0>>

	* M (U+004D) contains a short segment B<<549.0,655.5>-<536.0,649.0>-<532.0,632.0>>

	* M (U+004D) contains a short segment B<<250.0,632.0>-<246.0,649.0>-<233.5,655.5>>

	* M (U+004D) contains a short segment B<<148.0,660.5>-<133.0,659.0>-<127.0,653.0>>

	* M (U+004D) contains a short segment B<<127.0,653.0>-<121.0,647.0>-<118.0,632.0>>

	* v (U+0076) contains a short segment B<<174.0,46.0>-<176.0,40.0>-<180.5,37.0>>

	* v (U+0076) contains a short segment B<<359.0,37.0>-<364.0,40.0>-<365.0,46.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<141.5,659.5>-<127.0,657.0>-<123.0,650.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<123.0,650.5>-<119.0,644.0>-<117.0,633.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<117.0,408.0>-<119.0,397.0>-<123.0,390.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<123.0,390.5>-<127.0,384.0>-<141.5,381.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<140.5,342.5>-<126.0,340.0>-<122.0,334.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<122.0,334.0>-<118.0,328.0>-<115.0,316.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<115.0,66.0>-<117.0,55.0>-<121.0,48.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<121.0,48.5>-<125.0,42.0>-<139.5,39.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<141.5,659.5>-<127.0,657.0>-<123.0,650.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<123.0,650.5>-<119.0,644.0>-<117.0,633.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<117.0,408.0>-<119.0,397.0>-<123.0,390.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<123.0,390.5>-<127.0,384.0>-<141.5,381.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<140.5,342.5>-<126.0,340.0>-<122.0,334.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<122.0,334.0>-<118.0,328.0>-<115.0,316.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<115.0,66.0>-<117.0,55.0>-<121.0,48.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<121.0,48.5>-<125.0,42.0>-<139.5,39.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<141.5,659.5>-<127.0,657.0>-<123.0,650.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<123.0,650.5>-<119.0,644.0>-<117.0,633.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<117.0,408.0>-<119.0,397.0>-<123.0,390.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<123.0,390.5>-<127.0,384.0>-<141.5,381.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<140.5,342.5>-<126.0,340.0>-<122.0,334.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<122.0,334.0>-<118.0,328.0>-<115.0,316.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<115.0,66.0>-<117.0,55.0>-<121.0,48.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<121.0,48.5>-<125.0,42.0>-<139.5,39.5>>

	* trademark (U+2122) contains a short segment B<<981.5,191.0>-<988.0,177.0>-<994.5,174.0>>

	* trademark (U+2122) contains a short segment B<<994.5,174.0>-<1001.0,171.0>-<1010.0,171.0>>

	* trademark (U+2122) contains a short segment B<<1010.0,171.0>-<1019.0,171.0>-<1025.5,174.0>>

	* trademark (U+2122) contains a short segment B<<1025.5,174.0>-<1032.0,177.0>-<1038.5,191.0>>

	* trademark (U+2122) contains a short segment B<<1283.0,632.0>-<1279.0,652.0>-<1266.0,657.0>>

	* trademark (U+2122) contains a short segment B<<1168.0,655.5>-<1155.0,649.0>-<1151.0,632.0>>

	* trademark (U+2122) contains a short segment B<<869.0,632.0>-<865.0,649.0>-<852.5,655.5>>

	* trademark (U+2122) contains a short segment B<<767.0,660.5>-<752.0,659.0>-<746.0,653.0>>

	* trademark (U+2122) contains a short segment B<<746.0,653.0>-<740.0,647.0>-<737.0,632.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194

	* b (U+0062): L<<105.0,700.0>--<105.0,336.0>>/B<<105.0,336.0>-<112.0,375.0>-<136.5,412.0>> = 10.175510843043194

	* g (U+0067): B<<458.5,412.0>-<483.0,375.0>-<490.0,336.0>>/L<<490.0,336.0>--<490.0,480.0>> = 10.175510843043194

	* h (U+0068): B<<105.0,363.5>-<105.0,327.0>-<105.0,313.0>>/B<<105.0,313.0>-<110.0,360.0>-<134.5,401.5>> = 6.0724564072076905

	* m (U+006D): B<<105.5,387.5>-<105.0,347.0>-<105.0,313.0>>/B<<105.0,313.0>-<108.0,348.0>-<117.5,381.5>> = 4.899092453787774

	* m (U+006D): B<<417.5,453.0>-<460.0,412.0>-<466.0,323.0>>/B<<466.0,323.0>-<473.0,368.0>-<495.5,409.0>> = 12.698615545781497

	* ordfeminine (U+00AA): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194

	* p (U+0070): B<<107.5,79.5>-<86.0,118.0>-<77.0,161.0>>/B<<77.0,161.0>-<77.0,70.0>-<77.5,-20.0>> = 11.821488340607226

	* p (U+0070): B<<78.0,427.5>-<78.0,391.0>-<78.0,355.0>>/B<<78.0,355.0>-<88.0,395.0>-<109.5,430.0>> = 14.036243467926484

	* q (U+0071): B<<404.0,430.0>-<426.0,395.0>-<435.0,355.0>>/B<<435.0,355.0>-<435.0,391.0>-<435.0,427.5>> = 12.680383491819796

	* q (U+0071): B<<436.0,-20.0>-<436.0,70.0>-<436.0,161.0>>/B<<436.0,161.0>-<427.0,118.0>-<405.5,79.5>> = 11.821488340607226

	* r (U+0072): B<<105.5,387.5>-<105.0,347.0>-<105.0,313.0>>/B<<105.0,313.0>-<110.0,360.0>-<134.5,401.5>> = 6.0724564072076905

	* uni1EA5 (U+1EA5): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194

	* uni1EA7 (U+1EA7): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194

	* uni1EAB (U+1EAB): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194

	* uni1EAF (U+1EAF): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194

	* uni1EB1 (U+1EB1): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194

	* uni1EB5 (U+1EB5): B<<462.5,412.0>-<487.0,375.0>-<494.0,336.0>>/L<<494.0,336.0>--<494.0,480.0>> = 10.175510843043194 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<94.0,701.0>--<501.0,700.0>>

	* H (U+0048): L<<117.0,700.0>--<115.0,399.0>>

	* H (U+0048): L<<515.0,399.0>--<513.0,700.0>>

	* P (U+0050): L<<100.0,350.0>--<97.0,701.0>>

	* P (U+0050): L<<97.0,701.0>--<373.0,699.0>>

	* R (U+0052): L<<100.0,350.0>--<97.0,701.0>>

	* R (U+0052): L<<97.0,701.0>--<373.0,699.0>>

	* U (U+0055): L<<113.0,700.0>--<111.0,180.0>>

	* U (U+0055): L<<515.0,180.0>--<513.0,700.0>>

	* U (U+0055): L<<534.0,700.0>--<532.0,302.0>>

	* U (U+0055): L<<94.0,302.0>--<92.0,700.0>>

	* f (U+0066): L<<126.0,0.0>--<128.0,466.0>>

	* f (U+0066): L<<151.0,466.0>--<153.0,0.0>>

	* t (U+0074): L<<105.0,496.0>--<104.0,656.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Ojuju-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
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
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Ojuju-Bold.ttf', 'fonts/ttf/Ojuju-ExtraLight.ttf', 'fonts/ttf/Ojuju-Light.ttf', 'fonts/ttf/Ojuju-Regular.ttf', 'fonts/ttf/Ojuju-SemiBold.ttf', 'fonts/ttf/Ojuju-Medium.ttf', 'fonts/ttf/Ojuju-ExtraBold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 224, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
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

	- Glyph name: hyphen	Expected: 1

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Z	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: k	Expected: 1 or 2

	- Glyph name: w	Expected: 1

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: z	Expected: 1

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Z	Expected: 1

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

	- Glyph name: hyphen	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: k	Expected: 1 or 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: w	Expected: 1

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: z	Expected: 1

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

	- R.alt

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

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

	* B (U+0042): X=167.5,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=221.5,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=275.5,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=350.0,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=317.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=221.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=92.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=423.5,Y=1.5 (should be at baseline 0?)

	* I (U+0049): X=92.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=379.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=240.5,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=92.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=126.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=95.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=376.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=95.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=376.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=582.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=493.0,Y=482.0 (should be at x-height 481?)

	* a (U+0061): X=520.0,Y=482.0 (should be at x-height 481?)

	* a (U+0061): X=518.0,Y=-1.0 (should be at baseline 0?)

	* a (U+0061): X=382.0,Y=-1.0 (should be at baseline 0?)

	* b (U+0062): X=217.5,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=82.0,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=391.0,Y=479.0 (should be at x-height 481?)

	* f (U+0066): X=315.0,Y=798.0 (should be at ascender 800?)

	* g (U+0067): X=380.0,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=490.0,Y=482.0 (should be at x-height 481?)

	* g (U+0067): X=517.0,Y=482.0 (should be at x-height 481?)

	* u (U+0075): X=67.0,Y=480.0 (should be at x-height 481?)

	* u (U+0075): X=95.0,Y=480.0 (should be at x-height 481?)

	* u (U+0075): X=478.0,Y=480.0 (should be at x-height 481?)

	* u (U+0075): X=506.0,Y=480.0 (should be at x-height 481?)

	* v (U+0076): X=185.0,Y=1.5 (should be at baseline 0?)

	* v (U+0076): X=355.5,Y=1.5 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=518.0,Y=-1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=382.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=518.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=382.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=518.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=382.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=518.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=382.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=518.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=382.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=518.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=382.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=518.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=382.0,Y=-1.0 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=582.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<147.0,644.0>-<133.0,641.0>-<128.5,635.5>>

	* E (U+0045) contains a short segment B<<128.5,635.5>-<124.0,630.0>-<121.0,619.0>>

	* E (U+0045) contains a short segment B<<121.0,405.0>-<124.0,394.0>-<128.5,388.5>>

	* E (U+0045) contains a short segment B<<128.5,388.5>-<133.0,383.0>-<147.0,380.5>>

	* E (U+0045) contains a short segment B<<147.0,338.5>-<132.0,336.0>-<127.0,330.0>>

	* E (U+0045) contains a short segment B<<127.0,330.0>-<122.0,324.0>-<119.0,313.0>>

	* E (U+0045) contains a short segment B<<119.0,75.0>-<122.0,65.0>-<126.5,59.0>>

	* E (U+0045) contains a short segment B<<126.5,59.0>-<131.0,53.0>-<145.5,50.5>>

	* F (U+0046) contains a short segment B<<129.5,626.0>-<124.0,621.0>-<121.0,615.0>>

	* F (U+0046) contains a short segment B<<123.0,378.0>-<125.0,369.0>-<130.0,364.5>>

	* H (U+0048) contains a short segment B<<118.0,412.0>-<118.0,400.0>-<123.5,393.0>>

	* H (U+0048) contains a short segment B<<513.5,393.0>-<519.0,400.0>-<519.0,412.0>>

	* K (U+004B) contains a short segment B<<267.0,337.0>-<264.0,329.0>-<268.0,315.0>>

	* K (U+004B) contains a short segment B<<584.0,-7.0>-<575.0,-7.0>-<569.0,-7.0>>

	* L (U+004C) contains a short segment B<<406.0,32.5>-<406.0,27.0>-<406.0,21.5>>

	* M (U+004D) contains a short segment B<<364.5,203.0>-<371.0,189.0>-<377.5,186.5>>

	* M (U+004D) contains a short segment B<<377.5,186.5>-<384.0,184.0>-<393.0,184.0>>

	* M (U+004D) contains a short segment B<<393.0,184.0>-<402.0,184.0>-<408.5,186.5>>

	* M (U+004D) contains a short segment B<<408.5,186.5>-<415.0,189.0>-<421.5,203.0>>

	* M (U+004D) contains a short segment B<<665.0,610.0>-<660.0,629.0>-<647.5,634.0>>

	* M (U+004D) contains a short segment B<<550.0,632.5>-<537.0,626.0>-<533.0,610.0>>

	* M (U+004D) contains a short segment B<<254.0,610.0>-<249.0,626.0>-<236.0,632.5>>

	* M (U+004D) contains a short segment B<<138.5,635.0>-<126.0,631.0>-<121.0,610.0>>

	* v (U+0076) contains a short segment B<<172.0,65.0>-<174.0,57.0>-<179.0,54.0>>

	* v (U+0076) contains a short segment B<<362.0,54.0>-<367.0,57.0>-<369.0,65.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<147.0,644.0>-<133.0,641.0>-<128.5,635.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<128.5,635.5>-<124.0,630.0>-<121.0,619.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<121.0,405.0>-<124.0,394.0>-<128.5,388.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<128.5,388.5>-<133.0,383.0>-<147.0,380.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<147.0,338.5>-<132.0,336.0>-<127.0,330.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<127.0,330.0>-<122.0,324.0>-<119.0,313.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<119.0,75.0>-<122.0,65.0>-<126.5,59.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<126.5,59.0>-<131.0,53.0>-<145.5,50.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<147.0,644.0>-<133.0,641.0>-<128.5,635.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<128.5,635.5>-<124.0,630.0>-<121.0,619.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<121.0,405.0>-<124.0,394.0>-<128.5,388.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<128.5,388.5>-<133.0,383.0>-<147.0,380.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<147.0,338.5>-<132.0,336.0>-<127.0,330.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<127.0,330.0>-<122.0,324.0>-<119.0,313.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<119.0,75.0>-<122.0,65.0>-<126.5,59.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<126.5,59.0>-<131.0,53.0>-<145.5,50.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<147.0,644.0>-<133.0,641.0>-<128.5,635.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<128.5,635.5>-<124.0,630.0>-<121.0,619.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<121.0,405.0>-<124.0,394.0>-<128.5,388.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<128.5,388.5>-<133.0,383.0>-<147.0,380.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<147.0,338.5>-<132.0,336.0>-<127.0,330.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<127.0,330.0>-<122.0,324.0>-<119.0,313.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<119.0,75.0>-<122.0,65.0>-<126.5,59.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<126.5,59.0>-<131.0,53.0>-<145.5,50.5>>

	* trademark (U+2122) contains a short segment B<<986.5,203.0>-<993.0,189.0>-<999.5,186.5>>

	* trademark (U+2122) contains a short segment B<<999.5,186.5>-<1006.0,184.0>-<1015.0,184.0>>

	* trademark (U+2122) contains a short segment B<<1015.0,184.0>-<1024.0,184.0>-<1030.5,186.5>>

	* trademark (U+2122) contains a short segment B<<1030.5,186.5>-<1037.0,189.0>-<1043.5,203.0>>

	* trademark (U+2122) contains a short segment B<<1287.0,610.0>-<1282.0,629.0>-<1269.5,634.0>>

	* trademark (U+2122) contains a short segment B<<1172.0,632.5>-<1159.0,626.0>-<1155.0,610.0>>

	* trademark (U+2122) contains a short segment B<<876.0,610.0>-<871.0,626.0>-<858.0,632.5>>

	* trademark (U+2122) contains a short segment B<<760.5,635.0>-<748.0,631.0>-<743.0,610.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194

	* b (U+0062): B<<107.0,395.5>-<107.0,360.0>-<107.0,341.0>>/B<<107.0,341.0>-<115.0,380.0>-<139.5,416.0>> = 11.592175410291041

	* g (U+0067): B<<458.5,415.0>-<483.0,379.0>-<490.0,340.0>>/B<<490.0,340.0>-<490.0,375.0>-<490.0,411.0>> = 10.175510843043194

	* h (U+0068): B<<107.0,369.5>-<107.0,333.0>-<107.0,319.0>>/B<<107.0,319.0>-<112.0,365.0>-<136.5,405.5>> = 6.203447901691829

	* m (U+006D): B<<107.5,393.0>-<107.0,354.0>-<107.0,319.0>>/B<<107.0,319.0>-<111.0,353.0>-<121.0,386.0>> = 6.709836807756896

	* m (U+006D): B<<420.5,455.0>-<463.0,415.0>-<470.0,328.0>>/B<<470.0,328.0>-<477.0,372.0>-<500.0,412.5>> = 13.639578469618403

	* ordfeminine (U+00AA): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194

	* p (U+0070): B<<112.0,75.5>-<90.0,113.0>-<81.0,155.0>>/B<<81.0,155.0>-<81.0,66.0>-<81.0,-22.5>> = 12.094757077012089

	* p (U+0070): B<<82.0,429.5>-<82.0,393.0>-<82.0,358.0>>/B<<82.0,358.0>-<91.0,398.0>-<113.0,432.5>> = 12.680383491819796

	* q (U+0071): B<<406.0,432.5>-<428.0,398.0>-<438.0,358.0>>/B<<438.0,358.0>-<438.0,393.0>-<438.0,429.5>> = 14.036243467926484

	* q (U+0071): B<<438.5,-22.5>-<439.0,66.0>-<439.0,155.0>>/B<<439.0,155.0>-<429.0,113.0>-<407.5,75.5>> = 13.392497753751098

	* r (U+0072): B<<107.5,393.0>-<107.0,354.0>-<107.0,319.0>>/B<<107.0,319.0>-<112.0,365.0>-<136.5,405.5>> = 6.203447901691829

	* uni1EA5 (U+1EA5): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194

	* uni1EA7 (U+1EA7): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194

	* uni1EAB (U+1EAB): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194

	* uni1EAF (U+1EAF): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194

	* uni1EB1 (U+1EB1): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194

	* uni1EB5 (U+1EB5): B<<461.5,415.0>-<486.0,379.0>-<493.0,340.0>>/B<<493.0,340.0>-<493.0,371.0>-<493.0,389.0>> = 10.175510843043194 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<92.0,701.0>--<506.0,700.0>>

	* H (U+0048): L<<120.0,700.0>--<118.0,412.0>>

	* H (U+0048): L<<519.0,412.0>--<517.0,700.0>>

	* P (U+0050): L<<95.0,701.0>--<376.0,699.0>>

	* P (U+0050): L<<98.0,350.0>--<95.0,701.0>>

	* R (U+0052): L<<95.0,701.0>--<376.0,699.0>>

	* R (U+0052): L<<98.0,350.0>--<95.0,701.0>>

	* U (U+0055): L<<117.0,700.0>--<115.0,199.0>>

	* U (U+0055): L<<515.0,199.0>--<513.0,700.0>>

	* U (U+0055): L<<540.0,700.0>--<538.0,302.0>>

	* U (U+0055): L<<92.0,303.0>--<90.0,700.0>>

	* f (U+0066): L<<125.0,0.0>--<127.0,454.0>>

	* f (U+0066): L<<153.0,454.0>--<155.0,0.0>>

	* t (U+0074): L<<105.0,496.0>--<104.0,656.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Ojuju-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
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
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Ojuju-Bold.ttf', 'fonts/ttf/Ojuju-ExtraLight.ttf', 'fonts/ttf/Ojuju-Light.ttf', 'fonts/ttf/Ojuju-Regular.ttf', 'fonts/ttf/Ojuju-SemiBold.ttf', 'fonts/ttf/Ojuju-Medium.ttf', 'fonts/ttf/Ojuju-ExtraBold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 224, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
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

	- Glyph name: hyphen	Expected: 1

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Z	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: k	Expected: 1 or 2

	- Glyph name: w	Expected: 1

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: z	Expected: 1

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Z	Expected: 1

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

	- Glyph name: hyphen	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: k	Expected: 1 or 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: w	Expected: 1

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: z	Expected: 1

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

	- R.alt

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

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

	* B (U+0042): X=224.0,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=284.0,Y=699.0 (should be at cap-height 700?)

	* B (U+0042): X=361.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=460.0,Y=699.5 (should be at cap-height 700?)

	* D (U+0044): X=317.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=218.0,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=86.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=433.5,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=86.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=393.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=86.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=132.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=89.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=383.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=414.0,Y=-2.0 (should be at baseline 0?)

	* R (U+0052): X=89.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=383.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=591.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=526.0,Y=-1.0 (should be at baseline 0?)

	* b (U+0062): X=77.0,Y=-1.0 (should be at baseline 0?)

	* d (U+0064): X=129.5,Y=483.0 (should be at x-height 485?)

	* d (U+0064): X=341.5,Y=483.5 (should be at x-height 485?)

	* f (U+0066): X=317.0,Y=798.0 (should be at ascender 800?)

	* g (U+0067): X=377.5,Y=-2.0 (should be at baseline 0?)

	* u (U+0075): X=64.0,Y=484.0 (should be at x-height 485?)

	* u (U+0075): X=101.0,Y=484.0 (should be at x-height 485?)

	* u (U+0075): X=474.0,Y=484.0 (should be at x-height 485?)

	* u (U+0075): X=512.0,Y=484.0 (should be at x-height 485?)

	* ordfeminine (U+00AA): X=526.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=526.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=526.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=526.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=526.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=526.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=526.0,Y=-1.0 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=591.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<129.0,99.0>-<133.0,90.0>-<139.5,84.5>>

	* F (U+0046) contains a short segment B<<133.0,374.0>-<136.0,367.0>-<142.0,363.0>>

	* I (U+0049) contains a short segment B<<209.0,596.0>-<204.0,601.0>-<197.0,604.0>>

	* K (U+004B) contains a short segment B<<279.5,340.5>-<276.0,333.0>-<279.0,319.0>>

	* K (U+004B) contains a short segment B<<238.0,308.0>-<234.0,321.0>-<225.5,324.5>>

	* M (U+004D) contains a short segment B<<364.5,246.5>-<372.0,224.0>-<379.5,219.5>>

	* M (U+004D) contains a short segment B<<379.5,219.5>-<387.0,215.0>-<398.0,215.0>>

	* M (U+004D) contains a short segment B<<398.0,215.0>-<409.0,215.0>-<417.0,219.5>>

	* M (U+004D) contains a short segment B<<417.0,219.5>-<425.0,224.0>-<432.5,246.5>>

	* M (U+004D) contains a short segment B<<667.0,556.0>-<662.0,573.0>-<649.0,577.5>>

	* M (U+004D) contains a short segment B<<553.5,576.0>-<540.0,570.0>-<534.0,555.0>>

	* M (U+004D) contains a short segment B<<262.0,555.0>-<257.0,570.0>-<243.0,576.0>>

	* M (U+004D) contains a short segment B<<148.0,578.0>-<135.0,574.0>-<130.0,556.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<129.0,99.0>-<133.0,90.0>-<139.5,84.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<129.0,99.0>-<133.0,90.0>-<139.5,84.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<129.0,99.0>-<133.0,90.0>-<139.5,84.5>>

	* trademark (U+2122) contains a short segment B<<995.5,246.5>-<1003.0,224.0>-<1010.5,219.5>>

	* trademark (U+2122) contains a short segment B<<1010.5,219.5>-<1018.0,215.0>-<1029.0,215.0>>

	* trademark (U+2122) contains a short segment B<<1029.0,215.0>-<1040.0,215.0>-<1048.0,219.5>>

	* trademark (U+2122) contains a short segment B<<1048.0,219.5>-<1056.0,224.0>-<1063.5,246.5>>

	* trademark (U+2122) contains a short segment B<<1298.0,556.0>-<1293.0,573.0>-<1280.0,577.5>>

	* trademark (U+2122) contains a short segment B<<1184.5,576.0>-<1171.0,570.0>-<1165.0,555.0>>

	* trademark (U+2122) contains a short segment B<<893.0,555.0>-<888.0,570.0>-<874.0,576.0>>

	* trademark (U+2122) contains a short segment B<<779.0,578.0>-<766.0,574.0>-<761.0,556.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786

	* b (U+0062): B<<112.0,425.0>-<112.0,379.0>-<112.0,352.0>>/B<<112.0,352.0>-<121.0,392.0>-<146.5,426.0>> = 12.680383491819796

	* g (U+0067): B<<457.5,423.0>-<481.0,389.0>-<490.0,351.0>>/B<<490.0,351.0>-<490.0,382.0>-<489.5,418.5>> = 13.324531261890783

	* h (U+0068): B<<113.0,385.0>-<113.0,349.0>-<113.0,334.0>>/B<<113.0,334.0>-<119.0,378.0>-<143.5,416.0>> = 7.765166018425308

	* m (U+006D): B<<112.5,406.5>-<112.0,371.0>-<112.0,334.0>>/B<<112.0,334.0>-<118.0,378.0>-<136.5,417.0>> = 7.765166018425308

	* ordfeminine (U+00AA): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786

	* q (U+0071): B<<412.5,438.5>-<436.0,406.0>-<445.0,367.0>>/B<<445.0,367.0>-<445.0,397.0>-<445.0,433.5>> = 12.994616791916512

	* r (U+0072): B<<112.5,406.5>-<112.0,371.0>-<112.0,334.0>>/B<<112.0,334.0>-<118.0,378.0>-<142.5,416.0>> = 7.765166018425308

	* uni1EA5 (U+1EA5): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786

	* uni1EA7 (U+1EA7): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786

	* uni1EAB (U+1EAB): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786

	* uni1EAF (U+1EAF): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786

	* uni1EB1 (U+1EB1): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786

	* uni1EB5 (U+1EB5): B<<460.0,422.5>-<484.0,388.0>-<492.0,351.0>>/B<<492.0,351.0>-<492.0,378.0>-<491.5,396.5>> = 12.200468727380786 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<86.0,701.0>--<520.0,700.0>>

	* G (U+0047): L<<506.0,682.0>--<505.0,559.0>>

	* H (U+0048): L<<128.0,700.0>--<126.0,443.0>>

	* P (U+0050): L<<89.0,701.0>--<383.0,699.0>>

	* P (U+0050): L<<92.0,350.0>--<89.0,701.0>>

	* R (U+0052): L<<89.0,701.0>--<383.0,699.0>>

	* R (U+0052): L<<92.0,350.0>--<89.0,701.0>>

	* U (U+0055): L<<127.0,700.0>--<124.0,246.0>>

	* U (U+0055): L<<514.0,246.0>--<512.0,700.0>>

	* U (U+0055): L<<554.0,700.0>--<552.0,302.0>>

	* U (U+0055): L<<87.0,304.0>--<85.0,700.0>>

	* f (U+0066): L<<121.0,0.0>--<123.0,424.0>>

	* f (U+0066): L<<159.0,424.0>--<161.0,0.0>>

	* t (U+0074): L<<105.0,497.0>--<104.0,655.0>>

	* t (U+0074): L<<142.0,424.0>--<141.0,235.0>>

	* u (U+0075): L<<65.0,282.0>--<64.0,484.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Ojuju-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
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
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Ojuju-Bold.ttf', 'fonts/ttf/Ojuju-ExtraLight.ttf', 'fonts/ttf/Ojuju-Light.ttf', 'fonts/ttf/Ojuju-Regular.ttf', 'fonts/ttf/Ojuju-SemiBold.ttf', 'fonts/ttf/Ojuju-Medium.ttf', 'fonts/ttf/Ojuju-ExtraBold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 224, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
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

	- Glyph name: hyphen	Expected: 1

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Z	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: k	Expected: 1 or 2

	- Glyph name: w	Expected: 1

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: z	Expected: 1

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Z	Expected: 1

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

	- Glyph name: hyphen	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: k	Expected: 1 or 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: w	Expected: 1

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: z	Expected: 1

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

	- R.alt

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

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

	* exclam (U+0021): X=83.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=271.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=74.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=388.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=479.5,Y=698.5 (should be at cap-height 700?)

	* F (U+0046): X=73.0,Y=701.0 (should be at cap-height 700?)

	* F (U+0046): X=552.0,Y=699.0 (should be at cap-height 700?)

	* G (U+0047): X=463.5,Y=702.0 (should be at cap-height 700?)

	* G (U+0047): X=457.0,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=73.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=426.0,Y=699.0 (should be at cap-height 700?)

	* K (U+004B): X=630.0,Y=-2.0 (should be at baseline 0?)

	* L (U+004C): X=73.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=146.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=76.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=399.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=76.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=399.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=611.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=486.0,Y=494.0 (should be at x-height 493?)

	* a (U+0061): X=546.0,Y=494.0 (should be at x-height 493?)

	* f (U+0066): X=321.0,Y=799.0 (should be at ascender 800?)

	* g (U+0067): X=468.0,Y=-2.0 (should be at baseline 0?)

	* g (U+0067): X=392.5,Y=1.0 (should be at baseline 0?)

	* g (U+0067): X=487.0,Y=494.0 (should be at x-height 493?)

	* g (U+0067): X=547.0,Y=494.0 (should be at x-height 493?)

	* l (U+006C): X=275.5,Y=494.5 (should be at x-height 493?)

	* t (U+0074): X=404.5,Y=-1.0 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=611.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* B (U+0042) contains a short segment B<<466.0,367.0>-<466.0,367.0>-<479.5,363.0>>

	* E (U+0045) contains a short segment B<<155.0,381.0>-<163.0,374.0>-<175.0,370.5>>

	* K (U+004B) contains a short segment B<<162.5,287.5>-<152.0,284.0>-<148.0,274.0>>

	* M (U+004D) contains a short segment B<<376.5,317.5>-<383.0,298.0>-<391.0,293.5>>

	* M (U+004D) contains a short segment B<<391.0,293.5>-<399.0,289.0>-<410.0,289.0>>

	* M (U+004D) contains a short segment B<<410.0,289.0>-<422.0,289.0>-<430.0,293.5>>

	* M (U+004D) contains a short segment B<<430.0,293.5>-<438.0,298.0>-<444.5,317.5>>

	* M (U+004D) contains a short segment B<<672.0,427.0>-<665.0,439.0>-<652.0,442.5>>

	* M (U+004D) contains a short segment B<<561.5,441.0>-<546.0,436.0>-<538.0,424.0>>

	* M (U+004D) contains a short segment B<<283.0,424.0>-<275.0,436.0>-<259.5,441.0>>

	* M (U+004D) contains a short segment B<<169.0,442.5>-<156.0,439.0>-<149.0,427.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<155.0,381.0>-<163.0,374.0>-<175.0,370.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<155.0,381.0>-<163.0,374.0>-<175.0,370.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<155.0,381.0>-<163.0,374.0>-<175.0,370.5>>

	* trademark (U+2122) contains a short segment B<<1027.5,317.5>-<1034.0,298.0>-<1042.0,293.5>>

	* trademark (U+2122) contains a short segment B<<1042.0,293.5>-<1050.0,289.0>-<1061.0,289.0>>

	* trademark (U+2122) contains a short segment B<<1061.0,289.0>-<1073.0,289.0>-<1081.0,293.5>>

	* trademark (U+2122) contains a short segment B<<1081.0,293.5>-<1089.0,298.0>-<1095.5,317.5>>

	* trademark (U+2122) contains a short segment B<<1323.0,427.0>-<1316.0,439.0>-<1303.0,442.5>>

	* trademark (U+2122) contains a short segment B<<1212.5,441.0>-<1197.0,436.0>-<1189.0,424.0>>

	* trademark (U+2122) contains a short segment B<<934.0,424.0>-<926.0,436.0>-<910.5,441.0>>

	* trademark (U+2122) contains a short segment B<<820.0,442.5>-<807.0,439.0>-<800.0,427.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* h (U+0068): B<<126.0,421.5>-<126.0,386.0>-<126.0,369.0>>/B<<126.0,369.0>-<141.0,430.0>-<187.5,468.5>> = 13.81502534126161

	* m (U+006D): B<<124.5,439.0>-<123.0,412.0>-<123.0,369.0>>/B<<123.0,369.0>-<133.0,410.0>-<155.0,441.5>> = 13.706961004079783

	* r (U+0072): B<<124.5,439.0>-<123.0,412.0>-<123.0,369.0>>/B<<123.0,369.0>-<138.0,430.0>-<184.5,468.5>> = 13.81502534126161 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<73.0,701.0>--<552.0,699.0>>

	* G (U+0047): L<<526.0,681.0>--<525.0,436.0>>

	* P (U+0050): L<<76.0,701.0>--<399.0,699.0>>

	* P (U+0050): L<<79.0,350.0>--<76.0,701.0>>

	* R (U+0052): L<<76.0,701.0>--<399.0,699.0>>

	* R (U+0052): L<<79.0,350.0>--<76.0,701.0>>

	* S (U+0053): L<<57.0,10.0>--<56.0,173.0>>

	* U (U+0055): L<<589.0,700.0>--<587.0,302.0>>

	* U (U+0055): L<<74.0,307.0>--<73.0,700.0>>

	* f (U+0066): L<<172.0,352.0>--<175.0,0.0>>

	* u (U+0075): L<<525.0,493.0>--<523.0,241.0>>

	* u (U+0075): L<<58.0,245.0>--<56.0,493.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Ojuju-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
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
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Ojuju-Bold.ttf', 'fonts/ttf/Ojuju-ExtraLight.ttf', 'fonts/ttf/Ojuju-Light.ttf', 'fonts/ttf/Ojuju-Regular.ttf', 'fonts/ttf/Ojuju-SemiBold.ttf', 'fonts/ttf/Ojuju-Medium.ttf', 'fonts/ttf/Ojuju-ExtraBold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 224, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
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

	- Glyph name: hyphen	Expected: 1

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Z	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: k	Expected: 1 or 2

	- Glyph name: w	Expected: 1

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: z	Expected: 1

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Z	Expected: 1

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

	- Glyph name: hyphen	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: k	Expected: 1 or 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: w	Expected: 1

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: z	Expected: 1

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

	- R.alt

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

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

	* exclam (U+0021): X=257.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=98.0,Y=-1.5 (should be at baseline 0?)

	* exclam (U+0021): X=264.0,Y=-1.5 (should be at baseline 0?)

	* period (U+002E): X=96.5,Y=-1.5 (should be at baseline 0?)

	* period (U+002E): X=262.0,Y=-1.5 (should be at baseline 0?)

	* B (U+0042): X=294.0,Y=699.5 (should be at cap-height 700?)

	* B (U+0042): X=374.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=469.5,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=317.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=214.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=80.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=445.0,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=80.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=409.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=80.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=139.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=83.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=390.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=512.5,Y=-2.0 (should be at baseline 0?)

	* R (U+0052): X=83.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=390.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=601.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=488.0,Y=490.0 (should be at x-height 489?)

	* a (U+0061): X=536.0,Y=490.0 (should be at x-height 489?)

	* a (U+0061): X=535.0,Y=-1.0 (should be at baseline 0?)

	* b (U+0062): X=72.0,Y=-1.0 (should be at baseline 0?)

	* f (U+0066): X=319.0,Y=798.0 (should be at ascender 800?)

	* g (U+0067): X=488.0,Y=490.0 (should be at x-height 489?)

	* g (U+0067): X=536.0,Y=490.0 (should be at x-height 489?)

	* t (U+0074): X=391.5,Y=-2.0 (should be at baseline 0?)

	* u (U+0075): X=60.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=108.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=470.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=518.0,Y=488.0 (should be at x-height 489?)

	* ordfeminine (U+00AA): X=535.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=535.0,Y=-1.0 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=535.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=535.0,Y=-1.0 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=535.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=535.0,Y=-1.0 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=535.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=96.5,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=262.0,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=96.5,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=262.0,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=96.5,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=262.0,Y=-1.5 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=601.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* E (U+0045) contains a short segment B<<142.0,545.0>-<137.0,540.0>-<134.0,525.0>>

	* E (U+0045) contains a short segment B<<134.5,410.0>-<138.0,395.0>-<143.0,390.0>>

	* E (U+0045) contains a short segment B<<143.0,390.0>-<149.0,380.0>-<159.5,375.5>>

	* K (U+004B) contains a short segment B<<235.0,291.0>-<231.0,303.0>-<223.0,306.5>>

	* K (U+004B) contains a short segment B<<156.5,306.5>-<145.0,303.0>-<141.0,292.0>>

	* M (U+004D) contains a short segment B<<370.0,281.0>-<377.0,260.0>-<385.0,255.0>>

	* M (U+004D) contains a short segment B<<385.0,255.0>-<393.0,250.0>-<404.0,250.0>>

	* M (U+004D) contains a short segment B<<404.0,250.0>-<415.0,250.0>-<423.0,255.0>>

	* M (U+004D) contains a short segment B<<423.0,255.0>-<431.0,260.0>-<438.0,281.0>>

	* M (U+004D) contains a short segment B<<669.0,494.0>-<663.0,508.0>-<650.0,512.5>>

	* M (U+004D) contains a short segment B<<557.5,511.0>-<543.0,505.0>-<536.0,492.0>>

	* M (U+004D) contains a short segment B<<272.0,492.0>-<266.0,505.0>-<251.0,511.0>>

	* M (U+004D) contains a short segment B<<158.0,513.5>-<145.0,510.0>-<139.0,494.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<142.0,545.0>-<137.0,540.0>-<134.0,525.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<134.5,410.0>-<138.0,395.0>-<143.0,390.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<143.0,390.0>-<149.0,380.0>-<159.5,375.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<142.0,545.0>-<137.0,540.0>-<134.0,525.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<134.5,410.0>-<138.0,395.0>-<143.0,390.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<143.0,390.0>-<149.0,380.0>-<159.5,375.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<142.0,545.0>-<137.0,540.0>-<134.0,525.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<134.5,410.0>-<138.0,395.0>-<143.0,390.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<143.0,390.0>-<149.0,380.0>-<159.5,375.5>>

	* trademark (U+2122) contains a short segment B<<1011.0,281.0>-<1018.0,260.0>-<1026.0,255.0>>

	* trademark (U+2122) contains a short segment B<<1026.0,255.0>-<1034.0,250.0>-<1045.0,250.0>>

	* trademark (U+2122) contains a short segment B<<1045.0,250.0>-<1056.0,250.0>-<1064.0,255.0>>

	* trademark (U+2122) contains a short segment B<<1064.0,255.0>-<1072.0,260.0>-<1079.0,281.0>>

	* trademark (U+2122) contains a short segment B<<1310.0,494.0>-<1304.0,508.0>-<1291.0,512.5>>

	* trademark (U+2122) contains a short segment B<<1198.5,511.0>-<1184.0,505.0>-<1177.0,492.0>>

	* trademark (U+2122) contains a short segment B<<913.0,492.0>-<907.0,505.0>-<892.0,511.0>>

	* trademark (U+2122) contains a short segment B<<799.0,513.5>-<786.0,510.0>-<780.0,494.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184

	* g (U+0067): B<<457.0,432.0>-<480.0,400.0>-<489.0,364.0>>/B<<489.0,364.0>-<489.0,389.0>-<488.5,426.0>> = 14.036243467926484

	* h (U+0068): B<<119.0,402.5>-<119.0,367.0>-<119.0,351.0>>/B<<119.0,351.0>-<131.0,415.0>-<179.5,459.0>> = 10.61965527615514

	* m (U+006D): B<<118.0,422.0>-<117.0,391.0>-<117.0,351.0>>/B<<117.0,351.0>-<125.0,393.0>-<145.5,428.5>> = 10.784297867562596

	* ordfeminine (U+00AA): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184

	* r (U+0072): B<<118.0,422.0>-<117.0,391.0>-<117.0,351.0>>/B<<117.0,351.0>-<130.0,415.0>-<178.0,459.0>> = 11.481991354748077

	* uni1EA5 (U+1EA5): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184

	* uni1EA7 (U+1EA7): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184

	* uni1EAB (U+1EAB): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184

	* uni1EAF (U+1EAF): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184

	* uni1EB1 (U+1EB1): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184

	* uni1EB5 (U+1EB5): B<<458.5,430.5>-<482.0,398.0>-<490.0,364.0>>/B<<490.0,364.0>-<490.0,396.0>-<489.0,424.0>> = 13.240519915187184 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<536.0,700.0>--<535.0,562.0>>

	* F (U+0046): L<<80.0,701.0>--<536.0,700.0>>

	* P (U+0050): L<<83.0,701.0>--<390.0,699.0>>

	* P (U+0050): L<<86.0,350.0>--<83.0,701.0>>

	* R (U+0052): L<<83.0,701.0>--<390.0,699.0>>

	* R (U+0052): L<<86.0,350.0>--<83.0,701.0>>

	* S (U+0053): L<<55.0,12.0>--<54.0,135.0>>

	* U (U+0055): L<<571.0,700.0>--<569.0,302.0>>

	* U (U+0055): L<<80.0,305.0>--<79.0,700.0>>

	* f (U+0066): L<<118.0,0.0>--<119.0,389.0>>

	* f (U+0066): L<<165.0,389.0>--<168.0,0.0>>

	* t (U+0074): L<<105.0,498.0>--<104.0,653.0>>

	* t (U+0074): L<<106.0,248.0>--<105.0,388.0>>

	* t (U+0074): L<<152.0,389.0>--<151.0,242.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[24] Ojuju-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
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
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Ojuju-Bold.ttf', 'fonts/ttf/Ojuju-ExtraLight.ttf', 'fonts/ttf/Ojuju-Light.ttf', 'fonts/ttf/Ojuju-Regular.ttf', 'fonts/ttf/Ojuju-SemiBold.ttf', 'fonts/ttf/Ojuju-Medium.ttf', 'fonts/ttf/Ojuju-ExtraBold.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 224, but got 200 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (800) and hhea ascent (1000) must be equal. [code: ascender]
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

	- Glyph name: hyphen	Expected: 1

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Z	Expected: 1

	- Glyph name: bracketleft	Expected: 1

	- Glyph name: backslash	Expected: 1

	- Glyph name: bracketright	Expected: 1

	- Glyph name: asciicircum	Expected: 1

	- Glyph name: underscore	Expected: 1

	- Glyph name: k	Expected: 1 or 2

	- Glyph name: w	Expected: 1

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: z	Expected: 1

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

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

	- Glyph name: Cdotaccent	Expected: 2

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

	- Glyph name: W	Expected: 1 or 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: Wcircumflex	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: X	Expected: 1

	- Glyph name: Y	Expected: 1

	- Glyph name: Yacute	Expected: 2

	- Glyph name: Ycircumflex	Expected: 2

	- Glyph name: Ydieresis	Expected: 3

	- Glyph name: Ygrave	Expected: 2

	- Glyph name: Z	Expected: 1

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

	- Glyph name: hyphen	Expected: 1

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: k	Expected: 1 or 2

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

	- Glyph name: uni1EF8	Expected: 2

	- Glyph name: uni1EF9	Expected: 2

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: w	Expected: 1

	- Glyph name: wacute	Expected: 2

	- Glyph name: wcircumflex	Expected: 2

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: wgrave	Expected: 2

	- Glyph name: x	Expected: 1

	- Glyph name: y	Expected: 1

	- Glyph name: yacute	Expected: 2

	- Glyph name: ycircumflex	Expected: 2

	- Glyph name: ydieresis	Expected: 3

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: ygrave	Expected: 2

	- Glyph name: z	Expected: 1

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

	- R.alt

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

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

	* B (U+0042): X=236.0,Y=700.5 (should be at cap-height 700?)

	* B (U+0042): X=410.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=497.0,Y=698.0 (should be at cap-height 700?)

	* C (U+0043): X=449.5,Y=-2.0 (should be at baseline 0?)

	* F (U+0046): X=62.0,Y=701.0 (should be at cap-height 700?)

	* F (U+0046): X=580.0,Y=699.0 (should be at cap-height 700?)

	* G (U+0047): X=481.0,Y=702.0 (should be at cap-height 700?)

	* I (U+0049): X=62.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=455.0,Y=699.0 (should be at cap-height 700?)

	* J (U+004A): X=75.0,Y=2.0 (should be at baseline 0?)

	* L (U+004C): X=62.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=158.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=65.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=413.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=65.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=413.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=629.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=388.0,Y=498.5 (should be at x-height 500?)

	* a (U+0061): X=481.0,Y=502.0 (should be at x-height 500?)

	* a (U+0061): X=561.0,Y=502.0 (should be at x-height 500?)

	* a (U+0061): X=402.0,Y=1.5 (should be at baseline 0?)

	* f (U+0066): X=104.0,Y=501.0 (should be at x-height 500?)

	* f (U+0066): X=325.0,Y=799.0 (should be at ascender 800?)

	* g (U+0067): X=394.5,Y=499.5 (should be at x-height 500?)

	* g (U+0067): X=485.0,Y=502.0 (should be at x-height 500?)

	* g (U+0067): X=565.0,Y=502.0 (should be at x-height 500?)

	* g (U+0067): X=383.0,Y=-198.0 (should be at descender -200?)

	* n (U+006E): X=458.0,Y=501.0 (should be at x-height 500?)

	* s (U+0073): X=364.0,Y=1.5 (should be at baseline 0?)

	* t (U+0074): X=425.5,Y=0.5 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=402.0,Y=1.5 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=402.0,Y=1.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=402.0,Y=1.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=402.0,Y=1.5 (should be at baseline 0?)

	* uni1EAF (U+1EAF): X=402.0,Y=1.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=402.0,Y=1.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=402.0,Y=1.5 (should be at baseline 0?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=629.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* B (U+0042) contains a short segment B<<501.0,371.5>-<487.0,368.0>-<487.0,368.0>>

	* B (U+0042) contains a short segment B<<487.0,368.0>-<487.0,368.0>-<501.0,364.5>>

	* G (U+0047) contains a short segment B<<452.0,210.0>-<455.0,211.0>-<455.0,225.5>>

	* K (U+004B) contains a short segment B<<329.0,337.0>-<329.0,329.0>-<341.5,321.5>>

	* K (U+004B) contains a short segment B<<238.5,224.5>-<235.0,236.0>-<228.0,244.0>>

	* M (U+004D) contains a short segment B<<387.0,378.0>-<392.0,361.0>-<400.5,357.0>>

	* M (U+004D) contains a short segment B<<400.5,357.0>-<409.0,353.0>-<421.0,353.0>>

	* M (U+004D) contains a short segment B<<421.0,353.0>-<433.0,353.0>-<441.5,357.0>>

	* M (U+004D) contains a short segment B<<441.5,357.0>-<450.0,361.0>-<455.0,378.0>>

	* M (U+004D) contains a short segment B<<676.0,316.0>-<669.0,324.0>-<655.0,326.5>>

	* M (U+004D) contains a short segment B<<187.5,326.5>-<174.0,324.0>-<166.0,316.0>>

	* n (U+006E) contains a short segment B<<150.5,417.5>-<154.0,412.0>-<162.0,412.0>>

	* s (U+0073) contains a short segment B<<364.0,162.0>-<364.0,168.0>-<356.0,171.5>>

	* trademark (U+2122) contains a short segment B<<1056.0,378.0>-<1061.0,361.0>-<1069.5,357.0>>

	* trademark (U+2122) contains a short segment B<<1069.5,357.0>-<1078.0,353.0>-<1090.0,353.0>>

	* trademark (U+2122) contains a short segment B<<1090.0,353.0>-<1102.0,353.0>-<1110.5,357.0>>

	* trademark (U+2122) contains a short segment B<<1110.5,357.0>-<1119.0,361.0>-<1124.0,378.0>>

	* trademark (U+2122) contains a short segment B<<1345.0,316.0>-<1338.0,324.0>-<1324.0,326.5>>

	* trademark (U+2122) contains a short segment B<<856.5,326.5>-<843.0,324.0>-<835.0,316.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484

	* ordfeminine (U+00AA): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484

	* uni1EA5 (U+1EA5): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484

	* uni1EA7 (U+1EA7): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484

	* uni1EAB (U+1EAB): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484

	* uni1EAF (U+1EAF): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484

	* uni1EB1 (U+1EB1): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484

	* uni1EB5 (U+1EB5): B<<454.0,454.5>-<477.0,428.0>-<484.0,400.0>>/B<<484.0,400.0>-<484.0,408.0>-<483.5,429.0>> = 14.036243467926484 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* F (U+0046): L<<62.0,701.0>--<580.0,699.0>>

	* P (U+0050): L<<65.0,701.0>--<413.0,699.0>>

	* P (U+0050): L<<68.0,350.0>--<65.0,701.0>>

	* R (U+0052): L<<65.0,701.0>--<413.0,699.0>>

	* R (U+0052): L<<68.0,350.0>--<65.0,701.0>>

	* S (U+0053): L<<61.0,7.0>--<60.0,234.0>>

	* U (U+0055): L<<619.0,700.0>--<616.0,302.0>>

	* U (U+0055): L<<63.0,310.0>--<62.0,700.0>>

	* u (U+0075): L<<51.0,213.0>--<50.0,500.0>>

	* u (U+0075): L<<536.0,500.0>--<535.0,207.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 14 | 84 | 69 | 863 | 36 | 575 | 0 |
| 1% | 5% | 4% | 53% | 2% | 35% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
