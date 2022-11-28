## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[7] Voltaire-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* logicalnot
	* ucircumflex
	* Z
	* ampersand
	* atilde
	* six
	* nacute
	* tilde
	* Ntilde
	* percent and 106 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- i + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- zero.tf.zero
	- newGlyph 
	- And .null
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: hbar	Contours detected: 2	Expected: 1
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: lslash	Contours detected: 2	Expected: 1
	- Glyph name: Tbar	Contours detected: 2	Expected: 1
	- Glyph name: tbar	Contours detected: 2	Expected: 1
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0180	Contours detected: 3	Expected: 2
	- Glyph name: uni019A	Contours detected: 2	Expected: 1 
	- And 58 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Amacron (U+0100): L<<235.0,1721.0>--<236.0,1879.0>>
 * Amacron (U+0100): L<<718.0,1879.0>--<719.0,1721.0>>
 * Aogonek (U+0104): L<<951.0,-365.0>--<950.0,-506.0>>
 * Bmacronbelow (U+1E06): L<<194.0,-287.0>--<195.0,-129.0>>
 * Bmacronbelow (U+1E06): L<<677.0,-129.0>--<678.0,-287.0>>
 * Dmacronbelow (U+1E0E): L<<236.0,-287.0>--<237.0,-129.0>>
 * Dmacronbelow (U+1E0E): L<<719.0,-129.0>--<720.0,-287.0>>
 * Emacron (U+0112): L<<178.0,1721.0>--<179.0,1879.0>>
 * Emacron (U+0112): L<<661.0,1879.0>--<662.0,1721.0>>
 * Eng (U+014A): L<<337.0,1299.0>--<336.0,0.0>> and 163 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 7 | 104 | 8 | 106 | 0 |
| 0% | 0% | 3% | 46% | 4% | 47% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
