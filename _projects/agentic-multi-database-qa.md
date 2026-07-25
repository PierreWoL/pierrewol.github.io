---
layout: page
title: Agentic Multi-Database Question Answering
description: Schema linking, structured reasoning, and Text-to-SQL across heterogeneous databases.
importance: 3
category: research
---

Current work on an agentic data-analysis system that answers questions spanning
multiple databases. The system decomposes a request, identifies relevant
databases, tables, and attributes, produces structured intermediate decisions,
and coordinates Text-to-SQL execution.

Using Qwen2.5-14B with tool calling and constrained outputs improved
schema-matching performance by 20% in ongoing experiments. Modular validation
and evaluation components make linking failures traceable and support reliable
execution over heterogeneous schemas.

**Stack:** Python, Qwen2.5-14B, LangChain, LangGraph, SQL, structured outputs
