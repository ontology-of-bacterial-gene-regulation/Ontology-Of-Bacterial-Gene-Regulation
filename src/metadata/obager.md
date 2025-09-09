---
layout: ontology_detail
id: obager
title: Ontology of Bacterial Gene Regulation
jobs:
  - id: https://travis-ci.org/ontology-of-bacterial-gene-regulation/Ontology-Of-Bacterial-Gene-Regulation
    type: travis-ci
build:
  checkout: git clone https://github.com/ontology-of-bacterial-gene-regulation/Ontology-Of-Bacterial-Gene-Regulation.git
  system: git
  path: "."
contact:
  email: citlalli.mejiaalmonte@gmail.com
  label: Citlalli Mejía Almonte
description: Ontology of Bacterial Gene Regulation is an ontology...
domain: stuff
homepage: https://github.com/ontology-of-bacterial-gene-regulation/Ontology-Of-Bacterial-Gene-Regulation
products:
  - id: obager.owl
  - id: obager.obo
dependencies:

tracker: https://github.com/ontology-of-bacterial-gene-regulation/Ontology-Of-Bacterial-Gene-Regulation
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here

The Ontology of Bacterial Gene Regulation (OBAGER) is an ontology developed to formally represent the concepts and relationships underlying bacterial gene regulation. It translates expert-reviewed definitions of promoters, transcription units, transcription factors, and related entities into formal OWL axioms, enabling logical consistency and future integration with FAIR data initiatives.

Unlike instance-based models, OBAGER focuses on TBox-level definitions: necessary and sufficient conditions are defined at the class level to capture our best current understanding of regulatory biology. These definitions are provisional but expert-informed, designed to be transparent and extensible as new biological evidence emerges.