---
layout: default
title: IG Book
---

This page contains an overview of the central features of the Institutional Grammar 2.0 (IG 2.0) in a condensed form for quick reference. This includes the basic principles and motivations, as well as an overview of the different levels of expressiveness, followed by the discussion of specific features organized by level of expressiveness. 

Please click on the item of interest to expand the associated details.

## Principles

<br/>

The basic principles that motivate the introduction of the IG 2.0 are listed and explained in this section.

<details>
  <summary>Ontological consistency</summary><br/>
  
Ontological consistency describes the unambiguous characterization of the functional linkage of components in institutional statements with respect to each and/or the institutional setting (for more details, see Section 3.1 of the book). A specific refinement introduced in the IG 2.0 is the distinction between activation conditions and execution constraints as part of a statement specification.
  
</details>
<br/> 

<details>
  <summary>Comprehensive capturing of institutions</summary><br/>

Comprehensiveness in the context of the IG describes the ability to parse institutional statements comprehensively without omitting relevant institutional statement (e.g., omitting statements, or information within statements). Specifically the integrated treatment of regulative and constitutive statement forms address this issue, alongside the different forms of nesting that capture institutional information in detail.

</details>
<br/> 

<details>
  <summary>Computational tractability</summary><br/>
  
Computational tractability interacts with the objective of ontological consistency by making components and statements as a whole accessible for computational treatment. This includes the well-defined nature of components as well as enabling fine-grained parsing of institutional statements.

</details>
<br/> 

<details>
  <summary>Customizability</summary><br/>
  
The IG has found application in diverse domains. The refined IG aims at better accommodating diverse applications of the IG by allowing the analyst to selective apply or forego features of the IG as part of the parsing process. The aim is to extract information that best corresponds to downstream use using particular analytical techniques (e.g., statistical treatment, behavioral modeling, formal reasoning).

</details>
  
<br/>

## IG Features

<br/>

The specific features of the IG 2.0 are listed by level of expressiveness, ranging from coarse-grained coding via fine-grained structural coding to the augmentation of institutional statements with semantic concepts. 

<details>
<summary>Levels of Expressiveness</summary><br/>

Levels of expressiveness reflect the different levels of detail and focus at which institutional statements are encoded to meet different analytical objectives. 
  
*IG Core* as the basic level aims at capturing institutional information broadly, but comprehensively. Central here is the compatibility to the original Institutional Grammar by Crawford and Ostrom, alongside conceptual refinements that increase the ontological consistency and rigor of the IG. Specific examples include the distinction between activation conditions (conditions that lead to the applicability of a given institutional statements) and execution constraints (qualifications of the activity or function of the institutional statement) as part of the *Context* components (*Conditions* in Crawford and Ostrom's version), as well as the introduction of a constitutive syntactic form that enables a comprehensive capturing of institutional information.<br/>  
  
*IG Extended* aims at capturing *structural detail* by allowing fine-grained parsing on component level (i.e., parsing of institutional information within individual components), as well as extraction of richer conceptual structures embedded in institutional statements (e.g., conceptual relationships between entities in component property). This further includes the richer contextualization of selected components based on annotations of *Context*.<br/>
  
*IG Logico*, as the highest level of expressiveness, focuses on the semantic aspects of the institutional information, and specifically the epistemological embedding of the statement parsing in the theory and/or frameworks of interest. This includes the augmentation of encoded information with semantic annotations derived or linked to particular theories, or drawn from selected taxonomies maintained as part of the IG 2.0 (e.g., role annotations, governance functions of actors/actions). IG Logico further introduces a formal syntactic and semantic treatment of institutional statements, including the ability to transform institutional statements based on their structural properties.<br/>

In IG 2.0, the default assumption is the incremental application of the different levels and their features (ensuring that features on higher levels can draw on features encoded on lower levels) as visualized in the following.
  
<center><img src="/figures/IGBibCodingAnalysis.png" width="45%"></center>
  
However, analysts are free to selectively draw on features from specific or across levels that best correspond to their analytical needs or objectives as part of their coding, with the main priorities for the different levels highlighted in the figure below.

<center><img src="/figures/IGLevelObjectives.png" width="55%"></center>
  
</details>

### IG Core

<br/>

The central features introduced under IG Core include:

<details>
<summary>Regulative and Constitutive Statements</summary><br/>

The IG supports the notion of regulative and constitutive statements. 
  
Regulative statements include expressions that regulative of particular actors' behavior in terms of permissions (e.g., `may`) or associated duty (e.g., obligations or prohibitions), and in the IG, follow a principle structure that includes *Attributes*, *Deontic*, *Aim*, *Object* variants (direct and indirect object), and *Context* variants (activation conditions and execution constraints). Regulative statements can further describe consequences for the non-fulfillment of specified statements. 
 
Example: ```A(Citizens) D(must) I(submit) Bdir(tax returns) Bind(at the end of the following financial year).```
  
This statement explicitly signal obligations associated with a particular actor. 
  
Constitutive statements describe features of an institutional setting, e.g., by defining or introducing entities into the institutional setting, which can include actors, aims, venues, roles, objects and artifacts relevant in a given institutional setting. Central components include the *Constituted Entity*, *Modal*, *Constitutive Function*, *Constituting Properties*, *Context* variants (activation conditions and execution constraints). Constitutive statements can further describe consequences for the non-fulfillment of such statements. In contrast to regulative statements, such consequences are often existential in kind.
  
Example: ```E(Voters) F(are) P(citizens) P,p(aged 18 and older).```
  
This statement defines what voters are. Specific permissions and duty can be specified by corresponding regulative statements. 
  
</details>
<br/> 

<details>
<summary>Statement-level Nesting</summary><br/>

Central to the IG 2.0 is the introduction of nested institutional statements. The concepts builds on two observations, firstly that consequences in institutional statements have the structure of institutional statements (or states) themselves, and can thus be expressed using the same the syntactic form as applied for the leading statement. Consequently, institutional statements are divided into a part that is *monitored* (reflecting the *monitored statement*), and the second *consequential* part (reflecting the *consequential statement*) that captures the consequences for violating the monitored statement. This form of nesting is referred to as *vertical nesting*.
  
Example: ```A(Individuals) D(must [NOT]) I(violate) Bdir(public order), or else O{A(enforcement officials) D(must) I(intervene)}.```
  
The second observation refers to the common combination of terms in natural language, such as the combination of selected components (e.g., multiple actors and actions, such as ``Individuals may not enter or leave dwellings during curfew.``) in a single statement. Such statements can conceptually decomposed into logically-combined *atomic institutional statements* to capture the institutional content in detail and semantically precise. This form of nesting is referred to as *horizontal nesting*, since the evaluation of one statement (unlike in the vertical case) is in principle not conditional on the other.
  
Example: ```A(Individuals) D(may [NOT]) I((enter [AND] leave)) Bdir(dwellings) Cac(during curfew).```, which is conceptually equivalent to 
  
  ```{A(Individuals) D(may [NOT]) I(enter) Bdir(dwellings) Cac(during curfew).} [AND] {A(Individuals) D(may [NOT]) I(leave) Bdir(dwellings) Cac(during curfew).}``` 
  
Note that this particular example reveals the ambiguous use of `or` in natural language; logically, the statement implies the prohibition to neither enter nor leave. The purpose of the logical operators is to make such linkages explicit.

</details>

### IG Extended

<br/>

The central features introduced under IG Extended include:

<details>
<summary>Component-level Nesting</summary><br/>

Component-level nesting extends the concept of statement-level nesting by allowing the substitution of individual components with institutional state(ments). This way it is possible to explicitly parse the structure of activation conditions, which often contain institutional state information expressed in terms of the AIC or EFC pattern. This principles extends to various other components, including *Attributes*, *Object* variants, *Context* variants, *Constituted Entities*, *Constituting Properties*, as well as all *Properties* associated with selected components (e.g., *Attributes Properties*).

Example: ```A(Student) D(must) I(submit) Bdir(assignment) Cex(by the end of the term), Cac{unless [NOT] A(coordinator) I(has specified) a Bdir,p(different) Bdir(due date) Cex(in the course description)}.```
  
</details>
<br/> 

<details>
<summary>Object-Property/Concept Hierarchy</summary><br/>
  
A central feature to capture concept structures embedded within institutional statements is to be able to recognize the quality of the relationships of concepts, including the detection of functional dependencies (e.g., a suspension of certification, where the suspension necessarily depends on the existence of the certification in the first place) and potential logical relationships between those concepts. This feature is useful if the analyst seeks to extract a concept hierarchy, e.g., for the construction of ontologies, as part of the analysis process. The following figure exemplifies this for a given scenario describing a certification that can selectively be suspended, revoked based on a written notification. A richer discussion is offered as part of Section 5.1.4 of the book, as well as the <a href="https://arxiv.org/abs/2008.08937" target="_blank">IG 2.0 Codebook</a>.

<center><img src="/figures/ObjectPropertyHierarchyExample.png" width="45%"></center>
  
</details>
<br/> 

<details>
<summary>Property Typology</summary><br/>

The *Property Typology* offers a systematic qualification of properties as either quantitative or qualitative in nature (alongside further sub categories) in order to differentiate descriptors that are central for the evaluation of the fulfillment of a provision (e.g., ```*all* *accredited* members shall vote```, where *all* is a descriptor of quantitative kind, whereas *accredited* merely captures the quality associated with the concept *members*). The principles and the motivation of this feature are further discussed in Section 5.1.5 of the book.
  
</details>
<br/> 

<details>
<summary>Context Taxonomy</summary><br/>

The *Context Taxonomy* builds on Crawford and Ostrom's original conceptual characterization of the *Conditions* component (e.g., temporal, spatial and procedural aspects) and expands this categorization into a richer taxonomic structure that captures diverse types of context, including method, event and domanial categories, amongst others. Details are provided in the <a href="https://arxiv.org/abs/2008.08937" target="_blank">IG 2.0 Codebook</a>.
  
</details>

### IG Logico

<br/>

The central features introduced under IG Logico include:

<details>
<summary>Semantic Annotations</summary><br/>

IG Logico aims at developing an epistemological linkage between the domain of interest and the encoded institutional information. Central here is the ability to annotate encoded information using semantic annotations that capture the functional role (*Institutional Functions*) or signal that the component values convey with respect to the domain or through the applied analytical lens. Referencing an example of such institutional function, analyzing an institutional setting with respect to compliance behavior `not submitting the tax return on time` reflects a violation (whereas `submission on time` reflects the institutional function of signaling compliance). IG 2.0 provides a set of predefined taxonomies prepared for the annotations of selected components (e.g., roles, metatypes of referenced concepts, as well as institutional functions in the context of compliance assessment), but further allows for the introduction of classifications drawn from the domain of the analyst. More details can found in Section 6.1.2 onwards in the book, as well as the <a href="https://arxiv.org/abs/2008.08937" target="_blank">IG 2.0 Codebook</a>.
  
</details>
<br/> 

<details>
<summary>Statement Transformations</summary><br/>

With the encoding on higher levels of expressiveness (IG Extended or Logico), institutional statements can be transformed algorithmically, e.g., to reflect policy from specific actors' perspectives, establish a uniform structural representation to facilitate downstream analysis or comparative studies, or extrapolation multiple involved actors' perspectives tacitly captured in institutional statements for richer behavioral models or assessment of biases captured in policy. See Section 6.1.4 of the book for details on transformation rules and Section 8.3 for illustrative applications. 
  
</details>
<br/> 
