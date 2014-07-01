# ENSIME

[![Bountysource](https://www.bountysource.com/badge/tracker?tracker_id=239449)](https://www.bountysource.com/trackers/239449-ensime?utm_source=239449&utm_medium=shield&utm_campaign=TRACKER_BADGE)
[![Build Status](https://travis-ci.org/ensime/ensime-server.svg?branch=master)](https://travis-ci.org/ensime/ensime-server)
[![Stories in Ready](https://badge.waffle.io/ensime/ensime-server.png?label=Low+Hanging+Fruit)](https://waffle.io/ensime/ensime-server)
<!--
[![Coverage Status](https://coveralls.io/repos/bountysource/frontend/badge.png)](https://coveralls.io/r/ensime/ensime-server)
-->


ENhanced Scala Interaction Mode for text Editors
--- especially [GNU Emacs](http://www.gnu.org/software/emacs/).

ENSIME brings IDE-like features to your favourite text editor, such as:

- Show the `type` of the symbol under the cursor.
- Contextual completion for `var`s, `val`s and `def`s.
- Add an import for the symbol under the cursor.
- Fast classpath search (types and members).
- Jump to source code or documentation.
- Browse packages and type hierarchies.
- Find all references to a symbol.
- Refactorings (rename, organize imports, extract method).
- REPL with stack trace highlighting.
- Errors and warnings in your code: *red squigglies*.
- Debugging

and many more.


# Contributions

This project is actively community maintained, and we are very pleased
to see contributions from new members.

If you use this software you are already well placed, as a Scala
developer, to make it even better.

You can help out by:

<!--* [Triaging our open tickets](http://codetriage.com/ensime/ensime-server)-->

* [Pick up some low hanging fruit](https://github.com/ensime/ensime-server/issues?labels=Low+Hanging+Fruit)
* [Fixing a bug](http://github.com/ensime/ensime-server/issues?labels=Bug)
* [Helping with the current Milestone](http://github.com/ensime/ensime-server/issues/milestones)
* Sending an unsolicited pull request with a new feature
* Having a conversation on the [ENSIME Google Group](https://groups.google.com/forum/#!forum/ensime)
* Telling your co-workers!

We are using some great technologies to automate our build and testing process:

* Kanban project planning from [waffle.io](https://waffle.io/ensime/ensime-server)
* Continuous Integration from [travis-ci.org](https://travis-ci.org/ensime/ensime-server)
* ~~Coverage reports from coveralls.io~~ [#473](http://github.com/ensime/ensime-server/issues/473)
* Binary distribution from [sonatype.org](http://www.sonatype.org/)
* Emacs distributions from [MELPA](http://melpa.milkbox.net/#/ensime)

Along with unit testing, we have automated coverage checks and code
formatting as part of our build process. Pull requests will only be
accepted if the build and tests are successful, and coverage has not
decreased. Pull requests must be reviewed and should not be merged
by the person who created the request (except for trivial changes
and hotfixes).

We have branches for older versions of scala, which are merged regularly.


# Quick Start

There are a two ways to install the ENSIME server:

1. Install [ensime-emacs](http://github.com/ensime/ensime-emacs) and it will do it for you automatically.
2. Build from source: fork this repo, clone locally and `sbt publishLocal`.

The latter is also the recommended approach when developing ENSIME itself.


## Further Information

Most of the server documentation is in the code itself. A readable
version of the SWANK protocol is documented in the
[ENSIME User Manual](http://ensime.github.io/) (although best to always check the
code.)

[Older releases](https://www.dropbox.com/sh/ryd981hq08swyqr/V9o9rDvxkS/ENSIME%20Releases)
are bundled with the emacs plugin.
