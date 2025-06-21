# NLP project
# AIMedQA - AI for Medical Question Answering
### Exam Date: June 27th 2025
Text Generation - A Natural Language Processing (NLP) Project

In this NLP project, we address the challenge of building a Medical Question Answering (Q&A) system capable of generating responses that reflect the tone, clarity, and precision of a doctor or medical assistant replying to a patient's inquiry. We frame this as a sequence-to-sequence text generation task, with a strong emphasis on data preprocessing, the selection and adaptation of pretrained models (through fine-tuning or prompt engineering, a comprehensive data analysis and a detailed evaluation and comparison of the performance achieved.

## Table of Contents
- Introdution
- Models used
- Methodology
- Results
- Issues Encountered
- Project Recap
- Final Conclusion

## Introduction
This project investigates medical question answering using both fine-tuning and prompting approaches on encoder-decoder and instruction-tuned models. The dataset consists of 1000 simulated medical questions covering various clinical topics.

## Models used
- T5-small (general-purpose)
- SciFive (biomedical)
- Flan-T5 (instruction-tuned)
- Phi-3-mini (small LLM with 3.8B parameters)

## Methodology
1. Preprocessing: Lowercasing the text, removing extra spaces and non-relevant punctuation (retaining stopwords and clinical numbers such as 'doses', 'ages').
2. Visualization: We visualized term frequency, plotted word clouds and applied BERTopic to extract medical topics.
3. Fine-tuning on T5-small, SciFive
4. Prompting on Flan-T5 and Phi-3-mini
5. Analysis using evaluation metrics such as ROUGE, BLEU, BERTScore

## Results
- Fine-tuned models perform better on clinically specific questions
- Instruction-tuned models generate more fluent and coherent answers but are less accurate on medical content
- Few-shot prompting improves relevance compared to zero-shot

## Issues encountered
We faced several challenges, maily related to computational resources.

## Project Recap
To briefly recap, this project compares fine-tuning and prompting approaches for medical question answering using encoder-decoder and instruction-tuned models, after applying a customed preprocessing pipeline. We evaluate their performance on a custom dataset with automatic metrics and topic-aware analysis.

## Final Conclusion
We approached this project fully aware of its complexity, aiming not only to implement and evaluate models, but also to understand the underlying principles behind medical NLP applications. Despite the challenges, we found the experience both technically and theoretically enriching, as it deepened our classroom knowledge and gave it real-world relevance.
