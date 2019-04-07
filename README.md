# cnn_text_classification
Text Classification with CNN and Tensorflow

**[This code belongs to the "Implementing a CNN for Text Classification in Tensorflow" blog post.](http://www.wildml.com/2015/12/implementing-a-cnn-for-text-classification-in-tensorflow/)
Reference : https://github.com/dennybritz/cnn-text-classification-tf**

**Original paper: Kim's [Convolutional Neural Networks for Sentence Classification](http://arxiv.org/abs/1408.5882) paper in Tensorflow.**

## Requirements

- Python 3
- Tensorflow > 0.12
- Numpy

## Training:

```bash
python train.py
```

## Evaluating

```bash
python eval.py --eval_train --checkpoint_dir="./runs/1459637919/checkpoints/"
```

Replace the number folder with the output from the training.
