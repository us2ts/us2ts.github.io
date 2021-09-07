---
layout: page
title: Session - JSON-LD as an On Ramp to the Semantic Web
author: Maulik R. Kamdar
permalink: /2022/program-jsonld
mainnav: false
sidenav: false
published: true
order: 5
---

#### Session Organizers

- Harold Solbrig (Johns Hopkins University) and
- Dazhi Jiao (Johns Hopkins University)

#### Abstract

At its core, JSON Linked Data (JSON-LD) is just one more RDF serialization format that, at first glance, has little to add to an already long list of existing RDF serializations, including RDF-XML, N3, NQuads, NTriples, Turtle, RDFa, etc.  A “vanilla” (expanded) JSON-LD document brings little new to the table – it is not the most concise, readable, nor easy to work with.  JSON-LD, however, has an added feature, its “special sauce”, which allows developers to continue to work use the everyday JSON that comprises the backbone of the modern web while, under the covers, manipulating with the key features of Linked Open Data (LOD) and the semantic web.

The JSON-LD context specifies a set of mapping rules that translate between JSON objects and their component names and values and URI’s, data types, language identifiers and RDF collection idioms.  JSON-LD context can be maintained as a completely separate artifact, serving both the role of a JSON to RDF syntax transformation tool and a mechanism to assign semantics to bare JSON elements and values.

The original JSON-LD 1.0 specification, released in January of 2014, opened the door to a wealth of possibilities, but, as often the case with new ideas, led to a better understanding of the problem space and yielded an extended set of requirements.  The JSON-LD 1.1 specification was released as a W3C Committee Draft (CD) in December 2019 and provided a number of much needed enhancements including JSON path specific context maps, the ability to transform between data values and JSON keys, and the ability to maintain language specific value.  The JSON 1.1 specification also suggests approaches to applying JSON-LD to emerging alternatives to the JSON format, such as YAML.

JSON-LD transformations are fully bidirectional.  With a couple of minor exceptions, one can create data in JSON and apply a context to transform it to RDF.  One can also take RDF from a SPARQL source or an RDFa annotated source and transform it into JSON.

This presentation will start with a description of the basic JSON-LD RDF syntax, and will how an arbitrary RDF graph can be represented in its expanded JSON-LD form.  It will then touch on the JSON-LD framing language which, amongst other things, specifies how an arbitrary RDF graph structure should be mapped into the rooted hierarchy inherent in the JSON model.  The talk will then dive into the JSON-LD context, explaining the various mapping elements and demonstrating their application and use.
