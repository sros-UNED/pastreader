# Beyond Traditional OCR: Exploring the Efficiency of LLMs in Document Processing

## Authors

- Antonio Narbona<sup>1,†</sup>  
  Universidad de Alcalá de Henares (UAH), Spain. Centro de Estudios Universitarios Ramón Areces  
- Salvador Ros<sup>2,*,†</sup>  
  Universidad Nacional de Educación a Distancia (UNED), Spain  

---

## Overview

This repository supports the research presented in the article  
**_Beyond Traditional OCR: Exploring the Efficiency of LLMs in Document Processing_**,  
which investigates and compares two OCR architectures for historical document transcription:

1. A traditional, **multi-stage pipeline** architecture combining preprocessing, OCR engines, fusion mechanisms, and postprocessing.
2. A **streamlined, LLM-based architecture** using large language models as the sole recognition engine.

---

## Abstract

This work explores two distinct OCR architectures for historical document processing, comparing a complex, multi-stage pipeline with a streamlined approach based solely on large language models (LLMs). Our findings demonstrate that the LLM-based architecture significantly outperforms the more traditional, complex systems, achieving superior accuracy with lower Character and Word Error Rates (CER and WER). The results highlight that, without the need for supplementary preprocessing or fusion steps, LLMs represent the current state-of-the-art in OCR, offering both high precision and efficiency. This approach marks a new era in historical document transcription, establishing LLMs as the most effective solution for heritage digitization workflows in the digital humanities.

---

## Conclusions

- A **tiered evaluation** confirmed that each stage of the traditional pipeline—preprocessing, fusion, and postprocessing—contributed incrementally to accuracy, but at the cost of complexity.
- The **LLM-only architecture** (using Gemini 2.5 Pro) **matched or surpassed** the performance of the more complex system across nearly all test cases.
- **Character Error Rates (CER) consistently fell below 2%**, and **Word Error Rates (WER) remained between 4% and 8%**, even without auxiliary steps.
- A notable exception occurred in a complex two-column layout, where a structural misalignment slightly degraded LLM output—correctable via minimal postprocessing.
- The results validate **LLMs as viable, standalone OCR solutions** capable of delivering state-of-the-art results with minimal configuration, marking a methodological shift in heritage digitization.
- The study advocates for a **modular yet adaptive design philosophy** in document processing workflows, aligning model capabilities with the specific needs of each task.

---
