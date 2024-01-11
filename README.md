# NLP Information Extraction from Speech
## Introduction
Author: Zheng Zheng
Email: zheng.zheng2@northeastern.edu
Submission Date: 12/09/2023

This project explores advanced Natural Language Processing (NLP) techniques for extracting meaningful information from spoken language. The primary source material is a YouTube video, with the aim of converting speech to text, performing Named Entity Recognition (NER), dependency parsing, and visualizing the data for comprehensive analysis.

## Objective
The project's goal is to transform speech into text, preprocess the text data, perform NER, engage in dependency parsing, extract pivotal information, and effectively visualize this data.

## Methodology
### Data Collection:
Tools: Pytube library and OpenAI Whisper library
Process: Extracting audio information from a YouTube video and converting it to text.
### Text Preprocessing:
Tools: Re library and Flair library (SentenceSplitter)
Process: Cleaning and tokenizing the text data, removing filler words.
### Named Entity Recognition (NER):
Tools: 'ner-fast' model
Entities: Extraction of names of organizations, locations, and miscellaneous data.
### Dependency Parsing:
Tools: spaCy 'en_core_web_sm' model
Outcome: Analysis of sentence structures, identifying subjects, verbs, and objects.
### Information Extraction:
Tools: REBEL model
Process: Extracting relations from model output and compiling them into a knowledge base.
Data Visualization:

### Visualization Techniques: NetworkX and Matplotlib libraries.
Creation of a knowledge graph to depict the relationships between various entities.
## Results and Discussion
The project successfully converted speech to text, extracted significant entities, and analyzed their complex interrelationships. The primary focus was on electric vehicles (EVs), especially on brands like BYD and AUTO. A notable observation from the filtered knowledge graph was the close relation between entities like 'BYD cars' and 'my BYD', suggesting an area for future enhancement in entity recognition algorithms.

## Conclusion
This NLP project effectively demonstrates the synergy of combining diverse techniques such as speech-to-text conversion, NER, dependency parsing, and data visualization in extracting and analyzing information from spoken language.
