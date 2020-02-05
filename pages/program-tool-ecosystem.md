---
layout: page
title: Session - Fostering an awesome tool ecosystem for the semantic web
author: Maulik R. Kamdar
permalink: program-tool-ecosystem
mainnav: false
sidenav: false
published: true
order: 5
---

#### Session Organizers
- [Hilmar Lapp, Duke University](https://orcid.org/0000-0001-9107-0714) 
- [Rafael Gonçalves, Stanford University](https://www.rsgoncalves.com/)

#### Description

Do you develop tools, libraries, or other resources that are intended to enable, broaden, or apply semantic web technologies? Are you interested in raising the community’s awareness of them? Do you build (semantic web or not) applications (re)using such resources, and have a story to tell? Or have you tried building such applications and discovered shortcomings in the current tool or library ecosystem?

If your answer is yes to any of the above, this session aims to foster community awareness of existing resources based on semantic web technologies, and to facilitate the exchange of know-how and common gaps or limitations in current tooling.

We continue to invite contributions in the form of short (5-10 minutes) presentations, in particular for _awesome_ software tools and libraries, and for experiences with building end-user applications. _The meaning of awesome includes, but is not limited to, openly available, reusable resources that are potential building blocks contributing to an interoperable ecosystem._ [Submit your presentation](https://forms.gle/DkVnJ2qgjH1bB4ru7), review is rolling — acceptance is first-come, first-served until all allocable time for the session is used up. (At least one of the authors needs to attend and be able to present.)

A full description can be found here: Hilmar Lapp, Rafael Gonçalves. Fostering an awesome tool ecosystem for the semantic web. Authorea. January 03, 2020. DOI: <https://doi.org/10.22541/au.157807505.51352689>

#### Session program

The program below is developing; note that submissions currently remain open.

- **James A. Overton and Rebecca Jackson (Knocean Inc.): Ontology Automation with [ROBOT](http://robot.obolibrary.org)**.

  ROBOT is open source software for automating ontology development tasks. Building on OWLAPI, Apache Jena, and other Semantic Web tools, ROBOT provides a library of common ontology operations for use with any JVM-based language, and a convenient command-line interface to run these operations. ROBOT commands include: annotate, convert, diff, explain, extract, filter, materialize, merge, mirror, python, query, reason, reduce, relax, remove, rename, repair, report, template, unmerge, validate, and verify. These commands can be chained together and orchestrated with build tools such as GNU Make to create powerful automated workflows for ontology use, development, quality control, and release. While ROBOT is designed to support the best practises of the Open Biological and Biomedical Ontologies (OBO) community, and is used by dozens of OBO projects, most operations are generally applicable to any OWL ontology or RDF resource that makes use of OWL. In this presentation we give an overview of ROBOT, highlighting key features and use cases for the Semantic Web community.

- **Cogan Shimizu (Kansas State University): Graphical Ontology Modeling with [CoModIDE](https://comodide.com)**

  Ontology engineering is traditionally a complex and time-consuming process, requiring an intimate knowledge of description logic and predicting non-local effects of different ontological commitments. Pattern-based modular ontology engineering, coupled with a graphical modeling paradigm, can help make ontology engineering accessible to modellers with limited ontology expertise. We have developed CoModIDE, the Comprehensive Modular Ontology IDE, to develop and explore such a modeling approach.

- **Tomasz Pluskiewicz (Zazuko GmbH): [RDFine](https://github.com/tpluscode/rdfine) - idiomatic interface to graph data**

  For many years which I have spent working with Semantic Web technologies I missed a good abstraction which can bridge the native language features with the unique model of Resource Description Framework.

  So far I have made two attempts at a high-level tool for .NET and an internal piece of software for my JavaScript Hydra client. All of them, along with some other I witnessed share a common flaw that they tried very hard to detach themselves from the underlying RDF model.

  This time I propose something different. I want code which resembles native JavaScript objects but directly attaches itself tightly to the dataset. This way existing native tools can be leveraged yet at the same time specialised RDF code can be executed on the very same data structure.

  All made possible thanks to the awesome RDF/JS specification and a simple graph traversal library by my colleague Thomas Bergwinkl.

- **James P. Balhoff (Renaissance Computing Institute, University of North Carolina at Chapel Hill): [Whelk](https://github.com/balhoff/whelk), an OWL EL reasoner supporting parallel DL queries and immutable reasoning states**

  Whelk is an OWL EL reasoner with additional support for a subset of SWRL. Whelk is largely based on the reasoning algorithm used by the widely used ELK reasoner. However, the implementation of Whelk is designed to support use cases requiring the ability to preserve and reuse past reasoning states. Such use cases include: (1) Preclassifying a large Tbox at application startup—a possibly time consuming operation—then independently continuing reasoning with any number of independent Aboxes (e.g., supporting a multi-user instance graph editing application); and (2) Computing a very large number of DL queries in parallel in order to materialize inferences into a triplestore; Whelk's immutable reasoning state allows it to answer concurrent DL queries extremely quickly. Whelk's SWRL support provides a combination of OWL EL and RL reasoning at the instance level and supports Abox realization. Whelk is well suited to applications using a purely functional programming style. Whelk is implemented in Scala, runs on the JVM, and provides an implementation of the Java OWL API reasoner interface.

- **Harold Solbrig (Johns Hopkins University): [Funowl](https://github.com/hsolbrig/funowl) -- A OWL Functional Authoring Library for Python**

  There is not what one would term “a wealth” of Python based tools for OWL.  So far, this has been more or less OK, as the combination of published API’s, such as the OWL API and cross-language bridges like Py4J have allowed users to accomplish most of what is needed.  One glaring gap, however, is the ability to author OWL in Python – to directly transform models, assertions and knowledge from other idioms to (and from) an OWL representation.  To date, the Python developer is faced with a daunting choice - either create a textual representation of the OWL target or to attempt to emit an RDF representation of the target OWL using rdflib or a similar tool.  The textual representation of OWL embodies a steep learning curve and error checking and validation requires feeding the output into another tool such as Protégé.  The RDF representation presents an even steeper learning curve and results in code that, even in the best of cases, is so opaque as to be unreadable.

  The Functional OWL (funowl) library was created to address this problem.  It uses a near-literal translation of the OWL Functional Syntax into  Python to implement an OWL Functional syntax serializer,  loader, an  RDF  serializer as well as an evolving library of “syntactic sugar” to mask some of the more gnarly details under the cover.   This talk describes the goals of the funowl library, including clarifying what it is not, provides a couple of working examples and finishes with a summary of the current state and next steps.

- **James P. Balhoff (Renaissance Computing Institute, University of North Carolina at Chapel Hill): [Owlery](https://github.com/phenoscape/owlery), a JSON-LD-based REST API for description logic queries**

  Owlery is a web service application providing a REST interface to description logic queries. Owlery can support any OWL reasoner that works with the Java OWL API. Owlery handles standard queries, such as for subclasses, superclasses, and instances for either named classes or anonymous class expressions. By supporting reasoner-driven class expression queries, Owlery complements the capabilities of a SPARQL endpoint provisioned with the same ontologies. Furthermore, Owlery accepts SPARQL queries containing embedded DL queries, executing and expanding the DL queries into FILTER statements before the SPARQL query is submitted to a triplestore. Owlery results are returned in a JSON-LD format.

- **Rafael Gonçalves (Stanford University): [WebProtégé](https://webprotege.stanford.edu) -- Collaborative Ontology Editing in the Cloud**

  We present WebProtégé, a tool to develop ontologies represented in the Web Ontology Language (OWL). WebProtégé is a cloud-based application that allows users to collaboratively edit OWL ontologies, and it is freely available for use at https://webprotege.stanford.edu.  WebProtégé currently hosts more than 70,000 OWL ontology projects and has over 50,000 user accounts. In this talk, we will present the main new features of the latest version of WebProtégé.
