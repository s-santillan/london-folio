# London-TextFolio (london-folio)

* Fork of "London" theme for more text-heavy portfolios
* Preferred UX navigation is SOLELY project-based as it feels very overwhelming when adding secondary navigation (about/faqs/samples) AND all the project pages

## Departures from original design
* Doesn't use "wide" image widths for galleries (commented out only)
* Doesn't use mobile hamburger or 2ndary navigation
* Uses TOCBOT
* Slightly narrower margins for less scrolling through sections of text
* The original theme prefers using `vw` for element margins/paddings as a quick way to scale up/down based on viewport (mobile/desktop) w/o having to use breakpoints. However this breaks on extra-large, high-resolution screens. I'll be removing the use of vw slowly.
* yt embeds are too small — there seems to be no class defs in css, so i added a custom yt embed class.


# Copyright & License

Copyright (c) 2013-2021 Ghost Foundation - Released under the [MIT license](LICENSE).
