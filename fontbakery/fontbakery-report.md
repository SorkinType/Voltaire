## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[8] Voltaire-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* registered
	* section
	* Rcaron
	* eight
	* ntilde
	* g
	* n
	* two
	* ugrave
	* F and 108 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- two.lf
	- six.lf
	- five.lf
	- eight.lf
	- .null
	- seven.lf
	- zero.lf
	- three.lf
	- nine.lf
	- four.lf 
	- And one.lf
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0
	- Glyph name: oslash	Contours detected: 2	Expected: 3
	- Glyph name: aogonek	Contours detected: 3	Expected: 2
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: Obreve	Contours detected: 2	Expected: 3
	- Glyph name: tcaron	Contours detected: 1	Expected: 2
	- Glyph name: ohorn	Contours detected: 3	Expected: 2
	- Glyph name: Uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uhorn	Contours detected: 2	Expected: 1
	- Glyph name: uni01EA	Contours detected: 3	Expected: 2 
	- And 65 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* aogonek (U+0105): B<<390.5,-142.5>-<438.0,-62.0>-<532.0,-2.0>>/B<<532.0,-2.0>-<483.0,-19.0>-<429.0,-19.0>> = 13.416360286287913
	* aogonek (U+0105): B<<619.0,45.0>-<617.0,44.0>-<615.0,43.0>>/L<<615.0,43.0>--<620.0,45.0>> = 4.763641690726143
	* uni1EA2 (U+1EA2): B<<294.0,2008.0>-<295.0,2008.0>-<300.0,2007.0>>/B<<300.0,2007.0>-<298.0,2007.0>-<298.0,2007.5>> = 11.309932474020195
	* uni1EA2 (U+1EA2): B<<392.0,1697.0>-<389.0,1696.0>-<385.0,1696.0>>/L<<385.0,1696.0>--<392.0,1697.0>> = 8.13010235415596
	* uni1EA8 (U+1EA8): B<<294.0,2435.0>-<295.0,2435.0>-<300.0,2434.0>>/B<<300.0,2434.0>-<298.0,2434.0>-<298.0,2434.5>> = 11.309932474020195
	* uni1EA8 (U+1EA8): B<<392.0,2124.0>-<389.0,2123.0>-<385.0,2123.0>>/L<<385.0,2123.0>--<392.0,2124.0>> = 8.13010235415596
	* uni1EB2 (U+1EB2): B<<294.0,2404.0>-<295.0,2404.0>-<300.0,2403.0>>/B<<300.0,2403.0>-<298.0,2403.0>-<298.0,2403.5>> = 11.309932474020195
	* uni1EB2 (U+1EB2): B<<392.0,2093.0>-<389.0,2092.0>-<385.0,2092.0>>/L<<385.0,2092.0>--<392.0,2093.0>> = 8.13010235415596
	* uni1EBA (U+1EBA): B<<249.0,2008.0>-<250.0,2008.0>-<255.0,2007.0>>/B<<255.0,2007.0>-<253.0,2007.0>-<253.0,2007.5>> = 11.309932474020195
	* uni1EBA (U+1EBA): B<<347.0,1697.0>-<344.0,1696.0>-<340.0,1696.0>>/L<<340.0,1696.0>--<347.0,1697.0>> = 8.13010235415596 and 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Amacron (U+0100): L<<248.0,1701.0>--<249.0,1859.0>>
 * Amacron (U+0100): L<<731.0,1859.0>--<732.0,1701.0>>
 * Aogonek (U+0104): L<<951.0,-365.0>--<950.0,-506.0>>
 * Emacron (U+0112): L<<196.0,1701.0>--<197.0,1859.0>>
 * Emacron (U+0112): L<<679.0,1859.0>--<680.0,1701.0>>
 * Eogonek (U+0118): L<<709.0,-365.0>--<708.0,-506.0>>
 * F (U+0046): L<<178.0,1594.0>--<733.0,1593.0>>
 * Imacron (U+012A): L<<21.0,1701.0>--<22.0,1859.0>>
 * Imacron (U+012A): L<<504.0,1859.0>--<505.0,1701.0>>
 * Iogonek (U+012E): L<<372.0,-365.0>--<371.0,-506.0>> and 124 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 8 | 105 | 8 | 104 | 0 |
| 0% | 0% | 4% | 47% | 4% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
