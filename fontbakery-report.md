## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[19] Ojuju-Bold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsSelection value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-fsselection">opentype/fsselection</a></summary>
    <div>


> 
> The OS/2.fsSelection field is a bit field used to specify the stylistic
> qualities of the font - in particular, it specifies to some operating
> systems whether the font is italic (bit 0), bold (bit 5) or regular
> (bit 6).
> 
> This check verifies that the fsSelection field is set correctly for the
> font style. For a family of static fonts created in GlyphsApp, this is
> set by using the style linking checkboxes in the exports settings.
> 
> Additionally, the bold and italic bits in OS/2.fsSelection must match the
> bold and italic bits in head.macStyle per the OpenType spec.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829
> See also: https://github.com/fonttools/fontbakery/pull/2382





* 🔥 **FAIL** <p>fsSelection Bold flag False does not match font style Bold</p>
 [code: bad-BOLD]



* 🔥 **FAIL** <p>fsSelection Regular flag True does not match font style Bold</p>
 [code: bad-REGULAR]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking head.macStyle value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-mac-style">opentype/mac_style</a></summary>
    <div>


> 
> The values of the flags on the macStyle entry on the 'head' OpenType table
> that describe whether a font is bold and/or italic must be coherent with the
> actual style of the font as inferred by its filename.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* 🔥 **FAIL** <p>head macStyle BOLD bit should be set.</p>
 [code: bad-BOLD]





</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ᵉ, ᵋ, ⁱ, ᵒ, ᶤ, ᵓ, ᶶ, ᵃ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: t͟h, T͟H</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɤ̀, Ɤ̋, ɤ́, ɤ̀, ɤ̏, ɤ̂, ɤ̋, ɤ̄, Ɤ̄, Ɤ̏, ɤ, Ɤ́, Ɤ, Ɤ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɤ̀, ɤ́, Ɤ, Ɤ̂, ɤ, ɤ̂, Ɤ́, ɤ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꟈ, Ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-names">googlefonts/font_names</a></summary>
    <div>


> 
> Google Fonts has several rules which need to be adhered to when
> setting a font's name table. Please read:
> https://googlefonts.github.io/gf-guide/statics.html#supported-styles
> https://googlefonts.github.io/gf-guide/statics.html#style-linking
> https://googlefonts.github.io/gf-guide/statics.html#unsupported-styles
> https://googlefonts.github.io/gf-guide/statics.html#single-weight-families
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3800





* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Ojuju Bold</strong></td>
<td align="left"><strong>Ojuju</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left"><strong>Regular</strong></td>
<td align="left"><strong>Bold</strong></td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Ojuju Bold</td>
<td align="left">Ojuju Bold</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">Ojuju-Bold</td>
<td align="left">Ojuju-Bold</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Ojuju</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Bold</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0181	Contours detected: 4	Expected: 3

- Glyph name: uni0187	Contours detected: 2	Expected: 1

- Glyph name: uni0188	Contours detected: 2	Expected: 1

- 76 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 436 among a set of 7 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 437:
less, greater, greaterequal, lessequal</p>
<p>Width = 444:
multiply</p>
<p>Width = 475:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>


> 
> Some rasterizers encounter difficulties when rendering glyphs with
> overlapping path segments.
> 
> A path segment is a section of a path defined by two on-curve points.
> When two segments share the same coordinates, they are considered
> overlapping.
> 




> Original proposal: https://github.com/google/fonts/issues/7594#issuecomment-2401909084





* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* fl.salt: L&lt;&lt;449.0,729.0&gt;--&lt;449.0,729.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* fl.salt: L&lt;&lt;449.0,729.0&gt;--&lt;449.0,729.0&gt;&gt; -&gt; L&lt;&lt;449.0,729.0&gt;--&lt;449.0,729.0&gt;&gt;

* uni20A9 (U+20A9): L&lt;&lt;451.0,456.0&gt;--&lt;465.0,456.0&gt;&gt; -&gt; L&lt;&lt;465.0,456.0&gt;--&lt;479.0,456.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;38.0,427.0&gt;--&lt;30.0,542.0&gt;&gt; -&gt; L&lt;&lt;30.0,542.0&gt;--&lt;27.0,710.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;91.0,710.0&gt;--&lt;88.0,542.0&gt;&gt; -&gt; L&lt;&lt;88.0,542.0&gt;--&lt;80.0,427.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* filledbox (U+25A0): L&lt;&lt;32.0,65.0&gt;--&lt;31.0,261.0&gt;&gt;

* nine.dnom: L&lt;&lt;40.0,8.0&gt;--&lt;41.0,130.0&gt;&gt;

* nine.numr: L&lt;&lt;40.0,287.0&gt;--&lt;41.0,409.0&gt;&gt;

* six.dnom: L&lt;&lt;305.0,412.0&gt;--&lt;304.0,290.0&gt;&gt;

* six.numr: L&lt;&lt;305.0,696.0&gt;--&lt;304.0,574.0&gt;&gt;

* uni2076 (U+2076): L&lt;&lt;305.0,791.0&gt;--&lt;304.0,669.0&gt;&gt;

* uni2079 (U+2079): L&lt;&lt;40.0,382.0&gt;--&lt;41.0,504.0&gt;&gt;

* uni2086 (U+2086): L&lt;&lt;305.0,282.0&gt;--&lt;304.0,160.0&gt;&gt;

* uni2089 (U+2089): L&lt;&lt;40.0,-122.0&gt;--&lt;41.0,0.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,619.0&gt;&gt;

* 3 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[15] Ojuju-Black.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ⁱ, ᵋ, ᵉ, ᶶ, ᶤ, ᵓ, ᵒ, ᵃ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: T͟H, t͟h</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɤ̀, Ɤ̂, Ɤ̏, ɤ̏, ɤ, Ɤ̄, ɤ̂, Ɤ̋, Ɤ́, Ɤ, ɤ̀, ɤ́, ɤ̄, ɤ̋</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ́, ɤ̀, ɤ̂, Ɤ́, Ɤ̀, Ɤ̂, Ɤ, ɤ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ꟈ, ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0181	Contours detected: 4	Expected: 3

- Glyph name: uni0187	Contours detected: 2	Expected: 1

- Glyph name: uni0188	Contours detected: 2	Expected: 1

- 76 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 434 among a set of 7 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 435:
less, greater, greaterequal, lessequal</p>
<p>Width = 442:
multiply</p>
<p>Width = 551:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uniA78C (U+A78C): L&lt;&lt;103.0,716.0&gt;--&lt;99.0,527.0&gt;&gt; -&gt; L&lt;&lt;99.0,527.0&gt;--&lt;90.0,392.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;33.0,392.0&gt;--&lt;24.0,527.0&gt;&gt; -&gt; L&lt;&lt;24.0,527.0&gt;--&lt;20.0,716.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* filledbox (U+25A0): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,619.0&gt;&gt;

* filledbox (U+25A0): L&lt;&lt;582.0,619.0&gt;--&lt;584.0,65.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,619.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;515.0,134.0&gt;--&lt;514.0,550.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;582.0,619.0&gt;--&lt;584.0,65.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;99.0,550.0&gt;--&lt;100.0,134.0&gt;&gt;

* uni25AA (U+25AA): L&lt;&lt;31.0,65.0&gt;--&lt;30.0,366.0&gt;&gt;

* uni25AA (U+25AA): L&lt;&lt;330.0,366.0&gt;--&lt;331.0,65.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] Ojuju-ExtraBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ᶶ, ᵉ, ᵃ, ᶤ, ⁱ, ᵒ, ᵋ, ᵓ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: T͟H, t͟h</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ̀, ɤ, ɤ̂, Ɤ̄, Ɤ́, Ɤ̏, Ɤ̂, ɤ̏, ɤ́, Ɤ̀, Ɤ̋, Ɤ, ɤ̄, ɤ̋</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ, Ɤ̂, ɤ̀, Ɤ̀, Ɤ, Ɤ́, ɤ́, ɤ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ꟈ, ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0181	Contours detected: 4	Expected: 3

- Glyph name: uni0187	Contours detected: 2	Expected: 1

- Glyph name: uni0188	Contours detected: 2	Expected: 1

- 76 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 435 among a set of 7 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 436:
less, greater, greaterequal, lessequal</p>
<p>Width = 443:
multiply</p>
<p>Width = 515:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>


> 
> Some rasterizers encounter difficulties when rendering glyphs with
> overlapping path segments.
> 
> A path segment is a section of a path defined by two on-curve points.
> When two segments share the same coordinates, they are considered
> overlapping.
> 




> Original proposal: https://github.com/google/fonts/issues/7594#issuecomment-2401909084





* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* fl.salt: L&lt;&lt;474.0,735.0&gt;--&lt;474.0,735.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* fl.salt: L&lt;&lt;474.0,735.0&gt;--&lt;474.0,735.0&gt;&gt; -&gt; L&lt;&lt;474.0,735.0&gt;--&lt;474.0,735.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;35.0,409.0&gt;--&lt;27.0,534.0&gt;&gt; -&gt; L&lt;&lt;27.0,534.0&gt;--&lt;23.0,713.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;97.0,713.0&gt;--&lt;94.0,534.0&gt;&gt; -&gt; L&lt;&lt;94.0,534.0&gt;--&lt;86.0,409.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* E (U+0045): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Eacute (U+00C9): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Ecaron (U+011A): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Ecircumflex (U+00CA): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Edieresis (U+00CB): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Edotaccent (U+0116): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Egrave (U+00C8): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Emacron (U+0112): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* Eogonek (U+0118): L&lt;&lt;543.0,700.0&gt;--&lt;541.0,464.0&gt;&gt;

* nine.blackcircled: L&lt;&lt;277.0,292.0&gt;--&lt;276.0,146.0&gt;&gt;

* 23 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] Ojuju-ExtraLight.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ⁱ, ᶤ, ᵒ, ᵓ, ᶶ, ᵋ, ᵉ, ᵃ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: t͟h, T͟H</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ, ɤ̄, Ɤ̏, Ɤ̀, ɤ́, Ɤ̄, ɤ̏, ɤ̂, ɤ̋, Ɤ̋, Ɤ, ɤ̀, Ɤ̂, Ɤ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ̀, Ɤ̂, Ɤ, Ɤ́, ɤ̂, ɤ́, Ɤ̀, ɤ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꟈ, Ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: hbar	Contours detected: 2	Expected: 1

- Glyph name: Tbar	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- 92 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 440 among a set of 9 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 439:
logicalnot, plus</p>
<p>Width = 449:
multiply</p>
<p>Width = 337:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uniA78C (U+A78C): L&lt;&lt;46.0,491.0&gt;--&lt;40.0,570.0&gt;&gt; -&gt; L&lt;&lt;40.0,570.0&gt;--&lt;40.0,700.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;69.0,700.0&gt;--&lt;69.0,570.0&gt;&gt; -&gt; L&lt;&lt;69.0,570.0&gt;--&lt;63.0,491.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>


> 
> This check heuristically detects outline segments which form a particularly
> small angle, indicative of an outline error. This may cause false positives
> in cases such as extreme ink traps, so should be regarded as advisory and
> backed up by manual inspection.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3064





* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni20BE (U+20BE): L&lt;&lt;82.0,37.0&gt;--&lt;303.0,37.0&gt;&gt;/B&lt;&lt;303.0,37.0&gt;-&lt;173.0,60.0&gt;-&lt;105.5,157.0&gt;&gt; = 10.033120554331154
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* f (U+0066): L&lt;&lt;104.0,485.0&gt;--&lt;108.0,0.0&gt;&gt;

* f (U+0066): L&lt;&lt;76.0,0.0&gt;--&lt;80.0,485.0&gt;&gt;

* f_f: L&lt;&lt;104.0,485.0&gt;--&lt;108.0,0.0&gt;&gt;

* f_f: L&lt;&lt;366.0,0.0&gt;--&lt;370.0,485.0&gt;&gt;

* f_f: L&lt;&lt;394.0,485.0&gt;--&lt;398.0,0.0&gt;&gt;

* f_f: L&lt;&lt;76.0,0.0&gt;--&lt;80.0,485.0&gt;&gt;

* f_t: L&lt;&lt;104.0,485.0&gt;--&lt;108.0,0.0&gt;&gt;

* f_t: L&lt;&lt;76.0,0.0&gt;--&lt;80.0,485.0&gt;&gt;

* fi (U+FB01): L&lt;&lt;104.0,485.0&gt;--&lt;108.0,0.0&gt;&gt;

* fi (U+FB01): L&lt;&lt;76.0,0.0&gt;--&lt;80.0,485.0&gt;&gt;

* 14 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] Ojuju-Light.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ᵒ, ᵃ, ᵋ, ⁱ, ᵓ, ᶶ, ᵉ, ᶤ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: T͟H, t͟h</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ̄, ɤ̀, Ɤ̀, Ɤ̂, ɤ̂, ɤ̏, Ɤ, Ɤ̄, Ɤ̋, ɤ, Ɤ̏, ɤ́, ɤ̋, Ɤ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ̀, Ɤ̀, Ɤ́, Ɤ̂, ɤ̂, Ɤ, ɤ́, ɤ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꟈ, Ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0181	Contours detected: 4	Expected: 3

- Glyph name: uni0187	Contours detected: 2	Expected: 1

- Glyph name: uni0188	Contours detected: 2	Expected: 1

- 74 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 440 among a set of 9 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 439:
logicalnot, plus</p>
<p>Width = 449:
multiply</p>
<p>Width = 350:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* triagdn (U+25BC): L&lt;&lt;30.0,619.0&gt;--&lt;62.0,619.0&gt;&gt; -&gt; L&lt;&lt;62.0,619.0&gt;--&lt;566.0,586.0&gt;&gt;

* uni25B6 (U+25B6): L&lt;&lt;63.0,82.0&gt;--&lt;30.0,586.0&gt;&gt; -&gt; L&lt;&lt;30.0,586.0&gt;--&lt;30.0,618.0&gt;&gt;

* uni25B8 (U+25B8): L&lt;&lt;48.0,75.0&gt;--&lt;30.0,348.0&gt;&gt; -&gt; L&lt;&lt;30.0,348.0&gt;--&lt;30.0,366.0&gt;&gt;

* uni25BE (U+25BE): L&lt;&lt;30.0,366.0&gt;--&lt;48.0,366.0&gt;&gt; -&gt; L&lt;&lt;48.0,366.0&gt;--&lt;321.0,348.0&gt;&gt;

* uni25C0 (U+25C0): L&lt;&lt;551.0,602.0&gt;--&lt;584.0,98.0&gt;&gt; -&gt; L&lt;&lt;584.0,98.0&gt;--&lt;584.0,66.0&gt;&gt;

* uni25C2 (U+25C2): L&lt;&lt;313.0,357.0&gt;--&lt;331.0,84.0&gt;&gt; -&gt; L&lt;&lt;331.0,84.0&gt;--&lt;331.0,66.0&gt;&gt;

* uni25C6 (U+25C6): L&lt;&lt;435.0,217.0&gt;--&lt;251.0,8.0&gt;&gt; -&gt; L&lt;&lt;251.0,8.0&gt;--&lt;239.0,-4.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;45.0,485.0&gt;--&lt;39.0,567.0&gt;&gt; -&gt; L&lt;&lt;39.0,567.0&gt;--&lt;39.0,701.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;71.0,701.0&gt;--&lt;71.0,567.0&gt;&gt; -&gt; L&lt;&lt;71.0,567.0&gt;--&lt;65.0,485.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>


> 
> This check heuristically detects outline segments which form a particularly
> small angle, indicative of an outline error. This may cause false positives
> in cases such as extreme ink traps, so should be regarded as advisory and
> backed up by manual inspection.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3064





* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni20BE (U+20BE): L&lt;&lt;80.0,52.0&gt;--&lt;290.0,52.0&gt;&gt;/B&lt;&lt;290.0,52.0&gt;-&lt;166.0,74.0&gt;-&lt;101.5,168.0&gt;&gt; = 10.060689795322984
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* f (U+0066): L&lt;&lt;108.0,471.0&gt;--&lt;112.0,0.0&gt;&gt;

* f_f: L&lt;&lt;108.0,471.0&gt;--&lt;112.0,0.0&gt;&gt;

* f_f: L&lt;&lt;401.0,471.0&gt;--&lt;405.0,0.0&gt;&gt;

* f_t: L&lt;&lt;108.0,471.0&gt;--&lt;112.0,0.0&gt;&gt;

* fi (U+FB01): L&lt;&lt;108.0,471.0&gt;--&lt;112.0,0.0&gt;&gt;

* filledbox (U+25A0): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,586.0&gt;&gt;

* fl (U+FB02): L&lt;&lt;108.0,471.0&gt;--&lt;112.0,0.0&gt;&gt;

* fl.salt: L&lt;&lt;108.0,471.0&gt;--&lt;112.0,0.0&gt;&gt;

* uni1E1F (U+1E1F): L&lt;&lt;108.0,471.0&gt;--&lt;112.0,0.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,619.0&gt;&gt;

* 4 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] Ojuju-Medium.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ᵃ, ᵉ, ᵋ, ᶤ, ᵒ, ᵓ, ⁱ, ᶶ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: t͟h, T͟H</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɤ̏, Ɤ̂, Ɤ̄, ɤ̂, Ɤ̋, Ɤ, ɤ̏, ɤ̄, ɤ, ɤ̋, ɤ̀, Ɤ̀, Ɤ́, ɤ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɤ̀, Ɤ́, ɤ̀, ɤ́, Ɤ̂, ɤ̂, ɤ, Ɤ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꟈ, Ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0181	Contours detected: 4	Expected: 3

- Glyph name: uni0187	Contours detected: 2	Expected: 1

- Glyph name: uni0188	Contours detected: 2	Expected: 1

- 74 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 438 among a set of 7 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 439:
less, greater, greaterequal, lessequal</p>
<p>Width = 447:
multiply</p>
<p>Width = 400:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uniA78C (U+A78C): L&lt;&lt;42.0,462.0&gt;--&lt;35.0,557.0&gt;&gt; -&gt; L&lt;&lt;35.0,557.0&gt;--&lt;34.0,705.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;79.0,705.0&gt;--&lt;78.0,557.0&gt;&gt; -&gt; L&lt;&lt;78.0,557.0&gt;--&lt;71.0,462.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>


> 
> This check heuristically detects outline segments which form a particularly
> small angle, indicative of an outline error. This may cause false positives
> in cases such as extreme ink traps, so should be regarded as advisory and
> backed up by manual inspection.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3064





* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni20BE (U+20BE): L&lt;&lt;72.0,110.0&gt;--&lt;240.0,110.0&gt;&gt;/B&lt;&lt;240.0,110.0&gt;-&lt;138.0,132.0&gt;-&lt;85.5,212.5&gt;&gt; = 12.171458208587458
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* filledbox (U+25A0): L&lt;&lt;32.0,65.0&gt;--&lt;31.0,456.0&gt;&gt;

* six (U+0036): L&lt;&lt;475.0,683.0&gt;--&lt;474.0,568.0&gt;&gt;

* six.lf: L&lt;&lt;475.0,683.0&gt;--&lt;474.0,568.0&gt;&gt;

* six.osf: L&lt;&lt;475.0,683.0&gt;--&lt;474.0,568.0&gt;&gt;

* six.tf: L&lt;&lt;491.0,683.0&gt;--&lt;490.0,568.0&gt;&gt;

* six.tosf: L&lt;&lt;476.0,683.0&gt;--&lt;475.0,568.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,619.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;541.0,108.0&gt;--&lt;540.0,576.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;582.0,619.0&gt;--&lt;584.0,65.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;73.0,576.0&gt;--&lt;74.0,108.0&gt;&gt;

* 3 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[16] Ojuju-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ᵉ, ᶶ, ᵒ, ᵓ, ᵃ, ᶤ, ᵋ, ⁱ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: T͟H, t͟h</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ̄, ɤ́, Ɤ̋, Ɤ̄, ɤ̂, Ɤ̏, Ɤ̀, ɤ̀, Ɤ̂, ɤ̏, ɤ̋, ɤ, Ɤ, Ɤ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ̂, Ɤ́, ɤ́, ɤ̀, Ɤ̂, Ɤ, ɤ, Ɤ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꟈ, Ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0181	Contours detected: 4	Expected: 3

- Glyph name: uni0187	Contours detected: 2	Expected: 1

- Glyph name: uni0188	Contours detected: 2	Expected: 1

- 74 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 439 among a set of 9 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 438:
logicalnot, plus</p>
<p>Width = 448:
multiply</p>
<p>Width = 371:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* uniA78C (U+A78C): L&lt;&lt;44.0,475.0&gt;--&lt;37.0,563.0&gt;&gt; -&gt; L&lt;&lt;37.0,563.0&gt;--&lt;37.0,703.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;74.0,703.0&gt;--&lt;74.0,563.0&gt;&gt; -&gt; L&lt;&lt;74.0,563.0&gt;--&lt;67.0,475.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>


> 
> This check heuristically detects outline segments which form a particularly
> small angle, indicative of an outline error. This may cause false positives
> in cases such as extreme ink traps, so should be regarded as advisory and
> backed up by manual inspection.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3064





* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni20BE (U+20BE): L&lt;&lt;77.0,77.0&gt;--&lt;269.0,77.0&gt;&gt;/B&lt;&lt;269.0,77.0&gt;-&lt;154.0,99.0&gt;-&lt;94.5,187.0&gt;&gt; = 10.830079543406987
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* filledbox (U+25A0): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,530.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;32.0,65.0&gt;--&lt;30.0,619.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;546.0,103.0&gt;--&lt;545.0,581.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;582.0,619.0&gt;--&lt;584.0,65.0&gt;&gt;

* uni25A1 (U+25A1): L&lt;&lt;68.0,581.0&gt;--&lt;69.0,103.0&gt;&gt;

* uni25AA (U+25AA): L&lt;&lt;31.0,65.0&gt;--&lt;30.0,318.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[15] Ojuju-SemiBold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>


> 
> Running old versions of FontBakery can lead to a poor report which may
> include false WARNs and FAILs due do bugs, as well as outdated
> quality assurance criteria.
> 
> Older versions will also not report problems that are detected by new checks
> added to the tool in more recent updates.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/2093





* 🔥 **FAIL** <p>Current FontBakery version is 0.13.2, while a newer 1.0.0 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>


> 
> This check uses a heuristic to determine which GF glyphsets a font supports.
> Then it checks the font for correct shaping behaviour for all languages in
> those glyphsets.
> 




> Original proposal: https://github.com/googlefonts/fontbakery/issues/4147





* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left">ijs_Latn (Ijo, Southeast)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">mgo_Latn (Metaʼ) and gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F when shaping the text 'Ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F when shaping the text 'Ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F when shaping the text 'Ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D when shaping the text 'Ɥ̃́'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">bfd_Latn (Bafut) and nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">mhi_Latn (Ma’di) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268 when shaping the text 'ɨ̃'</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">igb_Latn (Ebira)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB when shaping the text 'ị̃'</td>
<td align="left">kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left">lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɨ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ᵋ, ᵉ, ᶤ, ᵓ, ᵒ, ᵃ, ⁱ, ᶶ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">bum_Latn (Bulu) and eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: t͟h, T͟H</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ḭ̄'</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left">bbj_Latn (Ghomala) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268 when shaping the text 'ɨ̈'</td>
<td align="left">nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ̏, ɤ̀, ɤ́, Ɤ̄, Ɤ̋, ɤ̂, Ɤ̏, Ɤ̀, ɤ, ɤ̄, Ɤ́, ɤ̋, Ɤ̂, Ɤ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to oe when shaping the text 'œ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to oe when shaping the text 'œ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oe when shaping the text 'œ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB when shaping the text 'ị̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe when shaping the text 'œ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268 when shaping the text 'ɨ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe when shaping the text 'œ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɨ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɨ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɨ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ḭ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ḭ́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F when shaping the text 'Ə̂'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ɤ́, Ɤ́, ɤ, Ɤ̂, ɤ̀, Ɤ, Ɤ̀, ɤ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꟈ, Ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe when shaping the text 'œ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268 when shaping the text 'ɨ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe when shaping the text 'œ̂'</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F when shaping the text 'Ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ŀ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ŀ</td>
<td align="left">ca_Latn (Catalan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to iogonek when shaping the text 'į̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0307 to iogonek when shaping the text 'į̇̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB when shaping the text 'ị̀'</td>
<td align="left">ig_Latn (Igbo) and ig_Latn (Igbo)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB when shaping the text 'ị́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB when shaping the text 'ị̄'</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB when shaping the text 'ị̌'</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek when shaping the text 'į́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268 when shaping the text 'ɨ̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃́'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F when shaping the text 'Ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268 when shaping the text 'ɨ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268 when shaping the text 'ɨ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F when shaping the text 'Ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F when shaping the text 'Ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F when shaping the text 'Ə̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>


> 
> The dotted circle character (U+25CC) is inserted by shaping engines before
> mark glyphs which do not have an associated base, especially in the context
> of broken syllabic clusters.
> 
> For fonts containing combining marks, it is recommended that the dotted circle
> character be included so that these isolated marks can be displayed properly;
> for fonts supporting complex scripts, this should be considered mandatory.
> 
> Additionally, when a dotted circle glyph is present, it should be able to
> display all marks correctly, meaning that it should contain anchors for all
> attaching marks.
> 
> A fontmake filter can be used to automatically add a dotted_circle to a font:
> 
> fontmake --filter 'DottedCircleFilter(pre=True)' --filter '...'
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3600





* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- uni031B

- uni0328

- uni0334

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>


> 
> Visually QAing thousands of glyphs by hand is tiring. Most glyphs can only
> be constructured in a handful of ways. This means a glyph's contour count
> will only differ slightly amongst different fonts, e.g a 'g' could either
> be 2 or 3 contours, depending on whether its double story or single story.
> 
> However, a quotedbl should have 2 contours, unless the font belongs
> to a display family.
> 
> This check currently does not cover variable fonts because there's plenty
> of alternative ways of constructing glyphs with multiple outlines for each
> feature in a VarFont. The expected contour count data for this check is
> currently optimized for the typical construction of glyphs in static fonts.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: dollar	Contours detected: 2	Expected: 1, 3 or 5

- Glyph name: Eth	Contours detected: 3	Expected: 2

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Dcroat	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni0181	Contours detected: 4	Expected: 3

- Glyph name: uni0187	Contours detected: 2	Expected: 1

- Glyph name: uni0188	Contours detected: 2	Expected: 1

- 76 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#ligature-carets">ligature_carets</a></summary>
    <div>


> 
> All ligatures in a font must have corresponding caret (text cursor) positions
> defined in the GDEF table, otherwhise, users may experience issues with
> caret rendering.
> 
> If using GlyphsApp or UFOs, ligature carets can be defined as anchors with
> names starting with `caret_`. These can be compiled with fontmake as of
> version v2.4.0.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/1225





* ⚠️ **WARN** <p>This font lacks caret positioning values for these ligature glyphs:
- fi</p>
<pre><code>- fl
</code></pre>
 [code: incomplete-caret-pos-data]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>


> 
> It is a common practice to have math signs sharing the same width
> (preferably the same width as tabular figures accross the entire font family).
> 
> This probably comes from the will to avoid additional tabular math signs
> knowing that their design can easily share the same width.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3832





* ⚠️ **WARN** <p>The most common width is 437 among a set of 7 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 438:
less, greater, greaterequal, lessequal</p>
<p>Width = 446:
multiply</p>
<p>Width = 436:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>


> 
> The 'Soft Hyphen' character (codepoint 0x00AD) is used to mark
> a hyphenation possibility within a word in the absence of or
> overriding dictionary hyphenation.
> 
> It is sometimes designed empty with no width (such as a control character),
> sometimes the same as the traditional hyphen, sometimes double encoded with
> the hyphen.
> 
> That being said, it is recommended to not include it in the font at all,
> because discretionary hyphenation should be handled at the level of the
> shaping engine, not the font. Also, even if present, the software would
> not display that character.
> 
> More discussion at:
> https://typedrawers.com/discussion/2046/special-dash-things-softhyphen-horizontalbar
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4046
> See also: https://github.com/fonttools/fontbakery/issues/3486





* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>


> 
> Glyphs are either accessible directly through Unicode codepoints or through
> substitution rules.
> 
> In Color Fonts, glyphs are also referenced by the COLR table. And mathematical
> fonts also reference glyphs via the MATH table.
> 
> Any glyphs not accessible by these means are redundant and serve only
> to increase the font's file size.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3160





* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.blackcircled

- eight.lf

- eight.osf

- eight.tosf

- five.blackcircled

- five.lf

- five.osf

- five.tosf

- four.blackcircled

- 52 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>


> 
> The purpose of this check is to ensure images (either raster or vector files)
> are not excessively large in filesize and resolution.
> 
> These constraints are loosely based on infrastructure limitations under
> default configurations.
> 
> It also ensures that the article page has a minimum length and includes
> at least one visual asset.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4594





* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
    <div>


> 
> This check ensures that all encoded glyphs in the font are covered by a
> subset declared in the METADATA.pb. Google Fonts splits the font into
> a set of subset fonts based on the contents of the `subsets` field and
> the subset definitions in the `glyphsets` repository.
> 
> Any encoded glyphs which are not by any of these subset definitions
> will not be served in the subsetted fonts, and so will be unreachable to
> the end user.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4097
> See also: https://github.com/fonttools/fontbakery/pull/4273





* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, math, tifinagh, duployan, coptic, tai-le, hebrew, syriac, old-permic, todhri, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar
125 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>


> 
> An accent placed on characters with a "soft dot", like i or j, causes
> the dot to disappear.
> An explicit dot above can be added where required.
> See "Diacritics on i and j" in Section 7.1, "Latin" in The Unicode Standard.
> 
> Characters with the Soft_Dotted property are listed in
> https://www.unicode.org/Public/UCD/latest/ucd/PropList.txt
> 
> See also:
> https://googlefonts.github.io/gf-guide/diacritics.html#soft-dotted-glyphs
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/4059





* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: ḭ̀ ḭ́ ḭ̂ ḭ̃ ḭ̄ ḭ̆ ḭ̇ ḭ̈ ḭ̉ ḭ̊ ḭ̋ ḭ̌ ḭ̍ ḭ̏ ḭ̐ ḭ̑ ḭ̒ ḭ̓ ḭ᷄ ḭ᷅</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-colinear-vectors">outline_colinear_vectors</a></summary>
    <div>


> 
> This check looks for consecutive line segments which have the same angle. This
> normally happens if an outline point has been added by accident.
> 
> This check is not run for variable fonts, as they may legitimately have
> colinear vectors.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* fl.salt: L&lt;&lt;424.0,723.0&gt;--&lt;424.0,723.0&gt;&gt; -&gt; L&lt;&lt;424.0,723.0&gt;--&lt;425.0,723.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;40.0,445.0&gt;--&lt;33.0,550.0&gt;&gt; -&gt; L&lt;&lt;33.0,550.0&gt;--&lt;31.0,707.0&gt;&gt;

* uniA78C (U+A78C): L&lt;&lt;85.0,707.0&gt;--&lt;83.0,550.0&gt;&gt; -&gt; L&lt;&lt;83.0,550.0&gt;--&lt;75.0,445.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>


> 
> This check detects line segments which are nearly, but not quite, exactly
> horizontal or vertical. Sometimes such lines are created by design, but often
> they are indicative of a design error.
> 
> This check is disabled for italic styles, which often contain nearly-upright
> lines.
> 




> Original proposal: https://github.com/fonttools/fontbakery/pull/3088





* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* AE (U+00C6): L&lt;&lt;919.0,700.0&gt;--&lt;918.0,557.0&gt;&gt;

* AEacute (U+01FC): L&lt;&lt;919.0,700.0&gt;--&lt;918.0,557.0&gt;&gt;

* E (U+0045): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* Eacute (U+00C9): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* Ecaron (U+011A): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* Ecircumflex (U+00CA): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* Edieresis (U+00CB): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* Edotaccent (U+0116): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* Egrave (U+00C8): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* Emacron (U+0112): L&lt;&lt;501.0,700.0&gt;--&lt;500.0,552.0&gt;&gt;

* 29 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: found-semi-vertical]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>


> 
> The OpenType 'meta' table originated at Apple. Microsoft added it to OT with
> just two DataMap records:
> 
> - dlng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font is designed for.
> 
> - slng: comma-separated ScriptLangTags that indicate which scripts,
> or languages and scripts, with possible variants, the font supports.
> 
> 
> The slng structure is intended to describe which languages and scripts the
> font overall supports. For example, a Traditional Chinese font that also
> contains Latin characters, can indicate Hant,Latn, showing that it supports
> Hant, the Traditional Chinese variant of the Hani script, and it also
> supports the Latn script.
> 
> The dlng structure is far more interesting. A font may contain various glyphs,
> but only a particular subset of the glyphs may be truly "leading" in the design,
> while other glyphs may have been included for technical reasons. Such a
> Traditional Chinese font could only list Hant there, showing that it’s designed
> for Traditional Chinese, but the font would omit Latn, because the developers
> don’t think the font is really recommended for purely Latin-script use.
> 
> The tags used in the structures can comprise just script, or also language
> and script. For example, if a font has Bulgarian Cyrillic alternates in the
> locl feature for the cyrl BGR OT languagesystem, it could also indicate in
> dlng explicitly that it supports bul-Cyrl. (Note that the scripts and languages
> in meta use the ISO language and script codes, not the OpenType ones).
> 
> This check ensures that the font has the meta table containing the
> slng and dlng structures.
> 
> All families in the Google Fonts collection should contain the 'meta' table.
> Windows 10 already uses it when deciding on which fonts to fall back to.
> The Google Fonts API and also other environments could use the data for
> smarter filtering. Most importantly, those entries should be added
> to the Noto fonts.
> 
> In the font making process, some environments store this data in external
> files already. But the meta table provides a convenient way to store this
> inside the font file, so some tools may add the data, and unrelated tools
> may read this data. This makes the solution much more portable and universal.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3349





* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>


> 
> Microsoft keeps a list of font vendors and their respective contact info. This
> list is updated regularly and is indexed by a 4-char "Vendor ID" which is
> stored in the achVendID field of the OS/2 table.
> 
> Registering your ID is not mandatory, but it is a good practice since some
> applications may display the type designer / type foundry contact info on some
> dialog and also because that info will be visible on Microsoft's website:
> 
> https://docs.microsoft.com/en-us/typography/vendors/
> 
> This check verifies whether or not a given font's vendor ID is registered in
> that list or if it has some of the default values used by the most common
> font editors.
> 
> Each new FontBakery release includes a cached copy of that list of vendor IDs.
> If you registered recently, you're safe to ignore warnings emitted by this
> check, since your ID will soon be included in one of our upcoming releases.
> 




> Original proposal: https://github.com/fonttools/fontbakery/issues/3943
> See also: https://github.com/fonttools/fontbakery/issues/4829





* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 27 | 102 | 819 | 49 | 772 | 0 | 
| 0% | 0% | 2% | 6% | 46% | 3% | 44% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
