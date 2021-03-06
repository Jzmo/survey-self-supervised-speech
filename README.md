# survery of self supervised leraning for speech

| Name        | Paper                                  | Comment | Organization | Source | Pre-trained model |
| ----------- | -------------------------------------- | ------- | ------------ | ------ | ----------------- |
| vq-APC      | [Vector-Quantized Autoregressive Predictive Coding](https://arxiv.org/pdf/2005.08392.pdf) | Interspeech 2020 | MIT | [code](https://github.com/iamyuanchung/VQ-APC) | |
| wav2vec 2.0 | [wav2vec 2.0: A Framework for Self-Supervised Learning of Speech Representations](https://arxiv.org/abs/2006.11477)       | NeurIPS 2020 | Facebook AI Research | [code](https://github.com/pytorch/fairseq/tree/master/examples/wav2vec) | [models](https://github.com/pytorch/fairseq/blob/master/examples/wav2vec/README.md) |
| CPC_audio   | [UNSUPERVISED PRETRAINING TRANSFERS WELL ACROSS LANGUAGES](https://arxiv.org/pdf/2002.02848.pdf) | ICASSP 2020 | Facebook AI Research | [code](https://github.com/facebookresearch/CPC_audio) |  |
| APC         | [An unsuper- vised autoregressive model for speech representation learning](https://arxiv.org/pdf/1904.03240.pdf) | Interspeech 2019 | MIT |        |                   |
| vq-wav2vec  | [VQ-WAV2VEC: SELF-SUPERVISED LEARNING OF DISCRETE SPEECH REPRESENTATIONS](https://arxiv.org/pdf/1910.05453.pdf)   | ICLR 2020 | Facebook AI Research | [code](https://github.com/pytorch/fairseq/tree/master/examples/wav2vec)       | [models](https://github.com/pytorch/fairseq/blob/master/examples/wav2vec/README.md) |
| wav2vec     | [wav2vec: Unsupervised Pre-Training for Speech Recognition](https://arxiv.org/pdf/1904.05862.pdf)   | Interspeech 2019 | Facebook AI Research | [code](https://github.com/pytorch/fairseq/tree/master/examples/wav2vec)       | [models](https://github.com/pytorch/fairseq/blob/master/examples/wav2vec/README.md) |

# Applications
| Name        | Paper                                  | Comment | Organization | Source | Pre-trained model |
| ----------- | -------------------------------------- | ------- | ------------ | ------ | ----------------- |
|             | [Self-training and Pre-training are Complementary for Speech Recognition](http://arxiv.org/abs/2010.11430) |  | Facebook AI Research | | |


# Tianzi
| Name        | Paper                                  | Comment | Organization | Source | Pre-trained model |
| ----------- | -------------------------------------- | ------- | ------------ | ------ | ----------------- |
|             | [Towards Semi-Supervised Semantics Understanding from Speech](https://arxiv.org/abs/2011.06195) |  | MIT/Amazon | | |
|             | [The Zero Resource Speech Benchmark 2021: Metrics and baselines for unsupervised spoken language modeling](https://arxiv.org/pdf/2011.11588.pdf) |  | | | |
|   C/A/MPC   | [Similarity Analysis of Self-Supervised Speech Representations](https://arxiv.org/abs/2010.11481) |  | MIT | | |
|   DAPC      | [Representation Learning for Sequence Data with Deep Autoencoding Predictive Components](https://arxiv.org/abs/2010.03135) |  | Cornell | | |
|  BertVideo  | [VideoBERT: A Joint Model for Video and Language Representation Learning](https://arxiv.org/pdf/1904.01766.pdf) |  | Google | | |

# ideas:

1. Hierarchy k-means
2. APC + CPC + MPC (joint training/conditional training/finetune)
3. PI

# Q:
1. Short term action
2. Metrics
