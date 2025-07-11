# PudMed-Python

# papersfetcher

## Overview
Fetch research papers from PubMed, and list those with authors from pharmaceutical/biotech companies.

## Installation
```bash
poetry install

Biopython: https://biopython.org/

Poetry: https://python-poetry.org/


poetry run get-papers-list "cancer treatment" -f output.csv



**Overview & design**


A Python module (e.g., papersfetcher)

A CLI script (e.g., get-papers-list) that uses the module

Use PubMed’s Entrez API (via Biopython or requests)

Identify non-academic authors by checking affiliations for words like:

scss

university, institute, college, hospital, center, lab, laboratory
