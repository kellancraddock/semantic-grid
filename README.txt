/**
* Forked from Tyler Tate's Semantic Grid https://github.com/tylertate/semantic-grid
*
* Author: Kellan Craddock
* Contact: kellancraddock@gmail.com
* Fork Location: https://github.com/kellancraddock/semantic-grid
*
**/

A fork of the Semantic Grid system utalizing the box-sizing rule to normalize container widths. This would allow for padding and borders on the column element, ultimately reducing markup and/or required css rules.

Initial support for modern browsers, IE8+. Will attempt a graceful fallback for browsers that dont support the box-sizing rule.

NOTE 2/3/12 - Grid mixin now uses box-sizing on browsers that support it. New arguments "gutter" and "padding" have been added to handle browsers that do not support box-sizing. Borders are still not factored for.