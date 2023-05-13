---
layout: default
title: IG Book
---

## IG Parser

IG Parser is a tool that parses institutional statements in the IG Script notation, which allows for the machine-accessible parsing of institutional information in the form of the Institutional Grammar (both the original version, as well as IG 2.0). The underlying syntax has been introduced as part of the [IG Book](book-content.md), with specific examples of encoded institutional statements referenced throughout Chapters 7 and 8 of the book provided under [Book Examples](book-examples.md).

<center><a href="https://ig-parser.newinstitutionalgrammar.org/visual/">
<img target="_blank" src="/figures/IG-Parser-UI-Visual.jpg" width="90%">
</a></center>

The current version of IG Parser is available in two versions that both take IG Script as input, but produce different output, selectively focusing on tabular output, as well as a tree output for visual exploration of the parsing outcome based on interactive navigation.

When opening the parser, you will see input fields, the first of which merely takes any original (i.e., unparsed) statement as reference, and a second field that asks for the "Encoded Statement". This field requires IG Script input (a guide is provided by clicking on the "Encoded Statement" label, alongside an extended guidance via the links below). In addition, you can parameterize the output to consider relevant features (e.g., IG Extended output -- to take fine-grained nesting into account; Semantic annotations to include IG Logico annotations in the output).

You can use the following links to access the parser (Note: you can interactively switch between both versions from within the user interface).

* The tabular version (Google Sheets, CSV output (e.g., for Excel processing)) can be found here: 
  * https://ig-parser.newinstitutionalgrammar.org/

* The visual version (tree output format) can be found here: 
  * https://ig-parser.newinstitutionalgrammar.org/visual/


An overview of the IG Script syntax supported by the IG Parser is provided [here](https://github.com/chrfrantz/IG-Parser/blob/main/README.md). The code repository is available on [Github](https://github.com/chrfrantz/IG-Parser).
