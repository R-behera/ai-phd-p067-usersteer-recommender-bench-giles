# Unique Prototype Algorithm

## Algorithm

**GilesCausalInformationRetrievalRankAgent** (`P067-Giles-InformationRetrieval`)

## Professor Alignment

- Professor: C. Lee Giles
- Research area: Information retrieval, search engines, digital libraries, deep learning
- Focus terms: Information retrieval, search engines, digital libraries

## Core Mechanism

This prototype prioritizes ranking cases where relevance, evidence, and controllability diverge.

## Decision Rule

Rank seed cases by retrieval-specific priority score with Giles-aligned focus term 'Information retrieval'.

## What The Code Adds

- A unique algorithm spec in `src/proposed_method.py`.
- A scoring function for the repo's `retrieval` data schema.
- A ranked list of cases that should be reviewed, repaired, reproduced, or expanded first.
- Integration into `src/value_add.py`, so demo output includes the proposed method.

## Honest Status

This is a runnable algorithmic prototype. It is not a validated contribution to C. Lee Giles's published work until the seed data is replaced with real public/lab-relevant data and the resulting claims are evaluated.

## Run

```bash
python src/proposed_method.py
python src/value_add.py --write-report reports/demo_results.json
python -m unittest discover -s tests
```
