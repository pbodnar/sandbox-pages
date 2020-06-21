# Sandbox Pages site

Hello World!

...

# Footnotes

See https://kramdown.gettalong.org/syntax.html#footnotes

This requires setting this in _\_config.yml_ for GitHub pages:

    markdown: kramdown

Naturally, the following example doesn't work with GitHub's markdown implementation (which is hard-coded for previews of markdown files), as even after 5 years since [github/markup#498](https://github.com/github/markup/issues/498) was created, GitHub authors seem to refuse this for unexplained reasons...

## Example

This is some text.[^1] Other text.[^footnote]

[^1]: Some *crazy* footnote definition.

[^footnote]:
    > Blockquotes can be in a footnote.

        as well as code blocks

    or, naturally, simple paragraphs.
