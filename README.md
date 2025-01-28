# CSS Specificity Bug

This repository demonstrates a common yet subtle bug related to CSS selector specificity.  The bug arises from the unexpected behavior of CSS selectors when dealing with nested elements and specificity.

## Bug Description

The provided CSS has conflicting styles for the `<p>` element. Due to selector specificity rules, the style applied might not be the expected one, depending on the context of the `<p>` element in the HTML.

## Bug Solution

The solution involves carefully considering specificity and using more specific selectors or the `!important` flag (although the latter should generally be avoided) to ensure intended styling.