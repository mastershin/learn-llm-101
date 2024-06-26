# Major NLP Tasks

- Text classification
- Text summarization
- Question answering
- Speech recognition / Text to Speech
- Language translation
- Chatbots

# LLM References

- Illustrated Transformer: https://jalammar.github.io/illustrated-transformer/
- https://nlp.seas.harvard.edu/annotated-transformer/

- Encoder Only BERT: https://arxiv.org/abs/1810.04805
- Decoder Only GPT: https://openai.com/research/language-unsupervised
- Training language models to follow instructions with human feedback: https://arxiv.org/abs/2203.02155
- Instruction Tuning for Large Language Models: A Survey: https://arxiv.org/abs/2308.10792
- Self-Alignment with Instruction Backtranslation: https://arxiv.org/abs/2308.06259
- Constitutional AI: Harmlessness from AI Feedback: https://arxiv.org/abs/2212.08073

# Evaluation Dataset
- ARC, 681 MB | 7,787 genuine grade-school level | https://huggingface.co/datasets/allenai/ai2_arc
- HellaSwag, 72 MB | Can a Machine Really Finish Your Sentence? For commonsense NLI. (ACL2019) | https://huggingface.co/datasets/Rowan/hellaswag
- MMLU, 120 MB | multiple-choice questions from various branches of knowledge. | https://huggingface.co/datasets/cais/mmlu
- TrufulQA, 271 KB | 817 questions that span 38 categories, including health, law, finance and politics | https://huggingface.co/datasets/truthful_qa

# Training Dataset
- ALPACA-cleaned, 43 MB | https://huggingface.co/datasets/yahma/alpaca-cleaned

## SuperGLUE Dataset

| Short Name | Full Name                         | Description                                                                      |
|------------|-----------------------------------|----------------------------------------------------------------------------------|
| BoolQ      | Boolean Questions                 | Involves answering a yes/no question based on a short passage.                   |
| CB         | CommitmentBank                    | Tests understanding of entailment and contradiction in a three-sentence format.  |
| COPA       | Choice of Plausible Alternatives  | Measures causal reasoning by asking for the cause/effect of a given sentence.    |
| MultiRC    | Multi-Sentence Reading Comprehension | Involves answering questions about a paragraph where each question may have multiple correct answers. |
| ReCoRD     | Reading Comprehension with Commonsense Reasoning | Requires selecting the correct named entity from a passage to fill in the blank of a question. |
| RTE        | Recognizing Textual Entailment    | Involves identifying whether a sentence entails, contradicts, or is neutral towards another sentence. |
| WiC        | Words in Context                  | Tests understanding of word sense disambiguation in different contexts.          |
| WSC        | Winograd Schema Challenge         | Focuses on resolving coreference resolution within a sentence, often requiring commonsense reasoning. |
| AX-b       | Broad Coverage Diagnostic         | A diagnostic set to evaluate model performance on a broad range of linguistic phenomena. |
| AX-g       | Winogender Schema Diagnostics     | Tests for the presence of gender bias in automated coreference resolution systems. |

## GLUE Dataset

| Short Name | Full Name                           | Description                                                                                                  |
|------------|-------------------------------------|--------------------------------------------------------------------------------------------------------------|
| CoLA       | Corpus of Linguistic Acceptability  | Measures the ability to determine if an English sentence is linguistically acceptable.                       |
| SST-2      | Stanford Sentiment Treebank         | Consists of sentences from movie reviews with human annotations about their sentiment.                       |
| MRPC       | Microsoft Research Paraphrase Corpus| Focuses on identifying whether two sentences are paraphrases of each other.                                  |
| STS-B      | Semantic Textual Similarity Benchmark | Involves determining the semantic similarity between two sentences.                                         |
| QQP        | Quora Question Pairs                | Aims to identify whether two Quora questions are semantically equivalent.                                    |
| MNLI       | Multi-Genre Natural Language Inference | Features sentence pairs labeled for textual entailment across various text genres.                          |
| QNLI       | Question Natural Language Inference | Involves determining whether a paragraph contains the answer to a question.                                 |
| RTE        | Recognizing Textual Entailment      | Requires understanding whether one sentence entails another.                                                |
| WNLI       | Winograd Natural Language Inference | Tests reading comprehension by determining the correct referent of a pronoun in a sentence, depending on contextual clues from specific words or phrases.          |

# Noteworthy Papers, including Attention Mechanisms
- A Decomposable Attention Model for Natural Language Inference, https://arxiv.org/abs/1606.01933v2 (2016)
- Attention Is All You Need, https://arxiv.org/abs/1706.03762 (2017)
- Bahdanau: Additive, https://arxiv.org/abs/1409.0473 (ICLR 2015)
- Luong: Multiplicative, https://arxiv.org/abs/1508.04025 (EMNLP 2015)
- HiCLIP: Contrastive Language-Image Pretraining with Hierarchy-aware Attention, https://arxiv.org/abs/2303.02995
- Understanding Parameter Sharing in Transformers, https://arxiv.org/abs/2306.09380

# Noteworthy LLMs
- LLama 3: https://huggingface.co/docs/transformers/main/en/model_doc/llama3