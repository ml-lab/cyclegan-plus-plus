# Artist Style Transfer Via Quadratic Potential

[arXiv paper](https://arxiv.org/abs/1902.11108)

### Abstract

In this paper we address the problem of artist style transfer where the painting style of a given artist is applied on a real world photograph. We train our neural networks in adversarial setting via recently introduced quadratic potential divergence for stable learning process. To further improve the quality of generated artist stylized images we also integrate some of the recently introduced deep learning techniques in our method. To our best knowledge this is the first attempt towards artist style transfer via quadratic potential divergence. We provide some stylized image samples in the supplementary material. The source code for experimentation was written in [PyTorch](https://pytorch.org) and is available online in my [GitHub repository](https://github.com/rahulbhalley/cyclegan-plus-plus).

Please consider citing this work with the following BibTex:
```
@article{bhalley2019artist,
  title={Artist Style Transfer Via Quadratic Potential},
  author={Bhalley, Rahul and Su, Jianlin},
  journal={arXiv preprint arXiv:1902.11108},
  year={2019}
}
```

### Prerequisites

The code was tested on following versions of respective libraries:

- PyTorch 1.0.1
- torchvision 0.2.1

### Usage

All the experiments may be performed by running `python main.py` command in terminal. All you need to make changes is the variables in `config.py` file. For instance, set `TRAIN = True` for training or change `BATCH_SIZE`, et cetera for more experimentations.

### Contact

For queries contact me at `[first name][second name][at][protonmail][dot][com]`.