# basic transformers

basic implementations of transformer model(s) for my own study

## about

inspired by [minGPT](https://github.com/karpathy/minGPT), i wanted to implement some basic transformer models "from scratch" by following the original papers. this is a purely academic challenge for myself, a practicum of sorts for my transformer reading, and this code is not intended to be suitable for any real-world applications. while i am trying to adhere to the original papers as my primary reference, i am checking my code against other implementations to ensure that i am not totally off-base, and modifying it as necessary. that said, i do not guarantee the accuracy of my implementation, and any implementational errors are my own.

## current status & plans

- [x] multi-head attention
- [x] sinusoidal positional encoding
- [x] basic transformer encoder, from [*Attention is All You Need*](https://arxiv.org/abs/1706.03762)
- [ ] basic transformer decoder, from [*Attention is All You Need*](https://arxiv.org/abs/1706.03762)
- [ ] sentencepiece-based tokenizer
- [ ] all above tested with basic seq2seq training and generation scripts (translation task)
- [ ] GPT-style decoder and example, from [*Improving Language Understanding
by Generative Pre-Training*](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)
- [ ] BERT-style encoder and example, from [*BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*](https://arxiv.org/abs/1810.04805)
- [ ] ALBERT-style encoder and example, from [*ALBERT: A Lite BERT for Self-supervised Learning of Language Representations*](https://arxiv.org/abs/1909.11942)
- [ ] newer positional embeddings besides learned and sinusoidal

## how to use

todo later

## references

### papers

[*Attention is All You Need*](https://arxiv.org/abs/1706.03762)  
[*Improving Language Understanding
by Generative Pre-Training*](https://s3-us-west-2.amazonaws.com/openai-assets/research-covers/language-unsupervised/language_understanding_paper.pdf)  
[*BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*](https://arxiv.org/abs/1810.04805)  
[*ALBERT: A Lite BERT for Self-supervised Learning of Language Representations*](https://arxiv.org/abs/1909.11942)  
[*On Layer Normalization in the Transformer Architecture*](https://arxiv.org/abs/2002.04745)  

### reference implementations and articles

[pytorch `Transformer` documentation](https://pytorch.org/docs/stable/_modules/torch/nn/modules/transformer.html#Transformer)  
[*The Illustrated Transformer*](https://jalammar.github.io/illustrated-transformer/)  
[*Transformers Explained Visually (Part 3): Multi-head Attention, deep dive*](https://towardsdatascience.com/transformers-explained-visually-part-3-multi-head-attention-deep-dive-1c1ff1024853)  
[*How to code The Transformer in Pytorch*](https://towardsdatascience.com/how-to-code-the-transformer-in-pytorch-24db27c8f9ec#3fa3)  
github: [wzlxjtu/PositionalEncoding2D](https://github.com/wzlxjtu/PositionalEncoding2D)  