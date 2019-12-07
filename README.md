[![Unix Build Status][travis-image]][travis-link]
[![Package Control Downloads][pc-image]][pc-link]
![License][license-image]
# BracketHighlighter
Bracket Highlighter matches a variety of brackets such as: `[]`, `()`, `{}`, `""`, `''`, `<tag></tag>`, and even custom brackets.

This was originally forked from pyparadigm's _SublimeBrackets_ and _SublimeTagmatcher_ (both are no longer available).  I forked this to fix some issues I had and to add some features I had wanted.  I also wanted to improve the efficiency of the matching.

Moving forward, I have thrown away all of the code and have completely rewritten the entire code base to allow for a more flexibility, faster, and more feature rich experience.

![screenshot](docs/src/markdown/images/Example1.png)

# Feature List
- Customizable to highlight almost any bracket.
- Customizable bracket highlight style.
- High visibility bracket highlight mode.
- Selectively disable or enable specific matching of tags, brackets, or quotes.
- Selectively whitelist or blacklist matching of specific tags, brackets, or quotes based on language.
- When bound to a shortcut, allow option to show line count and char count between match in the status bar.
- Highlight basic brackets within strings.
- Works with multi-select.
- Configurable custom gutter icons.
- Toggle bracket escape mode for string brackets (regex|string).
- Bracket plugins that can jump between bracket ends, select content, remove brackets and/or content, wrap selections with brackets, swap brackets, swap quotes (handling quote escaping between the main quotes), fold/unfold content between brackets, toggle through tag attribute selection, select both the opening and closing tag name to change both simultaneously.

# Documentation
https://eatbreathecode.github.io/sublime_bracket_highlighter/

# License

This work is licensed under the [The MIT License](LICENSE).

[travis-image]: https://img.shields.io/travis/facelessuser/BracketHighlighter/master.svg
[travis-link]: https://travis-ci.org/facelessuser/BracketHighlighter
[pc-image]: https://img.shields.io/packagecontrol/dt/BracketHighlighter.svg?logo=sublime%20text&logoColor=cccccc
[pc-link]: https://packagecontrol.io/packages/BracketHighlighter
[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
