# CSS Specificity and Inheritance Bug

This repository demonstrates a subtle bug related to CSS specificity and inheritance. The issue involves unexpected behavior when applying styles to nested elements.  The `div p` selector doesn't override the `div` selector as expected, even though it should have higher specificity.

**Bug Description:**
The provided CSS code snippet exhibits unusual inheritance behavior where the style set for `div p` selector is ignored.

**How to Reproduce:**
1. Create an HTML file with a `div` containing a `<p>` element.
2. Link the `bug.css` stylesheet to the HTML file.
3. Observe that the paragraph text is blue instead of green.

**Solution:**
The solution involves understanding how CSS specificity works, and ensuring correct rule application. The fix provided ensures proper style inheritance while demonstrating clear use of specificity. 

**Note:** This isn't necessarily a bug in the CSS engine itself, but rather a misunderstanding of its specificity rules.  Understanding CSS specificity is crucial for predictable styling.