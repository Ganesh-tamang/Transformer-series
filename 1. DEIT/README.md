## DeiT (Data-efficient image Transformers) is a specific type of transformer-based architecture developed for image classification tasks. It was introduced in the paper ["Training data-efficient image transformers & distillation through attention"](https://arxiv.org/pdf/2012.12877.pdf).
## In this paper,They introduce a teacher-student strategy specific to transformers. It relies on a distillation token ensuring that the student learns from the teacher through attention. They show the interest of this token-based distillation, especially when using a convnet as a teacher. This leads to report results competitive with convnets for Imagenet.

## 0. knowledge distillation.ipynb contains the information about knowledge distillation, but it is done in keras.

## Deit_transformer.ipynd contains the detailed training of deit transformer from scratch
​