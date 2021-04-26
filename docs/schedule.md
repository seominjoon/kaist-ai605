# Schedule & Materials

| # | Date      | Topics                                  | Assignments | Reading List |
|----------------|-----------|-------------------------------------------------|------------------|-------------------------|
|             01 |  3/3 | Intro to NLP, Deep Learning Basics [[slides][s01]]                     |                ||
|             02 |  3/8 | Deep Learning Basics (2), Tokenization, Word Embedding, Text Classification [[slides][s02]]                      | | [MNIST][mnist], [[Mikolov et al., 2014]][word2vec]                       |
|             03 | 3/10 | Text Classification, Tokenization, Word Embedding, Recurrent Neural Networks [[slides][s03]]                      |                |                         |
|             04 | 3/15 | Training, LSTM [[slides][s04]] |                                    | [[Hochreiter & Schmidhuber, 1997]][lstm] |
|             05 | 3/17 | Jupyter Notebook, Token Classification, NER, MRC [[slides][s05]] |  [Assignment 1][a1] is up                                    |[Vanishing Gradients and Fancy RNNs][cs224n-07]|
|             06 | 3/22 | Text Generation (Machine Translation, Summarization), Encoder-Decoder, Decoder Attention [[slides][s06]] |                                     | [[Cho et al., 2014]][seq2seq], [[Bahdanau et al., 2015]][att], [[Luong et al., 2015]][att-luong]                         |
|             07 | 3/24 | Encoder Attention, Transformer [[slides][s07]] |                     | [[Hermann et al., 2015]][teaching], [[Wang & Jiang, 2017]][matchlstm], [[Seo et al., 2017]][bidaf], [[Vaswani et al., 2017]][transformer] |
|             08 | 3/29 | Transformer [[slides][s08]] | | [[Vaswani et al., 2017]][transformer], [Annotated Transformer][annotated] |
|             09 | 3/31 | Annotated Transformer [[slides][s09]]  |  Assignment 1 is due               | [Annotated Transformer][annotated]                   |
|             10 |  4/5 | LayerNorm, Teacher Forcing, Beam Search, Byte Pair Encoding (BPE), Language Model [[slides][s10]] |  [Assignment 2][a2] is up    |  [[Ioffe & Szegedy, 2015]][batchnorm], [[Ba et al., 2016]][layernorm]                         |
|             11 |  4/7 | Language Model, Syntactic Parsing [[slides][s11]] |                                     |  [Syntactic Parsing][syntactic]                       |
|             12 | 4/12 | Syntactic Parsing, Semantic Parsing [[slides][s12]] |                                     | [Syntactic Parsing][syntactic], [[Zhong et al., 2017]][wikisql]                        |
|              | 4/14 | No lecture (Minjoon can't make it) |                             |                         |
|              | 4/19 | No lecture (midterm week) |Assignment 2 is due   |                         |
|              | 4/21 | No lecture (midterm week) |  |                         |
|             13 | 4/26 | Semantic Parsing, NLP paper analysis [[slides]][s13] |  Assignment 3 is up | [[Chen et al., 2016]][thorough], [[Rajpurkar et al., 2016]][squad]                        |
|             14 | 4/28 | NLP paper discussions |  |                            |
|             15 |  5/3 | Pretrained Language Model | Assignment 3 is due, Assignment 4 is up                    |                                         |
|                |  5/5 | No lecture (어린이날)  |                                     |                         |
|             16 | 5/10 | Pretrained LM Tools |   |                                        |
|             17 | 5/12 | Open-domain QA |                                     |                         |
|             18 | 5/17 | Final Project Tutorial | Assignment 4 is due  | |                      
|                | 5/19 | No lecture (석가탄신일)                         |                                   |                         |
|             19 | 5/24 | Large Language Model (1) |  |                                       |
|             20 | 5/26 | Large Language Model (2) |                     |                                        |
|             21 | 5/31 | Generalization and In-context Learning     |                                   |                         |
|             22 |  6/2 | Other topics in NLP                                                                   |                |                         |
|              |  6/7 | Final project presentation                      |                                    |                         |
|              |  6/9 | Final project presentation                      |                                    |                         |

[s01]: https://drive.google.com/file/d/1x5E7gCnYaIkHWsy9rzENnTiXnW0pbNfB/view?usp=sharing
[s02]: https://drive.google.com/file/d/1Z2jxgwZFLJzehFCGuIvkBMUIQkvgJGvV/view?usp=sharing
[s03]: https://drive.google.com/file/d/1eKMxk6hv7HSzlMOWSp_lUa3Qsy8pMcZ8/view?usp=sharing
[s04]: https://drive.google.com/file/d/1KaCsDCNnrN9z8CxQlQ_XuKyDI-i9g2Rg/view?usp=sharing
[s05]: https://drive.google.com/file/d/1rANZenSNZSgBs0-9mTNRv1ASlnM4ltHv/view?usp=sharing
[s06]: https://drive.google.com/file/d/1XOv_rHZsxGbCdo-gRummQhOJm0nfITl1/view?usp=sharing
[s07]: https://drive.google.com/file/d/1TNog2BnX8hJ1FoY1pHQ_MaLOyG1FkfUv/view?usp=sharing
[s08]: https://drive.google.com/file/d/1_cPZ04tJzB67oMm2QA6soiI1QNv6oRSs/view?usp=sharing
[s09]: https://drive.google.com/file/d/1iIBkBIlyO8wyHYsKUYcZwAd8hNFu6Yjl/view?usp=sharing
[s10]: https://drive.google.com/file/d/1_GojPXerbuPzmELcMtzLO-ttwRgB8PFD/view?usp=sharing
[s11]: https://drive.google.com/file/d/12pOBHmevCbS4cmXK50FD0LeB-HUfN6Js/view?usp=sharing
[s12]: https://drive.google.com/file/d/1R0t0PMOLmYPv2GvQCob5yUN7HXkF76A5/view?usp=sharing
[s13]: https://drive.google.com/file/d/1sFfLPIxIsz59pACfxRuwBZz75Qam-S42/view?usp=sharing

[a1]: https://colab.research.google.com/drive/1SrYqfgY7mFqolA6_fpH6nkCzUOTanmsA?usp=sharing
[a2]: https://colab.research.google.com/drive/14ivrFazt_vv4jSE9eZ3AdQfP0DsAG8Gw?usp=sharing

[word2vec]: https://arxiv.org/abs/1301.3781
[mnist]: http://yann.lecun.com/exdb/mnist/
[cs224n-07]: https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1194/slides/cs224n-2019-lecture07-fancy-rnn.pdf
[seq2seq]: https://arxiv.org/abs/1406.1078
[lstm]: https://www.bioinf.jku.at/publications/older/2604.pdf
[att]: https://arxiv.org/abs/1409.0473
[att-luong]: https://arxiv.org/abs/1508.04025
[teaching]: https://arxiv.org/abs/1506.03340
[matchlstm]: https://arxiv.org/abs/1608.07905
[bidaf]: https://arxiv.org/abs/1611.01603
[transformer]: https://arxiv.org/abs/1706.03762
[annotated]: https://nlp.seas.harvard.edu/2018/04/03/attention.html
[layernorm]: https://arxiv.org/abs/1607.06450
[batchnorm]: https://arxiv.org/abs/1502.03167
[syntactic]: https://www.cs.unc.edu/~mbansal/teaching/slidesFall20/nlp_comp786_fall2020_lec4_sep2.pdf
[wikisql]: https://arxiv.org/abs/1709.00103
[thorough]: https://arxiv.org/abs/1606.02858
[squad]: https://arxiv.org/abs/1606.05250
