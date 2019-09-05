## Fontbakery report

Fontbakery version: 0.7.11

<details>
<summary><b>[9] Gupter-Bold.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Checking OS/2 fsType.</summary>

* [com.google.fonts/check/fstype](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype)
* 🔥 **FAIL** OS/2 fsType is a legacy DRM-related field.
In this font it is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.
Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application.

More detailed info is available at:
https://docs.microsoft.com/en-us/typography/opentype/spec/os2#fstype [code: drm]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Check glyph coverage.</summary>

* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)
* 🔥 **FAIL** Missing required codepoints: 0x00AA (FEMININE ORDINAL INDICATOR), 0x00B2 (SUPERSCRIPT TWO), 0x00B3 (SUPERSCRIPT THREE), 0x00B5 (MICRO SIGN), 0x00B9 (SUPERSCRIPT ONE), 0x00BA (MASCULINE ORDINAL INDICATOR), 0x2074 (SUPERSCRIPT FOUR) and 0x2215 (DIVISION SLASH) [code: missing-codepoints]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"https://github.com/octaviopardo/GUPTER" [code: bad-notice-format]
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"https://github.com/octaviopardo/GUPTER" [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts.</summary>

* [com.google.fonts/check/integer_ppem_if_hinted](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted)
* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command.

# create virtualenvpython3 -m venv venv
# activate virtualenvsource venv/bin/activate
# install gftoolspip install git+https://www.github.com/googlefonts/tools [code: bad-flags]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (1000) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uni200C	Contours detected: 1	Expected: 0
Glyph name: uni200D	Contours detected: 1	Expected: 0
Glyph name: g	Contours detected: 4	Expected: 2 or 3
Glyph name: uni0904	Contours detected: 3	Expected: 1
Glyph name: uni0905	Contours detected: 2	Expected: 1
Glyph name: uni0906	Contours detected: 2	Expected: 1
Glyph name: uni090E	Contours detected: 2	Expected: 1
Glyph name: uni0910	Contours detected: 2	Expected: 1
Glyph name: uni0911	Contours detected: 3	Expected: 2
Glyph name: uni0912	Contours detected: 3	Expected: 1
Glyph name: uni0913	Contours detected: 3	Expected: 1
Glyph name: uni0914	Contours detected: 2	Expected: 1
Glyph name: uni091A	Contours detected: 2	Expected: 1
Glyph name: uni0925	Contours detected: 2	Expected: 1
Glyph name: uni0927	Contours detected: 2	Expected: 1
Glyph name: uni092D	Contours detected: 2	Expected: 1
Glyph name: uni0933	Contours detected: 1	Expected: 3
Glyph name: uni0934	Contours detected: 2	Expected: 4
Glyph name: uni0936	Contours detected: 3	Expected: 2
Glyph name: uni093B	Contours detected: 2	Expected: 1
Glyph name: uni094A	Contours detected: 2	Expected: 1
Glyph name: uni094B	Contours detected: 2	Expected: 1
Glyph name: uni094C	Contours detected: 3	Expected: 1
Glyph name: uni0948	Contours detected: 2	Expected: 1
Glyph name: uni0967	Contours detected: 2	Expected: 1
Glyph name: uni0972	Contours detected: 3	Expected: 2
Glyph name: uni0973	Contours detected: 3	Expected: 1
Glyph name: uni0974	Contours detected: 3	Expected: 1
Glyph name: uni0975	Contours detected: 2	Expected: 1
Glyph name: uni0976	Contours detected: 3	Expected: 2
Glyph name: uni0977	Contours detected: 4	Expected: 3
Glyph name: uni097B	Contours detected: 2	Expected: 1
Glyph name: uni097C	Contours detected: 2	Expected: 1
Glyph name: uni097F	Contours detected: 4	Expected: 3 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary>

* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)
* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary>

* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)
* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- i + f
	- f + l
	- l + f
	- i + l

   [code: lacks-kern-info]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps.</summary>

* [com.google.fonts/check/linegaps](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps)
* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]

</details>
<br>
</details>
<details>
<summary><b>[9] Gupter-Medium.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Checking OS/2 fsType.</summary>

* [com.google.fonts/check/fstype](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype)
* 🔥 **FAIL** OS/2 fsType is a legacy DRM-related field.
In this font it is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.
Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application.

More detailed info is available at:
https://docs.microsoft.com/en-us/typography/opentype/spec/os2#fstype [code: drm]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Check glyph coverage.</summary>

* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)
* 🔥 **FAIL** Missing required codepoints: 0x00AA (FEMININE ORDINAL INDICATOR), 0x00B2 (SUPERSCRIPT TWO), 0x00B3 (SUPERSCRIPT THREE), 0x00B5 (MICRO SIGN), 0x00B9 (SUPERSCRIPT ONE), 0x00BA (MASCULINE ORDINAL INDICATOR), 0x2074 (SUPERSCRIPT FOUR) and 0x2215 (DIVISION SLASH) [code: missing-codepoints]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"https://github.com/octaviopardo/GUPTER" [code: bad-notice-format]
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"https://github.com/octaviopardo/GUPTER" [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts.</summary>

* [com.google.fonts/check/integer_ppem_if_hinted](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted)
* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command.

# create virtualenvpython3 -m venv venv
# activate virtualenvsource venv/bin/activate
# install gftoolspip install git+https://www.github.com/googlefonts/tools [code: bad-flags]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (1000) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uni200C	Contours detected: 1	Expected: 0
Glyph name: uni200D	Contours detected: 1	Expected: 0
Glyph name: colon	Contours detected: 1	Expected: 2
Glyph name: divide	Contours detected: 1	Expected: 3
Glyph name: uni0904	Contours detected: 3	Expected: 1
Glyph name: uni0905	Contours detected: 2	Expected: 1
Glyph name: uni0906	Contours detected: 2	Expected: 1
Glyph name: uni090E	Contours detected: 2	Expected: 1
Glyph name: uni0910	Contours detected: 2	Expected: 1
Glyph name: uni0911	Contours detected: 3	Expected: 2
Glyph name: uni0912	Contours detected: 3	Expected: 1
Glyph name: uni0913	Contours detected: 3	Expected: 1
Glyph name: uni0914	Contours detected: 2	Expected: 1
Glyph name: uni091A	Contours detected: 2	Expected: 1
Glyph name: uni0925	Contours detected: 2	Expected: 1
Glyph name: uni0927	Contours detected: 2	Expected: 1
Glyph name: uni092D	Contours detected: 2	Expected: 1
Glyph name: uni0933	Contours detected: 1	Expected: 3
Glyph name: uni0934	Contours detected: 2	Expected: 4
Glyph name: uni0936	Contours detected: 3	Expected: 2
Glyph name: uni093B	Contours detected: 2	Expected: 1
Glyph name: uni094A	Contours detected: 2	Expected: 1
Glyph name: uni094B	Contours detected: 2	Expected: 1
Glyph name: uni094C	Contours detected: 3	Expected: 1
Glyph name: uni0948	Contours detected: 2	Expected: 1
Glyph name: uni0967	Contours detected: 2	Expected: 1
Glyph name: uni0972	Contours detected: 3	Expected: 2
Glyph name: uni0973	Contours detected: 3	Expected: 1
Glyph name: uni0974	Contours detected: 3	Expected: 1
Glyph name: uni0975	Contours detected: 2	Expected: 1
Glyph name: uni0976	Contours detected: 3	Expected: 2
Glyph name: uni0977	Contours detected: 4	Expected: 3
Glyph name: uni097B	Contours detected: 2	Expected: 1
Glyph name: uni097C	Contours detected: 2	Expected: 1
Glyph name: uni097F	Contours detected: 4	Expected: 3 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary>

* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)
* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary>

* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)
* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- i + f
	- f + l
	- l + f
	- i + l

   [code: lacks-kern-info]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps.</summary>

* [com.google.fonts/check/linegaps](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps)
* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]

</details>
<br>
</details>
<details>
<summary><b>[9] Gupter-Regular.ttf</b></summary>
<details>
<summary>🔥 <b>FAIL:</b> Checking OS/2 fsType.</summary>

* [com.google.fonts/check/fstype](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype)
* 🔥 **FAIL** OS/2 fsType is a legacy DRM-related field.
In this font it is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.
Fonts with this setting indicate that they may be embedded and permanently installed on the remote system by an application.

More detailed info is available at:
https://docs.microsoft.com/en-us/typography/opentype/spec/os2#fstype [code: drm]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Check glyph coverage.</summary>

* [com.google.fonts/check/glyph_coverage](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage)
* 🔥 **FAIL** Missing required codepoints: 0x00AA (FEMININE ORDINAL INDICATOR), 0x00B2 (SUPERSCRIPT TWO), 0x00B3 (SUPERSCRIPT THREE), 0x00B5 (MICRO SIGN), 0x00B9 (SUPERSCRIPT ONE), 0x00BA (MASCULINE ORDINAL INDICATOR), 0x2074 (SUPERSCRIPT FOUR) and 0x2215 (DIVISION SLASH) [code: missing-codepoints]

</details>
<details>
<summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts</summary>

* [com.google.fonts/check/font_copyright](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright)
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"https://github.com/octaviopardo/GUPTER" [code: bad-notice-format]
* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"https://github.com/octaviopardo/GUPTER" [code: bad-notice-format]

</details>
<details>
<summary>🔥 <b>FAIL:</b> PPEM must be an integer on hinted fonts.</summary>

* [com.google.fonts/check/integer_ppem_if_hinted](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/integer_ppem_if_hinted)
* 🔥 **FAIL** This is a hinted font, so it must have bit 3 set on the flags of the head table, so that PPEM values will be rounded into an integer value.

This can be accomplished by using the 'gftools fix-hinting' command.

# create virtualenvpython3 -m venv venv
# activate virtualenvsource venv/bin/activate
# install gftoolspip install git+https://www.github.com/googlefonts/tools [code: bad-flags]

</details>
<details>
<summary>⚠ <b>WARN:</b> Stricter unitsPerEm criteria for Google Fonts. </summary>

* [com.google.fonts/check/unitsperem_strict](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict)
* ⚠ **WARN** Even though unitsPerEm (1000) in this font is reasonable. It is strongly advised to consider changing it to 2000, since it will likely improve the quality of Variable Fonts by avoiding excessive rounding of coordinates on interpolations. [code: legacy-value]

</details>
<details>
<summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours.</summary>

* [com.google.fonts/check/contour_count](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/contour_count)
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

Glyph name: uni200C	Contours detected: 1	Expected: 0
Glyph name: uni200D	Contours detected: 1	Expected: 0
Glyph name: uni0904	Contours detected: 3	Expected: 1
Glyph name: uni0905	Contours detected: 2	Expected: 1
Glyph name: uni0906	Contours detected: 2	Expected: 1
Glyph name: uni090E	Contours detected: 2	Expected: 1
Glyph name: uni0910	Contours detected: 2	Expected: 1
Glyph name: uni0911	Contours detected: 3	Expected: 2
Glyph name: uni0912	Contours detected: 3	Expected: 1
Glyph name: uni0913	Contours detected: 3	Expected: 1
Glyph name: uni0914	Contours detected: 2	Expected: 1
Glyph name: uni091A	Contours detected: 2	Expected: 1
Glyph name: uni0925	Contours detected: 2	Expected: 1
Glyph name: uni0927	Contours detected: 2	Expected: 1
Glyph name: uni092D	Contours detected: 2	Expected: 1
Glyph name: uni0933	Contours detected: 1	Expected: 3
Glyph name: uni0934	Contours detected: 2	Expected: 4
Glyph name: uni0936	Contours detected: 3	Expected: 2
Glyph name: uni093B	Contours detected: 2	Expected: 1
Glyph name: uni094A	Contours detected: 2	Expected: 1
Glyph name: uni094B	Contours detected: 2	Expected: 1
Glyph name: uni094C	Contours detected: 3	Expected: 1
Glyph name: uni0948	Contours detected: 2	Expected: 1
Glyph name: uni0967	Contours detected: 2	Expected: 1
Glyph name: uni0972	Contours detected: 3	Expected: 2
Glyph name: uni0973	Contours detected: 3	Expected: 1
Glyph name: uni0974	Contours detected: 3	Expected: 1
Glyph name: uni0975	Contours detected: 2	Expected: 1
Glyph name: uni0976	Contours detected: 3	Expected: 2
Glyph name: uni0977	Contours detected: 4	Expected: 3
Glyph name: uni097B	Contours detected: 2	Expected: 1
Glyph name: uni097C	Contours detected: 2	Expected: 1
Glyph name: uni097F	Contours detected: 4	Expected: 3 [code: contour-count]

</details>
<details>
<summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature?</summary>

* [com.google.fonts/check/ligature_carets](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets)
* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]

</details>
<details>
<summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences?</summary>

* [com.google.fonts/check/kerning_for_non_ligated_sequences](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences)
* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- i + f
	- f + l
	- l + f
	- i + l

   [code: lacks-kern-info]

</details>
<details>
<summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps.</summary>

* [com.google.fonts/check/linegaps](https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps)
* ⚠ **WARN** hhea lineGap is not equal to 0. [code: hhea]

</details>
<br>
</details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS |
|:-----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 12 | 15 | 180 | 19 | 198 |
| 0% | 3% | 4% | 42% | 4% | 47% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
