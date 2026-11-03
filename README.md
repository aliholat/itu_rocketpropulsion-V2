# IGNITION v4 — Rocket Propulsion Midterm Study Website

## Only upload `index.html`

This version fixes equations appearing as raw TeX / plain text because a separate math-rendering file was missing, blocked or had not loaded. **All HTML, CSS, lesson content, and the full MathJax equation renderer are inside one file**. There is no vendor folder, CDN dependency for equations, installation, build step, framework, or Python required. The external Google Fonts stylesheet is cosmetic only; equations render without internet.

1. Delete the previous website files in your GitHub repository.
2. Upload **only `index.html`** to the root of the repository.
3. Commit changes and keep Settings → Pages → Deploy from a branch → main / (root).
4. Hard refresh your live site (`Ctrl+Shift+R` on Windows), or try a private window if you still see the cached old version.

You can also double-click `index.html` locally to view the website **offline**.

## Lecturer notation

The default 69-equation bank is transcribed from lecture slides 02 and 03: k, A_t, A_y, p_1, p_2, p_3, I_s, etc. Alternative symbols are in a separate tab. Detailed derivations, graphs, calculator, test, schematic and flashcards remain intact.

## License

MathJax licensed under the Apache License 2.0; see `MATHJAX_LICENSE.txt`. This bundled math engine ships only within `index.html`; license notice retained as this file in the ZIP. Other course content written independently as study material.
