# Hebrew-Paraphrase-Dataset
This repository contains a paraphrase dataset in Hebrew, consisting of 9,750 instances. The dataset includes both paragraph-level and sentence-level paraphrases, generated with the help of a large language model (LLM).

## Dataset Overview

- **Total Instances:** 9,750
- **Structure:** 
  - **75%** are paragraphs (7,313 instances)
  - **25%** are sentences (2,438 instances)
- **Genres/Sources:** The dataset covers a variety of text types:
  1. **Wikipedia** – Encyclopedic texts
  2. **Geektime** – Technological-news texts
  3. **Knesset** – Spoken language, dialogue, and protocol texts
  4. **Kol Zchut** – Legal language texts
  5. **Summaries** – Summeries from various sources

## Gold-Standard Subset

- **Gold Instances:** 300 instances have been manually validated by a linguist to ensure high quality.

## Data Format

Each instance in the dataset typically contains:
- **Original Text:** The source text.
- **Paraphrase:** A generated paraphrase of the original text.
- **Source:** Genre/Source (For Example: Wikipedia).
- **Type:** sentence/paragrph.
- **Gold:** indicate whether the instance is part of the gold-standard subset.

