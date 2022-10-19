---
layout: page
title: MLE 2022
subtitle: 4th International Workshop on Modeling Language Engineering, October 24, 2022 <br /> Co-located with <a href="https://conf.researchr.org/home/models-2022">MODELS 2022</a>
---

<style>
.session-chairs {
  display: flex;
  height: 200px;
}
.session-chair {
  flex: 1;
  text-align: center;
  max-height: 100%;
}

.session-chair img {
  max-height: 80%;
}

.session-chair a {
  max-height: 20%;
}

</style>

<p align="center">
  <a href="#about">About</a> | 
  <a href="#keynote">Keynote</a> | 
  <a href="#program">Program</a> |
  <a href="#call-for-papers">Call for papers</a> |
  <a href="#dates">Dates</a> | 
  <a href="#program-committee">Program committee</a>
</p>

## About

Software-intensive systems are complicated, driven by the need to integrate across multiple concerns.
Consequently, the development of such systems requires the integration of different concerns and skills.
These concerns can be covered by different domain-specific modeling languages, with specific concepts, technologies, and abstraction levels.
This multiplication of languages eases the development related to each individual specific concern but raises language and technology integration problems at the different stages of the software life cycle.
To reason about the global system as a whole, it is necessary to explicitly describe the different kinds of relationships that exist between the different languages used in its development.
To support effective language integration, there is a pressing need to reify and classify these relationships, as well as the language interactions that the relationships enable.
Equally, the proliferation of domain-specific modeling languages required increases the need for effective and efficient techniques for engineering languages and their support infrastructures (transformations, analysis tools, editors, execution infrastructure, debuggers, …).

The Modeling Language Engineering (MLE) workshop aims at bringing together researchers and practitioners working on modeling-language and software-language engineering. It is a meeting opportunity for Software Language Engineering (SLE) enthusiasts within the software-modeling community.


## Keynote
### Engineering Families of Modelling Languages: A tale of three approaches
**Abstract**: Modelling languages are intensively used in paradigms like model-driven engineering to automate all sort of tasks within the development process. These languages may have variants (like the cases of Petri nets, automata, architectural languages, and many others) in which case, there is the need to deal with language families rather than with individual languages. Moreover, low-code approaches aim at lowering the entry barrier to software development, frequently via the use of modelling notations. Users of low-code environments have a wide range of backgrounds, which calls for specialized language variants, tailored to users with different levels of expertise. However, from a language engineering perspective, specifying the syntax and semantics of each language variant separately is costly, hinders reuse across variants, and may yield inconsistent semantics between variants.
In this talk, I will introduce three different approaches to tackle this problem, based on multi-level modelling, superimposed language variants, and language modules. I will discuss the weak and strong points of each one of them based on a practical case study and propose challenges for future work.

### Speaker
<div style="text-align: left;" markdown="1">
<img style="display: block; margin: auto; height: 200px;" alt="Juan de Lara photo" src="/editions/mle2022/images/juandelara.jpeg">

[Prof. Juan de Lara](http://arantxa.ii.uam.es/~jlara/) is full professor at the computer science department of the Universidad Autónoma of Madrid (Spain), where he leads the modelling and software engineering research ([miso](http://www.miso.es/)) team together with Esther Guerra. His main research interests are in automated software engineering, model-driven development, domain-specific languages and language engineering, conversational interfaces, and augmented reality. This research has led to building many practical tools – including [AToM3](http://atom3.cs.mcgill.ca/), [metaDepth](https://metadepth.org/), [merlin](http://miso.es/tools/merlin/), [alter](https://alter-ar.github.io/), [DSL-comet](https://diagrameditorserver.herokuapp.com/), [DSL-tao](http://jdelara.github.io/DSL-tao/) and [Capone](https://capone-pl.github.io/)– and the publication of more than 230 papers in international journals and conferences. He has been the PC co-chair of several conferences within his research areas, like MODELS, SLE, ICGT, ICMT and FASE, and has been involved in workshops on topics like flexible modelling, multi-level modelling and low-code development.
</div>


## Session chairs

The [organizing committee](#organizing-committee) of MLE 2022 is unfortunately not able to be physically present at MODELS 2022.
Therefore, exceptionnally, MLE 2022 will be presented by three voluntary session chairs from the MLE community:


<div class='session-chairs'>
  <div class='session-chair'>
    <img style="display: block; margin: auto;" alt="Benoit Combemale photo" src="/editions/mle2022/images/benoit.jpg">
    <a href="https://people.irisa.fr/Benoit.Combemale/">Benoit Combemale</a>
  </div>
  <div class='session-chair'>
    <img style="display: block; margin: auto;" alt="Ed Seidewitz photo" src="/editions/mle2022/images/ed.jpg">
    <a href="https://www.linkedin.com/in/seidewitz">Ed Seidewitz</a>
  </div>
  <div class='session-chair'>
    <img style="display: block; margin: auto;" alt="Jean-Marie Mottu photo" src="/editions/mle2022/images/jmm.jpg">
    <a href="http://pagesperso.ls2n.fr/~mottu-jm/welcome-en.html">Jean-Marie Mottu</a>
  </div>
</div>



## Program

**Date**: Monday the 24th of October 2022

### Session 1 (8:30 − 10:00) 

_Chair: Benoit Combemale_

- 8:30 − Workshop introduction

- 8:40 − Keynote by Juan de Lara 

- 9:30 − _Design Guidelines for Improving User Experience in Industrial Domain-Specific Modelling Languages_<br />
            by Rohit Gupta, Nico Jansen, Nikolaus Regnat and Bernhard Rumpe ([paper](https://arxiv.org/abs/2209.14060)).

### Coffee break (10:00 − 10:30)

### Session 2 (10:30 − 12:00)

_Chair: Ed Seidewitz_

- 10:30 − _Towards The Systematic Design of Model Animation: Key Ingredients and General Guidelines_<br />
by Moussa Amrani, Abdelkader Ouared and Pierre-Yves Schobbens. 

- 11:00 − _Classification and Mapping of Layout Algorithms for Usage in Graph-Like Modeling Languages_<br />
            by Gregor Wrobel and Robert Scheffler ([paper](/editions/mle2022/papers/WrobelScheffler_ClassificationMapping_MLE2022_cr_final.pdf)).

- 11:30 − _Generalized Architecture for Client-Agnostic Hybrid Model Editors as a Service_<br />
            by Liam Walsh, Karim Jahed and Juergen Dingel.

### Lunch break (12:00 − 13:30)

### Session 3 (13:30 − 15:00)

_Chair: Jean-Marie Mottu_

- 13:30 − _An Implementation of a Statecharts Interpreter and Compiler With Semantic Variability_<br />
            by Joeri Exelmans, Simon Van Mierlo and Hans Vangheluwe.

- 14:00 − _Transforming Domain Models to Efficient C# for the Danish Pension Industry_<br />
            by Holger Stadel Borum and Morten Tychsen Clausen.

- 14:30 − _A Tool-Assisted Approach to Engineer Domain-Specific Languages (DSLs) using Rust_<br />
            by Léo Olivier, Lou-Anne Sauvêtre, Erwan Bousse and Gerson Sunyé ([paper](https://hal.archives-ouvertes.fr/hal-03790527/document)).


### Coffee break (15:00 − 15:30)

### Session 4 (15:30 − 17:00)

_Chairs: Benoit Combemale and Ed Seidewitz_

- Discussions (TBA) and closing words



## Call for papers

### Topics

The topics of interest for MLE 2022 include:


- Methodologies, languages, techniques, and methods for designing and implementing modeling languages
- Composition, extension, and reuse of modeling languages and model execution tools
- Heterogeneous modeling, simulation, and execution
- Customization of modeling languages
- Integration of modeling languages and programming languages
- Semantics-aware model transformations and code generation
- Scalability of model execution and execution-based model analysis
- Execution of partial and underspecified models
- Model execution in the presence of non-determinism and concurrency
- Tracing model executions and analyzing model execution traces
- Model execution tools for the (dynamic) validation, verification, and testing of systems (e.g., model animation, debugging, simulation, trace exploration, model checking, symbolic execution)
- Live modeling and exploratory modeling techniques
- Automation techniques for the development of modeling and model execution tools
- Evolution in the context of executable modeling (e.g.} evolution of executable modeling languages, execution semantics, executable models, model execution tools)
- Verification of semantic conformance (e.g., among executable modeling languages, executable models, model execution tools)
- Integration challenges for languages, from requirements to design, for analysis and simulation, during runtime, etc.
- Case studies and experience reports on the successful or failed adoption of modeling in different application domains and application contexts
- Surveys and benchmarks of different approaches for the development of modeling languages, model execution, and execution-based model analysis

Submissions describing practical and industrial experience related to the use of modeling languages are also encouraged, particularly in the following application domains:
Cyber-Physical Systems, Smart Manufacturing, Industry 4.0;  Internet of Services, Internet of Things; Smart City, Smart Building, Home automation; Smart and Learning systems.


### Workshop Format

This full-day workshop will prioritize discussions over presentations. We plan to open with a keynote in the morning, followed by paper presentations. 
The afternoon will then be spent primarily in discussions inspired by topics raised by the keynotes and paper presentations. 
Where there is sufficient divergence in the topics raised, we will create break-out groups of participants interested in each sub-topic. The goal of these discussions is to identify commonalities and connections between different topics, support research networking, cross-pollination, and informal knowledge transfer. 
The final session of the workshop will be focused on summarising the key topics and ideas discussed at the workshop to help identify the next steps that may be followed up by workshop participants.

### Submission

We expect early research results about the aforementioned topics, descriptions of problems, case studies, experience reports, or solutions related to the topics of interest.

Each contribution must be described in a short paper of 5 pages or a full paper of 10 pages, in ACM format (acmart). Two more pages containing only references are permitted.

Papers that describe use cases or novel approaches can be accompanied by concrete artifacts, such as models (requirements, design, analysis, transformation, composition, etc.), stored in a public repository. Artifacts should illustrate any experience with the conjoint use of different modeling languages.

All submissions have to follow the ACM format (acmart) and must be submitted electronically in PDF format [via Easychair](https://easychair.org/my/conference?conf=mle2022). They will be evaluated by at least three members of the program committee regarding novelty, correctness, significance, readability, and alignment with the workshop call. 
Furthermore, all submissions must be original work and must not have been previously published or being under review elsewhere. 
The accepted papers will be included in the joint workshop proceedings published in the ACM Digital Library and indexed in DBLP and Scopus.


## Dates

- **Abstract submission deadline**: July 13, 2022
- **Paper submission deadline**: ~~July 20, 2022~~  <span style="color:red">July 29, 2022 (Extended)</span>
- **Notification of acceptance**: August 19, 2022
- **Camera-ready deadline**: ~~August 26, 2022~~ <span style="color:red">September 6, 2022 (Extended)</span>


## Organizing committee

<div style="text-align: left;" markdown="1">

<img style="display: block; margin: auto;" alt="Erwan Bousse photo" src="/editions/mle2022/images/Erwan.jpg">

[Erwan Bousse (Nantes University)](https://bousse-e.univ-nantes.io/) is an Associate Professor at the University of Nantes (France). 
He obtained his PhD in France in 2015 at the University of Rennes 1 for his work on execution traces and omniscient debugging of executable models. 
He co-organized on multiple occasions the EXE, GEMOC, and MLE workshops at MODELS, and is a founder member of the MLE steering committee.
His current research interests include Software Language Engineering (SLE), Model-Driven Engineering (MDE), Domain-Specific Languages (DSLs), model execution and simulation, and the debugging and testing of models.

<img style="display: block; margin: auto;" alt="Faezeh Khorram photo" src="/editions/mle2022/images/faezeh.jpg">

[Faezeh Khorram (IMT Atlantique)](https://faezeh-kh.github.io/) is a PhD student at IMT Atlantique (France) and also a member of the Lowcomote European project.
As her PhD studies, she is working on advanced testing and debugging support for Executable Domain-Specific Languages (xDSL).
She was a visiting researcher (1) in the Department of Business Informatics – Software Engineering (WIN-SE) at JKU University (Linz, Austria) working on coverage computation and fault localization for executable models; and (2) in the Miso research group of Universidad Autónoma de Madrid (Madrid, Spain) working on test case generation, improvement, and selection for executable models.

<img style="display: block; margin: auto;" alt="Juha Pekka photo" src="/editions/mle2022/images/JuhaPekka.jpg">

[Juha-Pekka Tolvanen (MetaCase)](https://metacase.com/jpt.html) is the CEO of MetaCase and co-founder of the DSM Forum. 
He-Pekka holds a Ph.D. in computer science from the University of Jyväskylä, Finland (best national dissertation award 1999).
He has been involved in model-driven development and tools, notably metamodeling and code generators, since 1991. He has acted as a consultant worldwide for modeling language development, authored a book on Domain-Specific Modeling, and written over 80 articles for various software development magazines and conferences.
</div>

## Program committee


- Jeff Gray (University of Alabama),
- Thomas Degueule (CNRS),
- Jérémie Tatibouët (CEA),
- Marjan Mernik (University of Maribor),
- Federico Tomassetti (Strumenta),
- Sébastien Gérard  (CEA LIST),
- Daniele Dii Pompeo (University of L'Aquila),
- Ralf Lämmel (Universität Koblenz, Facebook London),
- Davide Di Ruscio (University of L’Aquila),
- Massimo Tisi (IMT Atlantique),
- Antonio Garmendia (JKU Linz),
- Antonio Garcia-Dominguez (Aston University),
- Bianca Wiesmayr	(JKU Linz).
<!-- - Edouard Batot (Universitat Oberta de Catalunya ), -->
<!-- - Stephanie Challita  (University of Rennes 1), -->
<!-- - Nicolas Rouquette (NASA's Jet Propulsion Laboratory (JPL)), -->
<!-- - Michalis Famelis (Université de Montréal), -->
<!-- - Dimitris Kolovos (University of York), -->
<!-- - Jean-Marie Mottu (Nantes University), -->
<!-- - Markus Voelter (Independent / itemis), -->