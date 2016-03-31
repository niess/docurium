# Docurium fork

This is a fork of [libgit2/docurium](https://github.com/libgit2/docurium), a lightweight Doxygen replacement. The `new-style` branch implements a modified template. The main modifications of the new template, with respect to the classic Docurium, are:

+ Similar styles for structures and functions.
+ Markdown support for arguments and struct members comments.
+ Generalised referencing and hyperlinks.
+ A modifed style sheet for examples and hyperlinks to types and callbacks as well.
+ The possibility to generate the docs in a subfolder instead of at the root of the project, for integration in another website.

You can check how the modified template looks over [here](http://niess.github.io/pumas).

# Installation

Clone this repository, `git clone https://github.com/niess/docurium.git`. You will need Pygments to be installed for code highlighting to work properly. Some additional dependencies might be needed though (?) Installing the base Docurium should get them if so.

# Usage

As for the base Docurium, but call explicitly the `bin/cm` script from this cloned fork, and pass it your Docurium config file.

    $ (..)/docurium/bin/cm doc api.docurium

# License

MIT, see LICENCE file
