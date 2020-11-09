# BracketHighlighter
[![Latest Release](https://img.shields.io/github/tag/CodeByZach/sublime_bracket_highlighter.svg?label=version)](https://github.com/CodeByZach/sublime_bracket_highlighter/releases)
[![Build][github-ci-image]][github-ci-link]
[![Package Control][pc-image]][pc-link]
[![License][license-image]][license-link]

Bracket Highlighter matches a variety of brackets such as: `[]`, `()`, `{}`, `""`, `''`, `<tag></tag>`, and even custom brackets.

This was originally forked from pyparadigm's _SublimeBrackets_ and _SublimeTagmatcher_ (both are no longer available).  I forked this to fix some issues I had and to add some features I had wanted.  I also wanted to improve the efficiency of the matching.

Moving forward, I have thrown away all of the code and have completely rewritten the entire code base to allow for a more flexibility, faster, and more feature rich experience.

![screenshot](docs/src/markdown/images/Example1.png)

# Feature List

- Customizable to highlight almost any bracket.
- Customizable bracket highlight style.
- High visibility bracket highlight mode.
- Selectively disable or enable specific matching of tags, brackets, or quotes.
- Selectively use an allowlist or blocklist for matching specific tags, brackets, or quotes based on language.
- When bound to a shortcut, allow option to show line count and char count between match in the status bar.
- Highlight basic brackets within strings.
- Works with multi-select.
- Configurable custom gutter icons.
- Toggle bracket escape mode for string brackets (regex|string).
- Bracket plugins that can jump between bracket ends, select content, remove brackets and/or content, wrap selections with brackets, swap brackets, swap quotes (handling quote escaping between the main quotes), fold/unfold content between brackets, toggle through tag attribute selection, select both the opening and closing tag name to change both simultaneously.

# Documentation

https://codebyzach.github.io/sublime_bracket_highlighter/

# License

This work is licensed under the [The MIT License](LICENSE).

[github-ci-image]: https://github.com/CodeByZach/sublime_bracket_highlighter/workflows/build/badge.svg?branch=master&event=push
[github-ci-link]: https://github.com/CodeByZach/sublime_bracket_highlighter/actions?query=workflow%3Abuild+branch%3Amaster
[pc-image]: https://img.shields.io/packagecontrol/dt/BracketHighlighter.svg?labelColor=333333&logo=sublime%20text
[pc-link]: https://packagecontrol.io/packages/BracketHighlighter
[license-image]: https://img.shields.io/badge/license-MIT-blue.svg?labelColor=333333
[license-link]: LICENSE
