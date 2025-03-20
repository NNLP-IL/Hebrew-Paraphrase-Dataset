# Hebrew Paraphrase Dataset

This repository contains a high-quality paraphrase dataset in Hebrew, consisting of **9785 instances**. The dataset includes both paragraph-level (75%) and sentence-level (25%) paraphrases generated with the help of a large language model. Among these, **300 instances** have been manually validated as gold standard examples.

## What Is a Paraphrase?

A *paraphrase* is a restatement of a text using different words and structures while preserving the original meaning. 

## Dataset Overview

Our dataset is designed to cover a wide range of text genres. It includes material from various domains such as encyclopedic entries, legal and conversational texts, news, and more.

## Automatic Quality Control

To ensure high quality, we applied several automatic filtering procedures:
- **Language Consistency:** We removed any paraphrases containing code switching to a language other than Hebrew.
- **Length Requirements:** Very short paraphrases relative to the original text were filtered out.
- **Generation Failures:** Instances where the model refused or failed to generate a paraphrase were excluded.
- **Similarity Check:** Paraphrases that were too similar to their source texts — thus not providing true rewording — were also removed.

## Gold-Standard Subset

- **Gold Instances:** 300 instances have been manually validated by a linguist to ensure high quality.

## Data Format

Each instance in the dataset includes:
- **Original Text:** The source text.
- **Paraphrase:** A generated paraphrase of the original text.
- **Type:** sentence/paragrph.
- **Gold:** indicate whether the instance is part of the gold-standard subset.
