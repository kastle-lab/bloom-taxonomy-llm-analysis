# bloom-taxonomy-llm-analysis [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This repository contains code and data for evaluating small and large language models (LLMs) on the task of generating educational questions aligned with Bloom's Taxonomy. The evaluation considers semantic similarity, prompt complexity, and readability across multiple Bloom levels and topics.

## Project Overview
- **Goal:** Generate and evaluate Bloom's Taxonomy-aligned questions using LLMs, assessing their capabilities and performance across key quality metrics.
- **Models:** GPT, Mistral, LLaMA, PaLM, Deepseek, Gemma, Granite, Phi, and others — across two model size categories (small and large).
- **Prompts:** 5 prompt complexities per topic
- **Metrics:**
  - Prompt-to-question similarity
  - Readability
  - Semantic evaluation (e.g., BERTScore)

## License
 - This repository is licensed under the [MIT License](LICENSE).  
 - Portions of the data are reused under compatible MIT licensing from third-party sources.

## Attributions
This project includes data adapted from work by [Nicy Scaria](https://github.com/nicyscaria/AEQG_Blooms_Evaluation_LLMs), licensed under the [MIT License](third_party/LICENSE.nicy_scaria).