# Schedule & Materials

- All assignments and the final project are due at 23:00 on Wednesday, unless otherwise noted.
- No lecture on 9/20 & 9/22 (Chuseok), 10/4 (National Foundation Day), 10/11 (Hangeul Day), 10/18 & 10/20 (Midterm), and 12/13 & 12/15 (Final).

| # | Date      | Topics                                  | Assignments | Reading List |
|----------------|-----------|-------------------------------------------------|------------------|-------------------------|
|             01 |  8/30 | Intro to NLP, Deep Learning Basics [[slides][s01]]                     |                ||
|             02 |  9/1 | Deep Learning Basics (2) [[slides][s02]]                      | |                        |
|             03 | 9/6 | Deep Learning Basics (3), Text Classification, Tokenization [[slides][s03]]                      |                |  [MNIST][mnist], [[Socher et al., 2013]][sst]                        |
|             04 | 9/8 | Tokenization (2), Word Embedding [[slides][s04]] |  [Assignment 1][a1] is up                                   | [[Sennrich et al., 2015]][bpe], [[Srivastava et al., 2014]][dropout], [[Mikolov et al., 2013]][word2vec] |
|             05 | 9/13 | Recurrent Neural Networks [[slides][s05]] |                                      |[Vanishing Gradients and Fancy RNNs][cs224n-07], [[Hochreiter & Schmidhuber, 1997]][lstm]|
|             06 | 9/15 | Recurrent Neural Networks (2), Token Classification [[slides][s06]] |                                      |[[Rajpurkar et al., 2016]][squad]|
|              | 9/20 | No lecture (Chuseok) |                             |                         |
|              | 9/22 | No lecture (Chuseok) |                             |                         |
|             07 | 9/27 | Token Classification (2), Retrieval [[slides][s07]]  |  |[[Hermann et al., 2015]][teaching], [[Chen et al., 2016]][thorough], [[Wang & Jiang, 2017]][matchlstm], [[Seo et al., 2017]][bidaf], [[Chen et al., 2017]][drqa] |
|             08 | 9/29 | Retrieval (2) [[slides][s08]] | Assignment 1 is due, [Final Project][final] is up | [`faiss`][faiss], [[Malkov & Yashunin, 2016]][hnsw] |
|              | 10/4 | No lecture (National Foundation Day) |                             |                         |
|             09 | 10/6 | Text Generation, Encoder-Decoder [[slides][s09]] | | [[Cho et al., 2014]][seq2seq]             |
|              | 10/11 | No lecture (Hangeul Proclamation Day) |                             |                         |
|             10 |  10/13 | Attention [[slides][s10]] | [Final Project Survey][final-survey] is due. [Assignment 2][a2] is up.  [Assignment 1 Solution][s1] is up.  | [[Bahdanau et al., 2015]][att], [[Luong et al., 2015]][att-luong]         |
|              | 10/18 | No lecture (midterm week) |   |                         |
|              | 10/20 | No lecture (midterm week) |  |                         |
|             11 |  10/25 | Transformer [[slides][s11]] |                                     | [[Vaswani et al., 2017]][transformer], [Annotated Transformer][annotated]                        |
|             12 | 10/27 | Transformer (2) [[slides][s12]]|  Assignment 2 is due.  |                         |
|             13 | 11/1 | Language Model, Regularization, Decoding [[slides][s13]] |   | [[Ioffe & Szgedy 2015]][batchnorm], [[Ba et al., 2016]][layernorm]                         |
|              | 11/3 | Pre-BERT Paper Discussion [[instructions][d1]] |  |                             |
|||||
|             14 |  11/8 | Transfer Learning, Pretrained Language Model [[slides][s14]]  | [Assignment 3][a3] is up.                     | [[Min et al., 2017]][qa-transfer], [[Peters et al., 2018]][elmo], [[Howard & Ruder, 2018]][ulmfit], [[Radford et al., 2018]][gpt]                                          |
|              | 11/10 | No lecture (EMNLP)  |   |                                         |
|             15 | 11/15 | BERT [[slides][s15]] |                                     | [[Devlin et al., 2018]][bert], [[Yang et al., 2019]][xlnet], [[Liu et al., 2019]][roberta], [BERT Slides][bert-slides] |
|             16 | 11/17 | Hugging Face and Final Project Tutorial [[slides][s16]] |  | [`transformers` Tutorial][transformers] |                      
|              | 11/22 | No lecture |Assignment 3 is due, [Assignment 4][a4] is up.  | |
|             17 | 11/24 |Pretraining for Generation   |  |[[Radford et al., 2019]][gpt-2], [[Lewis et al., 2020a]][bart], [[Raffel et al., 2020]][t5], [[Roberts et al., 2020]][cbqa], [[Lewis et al., 2020b]][overlap]  |
|             18 | 11/29 | Scaling Laws, In-Context Learning |                                   |[[Kaplan et al., 2020]][scaling], [[Brown et al., 2020]][gpt-3], [[Ramesh et al., 2021]][dall-e] |
|              |  12/1 | Post-BERT Paper Discussion  |  | |
|              |  12/6 | Final Project Presentation                      |  Assignment 4 is due. |           |
|             |  12/8 | Final Project Presentation                      |                                   |                         |
|              |  12/13 | No lecture (finals week)                      |                                    |                         |
|              |  12/15 | No lecture (finals week)                      |  Final Project Report is due                                  |                         |

[s01]: https://drive.google.com/file/d/1Wc3WWW5c1f0ZhusUAD-VEq2tWbRH7KCA/view?usp=sharing
[s02]: https://drive.google.com/file/d/11e7fpRWTW089Qvnivkh1fxxBQXxIcbvY/view?usp=sharing
[s03]: https://drive.google.com/file/d/1hWfX08e7mdjzbPgNn1txtbT3vOBINm6M/view?usp=sharing
[s04]: https://drive.google.com/file/d/11pa0p54qHVP9P4JHPa1QBUFrpOx_1N_V/view?usp=sharing
[s05]: https://drive.google.com/file/d/11tGioYJPIwvO6orqTwkgyuUqxFpheZ8p/view?usp=sharing
[s06]: https://drive.google.com/file/d/121Ga4V2U030RaLEPkRl5sDdoYTHyBN0c/view?usp=sharing
[s07]: https://drive.google.com/file/d/12ESkOClHnxURjEc45MDidJK0WdwBXj9z/view?usp=sharing
[s08]: https://drive.google.com/file/d/12KnsPNcRwmQezmxnjTLzaz7-bWQt81f0/view?usp=sharing
[s09]: https://drive.google.com/file/d/1OlGeBWNJnTGB10pfdVOl6dp5E4WTeGYv/view?usp=sharing
[s10]: https://drive.google.com/file/d/1--qPSaQgkB5HbeEwRZYDNeEdjasxQAB5/view?usp=sharing
[s11]: https://drive.google.com/file/d/1-cOaQyb-JiIPYA2E0akpt-ZQw4NnX_pl/view?usp=sharing
[s12]: https://drive.google.com/file/d/1-e1afB-rbwh7Xlvp_uu4K0TU6-wPYxUN/view?usp=sharing
[s13]: https://drive.google.com/file/d/105uffdFm9kk4vxsAOKbpNejtTiTfeYiH/view?usp=sharing
[s14]: https://drive.google.com/file/d/1079QeGAsL8lUMJuL-UE8UrJBhTJIwriu/view?usp=sharing
[s15]: https://drive.google.com/file/d/10B5wdxaQFvCh21O0Gi9hDn8c5189jcPH/view?usp=sharing
[s16]: https://drive.google.com/file/d/10Ljc-WoOyvb8D1ZGtzrEi6OaYiFYBg-w/view?usp=sharing
[s17]: https://drive.google.com/file/d/11F3jIcHsvyRb_7z1KpQN1RubowNiDYu-/view?usp=sharing
[s18]: https://drive.google.com/file/d/1VlNmxw9gdJ3FrbuMPBHtssz8Fml8bArS/view?usp=sharing
[s19]: https://drive.google.com/file/d/1lj58BULPV0SZUZBXkPdOYAIK_sL3vi0i/view?usp=sharing
[s20]: https://drive.google.com/file/d/17SUpIjpDX_if3rW3YZUGmUs_jk2__xRW/view?usp=sharing
[s21]: https://drive.google.com/file/d/1CdOeMFveW0kxMc5UgOt9Qc3tX-9pkFxE/view?usp=sharing

[a1]: https://colab.research.google.com/drive/19lEyaARbvyxlqaYa4MbKvzxuYv7yt-qG
[a2]: https://colab.research.google.com/drive/1BnZTWAtJHphAle0jkvJkc6zh86GuBxIU
[a3]: https://colab.research.google.com/drive/1xRr_ZZc-HUwR37X_7EmzaK-JHBtJ5WW2?usp=sharing
[a4]: https://colab.research.google.com/drive/1M4tfQtRh_F0JXajx-5uInfK1lUtg6u9w?usp=sharing
[final]: https://docs.google.com/document/d/17F5_dcE7U4akdIa2H0G0hYo_RHvnBsZSPF1XVRYeZpQ/edit?usp=sharing
[final-survey]: https://forms.gle/sUb6Tok21e19rZC76

[s1]: https://colab.research.google.com/drive/1Mq_ZUPis2F8xuH9a2u9FzA_hEdMzFYeW

[d1]: https://docs.google.com/document/d/1hLzjQCiqU7zQq4RMg9A063Fv537VXmccjWk0pph2tn0/edit?usp=sharing

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
[transformers]: https://huggingface.co/transformers/training.html
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
[bpe]: https://arxiv.org/abs/1508.07909
[dropout]: https://jmlr.org/papers/v15/srivastava14a.html
[exposure-bias]: https://openreview.net/forum?id=rJg2fTNtwr
[sst]: https://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf
[ulmfit]: https://arxiv.org/abs/1801.06146
[qa-transfer]: https://arxiv.org/abs/1702.02171
[bert-slides]: https://nlp.stanford.edu/seminar/details/jdevlin.pdf
[overlap]: https://arxiv.org/abs/2008.02637