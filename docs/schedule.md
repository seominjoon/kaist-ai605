# Schedule & Materials

- Lectures (Lec XX) are on-site for Seoul Campus students, while lab sessions (Lab XX) are via Zoom for everyone. 
- All assignments and the final project are due at 23:00 KST, unless otherwise noted.
- No class on 3/1 (Holiday), 4/19 & 4/21 (midterm exam week), 5/5 (Holiday), and 6/14 & 6/16 (final exam week).

| Session | Date      | Topics                                  | Assignments | Reading List |
|----------------|-----------|-------------------------------------------------|------------------|-------------------------|
|              |  3/1 | Holiday                     |                ||
|             Lec 01 |  3/3 | Intro to NLP, Math & ML Basics [[slides][s01]]                     |                ||
|             Lab 01 |  3/8 | Math & ML Basics [[slides][ls01]][[notebook][n01]] | |                        |
|             Lec 02 |  3/10 | Text Classification, Recurrent Neural Networks [[slides][s02]]                      | | [MNIST][mnist], [[Socher et al., 2013]][sst], [[Srivastava et al., 2014]][dropout], [[Mikolov et al., 2013]][word2vec]|
|             Lab 02 |  3/15 | Text Classification, Recurrent Neural Networks [[slides][ls02]][[notebook][n02]] | |                        |
|              |  3/17 | Class canceled |  |                        |
|             Lec 03 |  3/22 | LSTM, Token Classification [[slides][s03]] | [Assignment 1][a1] is up |[Vanishing Gradients and Fancy RNNs][cs224n-07], [[Hochreiter & Schmidhuber, 1997]][lstm] |
|             Lab 03 |  3/24 | LSTM, Token Classification [[slides][ls03]][[notebook][n03]]  | |                        |
|             Lec 04 |  3/29 | Question Answering, Retrieval [[slides][s04]]  |  |[[Rajpurkar et al., 2016]][squad], [[Hermann et al., 2015]][teaching], [[Seo et al., 2017]][bidaf], [[Chen et al., 2017]][drqa], [`faiss`][faiss], [[Malkov & Yashunin, 2016]][hnsw]                     |
|             Lab 04 |  3/31 | Question Answering, Retrieval [[slides][ls04]] [[notebook][n04]] |  |                     |
|             Lec 05 |  4/5 | Text Generation [[slides][s05]]  | Assignment 1 is due (11pm KST) | [[Cho et al., 2014]][seq2seq], [[Bahdanau et al., 2015]][att], [[Luong et al., 2015]][att-luong] |
|             Lab 05 |  4/7 | Text Generation [[slides][ls05]] [[notebook][n05]] |  |                     |
|             Lec 06 |  4/12 | Transformer [[slides][s06]]  | [Assignment 2][a2] is up |[[Vaswani et al., 2017]][transformer], [Annotated Transformer][annotated]  |
|             Lab 06 |  4/14 | Transformer [[slides][ls06]] [[notebook][n06]]  |  | |
| | 4/19 | No class (midterm exam week) |
| | 4/21 | No class (midterm exam week) |
|              |  4/26 | Class canceled | Assignment 2 is due (11pm KST) |                        |
|             Lec 07 |  4/28 | Transformer (2) [[slides][s07]]   |  | [[Ioffe & Szgedy 2015]][batchnorm], [[Ba et al., 2016]][layernorm], [[Shaw et al., 2018]][relpos]  |
| Lab 07 | 5/3  | Transformer (2) [[slides][ls07]]   | [Assignment 3][a3] is up  | |
|        | 5/5  | No class (Holiday) |
| Lec 08 | 5/10 | Language Model   |  |  |
| Lab 08 | 5/12 | Language Model   |  | |
| Lec 09 | 5/17 | BERT   |  Assignment 3 is due (11pm KST) |  |
| Lab 09 | 5/19 | BERT   |  | |
| Lec 10 | 5/24 | T5   |  Assignment 4 is up |  |
| Lab 10 | 5/26 | T5  |  | |
| Lec 11 | 5/31 | GPT-2   |  |  |
| Lab 11 | 6/2  | GPT-2  |  | |
| Lec 12 | 6/9  | Recent Trend in NLP   | Assignment 4 and Final Project Report are due (11pm KST) |  |
| Lab 12 | 6/11 | Final Project Presentations  |  | |
| | 6/16 | No class (final exam week) |
| | 6/18 | No class (final exam week) |

<!--
|             12 | 10/27 | Transformer (2) [[slides][s12]]|  Assignment 2 is due.  |                         |
|             13 | 11/1 | Language Model, Regularization, Decoding [[slides][s13]] |   | [[Ioffe & Szgedy 2015]][batchnorm], [[Ba et al., 2016]][layernorm]                         |
|              | 11/3 | Pre-BERT Paper Discussion [[instructions][d1]] |  |                             |
|||||
|             14 |  11/8 | Transfer Learning, Pretrained Language Model [[slides][s14]]  | [Assignment 3][a3] is up.                     | [[Min et al., 2017]][qa-transfer], [[Peters et al., 2018]][elmo], [[Howard & Ruder, 2018]][ulmfit], [[Radford et al., 2018]][gpt]                                          |
|              | 11/10 | No lecture (EMNLP)  |   |                                         |
|             15 | 11/15 | BERT [[slides][s15]] |                                     | [[Devlin et al., 2018]][bert], [[Yang et al., 2019]][xlnet], [[Liu et al., 2019]][roberta], [BERT Slides][bert-slides] |
|             16 | 11/17 | Hugging Face and Final Project Tutorial [[slides][s16]] |  | [`transformers` Tutorial][transformers] |                      
|              | 11/22 | No lecture |Assignment 3 is due, [Assignment 4][a4] is up.  | |
|             17 | 11/24 |Pretraining for Generation [[slides][s17]] |  |[[Radford et al., 2019]][gpt-2], [[Lewis et al., 2020a]][bart], [[Raffel et al., 2020]][t5], [[Roberts et al., 2020]][cbqa], [[Lewis et al., 2020b]][overlap]  |
|             18 | 11/29 | Scaling Laws, In-Context Learning [[slides][s18]]|                                   |[[Kaplan et al., 2020]][scaling], [[Brown et al., 2020]][gpt-3], [[Ramesh et al., 2021]][dall-e] |
|              |  12/1 | Post-BERT Paper Discussion [[instructions][d2]]  |  | |
|              |  12/6 | Final Project Presentation                      |  Assignment 4 is due. |           |
|             |  12/8 | Final Project Presentation                      |                                   |                         |
|              |  12/13 | No lecture (finals week)                      |                                    |                         |
|              |  12/15 | No lecture (finals week)                      |  Final Project Report is due                                  |                         |
-->

[s01]: https://drive.google.com/file/d/11OKl3ftd0qOmKy6RAiBCqpmECnj1WHZm/view?usp=sharing
[s02]: https://drive.google.com/file/d/1-BMrvIM33VKbACbh1loaehZlUSKsZ3Lj/view?usp=sharing
[s03]: https://drive.google.com/file/d/13-yi-xOdny80neM2zNTZfGF_cTq62Qzg/view?usp=sharing
[s04]: https://drive.google.com/file/d/1-Dg3Cgdhw_jegVwvso5lvjHE5o0SD7F8/view?usp=sharing
[s05]: https://drive.google.com/file/d/1-KyVamiPCXsh0vkqfkr1pkJVg018x-xD/view?usp=sharing
[s06]: https://drive.google.com/file/d/137OmKnHi-x-WixW7v92Y0ZUMgJq04VDC/view?usp=sharing
[s07]: https://drive.google.com/file/d/1-UPo1cT2u-PRLpbkg2-vlcyRJFrURTo5/view?usp=sharing
[s08]: https://drive.google.com/file/d/12KnsPNcRwmQezmxnjTLzaz7-bWQt81f0/view?usp=sharing
[s09]: https://drive.google.com/file/d/1OlGeBWNJnTGB10pfdVOl6dp5E4WTeGYv/view?usp=sharing
[s10]: https://drive.google.com/file/d/1--qPSaQgkB5HbeEwRZYDNeEdjasxQAB5/view?usp=sharing
[s11]: https://drive.google.com/file/d/1-cOaQyb-JiIPYA2E0akpt-ZQw4NnX_pl/view?usp=sharing
[s12]: https://drive.google.com/file/d/1-e1afB-rbwh7Xlvp_uu4K0TU6-wPYxUN/view?usp=sharing
[s13]: https://drive.google.com/file/d/105uffdFm9kk4vxsAOKbpNejtTiTfeYiH/view?usp=sharing
[s14]: https://drive.google.com/file/d/1079QeGAsL8lUMJuL-UE8UrJBhTJIwriu/view?usp=sharing
[s15]: https://drive.google.com/file/d/10B5wdxaQFvCh21O0Gi9hDn8c5189jcPH/view?usp=sharing
[s16]: https://drive.google.com/file/d/10Ljc-WoOyvb8D1ZGtzrEi6OaYiFYBg-w/view?usp=sharing
[s17]: https://drive.google.com/file/d/12LIFz0bPcs46UMXNKZWMY8lo9V1sCJo6/view?usp=sharing
[s18]: https://drive.google.com/file/d/1-DVP3fmGiW2SbCryQuMJV_1DL4QOlIEy/view?usp=sharing
[s19]: https://drive.google.com/file/d/1lj58BULPV0SZUZBXkPdOYAIK_sL3vi0i/view?usp=sharing
[s20]: https://drive.google.com/file/d/17SUpIjpDX_if3rW3YZUGmUs_jk2__xRW/view?usp=sharing
[s21]: https://drive.google.com/file/d/1CdOeMFveW0kxMc5UgOt9Qc3tX-9pkFxE/view?usp=sharing

[ls01]: https://drive.google.com/file/d/1--GKA5XfAVygQO8JVzWjrgi830mdpji3/view?usp=sharing
[ls02]: https://drive.google.com/file/d/12jaMLT0TXT_sdvz2nM9JgCqTH8xzZziv/view?usp=sharing
[ls03]: https://drive.google.com/file/d/134m0lrDZYl9FzbgS_GSSnbLboC_HeBcj/view?usp=sharing
[ls04]: https://drive.google.com/file/d/136kePu9pF8bQr3_Ri7kNY1yDGqP8PWfF/view?usp=sharing
[ls05]: https://drive.google.com/file/d/1rdyBpcPoSBE_UVCT3RhRDAWa6xmYCUwj/view?usp=sharing
[ls06]: https://drive.google.com/file/d/139DMvXkHVxik8DS4OlNT8SJ-fUbE36w-/view?usp=sharing
[ls07]: https://drive.google.com/file/d/1-_c85ftn2ZF2-gQ4_4G8PkzVwhrTBFGG/view?usp=sharing

[n01]: https://colab.research.google.com/drive/1ZPgqQGX5BoMdx5ueRl5h2u2pTHxKK7Ws?usp=sharing
[n02]: https://colab.research.google.com/drive/1SjOeBf5KGVjX1aYQzwWU0tzS1elCK36G?usp=sharing
[n03]: https://colab.research.google.com/drive/1UUVTXjdBCzMkT0-BI2tPqNKIglQhx_ad?usp=sharing
[n04]: https://colab.research.google.com/drive/1WLLcS3q-wnA_StGKQUEU7kiTuPJUyKyF?usp=sharing
[n05]: https://colab.research.google.com/drive/1dAP9gH8dXzAVTt54JqHtcX940ozPy66X
[n06]: https://colab.research.google.com/drive/1A4xcJnWEYXgcZHmMNOv1l8dzOhbppD72

[a1]: https://colab.research.google.com/drive/1czIUOqIG9vF6MUsY7zcAO0Ne03Wk2KwQ#scrollTo=mbGnNWI1lRy_
[a2]: https://colab.research.google.com/drive/1_zwhc3QPoTY0yKXbXSKN90ZnAqKjWdOM#scrollTo=Pr94hZkt-dc9
[a3]: https://colab.research.google.com/drive/1DC8gBsEechnjO3nVZpl39cNcsUc9i8ol?usp=sharing
[a4]: https://colab.research.google.com/drive/1DC8gBsEechnjO3nVZpl39cNcsUc9i8ol#scrollTo=MTm5eq4NwQZs
[final]: https://docs.google.com/document/d/17F5_dcE7U4akdIa2H0G0hYo_RHvnBsZSPF1XVRYeZpQ/edit?usp=sharing
[final-survey]: https://forms.gle/sUb6Tok21e19rZC76

[s1]: https://colab.research.google.com/drive/1Mq_ZUPis2F8xuH9a2u9FzA_hEdMzFYeW

[d1]: https://docs.google.com/document/d/1hLzjQCiqU7zQq4RMg9A063Fv537VXmccjWk0pph2tn0/edit?usp=sharing
[d2]: https://docs.google.com/document/d/19voNry_NNJd3QpMV2XnDVZwwyhwlBAlwDX4RqWeKT7s/edit?usp=sharing

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
[relpos]: https://arxiv.org/abs/1803.02155