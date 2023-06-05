---
layout: default
title: IG Book
---

# IG Parser Article Examples

This page lists IG Script-encoded institutional statements examples used as part of the IG Parser article submitted to the journal SoftwareX. 

At this stage, this page is dedicated to reviewers who wish to explore the statements in the IG Parser. Below, please find all statements necoded as part of the article manuscript, with corresponding links that prepopulate the parser. By default, the links with open the visual output version of the parser. You can interactively switch between visual and tabular output by clicking on the `Switch to tabular version of IG Parser` link in the UI. While switching between the different UIs all statement information is retained. After clicking on `Generate visual output` (for the visual output version) and `Generate tabular output` (for the tabular output version) respectively, you will see the corresponding output generated at the bottom. For tabular output, you can copy the CSV or Google Sheets output (using the corresponding button) and paste it into Excel (using the Text-to-Column feature with pipe (`|`) as delimiter) or into Google Sheets respectively (it will automatically parse the individual columns into the spreadsheet structure). 

UI Parameters relevant to see specific features exemplified in the statements are highlighted alongside the link for the corresponding example. 

More details about the supported IG Script features is provided in the [IG Parser Readme](https://github.com/chrfrantz/IG-Parser/blob/main/README.md). To explore more complex examples beyond the ones displayed below, please consider testing the various example statements provided in the IG Parser UI. 

<!--For an accessible introduction to IG Script (beyond the introduction in the manuscript), please refer to the [IG 2.0 Codebook](https://arxiv.org/abs/2008.08937). -->

## Examples in IG Script Section

```Cac(If officer observes or is made aware of violation), A(officer) D(must) I(fine and report) Bdir(violator) to Bind(authority).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20officer%20observes%20or%20is%20made%20aware%20of%20violation,%20officer%20must%20fine%20and%20report%20violator%20to%20authority.&codedStmt=Cac(If%20officer%20observes%20or%20is%20made%20aware%20of%20violation),%20A(officer)%20D(must)%20I(fine%20and%20report)%20Bdir(violator)%20to%20Bind(authority).)




```Cac(If officer observes or is made aware of violation), A(officer) D(must) I(fine [AND] report) Bdir(violator) to Bind(authority).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20officer%20observes%20or%20is%20made%20aware%20of%20violation,%20officer%20must%20fine%20and%20report%20violator%20to%20authority.&codedStmt=Cac(If%20officer%20observes%20or%20is%20made%20aware%20of%20violation),%20A(officer)%20D(must)%20I(fine%20[AND]%20report)%20Bdir(violator)%20to%20Bind(authority).)




```Cac{If A(officer) I(observes [XOR] is made aware of) Bdir(violation)}}, A(officer) D(must) I(fine [AND] report) Bdir(violator) to Bind(authority).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20officer%20observes%20or%20is%20made%20aware%20of%20violation,%20officer%20must%20fine%20and%20report%20violator%20to%20authority.&codedStmt=Cac{If%20A(officer)%20I(observes%20[OR]%20is%20made%20aware%20of)%20Bdir(violation)},%20A(officer)%20D(must)%20I(fine%20[AND]%20report)%20Bdir(violator)%20to%20Bind(authority).)

* Note: When generating tabular output, ensure to select `Produce IG Extended output` in order to see the decomposed nested structure in the output.




```Cac{Cac{If A(officer) I(observes [XOR] is made aware of) Bdir(violation)} [AND] Cac{if A(officer) I(deems) Bdir(intervention) Cex(safe)}}, A(officer) D(must) I(fine [AND] report) Bdir(violator) to Bind(authority).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20an%20officer%20observes%20or%20is%20made%20aware%20of%20a%20violation%20and%20if%20the%20officer%20deems%20intervention,%20the%20officer%20must%20fine%20and%20report%20the%20violator%20to%20authority.&codedStmt=Cac{Cac{If%20A(officer)%20I(observes%20[XOR]%20is%20made%20aware%20of)%20Bdir(violation)}%20[AND]%20Cac{if%20A(officer)%20I(deems)%20Bdir(intervention)%20Cex(safe)}},%20A(officer)%20D(must)%20I(fine%20[AND]%20report)%20Bdir(violator)%20to%20Bind(authority).)

* Note: When generating tabular output, ensure to select `Produce IG Extended output` in order to see the decomposed nested structure in the output.




```Cac{Cac{If A(officer) I(observes [XOR] is made aware of) Bdir(violation)} [AND] Cac{if A(officer) I(deems) Bdir(intervention) Cex(safe)}}, A(officer) D(must) {I(fine) Bdir(violator) [AND] I(file) Bdir(report) with Bind(district court)}```


[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20an%20officer%20observes%20or%20is%20made%20aware%20of%20a%20violation%20and%20if%20the%20officer%20deems%20intervention,%20the%20officer%20must%20fine%20the%20violator%20and%20file%20report%20with%20the%20district%20court.&codedStmt=Cac{Cac{If%20A(officer)%20I(observes%20[XOR]%20is%20made%20aware%20of)%20Bdir(violation)}%20[AND]%20Cac{if%20A(officer)%20I(deems)%20Bdir(intervention)%20Cex(safe)}},%20A(officer)%20D(must)%20{I(fine)%20Bdir(violator)%20[AND]%20I(file)%20Bdir(report)%20with%20Bind(district%20court)})

* Note: When generating tabular output, ensure to select `Produce IG Extended output` in order to see the decomposed nested structure in the output.




```Cac{Cac[condition=violation]{If A[role=enforcer](officer) I(observes [XOR] is made aware of) Bdir(violation)} [AND] Cac[condition=safety]{if A[role=enforcer](officer) I(deems) Bdir(intervention) Cex(safe)}}, A[role=enforcer](officer) D[stringency=high](must) {I[act=sanction](fine) Bdir(violator) [AND] I[act=report](file) Bdir(report) with Bind[act=authority](district court)}```


[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20an%20officer%20observes%20or%20is%20made%20aware%20of%20a%20violation%20and%20if%20the%20officer%20deems%20intervention,%20the%20officer%20must%20fine%20the%20violator%20and%20file%20report%20with%20district%20court.&codedStmt=Cac{Cac[condition=violation]{If%20A[role=enforcer](officer)%20I(observes%20[XOR]%20is%20made%20aware%20of)%20Bdir(violation)}%20[AND]%20Cac[condition=safety]{if%20A[role=enforcer](officer)%20I(deems)%20Bdir(intervention)%20Cex(safe)}},%20A[role=enforcer](officer)%20D[stringency=high](must)%20{I[act=sanction](fine)%20Bdir(violator)%20[AND]%20I[act=report](file)%20Bdir(report)%20with%20Bind[act=authority](district%20court)})

* Notes 
  * When generating tabular output, ensure to select two features, a) `Produce IG Extended output` in order to see the decomposed nested structure in the output, and b) `Include IG Logico annotations in output` to see additional columns capturing the annotations.
  * When generating visual output, ensure to select `Include IG Logico annotations in output` to see the annotations as part of the generated statement tree (as labels associated with the corresponding nodes).
  
## Illustrative Example

```Cac{Cac[condition=violation]{If A[role=enforcer](officer) I[act=detection](observes [XOR] is made aware of) Bdir(violation)} [AND] Cac[condition=safety]{if A[role=enforcer](officer) I(deems) Bdir(intervention) Cex(safe)}}, A[role=enforcer](officer) D[stringency=high](must) I[act=sanction](fine [AND] report) Bind[role=violator](violator).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20an%20officer%20observes%20or%20is%20made%20aware%20of%20a%20violation%20and%20if%20the%20officer%20deems%20intervention,%20the%20officer%20must%20fine%20and%20report%20violator.&codedStmt=Cac{Cac[condition=violation]{If%20A[role=enforcer](officer)%20I[act=detection](observes%20[XOR]%20is%20made%20aware%20of)%20Bdir(violation)}%20[AND]%20Cac[condition=safety]{if%20A[role=enforcer](officer)%20I(deems)%20Bdir(intervention)%20Cex(safe)}},%20A[role=enforcer](officer)%20D[stringency=high](must)%20I[act=sanction](fine%20[AND]%20report)%20Bind[role=violator](violator).)

* Note: Ensure to select `Include IG Logico annotations in output` to see the annotations as part of the generated statement tree (as labels associated with the corresponding nodes).