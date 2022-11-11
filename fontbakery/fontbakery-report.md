## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[10] Voltaire-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 1.0070037841796875 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 673, but got 570 instead. [code: descent]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* m
	* adieresis
	* h
	* Ecircumflex
	* Y
	* acircumflex
	* ampersand
	* r
	* oacute
	* Lslash and 111 more.

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
	- zero.lf
	- nine.lf
	- .null
	- eight.lf
	- three.lf
	- two.lf
	- one.lf
	- five.lf
	- newGlyph
	- seven.lf 
	- And 3 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: Eth	Contours detected: 3	Expected: 2
	- Glyph name: oslash	Contours detected: 2	Expected: 3
	- Glyph name: dcroat	Contours detected: 3	Expected: 2
	- Glyph name: hbar	Contours detected: 2	Expected: 1
	- Glyph name: Lslash	Contours detected: 2	Expected: 1
	- Glyph name: lslash	Contours detected: 2	Expected: 1
	- Glyph name: Tbar	Contours detected: 2	Expected: 1
	- Glyph name: tbar	Contours detected: 2	Expected: 1
	- Glyph name: Uogonek	Contours detected: 2	Expected: 1
	- Glyph name: uni0180	Contours detected: 3	Expected: 2 
	- And 56 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:
	* five (U+0035) contains a short segment L<<185.0,728.0>--<183.0,726.0>>
	* G (U+0047) contains a short segment L<<869.0,643.0>--<868.0,643.0>>
	* M (U+004D) contains a short segment L<<156.0,1612.0>--<199.0,1612.0>>
	* M (U+004D) contains a short segment L<<1053.0,1612.0>--<1096.0,1612.0>>
	* M (U+004D) contains a short segment L<<627.0,431.0>--<627.0,429.0>>
	* M (U+004D) contains a short segment L<<627.0,429.0>--<626.0,430.0>>
	* M (U+004D) contains a short segment L<<626.0,430.0>--<626.0,431.0>>
	* N (U+004E) contains a short segment L<<156.0,1612.0>--<181.0,1612.0>>
	* N (U+004E) contains a short segment L<<963.0,0.0>--<939.0,0.0>>
	* V (U+0056) contains a short segment L<<491.0,-30.0>--<463.0,-30.0>> and 53 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Amacron (U+0100): L<<235.0,1701.0>--<236.0,1859.0>>
 * Amacron (U+0100): L<<718.0,1859.0>--<719.0,1701.0>>
 * Aogonek (U+0104): L<<951.0,-365.0>--<950.0,-506.0>>
 * Bmacronbelow (U+1E06): L<<204.0,-287.0>--<205.0,-129.0>>
 * Bmacronbelow (U+1E06): L<<687.0,-129.0>--<688.0,-287.0>>
 * Dmacronbelow (U+1E0E): L<<286.0,-457.0>--<287.0,-299.0>>
 * Dmacronbelow (U+1E0E): L<<769.0,-299.0>--<770.0,-457.0>>
 * Emacron (U+0112): L<<188.0,1701.0>--<189.0,1859.0>>
 * Emacron (U+0112): L<<671.0,1859.0>--<672.0,1701.0>>
 * Eogonek (U+0118): L<<704.0,-365.0>--<703.0,-506.0>> and 145 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 2 | 8 | 104 | 8 | 103 | 0 |
| 0% | 1% | 4% | 46% | 4% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
