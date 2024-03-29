---
layout: default
title: IG Book
---

# Book Examples of IG Script-encoded Institutional Statements

This page lists IG Script-encoded institutional statements examples introduced in Chapters [7](./book-examples#ed1ch7) and [8](./book-examples#ed1ch8) of the IG Book. Where currently supported, the examples are augmented with links to the prepopulated version of that statement in the IG Parser. The IG Parser is a currently developed implementation to showcase the computational processing of the encoded information, with specific focus on the transformation of encoded statements into tabular output format for further analytical treatment. Additional features under active development include the calculation of analytical metrics for complex institutional statements (as discussed in Chapter 8 of the book), as well as the visual representation of institutional statements. 

For an accessible introduction to IG Script, beyond the intuitive introduction provided in Chapter 7, please refer to the [IG 2.0 Codebook](https://arxiv.org/abs/2008.08937). 

Please note that clicking on the link listed under each statement example of interest in the book should navigate directly to the corresponding statement on this page.

<br/>

<a name="ed1ch7"></a>
## Chapter 7 Examples

<a name="ed1ch7ex1"></a>
### Chapter 7 Example 1

```A(Actor)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Actor&codedStmt=A(Actor)&stmtId=1)

<a name="ed1ch7ex2"></a>
### Chapter 7 Example 2

```A(Actor) D(must) I(conform) with Bdir(policy) Cac(from 1st January) Cex(under all circumstances)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Actor%20must%20conform%20with%20policy%20from%201st%20January%20under%20all%20circumstances.&codedStmt=A(Actor)%20D(must)%20I(conform)%20with%20Bdir(policy)%20Cac(from%201st%20January)%20Cex(under%20all%20circumstances)&stmtId=1)

<a name="ed1ch7ex3"></a>
### Chapter 7 Example 3

```I(conform) D(must) with Cac(from 1st January) Cex(under all circumstances) Bdir(policy) A(Actor)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Actor%20must%20conform%20with%20policy%20from%201st%20January%20under%20all%20circumstances.&codedStmt=I(conform)%20D(must)%20with%20Cac(from%201st%20January)%20Cex(under%20all%20circumstances)%20Bdir(policy)%20A(Actor)&stmtId=1)

<a name="ed1ch7ex4"></a>
### Chapter 7 Example 4

```A,p(certified) A(operation) ...```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=certified%20operation%20...&codedStmt=A,p(certified)%20A(operation)%20...&stmtId=1)

<a name="ed1ch7ex5"></a>
### Chapter 7 Example 5

```A(Actor) D(must) I((accept [XOR] cede)) Bdir(responsibility)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Actor%20must%20accept%20or%20cede%20responsibility.&codedStmt=A(Actor)%20D(must)%20I((accept%20[XOR]%20cede))%20Bdir(responsibility).&stmtId=1)

<a name="ed1ch7ex6"></a>
### Chapter 7 Example 6

```A(Actor) D(must) I(accept) I(fulfill) Bdir(responsibility)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Actor%20must%20accept%20and%20fulfill%20responsibility.&codedStmt=A(Actor)%20D(must)%20I(accept)%20I(fulfill)%20Bdir(responsibility)&stmtId=1)

<a name="ed1ch7ex7"></a>
### Chapter 7 Example 7

```A(Actor) D(must) I((accept [XOR] cede)) Bdir(responsibility) [NOT]```

<a name="ed1ch7ex8"></a>
### Chapter 7 Example 8

```A(Actor) D(must) I(([NOT] accept [XOR] cede)) Bdir(responsibility)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Actor%20must%20not%20accept%20or%20cede%20responsibility.&codedStmt=A(Actor)%20D(must)%20I(([NOT]%20accept%20[XOR]%20cede))%20Bdir(responsibility).&stmtId=1)

<a name="ed1ch7ex9"></a>
### Chapter 7 Example 9

```{A(Actor) D(must) I(conform) with Bdir(policy)} {E(Policy) F(applies) Cac(from 1st January)}```

<a name="ed1ch7ex10"></a>
### Chapter 7 Example 10

```{ {A(Actor) D(must) I(conform) with Bdir(policy)} [AND] {E(Policy) F(applies) Cac(from 1st January)} }```

<a name="ed1ch7ex11"></a>
### Chapter 7 Example 11

```A(citizen) D(must) I(conform) with Bdir(policy) O{A(official) D(may) I(sanction) Bdir(citizen) Cex(immediately)}.```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=The%20citizen%20must%20conform%20with%20policy%20or%20else%20official%20may%20sanction%20citizen%20immediately.&codedStmt=A(citizen)%20D(must)%20I(conform)%20with%20Bdir(policy)%20O{A(official)%20D(may)%20I(sanction)%20Bdir(citizen)%20Cex(immediately)}.&stmtId=1)

<a name="ed1ch7ex12"></a>
### Chapter 7 Example 12

```E(Policy) F[confunc=lifecycle](applies) Cac[tmp=date](1st January).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=The%20Policy%20applies%20from%201st%20January.&codedStmt=E(Policy)%20F[confunc=lifecycle](applies)%20Cac[tmp=date](1st%20January).&stmtId=1)

<a name="ed1ch7ex13"></a>
### Chapter 7 Example 13

```... Cac[ctx=tmp[initiation,termination]](between June and July) ...```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=...%20between%20June%20and%20July%20...&codedStmt=...%20Cac[ctx=tmp[initiation,termination]](between%20June%20and%20July)%20...&stmtId=1)

<a name="ed1ch7ex14"></a>
### Chapter 7 Example 14

```A[role=experiencer,animacy=animate](Program Manager) ...```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Program%20Manager%20...&codedStmt=A[role=experiencer,animacy=animate](Program%20Manager)%20...&stmtId=1)

<a name="ed1ch7ex15"></a>
### Chapter 7 Example 15

```A(Program Manager) I([sends]) ...```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Program%20Manager%20...&codedStmt=A(Program%20Manager)%20I([sends])%20...&stmtId=1)

<a name="ed1ch7ex16"></a>
### Chapter 7 Example 16

```A A(student) D(may) I(request) an Bdir(Incomplete) Cac(if the student has exceptional circumstances that prevent the student from fulfilling all course requirements on time).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=A%20student%20may%20request%20an%20Incomplete%20if%20the%20student%20has%20exceptional%20circumstances%20that%20prevent%20the%20student%20from%20fulfilling%20all%20course%20requirements%20on%20time.&codedStmt=A%20A(student)%20D(may)%20I(request)%20an%20Bdir(Incomplete)%20Cac(if%20the%20student%20has%20exceptional%20circumstances%20that%20prevent%20the%20student%20from%20fulfilling%20all%20course%20requirements%20on%20time).&stmtId=1)

<a name="ed1ch7ex17"></a>
### Chapter 7 Example 17

```A(Students) D(are expected to) I(attend) Bdir,p(all) Bdir(class sessions) Cac([at all times]) Cex([no constraints]).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Students%20are%20expected%20to%20attend%20all%20class%20sessions.&codedStmt=A(Students)%20D(are%20expected%20to)%20I(attend)%20Bdir,p(all)%20Bdir(class%20sessions)%20Cac([at%20all%20times])%20Cex([no%20constraints]).&stmtId=1)

<a name="ed1ch7ex18"></a>
### Chapter 7 Example 18

```Cac(If physical access to university is restricted) A(instructors) D(shall) I(deliver) Bdir(courses) Cex(via online teaching platforms).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20physical%20access%20to%20university%20is%20restricted,%20instructors%20shall%20deliver%20courses%20via%20online%20teaching%20platforms.&codedStmt=Cac(If%20physical%20access%20to%20university%20is%20restricted)%20A(instructors)%20D(shall)%20I(deliver)%20Bdir(courses)%20Cex(via%20online%20teaching%20platforms).&stmtId=1)

<a name="ed1ch7ex19"></a>
### Chapter 7 Example 19

```A(Instructors) I(set) Bdir,p(course-specific) Bdir(policies) Bdir,p(on absences from scheduled class meetings) Cex(in their syllabi).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Instructors%20set%20course-specific%20policies%20on%20absences%20from%20scheduled%20class%20meetings%20in%20their%20syllabi.&codedStmt=A(Instructors)%20I(set)%20Bdir,p(course-specific)%20Bdir(policies)%20Bdir,p(on%20absences%20from%20scheduled%20class%20meetings)%20Cex(in%20their%20syllabi).&stmtId=1)

<a name="ed1ch7ex20"></a>
### Chapter 7 Example 20

```A(State) D(will) I(rely) Bdir(on the advice) Bdir,p(of recognized (clinical experts [AND] scientists)) Cex(to (review [AND] approve) the (safety [AND] effectiveness) of every vaccine that is authorized by the federal government for distribution).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=The%20State%20will%20rely%20on%20the%20advice%20of%20recognized%20clinical%20experts%20and%20scientists%20to%20review%20and%20approve%20the%20safety%20and%20effectiveness%20of%20every%20vaccine%20that%20is%20authorized%20by%20the%20federal%20government%20for%20distribution.&codedStmt=A(State)%20D(will)%20I(rely)%20Bdir(on%20the%20advice)%20Bdir,p(of%20recognized%20(clinical%20experts%20[AND]%20scientists))%20Cex(to%20(review%20[AND]%20approve)%20the%20(safety%20[AND]%20effectiveness)%20of%20every%20vaccine%20that%20is%20authorized%20by%20the%20federal%20government%20for%20distribution).&stmtId=1)

<a name="ed1ch7ex21"></a>
### Chapter 7 Example 21

```A(A sailing vessel) D(shall not) I(impede) Bdir(the passage of a vessel) Bdir,p(that can safely navigate only within a narrow channel or fairway).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=A%20sailing%20vessel%20shall%20not%20impede%20the%20passage%20of%20a%20vessel%20that%20can%20safely%20navigate%20only%20within%20a%20narrow%20channel%20or%20fairway.&codedStmt=A(A%20sailing%20vessel)%20D(shall%20not)%20I(impede)%20Bdir(the%20passage%20of%20a%20vessel)%20Bdir,p(that%20can%20safely%20navigate%20only%20within%20a%20narrow%20channel%20or%20fairway).&stmtId=1)

<a name="ed1ch7ex22"></a>
### Chapter 7 Example 22

```A(Businesses) D(must) I(submit) Bdir,p(a financial) Bdir(report) Cex(annually), O{A(authorizing body) D(may) I(suspend) Bdir(operating license)}.```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Businesses%20must%20submit%20a%20financial%20report%20annually,%20or%20else%20authorizing%20body%20may%20suspend%20operating%20license.&codedStmt=A(Businesses)%20D(must)%20I(submit)%20Bdir,p(a%20financial)%20Bdir(report)%20Cex(annually),%20O{A(authorizing%20body)%20D(may)%20I(suspend)%20Bdir(operating%20license)}.&stmtId=1)

<a name="ed1ch7ex23"></a>
### Chapter 7 Example 23

```A(farmer) D([must]) I(submit) Bdir,p(an organic systems) Bdir(plan) Cex(by the end of the calendar year) O{the A(certifier) D(may) I(suspend) the Bdir,p(farmer’s) Bdir(operating license)}.```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20farmer%20fails%20to%20submit%20an%20organic%20system%27s%20plan%20by%20the%20end%20of%20the%20calendar%20year,%20the%20certifier%20may%20suspend%20farmer%E2%80%99s%20operating%20license.&codedStmt=A(farmer)%20D([must])%20I(submit)%20Bdir,p(an%20organic%20systems)%20Bdir(plan)%20Cex(by%20the%20end%20of%20the%20calendar%20year)%20O{the%20A(certifier)%20D(may)%20I(suspend)%20the%20Bdir,p(farmer%E2%80%99s)%20Bdir(operating%20license)}.&stmtId=1)

<a name="ed1ch7ex24"></a>
### Chapter 7 Example 24

```E(Board Directors) F(are) P(“fiduciaries”) P,p(of the organization they serve).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Board%20Directors%20are%20%E2%80%9Cfiduciaries%E2%80%9D%20of%20the%20organization%20they%20serve.&codedStmt=E(Board%20Directors)%20F(are)%20P(%E2%80%9Cfiduciaries%E2%80%9D)%20P,p(of%20the%20organization%20they%20serve).&stmtId=1)

<a name="ed1ch7ex25"></a>
### Chapter 7 Example 25

```E,p(All) E(individuals) E,p((16 years of age and older [AND] that reside in the United States)) F(are eligible) Cex(by law) P(to receive the COVID vaccine).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=All%20individuals%2016%20years%20of%20age%20and%20older%20that%20reside%20in%20the%20United%20States%20are%20eligible%20by%20law%20to%20receive%20the%20COVID%20vaccine.&codedStmt=E,p(All)%20E(individuals)%20E,p((16%20years%20of%20age%20and%20older%20[AND]%20that%20reside%20in%20the%20United%20States))%20F(are%20eligible)%20Cex(by%20law)%20P(to%20receive%20the%20COVID%20vaccine).&stmtId=1)

<a name="ed1ch7ex26"></a>
### Chapter 7 Example 26

```A E(Renewable Energy Generation Unit) M(may) F(qualify) P(as a Class II Generation Unit) Cex(subject to regulatory provisions).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=A%20Renewable%20Energy%20Generation%20Unit%20may%20qualify%20as%20a%20Class%20II%20Generation%20Unit%20subject%20to%20regulatory%20provisions.&codedStmt=A%20E(Renewable%20Energy%20Generation%20Unit)%20M(may)%20F(qualify)%20P(as%20a%20Class%20II%20Generation%20Unit)%20Cex(subject%20to%20regulatory%20provisions).&stmtId=1)

<a name="ed1ch7ex27"></a>
### Chapter 7 Example 27

```An E(approval) E,p(granted by the Department) M(shall) F(be) a P,p(temporary) P(approval) Cex(only).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=An%20approval%20granted%20by%20the%20Department%20shall%20be%20a%20temporary%20approval%20only.&codedStmt=An%20E(approval)%20E,p(granted%20by%20the%20Department)%20M(shall)%20F(be)%20a%20P,p(temporary)%20P(approval)%20Cex(only).&stmtId=1)

<a name="ed1ch7ex28"></a>
### Chapter 7 Example 28

```E(Inspection procedures) F(are regulated) P(by provisions) P,p(laid out in Section 2).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Inspection%20procedures%20are%20regulated%20by%20provisions%20laid%20out%20in%20Section%202.&codedStmt=E(Inspection%20procedures)%20F(are%20regulated)%20P(by%20provisions)%20P,p(laid%20out%20in%20Section%202).&stmtId=1)

<a name="ed1ch7ex29"></a>
### Chapter 7 Example 29

```E(Audits) F(are) P,p(financial) P(inspections) P,p(conducted by a certified authority licensed according to this Act).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Audits%20are%20financial%20inspections%20conducted%20by%20a%20certified%20authority%20licensed%20according%20to%20this%20Act.&codedStmt=E(Audits)%20F(are)%20P,p(financial)%20P(inspections)%20P,p(conducted%20by%20a%20certified%20authority%20licensed%20according%20to%20this%20Act).&stmtId=1)
<a name="ed1ch7ex30"></a>
### Chapter 7 Example 30

```E([Characteristics]) F([are]): {P{A(Board of Directors) D(must) Cex(duly) I(be passed [pass]) Bdir([item in question])} [AND] P{A([Board of Directors]) I(establish) Bdir((rule [OR] convention)) Bdir,p(of general application) Bind([of item in question])} [AND] P{E([the item in question]) M(must) F(be) P(mission-consistent)}.}.```


<!-- only focusing on second statement, i.e., omitted The E(item in question) M(must) F(have) the P,p(following) P(characteristics). -->
[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=The%20item%20in%20question%20must%20have%20the%20following%20characteristics:%20be%20duly%20passed%20by%20the%20Board%20of%20Directors,%20establish%20rule%20or%20convention%20of%20general%20application,%20and%20must%20be%20mission-consistent.&codedStmt=E([Characteristics])%20F([are]):%20%7BP%7BA(Board%20of%20Directors)%20D(must)%20Cex(duly)%20I(be%20passed%20[pass])%20Bdir([item%20in%20question])%7D%20[AND]%20P%7BA([Board%20of%20Directors])%20I(establish)%20Bdir((rule%20[OR]%20convention))%20Bdir,p(of%20general%20application)%20Bind([of%20item%20in%20question])%7D%20[AND]%20P%7BE([the%20item%20in%20question])%20M(must)%20F(be)%20P(mission-consistent)%7D.%7D&stmtId=1)

<a name="ed1ch7ex31"></a>
### Chapter 7 Example 31

```A(Board members) I(serve) Cex(as organizational leaders).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Board%20members%20serve%20as%20organizational%20leaders.&codedStmt=A(Board%20members)%20I(serve)%20Cex(as%20organizational%20leaders).&stmtId=1)

<a name="ed1ch7ex32"></a>
### Chapter 7 Example 32

```E(Board members) F(serve as) P,p(organizational) P(leaders).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Board%20members%20serve%20as%20organizational%20leaders.&codedStmt=E(Board%20members)%20F(serve%20as)%20P,p(organizational)%20P(leaders).&stmtId=1)

<a name="ed1ch7ex33"></a>
### Chapter 7 Example 33

```A(Faculty) D([must]) I([assign]) Bdir(grades).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Faculty%20are%20responsible%20for%20assigning%20grades.&codedStmt=A(Faculty)%20D([must])%20I([assign])%20Bdir(grades).&stmtId=1)

<a name="ed1ch7ex34"></a>
### Chapter 7 Example 34

```E(Faculty) F(are responsible) for P(assigning grades).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Faculty%20are%20responsible%20for%20assigning%20grades.&codedStmt=E(Faculty)%20F(are%20responsible)%20for%20P(assigning%20grades).&stmtId=1)

<a name="ed1ch7ex35"></a>
### Chapter 7 Example 35

```Cac{When A(Program Manager) I(reveals) Bdir{A,p(accredited) A(certifying agent) I([is not in compliance]) with the Bdir((Act [OR] regulations in this part))} Cac{When A(Program Manager) I((([inspects] [OR] [reviews]) [OR] [investigates])) Bind,p(accredited) Bind(certifying agent)}} A([Program Manager]) D(shall) I([send]) Bdir(notification) Bdir,p(of non-compliance) to the Bind,p(accredited) Bind(certifying agent).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=When%20an%20inspection,%20review,%20or%20investigation%20of%20an%20accredited%20certifying%20agent%20by%20the%20Program%20Manager%20reveals%20any%20non-compliance%20with%20the%20Actor%20regulations%20in%20this%20part,%20a%20written%20notification%20of%20non-compliance%20shall%20be%20sent%20to%20the%20certifying%20agent.&codedStmt=Cac{When%20A(Program%20Manager)%20I(reveals)%20Bdir{A,p(accredited)%20A(certifying%20agent)%20I([is%20not%20in%20compliance])%20with%20the%20Bdir((Act%20[OR]%20regulations%20in%20this%20part))}%20Cac{When%20A(Program%20Manager)%20I((([inspects]%20[OR]%20[reviews])%20[OR]%20[investigates]))%20Bind,p(accredited)%20Bind(certifying%20agent)}}%20A([Program%20Manager])%20D(shall)%20I([send])%20Bdir(notification)%20Bdir,p(of%20non-compliance)%20to%20the%20Bind,p(accredited)%20Bind(certifying%20agent).&stmtId=1)

<a name="ed1ch7ex36"></a>
### Chapter 7 Example 36

```E(Audits) F(are) P,p1(financial) P(inspections) P,p2(conducted by a certified authority) P,p2,p(licensed according to this Act).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Audits%20are%20financial%20inspections%20conducted%20by%20a%20certified%20authority%20licensed%20according%20to%20this%20Act.&codedStmt=E(Audits)%20F(are)%20P,p1(financial)%20P(inspections)%20P,p2(conducted%20by%20a%20certified%20authority)%20P,p2,p(licensed%20according%20to%20this%20Act).&stmtId=1)

<a name="ed1ch7ex37"></a>
### Chapter 7 Example 37

```Cac{When A[role=[actor,experiencer]](Program Manager) I(reveals) Bdir[type=abstract]{A,p(accredited) A[role=actor](certifying agent) I[regfunc=violate](is not in compliance) with the Bdir[anim=inanimate,ref=[act,part]]((Act [OR] regulations in this part))} Cac{When A[role=actor](Program Manager) I[regfunc=monitor](((inspects [OR] reviews) [OR] investigates)) Bind,p(accredited) Bind[role=experiencer](certifying agent)}} A[role=actor](Program Manager) D(shall) I(send) Bdir[type=concrete,anim=inanimate](notification) Bdir,p(of non-compliance) to the Bind,p(accredited) Bind[role=[recipient,maleficiary]](certifying agent).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=When%20Program%20Manager%20reveals%20that%20accredited%20certifying%20agent%20is%20not%20in%20compliance%20with%20the%20Act%20or%20regulations%20in%20this%20part,%20when%20Program%20Manager%20inspects,%20reviews%20or%20investigates%20accredited%20certifying%20agent,%20Program%20Manager%20shall%20send%20notification%20of%20non-compliance%20to%20the%20accredited%20certifying%20agent.&codedStmt=Cac{When%20A[role=[actor,experiencer]](Program%20Manager)%20I(reveals)%20Bdir[type=abstract]{A,p(accredited)%20A[role=actor](certifying%20agent)%20I[regfunc=violate](is%20not%20in%20compliance)%20with%20the%20Bdir[anim=inanimate,ref=[act,part]]((Act%20[OR]%20regulations%20in%20this%20part))}%20Cac{When%20A[role=actor](Program%20Manager)%20I[regfunc=monitor](((inspects%20[OR]%20reviews)%20[OR]%20investigates))%20Bind,p(accredited)%20Bind[role=experiencer](certifying%20agent)}}%20A[role=actor](Program%20Manager)%20D(shall)%20I(send)%20Bdir[type=concrete,anim=inanimate](notification)%20Bdir,p(of%20non-compliance)%20to%20the%20Bind,p(accredited)%20Bind[role=[recipient,maleficiary]](certifying%20agent).&stmtId=1)

<br/> 

<a name="ed1ch8"></a>
## Chapter 8 Examples

<a name="ed1ch8ex1"></a>
### Chapter 8 Example 1

```The A(Program Manager) D(may) I(initiate) Bdir,p((suspension [XOR] revocation)) Bdir(proceedings) against a Bind,p(certified) Bind(operation): {Cac{when the A(Program Manager) I(believes) that Bdir{a A,p(certified) A(operation) I((has violated [OR] is not in compliance)) Bdir(with (the Act [OR] regulations in this part))}}, [OR] Cac{when a A((certifying agent [OR] State organic program’s governing State official)) I(fails to enforce) Bdir((the Act [OR] regulations in this part)).}}```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=The%20Program%20Manager%20may%20initiate%20suspension%20or%20revocation%20proceedings%20against%20a%20certified%20operation:%20when%20the%20Program%20Manager%20believes%20that%20a%20certified%20operation%20has%20violated%20or%20is%20not%20in%20compliance%20with%20the%20Act%20or%20regulations%20in%20this%20part,%20or%20when%20a%20certifying%20agent%20or%20State%20organic%20program%E2%80%99s%20governing%20State%20official%20fails%20to%20enforce%20the%20Act%20or%20regulations%20in%20this%20part.&codedStmt=The%20A(Program%20Manager)%20D(may)%20I(initiate)%20Bdir,p((suspension%20[XOR]%20revocation))%20Bdir(proceedings)%20against%20a%20Bind,p(certified)%20Bind(operation):%20{Cac{when%20the%20A(Program%20Manager)%20I(believes)%20that%20Bdir{a%20A,p(certified)%20A(operation)%20I((has%20violated%20[OR]%20is%20not%20in%20compliance))%20Bdir(with%20(the%20Act%20[OR]%20regulations%20in%20this%20part))}},%20[OR]%20Cac{when%20a%20A((certifying%20agent%20[OR]%20State%20organic%20program%E2%80%99s%20governing%20State%20official))%20I(fails%20to%20enforce)%20Bdir((the%20Act%20[OR]%20regulations%20in%20this%20part)).}}&stmtId=1)

<a name="ed1ch8ex2"></a>
### Chapter 8 Example 2

```A A(certifying agent) D(must) I(notify) the Bind(Program Manager) of Bdir,p(all) Bdir(compliance (proceedings [AND] actions)) Bdir,p(taken pursuant to this part).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=A%20certifying%20agent%20must%20notify%20the%20Program%20Manager%20of%20all%20compliance%20proceedings%20and%20actions%20taken%20pursuant%20to%20this%20part.&codedStmt=A%20A(certifying%20agent)%20D(must)%20I(notify)%20the%20Bind(Program%20Manager)%20of%20Bdir,p(all)%20Bdir(compliance%20(proceedings%20[AND]%20actions))%20Bdir,p(taken%20pursuant%20to%20this%20part).&stmtId=1)

<a name="ed1ch8ex3"></a>
### Chapter 8 Example 3

```Cac{When A([Program Manager]) I(reveals) Bdir,p(any) Bdir(noncompliance) Cex(with the (Act [OR] regulations in this part)) Cac{When A([Program Manager]) I(inspects) an Bdir,p(accredited) Bdir(certifying agent)}} A(Program Manager) D(shall) I(send) Bdir,p(written) Bdir(notification) Bdir,p(of noncompliance) to the Bind(certifying agent).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=When%20an%20inspection%20...%20of%20an%20accredited%20certifying%20agent%20by%20the%20Program%20Manager%20reveals%20any%20noncompliance%20with%20the%20Act%20or%20regulations%20in%20this%20part,%20a%20written%20notification%20of%20noncompliance%20shall%20be%20sent%20to%20the%20certifying%20agent.&codedStmt=Cac{When%20A([Program%20Manager])%20I(reveals)%20Bdir,p(any)%20Bdir(noncompliance)%20Cex(with%20the%20(Act%20[OR]%20regulations%20in%20this%20part))%20Cac{When%20A([Program%20Manager])%20I(inspects)%20an%20Bdir,p(accredited)%20Bdir(certifying%20agent)}}%20A(Program%20Manager)%20D(shall)%20I(send)%20Bdir,p(written)%20Bdir(notification)%20Bdir,p(of%20noncompliance)%20to%20the%20Bind(certifying%20agent).&stmtId=1)

<a name="ed1ch8ex4"></a>
### Chapter 8 Example 4

```Cac{If A(Program Manager) I(fails to submit) Bdir(notification) Bdir,p(of noncompliance)} E(noncompliance proceedings) F(are considered) P(not initiated).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=If%20Program%20Manager%20fails%20to%20submit%20notification%20of%20noncompliance,%20noncompliance%20proceedings%20are%20considered%20not%20initiated.&codedStmt=Cac{If%20A(Program%20Manager)%20I(fails%20to%20submit)%20Bdir(notification)%20Bdir,p(of%20noncompliance)},%20E(noncompliance%20proceedings)%20F(are%20considered)%20P(not%20initiated).&stmtId=1)

<a name="ed1ch8ex5"></a>
### Chapter 8 Example 5

```Cac{When A([Program Manager]) I(reveals) Bdir,p[proptype=quan](any) Bdir(noncompliance) Cex(with the (Act [OR] regulations in this part)) Cac{When A([Program Manager]) I(inspects) an Bdir,p[proptype=qual](accredited) Bdir(certifying agent)}} A(Program Manager) D(shall) I(send) Bdir,p(written) Bdir[proptype=structure](notification) Bdir,p(of noncompliance) to the Bind(certifying agent).```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=When%20an%20inspection%20of%20an%20accredited%20certifying%20agent%20by%20the%20Program%20Manager%20reveals%20any%20noncompliance%20with%20the%20Act%20or%20regulations%20in%20this%20part,%20a%20written%20notification%20of%20noncompliance%20shall%20be%20sent%20to%20the%20certifying%20agent.&codedStmt=Cac{When%20A([Program%20Manager])%20I(reveals)%20Bdir,p[proptype=quan](any)%20Bdir(noncompliance)%20Cex(with%20the%20(Act%20[OR]%20regulations%20in%20this%20part))%20Cac{When%20A([Program%20Manager])%20I(inspects)%20an%20Bdir,p[proptype=qual](accredited)%20Bdir(certifying%20agent)}}%20A(Program%20Manager)%20D(shall)%20I(send)%20Bdir,p(written)%20Bdir[proptype=structure](notification)%20Bdir,p(of%20noncompliance)%20to%20the%20Bind(certifying%20agent).&stmtId=1)

<a name="ed1ch8ex6"></a>
### Chapter 8 Example 6

```The A(Program Manager) D(may) I(initiate) Bdir,p(revocation) Bdir(proceedings) against a Bind,p(certified) Bind(operation): {Cac{when the A(Program Manager) I(believes) that a Bdir{A,p(certified) A(operation) has I(violated) the Bdir(Act)}}, [OR] Cac{when a A(certifying agent) I(fails to enforce) Bdir(the Act).}}```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=The%20Program%20Manager%20may%20initiate%20revocation%20proceedings%20against%20a%20certified%20operation:%20when%20the%20Program%20Manager%20believes%20that%20a%20certified%20operation%20has%20violated%20the%20Act,%20or%20when%20a%20certifying%20agent%20fails%20to%20enforce%20the%20Act.&codedStmt=The%20A(Program%20Manager)%20D(may)%20I(initiate)%20Bdir,p(revocation)%20Bdir(proceedings)%20against%20a%20Bind,p(certified)%20Bind(operation):%20{Cac{when%20the%20A(Program%20Manager)%20I(believes)%20that%20a%20Bdir{A,p(certified)%20A(operation)%20has%20I(violated)%20the%20Bdir(Act)}},%20[OR]%20Cac{when%20a%20A(certifying%20agent)%20I(fails%20to%20enforce)%20Bdir(the%20Act).}}&stmtId=1)

<a name="ed1ch8ex7"></a>
### Chapter 8 Example 7

```E(Councils) E,p(missing minority representation) F(are) P(illegitimate)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Councils%20missing%20minority%20representation%20are%20illegitimate.&codedStmt=E(Councils)%20E,p(missing%20minority%20representation)%20F(are)%20P(illegitimate).&stmtId=1)

<a name="ed1ch8ex8"></a>
### Chapter 8 Example 8

```E(Councils) F(are) P(illegitimate) Cac(missing minority representation)```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Councils%20are%20illegitimate%20missing%20minority%20representation.&codedStmt=E(Councils)%20F(are)%20P(illegitimate)%20Cac(missing%20minority%20representation).&stmtId=1)

<a name="ed1ch8ex9"></a>
### Chapter 8 Example 9

```E(Councils) F(are) P(illegitimate) Cac{if E(Councils) F(do not have) P(minority representation)}```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Councils%20are%20illegitimate%20if%20Councils%20do%20not%20have%20minority%20representation.&codedStmt=E(Councils)%20F(are)%20P(illegitimate)%20Cac{if%20E(Councils)%20F(do%20not%20have)%20P(minority%20representation)}.&stmtId=1)

<a name="ed1ch8ex10"></a>
### Chapter 8 Example 10

```E(Councils) M(are required) F(to have) P(minority representation) O{E(Councils) F(are) P(illegitimate)}.```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Councils%20are%20required%20to%20have%20minority%20representation,%20or%20else%20Councils%20are%20illegitimate.&codedStmt=E(Councils)%20M(are%20required)%20F(to%20have)%20P(minority%20representation)%20O{E(Councils)%20F(are)%20P(illegitimate)}.&stmtId=1)

<a name="ed1ch8ex11"></a>
### Chapter 8 Example 11

```A(Councils) D(must) I([establish]) Bdir(minority representation) O{E(Councils) F(are) P(illegitimate)}.```

[Open in IG Parser](https://ig-parser.newinstitutionalgrammar.org/visual/?rawStmt=Councils%20must%20[establish]%20minority%20representation,%20or%20else%20Councils%20are%20illegitimate.&codedStmt=A(Councils)%20D(must)%20I([establish])%20Bdir(minority%20representation)%20O{E(Councils)%20F(are)%20P(illegitimate)}.&stmtId=1)

<a name="ed1ch8ex12"></a>
### Chapter 8 Example 12

```{A(Program Manager) D(should) [NOT] I(believe) that a Bdir{A,p(certified) A(operation) I[regfunc=violate[severe,moderate]]((has violated [OR] is not in compliance)) Bdir[ref=[act,part]]((with the Act [OR] regulations in this part))}} [AND] {a A((certifying agent [OR] State organic program’s governing State official)) D(should) [NOT] I[regfunc=violate](fails to enforce) Bdir[ref=[act,part]]((the Act [OR] regulations in this part))} O{A(Program Manager) D(may) I[regfunc=sanction](initiate) Bdir,p[regfunc=sanction [mild,severe]]((suspension [XOR] revocation)) Bdir(proceedings) against a Bind,p(certified) Bind(operation)}```

