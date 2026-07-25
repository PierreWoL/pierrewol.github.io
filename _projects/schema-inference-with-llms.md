---
layout: page
title: Schema Inference with Large Language Models
description: Turning heterogeneous table repositories into concise conceptual schemas.
importance: 1
category: research
related_publications: true
---

Minimally curated table repositories often contain inconsistent representations
and little metadata. This research develops encoder- and decoder-based methods
that infer entity types, conceptual attributes, hierarchies, and cross-type
relationships directly from headers and cell values.

The systems combine self-supervised representation learning, hierarchical
clustering, prompt-based inference, and structured validation. Across real-world
web-table and open-data collections, they improved F1/Recall by 30–40% and Rand
Index by 7–10% over prior approaches.

**Methods:** EmSI, GeSI, and SI-LLM  
**Stack:** Python, PyTorch, Hugging Face Transformers, vLLM  
**Code:** [EmSI and GeSI](https://github.com/PierreWoL/SILM) ·
[SI-LLM](https://github.com/PierreWoL/SILM/)
