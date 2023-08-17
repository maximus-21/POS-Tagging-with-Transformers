# POS-Tagging-with-Transformers
Implementation of encoder only Transformer architecture for Part of Speech Tagging Task.<br>

Following the paper: [Attention is all you need](https://arxiv.org/abs/1706.03762) implemented the encoder part of the transformers architecture for the
Part of Speech Tagging task.<br>

`Dataset used`:  Penn Treebank<br>
`Tokenization`: sentencepiece<br>

 **Baseline Model**: A classifier where each word is assigned its most-frequent tag from the training data.<br>
`Accuracy`: 86.8<br>

**Transformer Model**<br>
`Accuracy`: 96.0<br>
