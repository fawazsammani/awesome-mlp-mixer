# Awesome MLP-based Transformers papers[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An up-to-date list of Transformers based fully on MLPs without attention!

#### Why this repo?
After transformers and fully-based attention mechanism models took over the deep learning world since 2018, it appears that the power does not come from attention, and indeed replacing the feed-forward network in a transformer by attention performs horrible [(~30% top-1 on ImageNet)](https://arxiv.org/pdf/2105.02723.pdf). It appears that *Attention is not all we need*. After all, we don't need inductive-biased models such as CNNs anymore, and we can lean back on MLPs since (1) we have enough data, (2) We have powerful optimization, regularization and data augmentation techniques. As we saw a big hipe on transformers [awesome vision transformer](https://github.com/dk-liang/Awesome-Visual-Transformer) and [BERT-related papers](https://github.com/tomohideshibata/BERT-related-papers), we expect to see a big hipe in fully MLP-based networks *without attention*, and the research focus is now shited to finding efficient ways of mixing tokens without involving attention mechanisms. This repository aims at gathering and collecting all these kind of papers.

## Contributing
Please help in contributing to this list by submitting an [issue](https://github.com/fawazsammani/awesome-mlp-mixer/issues) or a [pull request](https://github.com/fawazsammani/awesome-mlp-mixer/pulls)

```markdown
- Paper Name [[pdf]](link) [[code]](link)
```

## Papers
- MLP-Mixer: An all-MLP Architecture for Vision [[pdf]](https://arxiv.org/pdf/2105.01601.pdf) [[official code]](https://github.com/google-research/vision_transformer/tree/linen) [[code]](https://github.com/rishikksh20/MLP-Mixer-pytorch) [[code]](https://github.com/lucidrains/mlp-mixer-pytorch) [[code]](https://github.com/jeonsworld/MLP-Mixer-Pytorch) [[Yannic Kilcher Video]](https://www.youtube.com/watch?v=7K4Z8RqjWIk)
- Do You Even Need Attention? A Stack of Feed-Forward Layers Does Surprisingly Well on ImageNet [[pdf]](https://arxiv.org/pdf/2105.02723.pdf) [[code]](https://github.com/lukemelas/do-you-even-need-attention)
- ResMLP: Feedforward networks for image classification with data-efficient training [[pdf]](https://arxiv.org/pdf/2105.03404.pdf) [[code]](https://github.com/facebookresearch/deit) [[code]](https://github.com/lucidrains/res-mlp-pytorch) [[code]](https://github.com/rishikksh20/ResMLP-pytorch)
- Pay Attention to MLPs [[pdf]](https://arxiv.org/pdf/2105.08050.pdf) [[code]](https://github.com/lucidrains/g-mlp-pytorch) [[code]](https://github.com/lucidrains/g-mlp-gpt)
- FNet: Mixing Tokens with Fourier Transforms [[pdf]](https://arxiv.org/pdf/2105.03824.pdf) [[code]](https://github.com/rishikksh20/FNet-pytorch) [[Yannic Kilcher Video]](https://www.youtube.com/watch?v=JJR3pBl78zw&t=1s)
- Can Attention Enable MLPs To Catch Up With CNNs? [[pdf]](https://arxiv.org/pdf/2105.15078.pdf)
- MixerGAN: An MLP-Based Architecture for Unpaired Image-to-Image Translation [[pdf]](https://arxiv.org/pdf/2105.14110.pdf)
- On the Bias Against Inductive Biases [[pdf]](https://arxiv.org/pdf/2105.14077.pdf)
- S<sup>2</sup> MLP: Spatial-Shift MLP Architecture for Vision [[pdf]](https://arxiv.org/pdf/2106.07477.pdf)
- Vision Permutator: A Permutable MLP-Like Architecture for Visual Recognition [[pdf]](https://arxiv.org/pdf/2106.12368.pdf) [[code]](https://github.com/Andrew-Qibin/VisionPermutator)
- Rethinking Token-Mixing MLP for MLP-based Vision Backbone [[pdf]](https://arxiv.org/pdf/2106.14882.pdf)
- Global Filter Networks for Image Classification [[pdf]](https://arxiv.org/pdf/2107.00645.pdf) [[code]](https://github.com/raoyongming/GFNet)
- What Makes for Hierarchical Vision Transformer? [[pdf]](https://arxiv.org/pdf/2107.02174.pdf)
