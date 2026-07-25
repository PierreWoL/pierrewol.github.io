---
layout: page
title: Taxonomy Inference for Tabular Data
description: Contrastive representation learning and generative hierarchy construction.
importance: 2
category: research
related_publications: true
---

This work studies how to discover entity types in collections of tables and
organise them into useful hierarchies without relying on a pre-existing
ontology.

**EmTT** fine-tunes encoder language models with contrastive learning before
hierarchical clustering. **GeTT** uses decoder-only LLMs with iterative,
top-down Chain-of-Layer prompting. Evaluation across three real-world datasets
showed strong consistency with ground-truth taxonomies; contrastive fine-tuning
improved Rand Index by 10% and Purity by 18%.

**Stack:** Python, PyTorch, Transformers, contrastive learning, hierarchical clustering  
**Code:** [PierreWoL/TwoMethods](https://github.com/PierreWoL/TwoMethods)  
**Paper:** [ESWC 2025](https://doi.org/10.1007/978-3-031-94575-5_22)
