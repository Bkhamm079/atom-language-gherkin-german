Gherkin language support in Atom
================================

Provide syntax highlight for gherkin language files (.feature) in Atom for English and German.

Details about Gherkin could be find at https://github.com/cucumber/cucumber/wiki/Gherkin . The following features habe been added compared to the pure Gherkin syntax:

* values in text descriptions could be marked by "[" and "]"
* keyword "Formalisation:" / "Formalisierung:" inside a scenario or scenario outline
  extend the description by a more formal expression, which should be readable by the
  customer. A simple formal description could be an alternative for step definitions.

This project was forked from gigapixel/atom-language-gherkin at GitHub. I added german keywords, added missing english keywords (regarding to cucumber/gherkin), and changed support.class.gherkin to variable.class.gherkin for better visibility. Furthermore, I added the keywords and "Formalisation" and "Formalisierung:" to include more formal example expressions, like OCL, which are easy to understand even by customers.

Copyright
---------

Copyright (c) 2014 by Jan Gottschick, MIT license
