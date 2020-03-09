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

#### Survey
**Please fill out the post-session survey at [https://tinyurl.com/us2ts-tools](https://tinyurl.com/us2ts-tools)**

#### Description

Do you develop tools, libraries, or other resources that are intended to enable, broaden, or apply semantic web technologies? Are you interested in raising the community’s awareness of them? Do you build (semantic web or not) applications (re)using such resources, and have a story to tell? Or have you tried building such applications and discovered shortcomings in the current tool or library ecosystem?

If your answer is yes to any of the above, this session aims to foster community awareness of existing resources based on semantic web technologies, and to facilitate the exchange of know-how and common gaps or limitations in current tooling.

A full description can be found here: Hilmar Lapp, Rafael Gonçalves. Fostering an awesome tool ecosystem for the semantic web. Authorea. January 03, 2020. DOI: <https://doi.org/10.22541/au.157807505.51352689>

#### Session program

The lightning talk part of the program will consist of the following presentations (order remains tentative; submissions are now closed):

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

- **Paul Cuddihy, Jenny Weisenberg Williams, Varish Mulwad, Kareem S. Aggour (GE): [SemTK](http://semtk.research.ge.com): An Ontology-first, Open Source Semantic Toolkit for Managing and Querying Knowledge Graphs**

  We present SemTK, the Semantics Toolkit, a user-friendly suite of tools and services that allow both expert and non-expert semantics users convenient ingestion of relational data, visual query generation, and more.  Once queries have been built using the drag-and-drop editor in SPARQLgraph, they can be saved into a service layer.   Applications can then access queries by name and perform a number of functions via REST calls.  These include retrieving a list of runtime constraints and lists of legal values for each, and applying constraints to the query, thus supporting dropdown menus and filters without requiring application developers to have any experience with semantic web technologies.  The exploration of ontologies and instance data is performed through SPARQLgraph, an intuitive web-based user interface in SemTK understandable and navigable by a lay user. 

  SemTK has been under continuous development and use within GE for over 5 years and is available at https://github.com/ge-semtk/semtk under a the Apache 2 license.  Inside GE, it also includes ontology-based data access features which are scheduled to be released under the same license later in 2020.   These features allow the same query interface to generate REST calls to external data sources and seamlessly fold the results in with the SPARQL results.  SemTK is designed to work with any SPARQL1.1 compliant datastore, and has been used successfully with Fuseki, Virtuoso, and Neptune.

- **Chris Mungall (Lawrence Berkeley Laboratory): [SparqlProg](https://github.com/cmungall/sparqlprog): Modular Logic Programs for the Semantic Web**

  Logic programs (LPs) provide a way to combine data access, inference, and programming in a declarative fashion. SPARQLProg is a framework that allows for compilation and interpretation of LPs to federated SPARQL queries, allowing for  compositionality (it's currently hard to reuse logic from one SPARQL query  in another) and natural weaving of query + program (no impedance mismatch). It has modules and LP fragments for common bio triplestores and vocabs e.g  Wikidata, RHEA, GO + FALDO. The SparqlProg frameworks also includes a Docker container for running a server, and Python bindings.

- **John Graybeal, Martin O'Connor, Marcos Martinez Romero, Attila Egyedi, Mark Musen (Stanford University): [CEDAR](https://metadatacenter.org): Awesome Metadata Sauce**

  The Center for Expanded Data Annotation and Retrieval (CEDAR) was established in 2014 to create a computational ecosystem for development, evaluation, use, and refinement of biomedical metadata. This lightning talk will cover not just what CEDAR can do, but what makes it truly awesome.

  Our approach uses metadata templates, which define the data elements needed to describe particular topics, like biomedical experiments. The templates support controlled terms for establishing field relations and filling out field values.  CEDAR uses a library of such templates to help scientists submit annotated datasets to appropriate online data repositories. We built a framework that supports robust semantic metadata entry for any model, supporting both general and discipline-specific metadata. 

  CEDAR supports end-to-end metadata processes:
  * community-based organizations collaborating to create metadata templates,
  * investigators or curators using the templates to define metadata for their digital assets,
  * scientists searching the metadata to access and analyze the online assets.

  An important feature of the system is the use and development of controlled knowledge resources—ontologies, value sets, vocabularies, common data elements (CDEs), and others—that are appropriate for different disciplines and types of research. We build on existing ontologies, such as the Unified Medical Language System, and using BioPortal also enable users to discover, create, and manage their own knowledge resources.

  The consistent use of controlled terminology aids researchers searching for data. Not only will searches be able to find the common terms that have been suggested as the metadata is created, those terms can be related to other concepts using semantic technologies, and searches can leverage those relationships to identify other related materials.
