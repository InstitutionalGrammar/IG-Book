---
layout: default
title: IG Book
---

## Coder's Corner

This page specifically targets common challenges encountered when encoding institutional statements. While any coder is encouraged to review the IG 2.0 Codebook for reference (in which those aspects are covered), an overview of common questions alongside a practice-oriented explanation is provided here. We intend to update this overview based on typical challenges observed or reported during the encoding of institutional statements.

Please click on the individual questions to expand their content.


<details>
  <summary>What is the typical structure of regulative and constitutive statements?</summary><br/>
 
Regulative statements express observed, expected, or regulated behavior attributed to particular actors. For example, ```A(Citizens) D(must) I(submit) Bdir(tax returns)``` reflects a typical regulative structure, observable by the expression of duty (or permission) associated with a particular activity to a responsible actor.

Constitutive statements capture the introduction of concepts into the institutional settings. For example, ```E(Tax returns) F(are) P(annually filed documents stating the taxable income)``` defines what tax returns are in the context of the institutional setting. However, such statement does not express any explicit reference to a regulated activity or a responsible actor. Tax returns simply *are* what they are defined as (```annually filed ...```).
</details>
<br/>

<details>
  <summary>What is the difference between Execution Constraints vs. Object Properties?</summary><br/>
  
A common coding challenge is to differentiate between *Object Properties* and *Execution Constraints*. To operationalize the distinction, it is important to identify the entity the property or constraint in question refers to. Where *Object Properties* provide additional characterizations for an *Attribute*, *Object* variants (for regulative statements), *Constituted Entity* or *Constituting Properties* components (for constitutive statements), Execution constraints *qualify* the activity, i.e., the Aim (for the case of regulative statements), or Constitutive Function (in the case of a constitutive statement) of a statement. Conceptually, Property act as second-order descriptor of components that describe or reference entities, whereas Execution Constraints act as second-order descriptors of Aims or Constitutive Function, often indicating *how* or *why* an activity is performed (Note that various other types of execution constraints are reflected in the *Context Taxonomy*). The following examples highlight this distinctive difference.
 
In the statement ```A(Citizens) D(must) I(submit) Bdir(tax returns) Cex(to facilitate a precise tax assessment).``` the execution constraint qualifies the activity *submit* by indicating why this activity is to be performed (here signaling the purpose). It does, however, not qualify the nature of the tax returns in any specific way.
  
The statement ```A(Citizens) D(must) I(submit) Bdir(tax returns) Bdir,p(that indicate past year's earnings).```, in contrast, includes an *Object Property* (Bdir,p) that contains a descriptor of the *Direct Object*, i.e., the *tax returns*, and describes their content.
  
</details>
<br/>

<details>
  <summary>Should nesting be applied for all instances of ANDs, and ORs?</summary><br/>
  
The IG 2.0 emphasizes a semantic perspective when engaging in coding. It is central to identify whether the linguistically linked items also reflect an institutionally relevant logical linkage that requires separate consideration (e.g., to assess compliance). For instance, a reference to ```Ben and Jerry's``` does not reflect a separate consideration, since it semantically references a product or brand. ```Monitor and enforce```, in constrast, reflects distinctive activities that may need to be both fulfilled in order to consider them complied with. Similarly, ```divide and conquer``` may invite for separated evaluation (i.e., whether one has divided, and then conquered), but may in context refer to a figure of speech, in which the expression is treated in compound form without further decomposition. Essential for the assessment as to whether nesting is applied is the meaning of the expression in the context of the analyzed institutional setting, as well as the epistemological basis on which the analysis rests (e.g., assessment of regulatory compliance).  
</details>

</details>
<br/>

<details>
  <summary>What are hybrid institutional statements?</summary><br/>
  
Hybrid institutional statements are statements that combine regulative and constitutive statements in arbitrary form, where a regulative expression is followed by a constitutive element, or vice versa. A typical example has the following structure: ```Citizens must not violate the traffic rules, where traffic rules are defined as formal or informal rules of behavior applicable in any traffic setting.``` The former element is regulative (by guiding behavior), and the latter expression part (```... where traffic rules ...```) is constitutive in kind. Such statement thus reflects a regulative-constitutive hybrid statement. In cases, where contextual interpretation allows for the interpretation in both forms, such statement is referred to as a polymorphic institutional statement. Details are discussed in the IG 2.0 Codebook and Chapter 5 of the book.
</details>
<br/>

<details>
  <summary>When should a property be separated from the associated component?</summary><br/>
  
Generally, the property introduces a specific qualification of an entity (e.g., actor, object) that is variable in an institutional setting. For instance, proper names such as ```Program Manager``` should not be decomposed into component and associated property in as far as they describe a destinctive concept (or in this case, role). Where entities potentially appear with varying qualifications within an institutional setting (e.g., qualified employee, unqualified employee), the separation of component (```employee```) and its property (```qualified```, ```unqualified```) likely becomes analytically relevant, since it differentiates variations of a given role (employee) in an institutional setting. Drawing on the earlier reference to ```Program Manager```, a potential differentiation between ```appointed``` and ```voluntary``` program managers would warrant the introduction of those qualifications in associated properties.
</details>
<br/>

