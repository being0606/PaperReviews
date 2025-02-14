# Reviewed Papers Summary

This document provides an overview of the research papers reviewed, organized by detailed research fields. Each section includes a table with the paper's review date, publication venue, published year, and a link to the presentation.

---

## 1. MoE / Scalable Architectures

| #   | Paper Title                                                                         | Review Date | Conference / Venue | Published Year | Link                                                                                                         |
| --- | ----------------------------------------------------------------------------------- | ----------- | ------------------ | -------------- | ------------------------------------------------------------------------------------------------------------ |
| 1   | **Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer** | 2025.02.11  | ICLR               | 2017           | [Link](https://docs.google.com/presentation/d/13UgUTVf9Q6mWVIRAn1f0z6UXIe7-ffRQoYmWyGYHlds/edit?usp=sharing) |

---

## 2. Pretrained Transformer Models (T5, BART, BERT)

These papers share similar pretraining strategies and unified text-to-text frameworks.

| #   | Paper Title                                                                                                           | Review Date | Conference / Venue | Published Year | Link                                                                                                         |
| --- | --------------------------------------------------------------------------------------------------------------------- | ----------- | ------------------ | -------------- | ------------------------------------------------------------------------------------------------------------ |
| 1   | **BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension** | (TBD)       | ACL (Preprint)     | 2019           | [Link](https://docs.google.com/presentation/d/1G3L3qRQHZFukr5XntiWswpIZBZ15vhU4A8OAL7bvTwY/edit?usp=sharing) |
| 2   | **Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer**                                 | (TBD)       | arXiv / JMLR       | 2019           | [Link](https://docs.google.com/presentation/d/1s9Us2b5gyM_BHapcTuirmDaf6MmvA2Thswg2CS2Jg7o/edit?usp=sharing) |
| 3   | **BERT Bidirectional Encoder Representations from Transformers**                                                      | 2025.01.21  | NAACL              | 2019           | [Link](https://docs.google.com/presentation/d/1jXnY-XUmqbDP-8S07ohzwKElEkweXOiZ9eEZu5x83L8/edit?usp=sharing) |
| 4   | **Attention is all you need**                                                                                         | 2025.01.17  | NeurIPS            | 2017           | [Link](https://docs.google.com/presentation/d/1Ot4-j7qjnmUXUFDz4lnPO5yzspzc44KSsF6qlBqaQYQ/edit?usp=sharing) |
| 5   | **Seq2seq with attention**                                                                                            | 2024.06.29  | ICLR (assumed)     | 2015           | [Link](https://docs.google.com/presentation/d/1-iop7-Fl1rHyqmk_oOCYySII1ZMJ_5R5A8Il8RNtypw/edit#slide=id.p)  |

---

## 3. Reasoning in Language Models

Includes works on multi-agent debate and chain-of-thought reasoning techniques.

| #   | Paper Title                                                                                        | Review Date | Conference / Venue | Published Year | Link                                                                                                        |
| --- | -------------------------------------------------------------------------------------------------- | ----------- | ------------------ | -------------- | ----------------------------------------------------------------------------------------------------------- |
| 1   | **[CODE REVIEW] Improving Factuality and Reasoning in Language Models through Multi-agent Debate** | 2024.09.28  | ICML               | 2024           | [Link](https://docs.google.com/presentation/d/1fnnND1cRJlJfr8khoNS_s28MUFuynCG3uVCMhY7MXjo/edit#slide=id.p) |
| 2   | **Self-Consistency Improves Chain of Thought Reasoning in Language Models**                        | 2024.09.19  | arXiv (Preprint)   | 2022           | [Link](https://docs.google.com/presentation/d/118X6d-M7ye3b2iu2sX6WmXIhr0MIsUBXpd-NeG2ZMMA/edit#slide=id.p) |
| 3   | **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**                          | 2024.09.19  | arXiv (Preprint)   | 2022           | [Link](https://docs.google.com/presentation/d/15kuzsgWYiVYI9_NWR93VLWZrOn9-G0_OhAt5vZjwyZM/edit#slide=id.p) |

---

## 4. Exploratory Model Analysis

| #   | Paper Title         | Review Date | Conference / Venue | Published Year | Link                                                                                                        |
| --- | ------------------- | ----------- | ------------------ | -------------- | ----------------------------------------------------------------------------------------------------------- |
| 1   | **openAI O1 model** | 2024.09.17  | N/A                | N/A            | [Link](https://docs.google.com/presentation/d/1d7-MzAGycdje4dm7w1n5hyXvaELM99a71n2voPSwCb8/edit#slide=id.p) |

---

## 5. Training Optimization / Fine-Tuning Techniques

| #   | Paper Title              | Review Date | Conference / Venue | Published Year | Link                                                                                                         |
| --- | ------------------------ | ----------- | ------------------ | -------------- | ------------------------------------------------------------------------------------------------------------ |
| 1   | **introduce SFT / ORPO** | 2024.07.14  | N/A                | N/A            | [Link](https://docs.google.com/presentation/d/1RbBnz781TLRKS628d8bkvkCV3vpWhdLdpcWt6neXepY/edit?usp=sharing) |

---

## 6. Word Embeddings / Representation Learning

| #   | Paper Title                                                                    | Review Date | Conference / Venue | Published Year | Link                                                                                                         |
| --- | ------------------------------------------------------------------------------ | ----------- | ------------------ | -------------- | ------------------------------------------------------------------------------------------------------------ |
| 1   | **Distributed Representation of Words and Phrases and their Compositionality** | 2022.10.30  | NeurIPS            | 2013           | [Link](https://docs.google.com/presentation/d/1_Kljt1nXcfLUgOoe4DPnl7tx7Cq5_IESN8qhti19pDM/edit?usp=sharing) |

## Brief Explanations

- **Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer**  
  This influential paper introduced a sparsely-activated mixture-of-experts layer to efficiently scale neural networks. It was originally presented at _ICLR 2017_ and has inspired further research in large-scale model architectures.

- **BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension**  
  BART proposes a denoising autoencoder strategy for sequence-to-sequence tasks. Initially released as a preprint in 2019, it later gained recognition through its acceptance at _ACL_ events.

- **Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer**  
  Known as the T5 paper, this work frames a broad range of NLP tasks under a unified text-to-text format. It was first made available on _arXiv_ in 2019 and subsequently published in _JMLR_.

- **BERT Bidirectional Encoder Representations from Transformers**  
  BERT revolutionized natural language understanding by using deep bidirectional transformers. Presented at _NAACL 2019_, this work remains a cornerstone in pre-training techniques.

- **Attention is all you need**  
  This seminal paper introduced the Transformer model, replacing recurrent architectures with a fully attention-based mechanism. It was presented at _NeurIPS 2017_ and has had a profound impact on subsequent research.

- **Improving Factuality and Reasoning in Language Models through Multi-agent Debate**  
  Reviewed under the CODE REVIEW tag, this work (scheduled for _ICML 2024_) explores novel methods to improve language model reasoning and factual accuracy through debate strategies.

- **Self-Consistency Improves Chain of Thought Reasoning in Language Models**  
  This paper demonstrates that sampling multiple reasoning paths and selecting the most consistent one improves overall performance. It was released as an _arXiv preprint in 2022_.

- **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models**  
  Another pivotal work on chain-of-thought prompting, this preprint from 2022 highlights how prompting strategies can elicit more complex reasoning in language models.

- **openAI O1 model**  
  Details regarding the publication venue or year for this review remain unavailable. It appears to be an internal or exploratory review of an OpenAI model.

- **introduce SFT / ORPO**  
  Similar to the previous entry, this review does not yet have publicly available publication details and seems to be part of an internal presentation series.

- **Seq2seq with attention**  
  This entry revisits early work on attention mechanisms in sequence-to-sequence models. It is assumed to refer to the pioneering work presented at _ICLR 2015_.

- **Distributed Representation of Words and Phrases and their Compositionality**  
  A classic in the field, this paper by Mikolov et al. laid the groundwork for word embedding techniques and was presented at _NeurIPS 2013_.
