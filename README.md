# Autotransformer
A transformer variant for semantic continuous sentence representation and generation

We modify the transformer to give a fixed-length and distributed sentence representation.
This allows sampling from the latent space to generate sentences, semantic interpolations, sentence analogies etc.
The code is based on the Tensorflow Tensor2Tensor library and trains on TPU out of the box.

based on:

Vaswani et al., Attention Is All You Need, arxiv.org/abs/1706.03762

Cer et al., Universal Sentence Encoder, arxiv.org/abs/1803.11175

Cifka et al., Eval all, trust a few, do wrong to none: Comparing sentence generation models, arxiv.org/abs/1804.07972

Cifka and Bojar, Are BLEU and Meaning Representation in Opposition? arxiv.org/abs/1805.06536

motivation:

Bowman et al., Generating Sentences from a Continuous Space, arxiv.org/abs/1511.06349

Gan et al., Learning Generic Sentence Representations Using Convolutional Neural Networks arxiv.org/abs/1611.07897

Semeniuta et al., A Hybrid Convolutional Variational Autoencoder for Text Generation, arxiv.org/abs/1702.02390

Zhao et al, Adversarially Regularized Autoencoders, arxiv.org/abs/1706.04223

https://blogs.helsinki.fi/language-technology/files/2017/09/FINMT2017-Bojar.pdf

A rough guide to training transformer on TPU can be found here:

https://github.com/eyaler/autotransformer/blob/master/transformer_tpu.txt

Acknowledgements:
This work was supported by [Deep Learning Camp Jeju 2018](http://jeju.dlcamp.org/2018/) which was organized by [TensorFlow Korea User Group](https://facebook.com/groups/TensorFlowKR/)
