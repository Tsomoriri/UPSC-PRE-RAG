# UPSC-PRE-RAG
RAG application which applies inherent logical tricks to solve UPSC CSE prelims questions
## Development steps
-  Gemma as model served via llama.cpp
-  RAG LEVEL 6 as described by jxnl /cite{jxnl}
  - LLamaIndex for data parsing and embedding
-  pdf to text for gemma RAG search
-  generalise input to gemma using pydantic.
-  analysis with before and after RAG
-  possibility of fine tuning later

----------------------------------------------
GOAL: How general is general knowledge skill of gemma model / any LLM model?
UPSC CSE prelims tests GK but inherent logical rules dictate how aspirants clear this exam.
this includes tricks like etymology,sentiment analysis and probability theory
This RAG app tests if it is possible for a llm to learn these logical rules and apply them generally not specifically.
If yes, then can it identify more inherent laws which are not perceptible to human eye?
--------------------------------------------------
logic(rules)
- defined as context prompts llm must use as prescribed by embedding model
find logic rules()
- break questuon and answer in different styles, then use embedding model to search context and identify a rule
- 
