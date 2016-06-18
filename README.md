# The Conjured Codewars Codex [![Build Status](https://travis-ci.org/bkaestner/codewars-rules.svg?branch=master)](https://travis-ci.org/bkaestner/codewars-rules) [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/bkaestner/codewars-rules?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge) [![Maintainer needed](https://img.shields.io/badge/maintainer-needed-%23f00.svg)](https://github.com/bkaestner/codewars-rules/issues/41)

These documents contains some rules I've employed for my katas and my
translations on [Codewars]. Some of them are very simple
(e.g same arguments, same order), others are sometimes really hard to fulfill
(random tests). But only rules aren't interesting. This document contains also
some tips, so that you (or I) can implement them.

All documents are written in Markdown so that you can easily view them on GitHub
(see the rules directory).

If you find an error, have a better idea, or think that all of this is a pile of
unicorn misery, feel free to create an issue or a pull-request. Have a look at
the LICENCE before contributing (it's CC-BY-SA 4.0).

 [Codewars]: http://www.codewars.com

# Online versions
Since all of the files are written in Markdown, you can simply browse the
`rules` directory. However, there are some things that cannot get shown on
GitHub, such as included TeX math commands.

There's a [hosted version on GitHub](https://bkaestner.github.io/codewars-rules/).
However, that version gets updated by hand, so it might lag a little bit. You
can build a version with `make html` on your own.

# Offline versions

Clone the repository and use `make`. You need to install a recent version
of [pandoc]. However, since I'm using Travis to check that this really works,
I'm also releasing an automatically generated PDF from time to time, check the
releases.

 [pandoc]: http://pandoc.org/
