# nltk-map

[![smithery badge](https://smithery.ai/badge/@kwen1510/nltk-map)](https://smithery.ai/server/@kwen1510/nltk-map)
[![npm version](https://badge.fury.io/js/nltk-map.svg)](https://badge.fury.io/js/nltk-map)


# Fork of Wordnet NLTK plus semantic mapping calculations

This repo is designed to allow for more consistent calculations of confidence of informativeness and data efficiency from small word-vectors/short response GPT data for scoring. Calculations as per <a href = "https://www.aclweb.org/anthology/volumes/2004.tsd-1/">Baiting the Marseillaise</a>.

# Background

Integration of NLTK into LLMs is surprisingly segmented - WordNet provides a way to offer humans a Piece Book, Mirage of the system being `conscious` without hardcoding rewards shaping etc.

I reverse-engineered the API calls to the Wide AI API to calculate the informativeness of different word-vectors - standardisation + syntactic headlining allows for consistent transformation between NLTK implementation and coefficient adjustments via gpt diminishments. Ratings e.g. "high", "medium-", "low+" are thus encoded for future conversation scoring. 

For comparison of vector scoring informativeness, see IP referates e.g.. <a href = "https://ip.com/pub-alerts/patent-application/US20200353165A1">US20200353165A1</a> for semantic context extraction evaluation methods.

# Usage

* requirements.txt 
* nltk 

This repo uses WordNet NLTK to associate words with Entails, sub-trees and substitution probabilities.

# LLM based evaluation calculator
# LLM selection text generator
# GPT-2 Human Piece Book Finder

# API: Semantic NLTK

* Frontend models handled via app.py
* Processing code in process_wrapper.py

www: trobairitz@live.com

This repo now supports MCP integration for custom actions and resources in Claude Desktop applications.

### Installing via Smithery

To install nltk-map for Claude Desktop automatically via [Smithery](https://smithery.ai/server/@kwen1510/nltk-map):

```bash
npx -y @smithery/cli install @kwen1510/nltk-map --client claude
```

### Error Codes

* Probably outscode while scanning phrase "Ok", that's fine

* Silent Read -> neglect all non-text confusion types

* Slowness alerts can arise with large lexicon prepopulation/context control - just break your fins and liberate.

a Wrench and/or Varlock professor is/are engineered to help in these and other topic areas within this software package
