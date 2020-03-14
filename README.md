# Implementation of Papers
Implementation of Selected Paper Published in Conferences such as ACL, NeurIPS, ICLR, ICML, EMNLP, ACM, and reputed Journals

## Model Description
* LSTM based Sequence-to-Sequence model
* (ACL) Pointer mechanism for handling Out of Vocabulary (OOV) words [See et al. (2017)](https://arxiv.org/pdf/1704.04368.pdf)
* (NeurIPS) Deliberation Decoder and Incremental Encoder (Under Development) [ Y Xia et.al.(2019).](https://papers.nips.cc/paper/6775-deliberation-networks-sequence-generation-beyond-one-pass-decoding.pdf) (Ongoing)
* Hindi-to English Neural Machine Translation using Attention Model [See et al. (2017)](http://www.ijstr.org/final-print/nov2019/Hindi-english-Neural-Machine-Translation-Using-Attention-Model.pdf) (Ongoing)

## Requirements
* PyTorch
* Tensorflow
* Python 2 & 3  

#### LSTM based Sequence-to-Sequence Model
A end-to-end sequence to sequence LSTM based model tp perform tasks such as text generation, basic chatbots, machine translation, etc.
```
python seq2seq.py --gpuid 0 --type bi

```
A evaluation and graph visualization on tensorboard iby using:
```
tensorboard --logdir logs

```
  