# NameGen
Character-Level Name Generator with Manual Backpropagation

A character-level name generator implemented in PyTorch, with a manual implementation of backpropagation. 

The model learns patterns in names and generates new names by predicting one character at a time based on a fixed-length context.

- Paper: ["Neural Probabilistic Language Model" by Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf).
- It uses data from the [U.S. Social Security Administration's Baby Names dataset](https://www.ssa.gov/oact/babynames/limits.html)
- Features a _manually_ implemented backpropagation algorithm

#### Neural Architecture:
- Embedding Layer for character encoding.
- Flatten Layer
- Hidden Layer with Batch Normalization and Tanh activation.
- Output Layer for character prediction.

##### Dataset:
Processes over 100,000 unique names from the SSA Baby Names dataset.
##### Name Generation: 
Produces unique, realistic names character by character.

#### Output Examples
```
priah
kailas
sabirg
kyena
deka
kailas
sabirg
```
