# ICLShortcutLearning

## Shortcut Types

### Vanilla-label Bias
1. None of the Others: a General Technique to Distinguish Reasoning from Memorization in Multiple-Choice LLM Evaluation Benchmarks, Arxiv 2025

### Tokens
1. A Peek into Token Bias: Large Language Models Are Not Yet Genuine Reasoners, ICML-Workshop 2024.

### Entity
1. Rethinking Relation Extraction: Beyond Shortcuts to Generalization with a Debiased Benchmark, Arxiv, 2025

### Position
1. Revisiting Zero-Shot Abstractive Summarization in the Era of Large Language Models from the Perspective of Position Bias, NAACL, 2024

## Benchmarks
1. Rethinking Relation Extraction: Beyond Shortcuts to Generalization with a Debiased Benchmark, Arxiv-2025

## Causes of Shortcut Learning

1. Beyond Surface Structure: A Causal Assessment of LLMs’ Comprehension Ability, Arxiv-2024. **Abs**: It proposes a causal method to investigate the abilities of shallow understanding and deep understanding of LLMs, and finds that the proportion of deep understanding is larger, and as the scale of model parameters increases, the model is more inclined towards deep understanding. 

### Memory
Several studies have also shed light on the relationship between memorization and model generalization. While they do not explicitly articulate the impact on bias or shortcut learning, they nonetheless offer a valuable and feasible analytical perspective.

1. Think or Remember? Detecting and Directing LLMs Towards Memorization or Generalization, Arxiv-2024. **Abs**: It has been shown that LLMs are capable of memorizing specific patterns that frequently appear in the training data, which can lead to a decline in generalization performance. Interrupting the activation of corresponding memory neurons may help mitigate such undesirable memorization. This phenomenon appears to be related to shortcut formation observed in shortcut learning studies, though further investigation is needed to clarify the connection.

## Studies Related to Social Bias

1. Mitigating Social Bias in Large Language Models: A Multi-Objective Approach within a Multi-Agent Framework, AAAI-2025.
2. 

## Studies Utilizing LLMs but not ICL
1. Rectifying Demonstration Shortcut in In-Context Learning, Coling, 2025. **Abs**: LLM is used for data augmentation and the augmented data is used to train a BERT-like model. 
2. Causal keyword driven reliable text classification with large language model feedback, IPM, 2025. **Abs**: LLM is used to purify causal keywords and a BERT-like model is trained based on causal keywords to enhance generalization.
3. 
