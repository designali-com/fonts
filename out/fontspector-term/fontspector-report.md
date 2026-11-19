## FontSpector report

fontspector version: 1.9.1






## Check results




<details><summary>[16] fonts/terminal/DesignaliMonoTerm-Medium.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* scedilla (U+015F)
* Tbar (U+0166)
* uni0163 (U+0163)
* uogonek (U+0173)
* aogonek (U+0105)
* aogonek.cv01
* Ccedilla (U+00C7)
* nine (U+0039)
* Iogonek (U+012E)
* six (U+0036)
* iogonek (U+012F)
* Eth (U+00D0)
* Oslash (U+00D8)
* lslash (U+0142)
* Hbar (U+0126)
* Eogonek (U+0118)
* Aogonek (U+0104)
* Dcroat (U+0110)
* Uogonek (U+0172)
* ccedilla (U+00E7)
* Lslash (U+0141)
* Scedilla (U+015E)
* hbar (U+0127)
* dcroat (U+0111)
* uni0162 (U+0162)
* oslash (U+00F8) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̌
* į̀
* į̃
* į̄
* į̂
* į́The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̋
* į̊
* į̒
* į̇
* į̆
* į̈ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - aring (U+00E5): X=312,Y=708 (should be at cap-height 710?)
* - f (U+0066): X=266.5,Y=711 (should be at cap-height 710?)
* - ij (U+0133): X=390,Y=1 (should be at baseline 0?)
* - ij (U+0133): X=485,Y=-2 (should be at baseline 0?)
* - j (U+006A): X=357,Y=1 (should be at baseline 0?)
* - j (U+006A): X=452,Y=-2 (should be at baseline 0?)
* - uni0237 (U+0237): X=357,Y=1 (should be at baseline 0?)
* - uni0237 (U+0237): X=452,Y=-2 (should be at baseline 0?)
* - uni006A0301: X=357,Y=1 (should be at baseline 0?)
* - uni006A0301: X=452,Y=-2 (should be at baseline 0?)
* - jcircumflex (U+0135): X=357,Y=1 (should be at baseline 0?)
* - jcircumflex (U+0135): X=452,Y=-2 (should be at baseline 0?)
* - germandbls (U+00DF): X=439.5,Y=708 (should be at cap-height 710?)
* - germandbls (U+00DF): X=229,Y=-2 (should be at baseline 0?)
* - t (U+0074): X=521,Y=-2 (should be at baseline 0?)
* - tbar (U+0167): X=521,Y=-2 (should be at baseline 0?)
* - tcaron (U+0165): X=521,Y=-2 (should be at baseline 0?)
* - uni0163 (U+0163): X=521,Y=-2 (should be at baseline 0?)
* - uni021B (U+021B): X=521,Y=-2 (should be at baseline 0?)
* - uring (U+016F): X=302,Y=708 (should be at cap-height 710?)
* - aring.cv01: X=294,Y=708 (should be at cap-height 710?)
* - fi (U+FB01): X=136.5,Y=711 (should be at cap-height 710?)
* - fl (U+FB02): X=140,Y=711 (should be at cap-height 710?)
* - lambda (U+03BB): X=549,Y=-1 (should be at baseline 0?)
* - lambda (U+03BB): X=500,Y=-1 (should be at baseline 0?)
* - seven.dnom: X=219,Y=1 (should be at baseline 0?)
* - seven.dnom: X=295,Y=1 (should be at baseline 0?)
* - one.numr: X=326,Y=711 (should be at cap-height 710?)
* - one.numr: X=392,Y=711 (should be at cap-height 710?)
* - four.numr: X=284,Y=711 (should be at cap-height 710?)
* - four.numr: X=362,Y=711 (should be at cap-height 710?)
* - five.numr: X=189,Y=711 (should be at cap-height 710?)
* - five.numr: X=410,Y=711 (should be at cap-height 710?)
* - six.numr: X=286,Y=711 (should be at cap-height 710?)
* - six.numr: X=367,Y=711 (should be at cap-height 710?)
* - seven.numr: X=170,Y=711 (should be at cap-height 710?)
* - seven.numr: X=435,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=153,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=219,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=153,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=219,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=153,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=219,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=153,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=219,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=153,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=219,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=47,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=268,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=22,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=287,Y=711 (should be at cap-height 710?)
* - questiondown (U+00BF): X=180,Y=2 (should be at baseline 0?)
* - at (U+0040): X=210.5,Y=1 (should be at baseline 0?)
* - at (U+0040): X=100,Y=2 (should be at baseline 0?)
* - dollar (U+0024): X=268,Y=1 (should be at baseline 0?)
* - dollar (U+0024): X=268,Y=708 (should be at cap-height 710?)
* - dollar (U+0024): X=347,Y=708 (should be at cap-height 710?)
* - dollar (U+0024): X=347,Y=2 (should be at baseline 0?)
* - Euro (U+20AC): X=547,Y=708 (should be at cap-height 710?)
* - Euro (U+20AC): X=547,Y=2 (should be at baseline 0?)
* - arrowupdn (U+2195): X=261,Y=2 (should be at baseline 0?)
* - arrowupdn (U+2195): X=345,Y=2 (should be at baseline 0?)
* - uni030A (U+030A): X=303,Y=708 (should be at cap-height 710?)
* - ring (U+02DA): X=303,Y=708 (should be at cap-height 710?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (263.0, 362.0) to (253.0, 574.0) is colinear with segment from (253.0, 574.0) to (253.0, 710.0)
* uniA78B (U+A78B): from (353.0, 710.0) to (353.0, 574.0) is colinear with segment from (353.0, 574.0) to (343.0, 362.0)
* uniA78C (U+A78C): from (263.0, 398.0) to (253.0, 610.0) is colinear with segment from (253.0, 610.0) to (253.0, 746.0)
* uniA78C (U+A78C): from (353.0, 746.0) to (353.0, 610.0) is colinear with segment from (353.0, 610.0) to (343.0, 398.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* six (U+0036): Line(Line { p0: (184.0, 372.0), p1: (183.0, 371.0) })/Quad(QuadBez { p0: (183.0, 371.0), p1: (193.0, 384.0), p2: (212.5, 402.5) }) = 7.431407971172539 degrees
* nine (U+0039): Line(Line { p0: (422.0, 338.0), p1: (423.0, 339.0) })/Quad(QuadBez { p0: (423.0, 339.0), p1: (413.0, 326.0), p2: (393.5, 307.5) }) = 7.431407971172539 degrees
* trademark (U+2122): Line(Line { p0: (413.0, 415.0), p1: (364.0, 609.0) })/Line(Line { p0: (364.0, 609.0), p1: (364.0, 374.0) }) = 14.175142055252481 degrees
* uni2116 (U+2116): Line(Line { p0: (137.0, 710.0), p1: (230.0, 233.0) })/Line(Line { p0: (230.0, 233.0), p1: (230.0, 710.0) }) = 11.032473240897687 degrees
* uni2116 (U+2116): Line(Line { p0: (214.0, 0.0), p1: (122.0, 477.0) })/Line(Line { p0: (122.0, 477.0), p1: (122.0, 0.0) }) = 10.916709640336949 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* M (U+004D): Line(Line { p0: (463.0, 0.0), p1: (468.0, 587.0) }) (angle: 89.51 degrees, expected: 90.00 degrees)
* M (U+004D): Line(Line { p0: (137.0, 587.0), p1: (142.0, 0.0) }) (angle: -89.51 degrees, expected: -90.00 degrees)
* arrowright.ss04: Line(Line { p0: (390.0, 382.0), p1: (391.0, 502.0) }) (angle: 89.52 degrees, expected: 90.00 degrees)
* arrowleft.ss04: Line(Line { p0: (214.0, 502.0), p1: (215.0, 382.0) }) (angle: -89.52 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* eogonek (U+0119) contains a short segment Quad(QuadBez { p0: (401.0, -120.0), p1: (409.0, -120.0), p2: (418.0, -119.0) }) (length: 17.04, total outline: 2885.66)
* eogonek (U+0119) contains a short segment Quad(QuadBez { p0: (418.0, -119.0), p1: (427.0, -118.0), p2: (435.0, -116.0) }) (length: 17.28, total outline: 2885.66)
* eogonek (U+0119) contains a short segment Quad(QuadBez { p0: (318.0, -12.0), p1: (311.0, -12.0), p2: (304.0, -12.0) }) (length: 14.00, total outline: 2885.66)
* uni0E3F (U+0E3F) contains a short segment Line(Line { p0: (323.0, 89.0), p1: (324.0, 89.0) }) (length: 1.00, total outline: 606.23)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (443.5, 187.0), p1: (451.0, 175.0), p2: (469.0, 175.0) }) (length: 29.53, total outline: 5157.31)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (469.0, 175.0), p1: (481.0, 175.0), p2: (492.0, 187.5) }) (length: 27.01, total outline: 5157.31)
* equal_less_less.liga contains a short segment Line(Line { p0: (115.0, 403.0), p1: (115.0, 402.0) }) (length: 1.00, total outline: 3146.08)
* greater_greater_equal.liga contains a short segment Line(Line { p0: (-721.0, 402.0), p1: (-721.0, 403.0) }) (length: 1.00, total outline: 3146.08)
* uni2303 (U+2303) contains a short segment Line(Line { p0: (300.0, 673.0), p1: (306.0, 673.0) }) (length: 6.00, total outline: 1559.66) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[17] fonts/terminal/DesignaliMonoTerm-ExtraLight.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Combined length of family and style must not exceed 32 characters. (name/family_and_style_max_length)</summary>
    <div>








- ⚠️ **WARN** Name ID 6 'PostScript Name' exceeds 27 characters (1 characters too long). This has been found to cause problems with PostScript printers, especially on Mac platforms. [code: nameid6-too-long]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* aogonek.cv01
* aogonek (U+0105)
* iogonek (U+012F)
* Eogonek (U+0118)
* uogonek (U+0173)
* Eth (U+00D0)
* Hbar (U+0126)
* uni0162 (U+0162)
* Dcroat (U+0110)
* Uogonek (U+0172)
* Oslash (U+00D8)
* scedilla (U+015F)
* hbar (U+0127)
* dcroat (U+0111)
* Ccedilla (U+00C7)
* Iogonek (U+012E)
* oslash (U+00F8)
* Aogonek (U+0104)
* Lslash (U+0141)
* Scedilla (U+015E)
* lslash (U+0142)
* uni0163 (U+0163)
* Tbar (U+0166)
* ccedilla (U+00E7) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į́
* į̃
* į̂
* į̄
* į̌
* į̀The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̇
* į̆
* į̋
* į̈
* į̒
* į̊ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - Q (U+0051): X=378,Y=-2 (should be at baseline 0?)
* - aring (U+00E5): X=355.5,Y=709.5 (should be at cap-height 710?)
* - aring (U+00E5): X=278.5,Y=709.5 (should be at cap-height 710?)
* - germandbls (U+00DF): X=143,Y=709.5 (should be at cap-height 710?)
* - germandbls (U+00DF): X=220,Y=-2 (should be at baseline 0?)
* - t (U+0074): X=527,Y=-2 (should be at baseline 0?)
* - tbar (U+0167): X=527,Y=-2 (should be at baseline 0?)
* - tcaron (U+0165): X=527,Y=-2 (should be at baseline 0?)
* - uni0163 (U+0163): X=527,Y=-2 (should be at baseline 0?)
* - uni021B (U+021B): X=527,Y=-2 (should be at baseline 0?)
* - uring (U+016F): X=340.5,Y=709.5 (should be at cap-height 710?)
* - uring (U+016F): X=263.5,Y=709.5 (should be at cap-height 710?)
* - aring.cv01: X=327.5,Y=709.5 (should be at cap-height 710?)
* - aring.cv01: X=250.5,Y=709.5 (should be at cap-height 710?)
* - fi (U+FB01): X=330.5,Y=711.5 (should be at cap-height 710?)
* - fl (U+FB02): X=341,Y=711.5 (should be at cap-height 710?)
* - seven.dnom: X=231,Y=1 (should be at baseline 0?)
* - seven.dnom: X=276,Y=1 (should be at baseline 0?)
* - one.numr: X=348,Y=711 (should be at cap-height 710?)
* - one.numr: X=386,Y=711 (should be at cap-height 710?)
* - four.numr: X=309,Y=711 (should be at cap-height 710?)
* - four.numr: X=354,Y=711 (should be at cap-height 710?)
* - five.numr: X=196,Y=711 (should be at cap-height 710?)
* - five.numr: X=403,Y=711 (should be at cap-height 710?)
* - six.numr: X=301,Y=711 (should be at cap-height 710?)
* - six.numr: X=348,Y=711 (should be at cap-height 710?)
* - seven.numr: X=170,Y=711 (should be at cap-height 710?)
* - seven.numr: X=435,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=175,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=213,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=175,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=213,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=175,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=213,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=175,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=213,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=175,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=213,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=59,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=266,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=22,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=287,Y=711 (should be at cap-height 710?)
* - uni2083 (U+2083): X=168,Y=-1 (should be at baseline 0?)
* - uni2083 (U+2083): X=210,Y=-1 (should be at baseline 0?)
* - uni2083 (U+2083): X=395,Y=1 (should be at baseline 0?)
* - uni2075 (U+2075): X=403,Y=709 (should be at cap-height 710?)
* - uni2075 (U+2075): X=236,Y=709 (should be at cap-height 710?)
* - uni2077 (U+2077): X=384,Y=708 (should be at cap-height 710?)
* - uni2077 (U+2077): X=170,Y=708 (should be at cap-height 710?)
* - uni2077 (U+2077): X=435,Y=711 (should be at cap-height 710?)
* - dollar (U+0024): X=283,Y=709 (should be at cap-height 710?)
* - dollar (U+0024): X=327,Y=709 (should be at cap-height 710?)
* - dollar (U+0024): X=327,Y=1 (should be at baseline 0?)
* - perthousand (U+2030): X=437,Y=1 (should be at baseline 0?)
* - perthousand (U+2030): X=371,Y=1 (should be at baseline 0?)
* - uni030A (U+030A): X=341.5,Y=709.5 (should be at cap-height 710?)
* - uni030A (U+030A): X=264.5,Y=709.5 (should be at cap-height 710?)
* - ring (U+02DA): X=341.5,Y=709.5 (should be at cap-height 710?)
* - ring (U+02DA): X=264.5,Y=709.5 (should be at cap-height 710?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - Q.BRACKET.varAlt01: X=378,Y=-2 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (283.0, 373.0) to (276.0, 578.0) is colinear with segment from (276.0, 578.0) to (276.0, 710.0)
* uniA78B (U+A78B): from (330.0, 710.0) to (330.0, 578.0) is colinear with segment from (330.0, 578.0) to (323.0, 373.0)
* uniA78C (U+A78C): from (283.0, 409.0) to (276.0, 614.0) is colinear with segment from (276.0, 614.0) to (276.0, 746.0)
* uniA78C (U+A78C): from (330.0, 746.0) to (330.0, 614.0) is colinear with segment from (330.0, 614.0) to (323.0, 409.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* trademark (U+2122): Line(Line { p0: (424.0, 403.0), p1: (361.0, 653.0) })/Line(Line { p0: (361.0, 653.0), p1: (361.0, 374.0) }) = 14.144043490326734 degrees
* uni2116 (U+2116): Line(Line { p0: (116.0, 710.0), p1: (254.0, 102.0) })/Line(Line { p0: (254.0, 102.0), p1: (254.0, 710.0) }) = 12.787972654802259 degrees
* uni2116 (U+2116): Line(Line { p0: (238.0, 0.0), p1: (101.0, 607.0) })/Line(Line { p0: (101.0, 607.0), p1: (101.0, 0.0) }) = 12.718561209358683 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* uni2197 (U+2197): Line(Line { p0: (483.0, 573.0), p1: (146.0, 572.0) }) (angle: -179.83 degrees, expected: -180.00 degrees)
* uni2197 (U+2197): Line(Line { p0: (516.0, 201.0), p1: (517.0, 542.0) }) (angle: 89.83 degrees, expected: 90.00 degrees)
* uni2198 (U+2198): Line(Line { p0: (145.0, 150.0), p1: (486.0, 149.0) }) (angle: -0.17 degrees, expected: 0.00 degrees)
* uni2199 (U+2199): Line(Line { p0: (120.0, 149.0), p1: (461.0, 150.0) }) (angle: 0.17 degrees, expected: 0.00 degrees)
* uni2196 (U+2196): Line(Line { p0: (89.0, 542.0), p1: (90.0, 201.0) }) (angle: -89.83 degrees, expected: -90.00 degrees)
* uni2196 (U+2196): Line(Line { p0: (460.0, 572.0), p1: (123.0, 573.0) }) (angle: 179.83 degrees, expected: 180.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* uni018F (U+018F) contains a short segment Line(Line { p0: (496.0, 350.0), p1: (496.0, 353.0) }) (length: 3.00, total outline: 3058.67)
* Eng (U+014A) contains a short segment Line(Line { p0: (467.0, 0.0), p1: (448.0, 0.0) }) (length: 19.00, total outline: 5011.96)
* uni20B9 (U+20B9) contains a short segment Line(Line { p0: (400.0, 491.0), p1: (400.0, 491.0) }) (length: 0.00, total outline: 3963.90)
* uni21E7 (U+21E7) contains a short segment Quad(QuadBez { p0: (29.0, 306.0), p1: (29.0, 311.0), p2: (32.0, 316.5) }) (length: 11.04, total outline: 1884.98)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-1112.0, 72.0), p1: (-1112.0, 116.0) }) (length: 44.00, total outline: 11106.90)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-1112.0, 282.0), p1: (-1112.0, 326.0) }) (length: 44.00, total outline: 11106.90)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-1112.0, 492.0), p1: (-1112.0, 536.0) }) (length: 44.00, total outline: 11106.90)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-190.0, 684.0), p1: (-139.0, 684.0) }) (length: 51.00, total outline: 11106.90)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (506.0, 536.0), p1: (506.0, 492.0) }) (length: 44.00, total outline: 11106.90)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (506.0, 326.0), p1: (506.0, 282.0) }) (length: 44.00, total outline: 11106.90)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (506.0, 116.0), p1: (506.0, 72.0) }) (length: 44.00, total outline: 11106.90)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-416.0, -76.0), p1: (-467.0, -76.0) }) (length: 51.00, total outline: 11106.90)
* equal_less_less.liga contains a short segment Line(Line { p0: (149.0, 421.0), p1: (149.0, 421.0) }) (length: 0.00, total outline: 3144.71)
* equal_slash_equal.liga contains a short segment Line(Line { p0: (-1112.0, 145.0), p1: (-1112.0, 192.0) }) (length: 47.00, total outline: 7979.90)
* equal_slash_equal.liga contains a short segment Line(Line { p0: (-1112.0, 416.0), p1: (-1112.0, 463.0) }) (length: 47.00, total outline: 7979.90)
* equal_slash_equal.liga contains a short segment Line(Line { p0: (506.0, 463.0), p1: (506.0, 416.0) }) (length: 47.00, total outline: 7979.90)
* equal_slash_equal.liga contains a short segment Line(Line { p0: (506.0, 192.0), p1: (506.0, 145.0) }) (length: 47.00, total outline: 7979.90)
* greater_greater_equal.liga contains a short segment Line(Line { p0: (-755.0, 421.0), p1: (-755.0, 421.0) }) (length: 0.00, total outline: 3144.71)
* less_hyphen_hyphen_greater.liga contains a short segment Line(Line { p0: (234.0, 12.0), p1: (203.0, 42.0) }) (length: 43.14, total outline: 7405.36)
* less_hyphen_hyphen_greater.liga contains a short segment Line(Line { p0: (-1415.0, 42.0), p1: (-1446.0, 12.0) }) (length: 43.14, total outline: 7405.36)
* less_hyphen_hyphen_greater.liga contains a short segment Line(Line { p0: (-1446.0, 596.0), p1: (-1415.0, 566.0) }) (length: 43.14, total outline: 7405.36)
* less_hyphen_hyphen_greater.liga contains a short segment Line(Line { p0: (203.0, 566.0), p1: (234.0, 596.0) }) (length: 43.14, total outline: 7405.36)
* uni2303 (U+2303) contains a short segment Line(Line { p0: (300.0, 673.0), p1: (306.0, 673.0) }) (length: 6.00, total outline: 1576.46) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[16] fonts/terminal/DesignaliMonoTerm-ExtraBold.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* Uogonek (U+0172)
* aogonek (U+0105)
* oslash (U+00F8)
* Scedilla (U+015E)
* Dcroat (U+0110)
* Eogonek (U+0118)
* Hbar (U+0126)
* Iogonek (U+012E)
* ccedilla (U+00E7)
* uogonek (U+0173)
* Tbar (U+0166)
* aogonek.cv01
* Oslash (U+00D8)
* Ccedilla (U+00C7)
* dcroat (U+0111)
* Lslash (U+0141)
* Aogonek (U+0104)
* Eth (U+00D0)
* hbar (U+0127)
* iogonek (U+012F)
* lslash (U+0142)
* scedilla (U+015F)
* uni0163 (U+0163)
* uni0162 (U+0162) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į́
* į̃
* į̂
* į̌
* į̀
* į̄The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̇
* į̆
* į̒
* į̈
* į̊
* į̋ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - germandbls (U+00DF): X=242,Y=-2 (should be at baseline 0?)
* - t (U+0074): X=513,Y=-2 (should be at baseline 0?)
* - tbar (U+0167): X=513,Y=-2 (should be at baseline 0?)
* - tcaron (U+0165): X=513,Y=-2 (should be at baseline 0?)
* - uni0163 (U+0163): X=513,Y=-2 (should be at baseline 0?)
* - uni021B (U+021B): X=513,Y=-2 (should be at baseline 0?)
* - y (U+0079): X=231,Y=2 (should be at baseline 0?)
* - yacute (U+00FD): X=231,Y=2 (should be at baseline 0?)
* - ycircumflex (U+0177): X=231,Y=2 (should be at baseline 0?)
* - ydieresis (U+00FF): X=231,Y=2 (should be at baseline 0?)
* - ygrave (U+1EF3): X=231,Y=2 (should be at baseline 0?)
* - uni1EF9 (U+1EF9): X=231,Y=2 (should be at baseline 0?)
* - seven.dnom: X=192,Y=1 (should be at baseline 0?)
* - seven.dnom: X=316,Y=1 (should be at baseline 0?)
* - one.numr: X=293,Y=711 (should be at cap-height 710?)
* - one.numr: X=405,Y=711 (should be at cap-height 710?)
* - four.numr: X=250,Y=711 (should be at cap-height 710?)
* - four.numr: X=370,Y=711 (should be at cap-height 710?)
* - five.numr: X=177,Y=711 (should be at cap-height 710?)
* - five.numr: X=422,Y=711 (should be at cap-height 710?)
* - six.numr: X=264,Y=711 (should be at cap-height 710?)
* - six.numr: X=398,Y=711 (should be at cap-height 710?)
* - seven.numr: X=160,Y=711 (should be at cap-height 710?)
* - seven.numr: X=445,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=120,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=232,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=120,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=232,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=120,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=232,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=120,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=232,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=120,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=232,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=29,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=274,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=12,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=297,Y=711 (should be at cap-height 710?)
* - questiondown (U+00BF): X=70,Y=2 (should be at baseline 0?)
* - at (U+0040): X=90,Y=-1 (should be at baseline 0?)
* - ampersand (U+0026): X=315.5,Y=2.5 (should be at baseline 0?)
* - exclam_asciitilde.liga: X=230,Y=-2 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (230.0, 345.0) to (220.0, 566.0) is colinear with segment from (220.0, 566.0) to (220.0, 710.0)
* uniA78B (U+A78B): from (386.0, 710.0) to (386.0, 566.0) is colinear with segment from (386.0, 566.0) to (376.0, 345.0)
* uniA78C (U+A78C): from (230.0, 381.0) to (220.0, 602.0) is colinear with segment from (220.0, 602.0) to (220.0, 746.0)
* uniA78C (U+A78C): from (386.0, 746.0) to (386.0, 602.0) is colinear with segment from (386.0, 602.0) to (376.0, 381.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* M (U+004D): Line(Line { p0: (405.0, 0.0), p1: (437.0, 512.0) })/Line(Line { p0: (437.0, 512.0), p1: (353.0, 170.0) }) = 10.223151021022044 degrees
* M (U+004D): Line(Line { p0: (252.0, 170.0), p1: (168.0, 512.0) })/Line(Line { p0: (168.0, 512.0), p1: (200.0, 0.0) }) = 10.223151021022044 degrees
* W (U+0057): Line(Line { p0: (182.0, 710.0), p1: (201.0, 277.0) })/Line(Line { p0: (201.0, 277.0), p1: (241.0, 548.0) }) = 10.908839040667193 degrees
* W (U+0057): Line(Line { p0: (364.0, 548.0), p1: (404.0, 277.0) })/Line(Line { p0: (404.0, 277.0), p1: (423.0, 710.0) }) = 10.908839040667193 degrees
* Wacute (U+1E82): Line(Line { p0: (182.0, 710.0), p1: (201.0, 277.0) })/Line(Line { p0: (201.0, 277.0), p1: (241.0, 548.0) }) = 10.908839040667193 degrees
* Wacute (U+1E82): Line(Line { p0: (364.0, 548.0), p1: (404.0, 277.0) })/Line(Line { p0: (404.0, 277.0), p1: (423.0, 710.0) }) = 10.908839040667193 degrees
* Wcircumflex (U+0174): Line(Line { p0: (182.0, 710.0), p1: (201.0, 277.0) })/Line(Line { p0: (201.0, 277.0), p1: (241.0, 548.0) }) = 10.908839040667193 degrees
* Wcircumflex (U+0174): Line(Line { p0: (364.0, 548.0), p1: (404.0, 277.0) })/Line(Line { p0: (404.0, 277.0), p1: (423.0, 710.0) }) = 10.908839040667193 degrees
* Wdieresis (U+1E84): Line(Line { p0: (182.0, 710.0), p1: (201.0, 277.0) })/Line(Line { p0: (201.0, 277.0), p1: (241.0, 548.0) }) = 10.908839040667193 degrees
* Wdieresis (U+1E84): Line(Line { p0: (364.0, 548.0), p1: (404.0, 277.0) })/Line(Line { p0: (404.0, 277.0), p1: (423.0, 710.0) }) = 10.908839040667193 degrees
* Wgrave (U+1E80): Line(Line { p0: (182.0, 710.0), p1: (201.0, 277.0) })/Line(Line { p0: (201.0, 277.0), p1: (241.0, 548.0) }) = 10.908839040667193 degrees
* Wgrave (U+1E80): Line(Line { p0: (364.0, 548.0), p1: (404.0, 277.0) })/Line(Line { p0: (404.0, 277.0), p1: (423.0, 710.0) }) = 10.908839040667193 degrees
* w (U+0077): Line(Line { p0: (170.0, 509.0), p1: (195.0, 167.0) })/Line(Line { p0: (195.0, 167.0), p1: (246.0, 509.0) }) = 12.662457523927673 degrees
* w (U+0077): Line(Line { p0: (359.0, 509.0), p1: (410.0, 167.0) })/Line(Line { p0: (410.0, 167.0), p1: (435.0, 509.0) }) = 12.662457523927673 degrees
* wacute (U+1E83): Line(Line { p0: (170.0, 509.0), p1: (195.0, 167.0) })/Line(Line { p0: (195.0, 167.0), p1: (246.0, 509.0) }) = 12.662457523927673 degrees
* wacute (U+1E83): Line(Line { p0: (359.0, 509.0), p1: (410.0, 167.0) })/Line(Line { p0: (410.0, 167.0), p1: (435.0, 509.0) }) = 12.662457523927673 degrees
* wcircumflex (U+0175): Line(Line { p0: (170.0, 509.0), p1: (195.0, 167.0) })/Line(Line { p0: (195.0, 167.0), p1: (246.0, 509.0) }) = 12.662457523927673 degrees
* wcircumflex (U+0175): Line(Line { p0: (359.0, 509.0), p1: (410.0, 167.0) })/Line(Line { p0: (410.0, 167.0), p1: (435.0, 509.0) }) = 12.662457523927673 degrees
* wdieresis (U+1E85): Line(Line { p0: (170.0, 509.0), p1: (195.0, 167.0) })/Line(Line { p0: (195.0, 167.0), p1: (246.0, 509.0) }) = 12.662457523927673 degrees
* wdieresis (U+1E85): Line(Line { p0: (359.0, 509.0), p1: (410.0, 167.0) })/Line(Line { p0: (410.0, 167.0), p1: (435.0, 509.0) }) = 12.662457523927673 degrees
* wgrave (U+1E81): Line(Line { p0: (170.0, 509.0), p1: (195.0, 167.0) })/Line(Line { p0: (195.0, 167.0), p1: (246.0, 509.0) }) = 12.662457523927673 degrees
* wgrave (U+1E81): Line(Line { p0: (359.0, 509.0), p1: (410.0, 167.0) })/Line(Line { p0: (410.0, 167.0), p1: (435.0, 509.0) }) = 12.662457523927673 degrees
* uni2116 (U+2116): Line(Line { p0: (128.0, 710.0), p1: (194.0, 420.0) })/Line(Line { p0: (194.0, 420.0), p1: (194.0, 710.0) }) = 12.8213437933989 degrees
* uni2116 (U+2116): Line(Line { p0: (206.0, 0.0), p1: (140.0, 296.0) })/Line(Line { p0: (140.0, 296.0), p1: (140.0, 0.0) }) = 12.569791807678728 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* bar_greater.liga: Line(Line { p0: (-345.0, -60.0), p1: (-346.0, 770.0) }) (angle: 90.07 degrees, expected: 90.00 degrees)
* less_bar.liga: Line(Line { p0: (346.0, 770.0), p1: (345.0, -60.0) }) (angle: -90.07 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* Eng (U+014A) contains a short segment Line(Line { p0: (374.0, 0.0), p1: (360.0, 0.0) }) (length: 14.00, total outline: 4070.49)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (483.0, 221.0), p1: (488.0, 212.0), p2: (500.0, 212.0) }) (length: 20.28, total outline: 5301.61)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (500.0, 212.0), p1: (510.0, 212.0), p2: (516.0, 223.5) }) (length: 20.82, total outline: 5301.61)
* Euro (U+20AC) contains a short segment Quad(QuadBez { p0: (110.0, 336.0), p1: (110.0, 345.0), p2: (110.0, 355.0) }) (length: 19.00, total outline: 3673.45)
* Euro (U+20AC) contains a short segment Quad(QuadBez { p0: (110.0, 355.0), p1: (110.0, 364.0), p2: (110.0, 373.0) }) (length: 18.00, total outline: 3673.45)
* Euro (U+20AC) contains a short segment Quad(QuadBez { p0: (278.0, 376.0), p1: (278.0, 366.0), p2: (278.0, 355.0) }) (length: 21.00, total outline: 3673.45)
* Euro (U+20AC) contains a short segment Quad(QuadBez { p0: (278.0, 355.0), p1: (278.0, 348.0), p2: (278.0, 341.0) }) (length: 14.00, total outline: 3673.45)
* uni20B1 (U+20B1) contains a short segment Quad(QuadBez { p0: (540.0, 436.0), p1: (540.0, 429.0), p2: (540.0, 422.0) }) (length: 14.00, total outline: 2586.48)
* uni20B1 (U+20B1) contains a short segment Quad(QuadBez { p0: (540.0, 422.0), p1: (540.0, 416.0), p2: (540.0, 410.0) }) (length: 12.00, total outline: 2586.48)
* sterling (U+00A3) contains a short segment Quad(QuadBez { p0: (164.0, 246.0), p1: (164.0, 255.0), p2: (163.0, 265.0) }) (length: 19.03, total outline: 3335.23)
* sterling (U+00A3) contains a short segment Line(Line { p0: (163.0, 265.0), p1: (163.0, 265.0) }) (length: 0.00, total outline: 3335.23)
* uni2303 (U+2303) contains a short segment Line(Line { p0: (300.0, 673.0), p1: (306.0, 673.0) }) (length: 6.00, total outline: 1477.23)
* Q.BRACKET.varAlt01 contains a short segment Line(Line { p0: (384.0, 284.0), p1: (385.0, 278.0) }) (length: 6.08, total outline: 1063.33) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[16] fonts/terminal/DesignaliMonoTerm-Regular.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* oslash (U+00F8)
* Iogonek (U+012E)
* uni0163 (U+0163)
* Ccedilla (U+00C7)
* uogonek (U+0173)
* Aogonek (U+0104)
* aogonek.cv01
* nine.dnom
* uni2086 (U+2086)
* Dcroat (U+0110)
* ccedilla (U+00E7)
* aogonek (U+0105)
* Scedilla (U+015E)
* six.dnom
* Hbar (U+0126)
* Oslash (U+00D8)
* Tbar (U+0166)
* Uogonek (U+0172)
* nine.numr
* uni2089 (U+2089)
* dcroat (U+0111)
* hbar (U+0127)
* lslash (U+0142)
* uni2465 (U+2465)
* six.numr
* Eogonek (U+0118)
* Lslash (U+0141)
* uni0162 (U+0162)
* scedilla (U+015F)
* iogonek (U+012F)
* uni2076 (U+2076)
* Eth (U+00D0) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̃
* į̄
* į́
* į̌
* į̀
* į̂The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̒
* į̈
* į̇
* į̊
* į̋
* į̆ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - aring (U+00E5): X=314,Y=711 (should be at cap-height 710?)
* - eth (U+00F0): X=339.5,Y=709.5 (should be at cap-height 710?)
* - f (U+0066): X=270,Y=712 (should be at cap-height 710?)
* - germandbls (U+00DF): X=437,Y=708 (should be at cap-height 710?)
* - germandbls (U+00DF): X=227,Y=-2 (should be at baseline 0?)
* - t (U+0074): X=522,Y=-2 (should be at baseline 0?)
* - tbar (U+0167): X=522,Y=-2 (should be at baseline 0?)
* - tcaron (U+0165): X=522,Y=-2 (should be at baseline 0?)
* - uni0163 (U+0163): X=522,Y=-2 (should be at baseline 0?)
* - uni021B (U+021B): X=522,Y=-2 (should be at baseline 0?)
* - uring (U+016F): X=302,Y=711 (should be at cap-height 710?)
* - aring.cv01: X=292,Y=711 (should be at cap-height 710?)
* - fi (U+FB01): X=137,Y=712 (should be at cap-height 710?)
* - fl (U+FB02): X=141,Y=712 (should be at cap-height 710?)
* - lambda (U+03BB): X=546,Y=-1 (should be at baseline 0?)
* - lambda (U+03BB): X=502,Y=-1 (should be at baseline 0?)
* - seven.dnom: X=222,Y=1 (should be at baseline 0?)
* - seven.dnom: X=293,Y=1 (should be at baseline 0?)
* - one.numr: X=330,Y=711 (should be at cap-height 710?)
* - one.numr: X=390,Y=711 (should be at cap-height 710?)
* - four.numr: X=288,Y=711 (should be at cap-height 710?)
* - four.numr: X=361,Y=711 (should be at cap-height 710?)
* - five.numr: X=190,Y=711 (should be at cap-height 710?)
* - five.numr: X=409,Y=711 (should be at cap-height 710?)
* - six.numr: X=289,Y=711 (should be at cap-height 710?)
* - six.numr: X=363,Y=711 (should be at cap-height 710?)
* - seven.numr: X=171,Y=711 (should be at cap-height 710?)
* - seven.numr: X=434,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=157,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=217,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=157,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=217,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=157,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=217,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=157,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=217,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=157,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=217,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=49,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=268,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=23,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=286,Y=711 (should be at cap-height 710?)
* - uni2088 (U+2088): X=374,Y=1 (should be at baseline 0?)
* - uni2088 (U+2088): X=231,Y=1 (should be at baseline 0?)
* - questiondown (U+00BF): X=173,Y=1 (should be at baseline 0?)
* - braceleft (U+007B): X=307.5,Y=1 (should be at baseline 0?)
* - braceright (U+007D): X=298.5,Y=1 (should be at baseline 0?)
* - at (U+0040): X=211,Y=1 (should be at baseline 0?)
* - at (U+0040): X=101.5,Y=2 (should be at baseline 0?)
* - dollar (U+0024): X=271,Y=1 (should be at baseline 0?)
* - dollar (U+0024): X=271,Y=708 (should be at cap-height 710?)
* - dollar (U+0024): X=345,Y=708 (should be at cap-height 710?)
* - dollar (U+0024): X=345,Y=2 (should be at baseline 0?)
* - Euro (U+20AC): X=545,Y=708 (should be at cap-height 710?)
* - Euro (U+20AC): X=545,Y=2 (should be at baseline 0?)
* - greaterequal (U+2265): X=80,Y=1 (should be at baseline 0?)
* - greaterequal (U+2265): X=526,Y=1 (should be at baseline 0?)
* - lessequal (U+2264): X=526,Y=1 (should be at baseline 0?)
* - lessequal (U+2264): X=80,Y=1 (should be at baseline 0?)
* - plusminus (U+00B1): X=50,Y=1 (should be at baseline 0?)
* - plusminus (U+00B1): X=556,Y=1 (should be at baseline 0?)
* - integral (U+222B): X=230,Y=-2 (should be at baseline 0?)
* - uni00B5 (U+00B5): X=216,Y=-2.5 (should be at baseline 0?)
* - uni030A (U+030A): X=303,Y=711 (should be at cap-height 710?)
* - ring (U+02DA): X=303,Y=711 (should be at cap-height 710?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (267.0, 364.0) to (257.0, 575.0) is colinear with segment from (257.0, 575.0) to (257.0, 710.0)
* uniA78B (U+A78B): from (349.0, 710.0) to (349.0, 575.0) is colinear with segment from (349.0, 575.0) to (339.0, 364.0)
* uniA78C (U+A78C): from (267.0, 400.0) to (257.0, 611.0) is colinear with segment from (257.0, 611.0) to (257.0, 746.0)
* uniA78C (U+A78C): from (349.0, 746.0) to (349.0, 611.0) is colinear with segment from (349.0, 611.0) to (339.0, 400.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni2465 (U+2465): Line(Line { p0: (244.0, 375.0), p1: (243.0, 374.0) })/Quad(QuadBez { p0: (243.0, 374.0), p1: (253.0, 385.0), p2: (271.5, 397.0) }) = 2.7263109939063455 degrees
* six.dnom: Line(Line { p0: (244.0, 203.0), p1: (243.0, 202.0) })/Quad(QuadBez { p0: (243.0, 202.0), p1: (253.0, 213.0), p2: (271.5, 225.0) }) = 2.7263109939063455 degrees
* nine.dnom: Line(Line { p0: (362.0, 170.0), p1: (363.0, 171.0) })/Quad(QuadBez { p0: (363.0, 171.0), p1: (353.0, 160.0), p2: (334.5, 148.0) }) = 2.7263109939063455 degrees
* six.numr: Line(Line { p0: (244.0, 541.0), p1: (243.0, 540.0) })/Quad(QuadBez { p0: (243.0, 540.0), p1: (253.0, 551.0), p2: (271.5, 563.0) }) = 2.7263109939063455 degrees
* nine.numr: Line(Line { p0: (362.0, 508.0), p1: (363.0, 509.0) })/Quad(QuadBez { p0: (363.0, 509.0), p1: (353.0, 498.0), p2: (334.5, 486.0) }) = 2.7263109939063455 degrees
* uni2086 (U+2086): Line(Line { p0: (244.0, 97.0), p1: (243.0, 96.0) })/Quad(QuadBez { p0: (243.0, 96.0), p1: (253.0, 107.0), p2: (271.5, 119.0) }) = 2.7263109939063455 degrees
* uni2089 (U+2089): Line(Line { p0: (362.0, 64.0), p1: (363.0, 65.0) })/Quad(QuadBez { p0: (363.0, 65.0), p1: (353.0, 54.0), p2: (334.5, 42.0) }) = 2.7263109939063455 degrees
* uni2076 (U+2076): Line(Line { p0: (244.0, 577.0), p1: (243.0, 576.0) })/Quad(QuadBez { p0: (243.0, 576.0), p1: (253.0, 587.0), p2: (271.5, 599.0) }) = 2.7263109939063455 degrees
* trademark (U+2122): Line(Line { p0: (414.0, 413.0), p1: (362.0, 623.0) })/Line(Line { p0: (362.0, 623.0), p1: (362.0, 374.0) }) = 13.907777809854728 degrees
* uni2116 (U+2116): Line(Line { p0: (138.0, 710.0), p1: (234.0, 208.0) })/Line(Line { p0: (234.0, 208.0), p1: (234.0, 710.0) }) = 10.826249739628546 degrees
* uni2116 (U+2116): Line(Line { p0: (215.0, 0.0), p1: (120.0, 502.0) })/Line(Line { p0: (120.0, 502.0), p1: (120.0, 0.0) }) = 10.716101128693715 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* M (U+004D): Line(Line { p0: (470.0, 0.0), p1: (472.0, 594.0) }) (angle: 89.81 degrees, expected: 90.00 degrees)
* M (U+004D): Line(Line { p0: (133.0, 594.0), p1: (135.0, 0.0) }) (angle: -89.81 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* eogonek (U+0119) contains a short segment Quad(QuadBez { p0: (398.0, -123.0), p1: (406.0, -123.0), p2: (414.5, -122.0) }) (length: 16.54, total outline: 2888.34)
* eogonek (U+0119) contains a short segment Quad(QuadBez { p0: (414.5, -122.0), p1: (423.0, -121.0), p2: (431.0, -119.0) }) (length: 16.78, total outline: 2888.34)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (439.0, 183.0), p1: (447.0, 170.0), p2: (465.0, 170.0) }) (length: 30.50, total outline: 5143.53)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (465.0, 170.0), p1: (477.0, 170.0), p2: (488.5, 183.0) }) (length: 27.69, total outline: 5143.53)
* equal_less_less.liga contains a short segment Line(Line { p0: (123.0, 406.0), p1: (123.0, 405.0) }) (length: 1.00, total outline: 3159.54)
* greater_greater_equal.liga contains a short segment Line(Line { p0: (-729.0, 405.0), p1: (-729.0, 406.0) }) (length: 1.00, total outline: 3159.54)
* uni2303 (U+2303) contains a short segment Line(Line { p0: (300.0, 673.0), p1: (306.0, 673.0) }) (length: 6.00, total outline: 1572.19) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[16] fonts/terminal/DesignaliMonoTerm-SemiBold.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* dcroat (U+0111)
* aogonek.cv01
* Tbar (U+0166)
* Eogonek (U+0118)
* Oslash (U+00D8)
* Aogonek (U+0104)
* Lslash (U+0141)
* uni0162 (U+0162)
* ccedilla (U+00E7)
* iogonek (U+012F)
* lslash (U+0142)
* Iogonek (U+012E)
* aogonek (U+0105)
* Ccedilla (U+00C7)
* Eth (U+00D0)
* hbar (U+0127)
* oslash (U+00F8)
* uni0163 (U+0163)
* scedilla (U+015F)
* Uogonek (U+0172)
* Dcroat (U+0110)
* Hbar (U+0126)
* Scedilla (U+015E)
* uogonek (U+0173) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̄
* į́
* į̃
* į̂
* į̌
* į̀The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̒
* į̊
* į̋
* į̆
* į̈
* į̇ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - atilde (U+00E3): X=298.5,Y=711 (should be at cap-height 710?)
* - uni1EBD (U+1EBD): X=297.5,Y=711 (should be at cap-height 710?)
* - f (U+0066): X=259,Y=709.5 (should be at cap-height 710?)
* - itilde (U+0129): X=308.5,Y=711 (should be at cap-height 710?)
* - ntilde (U+00F1): X=293.5,Y=711 (should be at cap-height 710?)
* - otilde (U+00F5): X=292.5,Y=711 (should be at cap-height 710?)
* - germandbls (U+00DF): X=232,Y=-2 (should be at baseline 0?)
* - t (U+0074): X=519,Y=-2 (should be at baseline 0?)
* - tbar (U+0167): X=519,Y=-2 (should be at baseline 0?)
* - tcaron (U+0165): X=519,Y=-2 (should be at baseline 0?)
* - uni0163 (U+0163): X=519,Y=-2 (should be at baseline 0?)
* - uni021B (U+021B): X=519,Y=-2 (should be at baseline 0?)
* - utilde (U+0169): X=291.5,Y=711 (should be at cap-height 710?)
* - uni1EF9 (U+1EF9): X=291.5,Y=711 (should be at cap-height 710?)
* - atilde.cv01: X=286.5,Y=711 (should be at cap-height 710?)
* - fi (U+FB01): X=136.5,Y=709.5 (should be at cap-height 710?)
* - fl (U+FB02): X=139,Y=709.5 (should be at cap-height 710?)
* - lambda (U+03BB): X=554,Y=-1 (should be at baseline 0?)
* - lambda (U+03BB): X=496,Y=-1 (should be at baseline 0?)
* - seven.dnom: X=212,Y=1 (should be at baseline 0?)
* - seven.dnom: X=300,Y=1 (should be at baseline 0?)
* - one.numr: X=318,Y=711 (should be at cap-height 710?)
* - one.numr: X=395,Y=711 (should be at cap-height 710?)
* - four.numr: X=276,Y=711 (should be at cap-height 710?)
* - four.numr: X=364,Y=711 (should be at cap-height 710?)
* - five.numr: X=186,Y=711 (should be at cap-height 710?)
* - five.numr: X=413,Y=711 (should be at cap-height 710?)
* - six.numr: X=281,Y=711 (should be at cap-height 710?)
* - six.numr: X=374,Y=711 (should be at cap-height 710?)
* - seven.numr: X=167,Y=711 (should be at cap-height 710?)
* - seven.numr: X=438,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=145,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=222,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=145,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=222,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=145,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=222,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=145,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=222,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=145,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=222,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=43,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=270,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=19,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=290,Y=711 (should be at cap-height 710?)
* - uni2085 (U+2085): X=165,Y=-2 (should be at baseline 0?)
* - uni2085 (U+2085): X=249,Y=-2 (should be at baseline 0?)
* - uni2089 (U+2089): X=398,Y=1 (should be at baseline 0?)
* - questiondown (U+00BF): X=77,Y=1 (should be at baseline 0?)
* - at (U+0040): X=98,Y=1.5 (should be at baseline 0?)
* - dollar (U+0024): X=263,Y=2 (should be at baseline 0?)
* - dollar (U+0024): X=263,Y=708 (should be at cap-height 710?)
* - dollar (U+0024): X=352,Y=708 (should be at cap-height 710?)
* - Euro (U+20AC): X=551,Y=709 (should be at cap-height 710?)
* - Euro (U+20AC): X=551,Y=1 (should be at baseline 0?)
* - tildecomb (U+0303): X=292.5,Y=711 (should be at cap-height 710?)
* - tilde (U+02DC): X=292.5,Y=711 (should be at cap-height 710?)
* - uni21EA (U+21EA): X=123,Y=1 (should be at baseline 0?)
* - uni21EA (U+21EA): X=483,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (255.0, 358.0) to (245.0, 572.0) is colinear with segment from (245.0, 572.0) to (245.0, 710.0)
* uniA78B (U+A78B): from (361.0, 710.0) to (361.0, 572.0) is colinear with segment from (361.0, 572.0) to (351.0, 358.0)
* uniA78C (U+A78C): from (255.0, 394.0) to (245.0, 608.0) is colinear with segment from (245.0, 608.0) to (245.0, 746.0)
* uniA78C (U+A78C): from (361.0, 746.0) to (361.0, 608.0) is colinear with segment from (361.0, 608.0) to (351.0, 394.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* uni2116 (U+2116): Line(Line { p0: (135.0, 710.0), p1: (221.0, 282.0) })/Line(Line { p0: (221.0, 282.0), p1: (221.0, 710.0) }) = 11.36141114796064 degrees
* uni2116 (U+2116): Line(Line { p0: (212.0, 0.0), p1: (126.0, 430.0) })/Line(Line { p0: (126.0, 430.0), p1: (126.0, 0.0) }) = 11.309932474020227 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* uni2197 (U+2197): Line(Line { p0: (411.0, 523.0), p1: (155.0, 522.0) }) (angle: -179.78 degrees, expected: -180.00 degrees)
* uni2196 (U+2196): Line(Line { p0: (451.0, 522.0), p1: (195.0, 523.0) }) (angle: 179.78 degrees, expected: 180.00 degrees)
* uni21E7 (U+21E7): Line(Line { p0: (454.0, 275.0), p1: (453.0, 72.0) }) (angle: -90.28 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* Eng (U+014A) contains a short segment Line(Line { p0: (417.0, 0.0), p1: (390.0, 0.0) }) (length: 27.00, total outline: 4640.38)
* uni0E3F (U+0E3F) contains a short segment Line(Line { p0: (327.0, 415.0), p1: (329.0, 415.0) }) (length: 2.00, total outline: 484.82)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (453.0, 195.5), p1: (460.0, 184.0), p2: (476.0, 184.0) }) (length: 26.99, total outline: 5193.51)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (476.0, 184.0), p1: (488.0, 184.0), p2: (498.0, 196.0) }) (length: 25.92, total outline: 5193.51)
* equal_less_less.liga contains a short segment Line(Line { p0: (99.0, 397.0), p1: (99.0, 396.0) }) (length: 1.00, total outline: 3120.87)
* greater_greater_equal.liga contains a short segment Line(Line { p0: (-705.0, 396.0), p1: (-705.0, 397.0) }) (length: 1.00, total outline: 3120.87)
* uni2303 (U+2303) contains a short segment Line(Line { p0: (300.0, 673.0), p1: (306.0, 673.0) }) (length: 6.00, total outline: 1540.72) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[15] fonts/terminal/DesignaliMonoTerm-Thin.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* Ccedilla (U+00C7)
* lslash (U+0142)
* oslash (U+00F8)
* aogonek.cv01
* Lslash (U+0141)
* hbar (U+0127)
* Oslash (U+00D8)
* Eogonek (U+0118)
* Hbar (U+0126)
* aogonek (U+0105)
* Iogonek (U+012E)
* dcroat (U+0111)
* scedilla (U+015F)
* uni0163 (U+0163)
* uogonek (U+0173)
* iogonek (U+012F)
* Tbar (U+0166)
* Dcroat (U+0110)
* uni0162 (U+0162)
* Scedilla (U+015E)
* Uogonek (U+0172)
* Eth (U+00D0)
* Aogonek (U+0104)
* ccedilla (U+00E7) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̄
* į̃
* į̌
* į̂
* į́
* į̀The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̊
* į̒
* į̆
* į̋
* į̇
* į̈ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - Q (U+0051): X=388,Y=2 (should be at baseline 0?)
* - germandbls (U+00DF): X=216,Y=-2 (should be at baseline 0?)
* - t (U+0074): X=529,Y=-2 (should be at baseline 0?)
* - tbar (U+0167): X=529,Y=-2 (should be at baseline 0?)
* - tcaron (U+0165): X=529,Y=-2 (should be at baseline 0?)
* - uni0163 (U+0163): X=529,Y=-2 (should be at baseline 0?)
* - uni021B (U+021B): X=529,Y=-2 (should be at baseline 0?)
* - seven.dnom: X=236,Y=1 (should be at baseline 0?)
* - seven.dnom: X=266,Y=1 (should be at baseline 0?)
* - one.numr: X=358,Y=711 (should be at cap-height 710?)
* - one.numr: X=383,Y=711 (should be at cap-height 710?)
* - four.numr: X=320,Y=711 (should be at cap-height 710?)
* - four.numr: X=350,Y=711 (should be at cap-height 710?)
* - five.numr: X=200,Y=711 (should be at cap-height 710?)
* - five.numr: X=400,Y=711 (should be at cap-height 710?)
* - six.numr: X=308,Y=711 (should be at cap-height 710?)
* - six.numr: X=340,Y=711 (should be at cap-height 710?)
* - seven.numr: X=170,Y=711 (should be at cap-height 710?)
* - seven.numr: X=435,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=185,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=210,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=185,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=210,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=185,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=210,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=185,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=210,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=185,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=210,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=65,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=265,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=22,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=287,Y=711 (should be at cap-height 710?)
* - uni2083 (U+2083): X=407,Y=-2 (should be at baseline 0?)
* - uni00B3 (U+00B3): X=376,Y=708 (should be at cap-height 710?)
* - uni00B3 (U+00B3): X=228,Y=709 (should be at cap-height 710?)
* - period (U+002E): X=267,Y=2.5 (should be at baseline 0?)
* - period (U+002E): X=339.5,Y=2.5 (should be at baseline 0?)
* - colon (U+003A): X=267,Y=2.5 (should be at baseline 0?)
* - colon (U+003A): X=339.5,Y=2.5 (should be at baseline 0?)
* - ellipsis (U+2026): X=64,Y=2.5 (should be at baseline 0?)
* - ellipsis (U+2026): X=136.5,Y=2.5 (should be at baseline 0?)
* - ellipsis (U+2026): X=267,Y=2.5 (should be at baseline 0?)
* - ellipsis (U+2026): X=339.5,Y=2.5 (should be at baseline 0?)
* - ellipsis (U+2026): X=470,Y=2.5 (should be at baseline 0?)
* - ellipsis (U+2026): X=542.5,Y=2.5 (should be at baseline 0?)
* - exclam (U+0021): X=267,Y=2 (should be at baseline 0?)
* - exclam (U+0021): X=339.5,Y=2 (should be at baseline 0?)
* - question (U+003F): X=270,Y=2 (should be at baseline 0?)
* - question (U+003F): X=342.5,Y=2 (should be at baseline 0?)
* - equal_exclam_equal.liga: X=-339,Y=2 (should be at baseline 0?)
* - equal_exclam_equal.liga: X=-266.5,Y=2 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - Q.BRACKET.varAlt01: X=388,Y=2 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (292.0, 378.0) to (287.0, 580.0) is colinear with segment from (287.0, 580.0) to (287.0, 710.0)
* uniA78B (U+A78B): from (319.0, 710.0) to (319.0, 580.0) is colinear with segment from (319.0, 580.0) to (314.0, 378.0)
* uniA78C (U+A78C): from (292.0, 414.0) to (287.0, 616.0) is colinear with segment from (287.0, 616.0) to (287.0, 746.0)
* uniA78C (U+A78C): from (319.0, 746.0) to (319.0, 616.0) is colinear with segment from (319.0, 616.0) to (314.0, 414.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* trademark (U+2122): Line(Line { p0: (429.0, 398.0), p1: (360.0, 670.0) })/Line(Line { p0: (360.0, 670.0), p1: (360.0, 374.0) }) = 14.23432661828661 degrees
* uni2116 (U+2116): Line(Line { p0: (104.0, 710.0), p1: (265.0, 51.0) })/Line(Line { p0: (265.0, 51.0), p1: (265.0, 710.0) }) = 13.728975518859539 degrees
* uni2116 (U+2116): Line(Line { p0: (251.0, 0.0), p1: (90.0, 657.0) })/Line(Line { p0: (90.0, 657.0), p1: (90.0, 0.0) }) = 13.769180097740424 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* p (U+0070): Line(Line { p0: (128.0, 509.0), p1: (129.0, 388.0) }) (angle: -89.53 degrees, expected: -90.00 degrees)
* q (U+0071): Line(Line { p0: (477.0, 390.0), p1: (478.0, 509.0) }) (angle: 89.52 degrees, expected: 90.00 degrees)
* uni2197 (U+2197): Line(Line { p0: (509.0, 591.0), p1: (142.0, 590.0) }) (angle: -179.84 degrees, expected: -180.00 degrees)
* uni2197 (U+2197): Line(Line { p0: (529.0, 202.0), p1: (531.0, 573.0) }) (angle: 89.69 degrees, expected: 90.00 degrees)
* uni2198 (U+2198): Line(Line { p0: (530.0, 157.0), p1: (529.0, 524.0) }) (angle: 90.16 degrees, expected: 90.00 degrees)
* uni2198 (U+2198): Line(Line { p0: (141.0, 137.0), p1: (512.0, 135.0) }) (angle: -0.31 degrees, expected: 0.00 degrees)
* uni2199 (U+2199): Line(Line { p0: (77.0, 524.0), p1: (76.0, 157.0) }) (angle: -90.16 degrees, expected: -90.00 degrees)
* uni2199 (U+2199): Line(Line { p0: (94.0, 135.0), p1: (465.0, 137.0) }) (angle: 0.31 degrees, expected: 0.00 degrees)
* uni2196 (U+2196): Line(Line { p0: (75.0, 573.0), p1: (77.0, 202.0) }) (angle: -89.69 degrees, expected: -90.00 degrees)
* uni2196 (U+2196): Line(Line { p0: (464.0, 590.0), p1: (97.0, 591.0) }) (angle: 179.84 degrees, expected: 180.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[2] fonts/terminal</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Ensure Fonts have 'ital' STAT axis. (opentype/STAT/ital_axis)</summary>
    <div>








- ⚠️ **WARN** Static font is missing the 'STAT' table. [code: no-stat-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-Bold.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-ExtraBold.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-ExtraLight.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-Light.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-Medium.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-Regular.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-SemiBold.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** fonts/terminal/DesignaliMonoTerm-Thin.ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
* U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
* U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
* U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
* U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, hebrew, todhri, math, old-permic, duployan, coptic, malayalam, syriac
* U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan
* U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
* U+030C COMBINING CARON: try adding one of: cherokee, tai-le
* U+0312 COMBINING TURNED COMMA ABOVE: try adding math
* U+0326 COMBINING COMMA BELOW: try adding math
* U+0327 COMBINING CEDILLA: try adding math
* U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math
* U+039B GREEK CAPITAL LETTER LAMDA: try adding one of: math, elbasan, greek
* U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek
* U+03BB GREEK SMALL LETTER LAMDA: try adding one of: math, greek
* U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math
* U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, math, yi
* U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
* U+2021 DOUBLE DAGGER: try adding adlam
* U+2030 PER MILLE SIGN: try adding adlam
* U+2070 SUPERSCRIPT ZERO: try adding math
* U+2074 SUPERSCRIPT FOUR: try adding math
* U+2075 SUPERSCRIPT FIVE: try adding math
* U+2076 SUPERSCRIPT SIX: try adding math
* U+2077 SUPERSCRIPT SEVEN: try adding math
* U+2078 SUPERSCRIPT EIGHT: try adding math
* U+2079 SUPERSCRIPT NINE: try adding math
* U+2080 SUBSCRIPT ZERO: try adding math
* U+2081 SUBSCRIPT ONE: try adding math
* U+2082 SUBSCRIPT TWO: try adding math
* U+2083 SUBSCRIPT THREE: try adding math
* U+2084 SUBSCRIPT FOUR: try adding math
* U+2085 SUBSCRIPT FIVE: try adding math
* U+2086 SUBSCRIPT SIX: try adding math
* U+2087 SUBSCRIPT SEVEN: try adding math
* U+2088 SUBSCRIPT EIGHT: try adding math
* U+2089 SUBSCRIPT NINE: try adding math
* U+2116 NUMERO SIGN: try adding cyrillic
* U+2117 SOUND RECORDING COPYRIGHT: try adding math
* U+2153 VULGAR FRACTION ONE THIRD: try adding symbols
* U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols
* U+2155 VULGAR FRACTION ONE FIFTH: try adding symbols
* U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols
* U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols
* U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols
* U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols
* U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
* U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
* U+2194 LEFT RIGHT ARROW: try adding one of: math, symbols
* U+2195 UP DOWN ARROW: try adding one of: symbols, math
* U+2196 NORTH WEST ARROW: try adding one of: math, symbols
* U+2197 NORTH EAST ARROW: try adding one of: symbols, math
* U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
* U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
* U+21A9 LEFTWARDS ARROW WITH HOOK: try adding math
* U+21AA RIGHTWARDS ARROW WITH HOOK: try adding math
* U+21B0 UPWARDS ARROW WITH TIP LEFTWARDS: try adding math
* U+21B1 UPWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B3 DOWNWARDS ARROW WITH TIP RIGHTWARDS: try adding math
* U+21B4 RIGHTWARDS ARROW WITH CORNER DOWNWARDS: try adding math
* U+21B5 DOWNWARDS ARROW WITH CORNER LEFTWARDS: try adding math
* U+21B9 LEFTWARDS ARROW TO BAR OVER RIGHTWARDS ARROW TO BAR: try adding math
* U+21C6 LEFTWARDS ARROW OVER RIGHTWARDS ARROW: try adding math
* U+21E4 LEFTWARDS ARROW TO BAR: try adding math
* U+21E5 RIGHTWARDS ARROW TO BAR: try adding math
* U+21E7 UPWARDS WHITE ARROW: try adding symbols
* U+21EA UPWARDS WHITE ARROW FROM BAR: try adding symbols
* U+2202 PARTIAL DIFFERENTIAL: try adding math
* U+2206 INCREMENT: try adding math
* U+220F N-ARY PRODUCT: try adding math
* U+2211 N-ARY SUMMATION: try adding math
* U+221A SQUARE ROOT: try adding math
* U+221E INFINITY: try adding math
* U+222B INTEGRAL: try adding math
* U+2236 RATIO: try adding math
* U+2248 ALMOST EQUAL TO: try adding math
* U+2260 NOT EQUAL TO: try adding math
* U+2264 LESS-THAN OR EQUAL TO: try adding math
* U+2265 GREATER-THAN OR EQUAL TO: try adding math
* U+2303 UP ARROWHEAD: try adding symbols
* U+2318 PLACE OF INTEREST SIGN: try adding symbols
* U+2325 OPTION KEY: try adding symbols
* U+2326 ERASE TO THE RIGHT: try adding symbols
* U+2327 X IN A RECTANGLE BOX: try adding symbols
* U+232B ERASE TO THE LEFT: try adding symbols
* U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
* U+23CE RETURN SYMBOL: try adding symbols
* U+2460 CIRCLED DIGIT ONE: try adding one of: yi, symbols, mongolian
* U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
* U+2462 CIRCLED DIGIT THREE: try adding one of: mongolian, yi, symbols
* U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
* U+2464 CIRCLED DIGIT FIVE: try adding one of: yi, mongolian, symbols
* U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
* U+2466 CIRCLED DIGIT SEVEN: try adding one of: mongolian, symbols, yi
* U+2467 CIRCLED DIGIT EIGHT: try adding one of: yi, mongolian, symbols
* U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, yi, mongolian
* U+24EA CIRCLED DIGIT ZERO: try adding symbols
* U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
* U+25CA LOZENGE: try adding one of: symbols, math
* U+25CB WHITE CIRCLE: try adding symbols
* U+25CF BLACK CIRCLE: try adding symbols
* U+25E6 WHITE BULLET: try adding symbols
* U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
* U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
* U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
* U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
* U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
* U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
* U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
* U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
* U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
* U+3003 DITTO MARK: try adding one of: chinese-traditional, yi, chinese-hongkong, japanese, phags-pa, chinese-simplified
* U+301C WAVE DASH: try adding japanese

Or you can add the above codepoints to one of the subsets supported by the font: cyrillic-ext, latin-ext, latin, symbols2 [code: unreachable-subsetting]
  
  

</div>
</details>


</div>
</details>


<details><summary>[16] fonts/terminal/DesignaliMonoTerm-Bold.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* uni0162 (U+0162)
* Eth (U+00D0)
* Dcroat (U+0110)
* Ccedilla (U+00C7)
* lslash (U+0142)
* uogonek (U+0173)
* aogonek.cv01
* dcroat (U+0111)
* Tbar (U+0166)
* ccedilla (U+00E7)
* aogonek (U+0105)
* Oslash (U+00D8)
* scedilla (U+015F)
* Hbar (U+0126)
* iogonek (U+012F)
* Iogonek (U+012E)
* Scedilla (U+015E)
* Uogonek (U+0172)
* hbar (U+0127)
* oslash (U+00F8)
* Lslash (U+0141)
* uni0163 (U+0163)
* Aogonek (U+0104)
* Eogonek (U+0118) [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į̀
* į̃
* į̌
* į́
* į̂
* į̄The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̆
* į̒
* į̋
* į̈
* į̇
* į̊ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - f (U+0066): X=251.5,Y=708 (should be at cap-height 710?)
* - germandbls (U+00DF): X=235,Y=-2 (should be at baseline 0?)
* - t (U+0074): X=517,Y=-2 (should be at baseline 0?)
* - tbar (U+0167): X=517,Y=-2 (should be at baseline 0?)
* - tcaron (U+0165): X=517,Y=-2 (should be at baseline 0?)
* - uni0163 (U+0163): X=517,Y=-2 (should be at baseline 0?)
* - uni021B (U+021B): X=517,Y=-2 (should be at baseline 0?)
* - fi (U+FB01): X=136,Y=708 (should be at cap-height 710?)
* - fl (U+FB02): X=138,Y=708 (should be at cap-height 710?)
* - seven.dnom: X=206,Y=1 (should be at baseline 0?)
* - seven.dnom: X=305,Y=1 (should be at baseline 0?)
* - one.numr: X=310,Y=711 (should be at cap-height 710?)
* - one.numr: X=398,Y=711 (should be at cap-height 710?)
* - four.numr: X=267,Y=711 (should be at cap-height 710?)
* - four.numr: X=366,Y=711 (should be at cap-height 710?)
* - five.numr: X=183,Y=711 (should be at cap-height 710?)
* - five.numr: X=416,Y=711 (should be at cap-height 710?)
* - six.numr: X=275,Y=711 (should be at cap-height 710?)
* - six.numr: X=382,Y=711 (should be at cap-height 710?)
* - seven.numr: X=165,Y=711 (should be at cap-height 710?)
* - seven.numr: X=440,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=137,Y=711 (should be at cap-height 710?)
* - onehalf (U+00BD): X=225,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=137,Y=711 (should be at cap-height 710?)
* - uni2153 (U+2153): X=225,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=137,Y=711 (should be at cap-height 710?)
* - onequarter (U+00BC): X=225,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=137,Y=711 (should be at cap-height 710?)
* - uni2155 (U+2155): X=225,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=137,Y=711 (should be at cap-height 710?)
* - oneeighth (U+215B): X=225,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=38,Y=711 (should be at cap-height 710?)
* - fiveeighths (U+215D): X=271,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=17,Y=711 (should be at cap-height 710?)
* - seveneighths (U+215E): X=292,Y=711 (should be at cap-height 710?)
* - uni2085 (U+2085): X=162,Y=2 (should be at baseline 0?)
* - uni2085 (U+2085): X=258,Y=2 (should be at baseline 0?)
* - questiondown (U+00BF): X=75,Y=1 (should be at baseline 0?)
* - dollar (U+0024): X=258,Y=2 (should be at baseline 0?)
* - Euro (U+20AC): X=555,Y=709 (should be at cap-height 710?)
* - Euro (U+20AC): X=555,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - uni25CF (U+25CF): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?)
* - circle (U+25CB): X=303,Y=1 (should be at baseline 0?) [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (247.0, 354.0) to (237.0, 570.0) is colinear with segment from (237.0, 570.0) to (237.0, 710.0)
* uniA78B (U+A78B): from (369.0, 710.0) to (369.0, 570.0) is colinear with segment from (369.0, 570.0) to (359.0, 354.0)
* uniA78C (U+A78C): from (247.0, 390.0) to (237.0, 606.0) is colinear with segment from (237.0, 606.0) to (237.0, 746.0)
* uniA78C (U+A78C): from (369.0, 746.0) to (369.0, 606.0) is colinear with segment from (369.0, 606.0) to (359.0, 390.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* M (U+004D): Line(Line { p0: (435.0, 0.0), p1: (454.0, 555.0) })/Line(Line { p0: (454.0, 555.0), p1: (347.0, 170.0) }) = 13.57107484945054 degrees
* M (U+004D): Line(Line { p0: (258.0, 170.0), p1: (151.0, 555.0) })/Line(Line { p0: (151.0, 555.0), p1: (170.0, 0.0) }) = 13.57107484945054 degrees
* W (U+0057): Line(Line { p0: (143.0, 710.0), p1: (183.0, 154.0) })/Line(Line { p0: (183.0, 154.0), p1: (247.0, 544.0) }) = 13.43423048959679 degrees
* W (U+0057): Line(Line { p0: (358.0, 544.0), p1: (422.0, 155.0) })/Line(Line { p0: (422.0, 155.0), p1: (462.0, 710.0) }) = 13.465154430814774 degrees
* Wacute (U+1E82): Line(Line { p0: (143.0, 710.0), p1: (183.0, 154.0) })/Line(Line { p0: (183.0, 154.0), p1: (247.0, 544.0) }) = 13.43423048959679 degrees
* Wacute (U+1E82): Line(Line { p0: (358.0, 544.0), p1: (422.0, 155.0) })/Line(Line { p0: (422.0, 155.0), p1: (462.0, 710.0) }) = 13.465154430814774 degrees
* Wcircumflex (U+0174): Line(Line { p0: (143.0, 710.0), p1: (183.0, 154.0) })/Line(Line { p0: (183.0, 154.0), p1: (247.0, 544.0) }) = 13.43423048959679 degrees
* Wcircumflex (U+0174): Line(Line { p0: (358.0, 544.0), p1: (422.0, 155.0) })/Line(Line { p0: (422.0, 155.0), p1: (462.0, 710.0) }) = 13.465154430814774 degrees
* Wdieresis (U+1E84): Line(Line { p0: (143.0, 710.0), p1: (183.0, 154.0) })/Line(Line { p0: (183.0, 154.0), p1: (247.0, 544.0) }) = 13.43423048959679 degrees
* Wdieresis (U+1E84): Line(Line { p0: (358.0, 544.0), p1: (422.0, 155.0) })/Line(Line { p0: (422.0, 155.0), p1: (462.0, 710.0) }) = 13.465154430814774 degrees
* Wgrave (U+1E80): Line(Line { p0: (143.0, 710.0), p1: (183.0, 154.0) })/Line(Line { p0: (183.0, 154.0), p1: (247.0, 544.0) }) = 13.43423048959679 degrees
* Wgrave (U+1E80): Line(Line { p0: (358.0, 544.0), p1: (422.0, 155.0) })/Line(Line { p0: (422.0, 155.0), p1: (462.0, 710.0) }) = 13.465154430814774 degrees
* uni2465 (U+2465): Line(Line { p0: (270.0, 388.0), p1: (268.0, 386.0) })/Quad(QuadBez { p0: (268.0, 386.0), p1: (278.0, 395.0), p2: (294.0, 402.5) }) = 3.0127875041834073 degrees
* six.dnom: Line(Line { p0: (270.0, 216.0), p1: (268.0, 214.0) })/Quad(QuadBez { p0: (268.0, 214.0), p1: (278.0, 223.0), p2: (294.0, 230.5) }) = 3.0127875041834073 degrees
* nine.dnom: Line(Line { p0: (336.0, 157.0), p1: (338.0, 159.0) })/Quad(QuadBez { p0: (338.0, 159.0), p1: (328.0, 150.0), p2: (312.0, 142.5) }) = 3.0127875041834073 degrees
* six.numr: Line(Line { p0: (270.0, 554.0), p1: (268.0, 552.0) })/Quad(QuadBez { p0: (268.0, 552.0), p1: (278.0, 561.0), p2: (294.0, 568.5) }) = 3.0127875041834073 degrees
* nine.numr: Line(Line { p0: (336.0, 495.0), p1: (338.0, 497.0) })/Quad(QuadBez { p0: (338.0, 497.0), p1: (328.0, 488.0), p2: (312.0, 480.5) }) = 3.0127875041834073 degrees
* uni2086 (U+2086): Line(Line { p0: (270.0, 110.0), p1: (268.0, 108.0) })/Quad(QuadBez { p0: (268.0, 108.0), p1: (278.0, 117.0), p2: (294.0, 124.5) }) = 3.0127875041834073 degrees
* uni2089 (U+2089): Line(Line { p0: (336.0, 51.0), p1: (338.0, 53.0) })/Quad(QuadBez { p0: (338.0, 53.0), p1: (328.0, 44.0), p2: (312.0, 36.5) }) = 3.0127875041834073 degrees
* uni2076 (U+2076): Line(Line { p0: (270.0, 590.0), p1: (268.0, 588.0) })/Quad(QuadBez { p0: (268.0, 588.0), p1: (278.0, 597.0), p2: (294.0, 604.5) }) = 3.0127875041834073 degrees
* uni2116 (U+2116): Line(Line { p0: (133.0, 710.0), p1: (212.0, 328.0) })/Line(Line { p0: (212.0, 328.0), p1: (212.0, 710.0) }) = 11.684409360743015 degrees
* uni2116 (U+2116): Line(Line { p0: (210.0, 0.0), p1: (131.0, 385.0) })/Line(Line { p0: (131.0, 385.0), p1: (131.0, 0.0) }) = 11.59583718439696 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* uni2197 (U+2197): Line(Line { p0: (394.0, 512.0), p1: (157.0, 511.0) }) (angle: -179.76 degrees, expected: -180.00 degrees)
* uni2197 (U+2197): Line(Line { p0: (471.0, 197.0), p1: (472.0, 438.0) }) (angle: 89.76 degrees, expected: 90.00 degrees)
* uni2198 (U+2198): Line(Line { p0: (471.0, 272.0), p1: (470.0, 509.0) }) (angle: 90.24 degrees, expected: 90.00 degrees)
* uni2198 (U+2198): Line(Line { p0: (156.0, 195.0), p1: (397.0, 194.0) }) (angle: -0.24 degrees, expected: 0.00 degrees)
* uni2199 (U+2199): Line(Line { p0: (136.0, 509.0), p1: (135.0, 272.0) }) (angle: -90.24 degrees, expected: -90.00 degrees)
* uni2199 (U+2199): Line(Line { p0: (209.0, 194.0), p1: (450.0, 195.0) }) (angle: 0.24 degrees, expected: 0.00 degrees)
* uni2196 (U+2196): Line(Line { p0: (134.0, 438.0), p1: (135.0, 197.0) }) (angle: -89.76 degrees, expected: -90.00 degrees)
* uni2196 (U+2196): Line(Line { p0: (449.0, 511.0), p1: (212.0, 512.0) }) (angle: 179.76 degrees, expected: 180.00 degrees)
* uni21E7 (U+21E7): Line(Line { p0: (457.0, 272.0), p1: (456.0, 72.0) }) (angle: -90.29 degrees, expected: -90.00 degrees)
* bar_greater.liga: Line(Line { p0: (-336.0, -54.0), p1: (-337.0, 764.0) }) (angle: 90.07 degrees, expected: 90.00 degrees)
* less_bar.liga: Line(Line { p0: (337.0, 764.0), p1: (336.0, -54.0) }) (angle: -90.07 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* Eng (U+014A) contains a short segment Line(Line { p0: (403.0, 0.0), p1: (381.0, 0.0) }) (length: 22.00, total outline: 4457.72)
* zero.zero contains a short segment Line(Line { p0: (185.0, 342.0), p1: (185.0, 342.0) }) (length: 0.00, total outline: 755.07)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (462.5, 203.5), p1: (469.0, 193.0), p2: (484.0, 193.0) }) (length: 25.09, total outline: 5227.23)
* at (U+0040) contains a short segment Quad(QuadBez { p0: (484.0, 193.0), p1: (495.0, 193.0), p2: (503.5, 205.0) }) (length: 23.85, total outline: 5227.23)
* uni20B1 (U+20B1) contains a short segment Quad(QuadBez { p0: (521.0, 443.0), p1: (521.0, 436.0), p2: (521.0, 429.0) }) (length: 14.00, total outline: 2584.44)
* equal_less_less.liga contains a short segment Line(Line { p0: (82.0, 391.0), p1: (82.0, 390.0) }) (length: 1.00, total outline: 3096.77)
* greater_greater_equal.liga contains a short segment Line(Line { p0: (-688.0, 390.0), p1: (-688.0, 391.0) }) (length: 1.00, total outline: 3096.77)
* uni2303 (U+2303) contains a short segment Line(Line { p0: (300.0, 673.0), p1: (306.0, 673.0) }) (length: 6.00, total outline: 1518.79)
* Q.BRACKET.varAlt01 contains a short segment Line(Line { p0: (386.0, 165.0), p1: (388.0, 160.0) }) (length: 5.39, total outline: 1270.12) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>


<details><summary>[15] fonts/terminal/DesignaliMonoTerm-Light.ttf</summary>
<div>


<details>
    <summary>⚠️ <b>WARN</b> Check that OS/2 fsSelection WWS bit is set correctly. (opentype/fsselection_wws)</summary>
    <div>








- ⚠️ **WARN** OS/2 fsSelection WWS bit is not set, and the font does not have name IDs 21/22 (WWS Family/Subfamily). If the font's naming is WWS-conformant, the WWS bit should be set. [code: no-wws-without-wws-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking correctness of monospaced metadata. (opentype/monospace)</summary>
    <div>








- ⚠️ **WARN** The OpenType spec recommends at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 594 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron (alt_caron)</summary>
    <div>








- ⚠️ **WARN** dcaron is decomposed and therefore could not be checked. Please check manually. [code: decomposed-outline]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* blackCircled
* Q.BRACKET.varAlt01 [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Glyph names are all valid? (valid_glyphnames)</summary>
    <div>








- ⚠️ **WARN** The following glyph names are too long: "asciitilde_asciitilde_greater.liga" [code: legacy-long-names]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure font has overlaps bit set correctly. (overlaps_bit)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlaps but the overlaps bit is not set:
* dcroat (U+0111)
* Scedilla (U+015E)
* uni0162 (U+0162)
* Aogonek (U+0104)
* Hbar (U+0126)
* hbar (U+0127)
* iogonek (U+012F)
* Lslash (U+0141)
* uni0163 (U+0163)
* lslash (U+0142)
* Ccedilla (U+00C7)
* Dcroat (U+0110)
* Eth (U+00D0)
* Uogonek (U+0172)
* Iogonek (U+012E)
* oslash (U+00F8)
* Oslash (U+00D8)
* Eogonek (U+0118)
* aogonek (U+0105)
* ccedilla (U+00E7)
* scedilla (U+015F)
* uogonek (U+0173)
* Tbar (U+0166)
* aogonek.cv01 [code: no-overlaps-bit]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages              |
|-------------------------------------------------------------------|------------------------|
| Auxiliary orthography codepoints:                                 | * en_Latn (English)    |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ʻ |                        |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)     |
|   The following auxiliary characters are missing from the font: Ǔ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
|   The following auxiliary characters are missing from the font: ǔ |                        |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)     |
|   The following auxiliary characters are missing from the font: Ǿ |                        |
|   The following auxiliary characters are missing from the font: ǿ |                        |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)     |
|   The following auxiliary characters are missing from the font: Ĕ |                        |
|   The following auxiliary characters are missing from the font: Ĭ |                        |
|   The following auxiliary characters are missing from the font: Ŏ |                        |
|   The following auxiliary characters are missing from the font: ĕ |                        |
|   The following auxiliary characters are missing from the font: ĭ |                        |
|   The following auxiliary characters are missing from the font: ŏ |                        |
|   The following auxiliary characters are missing from the font: ſ |                        |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)    |
|   The following auxiliary characters are missing from the font: Ĕ | * cs_Latn (Czech)      |
|   The following auxiliary characters are missing from the font: Ĭ | * cy_Latn (Welsh)      |
|   The following auxiliary characters are missing from the font: Ŏ | * es_Latn (Spanish)    |
|   The following auxiliary characters are missing from the font: ĕ | * hu_Latn (Hungarian)  |
|   The following auxiliary characters are missing from the font: ĭ | * pt_Latn (Portuguese) |
|   The following auxiliary characters are missing from the font: ŏ | * sk_Latn (Slovak)     |
|                                                                   | * tr_Latn (Turkish)    |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)    |
|   The following auxiliary characters are missing from the font: Ȟ |                        |
|   The following auxiliary characters are missing from the font: Ʒ |                        |
|   The following auxiliary characters are missing from the font: Ǯ |                        |
|   The following auxiliary characters are missing from the font: ȟ |                        |
|   The following auxiliary characters are missing from the font: ʒ |                        |
|   The following auxiliary characters are missing from the font: ǯ |                        | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings:

* į́
* į̃
* į̄
* į̀
* į̂
* į̌The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̇
* į̈
* į̆
* į̋
* į̒
* į̊ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? (outline_colinear_vectors)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have colinear vectors:

* uniA78B (U+A78B): from (276.0, 369.0) to (268.0, 577.0) is colinear with segment from (268.0, 577.0) to (268.0, 710.0)
* uniA78B (U+A78B): from (338.0, 710.0) to (338.0, 577.0) is colinear with segment from (338.0, 577.0) to (330.0, 369.0)
* uniA78C (U+A78C): from (276.0, 405.0) to (268.0, 613.0) is colinear with segment from (268.0, 613.0) to (268.0, 746.0)
* uniA78C (U+A78C): from (338.0, 746.0) to (338.0, 613.0) is colinear with segment from (338.0, 613.0) to (330.0, 405.0) [code: found-colinear-vectors]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? (outline_jaggy_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have jaggy segments:

* m (U+006D): Line(Line { p0: (320.0, 421.0), p1: (320.0, 419.0) })/Quad(QuadBez { p0: (320.0, 419.0), p1: (332.0, 467.0), p2: (363.0, 494.0) }) = 14.036243467926457 degrees
* six (U+0036): Quad(QuadBez { p0: (196.0, 419.0), p1: (178.0, 391.0), p2: (170.0, 373.0) })/Quad(QuadBez { p0: (170.0, 373.0), p1: (182.0, 389.0), p2: (203.0, 406.5) }) = 12.90740867126579 degrees
* nine (U+0039): Quad(QuadBez { p0: (410.0, 291.0), p1: (428.0, 319.0), p2: (436.0, 337.0) })/Quad(QuadBez { p0: (436.0, 337.0), p1: (424.0, 321.0), p2: (403.0, 303.5) }) = 12.90740867126579 degrees
* trademark (U+2122): Line(Line { p0: (419.0, 408.0), p1: (361.0, 640.0) })/Line(Line { p0: (361.0, 640.0), p1: (361.0, 374.0) }) = 14.036243467926484 degrees
* uni2116 (U+2116): Line(Line { p0: (126.0, 710.0), p1: (245.0, 146.0) })/Line(Line { p0: (245.0, 146.0), p1: (245.0, 710.0) }) = 11.914254794319415 degrees
* uni2116 (U+2116): Line(Line { p0: (228.0, 0.0), p1: (109.0, 563.0) })/Line(Line { p0: (109.0, 563.0), p1: (109.0, 0.0) }) = 11.934810541560223 degrees [code: found-jaggy-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? (outline_semi_vertical)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

* M (U+004D): Line(Line { p0: (484.0, 0.0), p1: (485.0, 622.0) }) (angle: 89.91 degrees, expected: 90.00 degrees)
* M (U+004D): Line(Line { p0: (120.0, 622.0), p1: (121.0, 0.0) }) (angle: -89.91 degrees, expected: -90.00 degrees)
* uni2198 (U+2198): Line(Line { p0: (506.0, 204.0), p1: (505.0, 518.0) }) (angle: 90.18 degrees, expected: 90.00 degrees)
* uni2199 (U+2199): Line(Line { p0: (101.0, 518.0), p1: (100.0, 204.0) }) (angle: -90.18 degrees, expected: -90.00 degrees) [code: found-semi-vertical]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? (outline_short_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have short segments:

* Eng (U+014A) contains a short segment Line(Line { p0: (454.0, 0.0), p1: (429.0, 0.0) }) (length: 25.00, total outline: 4967.90)
* uni0E3F (U+0E3F) contains a short segment Line(Line { p0: (310.0, 332.0), p1: (310.0, 332.0) }) (length: 0.00, total outline: 721.23)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-1112.0, 67.0), p1: (-1112.0, 125.0) }) (length: 58.00, total outline: 11046.10)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-1112.0, 275.0), p1: (-1112.0, 333.0) }) (length: 58.00, total outline: 11046.10)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-1112.0, 483.0), p1: (-1112.0, 541.0) }) (length: 58.00, total outline: 11046.10)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-198.0, 685.0), p1: (-133.0, 685.0) }) (length: 65.00, total outline: 11046.10)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (506.0, 541.0), p1: (506.0, 483.0) }) (length: 58.00, total outline: 11046.10)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (506.0, 333.0), p1: (506.0, 275.0) }) (length: 58.00, total outline: 11046.10)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (506.0, 125.0), p1: (506.0, 67.0) }) (length: 58.00, total outline: 11046.10)
* exclam_equal_equal.liga contains a short segment Line(Line { p0: (-408.0, -77.0), p1: (-473.0, -77.0) }) (length: 65.00, total outline: 11046.10)
* equal_less_less.liga contains a short segment Line(Line { p0: (138.0, 415.0), p1: (138.0, 414.0) }) (length: 1.00, total outline: 3150.18)
* greater_greater_equal.liga contains a short segment Line(Line { p0: (-744.0, 414.0), p1: (-744.0, 415.0) }) (length: 1.00, total outline: 3150.18)
* uni2303 (U+2303) contains a short segment Line(Line { p0: (300.0, 673.0), p1: (306.0, 673.0) }) (length: 6.00, total outline: 1573.30) [code: found-short-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'DSAL' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>


</div>
</details>






### Summary

| ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|
| 144 | 106 | 682 | 486 | 
| 10% | 7% | 48% | 34% | 



