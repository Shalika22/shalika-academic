---
title: "Text-to-SQL Generation with LLMs"
summary: "Dual-model LLM pipeline for accurate Text-to-SQL generation"
tags:
  - NLP
  - LLM
  - Development
date: 2024-11-01

image:
  caption: 
  focal_point: "Smart"

url_code: ""
---

- Designed a dual-model pipeline using a small LLM for schema-aware skeleton generation and a larger LLM for final SQL query synthesis
- Improved zero-shot performance over single-model baselines on Spider 2.0 and NLText2SQL benchmarks
- Reduced query errors by structuring generation into intermediate representations
