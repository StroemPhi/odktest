---
layout: ontology_detail
id: odktest
title: ODK test ontology
jobs:
  - id: https://travis-ci.org/pstroem/odktest
    type: travis-ci
build:
  checkout: git clone https://github.com/pstroem/odktest.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: ODK test ontology is an ontology...
domain: stuff
homepage: https://github.com/pstroem/odktest
products:
  - id: odktest.owl
    name: "ODK test ontology main release in OWL format"
  - id: odktest.obo
    name: "ODK test ontology additional release in OBO format"
  - id: odktest.json
    name: "ODK test ontology additional release in OBOJSon format"
  - id: odktest/odktest-base.owl
    name: "ODK test ontology main release in OWL format"
  - id: odktest/odktest-base.obo
    name: "ODK test ontology additional release in OBO format"
  - id: odktest/odktest-base.json
    name: "ODK test ontology additional release in OBOJSon format"
dependencies:
- id: bfo
- id: ro
- id: omo
- id: obi
- id: chmo
- id: apollo_sv

tracker: https://github.com/pstroem/odktest/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
activity_status: active
---

Enter a detailed description of your ontology here. You can use arbitrary markdown and HTML.
You can also embed images too.

