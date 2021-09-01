# Schedule & Materials

| # | Date      | Topics                                  | Assignments | Reading List |
|----------------|-----------|-------------------------------------------------|------------------|-------------------------|
|             01 |  8/30 | Intro to NLP, Deep Learning Basics [[slides][s01]]                     |                ||
|             02 |  9/1 | Deep Learning Basics (2) [[slides][s02]]                      | |                        |
|             03 | 9/6 | Deep Learning Basics (3), Text Classification, Tokenization, Word Embedding, Recurrent Neural Networks [[slides][s03]]                      |                |  [MNIST][mnist], [[Mikolov et al., 2014]][word2vec]                       |
|             04 | 9/8 | Training, LSTM [[slides][s04]] |                                    | [[Hochreiter & Schmidhuber, 1997]][lstm] |
|             05 | 9/13 | Jupyter Notebook, Token Classification, NER, MRC [[slides][s05]] |  [Assignment 1][a1] is up                                    |[Vanishing Gradients and Fancy RNNs][cs224n-07]|
|             06 | 9/15 | Text Generation (Machine Translation, Summarization), Encoder-Decoder, Decoder Attention [[slides][s06]] |                                     | [[Cho et al., 2014]][seq2seq], [[Bahdanau et al., 2015]][att], [[Luong et al., 2015]][att-luong]                         |
|              | 9/20 | No lecture (Chuseok) |                             |                         |
|              | 9/22 | No lecture (Chuseok) |                             |                         |
|             07 | 9/27 | Encoder Attention, Transformer [[slides][s07]] |                     | [[Hermann et al., 2015]][teaching], [[Wang & Jiang, 2017]][matchlstm], [[Seo et al., 2017]][bidaf], [[Vaswani et al., 2017]][transformer] |
|             08 | 9/29 | Transformer [[slides][s08]] | | [[Vaswani et al., 2017]][transformer], [Annotated Transformer][annotated] |
|              | 10/4 | No lecture (National Foundation Day) |                             |                         |
|             09 | 10/6 | Annotated Transformer [[slides][s09]]  |  Assignment 1 is due               | [Annotated Transformer][annotated]                   |
|              | 10/11 | No lecture (Hangeul Proclamation Day) |                             |                         |
|             10 |  10/13 | LayerNorm, Teacher Forcing, Beam Search, Byte Pair Encoding (BPE), Language Model [[slides][s10]] |  [Assignment 2][a2] is up    |  [[Ioffe & Szegedy, 2015]][batchnorm], [[Ba et al., 2016]][layernorm]                         |
|              | 10/18 | No lecture (midterm week) |Assignment 2 is due   |                         |
|              | 10/20 | No lecture (midterm week) |  |                         |
|             11 |  10/25 | Language Model, Syntactic Parsing [[slides][s11]] |                                     |  [Syntactic Parsing][syntactic]                       |
|             12 | 10/27 | Syntactic Parsing, Semantic Parsing [[slides][s12]] |                                     | [Syntactic Parsing][syntactic], [[Zhong et al., 2017]][wikisql]                        |
|             13 | 11/1 | Semantic Parsing, NLP paper analysis [[slides][s13]] |  [Assignment 3][a3] is up | [[Chen et al., 2016]][thorough], [[Rajpurkar et al., 2016]][squad]                        |
|             14 | 11/3 | NLP paper analysis discussions [[slides][s14]] |  |                            |
|             15 |  11/8 | Pretrained Language Model [[slides][s15]] |                     | [[Peters et al., 2018]][elmo], [[Howard & Ruder, 2018]][ulmfit] [[Radford et al., 2018]][gpt], [[Devlin et al., 2018]][bert]                                         |
|             16 | 11/10 | Pretrained LM and Tools [[slides][s16]]  | Assignment 3 is due  |                                        |
|             17 | 11/15 | Pretrained LM Tools [[slides][s17]] | [Assignment 4][a4] is up                                    | [`transformers`][transformers]                        |
|             18 | 11/17 | Open-domain QA and Final Project Tutorial [[slides][s18]] | [Final Project][final] is up  | [[Chen et al., 2017]][drqa], [[Karpukhin et al., 2020]][dpr] |                      
|             19 | 11/22 | Nearest Neighbor Search, Large Language Models [[slides][s19]] |  |[`faiss`][faiss], [[Malkov & Yashunin, 2016]][hnsw], [[Yang et al., 2019]][xlnet], [[Liu et al., 2019]][roberta], [[Lewis et al., 2020]][bart]|
|             20 | 11/24 | Large Language Models [[slides][s20]] | Assignment 4 is due                    | [[Lan et al., 2020]][albert], [[Clark et al., 2020]][electra], [[Raffel et al., 2020]][t5], [[Xu et al., 2020]][layoutlm], [[Sun et al., 2020]][mobilebert], [[Radford et al., 2019]][gpt-2], [[Roberts et al., 2020]][cbqa], [[Hong et al., 2021]][bros]|
|             21 | 11/29 | In-context Learning, Recent Trend in NLP [[slides][s21]]     |                                   | [[Kaplan et al., 2020]][scaling], [[Brown et al., 2020]][gpt-3], [[Ramesh et al., 2021]][dall-e] |
|              |  12/1 | Spare       |                |                         |
|             22 |  12/6 | Final project presentation                      |                                    |                         |
|            23 |  12/8 | Final project presentation                      |                                    |                         |
|              |  12/13 | No lecture (finals week)                      |                                    |                         |
|              |  12/15 | No lecture (finals week)                      |  Final Project Report is due                                  |                         |

[s01]: https://drive.google.com/file/d/1Wc3WWW5c1f0ZhusUAD-VEq2tWbRH7KCA/view?usp=sharing
[s02]: https://drive.google.com/file/d/11e7fpRWTW089Qvnivkh1fxxBQXxIcbvY/view?usp=sharing
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
[s14]: https://drive.google.com/file/d/1fW45gUS0K5omc4WfV4hOLjlzclZDqqeO/view?usp=sharing
[s15]: https://drive.google.com/file/d/1YeEHt9TuTZJzHpxJav2NC8xKNo_qLrvh/view?usp=sharing
[s16]: https://drive.google.com/file/d/14yBYoyIfiLgfgcq6oE2ZhPfAe-u1df1b/view?usp=sharing
[s17]: https://drive.google.com/file/d/11F3jIcHsvyRb_7z1KpQN1RubowNiDYu-/view?usp=sharing
[s18]: https://drive.google.com/file/d/1VlNmxw9gdJ3FrbuMPBHtssz8Fml8bArS/view?usp=sharing
[s19]: https://drive.google.com/file/d/1lj58BULPV0SZUZBXkPdOYAIK_sL3vi0i/view?usp=sharing
[s20]: https://drive.google.com/file/d/17SUpIjpDX_if3rW3YZUGmUs_jk2__xRW/view?usp=sharing
[s21]: https://drive.google.com/file/d/1CdOeMFveW0kxMc5UgOt9Qc3tX-9pkFxE/view?usp=sharing

[a1]: https://colab.research.google.com/drive/1SrYqfgY7mFqolA6_fpH6nkCzUOTanmsA?usp=sharing
[a2]: https://colab.research.google.com/drive/14ivrFazt_vv4jSE9eZ3AdQfP0DsAG8Gw?usp=sharing
[a3]: https://www.overleaf.com/read/vrpvdhcywbnv
[a4]: https://colab.research.google.com/drive/1v_oaSFru0rEN1fUXGOV0DSoX5J490JgT?usp=sharing
[final]: https://drive.google.com/file/d/1ARYetuQsPot3PhzsqT0wny4WZyJNDySi/view?usp=sharing

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
[elmo]: https://arxiv.org/abs/1802.05365
[gpt]: https://openai.com/blog/language-unsupervised/
[bert]: https://arxiv.org/abs/1810.04805
[transformers]: https://huggingface.co/transformers/
[drqa]: https://arxiv.org/abs/1704.00051
[dpr]: https://arxiv.org/abs/2004.04906
[hnsw]: https://arxiv.org/abs/1603.09320
[roberta]: https://arxiv.org/abs/1907.11692
[bart]: https://arxiv.org/abs/1910.13461
[xlnet]: https://arxiv.org/abs/1906.08237
[faiss]: https://github.com/facebookresearch/faiss
[gpt-2]: https://openai.com/blog/better-language-models/
[albert]: https://arxiv.org/abs/1909.11942
[electra]: https://arxiv.org/abs/2003.10555
[t5]: https://arxiv.org/abs/1910.10683
[layoutlm]: https://arxiv.org/abs/1912.13318
[m2m-100]: https://arxiv.org/abs/2010.11125
[mobilebert]: https://arxiv.org/abs/2004.02984
[scaling]: https://arxiv.org/abs/2001.08361
[gpt-3]: https://arxiv.org/abs/2005.14165
[cbqa]: https://arxiv.org/abs/2002.08910
[bros]: https://openreview.net/forum?id=punMXQEsPr0
[dall-e]: https://arxiv.org/abs/2102.12092
[ulmfit]: https://arxiv.org/abs/1801.06146
