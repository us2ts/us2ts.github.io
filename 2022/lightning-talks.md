---
layout: page
title: Lightning Talks
author: Maulik R. Kamdar
permalink: /2022/lightning-talks
mainnav: false
sidenav: false
sidebartitle: Lightning Talks
published: true
order: 7
---

----------------------------------------------------------------

# A new Biodiversity and Ecology dataset {#biodiversity}

#### Speakers
- [Jen Hammock, Smithsonian Institution](https://orcid.org/0000-0002-9943-2342)
- [Katja Schulz, Smithsonian Institution](https://orcid.org/0000-0001-7134-3324)

#### Abstract

The Encyclopedia of Life integrates data connecting organisms, categorical attributes, environments, and geographic entities. This is stored natively as a property graph. A projection of the dataset simplifies the graph to taxa rather than individual organisms, and bundles records supporting the same relationship type between the same two entities. The provenance data in this projection is linked less directly, but the graph supports intuitive triples of the form:

Elkhorn_coral builds_habitat reef
or
mosquito feeds_on human

We are working on translating the projection into an RDF resource. We are in need of feedback on the semantic structure of the current draft.

The graph includes 2 million taxa, 1.2M linked to geographic entities, 800,000 linked to habitats, 600,000 linked to functional or ecological categories, and 200,000 linked to other taxa via ecological interactions. Taxa, geographic entities, attribute categorical values and habitats are hierarchically organized. Entities and relationships are identified using OBO Foundry ontologies, Wikidata, Geonames or specialist biodiversity thesauri wherever possible; where necessary, ad hoc terms are minted.

----------------------------------------------------------------

# Finding Correlation and Causation in Knowledge Graphs {#correlation-causation}

#### Speakers
- [Jans Aasman, Franz Inc.](https://franz.com)

#### Abstract

Franz is involved in a number of Knowledge Graph projects that capture real world events. For fairly obvious business purposes we would like to know in each of the domains the correlation and co-occurrence of certain events so, given an event X, we can predict the chance of event Y. In a healthcare Knowledge Graph we find significant correlations (and co-occurrence) between having HIV and being Bipolar, but what causes what? Why do we see that strange correlation?

In a Knowledge Graph around airplane repairs we find a high correlation between certain types of breakdowns, repairs and purchases that on first sight seem relatively unexplainable. There is no relationship between the part that breaks and the part that we have to purchase in the bill of material for the plane. So what causes what and why?

Finally, in the domain of call center interactions we find high correlations between 'product names' mentioned by the call center agent and 'product names' mentioned by the Customer. How does one trigger the other?

Based on the ideas in the "Book of Why" by Judea Pearl we came up with new techniques that will add the arrow of time to our analysis so that we actually start showing in a visual graph how one event might cause (and thereby predict) the other event.

----------------------------------------------------------------

# Heuristic evaluation of semantic search interfaces in bibliographic systems {#bibliographic}

#### Speakers
- [Jim Hahn, University of Pennsylvania](https://www.library.upenn.edu/people/staff/jim-hahn)

#### Abstract

This lightening talk will present a position statement and research agenda in the areas of user interface evaluation for semantic search interfaces in bibliographic systems. Within the community of bibliographic systems research, there has been growing interest and enthusiasm for connecting traditional library data within the graph structures of the semantic web. Classical library metadata is an expressive and highly specialized vocabulary rooted in descriptive and subject cataloging. Efforts to re-deploy this expressiveness for the semantic web are underway with transformation and enrichment of library data. Bibliographic systems researchers have also prototyped the development of semantic search interfaces that take advantage of graph based data. The Library of Congress is leading the development of the upper level bibliographic ontology BIBFRAME, aimed at supporting the discovery of library linked data on the web. While development of semantic interfaces based on BIBFRAME have been prototyped, there is a need to verify that new semantic search interfaces can meet traditional bibliographic tasks. The research agenda will seek to understand how semantic interfaces support library tasks that classical bibliographic systems support, specifically attributes of finding, identifying, selecting, obtaining and exploring by way of contextual search. A possible outcome of such a research area may include the articulation for best uses of semantic searching with contextual exploration relative to classic library record based (non-graph based) searches of named entity searching.

----------------------------------------------------------------

# Study Data Validation & Submission Conformance {#study-validation}

#### Speakers
- Tim Williams, UCB Biosciences Inc.

#### Abstract

Converting study data to Linked Data as Resource Description Framework (RDF) goes a long way toward improving data quality and flexibility. But the unique identifiers, semantic relationships, ontology-based schema, and integral metadata are just part of the equation. When validation rules are included in the data ecosystem, quality control spans the entire data life cycle from data collection all the way through to submission and reporting.

FDA Submission conformance checks can be represented using Shapes Constraint Language (SHACL), with a goal of replacing labor-intensive, manual validation processes performed by both study sponsors and regulatory agencies. Faster approvals will ensure patients receive treatment sooner.

----------------------------------------------------------------

# Semantic Awareness and Application in Chemical Hazard Assessment Workflow {#chemical-assessment}

#### Speakers
- Michelle Angrish, US EPA

#### Abstract

Semantic awareness in the form of controlled vocabularies and ontologies are a natural fit for literature-based chemical assessments deploying systematic review (SR) method workflows. This is because study methods and findings are almost exclusively recorded using written (and highly variable) natural language. While SR methods provide a mechanism for meeting the expectation that an assessment will include the most relevant and robust information, they also present a significant semantic challenge because linguistic variation can obscure concepts and relationships needed for information retrieval and interpretation. In order to maximize the potential of computationally intelligent approaches (i.e. artificial intelligence) and reap the benefits established by the Findable, Accessible, Interoperable, and Reusable (FAIR) data principles, controlled vocabularies and ontologies have been extended as an information digitization strategy in our chemical assessment space. In this lightening talk I will briefly touch upon the application of semantics in our chemical assessment workflows, including information transformation to controlled vocabularies, environmental health finding “ontologization”, ontology mapping, advances made, and challenges faced. The views and opinions expressed here are mine alone and do not reflect official US Environmental Protection Agency policy.

----------------------------------------------------------------

# Extending health intervention representation through annotations {#health-annotations}

#### Speakers
- Alexis McClimans

#### Abstract

This presentation will discuss current work being done at the Institute for Health Metrics and Evaluation (IHME) in representing and describing complex health interventions in context for the Cost-Effectiveness Meta-Regression (CEMR) team. The CEMR team’s work informs health policy by thorough analyses of costs, constraints, and cost-effectiveness of health interventions. Within the field of population health, there have been growing efforts towards standardization in classification of health interventions. Although classification schemes exist for representing health interventions, their coverage is either incomplete or targeted towards specific applications, which necessitated CEMR to establish a new standardized method for describing a given intervention. These efforts have resulted in the construction of the Health Interventions Taxonomy (HIT), a flat classification scheme, representing over 2000 complex health interventions.

My research is exploring the applicability of semantic web technology to enrich health intervention representations through the use of compositional annotations. HIT terms represent a combination of discrete components loosely aligning with an intervention target, action, and additional attributes. Through the use of unique identifiers and formal definition of relationships between terms, I hope to achieve greater granularity in CEMR’s ability to represent health interventions and their contexts.

----------------------------------------------------------------

# Extending RDF for Immutability {#rdf-immutability}

#### Speakers
- [Brian Platz](https://www.platz.me/)

#### Abstract

In this talk, Brian proposes we treat relationships and time as primary componentry to a semantic graph implementation, alongside RDF data. The ability for an application to leverage an immutable (time-stamped chronology of events) graph database gives way to a temporal lens for which systems can analyze information. Brian will speak about the benefits of Time Travel (query a state of a graph at a specific point in time), time-joins (the ability to "join" two states of a graph for deeper time-oriented analysis), and how SPARQL Query can leverage Time in a semantic knowledge graph.

----------------------------------------------------------------

# Using Semantic Technologies to Link Metagenomic Data for the National Microbiome Data Collaborative {#microbiome}

#### Speakers
- William Duncan
- Chris Mungall (Lawrence Berkeley National Laboratory)

#### Abstract

The National Microbiome Data Collaborative (NMDC) is a multi-organizational effort to enable integrated microbiome data across diverse areas in medicine, agriculture, bioenergy, and the environment. Using semantic technologies, we are developing a framework to fully leverage existing microbiome data science resources and high-performance computing systems available within the Department of Energy complex for data access, integration, and advanced analyses. This framework will enable NMDC collaborators to develop microbiome workflows for processing metagenomic, metatranscriptomic, metaproteomic, and metabolomic data.

----------------------------------------------------------------

# Secrets to using a graph database for data harmonization and analytics {#harmonization-analytics}

#### Speakers
- [Steven Sarsfield, Cambridge Semantics Inc.](https://www.linkedin.com/in/steve-sarsfield/)

#### Abstract

The extraordinary growth in complex data has left many enterprises struggling to create an integrated, comprehensive view of that data. The high level of technical acumen needed and the cost of managing and transforming massive amounts of disparate data, as well as the shortcomings of traditional data management solutions and architectures, has resulted in a significant underutilization of enterprise data for meaningful analytics and insight.

In recent years, knowledge graphs have emerged as a powerful tool for integrating large volumes of distributed, data, both structured and unstructured. A simplified graph data model available in graph databases helps enterprises achieve this goal in fewer steps and without locking into a single notion of the analytics needed.

In this session, learn how enterprises are using new OLAP technologies for diverse data harmonization and analytics at scale (trillions of triples & more), speed, and deep link insights – to accelerate complex, large-scale data integration initiatives, including those involving massive knowledge graphs.

----------------------------------------------------------------

# Semantic Knowledge Graphs for Machine Learning and Data Science {#mlkgds}

#### Speakers
- [Steven Sarsfield, Cambridge Semantics Inc.](https://www.linkedin.com/in/steve-sarsfield/)

#### Abstract

Increasingly machine learning is being applied to a variety of use cases. Data preparation and feature engineering continue to be a manual time-consuming process requiring significant IT involvement, data scientist expertise with limited governance. Knowledge Graphs are starting to be used to automate data preparation, data wrangling and feature engineering, provide rich context for increased insights, and improve governance. Learn why Knowledge Graphs and Graph Analytics are valuable and how companies are using Knowledge Graphs in machine learning and data science.

----------------------------------------------------------------

# Extend the SemWeb by providing High-Performance Analytics and RDF* {#semweb-analytics-rdf}

#### Speakers
- [Thomas Cook, AnzoGraph](http://AnzoGraph.com)

#### Abstract

Extend the functionality of your SPARQL endpoint by making it RDF* enabled and allowing high-performance analytics. Many SPARQL endpoints timeout when you try to perform any complex operation, even simple aggregations. Not anymore. Download the Free Edition of AnzoGraph DB to power your SPARQL endpoint and give your users the power of in-memory, MPP processing. Extreme Performance for both query and data loading. Want to add properties to edges and provide other advanced analytics capabilities? You can do that today with RDF* and the Free Edition of AnzoGraph DB. Containerized and ready to deploy in commercial applications on-prem or in the cloud. Completely free of charge for up to 16GB of RAM for processing. Download from: [http://AnzoGraph.com](http://AnzoGraph.com)

----------------------------------------------------------------

# Beware of Paving Cowpaths With Semantic Silos {#cowpaths}

#### Speakers
- [Michael Uschold, Semantic Arts](https://www.semanticarts.com/)

#### Abstract

Numerous modern day streets in downtown Boston defy logic – until you realize that the city fathers literally paved over the transit system that was used by cows. This gave the immediate benefit of getting places faster, while losing out on longer-term gains that designing a purpose-built street plan could have yielded. In the modern enterprise, replacing existing applications using semantic technology is paving more cowpaths. It recreates the very silos that semantic technology aims to get rid of. We'll tell you what to do instead.

----------------------------------------------------------------

# NIH Common Fund Metabolomics Consortium People Portal: Build a research graph and portal with open source tools {#metabolomics}

#### Speakers
- [Michael Conlon, University of Florida](http://vivo.ufl.edu/individual/mconlon)
- [Christopher P Barnes, University of Florida](http://vivo.ufl.edu/individual/cpb)
- [Kevin Hanson, University of Florida](http://vivo.ufl.edu/individual/kshanson)
- [Taeber Rapczak, University of Florida](http://vivo.ufl.edu/individual/taeber)
- [Hunter Jarrell, University of Florida](http://vivo.ufl.edu/individual/hunter.jarrell)
- [Alyssa Kelly, University of Florida](https://vivo.ufl.edu/display/n51363)

#### Abstract

The NIH Common Fund Metabolomics People Portal is a semantic application using open source components and the BFO-based VIVO ontology to build a portal and a research graph of activity in the field of metabolomics. Staring with metadata from the National Metabolomics Data Registry, the portal represents studies, datasets, people, labs, software tools, and papers with metadata from PubMed. The current graph represents over 1200 studies, 1300 investigators, and 17,000 papers dating back to 1977. The portal is used by investigators to find related work and data sets for analysis. The graph will be used by social network analysts to study the collaborative structure of the metabolomics community.

Metabolomics is the study of small molecules in tissue. Metabolomics is used to understand cell biology and disease mechanisms. The NIH Common Fund supports a consortium of 14 sites working to advance the technology of metabolite identification, and the application of metabolomics in biomedicine.

----------------------------------------------------------------

# Explaining AI Explainability: Building a Taxonomy of Explanation Types {#explainability}

#### Speakers
- Shruthi Chari, Rensselaer Polytechnic Institute
- Daniel Gruen, IBM Research, Cambridge
- Oshani Seneviratne, Rensselaer Polytechnic Institute
- Morgan Foreman, IBM Research, Cambridge
- [Amar K. Das, IBM](http://researcher.watson.ibm.com/researcher/view.php?person=us-amardas)
- [Deborah McGuinness, Rensselaer Polytechnic Institute](http://tw.rpi.edu/web/person/Deborah_L_McGuinness)

#### Abstract

The proliferation of machine learning (ML) techniques in healthcare and other critical applications has led to a renewed emphasis on developing explainable Artificial Intelligence (AI) models and systems. More specifically, there has been an increased emphasis on tackling explainability from user-centric perspectives. Traditionally, developments in explainable AI have reflected advances in AI, from early expert systems to current ML methods. For example, explanations in second-generation expert systems typically addressWhy, What, and How questions. With ML methods, explainability has focused on interpreting the functioning of black-box models, such as identifying the input features that are associated the most with different outputs. While these explanations of the mechanistic functioning of the AI model are important, a recent report by the National Academy of Medicine emphasizes the need for "enhanced explainability" that considers what needs to be explained and what models support it.

To begin to address the varied needs of explainability, mainly to allow explanations to be tailored differently to situations, contexts, and users' needs and preferences, we have begun to develop a taxonomy of explanation types. Prior efforts to define an explainable AI model or system exist, however, we are unaware of a comprehensive analysis of the breadth and styles of explanations. We have created such a synthesis drawn from literature in computer science, social sciences, and philosophy, and we have identified explanation types from a variety of settings in which explanations are desirable. In this review, we found a lack of consensus among the definitions of these explanation types. To address this ambiguity, we identified different explanation types from review papers, followed the embedded citations, and chose seminal papers defining the types.

Additionally, while explanations can be objectively defined and generated without user input, explainability is a subjective experience and the result of a continuous and co-adaptive process. Our taxonomy, is intended to help determine which explainability needs are relevant to specific types of users and settings. Further, aligning with the clinical focus of our Health Empowerment by Analytics, Learning, and Semantics (HEALS) project, we have defined a prototypical question from a clinical setting for each explanation type that they can address.

As a next step, we plan to build a semantic representation from the basis provided by our taxonomy of explanation types. We believe that a semantic representation would benefit upstream AI tasks, and would provide the ability to alter their explanation facilities to generate explanation types suited to their end-users' requirements and context.
We are also using our taxonomy to inform user studies that will assess which types of explanation are needed by the user and how to implement them within hybrid AI systems that use both ML and ontology-based reasoning. Finally, we argue that trustworthy and transparent AI systems will need to provide the appropriate explanations that support different forms of reasoning and are adapted to different user requirements. To this end, an understanding and representation of explanation types with varied strengths and focuses, such as the one we are building, will be useful.

# X3D Ontology for Semantic Web {#x3dontology}

#### Speakers
- [Don Brutzman](http://faculty.nps.edu/brutzman/brutzman.html), Naval Postgraduate School

#### Abstract

Extensible 3D (X3D) Graphics is the royalty-free open standard for publishing, viewing, printing and archiving interactive 3D models on the Web.  The [X3D Ontology for Semantic Web](https://www.web3d.org/x3d/content/semantics/semantics.html) provides terms of reference for semantic query of X3D models.

The X3D Semantic Web Working Group mission is to publish models to the Web using X3D in order to best gain Web interoperability and enable intelligent 3D applications, feature-based 3D model querying, and reasoning over 3D scenes.

Motivations
* Establish best practices for metadata and semantic information/relationships using X3D as a Web-based presentation layer.
* Enable authors to utilize the power of X3Dv4 and HTML5/DOM together in any Web page utilizing a family of specifications and practices provided by the Semantic Web, such as HTML5 Microdata (microformats) and Linked Open Data, (possibly) MPEG-7 and related references.
* Align the X3Dv4 specification with these standards as best possible to further enable the Digital Publishing industry and communities.
* Describe value proposition for utilizing semantic information in concert with archival export, publishing, visualization, and printing of any 3D model as X3D.
