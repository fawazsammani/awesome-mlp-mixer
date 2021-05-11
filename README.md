# Awesome All-MLP-based papers[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome fully MLP-based learning resources. 

#### Why this repo?
After transformers and fully-based attention mechanism models took over the deep learning world since 2018, it appears that the power does not come from attention, and indeed replacing the feed-forward network by attention performs horrible [(~30% top-1 on ImageNet)](https://arxiv.org/pdf/2105.02723.pdf). It appears that *Attention is not all we need*. After all, we don't need inductive-biased models such as CNNs anymore, and we can lean back on MLPs since (1) we have enough data, (2) We have powerful optimization and regularization techniques. As we saw a big hipe on transformers [awesome vision transformer](https://github.com/dk-liang/Awesome-Visual-Transformer) and [BERT-related papers](https://github.com/tomohideshibata/BERT-related-papers), we exepct to see a big hipe in fully MLP-based networks *without attention*. This repository aims at gathering and collecting all these kind of papers.

## Contributing
Please help in contributing to this list by submitting an [issue](https://github.com/fawazsammani/awesome-mlp-mixer/issues) or a [pull request](https://github.com/fawazsammani/awesome-mlp-mixer/pulls)

Markdown format:
```markdown
- Paper Name [[pdf]](link) [[code]](link), *Conference Year*
```


## Computer Vision
- MLP-Mixer: An all-MLP Architecture for Vision [[pdf]](link) [[official code]](https://github.com/google-research/vision_transformer/tree/linen) [[code]](https://github.com/rishikksh20/MLP-Mixer-pytorch) [[code]](https://github.com/lucidrains/mlp-mixer-pytorch), [Yannic Kilcher Video](https://www.youtube.com/watch?v=7K4Z8RqjWIk) *2021*
- Do You Even Need Attention? A Stack of Feed-Forward Layers Does Surprisingly Well on ImageNet [[pdf]](https://arxiv.org/pdf/2105.02723.pdf) [[code]](https://github.com/lukemelas/do-you-even-need-attention), *2021*
- ResMLP: Feedforward networks for image classification with data-efficient training [[pdf]](https://arxiv.org/pdf/2105.03404.pdf) [[code]](https://github.com/lucidrains/res-mlp-pytorch), *2021*
