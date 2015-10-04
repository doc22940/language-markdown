<!-- Issues -->

<!-- https://github.com/burodepeper/language-markdown/issues/17 -->
A line with *italics* and **bold** fails.
Even _mixing_ the **type** of *markers* is __not enough__.

<!-- https://github.com/atom/language-gfm/issues/117 -->
<!-- expected outcome: only emphasize first letters of words -->
*f*oo *b*ar baz
**f**oo **b**ar baz
<!-- expected outcome: ignore single underscores -->
Blah blah _ blah
blah blah blah foo bar
fooooo _ oh hi

<!-- http://spec.commonmark.org/0.22/#emphasis-and-strong-emphasis -->

<!-- http://spec.commonmark.org/0.22/#example-313 -->
*foo bar*

<!-- http://spec.commonmark.org/0.22/#example-314 -->
a * foo bar*

<!-- http://spec.commonmark.org/0.22/#example-315 -->
a*"foo"*

<!-- http://spec.commonmark.org/0.22/#example-316 -->
* a *
<!-- NOTE: non-breaking white space, therefor not a list -->

<!-- http://spec.commonmark.org/0.22/#example-317 -->
foo*bar*

<!-- http://spec.commonmark.org/0.22/#example-318 -->
5*6*78

<!-- http://spec.commonmark.org/0.22/#example-319 -->
_foo bar_

<!-- http://spec.commonmark.org/0.22/#example-320 -->
_ foo bar_

<!-- http://spec.commonmark.org/0.22/#example-321 -->
a_"foo"_

<!-- http://spec.commonmark.org/0.22/#example-322 -->
foo_bar_

<!-- http://spec.commonmark.org/0.22/#example-323 -->
5_6_78

<!-- http://spec.commonmark.org/0.22/#example-324 -->
пристаням_стремятся_

<!-- http://spec.commonmark.org/0.22/#example-325 -->
aa_"bb"_cc

<!-- http://spec.commonmark.org/0.22/#example-326 -->
foo-_(bar)_

<!-- http://spec.commonmark.org/0.22/#example-327 -->
_foo*

<!-- http://spec.commonmark.org/0.22/#example-328 -->
*foo bar *

<!-- http://spec.commonmark.org/0.22/#example-329 -->
*foo bar
*

<!-- http://spec.commonmark.org/0.22/#example-330 -->
*(*foo)

<!-- http://spec.commonmark.org/0.22/#example-331 -->
*(*foo*)*

<!-- http://spec.commonmark.org/0.22/#example-332 -->
foo*bar*
5*6*78
*foo*bar

<!-- http://spec.commonmark.org/0.22/#example-333 -->
_foo bar _

<!-- http://spec.commonmark.org/0.22/#example-334 -->
_(_foo)

<!-- http://spec.commonmark.org/0.22/#example-335 -->
_(_foo_)_

<!-- http://spec.commonmark.org/0.22/#example-336 -->
_foo_bar

<!-- http://spec.commonmark.org/0.22/#example-337 -->
_пристаням_стремятся

<!-- http://spec.commonmark.org/0.22/#example-338 -->
_foo_bar_baz_

<!-- http://spec.commonmark.org/0.22/#example-339 -->
_(bar)_.

<!-- http://spec.commonmark.org/0.22/#example-340 -->
**foo bar**

<!-- http://spec.commonmark.org/0.22/#example-341 -->
** foo bar**

<!-- http://spec.commonmark.org/0.22/#example-342 -->
a**"foo"**

<!-- http://spec.commonmark.org/0.22/#example-343 -->
foo**bar**

<!-- http://spec.commonmark.org/0.22/#example-344 -->
__foo bar__

<!-- http://spec.commonmark.org/0.22/#example-345 -->
__ foo bar__

<!-- http://spec.commonmark.org/0.22/#example-346 -->
__
foo bar__

<!-- http://spec.commonmark.org/0.22/#example-347 -->
a__"foo"__

<!-- http://spec.commonmark.org/0.22/#example-348 -->
foo__bar__

<!-- http://spec.commonmark.org/0.22/#example-349 -->
5__6__78

<!-- http://spec.commonmark.org/0.22/#example-350 -->
пристаням__стремятся__

<!-- http://spec.commonmark.org/0.22/#example-351 -->
__foo, __bar__, baz__

<!-- http://spec.commonmark.org/0.22/#example-352 -->
foo-__(bar)__

<!-- http://spec.commonmark.org/0.22/#example-353 -->
**foo bar **

<!-- http://spec.commonmark.org/0.22/#example-354 -->
**(**foo)

<!-- http://spec.commonmark.org/0.22/#example-355 -->
*(**foo**)*

<!-- http://spec.commonmark.org/0.22/#example-356 -->
**Gomphocarpus (*Gomphocarpus physocarpus*, syn.
*Asclepias physocarpa*)**

__Gomphocarpus (_Gomphocarpus physocarpus_, syn.
_Asclepias physocarpa_)__

**Gomphocarpus (_Gomphocarpus physocarpus_, syn.
_Asclepias physocarpa_)**

**Gomphocarpus (_Gomphocarpus physocarpus_, syn. _Asclepias physocarpa_)**

<!-- http://spec.commonmark.org/0.22/#example-357 -->
**foo "*bar*" foo**

<!-- http://spec.commonmark.org/0.22/#example-358 -->
**foo**bar

<!-- http://spec.commonmark.org/0.22/#example-359 -->
__foo bar __

<!-- http://spec.commonmark.org/0.22/#example-360 -->
__(__foo)

<!-- http://spec.commonmark.org/0.22/#example-361 -->
_(__foo__)_

<!-- http://spec.commonmark.org/0.22/#example-362 -->
__foo__bar

<!-- http://spec.commonmark.org/0.22/#example-363 -->
__пристаням__стремятся

<!-- http://spec.commonmark.org/0.22/#example-364 -->
__foo__bar__baz__

<!-- http://spec.commonmark.org/0.22/#example-365 -->
__(bar)__.

<!-- http://spec.commonmark.org/0.22/#example-366 -->
*foo [bar](/url)*

<!-- http://spec.commonmark.org/0.22/#example-367 -->
*foo
bar*

<!-- http://spec.commonmark.org/0.22/#example-368 -->
_foo __bar__ baz_

<!-- http://spec.commonmark.org/0.22/#example-369 -->
_foo _bar_ baz_

<!-- http://spec.commonmark.org/0.22/#example-370 -->
__foo_ bar_

<!-- http://spec.commonmark.org/0.22/#example-371 -->
*foo *bar**

<!-- http://spec.commonmark.org/0.22/#example-372 -->
*foo **bar** baz*

<!-- http://spec.commonmark.org/0.22/#example-373 -->
*foo**bar**baz*

<!-- http://spec.commonmark.org/0.22/#example-374 -->
***foo** bar*

<!-- http://spec.commonmark.org/0.22/#example-375 -->
*foo **bar***

<!-- http://spec.commonmark.org/0.22/#example-376 -->
*foo**bar***

<!-- http://spec.commonmark.org/0.22/#example-377 -->
*foo **bar *baz* bim** bop*

<!-- http://spec.commonmark.org/0.22/#example-378 -->
*foo [*bar*](/url)*

<!-- http://spec.commonmark.org/0.22/#example-379 -->
** is not an empty emphasis

<!-- http://spec.commonmark.org/0.22/#example-380 -->
**** is not an empty strong emphasis

<!-- http://spec.commonmark.org/0.22/#example-381 -->
**foo [bar](/url)**

<!-- http://spec.commonmark.org/0.22/#example-382 -->
**foo
bar**

<!-- http://spec.commonmark.org/0.22/#example-383 -->
__foo _bar_ baz__

<!-- http://spec.commonmark.org/0.22/#example-384 -->
__foo __bar__ baz__

<!-- http://spec.commonmark.org/0.22/#example-385 -->
____foo__ bar__

<!-- http://spec.commonmark.org/0.22/#example-386 -->
**foo **bar****

<!-- http://spec.commonmark.org/0.22/#example-387 -->
**foo *bar* baz**

<!-- http://spec.commonmark.org/0.22/#example-388 -->
**foo*bar*baz**

<!-- http://spec.commonmark.org/0.22/#example-389 -->
***foo* bar**

<!-- http://spec.commonmark.org/0.22/#example-390 -->
**foo *bar***

<!-- http://spec.commonmark.org/0.22/#example-391 -->
**foo *bar **baz**
bim* bop**

<!-- http://spec.commonmark.org/0.22/#example-392 -->
**foo [*bar*](/url)**

<!-- http://spec.commonmark.org/0.22/#example-393 -->
__ is not an empty emphasis

<!-- http://spec.commonmark.org/0.22/#example-394 -->
____ is not an empty strong emphasis

<!-- http://spec.commonmark.org/0.22/#example-395 -->
foo ***

<!-- http://spec.commonmark.org/0.22/#example-396 -->
foo *\**

<!-- http://spec.commonmark.org/0.22/#example-397 -->
foo *_*

<!-- http://spec.commonmark.org/0.22/#example-398 -->
foo *****

<!-- http://spec.commonmark.org/0.22/#example-399 -->
foo **\***

<!-- http://spec.commonmark.org/0.22/#example-400 -->
foo **_**

<!-- http://spec.commonmark.org/0.22/#example-401 -->
**foo*

<!-- http://spec.commonmark.org/0.22/#example-402 -->
*foo**

<!-- http://spec.commonmark.org/0.22/#example-403 -->
***foo**

<!-- http://spec.commonmark.org/0.22/#example-404 -->
****foo*

<!-- http://spec.commonmark.org/0.22/#example-405 -->
**foo***

<!-- http://spec.commonmark.org/0.22/#example-406 -->
*foo****

<!-- http://spec.commonmark.org/0.22/#example-407 -->
foo ___

<!-- http://spec.commonmark.org/0.22/#example-408 -->
foo _\__

<!-- http://spec.commonmark.org/0.22/#example-409 -->
foo _*_

<!-- http://spec.commonmark.org/0.22/#example-410 -->
foo _____

<!-- http://spec.commonmark.org/0.22/#example-411 -->
foo __\___

<!-- http://spec.commonmark.org/0.22/#example-412 -->
foo __*__

<!-- http://spec.commonmark.org/0.22/#example-413 -->
__foo_

<!-- http://spec.commonmark.org/0.22/#example-414 -->
_foo__

<!-- http://spec.commonmark.org/0.22/#example-415 -->
___foo__

<!-- http://spec.commonmark.org/0.22/#example-416 -->
____foo_

<!-- http://spec.commonmark.org/0.22/#example-417 -->
__foo___

<!-- http://spec.commonmark.org/0.22/#example-418 -->
_foo____

<!-- http://spec.commonmark.org/0.22/#example-419 -->
**foo**

<!-- http://spec.commonmark.org/0.22/#example-420 -->
*_foo_*

<!-- http://spec.commonmark.org/0.22/#example-421 -->
__foo__

<!-- http://spec.commonmark.org/0.22/#example-422 -->
_*foo*_

<!-- http://spec.commonmark.org/0.22/#example-423 -->
****foo****

<!-- http://spec.commonmark.org/0.22/#example-424 -->
____foo____

<!-- http://spec.commonmark.org/0.22/#example-425 -->
******foo******

<!-- http://spec.commonmark.org/0.22/#example-426 -->
***foo***

<!-- http://spec.commonmark.org/0.22/#example-427 -->
_____foo_____

<!-- http://spec.commonmark.org/0.22/#example-428 -->
*foo _bar* baz_

<!-- http://spec.commonmark.org/0.22/#example-429 -->
**foo*bar**

<!-- http://spec.commonmark.org/0.22/#example-430 -->
*foo __bar *baz bim__ bam*

<!-- http://spec.commonmark.org/0.22/#example-431 -->
**foo **bar baz**

<!-- http://spec.commonmark.org/0.22/#example-432 -->
*foo *bar baz*

<!-- http://spec.commonmark.org/0.22/#example-433 -->
*[bar*](/url)

<!-- http://spec.commonmark.org/0.22/#example-434 -->
_foo [bar_](/url)

<!-- http://spec.commonmark.org/0.22/#example-435 -->
*<img src="foo" title="*"/>

<!-- http://spec.commonmark.org/0.22/#example-436 -->
**<a href="**">

<!-- http://spec.commonmark.org/0.22/#example-437 -->
__<a href="__">

<!-- http://spec.commonmark.org/0.22/#example-438 -->
*a `*`*

<!-- http://spec.commonmark.org/0.22/#example-439 -->
_a `_`_

<!-- http://spec.commonmark.org/0.22/#example-440 -->
**a<http://foo.bar/?q=**>

<!-- http://spec.commonmark.org/0.22/#example-441 -->
__a<http://foo.bar/?q=__>