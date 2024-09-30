## Out-of-the-Box Graded Vocabulary Lists with Generative Language Models: Fact or Fiction?

This repository contains the annotated data for the paper: Out-of-the-Box Graded Vocabulary Lists with Generative Language Models: Fact or Fiction?


## Data structure

The data comes in two forms, first the automatically (re-)annotated grades using LLMs (`/annotated`), second the generated word lists (`/generated`). 

## Data description

This project uses the CEFRLex lists (https://cental.uclouvain.be/cefrlex/) in English, Spanish, French, Swedish and Dutch. The data was cleaned to exclude multi-word expressions and non-alphabetic sequences.

For annotation, the data was graded using five different large language models (Gemma, Mistral, Llama, Phi3, GPT-4o).

For generation, the language models were asked for 100 words of each target level (A1 to C1). The data in `/generated` has been cleaned to only include the words, stripping other text such as "Here are 100 words..." and various markup.