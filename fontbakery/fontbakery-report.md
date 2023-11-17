## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[22] Ojuju-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 460, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

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

	- Glyph name: grave	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: macron	Expected: 1

	- Glyph name: degree	Expected: 2

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: cedilla	Expected: 1

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

	- Glyph name: Itilde	Expected: 2

	- Glyph name: itilde	Expected: 2

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

	- Glyph name: Utilde	Expected: 2

	- Glyph name: utilde	Expected: 2

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EA	Expected: 2

	- Glyph name: uni01EB	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F4	Expected: 2

	- Glyph name: uni01F5	Expected: 3

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: Oslashacute	Expected: 4

	- Glyph name: oslashacute	Expected: 4

	- Glyph name: uni0200	Expected: 4

	- Glyph name: uni0201	Expected: 4

	- Glyph name: uni0202	Expected: 3

	- Glyph name: uni0203	Expected: 3

	- Glyph name: uni0204	Expected: 3

	- Glyph name: uni0205	Expected: 4

	- Glyph name: uni0206	Expected: 2

	- Glyph name: uni0207	Expected: 3

	- Glyph name: uni0208	Expected: 3

	- Glyph name: uni0209	Expected: 3

	- Glyph name: uni020A	Expected: 2

	- Glyph name: uni020B	Expected: 2

	- Glyph name: uni020C	Expected: 4

	- Glyph name: uni020D	Expected: 4

	- Glyph name: uni020E	Expected: 3

	- Glyph name: uni020F	Expected: 3

	- Glyph name: uni0210	Expected: 4

	- Glyph name: uni0211	Expected: 3

	- Glyph name: uni0212	Expected: 3

	- Glyph name: uni0213	Expected: 2

	- Glyph name: uni0214	Expected: 3

	- Glyph name: uni0215	Expected: 3

	- Glyph name: uni0216	Expected: 2

	- Glyph name: uni0217	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: gravecomb	Expected: 1

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: hookabovecomb	Expected: 1

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: dotbelowcomb	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: Dmacronbelow	Expected: 3

	- Glyph name: dmacronbelow	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E1F	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: Lmacronbelow	Expected: 2

	- Glyph name: lmacronbelow	Expected: 2

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: Nmacronbelow	Expected: 2

	- Glyph name: nmacronbelow	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: Rmacronbelow	Expected: 3

	- Glyph name: rmacronbelow	Expected: 2

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: Tmacronbelow	Expected: 2

	- Glyph name: tmacronbelow	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni207F	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

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

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Itilde	Expected: 2

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

	- Glyph name: Oslashacute	Expected: 4

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

	- Glyph name: Utilde	Expected: 2

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

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

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

	- Glyph name: breve	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: circumflex	Expected: 1

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: itilde	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: oslashacute	Expected: 4

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

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: utilde	Expected: 2

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
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, syriac, tai-le, canadian-aboriginal, coptic, malayalam, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, cherokee, syriac, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: myanmar, masaram-gondi, gunjala-gondi, syloti-nagri, chakma, bengali, sharada, tamil, tibetan, tagalog, miao, marchen, sundanese, zanabazar-square, thai, newa, dogra, grantha, mongolian, hebrew, takri, soyombo, nko, devanagari, brahmi, symbols, syriac, oriya, mandaic, psalter-pahlavi, rejang, sogdian, khmer, caucasian-albanian, cham, khojki, osage, meetei-mayek, tai-le, phags-pa, kannada, tirhuta, javanese, hanunoo, hanifi-rohingya, kharoshthi, old-permic, lao, mahajani, music, lepcha, gurmukhi, modi, siddham, buhid, adlam, duployan, manichaean, mende-kikakui, telugu, tagbanwa, sinhala, tai-viet, yi, coptic, wancho, malayalam, math, pahawh-hmong, khudawadi, thaana, tifinagh, bassa-vah, batak, ahom, kaithi, limbu, elbasan, gujarati, bhaiksuki, new-tai-lue, balinese, buginese, kayah-li
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* one (U+0031): X=225.0,Y=700.5 (should be at cap-height 700?)

	* one (U+0031): X=295.0,Y=700.5 (should be at cap-height 700?)

	* six (U+0036): X=526.5,Y=701.0 (should be at cap-height 700?)

	* nine (U+0039): X=341.5,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=344.0,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=313.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=218.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=90.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=448.5,Y=702.0 (should be at cap-height 700?)

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

	* R (U+0052): X=299.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=559.0,Y=-1.0 (should be at baseline 0?)

	* T (U+0054): X=40.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=579.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=359.0,Y=480.5 (should be at x-height 480?)

	* a (U+0061): X=359.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=234.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=234.0,Y=480.5 (should be at x-height 480?)

	* d (U+0064): X=359.0,Y=480.5 (should be at x-height 480?)

	* d (U+0064): X=359.0,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=131.5,Y=698.5 (should be at cap-height 700?)

	* f (U+0066): X=245.0,Y=741.0 (should be at ascender 740?)

	* f (U+0066): X=295.5,Y=699.0 (should be at cap-height 700?)

	* g (U+0067): X=359.0,Y=480.5 (should be at x-height 480?)

	* g (U+0067): X=359.5,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=235.5,Y=480.5 (should be at x-height 480?)

	* m (U+006D): X=217.5,Y=479.0 (should be at x-height 480?)

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

	* y (U+0079): X=217.5,Y=1.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=359.0,Y=-0.5 (should be at baseline 0?)

	* tildecomb (U+0303): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1EA5 (U+1EA5): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EAF (U+1EAF): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=359.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EC5 (U+1EC5): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED6 (U+1ED6): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED7 (U+1ED7): X=389.0,Y=699.0 (should be at cap-height 700?)

	* uni1EF9 (U+1EF9): X=217.5,Y=1.0 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=391.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=40.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=579.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<91.0,700.0>--<344.0,699.0>>

	* F (U+0046): L<<90.0,701.0>--<497.0,700.0>>

	* H (U+0048): L<<117.0,700.0>--<115.0,399.0>>

	* H (U+0048): L<<515.0,399.0>--<513.0,700.0>>

	* P (U+0050): L<<93.0,701.0>--<373.0,699.0>>

	* P (U+0050): L<<95.0,350.0>--<93.0,701.0>>

	* R (U+0052): L<<96.0,350.0>--<93.0,701.0>>

	* U (U+0055): L<<479.0,180.0>--<477.0,700.0>>

	* U (U+0055): L<<503.0,700.0>--<501.0,302.0>>

	* U (U+0055): L<<59.0,302.0>--<57.0,700.0>>

	* U (U+0055): L<<83.0,700.0>--<81.0,180.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[23] Ojuju-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 460, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

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

	- Glyph name: grave	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: macron	Expected: 1

	- Glyph name: degree	Expected: 2

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: cedilla	Expected: 1

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

	- Glyph name: Itilde	Expected: 2

	- Glyph name: itilde	Expected: 2

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

	- Glyph name: Utilde	Expected: 2

	- Glyph name: utilde	Expected: 2

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EA	Expected: 2

	- Glyph name: uni01EB	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F4	Expected: 2

	- Glyph name: uni01F5	Expected: 3

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: Oslashacute	Expected: 4

	- Glyph name: oslashacute	Expected: 4

	- Glyph name: uni0200	Expected: 4

	- Glyph name: uni0201	Expected: 4

	- Glyph name: uni0202	Expected: 3

	- Glyph name: uni0203	Expected: 3

	- Glyph name: uni0204	Expected: 3

	- Glyph name: uni0205	Expected: 4

	- Glyph name: uni0206	Expected: 2

	- Glyph name: uni0207	Expected: 3

	- Glyph name: uni0208	Expected: 3

	- Glyph name: uni0209	Expected: 3

	- Glyph name: uni020A	Expected: 2

	- Glyph name: uni020B	Expected: 2

	- Glyph name: uni020C	Expected: 4

	- Glyph name: uni020D	Expected: 4

	- Glyph name: uni020E	Expected: 3

	- Glyph name: uni020F	Expected: 3

	- Glyph name: uni0210	Expected: 4

	- Glyph name: uni0211	Expected: 3

	- Glyph name: uni0212	Expected: 3

	- Glyph name: uni0213	Expected: 2

	- Glyph name: uni0214	Expected: 3

	- Glyph name: uni0215	Expected: 3

	- Glyph name: uni0216	Expected: 2

	- Glyph name: uni0217	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: gravecomb	Expected: 1

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: hookabovecomb	Expected: 1

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: dotbelowcomb	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: Dmacronbelow	Expected: 3

	- Glyph name: dmacronbelow	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E1F	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: Lmacronbelow	Expected: 2

	- Glyph name: lmacronbelow	Expected: 2

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: Nmacronbelow	Expected: 2

	- Glyph name: nmacronbelow	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: Rmacronbelow	Expected: 3

	- Glyph name: rmacronbelow	Expected: 2

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: Tmacronbelow	Expected: 2

	- Glyph name: tmacronbelow	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni207F	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

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

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Itilde	Expected: 2

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

	- Glyph name: Oslashacute	Expected: 4

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

	- Glyph name: Utilde	Expected: 2

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

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

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

	- Glyph name: breve	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: circumflex	Expected: 1

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: itilde	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: oslashacute	Expected: 4

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

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: utilde	Expected: 2

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
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, syriac, tai-le, canadian-aboriginal, coptic, malayalam, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, cherokee, syriac, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: myanmar, masaram-gondi, gunjala-gondi, syloti-nagri, chakma, bengali, sharada, tamil, tibetan, tagalog, miao, marchen, sundanese, zanabazar-square, thai, newa, dogra, grantha, mongolian, hebrew, takri, soyombo, nko, devanagari, brahmi, symbols, syriac, oriya, mandaic, psalter-pahlavi, rejang, sogdian, khmer, caucasian-albanian, cham, khojki, osage, meetei-mayek, tai-le, phags-pa, kannada, tirhuta, javanese, hanunoo, hanifi-rohingya, kharoshthi, old-permic, lao, mahajani, music, lepcha, gurmukhi, modi, siddham, buhid, adlam, duployan, manichaean, mende-kikakui, telugu, tagbanwa, sinhala, tai-viet, yi, coptic, wancho, malayalam, math, pahawh-hmong, khudawadi, thaana, tifinagh, bassa-vah, batak, ahom, kaithi, limbu, elbasan, gujarati, bhaiksuki, new-tai-lue, balinese, buginese, kayah-li
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=84.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=204.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=88.5,Y=-1.5 (should be at baseline 0?)

	* exclam (U+0021): X=201.0,Y=-1.0 (should be at baseline 0?)

	* period (U+002E): X=88.5,Y=-1.5 (should be at baseline 0?)

	* period (U+002E): X=201.0,Y=-1.0 (should be at baseline 0?)

	* one (U+0031): X=293.0,Y=698.0 (should be at cap-height 700?)

	* six (U+0036): X=526.5,Y=701.0 (should be at cap-height 700?)

	* nine (U+0039): X=341.5,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=363.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=453.5,Y=701.0 (should be at cap-height 700?)

	* D (U+0044): X=314.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=215.0,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=83.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=457.0,Y=702.0 (should be at cap-height 700?)

	* G (U+0047): X=446.5,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=53.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=362.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=83.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=133.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=86.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=384.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=586.0,Y=-261.0 (should be at descender -260?)

	* R (U+0052): X=86.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=329.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=572.0,Y=1.0 (should be at baseline 0?)

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

	* k (U+006B): X=428.0,Y=1.0 (should be at baseline 0?)

	* l (U+006C): X=322.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=224.5,Y=484.5 (should be at x-height 485?)

	* n (U+006E): X=240.0,Y=485.5 (should be at x-height 485?)

	* p (U+0070): X=239.5,Y=-0.5 (should be at baseline 0?)

	* p (U+0070): X=239.5,Y=485.5 (should be at x-height 485?)

	* q (U+0071): X=368.0,Y=485.5 (should be at x-height 485?)

	* q (U+0071): X=368.0,Y=-0.5 (should be at baseline 0?)

	* r (U+0072): X=238.0,Y=486.0 (should be at x-height 485?)

	* s (U+0073): X=414.0,Y=486.0 (should be at x-height 485?)

	* t (U+0074): X=248.0,Y=-2.0 (should be at baseline 0?)

	* t (U+0074): X=248.0,Y=-2.0 (should be at baseline 0?)

	* x (U+0078): X=33.0,Y=486.0 (should be at x-height 485?)

	* x (U+0078): X=77.0,Y=486.0 (should be at x-height 485?)

	* x (U+0078): X=397.0,Y=486.0 (should be at x-height 485?)

	* x (U+0078): X=471.0,Y=486.0 (should be at x-height 485?)

	* ordfeminine (U+00AA): X=366.0,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=263.0,Y=-1.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=453.5,Y=701.0 (should be at cap-height 700?)

	* tildecomb (U+0303): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1EA5 (U+1EA5): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EAF (U+1EAF): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=366.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EC5 (U+1EC5): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED6 (U+1ED6): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED7 (U+1ED7): X=392.0,Y=699.0 (should be at cap-height 700?)

	* uni1EF9 (U+1EF9): X=364.0,Y=699.0 (should be at cap-height 700?)

	* ellipsis (U+2026): X=108.5,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=221.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=380.5,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=493.0,Y=-1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=653.5,Y=-1.5 (should be at baseline 0?)

	* ellipsis (U+2026): X=766.0,Y=-1.0 (should be at baseline 0?)

	* trademark (U+2122): X=36.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=588.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* three (U+0033) contains a short segment B<<524.0,343.5>-<520.0,332.0>-<520.0,321.0>>

	* three (U+0033) contains a short segment B<<520.0,321.0>-<520.0,311.0>-<524.0,299.5>>

	* E (U+0045) contains a short segment B<<162.0,601.0>-<148.0,599.0>-<142.0,594.0>>

	* E (U+0045) contains a short segment B<<142.0,594.0>-<136.0,589.0>-<132.0,579.0>>

	* E (U+0045) contains a short segment B<<132.0,397.0>-<136.0,388.0>-<141.5,383.0>>

	* E (U+0045) contains a short segment B<<141.5,383.0>-<147.0,378.0>-<160.5,376.0>>

	* E (U+0045) contains a short segment B<<141.5,319.5>-<135.0,314.0>-<129.0,304.0>>

	* E (U+0045) contains a short segment B<<130.0,102.0>-<135.0,93.0>-<141.5,88.0>>

	* E (U+0045) contains a short segment B<<141.5,88.0>-<148.0,83.0>-<162.5,80.5>>

	* K (U+004B) contains a short segment B<<232.0,281.0>-<227.0,294.0>-<221.0,297.5>>

	* K (U+004B) contains a short segment B<<272.0,310.0>-<264.0,305.0>-<267.0,292.0>>

	* M (U+004D) contains a short segment B<<379.5,224.5>-<387.0,219.0>-<398.0,219.0>>

	* M (U+004D) contains a short segment B<<398.0,219.0>-<409.0,219.0>-<416.5,224.5>>

	* M (U+004D) contains a short segment B<<666.0,548.0>-<661.0,564.0>-<648.5,569.0>>

	* M (U+004D) contains a short segment B<<553.0,568.0>-<541.0,562.0>-<535.0,547.0>>

	* M (U+004D) contains a short segment B<<261.0,547.0>-<255.0,562.0>-<243.0,568.0>>

	* M (U+004D) contains a short segment B<<148.0,570.0>-<135.0,566.0>-<130.0,548.0>>

	* N (U+004E) contains a short segment B<<447.0,148.5>-<455.0,138.0>-<468.0,135.5>>

	* W (U+0057) contains a short segment B<<144.0,152.0>-<150.0,135.0>-<161.5,130.5>>

	* W (U+0057) contains a short segment B<<161.5,130.5>-<173.0,126.0>-<191.0,126.0>>

	* W (U+0057) contains a short segment B<<230.5,132.0>-<242.0,138.0>-<248.0,153.0>>

	* W (U+0057) contains a short segment B<<524.0,153.0>-<530.0,138.0>-<541.5,132.0>>

	* W (U+0057) contains a short segment B<<582.0,126.0>-<599.0,126.0>-<610.5,130.5>>

	* W (U+0057) contains a short segment B<<610.5,130.5>-<622.0,135.0>-<628.0,152.0>>

	* W (U+0057) contains a short segment B<<403.5,475.5>-<396.0,481.0>-<385.0,481.0>>

	* W (U+0057) contains a short segment B<<385.0,481.0>-<374.0,481.0>-<366.5,475.5>>

	* X (U+0058) contains a short segment B<<184.0,361.0>-<184.0,370.0>-<181.5,380.0>>

	* X (U+0058) contains a short segment B<<445.0,380.0>-<443.0,370.0>-<443.0,361.0>>

	* Z (U+005A) contains a short segment B<<130.0,113.0>-<131.0,101.0>-<133.5,94.0>>

	* Z (U+005A) contains a short segment B<<133.5,94.0>-<136.0,87.0>-<149.0,83.5>>

	* f (U+0066) contains a short segment B<<111.0,494.0>-<111.0,498.0>-<109.0,504.0>>

	* f (U+0066) contains a short segment B<<144.0,500.0>-<144.0,493.0>-<145.0,490.0>>

	* f (U+0066) contains a short segment B<<145.0,490.0>-<147.0,485.0>-<154.0,485.0>>

	* h (U+0068) contains a short segment B<<126.0,402.5>-<128.0,398.0>-<131.0,398.0>>

	* k (U+006B) contains a short segment B<<275.0,267.0>-<265.0,264.0>-<262.0,262.0>>

	* k (U+006B) contains a short segment B<<262.0,262.0>-<259.0,260.0>-<259.0,255.0>>

	* k (U+006B) contains a short segment B<<259.0,255.0>-<259.0,250.0>-<260.5,246.0>>

	* k (U+006B) contains a short segment B<<260.5,246.0>-<262.0,242.0>-<269.0,230.0>>

	* n (U+006E) contains a short segment B<<124.0,402.5>-<126.0,398.0>-<131.0,398.0>>

	* r (U+0072) contains a short segment B<<124.0,388.0>-<126.0,383.0>-<131.0,383.0>>

	* t (U+0074) contains a short segment B<<104.5,398.0>-<101.0,401.0>-<94.0,401.0>>

	* t (U+0074) contains a short segment B<<151.0,401.0>-<147.0,401.0>-<144.0,398.5>>

	* t (U+0074) contains a short segment B<<144.0,398.5>-<141.0,396.0>-<141.0,387.0>>

	* w (U+0077) contains a short segment B<<123.0,115.0>-<127.0,104.0>-<133.0,99.0>>

	* w (U+0077) contains a short segment B<<133.0,99.0>-<139.0,94.0>-<153.0,92.5>>

	* w (U+0077) contains a short segment B<<567.5,92.5>-<582.0,94.0>-<588.0,99.5>>

	* w (U+0077) contains a short segment B<<588.0,99.5>-<594.0,105.0>-<598.0,116.0>>

	* w (U+0077) contains a short segment B<<376.0,382.5>-<370.0,396.0>-<359.0,396.0>>

	* w (U+0077) contains a short segment B<<359.0,396.0>-<348.0,396.0>-<341.5,382.5>>

	* y (U+0079) contains a short segment B<<190.0,114.0>-<192.0,105.0>-<198.5,100.5>>

	* y (U+0079) contains a short segment B<<379.5,100.5>-<386.0,105.0>-<389.0,114.0>>

	* z (U+007A) contains a short segment B<<377.0,378.5>-<379.0,385.0>-<379.0,394.0>>

	* z (U+007A) contains a short segment B<<379.0,394.0>-<379.0,403.0>-<374.5,407.5>>

	* z (U+007A) contains a short segment B<<114.0,85.0>-<112.0,80.0>-<112.0,71.0>>

	* uni02B0 (U+02B0) contains a short segment B<<126.0,402.5>-<128.0,398.0>-<131.0,398.0>>

	* uni02B7 (U+02B7) contains a short segment B<<123.0,115.0>-<127.0,104.0>-<133.0,99.0>>

	* uni02B7 (U+02B7) contains a short segment B<<133.0,99.0>-<139.0,94.0>-<153.0,92.5>>

	* uni02B7 (U+02B7) contains a short segment B<<567.5,92.5>-<582.0,94.0>-<588.0,99.5>>

	* uni02B7 (U+02B7) contains a short segment B<<588.0,99.5>-<594.0,105.0>-<598.0,116.0>>

	* uni02B7 (U+02B7) contains a short segment B<<376.0,382.5>-<370.0,396.0>-<359.0,396.0>>

	* uni02B7 (U+02B7) contains a short segment B<<359.0,396.0>-<348.0,396.0>-<341.5,382.5>>

	* uni1DBB (U+1DBB) contains a short segment B<<377.0,378.5>-<379.0,385.0>-<379.0,394.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<379.0,394.0>-<379.0,403.0>-<374.5,407.5>>

	* uni1DBB (U+1DBB) contains a short segment B<<114.0,85.0>-<112.0,80.0>-<112.0,71.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<162.0,601.0>-<148.0,599.0>-<142.0,594.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<142.0,594.0>-<136.0,589.0>-<132.0,579.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<132.0,397.0>-<136.0,388.0>-<141.5,383.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<141.5,383.0>-<147.0,378.0>-<160.5,376.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<141.5,319.5>-<135.0,314.0>-<129.0,304.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<130.0,102.0>-<135.0,93.0>-<141.5,88.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<141.5,88.0>-<148.0,83.0>-<162.5,80.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<162.0,601.0>-<148.0,599.0>-<142.0,594.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<142.0,594.0>-<136.0,589.0>-<132.0,579.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<132.0,397.0>-<136.0,388.0>-<141.5,383.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<141.5,383.0>-<147.0,378.0>-<160.5,376.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<141.5,319.5>-<135.0,314.0>-<129.0,304.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<130.0,102.0>-<135.0,93.0>-<141.5,88.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<141.5,88.0>-<148.0,83.0>-<162.5,80.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<162.0,601.0>-<148.0,599.0>-<142.0,594.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<142.0,594.0>-<136.0,589.0>-<132.0,579.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<132.0,397.0>-<136.0,388.0>-<141.5,383.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<141.5,383.0>-<147.0,378.0>-<160.5,376.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<141.5,319.5>-<135.0,314.0>-<129.0,304.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<130.0,102.0>-<135.0,93.0>-<141.5,88.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<141.5,88.0>-<148.0,83.0>-<162.5,80.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<190.0,114.0>-<192.0,105.0>-<198.5,100.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<379.5,100.5>-<386.0,105.0>-<389.0,114.0>>

	* trademark (U+2122) contains a short segment B<<1011.5,224.5>-<1019.0,219.0>-<1030.0,219.0>>

	* trademark (U+2122) contains a short segment B<<1030.0,219.0>-<1041.0,219.0>-<1048.5,224.5>>

	* trademark (U+2122) contains a short segment B<<1298.0,548.0>-<1293.0,564.0>-<1280.5,569.0>>

	* trademark (U+2122) contains a short segment B<<1185.0,568.0>-<1173.0,562.0>-<1167.0,547.0>>

	* trademark (U+2122) contains a short segment B<<893.0,547.0>-<887.0,562.0>-<875.0,568.0>>

	* trademark (U+2122) contains a short segment B<<780.0,570.0>-<767.0,566.0>-<762.0,548.0>>

	* estimated (U+212E) contains a short segment B<<196.0,334.0>-<189.0,334.0>-<185.0,331.0>>

	* estimated (U+212E) contains a short segment B<<185.0,331.0>-<181.0,328.0>-<181.0,315.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<83.0,700.0>--<363.0,699.0>>

	* F (U+0046): L<<83.0,701.0>--<519.0,700.0>>

	* G (U+0047): L<<519.0,681.0>--<518.0,552.0>>

	* H (U+0048): L<<129.0,700.0>--<127.0,447.0>>

	* H (U+0048): L<<530.0,447.0>--<528.0,700.0>>

	* P (U+0050): L<<86.0,701.0>--<384.0,699.0>>

	* P (U+0050): L<<88.0,350.0>--<86.0,701.0>>

	* R (U+0052): L<<86.0,701.0>--<329.0,699.0>>

	* R (U+0052): L<<89.0,350.0>--<86.0,701.0>>

	* U (U+0055): L<<102.0,700.0>--<99.0,245.0>>

	* U (U+0055): L<<482.0,245.0>--<480.0,700.0>>

	* U (U+0055): L<<528.0,700.0>--<526.0,302.0>>

	* U (U+0055): L<<55.0,304.0>--<53.0,700.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[22] Ojuju-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 460, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

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

	- Glyph name: grave	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: macron	Expected: 1

	- Glyph name: degree	Expected: 2

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: cedilla	Expected: 1

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

	- Glyph name: Itilde	Expected: 2

	- Glyph name: itilde	Expected: 2

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

	- Glyph name: Utilde	Expected: 2

	- Glyph name: utilde	Expected: 2

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EA	Expected: 2

	- Glyph name: uni01EB	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F4	Expected: 2

	- Glyph name: uni01F5	Expected: 3

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: Oslashacute	Expected: 4

	- Glyph name: oslashacute	Expected: 4

	- Glyph name: uni0200	Expected: 4

	- Glyph name: uni0201	Expected: 4

	- Glyph name: uni0202	Expected: 3

	- Glyph name: uni0203	Expected: 3

	- Glyph name: uni0204	Expected: 3

	- Glyph name: uni0205	Expected: 4

	- Glyph name: uni0206	Expected: 2

	- Glyph name: uni0207	Expected: 3

	- Glyph name: uni0208	Expected: 3

	- Glyph name: uni0209	Expected: 3

	- Glyph name: uni020A	Expected: 2

	- Glyph name: uni020B	Expected: 2

	- Glyph name: uni020C	Expected: 4

	- Glyph name: uni020D	Expected: 4

	- Glyph name: uni020E	Expected: 3

	- Glyph name: uni020F	Expected: 3

	- Glyph name: uni0210	Expected: 4

	- Glyph name: uni0211	Expected: 3

	- Glyph name: uni0212	Expected: 3

	- Glyph name: uni0213	Expected: 2

	- Glyph name: uni0214	Expected: 3

	- Glyph name: uni0215	Expected: 3

	- Glyph name: uni0216	Expected: 2

	- Glyph name: uni0217	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: gravecomb	Expected: 1

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: hookabovecomb	Expected: 1

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: dotbelowcomb	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: Dmacronbelow	Expected: 3

	- Glyph name: dmacronbelow	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E1F	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: Lmacronbelow	Expected: 2

	- Glyph name: lmacronbelow	Expected: 2

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: Nmacronbelow	Expected: 2

	- Glyph name: nmacronbelow	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: Rmacronbelow	Expected: 3

	- Glyph name: rmacronbelow	Expected: 2

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: Tmacronbelow	Expected: 2

	- Glyph name: tmacronbelow	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni207F	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

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

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Itilde	Expected: 2

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

	- Glyph name: Oslashacute	Expected: 4

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

	- Glyph name: Utilde	Expected: 2

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

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

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

	- Glyph name: breve	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: circumflex	Expected: 1

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: itilde	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: oslashacute	Expected: 4

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

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: utilde	Expected: 2

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
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, syriac, tai-le, canadian-aboriginal, coptic, malayalam, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, cherokee, syriac, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: myanmar, masaram-gondi, gunjala-gondi, syloti-nagri, chakma, bengali, sharada, tamil, tibetan, tagalog, miao, marchen, sundanese, zanabazar-square, thai, newa, dogra, grantha, mongolian, hebrew, takri, soyombo, nko, devanagari, brahmi, symbols, syriac, oriya, mandaic, psalter-pahlavi, rejang, sogdian, khmer, caucasian-albanian, cham, khojki, osage, meetei-mayek, tai-le, phags-pa, kannada, tirhuta, javanese, hanunoo, hanifi-rohingya, kharoshthi, old-permic, lao, mahajani, music, lepcha, gurmukhi, modi, siddham, buhid, adlam, duployan, manichaean, mende-kikakui, telugu, tagbanwa, sinhala, tai-viet, yi, coptic, wancho, malayalam, math, pahawh-hmong, khudawadi, thaana, tifinagh, bassa-vah, batak, ahom, kaithi, limbu, elbasan, gujarati, bhaiksuki, new-tai-lue, balinese, buginese, kayah-li
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* one (U+0031): X=222.5,Y=698.5 (should be at cap-height 700?)

	* one (U+0031): X=294.0,Y=699.0 (should be at cap-height 700?)

	* six (U+0036): X=526.5,Y=701.0 (should be at cap-height 700?)

	* nine (U+0039): X=341.5,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=354.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=450.5,Y=700.5 (should be at cap-height 700?)

	* D (U+0044): X=314.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=217.0,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=86.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=453.0,Y=702.0 (should be at cap-height 700?)

	* G (U+0047): X=441.5,Y=1.5 (should be at baseline 0?)

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

	* R (U+0052): X=315.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=38.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=584.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=363.5,Y=483.5 (should be at x-height 483?)

	* a (U+0061): X=363.5,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=236.5,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=236.5,Y=483.5 (should be at x-height 483?)

	* d (U+0064): X=363.5,Y=483.5 (should be at x-height 483?)

	* d (U+0064): X=363.5,Y=-0.5 (should be at baseline 0?)

	* g (U+0067): X=363.5,Y=483.5 (should be at x-height 483?)

	* g (U+0067): X=363.0,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=238.0,Y=483.5 (should be at x-height 483?)

	* k (U+006B): X=437.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=221.0,Y=482.0 (should be at x-height 483?)

	* n (U+006E): X=238.0,Y=483.5 (should be at x-height 483?)

	* p (U+0070): X=236.5,Y=-0.5 (should be at baseline 0?)

	* p (U+0070): X=236.5,Y=483.5 (should be at x-height 483?)

	* q (U+0071): X=363.5,Y=483.5 (should be at x-height 483?)

	* q (U+0071): X=363.5,Y=-0.5 (should be at baseline 0?)

	* r (U+0072): X=235.5,Y=483.5 (should be at x-height 483?)

	* t (U+0074): X=248.0,Y=-1.0 (should be at baseline 0?)

	* t (U+0074): X=248.0,Y=-1.0 (should be at baseline 0?)

	* u (U+0075): X=58.0,Y=482.0 (should be at x-height 483?)

	* u (U+0075): X=94.0,Y=482.0 (should be at x-height 483?)

	* u (U+0075): X=431.0,Y=482.0 (should be at x-height 483?)

	* u (U+0075): X=467.0,Y=482.0 (should be at x-height 483?)

	* ordfeminine (U+00AA): X=363.5,Y=-0.5 (should be at baseline 0?)

	* ae (U+00E6): X=267.0,Y=1.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=450.5,Y=700.5 (should be at cap-height 700?)

	* tildecomb (U+0303): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1EA5 (U+1EA5): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EAF (U+1EAF): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=363.5,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EC5 (U+1EC5): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED6 (U+1ED6): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED7 (U+1ED7): X=391.0,Y=699.0 (should be at cap-height 700?)

	* uni1EF9 (U+1EF9): X=376.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=38.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=584.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<87.0,700.0>--<354.0,699.0>>

	* F (U+0046): L<<86.0,701.0>--<509.0,700.0>>

	* H (U+0048): L<<523.0,425.0>--<521.0,700.0>>

	* P (U+0050): L<<89.0,701.0>--<379.0,699.0>>

	* P (U+0050): L<<91.0,350.0>--<89.0,701.0>>

	* R (U+0052): L<<92.0,350.0>--<89.0,701.0>>

	* U (U+0055): L<<481.0,215.0>--<478.0,700.0>>

	* U (U+0055): L<<517.0,700.0>--<515.0,302.0>>

	* U (U+0055): L<<57.0,303.0>--<55.0,700.0>>

	* U (U+0055): L<<93.0,700.0>--<90.0,215.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[23] Ojuju-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 460, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

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

	- Glyph name: grave	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: macron	Expected: 1

	- Glyph name: degree	Expected: 2

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: cedilla	Expected: 1

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

	- Glyph name: Itilde	Expected: 2

	- Glyph name: itilde	Expected: 2

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

	- Glyph name: Utilde	Expected: 2

	- Glyph name: utilde	Expected: 2

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EA	Expected: 2

	- Glyph name: uni01EB	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F4	Expected: 2

	- Glyph name: uni01F5	Expected: 3

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: Oslashacute	Expected: 4

	- Glyph name: oslashacute	Expected: 4

	- Glyph name: uni0200	Expected: 4

	- Glyph name: uni0201	Expected: 4

	- Glyph name: uni0202	Expected: 3

	- Glyph name: uni0203	Expected: 3

	- Glyph name: uni0204	Expected: 3

	- Glyph name: uni0205	Expected: 4

	- Glyph name: uni0206	Expected: 2

	- Glyph name: uni0207	Expected: 3

	- Glyph name: uni0208	Expected: 3

	- Glyph name: uni0209	Expected: 3

	- Glyph name: uni020A	Expected: 2

	- Glyph name: uni020B	Expected: 2

	- Glyph name: uni020C	Expected: 4

	- Glyph name: uni020D	Expected: 4

	- Glyph name: uni020E	Expected: 3

	- Glyph name: uni020F	Expected: 3

	- Glyph name: uni0210	Expected: 4

	- Glyph name: uni0211	Expected: 3

	- Glyph name: uni0212	Expected: 3

	- Glyph name: uni0213	Expected: 2

	- Glyph name: uni0214	Expected: 3

	- Glyph name: uni0215	Expected: 3

	- Glyph name: uni0216	Expected: 2

	- Glyph name: uni0217	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: gravecomb	Expected: 1

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: hookabovecomb	Expected: 1

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: dotbelowcomb	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: Dmacronbelow	Expected: 3

	- Glyph name: dmacronbelow	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E1F	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: Lmacronbelow	Expected: 2

	- Glyph name: lmacronbelow	Expected: 2

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: Nmacronbelow	Expected: 2

	- Glyph name: nmacronbelow	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: Rmacronbelow	Expected: 3

	- Glyph name: rmacronbelow	Expected: 2

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: Tmacronbelow	Expected: 2

	- Glyph name: tmacronbelow	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni207F	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

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

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Itilde	Expected: 2

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

	- Glyph name: Oslashacute	Expected: 4

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

	- Glyph name: Utilde	Expected: 2

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

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

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

	- Glyph name: breve	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: circumflex	Expected: 1

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: itilde	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: oslashacute	Expected: 4

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

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: utilde	Expected: 2

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
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, syriac, tai-le, canadian-aboriginal, coptic, malayalam, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, cherokee, syriac, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: myanmar, masaram-gondi, gunjala-gondi, syloti-nagri, chakma, bengali, sharada, tamil, tibetan, tagalog, miao, marchen, sundanese, zanabazar-square, thai, newa, dogra, grantha, mongolian, hebrew, takri, soyombo, nko, devanagari, brahmi, symbols, syriac, oriya, mandaic, psalter-pahlavi, rejang, sogdian, khmer, caucasian-albanian, cham, khojki, osage, meetei-mayek, tai-le, phags-pa, kannada, tirhuta, javanese, hanunoo, hanifi-rohingya, kharoshthi, old-permic, lao, mahajani, music, lepcha, gurmukhi, modi, siddham, buhid, adlam, duployan, manichaean, mende-kikakui, telugu, tagbanwa, sinhala, tai-viet, yi, coptic, wancho, malayalam, math, pahawh-hmong, khudawadi, thaana, tifinagh, bassa-vah, batak, ahom, kaithi, limbu, elbasan, gujarati, bhaiksuki, new-tai-lue, balinese, buginese, kayah-li
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=63.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=255.0,Y=701.0 (should be at cap-height 700?)

	* comma (U+002C): X=262.0,Y=1.0 (should be at baseline 0?)

	* six (U+0036): X=526.5,Y=701.0 (should be at cap-height 700?)

	* nine (U+0039): X=341.5,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=72.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=391.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=464.5,Y=702.0 (should be at cap-height 700?)

	* C (U+0043): X=450.5,Y=1.5 (should be at baseline 0?)

	* F (U+0046): X=71.0,Y=701.0 (should be at cap-height 700?)

	* F (U+0046): X=553.0,Y=699.0 (should be at cap-height 700?)

	* G (U+0047): X=470.5,Y=702.0 (should be at cap-height 700?)

	* G (U+0047): X=463.5,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=47.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=402.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=71.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=152.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=74.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=400.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=479.5,Y=-259.0 (should be at descender -260?)

	* R (U+0052): X=74.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=375.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=29.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=602.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=378.5,Y=493.5 (should be at x-height 493?)

	* d (U+0064): X=562.0,Y=491.0 (should be at x-height 493?)

	* f (U+0066): X=372.0,Y=742.0 (should be at ascender 740?)

	* g (U+0067): X=378.5,Y=493.5 (should be at x-height 493?)

	* h (U+0068): X=248.0,Y=493.5 (should be at x-height 493?)

	* i (U+0069): X=302.0,Y=738.5 (should be at ascender 740?)

	* j (U+006A): X=302.5,Y=738.5 (should be at ascender 740?)

	* l (U+006C): X=343.0,Y=1.0 (should be at baseline 0?)

	* m (U+006D): X=235.0,Y=492.5 (should be at x-height 493?)

	* n (U+006E): X=248.0,Y=493.5 (should be at x-height 493?)

	* r (U+0072): X=243.5,Y=494.0 (should be at x-height 493?)

	* s (U+0073): X=440.0,Y=495.0 (should be at x-height 493?)

	* t (U+0074): X=314.5,Y=1.5 (should be at baseline 0?)

	* x (U+0078): X=35.0,Y=495.0 (should be at x-height 493?)

	* x (U+0078): X=99.0,Y=495.0 (should be at x-height 493?)

	* x (U+0078): X=349.0,Y=495.0 (should be at x-height 493?)

	* x (U+0078): X=481.0,Y=495.0 (should be at x-height 493?)

	* y (U+0079): X=342.5,Y=-2.0 (should be at baseline 0?)

	* Cdotaccent (U+010A): X=464.5,Y=702.0 (should be at cap-height 700?)

	* Cdotaccent (U+010A): X=450.5,Y=1.5 (should be at baseline 0?)

	* tildecomb (U+0303): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni0307 (U+0307): X=95.0,Y=702.0 (should be at cap-height 700?)

	* uni1EAB (U+1EAB): X=397.0,Y=699.0 (should be at cap-height 700?)

	* uni1EB5 (U+1EB5): X=397.0,Y=699.0 (should be at cap-height 700?)

	* uni1EC5 (U+1EC5): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED6 (U+1ED6): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED7 (U+1ED7): X=396.0,Y=699.0 (should be at cap-height 700?)

	* uni1EF9 (U+1EF9): X=342.5,Y=-2.0 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=322.0,Y=699.0 (should be at cap-height 700?)

	* quotedblbase (U+201E): X=262.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=262.0,Y=1.0 (should be at baseline 0?)

	* trademark (U+2122): X=29.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=602.0,Y=699.0 (should be at cap-height 700?)

	* estimated (U+212E): X=425.0,Y=-2.0 (should be at baseline 0?)

	* estimated (U+212E): X=425.0,Y=702.0 (should be at cap-height 700?)

	* estimated (U+212E): X=425.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* three (U+0033) contains a short segment B<<524.0,343.5>-<520.0,332.0>-<520.0,321.0>>

	* three (U+0033) contains a short segment B<<520.0,321.0>-<520.0,311.0>-<524.0,299.5>>

	* K (U+004B) contains a short segment B<<230.0,261.0>-<225.0,272.0>-<219.5,275.0>>

	* K (U+004B) contains a short segment B<<160.5,275.5>-<151.0,273.0>-<146.0,262.0>>

	* K (U+004B) contains a short segment B<<292.0,303.5>-<283.0,299.0>-<285.0,288.0>>

	* M (U+004D) contains a short segment B<<391.5,298.5>-<399.0,293.0>-<411.0,293.0>>

	* M (U+004D) contains a short segment B<<411.0,293.0>-<422.0,293.0>-<430.0,298.5>>

	* M (U+004D) contains a short segment B<<672.0,420.0>-<665.0,432.0>-<652.5,435.5>>

	* M (U+004D) contains a short segment B<<560.5,435.0>-<549.0,431.0>-<538.0,418.0>>

	* M (U+004D) contains a short segment B<<283.0,418.0>-<273.0,431.0>-<261.5,435.0>>

	* M (U+004D) contains a short segment B<<169.0,436.0>-<156.0,433.0>-<150.0,420.0>>

	* N (U+004E) contains a short segment B<<434.0,295.0>-<442.0,286.0>-<453.0,283.5>>

	* W (U+0057) contains a short segment B<<162.0,280.0>-<169.0,267.0>-<178.5,264.0>>

	* W (U+0057) contains a short segment B<<250.5,265.0>-<261.0,269.0>-<271.0,282.0>>

	* W (U+0057) contains a short segment B<<530.0,282.0>-<540.0,269.0>-<550.5,265.0>>

	* W (U+0057) contains a short segment B<<622.5,264.0>-<632.0,267.0>-<639.0,280.0>>

	* W (U+0057) contains a short segment B<<417.5,401.5>-<410.0,407.0>-<399.0,407.0>>

	* W (U+0057) contains a short segment B<<399.0,407.0>-<387.0,407.0>-<379.5,401.5>>

	* X (U+0058) contains a short segment B<<179.0,361.0>-<179.0,370.0>-<176.5,380.0>>

	* X (U+0058) contains a short segment B<<497.0,380.0>-<495.0,370.0>-<495.0,361.0>>

	* Z (U+005A) contains a short segment B<<442.0,481.0>-<442.0,494.0>-<437.0,501.0>>

	* Z (U+005A) contains a short segment B<<208.0,185.5>-<204.0,178.0>-<204.0,167.0>>

	* Z (U+005A) contains a short segment B<<204.0,167.0>-<204.0,156.0>-<208.5,151.5>>

	* b (U+0062) contains a short segment B<<138.0,415.5>-<141.0,404.0>-<146.0,404.0>>

	* f (U+0066) contains a short segment B<<122.0,503.0>-<122.0,506.0>-<121.0,512.0>>

	* f (U+0066) contains a short segment B<<178.0,510.0>-<176.0,503.0>-<177.0,500.0>>

	* f (U+0066) contains a short segment B<<177.0,500.0>-<177.0,493.0>-<187.0,493.0>>

	* h (U+0068) contains a short segment B<<135.5,413.0>-<138.0,404.0>-<143.0,404.0>>

	* k (U+006B) contains a short segment B<<257.0,267.0>-<247.0,264.0>-<244.0,262.0>>

	* k (U+006B) contains a short segment B<<244.0,262.0>-<241.0,260.0>-<241.0,254.0>>

	* k (U+006B) contains a short segment B<<241.0,254.0>-<241.0,248.0>-<243.0,244.0>>

	* k (U+006B) contains a short segment B<<243.0,244.0>-<245.0,240.0>-<252.0,232.0>>

	* m (U+006D) contains a short segment B<<482.0,413.5>-<488.0,403.0>-<497.0,403.0>>

	* m (U+006D) contains a short segment B<<497.0,403.0>-<507.0,403.0>-<515.0,413.5>>

	* n (U+006E) contains a short segment B<<134.0,409.0>-<137.0,404.0>-<143.0,404.0>>

	* p (U+0070) contains a short segment B<<131.0,411.0>-<133.0,404.0>-<140.0,404.0>>

	* r (U+0072) contains a short segment B<<134.5,403.0>-<137.0,398.0>-<142.0,398.0>>

	* t (U+0074) contains a short segment B<<110.5,327.5>-<106.0,331.0>-<100.0,331.0>>

	* t (U+0074) contains a short segment B<<178.0,331.0>-<173.0,331.0>-<169.0,328.5>>

	* w (U+0077) contains a short segment B<<125.0,208.0>-<131.0,197.0>-<137.0,192.0>>

	* w (U+0077) contains a short segment B<<137.0,192.0>-<143.0,187.0>-<155.5,185.5>>

	* w (U+0077) contains a short segment B<<238.0,185.5>-<253.0,187.0>-<259.5,191.5>>

	* w (U+0077) contains a short segment B<<259.5,191.5>-<266.0,196.0>-<271.0,207.0>>

	* w (U+0077) contains a short segment B<<447.0,211.0>-<452.0,198.0>-<459.0,192.5>>

	* w (U+0077) contains a short segment B<<568.0,185.5>-<581.0,187.0>-<587.0,193.0>>

	* w (U+0077) contains a short segment B<<587.0,193.0>-<593.0,199.0>-<597.0,212.0>>

	* y (U+0079) contains a short segment B<<349.0,-9.0>-<349.0,-4.0>-<342.5,-2.0>>

	* z (U+007A) contains a short segment B<<349.5,327.0>-<352.0,332.0>-<352.0,340.0>>

	* z (U+007A) contains a short segment B<<352.0,340.0>-<352.0,349.0>-<349.0,353.5>>

	* z (U+007A) contains a short segment B<<170.0,128.0>-<167.0,124.0>-<167.0,116.0>>

	* z (U+007A) contains a short segment B<<167.0,116.0>-<167.0,108.0>-<174.5,106.5>>

	* uni02B0 (U+02B0) contains a short segment B<<135.5,413.0>-<138.0,404.0>-<143.0,404.0>>

	* uni02B7 (U+02B7) contains a short segment B<<125.0,208.0>-<131.0,197.0>-<137.0,192.0>>

	* uni02B7 (U+02B7) contains a short segment B<<137.0,192.0>-<143.0,187.0>-<155.5,185.5>>

	* uni02B7 (U+02B7) contains a short segment B<<238.0,185.5>-<253.0,187.0>-<259.5,191.5>>

	* uni02B7 (U+02B7) contains a short segment B<<259.5,191.5>-<266.0,196.0>-<271.0,207.0>>

	* uni02B7 (U+02B7) contains a short segment B<<447.0,211.0>-<452.0,198.0>-<459.0,192.5>>

	* uni02B7 (U+02B7) contains a short segment B<<568.0,185.5>-<581.0,187.0>-<587.0,193.0>>

	* uni02B7 (U+02B7) contains a short segment B<<587.0,193.0>-<593.0,199.0>-<597.0,212.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<349.5,327.0>-<352.0,332.0>-<352.0,340.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<352.0,340.0>-<352.0,349.0>-<349.0,353.5>>

	* uni1DBB (U+1DBB) contains a short segment B<<170.0,128.0>-<167.0,124.0>-<167.0,116.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<167.0,116.0>-<167.0,108.0>-<174.5,106.5>>

	* uni1EF9 (U+1EF9) contains a short segment B<<349.0,-9.0>-<349.0,-4.0>-<342.5,-2.0>>

	* trademark (U+2122) contains a short segment B<<1043.5,298.5>-<1051.0,293.0>-<1063.0,293.0>>

	* trademark (U+2122) contains a short segment B<<1063.0,293.0>-<1074.0,293.0>-<1082.0,298.5>>

	* trademark (U+2122) contains a short segment B<<1324.0,420.0>-<1317.0,432.0>-<1304.5,435.5>>

	* trademark (U+2122) contains a short segment B<<1212.5,435.0>-<1201.0,431.0>-<1190.0,418.0>>

	* trademark (U+2122) contains a short segment B<<935.0,418.0>-<925.0,431.0>-<913.5,435.0>>

	* trademark (U+2122) contains a short segment B<<821.0,436.0>-<808.0,433.0>-<802.0,420.0>>

	* estimated (U+212E) contains a short segment B<<198.0,340.0>-<191.0,340.0>-<187.0,337.5>>

	* estimated (U+212E) contains a short segment B<<187.0,337.5>-<183.0,335.0>-<183.0,322.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<72.0,701.0>--<391.0,699.0>>

	* F (U+0046): L<<553.0,699.0>--<552.0,514.0>>

	* F (U+0046): L<<71.0,701.0>--<553.0,699.0>>

	* P (U+0050): L<<74.0,701.0>--<400.0,699.0>>

	* P (U+0050): L<<77.0,350.0>--<74.0,701.0>>

	* R (U+0052): L<<74.0,701.0>--<375.0,699.0>>

	* R (U+0052): L<<77.0,350.0>--<74.0,701.0>>

	* S (U+0053): L<<55.0,10.0>--<54.0,177.0>>

	* U (U+0055): L<<48.0,307.0>--<47.0,700.0>>

	* U (U+0055): L<<567.0,700.0>--<565.0,302.0>>

	* i (U+0069): L<<57.0,323.0>--<56.0,493.0>>

	* l (U+006C): L<<147.0,89.0>--<148.0,469.0>>

	* l (U+006C): L<<9.0,570.0>--<8.0,740.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[22] Ojuju-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 460, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

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

	- Glyph name: grave	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: macron	Expected: 1

	- Glyph name: degree	Expected: 2

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: cedilla	Expected: 1

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

	- Glyph name: Itilde	Expected: 2

	- Glyph name: itilde	Expected: 2

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

	- Glyph name: Utilde	Expected: 2

	- Glyph name: utilde	Expected: 2

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EA	Expected: 2

	- Glyph name: uni01EB	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F4	Expected: 2

	- Glyph name: uni01F5	Expected: 3

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: Oslashacute	Expected: 4

	- Glyph name: oslashacute	Expected: 4

	- Glyph name: uni0200	Expected: 4

	- Glyph name: uni0201	Expected: 4

	- Glyph name: uni0202	Expected: 3

	- Glyph name: uni0203	Expected: 3

	- Glyph name: uni0204	Expected: 3

	- Glyph name: uni0205	Expected: 4

	- Glyph name: uni0206	Expected: 2

	- Glyph name: uni0207	Expected: 3

	- Glyph name: uni0208	Expected: 3

	- Glyph name: uni0209	Expected: 3

	- Glyph name: uni020A	Expected: 2

	- Glyph name: uni020B	Expected: 2

	- Glyph name: uni020C	Expected: 4

	- Glyph name: uni020D	Expected: 4

	- Glyph name: uni020E	Expected: 3

	- Glyph name: uni020F	Expected: 3

	- Glyph name: uni0210	Expected: 4

	- Glyph name: uni0211	Expected: 3

	- Glyph name: uni0212	Expected: 3

	- Glyph name: uni0213	Expected: 2

	- Glyph name: uni0214	Expected: 3

	- Glyph name: uni0215	Expected: 3

	- Glyph name: uni0216	Expected: 2

	- Glyph name: uni0217	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: gravecomb	Expected: 1

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: hookabovecomb	Expected: 1

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: dotbelowcomb	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: Dmacronbelow	Expected: 3

	- Glyph name: dmacronbelow	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E1F	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: Lmacronbelow	Expected: 2

	- Glyph name: lmacronbelow	Expected: 2

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: Nmacronbelow	Expected: 2

	- Glyph name: nmacronbelow	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: Rmacronbelow	Expected: 3

	- Glyph name: rmacronbelow	Expected: 2

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: Tmacronbelow	Expected: 2

	- Glyph name: tmacronbelow	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni207F	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

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

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Itilde	Expected: 2

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

	- Glyph name: Oslashacute	Expected: 4

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

	- Glyph name: Utilde	Expected: 2

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

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

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

	- Glyph name: breve	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: circumflex	Expected: 1

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: itilde	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: oslashacute	Expected: 4

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

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: utilde	Expected: 2

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
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, syriac, tai-le, canadian-aboriginal, coptic, malayalam, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, cherokee, syriac, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: myanmar, masaram-gondi, gunjala-gondi, syloti-nagri, chakma, bengali, sharada, tamil, tibetan, tagalog, miao, marchen, sundanese, zanabazar-square, thai, newa, dogra, grantha, mongolian, hebrew, takri, soyombo, nko, devanagari, brahmi, symbols, syriac, oriya, mandaic, psalter-pahlavi, rejang, sogdian, khmer, caucasian-albanian, cham, khojki, osage, meetei-mayek, tai-le, phags-pa, kannada, tirhuta, javanese, hanunoo, hanifi-rohingya, kharoshthi, old-permic, lao, mahajani, music, lepcha, gurmukhi, modi, siddham, buhid, adlam, duployan, manichaean, mende-kikakui, telugu, tagbanwa, sinhala, tai-viet, yi, coptic, wancho, malayalam, math, pahawh-hmong, khudawadi, thaana, tifinagh, bassa-vah, batak, ahom, kaithi, limbu, elbasan, gujarati, bhaiksuki, new-tai-lue, balinese, buginese, kayah-li
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* one (U+0031): X=224.0,Y=699.5 (should be at cap-height 700?)

	* six (U+0036): X=526.5,Y=701.0 (should be at cap-height 700?)

	* nine (U+0039): X=341.5,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=348.0,Y=699.0 (should be at cap-height 700?)

	* D (U+0044): X=313.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=217.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=88.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=450.5,Y=702.0 (should be at cap-height 700?)

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

	* R (U+0052): X=306.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=562.0,Y=-1.0 (should be at baseline 0?)

	* T (U+0054): X=39.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=581.0,Y=699.0 (should be at cap-height 700?)

	* a (U+0061): X=361.0,Y=481.5 (should be at x-height 481?)

	* a (U+0061): X=361.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=235.0,Y=-0.5 (should be at baseline 0?)

	* b (U+0062): X=235.0,Y=481.5 (should be at x-height 481?)

	* d (U+0064): X=361.0,Y=481.5 (should be at x-height 481?)

	* d (U+0064): X=361.0,Y=-0.5 (should be at baseline 0?)

	* f (U+0066): X=245.0,Y=698.0 (should be at cap-height 700?)

	* g (U+0067): X=361.0,Y=481.5 (should be at x-height 481?)

	* g (U+0067): X=361.5,Y=-0.5 (should be at baseline 0?)

	* h (U+0068): X=236.5,Y=481.5 (should be at x-height 481?)

	* i (U+0069): X=217.0,Y=741.0 (should be at ascender 740?)

	* j (U+006A): X=216.0,Y=741.0 (should be at ascender 740?)

	* m (U+006D): X=219.0,Y=480.0 (should be at x-height 481?)

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

	* v (U+0076): X=213.0,Y=1.5 (should be at baseline 0?)

	* v (U+0076): X=358.5,Y=1.5 (should be at baseline 0?)

	* y (U+0079): X=214.5,Y=1.5 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=361.0,Y=-0.5 (should be at baseline 0?)

	* tildecomb (U+0303): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1D5B (U+1D5B): X=213.0,Y=1.5 (should be at baseline 0?)

	* uni1D5B (U+1D5B): X=358.5,Y=1.5 (should be at baseline 0?)

	* uni1EA5 (U+1EA5): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EA7 (U+1EA7): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EAB (U+1EAB): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EAF (U+1EAF): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB1 (U+1EB1): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=361.0,Y=-0.5 (should be at baseline 0?)

	* uni1EB5 (U+1EB5): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EC5 (U+1EC5): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED6 (U+1ED6): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED7 (U+1ED7): X=390.0,Y=699.0 (should be at cap-height 700?)

	* uni1EF9 (U+1EF9): X=214.5,Y=1.5 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=385.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=39.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=581.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<89.0,700.0>--<348.0,699.0>>

	* F (U+0046): L<<88.0,701.0>--<502.0,700.0>>

	* H (U+0048): L<<120.0,700.0>--<118.0,409.0>>

	* H (U+0048): L<<518.0,409.0>--<516.0,700.0>>

	* P (U+0050): L<<91.0,701.0>--<375.0,699.0>>

	* P (U+0050): L<<93.0,350.0>--<91.0,701.0>>

	* R (U+0052): L<<94.0,350.0>--<91.0,701.0>>

	* U (U+0055): L<<480.0,194.0>--<478.0,700.0>>

	* U (U+0055): L<<508.0,700.0>--<506.0,302.0>>

	* U (U+0055): L<<58.0,302.0>--<56.0,700.0>>

	* U (U+0055): L<<87.0,700.0>--<85.0,194.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[23] Ojuju-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 460, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

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

	- Glyph name: grave	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: macron	Expected: 1

	- Glyph name: degree	Expected: 2

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: cedilla	Expected: 1

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

	- Glyph name: Itilde	Expected: 2

	- Glyph name: itilde	Expected: 2

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

	- Glyph name: Utilde	Expected: 2

	- Glyph name: utilde	Expected: 2

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EA	Expected: 2

	- Glyph name: uni01EB	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F4	Expected: 2

	- Glyph name: uni01F5	Expected: 3

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: Oslashacute	Expected: 4

	- Glyph name: oslashacute	Expected: 4

	- Glyph name: uni0200	Expected: 4

	- Glyph name: uni0201	Expected: 4

	- Glyph name: uni0202	Expected: 3

	- Glyph name: uni0203	Expected: 3

	- Glyph name: uni0204	Expected: 3

	- Glyph name: uni0205	Expected: 4

	- Glyph name: uni0206	Expected: 2

	- Glyph name: uni0207	Expected: 3

	- Glyph name: uni0208	Expected: 3

	- Glyph name: uni0209	Expected: 3

	- Glyph name: uni020A	Expected: 2

	- Glyph name: uni020B	Expected: 2

	- Glyph name: uni020C	Expected: 4

	- Glyph name: uni020D	Expected: 4

	- Glyph name: uni020E	Expected: 3

	- Glyph name: uni020F	Expected: 3

	- Glyph name: uni0210	Expected: 4

	- Glyph name: uni0211	Expected: 3

	- Glyph name: uni0212	Expected: 3

	- Glyph name: uni0213	Expected: 2

	- Glyph name: uni0214	Expected: 3

	- Glyph name: uni0215	Expected: 3

	- Glyph name: uni0216	Expected: 2

	- Glyph name: uni0217	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: gravecomb	Expected: 1

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: hookabovecomb	Expected: 1

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: dotbelowcomb	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: Dmacronbelow	Expected: 3

	- Glyph name: dmacronbelow	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E1F	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: Lmacronbelow	Expected: 2

	- Glyph name: lmacronbelow	Expected: 2

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: Nmacronbelow	Expected: 2

	- Glyph name: nmacronbelow	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: Rmacronbelow	Expected: 3

	- Glyph name: rmacronbelow	Expected: 2

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: Tmacronbelow	Expected: 2

	- Glyph name: tmacronbelow	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni207F	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

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

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Itilde	Expected: 2

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

	- Glyph name: Oslashacute	Expected: 4

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

	- Glyph name: Utilde	Expected: 2

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

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

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

	- Glyph name: breve	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: circumflex	Expected: 1

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: itilde	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: oslashacute	Expected: 4

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

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: utilde	Expected: 2

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
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, syriac, tai-le, canadian-aboriginal, coptic, malayalam, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, cherokee, syriac, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: myanmar, masaram-gondi, gunjala-gondi, syloti-nagri, chakma, bengali, sharada, tamil, tibetan, tagalog, miao, marchen, sundanese, zanabazar-square, thai, newa, dogra, grantha, mongolian, hebrew, takri, soyombo, nko, devanagari, brahmi, symbols, syriac, oriya, mandaic, psalter-pahlavi, rejang, sogdian, khmer, caucasian-albanian, cham, khojki, osage, meetei-mayek, tai-le, phags-pa, kannada, tirhuta, javanese, hanunoo, hanifi-rohingya, kharoshthi, old-permic, lao, mahajani, music, lepcha, gurmukhi, modi, siddham, buhid, adlam, duployan, manichaean, mende-kikakui, telugu, tagbanwa, sinhala, tai-viet, yi, coptic, wancho, malayalam, math, pahawh-hmong, khudawadi, thaana, tifinagh, bassa-vah, batak, ahom, kaithi, limbu, elbasan, gujarati, bhaiksuki, new-tai-lue, balinese, buginese, kayah-li
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=76.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=226.0,Y=701.0 (should be at cap-height 700?)

	* exclam (U+0021): X=85.5,Y=1.0 (should be at baseline 0?)

	* exclam (U+0021): X=216.0,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=85.5,Y=1.0 (should be at baseline 0?)

	* period (U+002E): X=216.0,Y=1.0 (should be at baseline 0?)

	* six (U+0036): X=526.5,Y=701.0 (should be at cap-height 700?)

	* nine (U+0039): X=341.5,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=374.0,Y=699.0 (should be at cap-height 700?)

	* C (U+0043): X=458.0,Y=701.5 (should be at cap-height 700?)

	* D (U+0044): X=315.0,Y=1.0 (should be at baseline 0?)

	* D (U+0044): X=213.5,Y=0.5 (should be at baseline 0?)

	* F (U+0046): X=78.0,Y=701.0 (should be at cap-height 700?)

	* G (U+0047): X=462.5,Y=702.0 (should be at cap-height 700?)

	* G (U+0047): X=453.5,Y=2.0 (should be at baseline 0?)

	* I (U+0049): X=51.0,Y=699.0 (should be at cap-height 700?)

	* I (U+0049): X=379.0,Y=699.0 (should be at cap-height 700?)

	* L (U+004C): X=78.0,Y=701.0 (should be at cap-height 700?)

	* L (U+004C): X=141.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=81.0,Y=701.0 (should be at cap-height 700?)

	* P (U+0050): X=390.0,Y=699.0 (should be at cap-height 700?)

	* Q (U+0051): X=591.5,Y=-262.0 (should be at descender -260?)

	* R (U+0052): X=81.0,Y=701.0 (should be at cap-height 700?)

	* R (U+0052): X=348.0,Y=699.0 (should be at cap-height 700?)

	* R (U+0052): X=580.0,Y=2.0 (should be at baseline 0?)

	* T (U+0054): X=33.0,Y=699.0 (should be at cap-height 700?)

	* T (U+0054): X=594.0,Y=699.0 (should be at cap-height 700?)

	* k (U+006B): X=415.5,Y=-0.5 (should be at baseline 0?)

	* l (U+006C): X=330.0,Y=2.0 (should be at baseline 0?)

	* m (U+006D): X=229.0,Y=487.5 (should be at x-height 489?)

	* m (U+006D): X=593.0,Y=488.0 (should be at x-height 489?)

	* s (U+0073): X=425.0,Y=490.0 (should be at x-height 489?)

	* u (U+0075): X=51.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=101.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=435.0,Y=488.0 (should be at x-height 489?)

	* u (U+0075): X=486.0,Y=488.0 (should be at x-height 489?)

	* x (U+0078): X=34.0,Y=490.0 (should be at x-height 489?)

	* x (U+0078): X=86.0,Y=490.0 (should be at x-height 489?)

	* x (U+0078): X=378.0,Y=490.0 (should be at x-height 489?)

	* x (U+0078): X=475.0,Y=490.0 (should be at x-height 489?)

	* Cdotaccent (U+010A): X=458.0,Y=701.5 (should be at cap-height 700?)

	* tildecomb (U+0303): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1EAB (U+1EAB): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EB5 (U+1EB5): X=398.0,Y=699.0 (should be at cap-height 700?)

	* uni1EC5 (U+1EC5): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED6 (U+1ED6): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED7 (U+1ED7): X=394.0,Y=699.0 (should be at cap-height 700?)

	* uni1EF9 (U+1EF9): X=346.0,Y=699.0 (should be at cap-height 700?)

	* ellipsis (U+2026): X=105.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=236.0,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=391.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=522.0,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=677.5,Y=1.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=808.0,Y=1.0 (should be at baseline 0?)

	* trademark (U+2122): X=33.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=594.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* three (U+0033) contains a short segment B<<524.0,343.5>-<520.0,332.0>-<520.0,321.0>>

	* three (U+0033) contains a short segment B<<520.0,321.0>-<520.0,311.0>-<524.0,299.5>>

	* E (U+0045) contains a short segment B<<142.0,546.0>-<136.0,540.0>-<133.0,525.5>>

	* E (U+0045) contains a short segment B<<133.0,410.0>-<136.0,395.0>-<142.0,390.0>>

	* E (U+0045) contains a short segment B<<142.0,390.0>-<149.0,380.0>-<159.0,375.5>>

	* K (U+004B) contains a short segment B<<231.0,272.0>-<226.0,285.0>-<220.0,288.0>>

	* K (U+004B) contains a short segment B<<152.5,288.5>-<142.0,286.0>-<137.0,274.0>>

	* K (U+004B) contains a short segment B<<280.5,307.5>-<272.0,303.0>-<275.0,290.0>>

	* M (U+004D) contains a short segment B<<384.5,255.5>-<392.0,250.0>-<403.0,250.0>>

	* M (U+004D) contains a short segment B<<403.0,250.0>-<414.0,250.0>-<422.0,255.5>>

	* M (U+004D) contains a short segment B<<669.0,495.0>-<663.0,510.0>-<650.0,514.0>>

	* M (U+004D) contains a short segment B<<556.0,513.0>-<544.0,508.0>-<536.0,494.0>>

	* M (U+004D) contains a short segment B<<270.0,494.0>-<262.0,508.0>-<250.5,513.0>>

	* M (U+004D) contains a short segment B<<156.5,514.5>-<144.0,511.0>-<138.0,495.0>>

	* N (U+004E) contains a short segment B<<442.0,209.5>-<450.0,200.0>-<462.0,197.0>>

	* W (U+0057) contains a short segment B<<152.0,205.0>-<158.0,190.0>-<168.5,186.0>>

	* W (U+0057) contains a short segment B<<239.0,187.0>-<250.0,192.0>-<258.0,206.0>>

	* W (U+0057) contains a short segment B<<526.0,206.0>-<534.0,192.0>-<545.0,187.0>>

	* W (U+0057) contains a short segment B<<615.5,186.0>-<626.0,190.0>-<633.0,205.0>>

	* W (U+0057) contains a short segment B<<409.5,444.5>-<402.0,450.0>-<391.0,450.0>>

	* W (U+0057) contains a short segment B<<391.0,450.0>-<380.0,450.0>-<372.0,444.5>>

	* X (U+0058) contains a short segment B<<182.0,361.0>-<182.0,370.0>-<179.5,380.0>>

	* X (U+0058) contains a short segment B<<466.5,380.0>-<464.0,370.0>-<464.0,361.0>>

	* Z (U+005A) contains a short segment B<<449.0,474.0>-<456.0,483.0>-<457.0,493.0>>

	* b (U+0062) contains a short segment B<<130.0,412.5>-<133.0,400.0>-<137.0,400.0>>

	* f (U+0066) contains a short segment B<<116.0,498.0>-<116.0,501.0>-<114.0,507.0>>

	* f (U+0066) contains a short segment B<<158.0,504.0>-<157.0,497.0>-<158.0,494.0>>

	* f (U+0066) contains a short segment B<<158.0,494.0>-<159.0,489.0>-<168.0,489.0>>

	* h (U+0068) contains a short segment B<<130.5,405.0>-<133.0,400.0>-<136.0,400.0>>

	* k (U+006B) contains a short segment B<<267.0,267.0>-<257.0,264.0>-<254.5,262.0>>

	* k (U+006B) contains a short segment B<<254.5,262.0>-<252.0,260.0>-<252.0,255.0>>

	* k (U+006B) contains a short segment B<<252.0,255.0>-<252.0,249.0>-<253.5,245.0>>

	* k (U+006B) contains a short segment B<<253.5,245.0>-<255.0,241.0>-<262.0,231.0>>

	* m (U+006D) contains a short segment B<<472.0,409.5>-<479.0,399.0>-<488.0,399.0>>

	* n (U+006E) contains a short segment B<<128.5,405.0>-<131.0,400.0>-<136.0,400.0>>

	* r (U+0072) contains a short segment B<<128.5,394.0>-<131.0,389.0>-<136.0,389.0>>

	* t (U+0074) contains a short segment B<<107.0,369.0>-<103.0,372.0>-<96.0,372.0>>

	* t (U+0074) contains a short segment B<<162.0,372.0>-<158.0,372.0>-<154.5,369.5>>

	* w (U+0077) contains a short segment B<<124.0,153.0>-<128.0,142.0>-<134.0,137.0>>

	* w (U+0077) contains a short segment B<<134.0,137.0>-<140.0,132.0>-<154.0,131.0>>

	* w (U+0077) contains a short segment B<<238.5,131.0>-<253.0,132.0>-<259.0,137.0>>

	* w (U+0077) contains a short segment B<<259.0,137.0>-<265.0,142.0>-<270.0,153.0>>

	* w (U+0077) contains a short segment B<<568.0,131.5>-<582.0,133.0>-<587.5,138.5>>

	* w (U+0077) contains a short segment B<<587.5,138.5>-<593.0,144.0>-<598.0,156.0>>

	* w (U+0077) contains a short segment B<<377.5,350.5>-<371.0,363.0>-<359.0,363.0>>

	* w (U+0077) contains a short segment B<<359.0,363.0>-<348.0,363.0>-<341.0,350.5>>

	* z (U+007A) contains a short segment B<<366.0,357.5>-<368.0,363.0>-<368.0,371.0>>

	* z (U+007A) contains a short segment B<<368.0,371.0>-<368.0,381.0>-<364.0,385.0>>

	* z (U+007A) contains a short segment B<<137.5,103.0>-<135.0,98.0>-<135.0,89.0>>

	* z (U+007A) contains a short segment B<<135.0,89.0>-<135.0,80.0>-<144.0,78.5>>

	* uni02B0 (U+02B0) contains a short segment B<<130.5,405.0>-<133.0,400.0>-<136.0,400.0>>

	* uni02B7 (U+02B7) contains a short segment B<<124.0,153.0>-<128.0,142.0>-<134.0,137.0>>

	* uni02B7 (U+02B7) contains a short segment B<<134.0,137.0>-<140.0,132.0>-<154.0,131.0>>

	* uni02B7 (U+02B7) contains a short segment B<<238.5,131.0>-<253.0,132.0>-<259.0,137.0>>

	* uni02B7 (U+02B7) contains a short segment B<<259.0,137.0>-<265.0,142.0>-<270.0,153.0>>

	* uni02B7 (U+02B7) contains a short segment B<<568.0,131.5>-<582.0,133.0>-<587.5,138.5>>

	* uni02B7 (U+02B7) contains a short segment B<<587.5,138.5>-<593.0,144.0>-<598.0,156.0>>

	* uni02B7 (U+02B7) contains a short segment B<<377.5,350.5>-<371.0,363.0>-<359.0,363.0>>

	* uni02B7 (U+02B7) contains a short segment B<<359.0,363.0>-<348.0,363.0>-<341.0,350.5>>

	* uni1DBB (U+1DBB) contains a short segment B<<366.0,357.5>-<368.0,363.0>-<368.0,371.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<368.0,371.0>-<368.0,381.0>-<364.0,385.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<137.5,103.0>-<135.0,98.0>-<135.0,89.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<135.0,89.0>-<135.0,80.0>-<144.0,78.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<142.0,546.0>-<136.0,540.0>-<133.0,525.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<133.0,410.0>-<136.0,395.0>-<142.0,390.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<142.0,390.0>-<149.0,380.0>-<159.0,375.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<142.0,546.0>-<136.0,540.0>-<133.0,525.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<133.0,410.0>-<136.0,395.0>-<142.0,390.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<142.0,390.0>-<149.0,380.0>-<159.0,375.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<142.0,546.0>-<136.0,540.0>-<133.0,525.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<133.0,410.0>-<136.0,395.0>-<142.0,390.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<142.0,390.0>-<149.0,380.0>-<159.0,375.5>>

	* trademark (U+2122) contains a short segment B<<1025.5,255.5>-<1033.0,250.0>-<1044.0,250.0>>

	* trademark (U+2122) contains a short segment B<<1044.0,250.0>-<1055.0,250.0>-<1063.0,255.5>>

	* trademark (U+2122) contains a short segment B<<1310.0,495.0>-<1304.0,510.0>-<1291.0,514.0>>

	* trademark (U+2122) contains a short segment B<<1197.0,513.0>-<1185.0,508.0>-<1177.0,494.0>>

	* trademark (U+2122) contains a short segment B<<911.0,494.0>-<903.0,508.0>-<891.5,513.0>>

	* trademark (U+2122) contains a short segment B<<797.5,514.5>-<785.0,511.0>-<779.0,495.0>>

	* estimated (U+212E) contains a short segment B<<197.0,336.0>-<190.0,336.0>-<186.0,333.5>>

	* estimated (U+212E) contains a short segment B<<186.0,333.5>-<182.0,331.0>-<182.0,318.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<78.0,700.0>--<374.0,699.0>>

	* F (U+0046): L<<533.0,700.0>--<532.0,567.0>>

	* F (U+0046): L<<78.0,701.0>--<533.0,700.0>>

	* P (U+0050): L<<81.0,701.0>--<390.0,699.0>>

	* P (U+0050): L<<83.0,350.0>--<81.0,701.0>>

	* R (U+0052): L<<81.0,701.0>--<348.0,699.0>>

	* R (U+0052): L<<84.0,350.0>--<81.0,701.0>>

	* S (U+0053): L<<56.0,12.0>--<55.0,136.0>>

	* U (U+0055): L<<113.0,700.0>--<110.0,286.0>>

	* U (U+0055): L<<52.0,305.0>--<51.0,700.0>>

	* U (U+0055): L<<545.0,700.0>--<542.0,302.0>>

	* l (U+006C): L<<6.0,619.0>--<5.0,740.0>>

	* r (U+0072): L<<377.0,502.0>--<376.0,360.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[23] Ojuju-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:registered_vendor_ids> had an error: ModuleNotFoundError: No module named 'bs4'
</div></details><details><summary>💔 <b>ERROR:</b> Show hinting filesize impact. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/hinting_impact">com.google.fonts/check/hinting_impact</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:hinting_stats> had an error: ModuleNotFoundError: No module named 'dehinter'
</div></details><details><summary>💔 <b>ERROR:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 💔 **ERROR** Failed with ModuleNotFoundError: No module named 'shaperglot'
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


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 460, but got 260 instead [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (740) and hhea ascent (940) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Do we have the latest version of FontBakery installed? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/fontbakery_version">com.google.fonts/check/fontbakery_version</a>)</summary><div>


* 🔥 **FAIL** Current FontBakery version is 0.9.2, while a newer 0.10.4 is already available. Please upgrade it with 'pip install -U fontbakery' [code: outdated-fontbakery]
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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: seven	Expected: 1

	- Glyph name: eight	Expected: 3

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

	- Glyph name: grave	Expected: 1

	- Glyph name: braceleft	Expected: 1

	- Glyph name: bar	Expected: 1

	- Glyph name: braceright	Expected: 1

	- Glyph name: asciitilde	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: yen	Expected: 1 or 2

	- Glyph name: section	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: copyright	Expected: 3

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: registered	Expected: 3 or 4

	- Glyph name: macron	Expected: 1

	- Glyph name: degree	Expected: 2

	- Glyph name: acute	Expected: 1

	- Glyph name: paragraph	Expected: 1, 2 or 3

	- Glyph name: periodcentered	Expected: 1

	- Glyph name: cedilla	Expected: 1

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

	- Glyph name: Itilde	Expected: 2

	- Glyph name: itilde	Expected: 2

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

	- Glyph name: Utilde	Expected: 2

	- Glyph name: utilde	Expected: 2

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: Dtail	Expected: 2

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: florin	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: Gammalatin	Expected: 2

	- Glyph name: Iotalatin	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: nlongrightleg	Expected: 1

	- Glyph name: Obarred	Expected: 3

	- Glyph name: Ohorn	Expected: 2 or 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: Uhorn	Expected: 1

	- Glyph name: uhorn	Expected: 1

	- Glyph name: Upsilonlatin	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EA	Expected: 2

	- Glyph name: uni01EB	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F4	Expected: 2

	- Glyph name: uni01F5	Expected: 3

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: Oslashacute	Expected: 4

	- Glyph name: oslashacute	Expected: 4

	- Glyph name: uni0200	Expected: 4

	- Glyph name: uni0201	Expected: 4

	- Glyph name: uni0202	Expected: 3

	- Glyph name: uni0203	Expected: 3

	- Glyph name: uni0204	Expected: 3

	- Glyph name: uni0205	Expected: 4

	- Glyph name: uni0206	Expected: 2

	- Glyph name: uni0207	Expected: 3

	- Glyph name: uni0208	Expected: 3

	- Glyph name: uni0209	Expected: 3

	- Glyph name: uni020A	Expected: 2

	- Glyph name: uni020B	Expected: 2

	- Glyph name: uni020C	Expected: 4

	- Glyph name: uni020D	Expected: 4

	- Glyph name: uni020E	Expected: 3

	- Glyph name: uni020F	Expected: 3

	- Glyph name: uni0210	Expected: 4

	- Glyph name: uni0211	Expected: 3

	- Glyph name: uni0212	Expected: 3

	- Glyph name: uni0213	Expected: 2

	- Glyph name: uni0214	Expected: 3

	- Glyph name: uni0215	Expected: 3

	- Glyph name: uni0216	Expected: 2

	- Glyph name: uni0217	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: Glottalstopsmall	Expected: 1

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: circumflex	Expected: 1

	- Glyph name: caron	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: breve	Expected: 1

	- Glyph name: dotaccent	Expected: 1

	- Glyph name: ring	Expected: 2

	- Glyph name: ogonek	Expected: 1

	- Glyph name: tilde	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: gravecomb	Expected: 1

	- Glyph name: acutecomb	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: hookabovecomb	Expected: 1

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: dotbelowcomb	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni0334	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: Dmacronbelow	Expected: 3

	- Glyph name: dmacronbelow	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E1F	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: Lmacronbelow	Expected: 2

	- Glyph name: lmacronbelow	Expected: 2

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: Nmacronbelow	Expected: 2

	- Glyph name: nmacronbelow	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: Rmacronbelow	Expected: 3

	- Glyph name: rmacronbelow	Expected: 2

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: Tmacronbelow	Expected: 2

	- Glyph name: tmacronbelow	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: Wgrave	Expected: 2

	- Glyph name: wgrave	Expected: 2

	- Glyph name: Wacute	Expected: 2

	- Glyph name: wacute	Expected: 2

	- Glyph name: Wdieresis	Expected: 3

	- Glyph name: wdieresis	Expected: 3

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni207F	Expected: 1

	- Glyph name: Euro	Expected: 1 or 2

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

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

	- Glyph name: Gcaron	Expected: 2

	- Glyph name: Gdotaccent	Expected: 2

	- Glyph name: Hbar	Expected: 2

	- Glyph name: Iacute	Expected: 2

	- Glyph name: Icircumflex	Expected: 2

	- Glyph name: Idieresis	Expected: 3

	- Glyph name: Idotaccent	Expected: 2

	- Glyph name: Igrave	Expected: 2

	- Glyph name: Imacron	Expected: 2

	- Glyph name: Iogonek	Expected: 1 or 2

	- Glyph name: Itilde	Expected: 2

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

	- Glyph name: Oslashacute	Expected: 4

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

	- Glyph name: Utilde	Expected: 2

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

	- Glyph name: acute	Expected: 1

	- Glyph name: adieresis	Expected: 4

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

	- Glyph name: breve	Expected: 1

	- Glyph name: bullet	Expected: 1

	- Glyph name: cacute	Expected: 2

	- Glyph name: caron	Expected: 1

	- Glyph name: ccaron	Expected: 2

	- Glyph name: ccedilla	Expected: 1 or 2

	- Glyph name: cdotaccent	Expected: 2

	- Glyph name: cedilla	Expected: 1

	- Glyph name: cent	Expected: 1 or 2

	- Glyph name: circumflex	Expected: 1

	- Glyph name: copyright	Expected: 3

	- Glyph name: dcaron	Expected: 3

	- Glyph name: dcroat	Expected: 2

	- Glyph name: degree	Expected: 2

	- Glyph name: dieresis	Expected: 2

	- Glyph name: divide	Expected: 3

	- Glyph name: dollar	Expected: 1, 3 or 5

	- Glyph name: dotaccent	Expected: 1

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

	- Glyph name: four	Expected: 1 or 2

	- Glyph name: gbreve	Expected: 3 or 4

	- Glyph name: gcaron	Expected: 3 or 4

	- Glyph name: gdotaccent	Expected: 3 or 4

	- Glyph name: germandbls	Expected: 1

	- Glyph name: grave	Expected: 1

	- Glyph name: greater	Expected: 1

	- Glyph name: guillemotleft	Expected: 2

	- Glyph name: guillemotright	Expected: 2

	- Glyph name: guilsinglleft	Expected: 1

	- Glyph name: guilsinglright	Expected: 1

	- Glyph name: hbar	Expected: 1

	- Glyph name: hungarumlaut	Expected: 2

	- Glyph name: iacute	Expected: 2

	- Glyph name: icircumflex	Expected: 2

	- Glyph name: idieresis	Expected: 3

	- Glyph name: igrave	Expected: 2

	- Glyph name: imacron	Expected: 2

	- Glyph name: iogonek	Expected: 2 or 3

	- Glyph name: itilde	Expected: 2

	- Glyph name: lacute	Expected: 2

	- Glyph name: lcaron	Expected: 2

	- Glyph name: less	Expected: 1

	- Glyph name: lslash	Expected: 1

	- Glyph name: macron	Expected: 1

	- Glyph name: minus	Expected: 1

	- Glyph name: multiply	Expected: 1

	- Glyph name: nacute	Expected: 2

	- Glyph name: ncaron	Expected: 2

	- Glyph name: ntilde	Expected: 2

	- Glyph name: numbersign	Expected: 2

	- Glyph name: oacute	Expected: 3

	- Glyph name: ocircumflex	Expected: 3

	- Glyph name: odieresis	Expected: 4

	- Glyph name: oe	Expected: 3

	- Glyph name: ogonek	Expected: 1

	- Glyph name: ograve	Expected: 3

	- Glyph name: ohorn	Expected: 2

	- Glyph name: ohungarumlaut	Expected: 4

	- Glyph name: omacron	Expected: 3

	- Glyph name: oslash	Expected: 3

	- Glyph name: oslashacute	Expected: 4

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

	- Glyph name: ring	Expected: 2

	- Glyph name: sacute	Expected: 2

	- Glyph name: scaron	Expected: 2

	- Glyph name: section	Expected: 2

	- Glyph name: seven	Expected: 1

	- Glyph name: slash	Expected: 1

	- Glyph name: sterling	Expected: 1 or 2

	- Glyph name: tcaron	Expected: 2

	- Glyph name: thorn	Expected: 2

	- Glyph name: tilde	Expected: 1

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

	- Glyph name: uni0180	Expected: 2

	- Glyph name: uni0181	Expected: 3

	- Glyph name: uni0186	Expected: 1

	- Glyph name: uni0187	Expected: 1

	- Glyph name: uni0188	Expected: 1

	- Glyph name: uni018A	Expected: 2

	- Glyph name: uni018E	Expected: 1

	- Glyph name: uni018F	Expected: 2

	- Glyph name: uni0190	Expected: 1

	- Glyph name: uni0191	Expected: 1

	- Glyph name: uni0193	Expected: 1

	- Glyph name: uni0197	Expected: 1

	- Glyph name: uni0198	Expected: 1

	- Glyph name: uni0199	Expected: 1

	- Glyph name: uni019A	Expected: 1

	- Glyph name: uni019B	Expected: 1

	- Glyph name: uni019C	Expected: 1

	- Glyph name: uni019D	Expected: 1

	- Glyph name: uni01A4	Expected: 2

	- Glyph name: uni01A5	Expected: 2

	- Glyph name: uni01A9	Expected: 1

	- Glyph name: uni01AC	Expected: 1

	- Glyph name: uni01AD	Expected: 1

	- Glyph name: uni01AE	Expected: 1

	- Glyph name: uni01B2	Expected: 1

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

	- Glyph name: uni01CD	Expected: 3

	- Glyph name: uni01CE	Expected: 3

	- Glyph name: uni01CF	Expected: 2

	- Glyph name: uni01D0	Expected: 2

	- Glyph name: uni01D1	Expected: 3

	- Glyph name: uni01D2	Expected: 3

	- Glyph name: uni01D3	Expected: 2

	- Glyph name: uni01D4	Expected: 2

	- Glyph name: uni01D5	Expected: 4

	- Glyph name: uni01D6	Expected: 4

	- Glyph name: uni01D7	Expected: 4

	- Glyph name: uni01D8	Expected: 4

	- Glyph name: uni01D9	Expected: 4

	- Glyph name: uni01DA	Expected: 4

	- Glyph name: uni01DB	Expected: 4

	- Glyph name: uni01DC	Expected: 4

	- Glyph name: uni01DD	Expected: 2

	- Glyph name: uni01DE	Expected: 5

	- Glyph name: uni01DF	Expected: 5

	- Glyph name: uni01E0	Expected: 4

	- Glyph name: uni01E1	Expected: 4

	- Glyph name: uni01E2	Expected: 3

	- Glyph name: uni01E3	Expected: 4

	- Glyph name: uni01E4	Expected: 1

	- Glyph name: uni01E5	Expected: 2

	- Glyph name: uni01E8	Expected: 2

	- Glyph name: uni01E9	Expected: 2

	- Glyph name: uni01EC	Expected: 3

	- Glyph name: uni01ED	Expected: 3

	- Glyph name: uni01EE	Expected: 2

	- Glyph name: uni01EF	Expected: 2

	- Glyph name: uni01F8	Expected: 2

	- Glyph name: uni01F9	Expected: 2

	- Glyph name: uni0218	Expected: 2

	- Glyph name: uni0219	Expected: 2

	- Glyph name: uni021A	Expected: 2

	- Glyph name: uni021B	Expected: 2

	- Glyph name: uni021E	Expected: 2

	- Glyph name: uni021F	Expected: 2

	- Glyph name: uni0220	Expected: 1

	- Glyph name: uni0222	Expected: 2

	- Glyph name: uni0223	Expected: 2

	- Glyph name: uni0226	Expected: 3

	- Glyph name: uni0227	Expected: 3

	- Glyph name: uni0228	Expected: 1

	- Glyph name: uni0229	Expected: 2

	- Glyph name: uni022A	Expected: 5

	- Glyph name: uni022B	Expected: 5

	- Glyph name: uni022C	Expected: 4

	- Glyph name: uni022D	Expected: 4

	- Glyph name: uni022E	Expected: 3

	- Glyph name: uni022F	Expected: 3

	- Glyph name: uni0230	Expected: 4

	- Glyph name: uni0231	Expected: 4

	- Glyph name: uni0232	Expected: 2

	- Glyph name: uni0233	Expected: 2

	- Glyph name: uni0237	Expected: 1

	- Glyph name: uni023A	Expected: 3

	- Glyph name: uni023B	Expected: 2

	- Glyph name: uni023C	Expected: 2

	- Glyph name: uni023D	Expected: 1

	- Glyph name: uni023E	Expected: 2

	- Glyph name: uni0242	Expected: 1

	- Glyph name: uni0243	Expected: 3

	- Glyph name: uni0244	Expected: 2

	- Glyph name: uni0245	Expected: 1

	- Glyph name: uni0246	Expected: 3

	- Glyph name: uni0247	Expected: 4

	- Glyph name: uni0248	Expected: 1

	- Glyph name: uni0249	Expected: 2

	- Glyph name: uni024A	Expected: 2

	- Glyph name: uni024B	Expected: 2

	- Glyph name: uni024C	Expected: 2

	- Glyph name: uni024D	Expected: 1

	- Glyph name: uni024E	Expected: 2

	- Glyph name: uni024F	Expected: 2

	- Glyph name: uni0251	Expected: 2

	- Glyph name: uni0259	Expected: 2

	- Glyph name: uni0272	Expected: 1

	- Glyph name: uni0292	Expected: 1

	- Glyph name: uni02BB	Expected: 1

	- Glyph name: uni02BC	Expected: 1

	- Glyph name: uni02BE	Expected: 1

	- Glyph name: uni02BF	Expected: 1

	- Glyph name: uni02CA	Expected: 1

	- Glyph name: uni02CB	Expected: 1

	- Glyph name: uni0302	Expected: 1

	- Glyph name: uni0304	Expected: 1

	- Glyph name: uni0306	Expected: 1

	- Glyph name: uni0308	Expected: 2

	- Glyph name: uni030A	Expected: 2

	- Glyph name: uni030B	Expected: 2

	- Glyph name: uni030C	Expected: 1

	- Glyph name: uni030F	Expected: 2

	- Glyph name: uni0311	Expected: 1

	- Glyph name: uni0312	Expected: 1

	- Glyph name: uni0313	Expected: 1

	- Glyph name: uni031B	Expected: 1

	- Glyph name: uni0325	Expected: 2

	- Glyph name: uni0326	Expected: 1

	- Glyph name: uni0327	Expected: 1

	- Glyph name: uni0328	Expected: 1

	- Glyph name: uni0329	Expected: 1

	- Glyph name: uni0331	Expected: 1

	- Glyph name: uni1E00	Expected: 4

	- Glyph name: uni1E01	Expected: 4

	- Glyph name: uni1E02	Expected: 4

	- Glyph name: uni1E03	Expected: 3

	- Glyph name: uni1E08	Expected: 2

	- Glyph name: uni1E09	Expected: 2

	- Glyph name: uni1E0A	Expected: 3

	- Glyph name: uni1E0B	Expected: 3

	- Glyph name: uni1E0C	Expected: 3

	- Glyph name: uni1E0D	Expected: 3

	- Glyph name: uni1E14	Expected: 3

	- Glyph name: uni1E15	Expected: 4

	- Glyph name: uni1E16	Expected: 3

	- Glyph name: uni1E17	Expected: 4

	- Glyph name: uni1E1C	Expected: 2

	- Glyph name: uni1E1D	Expected: 3

	- Glyph name: uni1E1E	Expected: 2

	- Glyph name: uni1E20	Expected: 2

	- Glyph name: uni1E21	Expected: 3 or 4

	- Glyph name: uni1E24	Expected: 2

	- Glyph name: uni1E25	Expected: 2

	- Glyph name: uni1E2A	Expected: 2

	- Glyph name: uni1E2B	Expected: 2

	- Glyph name: uni1E2E	Expected: 4

	- Glyph name: uni1E2F	Expected: 4

	- Glyph name: uni1E36	Expected: 2

	- Glyph name: uni1E37	Expected: 2

	- Glyph name: uni1E38	Expected: 3

	- Glyph name: uni1E39	Expected: 3

	- Glyph name: uni1E3E	Expected: 2

	- Glyph name: uni1E3F	Expected: 2

	- Glyph name: uni1E40	Expected: 2

	- Glyph name: uni1E41	Expected: 2

	- Glyph name: uni1E42	Expected: 2

	- Glyph name: uni1E43	Expected: 2

	- Glyph name: uni1E44	Expected: 2

	- Glyph name: uni1E45	Expected: 2

	- Glyph name: uni1E46	Expected: 2

	- Glyph name: uni1E47	Expected: 2

	- Glyph name: uni1E4C	Expected: 4

	- Glyph name: uni1E4D	Expected: 4

	- Glyph name: uni1E4E	Expected: 5

	- Glyph name: uni1E4F	Expected: 5

	- Glyph name: uni1E50	Expected: 4

	- Glyph name: uni1E51	Expected: 4

	- Glyph name: uni1E52	Expected: 4

	- Glyph name: uni1E53	Expected: 4

	- Glyph name: uni1E56	Expected: 3

	- Glyph name: uni1E57	Expected: 3

	- Glyph name: uni1E5A	Expected: 3

	- Glyph name: uni1E5B	Expected: 2

	- Glyph name: uni1E5C	Expected: 4

	- Glyph name: uni1E5D	Expected: 3

	- Glyph name: uni1E60	Expected: 2

	- Glyph name: uni1E61	Expected: 2

	- Glyph name: uni1E62	Expected: 2

	- Glyph name: uni1E63	Expected: 2

	- Glyph name: uni1E64	Expected: 3

	- Glyph name: uni1E65	Expected: 3

	- Glyph name: uni1E66	Expected: 3

	- Glyph name: uni1E67	Expected: 3

	- Glyph name: uni1E68	Expected: 3

	- Glyph name: uni1E69	Expected: 3

	- Glyph name: uni1E6A	Expected: 2

	- Glyph name: uni1E6B	Expected: 2

	- Glyph name: uni1E6C	Expected: 2

	- Glyph name: uni1E6D	Expected: 2

	- Glyph name: uni1E78	Expected: 3

	- Glyph name: uni1E79	Expected: 3

	- Glyph name: uni1E7A	Expected: 4

	- Glyph name: uni1E7B	Expected: 4

	- Glyph name: uni1E8E	Expected: 2

	- Glyph name: uni1E8F	Expected: 2

	- Glyph name: uni1E92	Expected: 2

	- Glyph name: uni1E93	Expected: 2

	- Glyph name: uni1E9E	Expected: 1

	- Glyph name: uni1EA0	Expected: 3

	- Glyph name: uni1EA1	Expected: 3

	- Glyph name: uni1EA2	Expected: 3

	- Glyph name: uni1EA3	Expected: 3

	- Glyph name: uni1EA8	Expected: 4

	- Glyph name: uni1EA9	Expected: 4

	- Glyph name: uni1EAC	Expected: 4

	- Glyph name: uni1EAD	Expected: 4

	- Glyph name: uni1EB2	Expected: 4

	- Glyph name: uni1EB3	Expected: 4

	- Glyph name: uni1EB6	Expected: 4

	- Glyph name: uni1EB7	Expected: 4

	- Glyph name: uni1EB8	Expected: 2

	- Glyph name: uni1EB9	Expected: 3

	- Glyph name: uni1EBA	Expected: 2

	- Glyph name: uni1EBB	Expected: 3

	- Glyph name: uni1EBC	Expected: 2

	- Glyph name: uni1EBD	Expected: 3

	- Glyph name: uni1EC2	Expected: 3

	- Glyph name: uni1EC3	Expected: 4

	- Glyph name: uni1EC6	Expected: 3

	- Glyph name: uni1EC7	Expected: 4

	- Glyph name: uni1EC8	Expected: 2

	- Glyph name: uni1EC9	Expected: 2

	- Glyph name: uni1ECA	Expected: 2

	- Glyph name: uni1ECB	Expected: 3

	- Glyph name: uni1ECC	Expected: 3

	- Glyph name: uni1ECD	Expected: 3

	- Glyph name: uni1ECE	Expected: 3

	- Glyph name: uni1ECF	Expected: 3

	- Glyph name: uni1ED4	Expected: 4

	- Glyph name: uni1ED5	Expected: 4

	- Glyph name: uni1ED8	Expected: 4

	- Glyph name: uni1ED9	Expected: 4

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

	- Glyph name: uni1EE4	Expected: 2

	- Glyph name: uni1EE5	Expected: 2

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

	- Glyph name: uni20AD	Expected: 1

	- Glyph name: uniA78B	Expected: 1

	- Glyph name: uniA78C	Expected: 1

	- Glyph name: uogonek	Expected: 1

	- Glyph name: uring	Expected: 3

	- Glyph name: utilde	Expected: 2

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
 [code: no-contour]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4

	- Glyph name: ae	Contours detected: 4	Expected: 3

	- Glyph name: uni1EA4	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA5	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA6	Contours detected: 2	Expected: 4

	- Glyph name: uni1EA7	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAA	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAB	Contours detected: 3	Expected: 4

	- Glyph name: uni1EAE	Contours detected: 2	Expected: 4

	- Glyph name: uni1EAF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB0	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EB4	Contours detected: 3	Expected: 4

	- Glyph name: uni1EB5	Contours detected: 3	Expected: 4

	- Glyph name: uni1EBE	Contours detected: 1	Expected: 3

	- Glyph name: uni1EBF	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC0	Contours detected: 1	Expected: 3

	- Glyph name: uni1EC1	Contours detected: 2	Expected: 4

	- Glyph name: uni1EC4	Contours detected: 2	Expected: 3

	- Glyph name: uni1EC5	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED0	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED1	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED2	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED3	Contours detected: 2	Expected: 4

	- Glyph name: uni1ED6	Contours detected: 3	Expected: 4

	- Glyph name: uni1ED7	Contours detected: 3	Expected: 4
 [code: contour-count]
</div></details><details><summary>🔥 <b>FAIL:</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/glyf.html#com.google.fonts/check/glyf_non_transformed_duplicate_components">com.google.fonts/check/glyf_non_transformed_duplicate_components</a>)</summary><div>


* 🔥 **FAIL** The following glyphs have duplicate components which have the same x,y coordinates:
	* {'glyph': 'quotedblbase', 'component': 'comma', 'x': 0, 'y': 0} [code: found-duplicates]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x1D3A (MODIFIER LETTER CAPITAL N)


	- 0x0114 (LATIN CAPITAL LETTER E WITH BREVE)


	- 0x012C (LATIN CAPITAL LETTER I WITH BREVE)


	- 0x014E (LATIN CAPITAL LETTER O WITH BREVE)


	- 0x0115 (LATIN SMALL LETTER E WITH BREVE)


	- 0x012D (LATIN SMALL LETTER I WITH BREVE)


	- 0x014F (LATIN SMALL LETTER O WITH BREVE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_Latin_Beyond is almost fulfilled. Missing codepoints:

	- 0x03BB (GREEK SMALL LETTER LAMDA)


	- 0x03C7 (GREEK SMALL LETTER CHI)


	- 0x0108 (LATIN CAPITAL LETTER C WITH CIRCUMFLEX)


	- 0x011C (LATIN CAPITAL LETTER G WITH CIRCUMFLEX)


	- 0x0124 (LATIN CAPITAL LETTER H WITH CIRCUMFLEX)


	- 0x0134 (LATIN CAPITAL LETTER J WITH CIRCUMFLEX)


	- 0x015C (LATIN CAPITAL LETTER S WITH CIRCUMFLEX)


	- 0x0166 (LATIN CAPITAL LETTER T WITH STROKE)


	- 0x0162 (LATIN CAPITAL LETTER T WITH CEDILLA)


	- 0x0109 (LATIN SMALL LETTER C WITH CIRCUMFLEX)


	- 0x011D (LATIN SMALL LETTER G WITH CIRCUMFLEX)


	- 0x0125 (LATIN SMALL LETTER H WITH CIRCUMFLEX)


	- 0x01F0 (LATIN SMALL LETTER J WITH CARON)


	- 0x0135 (LATIN SMALL LETTER J WITH CIRCUMFLEX)


	- 0x0138 (LATIN SMALL LETTER KRA)


	- 0x015D (LATIN SMALL LETTER S WITH CIRCUMFLEX)


	- 0x0167 (LATIN SMALL LETTER T WITH STROKE)


	- 0x0163 (LATIN SMALL LETTER T WITH CEDILLA)


	- 0x02B8 (MODIFIER LETTER SMALL Y)


	- 0x1DBF (MODIFIER LETTER SMALL THETA)


	- 0x2144 (TURNED SANS-SERIF CAPITAL Y)


	- 0x0315 (COMBINING COMMA ABOVE RIGHT)


	- 0x0335 (COMBINING SHORT STROKE OVERLAY)


	- 0x02B9 (MODIFIER LETTER PRIME)


	- 0x02C8 (MODIFIER LETTER VERTICAL LINE)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)


	- 0x1E97 (LATIN SMALL LETTER T WITH DIAERESIS)


	- 0x032E (COMBINING BREVE BELOW)


	- 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B0 MODIFIER LETTER SMALL H: not included in any glyphset definition
 * U+02B7 MODIFIER LETTER SMALL W: not included in any glyphset definition
 * U+02BE MODIFIER LETTER RIGHT HALF RING: not included in any glyphset definition
 * U+02BF MODIFIER LETTER LEFT HALF RING: not included in any glyphset definition
 * U+02C0 MODIFIER LETTER GLOTTAL STOP: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: yi, tifinagh, canadian-aboriginal
 * U+02CA MODIFIER LETTER ACUTE ACCENT: not included in any glyphset definition
 * U+02CB MODIFIER LETTER GRAVE ACCENT: not included in any glyphset definition
 * U+02D7 MODIFIER LETTER MINUS SIGN: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+02EE MODIFIER LETTER DOUBLE APOSTROPHE: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: tifinagh, old-permic, syriac, tai-le, canadian-aboriginal, coptic, malayalam, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+030D COMBINING VERTICAL LINE ABOVE: not included in any glyphset definition
 * U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition
 * U+0310 COMBINING CANDRABINDU: not included in any glyphset definition
 * U+0311 COMBINING INVERTED BREVE: try adding coptic
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0313 COMBINING COMMA ABOVE: try adding old-permic
 * U+031B COMBINING HORN: not included in any glyphset definition
 * U+0325 COMBINING RING BELOW: try adding syriac
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding syriac
 * U+032F COMBINING INVERTED BREVE BELOW: not included in any glyphset definition
 * U+0330 COMBINING TILDE BELOW: try adding one of: syriac, math, cherokee
 * U+0331 COMBINING MACRON BELOW: try adding one of: tifinagh, gothic, cherokee, syriac, caucasian-albanian
 * U+0332 COMBINING LOW LINE: not included in any glyphset definition
 * U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition
 * U+0358 COMBINING DOT ABOVE RIGHT: try adding osage
 * U+1D58 MODIFIER LETTER SMALL U: not included in any glyphset definition
 * U+1D5B MODIFIER LETTER SMALL V: not included in any glyphset definition
 * U+1D7D LATIN SMALL LETTER P WITH STROKE: not included in any glyphset definition
 * U+1DBB MODIFIER LETTER SMALL Z: not included in any glyphset definition
 * U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition
 * U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition
 * U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition
 * U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition
 * U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition
 * U+207F SUPERSCRIPT LATIN SMALL LETTER N: not included in any glyphset definition
 * U+212E ESTIMATED SYMBOL: not included in any glyphset definition
 * U+25CA LOZENGE: try adding one of: math, symbols
 * U+25CC DOTTED CIRCLE: try adding one of: myanmar, masaram-gondi, gunjala-gondi, syloti-nagri, chakma, bengali, sharada, tamil, tibetan, tagalog, miao, marchen, sundanese, zanabazar-square, thai, newa, dogra, grantha, mongolian, hebrew, takri, soyombo, nko, devanagari, brahmi, symbols, syriac, oriya, mandaic, psalter-pahlavi, rejang, sogdian, khmer, caucasian-albanian, cham, khojki, osage, meetei-mayek, tai-le, phags-pa, kannada, tirhuta, javanese, hanunoo, hanifi-rohingya, kharoshthi, old-permic, lao, mahajani, music, lepcha, gurmukhi, modi, siddham, buhid, adlam, duployan, manichaean, mende-kikakui, telugu, tagbanwa, sinhala, tai-viet, yi, coptic, wancho, malayalam, math, pahawh-hmong, khudawadi, thaana, tifinagh, bassa-vah, batak, ahom, kaithi, limbu, elbasan, gujarati, bhaiksuki, new-tai-lue, balinese, buginese, kayah-li
 * U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `vietnamese` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Font has old ttfautohint applied? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/old_ttfautohint">com.google.fonts/check/old_ttfautohint</a>)</summary><div>


* ⚠ **WARN** ttfautohint used in font = 1.8.3; latest = 1.8.4; Need to re-run with the newer version! [code: old-ttfa]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- e.ss01

	- i.loclTRK

	- m.alt

	- n.alt

	- periodcentered.loclCAT

	- periodcentered.loclCAT.case

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

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Checking post.italicAngle value. (derived from com.google.fonts/check/italic_angle) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/post.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* ⚠ **WARN** The following glyphs were present but did not contain any outlines: bar, bracketleft [code: empty-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=46.0,Y=702.0 (should be at cap-height 700?)

	* exclam (U+0021): X=297.0,Y=702.0 (should be at cap-height 700?)

	* six (U+0036): X=526.5,Y=701.0 (should be at cap-height 700?)

	* nine (U+0039): X=341.5,Y=-1.0 (should be at baseline 0?)

	* B (U+0042): X=62.0,Y=701.0 (should be at cap-height 700?)

	* B (U+0042): X=414.0,Y=699.0 (should be at cap-height 700?)

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

	* f (U+0066): X=206.0,Y=501.5 (should be at x-height 500?)

	* h (U+0068): X=452.0,Y=501.0 (should be at x-height 500?)

	* k (U+006B): X=344.5,Y=-1.5 (should be at baseline 0?)

	* l (U+006C): X=132.5,Y=500.5 (should be at x-height 500?)

	* l (U+006C): X=13.0,Y=501.0 (should be at x-height 500?)

	* m (U+006D): X=243.5,Y=499.0 (should be at x-height 500?)

	* n (U+006E): X=452.0,Y=501.0 (should be at x-height 500?)

	* s (U+0073): X=460.0,Y=502.0 (should be at x-height 500?)

	* ae (U+00E6): X=859.0,Y=2.0 (should be at baseline 0?)

	* tildecomb (U+0303): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1EAB (U+1EAB): X=397.0,Y=699.0 (should be at cap-height 700?)

	* uni1EB5 (U+1EB5): X=397.0,Y=699.0 (should be at cap-height 700?)

	* uni1EBF (U+1EBF): X=504.0,Y=2.0 (should be at baseline 0?)

	* uni1EC1 (U+1EC1): X=504.0,Y=2.0 (should be at baseline 0?)

	* uni1EC5 (U+1EC5): X=504.0,Y=2.0 (should be at baseline 0?)

	* uni1EC5 (U+1EC5): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED6 (U+1ED6): X=288.0,Y=699.0 (should be at cap-height 700?)

	* uni1ED7 (U+1ED7): X=400.0,Y=699.0 (should be at cap-height 700?)

	* uni1EF8 (U+1EF8): X=350.5,Y=1.5 (should be at baseline 0?)

	* uni1EF9 (U+1EF9): X=288.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=24.0,Y=699.0 (should be at cap-height 700?)

	* trademark (U+2122): X=613.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* three (U+0033) contains a short segment B<<524.0,343.5>-<520.0,332.0>-<520.0,321.0>>

	* three (U+0033) contains a short segment B<<520.0,321.0>-<520.0,311.0>-<524.0,299.5>>

	* E (U+0045) contains a short segment B<<153.0,419.0>-<147.0,412.0>-<147.0,398.0>>

	* E (U+0045) contains a short segment B<<147.0,398.0>-<147.0,385.0>-<153.0,378.0>>

	* E (U+0045) contains a short segment B<<145.5,259.0>-<139.0,252.0>-<139.0,238.0>>

	* E (U+0045) contains a short segment B<<139.0,238.0>-<139.0,223.0>-<146.0,215.5>>

	* G (U+0047) contains a short segment B<<452.0,210.0>-<455.0,211.0>-<455.0,225.5>>

	* K (U+004B) contains a short segment B<<228.0,244.0>-<224.0,254.0>-<218.5,256.5>>

	* K (U+004B) contains a short segment B<<218.5,256.5>-<213.0,259.0>-<197.0,259.0>>

	* K (U+004B) contains a short segment B<<171.5,256.5>-<165.0,254.0>-<160.0,245.0>>

	* K (U+004B) contains a short segment B<<160.0,245.0>-<156.0,238.0>-<155.0,227.5>>

	* K (U+004B) contains a short segment B<<308.0,299.0>-<299.0,295.0>-<299.0,284.0>>

	* K (U+004B) contains a short segment B<<299.0,284.0>-<299.0,276.0>-<304.5,272.0>>

	* M (U+004D) contains a short segment B<<397.0,363.0>-<406.0,353.0>-<421.0,353.0>>

	* M (U+004D) contains a short segment B<<421.0,353.0>-<436.0,353.0>-<445.0,363.0>>

	* M (U+004D) contains a short segment B<<676.0,316.0>-<669.0,324.0>-<656.0,326.5>>

	* M (U+004D) contains a short segment B<<577.5,328.0>-<565.0,327.0>-<557.5,323.5>>

	* M (U+004D) contains a short segment B<<557.5,323.5>-<550.0,320.0>-<541.0,312.0>>

	* M (U+004D) contains a short segment B<<301.0,312.0>-<292.0,320.0>-<284.5,323.5>>

	* M (U+004D) contains a short segment B<<284.5,323.5>-<277.0,327.0>-<264.5,328.0>>

	* M (U+004D) contains a short segment B<<186.5,326.5>-<174.0,324.0>-<166.0,316.0>>

	* N (U+004E) contains a short segment B<<423.5,415.5>-<431.0,407.0>-<440.5,405.0>>

	* W (U+0057) contains a short segment B<<176.0,384.0>-<185.0,375.0>-<193.0,373.0>>

	* W (U+0057) contains a short segment B<<632.0,373.0>-<640.0,375.0>-<649.0,384.0>>

	* W (U+0057) contains a short segment B<<432.5,337.0>-<424.0,347.0>-<410.0,347.0>>

	* W (U+0057) contains a short segment B<<410.0,347.0>-<395.0,347.0>-<386.0,337.0>>

	* X (U+0058) contains a short segment B<<172.5,341.5>-<175.0,352.0>-<175.0,361.0>>

	* X (U+0058) contains a short segment B<<175.0,361.0>-<175.0,370.0>-<172.5,380.0>>

	* X (U+0058) contains a short segment B<<539.0,380.0>-<537.0,370.0>-<537.0,361.0>>

	* X (U+0058) contains a short segment B<<537.0,361.0>-<537.0,352.0>-<539.5,341.5>>

	* Y (U+0059) contains a short segment B<<512.0,297.0>-<511.0,310.0>-<500.0,310.0>>

	* Z (U+005A) contains a short segment B<<419.0,414.5>-<422.0,420.0>-<421.0,426.0>>

	* Z (U+005A) contains a short segment B<<421.0,426.0>-<420.0,431.0>-<414.5,434.0>>

	* Z (U+005A) contains a short segment B<<269.0,225.0>-<264.0,219.0>-<264.0,211.0>>

	* Z (U+005A) contains a short segment B<<264.0,211.0>-<264.0,202.0>-<271.5,200.0>>

	* b (U+0062) contains a short segment B<<149.0,419.5>-<152.0,410.0>-<158.0,410.0>>

	* d (U+0064) contains a short segment B<<496.0,410.0>-<502.0,410.0>-<504.5,421.5>>

	* f (U+0066) contains a short segment B<<119.0,500.0>-<124.0,500.0>-<128.0,503.0>>

	* f (U+0066) contains a short segment B<<128.0,503.0>-<132.0,506.0>-<132.0,510.0>>

	* f (U+0066) contains a short segment B<<132.0,510.0>-<132.0,513.0>-<130.0,519.0>>

	* f (U+0066) contains a short segment B<<205.0,518.0>-<202.0,512.0>-<202.0,508.0>>

	* f (U+0066) contains a short segment B<<202.0,508.0>-<202.0,503.0>-<206.0,501.5>>

	* f (U+0066) contains a short segment B<<206.0,501.5>-<210.0,500.0>-<213.0,500.0>>

	* g (U+0067) contains a short segment B<<499.5,81.0>-<497.0,90.0>-<488.0,90.0>>

	* h (U+0068) contains a short segment B<<144.0,419.5>-<147.0,410.0>-<152.0,410.0>>

	* k (U+006B) contains a short segment B<<243.0,268.0>-<233.0,265.0>-<229.5,262.5>>

	* k (U+006B) contains a short segment B<<229.5,262.5>-<226.0,260.0>-<226.0,253.0>>

	* m (U+006D) contains a short segment B<<135.0,416.0>-<137.0,410.0>-<141.0,410.0>>

	* m (U+006D) contains a short segment B<<495.5,419.5>-<501.0,409.0>-<511.0,409.0>>

	* m (U+006D) contains a short segment B<<511.0,409.0>-<521.0,409.0>-<529.0,419.5>>

	* m (U+006D) contains a short segment B<<825.5,123.0>-<826.0,136.0>-<826.0,145.0>>

	* n (U+006E) contains a short segment B<<142.0,415.0>-<145.0,410.0>-<152.0,410.0>>

	* p (U+0070) contains a short segment B<<140.0,416.5>-<142.0,410.0>-<150.0,410.0>>

	* q (U+0071) contains a short segment B<<496.0,410.0>-<505.0,410.0>-<506.5,416.5>>

	* r (U+0072) contains a short segment B<<143.5,415.0>-<146.0,410.0>-<151.0,410.0>>

	* t (U+0074) contains a short segment B<<115.5,270.0>-<110.0,274.0>-<105.0,274.0>>

	* t (U+0074) contains a short segment B<<199.0,274.0>-<195.0,274.0>-<190.0,271.0>>

	* w (U+0077) contains a short segment B<<259.0,268.0>-<266.0,273.0>-<273.0,283.0>>

	* w (U+0077) contains a short segment B<<568.0,261.5>-<580.0,263.0>-<586.0,270.0>>

	* y (U+0079) contains a short segment B<<346.0,-10.0>-<346.0,-5.0>-<338.5,-2.5>>

	* z (U+007A) contains a short segment B<<328.0,285.0>-<331.0,289.0>-<331.0,296.0>>

	* z (U+007A) contains a short segment B<<216.0,163.5>-<212.0,160.0>-<212.0,153.0>>

	* z (U+007A) contains a short segment B<<212.0,153.0>-<212.0,147.0>-<217.5,145.5>>

	* uni02B0 (U+02B0) contains a short segment B<<144.0,419.5>-<147.0,410.0>-<152.0,410.0>>

	* uni02B7 (U+02B7) contains a short segment B<<259.0,268.0>-<266.0,273.0>-<273.0,283.0>>

	* uni02B7 (U+02B7) contains a short segment B<<568.0,261.5>-<580.0,263.0>-<586.0,270.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<328.0,285.0>-<331.0,289.0>-<331.0,296.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<216.0,163.5>-<212.0,160.0>-<212.0,153.0>>

	* uni1DBB (U+1DBB) contains a short segment B<<212.0,153.0>-<212.0,147.0>-<217.5,145.5>>

	* uni1EBE (U+1EBE) contains a short segment B<<153.0,419.0>-<147.0,412.0>-<147.0,398.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<147.0,398.0>-<147.0,385.0>-<153.0,378.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<145.5,259.0>-<139.0,252.0>-<139.0,238.0>>

	* uni1EBE (U+1EBE) contains a short segment B<<139.0,238.0>-<139.0,223.0>-<146.0,215.5>>

	* uni1EC0 (U+1EC0) contains a short segment B<<153.0,419.0>-<147.0,412.0>-<147.0,398.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<147.0,398.0>-<147.0,385.0>-<153.0,378.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<145.5,259.0>-<139.0,252.0>-<139.0,238.0>>

	* uni1EC0 (U+1EC0) contains a short segment B<<139.0,238.0>-<139.0,223.0>-<146.0,215.5>>

	* uni1EC4 (U+1EC4) contains a short segment B<<153.0,419.0>-<147.0,412.0>-<147.0,398.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<147.0,398.0>-<147.0,385.0>-<153.0,378.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<145.5,259.0>-<139.0,252.0>-<139.0,238.0>>

	* uni1EC4 (U+1EC4) contains a short segment B<<139.0,238.0>-<139.0,223.0>-<146.0,215.5>>

	* uni1EF8 (U+1EF8) contains a short segment B<<512.0,297.0>-<511.0,310.0>-<500.0,310.0>>

	* uni1EF9 (U+1EF9) contains a short segment B<<346.0,-10.0>-<346.0,-5.0>-<338.5,-2.5>>

	* trademark (U+2122) contains a short segment B<<1066.0,363.0>-<1075.0,353.0>-<1090.0,353.0>>

	* trademark (U+2122) contains a short segment B<<1090.0,353.0>-<1105.0,353.0>-<1114.0,363.0>>

	* trademark (U+2122) contains a short segment B<<1345.0,316.0>-<1338.0,324.0>-<1325.0,326.5>>

	* trademark (U+2122) contains a short segment B<<1246.5,328.0>-<1234.0,327.0>-<1226.5,323.5>>

	* trademark (U+2122) contains a short segment B<<1226.5,323.5>-<1219.0,320.0>-<1210.0,312.0>>

	* trademark (U+2122) contains a short segment B<<970.0,312.0>-<961.0,320.0>-<953.5,323.5>>

	* trademark (U+2122) contains a short segment B<<953.5,323.5>-<946.0,327.0>-<933.5,328.0>>

	* trademark (U+2122) contains a short segment B<<855.5,326.5>-<843.0,324.0>-<835.0,316.0>>

	* estimated (U+212E) contains a short segment B<<200.0,346.0>-<193.0,346.0>-<189.0,343.5>>

	* estimated (U+212E) contains a short segment B<<189.0,343.5>-<185.0,341.0>-<185.0,327.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* B (U+0042): L<<62.0,701.0>--<414.0,699.0>>

	* F (U+0046): L<<62.0,701.0>--<580.0,699.0>>

	* P (U+0050): L<<65.0,701.0>--<413.0,699.0>>

	* P (U+0050): L<<68.0,350.0>--<65.0,701.0>>

	* R (U+0052): L<<65.0,701.0>--<413.0,699.0>>

	* R (U+0052): L<<68.0,350.0>--<65.0,701.0>>

	* S (U+0053): L<<53.0,7.0>--<52.0,234.0>>

	* U (U+0055): L<<43.0,310.0>--<42.0,700.0>>

	* U (U+0055): L<<599.0,700.0>--<596.0,302.0>>

	* i (U+0069): L<<61.0,261.0>--<60.0,500.0>>

	* l (U+006C): L<<13.0,501.0>--<12.0,740.0>>

	* l (U+006C): L<<155.0,99.0>--<156.0,404.0>> [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 21 | 63 | 74 | 849 | 36 | 598 | 0 |
| 1% | 4% | 5% | 52% | 2% | 36% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
