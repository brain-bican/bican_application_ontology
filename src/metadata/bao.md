---
layout: ontology_detail
id: bao
title: BICAN Application Ontology
jobs:
  - id: https://travis-ci.org/brain-bican/bican_application_ontology
    type: travis-ci
build:
  checkout: git clone https://github.com/brain-bican/bican_application_ontology.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: BICAN Application Ontology is an ontology that represents research, subjects of research, and the results of research in BICAN. It is a link between scientific knowledge gained through experimentation and the distribution/dissemination of that knowledge. It aims to help scientists annotate data and communicate about their work by defining a set of terms relevant to BICAN efforts. 
domain: BRAIN Initiative Cell Atlas Network entities
homepage: https://github.com/brain-bican/bican_application_ontology
products:
  - id: bao.owl
    name: "BICAN Application Ontology main release in OWL format"
  - id: bao.obo
    name: "BICAN Application Ontology additional release in OBO format"
  - id: bao.json
    name: "BICAN Application Ontology additional release in OBOJSon format"
  - id: bao/bao-base.owl
    name: "BICAN Application Ontology main release in OWL format"
  - id: bao/bao-base.obo
    name: "BICAN Application Ontology additional release in OBO format"
  - id: bao/bao-base.json
    name: "BICAN Application Ontology additional release in OBOJSon format"
dependencies:
- id: cob
- id: obi
- id: ro
- id: cl
- id: omo

tracker: https://github.com/brain-bican/bican_application_ontology/issues
license:
  url: http://creativecommons.org/licenses/by/4.0/
  label: CC-BY-4.0
activity_status: active
---
