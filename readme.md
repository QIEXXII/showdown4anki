# Showdown4Anki

Showdown4Anki is an Anki template.You can use it to write Markdown directly in Anki.So far,Showdown4Anki is semi-finished.

## Sources

Markdown to HTML convert is implement by [showdownjs/showdown](https://github.com/showdownjs/showdown).

CSS(Github style) is a fork from [github.css](https://gist.github.com/tuzz/3331384).

## Markdown Flavor

What Showdown Options Applied In Showdown4Anki:

```Javascript
showdown.setFlavor('github');
showdown.setOption('tasklists', 'true');
```

This means that these Showdown options are applied:

```plain
omitExtraWLInCodeBlocks:              true,
simplifiedAutoLink:                   true,
excludeTrailingPunctuationFromURLs:   true,
literalMidWordUnderscores:            true,
strikethrough:                        true,
tables:                               true,
tablesHeaderId:                       true,
ghCodeBlocks:                         true,
tasklists:                            true,
disableForced4SpacesIndentedSublists: true,
simpleLineBreaks:                     true,
requireSpaceBeforeHeadingText:        true,
ghCompatibleHeaderId:                 true,
ghMentions:                           true,
backslashEscapesHTMLTags:             true,
emoji:                                true,
splitAdjacentBlockquotes:             true
```

## References

* [Showdown's Markdown syntax](https://github.com/showdownjs/showdown/wiki/Showdown's-Markdown-syntax)
* [Showdown Options](https://github.com/showdownjs/showdown/wiki/Showdown-Options)
* [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/)

## Imperfections

AnkiDroid is not supported!

|       Markdown syntax        | Support? |
| :--------------------------- | :------: |
| Headers                      |    Y     |
| Emphasis                     |    Y     |
| Unordered Lists              |    Y     |
| Nested Unordered Lists       |    N     |
| Ordered Lists                |    Y     |
| Nested Ordered Lists         |    N     |
| Blockquotes                  |    Y     |
| Inline code                  |    Y     |
| Syntax highlighting(GFM)     |    N     |
| Task lists(GFM)              |    Y     |
| Tables(GFM)                  |    Y     |
| Strikethrough(GFM)           |    Y     |
| Ignoring Markdown formatting |    Y     |
