
# Corpus Text Processing and Analysis

This project provides a framework for cleaning, processing, and analyzing a corpus of text, focusing on word and character frequency analysis. The steps involve cleaning the corpus, counting sentences, words, and characters, and performing unigram, bigram, and trigram analysis with frequency plots.

## Table of Contents
- [Overview](#overview)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
  - [Phase 1: Corpus Cleaning and Sentence Analysis](#phase-1-corpus-cleaning-and-sentence-analysis)
  - [Phase 2: Word and Character Count, Frequency Analysis](#phase-2-word-and-character-count-frequency-analysis)
  - [Phase 3: Character N-gram Frequency Analysis](#phase-3-character-n-gram-frequency-analysis)
- [Dependencies](#dependencies)

## Overview
This project reads a text corpus from an XML file, cleans and processes it by removing unnecessary symbols and whitespace, and analyzes the data to generate useful insights, such as:
- Number of sentences, words, and characters
- Unigram, bigram, and trigram word and character frequency
- Distribution of word lengths
- Zipf’s Law visualization using unigram word frequencies

## Setup and Installation

### 1. Clone the Repository:
```bash
git clone https://github.com/yourusername/corpus-analysis.git
cd corpus-analysis
