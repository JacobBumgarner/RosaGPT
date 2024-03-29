# RosaGPT
[RosaGPT](https://chat.openai.com/g/g-6VqZewHmW-rosagpt) is a working and learning assistant for bioinformatics and biostatistics topics.

**Contents**
- [Overview](#overview)
- [Examples](#examples)
  - [RosaGPT vs. ChatGPT](#rosagpt-vs-chatgpt)
  - [Functional Examples](#functional-examples)
  - [Pair Learning](#pair-learning-examples)
- [Disclaimer](#disclaimer)

## Overview
RosaGPT is a modified version of ChatGPT, built using the OpenAI GPT Assistant feature.

Rosa's [system prompt](https://github.com/JacobBumgarner/RosaGPT/tree/main/system_prompts) includes a variety of single-shot examples to promote clear, organized, and in-depth responses. As a result, Rosa helps with complicated topics in a more effective manner than base ChatGPT.

From an analytics and coding perspective, Rosa is instructed to provide structured and single-block solutions.

Rosa also acts as an excellent pair learner by providing step-by-step topic, equation, and algorithm walkthroughs. During pair learning sessions, it encourages the user to ask refined questions to dive into the deeper aspects of understanding a topic.

## Examples
### RosaGPT vs. ChatGPT
| Description | RosaGPT | ChatGPT | 
| ----------- | ------- | ------- |
| Asking specific questions about a covariance equation proof in image format. RosaGPT provides a correct and line-by-line proof rationale. ChatGPT completely fails the task, providing incorrect equation identification and proof rationale. | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/d5e9e547-9eb0-47f5-9851-df0c90699331" width="300px"/> | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/3be121d6-982d-4ec9-bfe7-5259beb79fcc" width="300px"/> |
| Generating a script to run and visualize an ORA anlaysis. Rosa provides single block code solutions with commented descriptions and step-by-step explanations. | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/838850c8-cf0c-499c-a46f-a65df3eb5c27" width="300px"/> | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/4e7b34f5-0b2f-4813-a811-e7b93c9058cc" width="300px"/> |
| Asking for a summarization of the methods used to generate a gene signature in a manuscript [link](https://www.nature.com/articles/s41467-018-07841-3). Rosa correctly summarizes the methods in a concise manner, while the base ChatGPT misses the understanding of the structure of the article and provides an incorrect answer. | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/d11939fe-61fa-4ac4-924b-cfd9dcec9098" width="300px"/> | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/c9969076-078a-4bae-9377-65fcd4d36a11" width="300px"/> |

### Functional Examples
| Example | Conversation | 
| ------- | ------------ |
| Asking for help converting gene symbols to Ensembl IDs  | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/1703a69e-4b6d-4fac-93f6-2764629e1665" width="300px"> | 

### Pair Learning Examples
| Example | Conversation | 
| ------- | ------------ |
| Asking for a high-level overview of LASSO for feature selection.  | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/8e7b0051-2935-4f05-891f-26daa996ca89" width="300px"> | 
| Variance Equation Derivation | <img src="https://github.com/JacobBumgarner/RosaGPT/assets/70919881/f13c4bbf-d36a-41a6-acfe-d8977c5c91b2" width="300px"> |

## Disclaimer
RosaGPT is a beta version of an [OpenAI GPT Assistant](https://platform.openai.com/docs/assistants/overview). The behavior of this GPT and the OpenAI Assistant API are still in development.

Like all large language models (LLMs), RosaGPT is not infallible and ***will provide incorrect information***. Users should exercise caution and verify the accuracy of any information obtained from this tool before relying on it. I do not assume responsibility for any errors, inaccuracies, or misinterpretations that arise from the use of this GPT Assistant.
