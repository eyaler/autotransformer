# autotransformer
A transformer variant for semantic continuous sentence representation and generation

We modify the transformer to give a fixed-length and distributed sentence representation.
This allows sampling from the latent space to generate sentences, semantic interpolations, sentence analogies etc.
The code is based on the Tensorflow Tensor2Tensor library and trains on TPU out of the box.
