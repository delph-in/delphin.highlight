# delphin.highlight

This module provides [Pygments][] [lexers](http://pygments.org/lexers)
for the following [DELPH-IN][] formats:

* [TDL][] -- Type Description Language
* [SimpleMRS][] -- A popular serialization format for Minimal
  Recursion Semantics

In addition, a Pygments [style](http://pygments.org/docs/styles/) for
MRS is available which helps highlight the interesting information in
SimpleMRS.

# Examples

The SimpleMRS style is meant for console output, and works with both
dark and light backgrounds:

![SimpleMRS on a dark background](images/mrs-dark.png)

![SimpleMRS on a light background](images/mrs-light.png)

The TDL lexer is used for [PyDelphin][]'s [Sphinx][]-based documentation:

![TDL highlighting from PyDelphin's documentation](images/tdl.png)


# Installation and Requirements

This module only depends on Pygments version 2.3.1 or higher.

# Usage

While you can drop in the lexers into Pygments-capable applications
like wikis or documentation sites, the console highlighting of
SimpleMRS is provided by the [PyDelphin][] package via the `delphin
convert` command.


[DELPH-IN]: http://www.delph-in.net
[Pygments]: http://pygments.org
[PyDelphin]: https://github.com/delph-in/pydelphin
[SimpleMRS]: http://moin.delph-in.net/MrsRfc
[Sphinx]: http://www.sphinx-doc.org/
[TDL]: http://moin.delph-in.net/TdlRfc
