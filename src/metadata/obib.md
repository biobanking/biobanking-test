---
layout: ontology_detail
id: obib
title: biobanking test
jobs:
  - id: https://travis-ci.org/biobanking/biobanking-test
    type: travis-ci
build:
  checkout: git clone https://github.com/biobanking/biobanking-test.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: biobanking test is an ontology...
domain: stuff
homepage: https://github.com/biobanking/biobanking-test
products:
  - id: obib.owl
  - id: obib.obo
dependencies:
 - id: obi
 - id: ro
tracker: https://github.com/biobanking/biobanking-test/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
