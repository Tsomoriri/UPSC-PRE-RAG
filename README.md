# UPSC-PRE-RAG
RAG application which applies inherent logical tricks to solve UPSC CSE prelims questions.

## Custom Dataset
A dataset of UPSC CSE Prelims [2013:2021] was created for this purpose.

## Observations

- Both gemma-2b-it and Hermes 2 pro seems to be trained on UPSC answers as they were able to identify the context directly.
- Retrieval of the context rather reduced hallucination with different seeds.

## Usage
```
Run data_processing.py to get dataset
Run rag.ipynb
