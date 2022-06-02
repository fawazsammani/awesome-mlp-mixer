# Awesome MLP Mixer papers[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An up-to-date list of fully MLPs without attention!

#### Why this repo?
After transformers and fully-based attention mechanism models took over most of the deep learning world since 2019, it appears that the power does not come from attention, and indeed replacing the feed-forward network in a transformer by attention performs horrible [(~30% top-1 on ImageNet)](https://arxiv.org/pdf/2105.02723.pdf). It appears that *Attention is not all we need*. After all, we don't need inductive-biased models such as CNNs anymore, and we can lean back on MLPs since (1) we have enough data, (2) We have powerful optimization, regularization and data augmentation techniques. As we saw a big hipe on transformers [awesome vision transformer](https://github.com/dk-liang/Awesome-Visual-Transformer) and [BERT-related papers](https://github.com/tomohideshibata/BERT-related-papers), we expect to see a big hipe in fully MLP-based networks *without attention*, and the research focus is now shited to finding efficient ways of mixing tokens without involving attention mechanisms. This repository aims at gathering and collecting all these kind of papers.

## Contributing
Please help in contributing to this list by submitting an [issue](https://github.com/fawazsammani/awesome-mlp-mixer/issues) or a [pull request](https://github.com/fawazsammani/awesome-mlp-mixer/pulls)

```markdown
- Paper Name [[pdf]](link) [[code]](link)
```

## Papers
- **[MLP-Mixer]** An all-MLP Architecture for Vision [[pdf]](https://arxiv.org/pdf/2105.01601.pdf) [[official code]](https://github.com/google-research/vision_transformer/tree/linen) [[code]](https://github.com/rishikksh20/MLP-Mixer-pytorch) [[code]](https://github.com/lucidrains/mlp-mixer-pytorch) [[code]](https://github.com/jeonsworld/MLP-Mixer-Pytorch) [[Yannic Kilcher Video]](https://www.youtube.com/watch?v=7K4Z8RqjWIk)
- Do You Even Need Attention? A Stack of Feed-Forward Layers Does Surprisingly Well on ImageNet [[pdf]](https://arxiv.org/pdf/2105.02723.pdf) [[code]](https://github.com/lukemelas/do-you-even-need-attention)
- **[ResMLP]** Feedforward networks for image classification with data-efficient training [[pdf]](https://arxiv.org/pdf/2105.03404.pdf) [[code]](https://github.com/facebookresearch/deit) [[code]](https://github.com/lucidrains/res-mlp-pytorch) [[code]](https://github.com/rishikksh20/ResMLP-pytorch)
- Pay Attention to MLPs [[pdf]](https://arxiv.org/pdf/2105.08050.pdf) [[code]](https://github.com/lucidrains/g-mlp-pytorch) [[code]](https://github.com/lucidrains/g-mlp-gpt) [[code]](https://github.com/jaketae/g-mlp)
- **[FNet]** Mixing Tokens with Fourier Transforms [[pdf]](https://arxiv.org/pdf/2105.03824.pdf) [[code]](https://github.com/rishikksh20/FNet-pytorch) [[Yannic Kilcher Video]](https://www.youtube.com/watch?v=JJR3pBl78zw&t=1s)
- Can Attention Enable MLPs To Catch Up With CNNs? [[pdf]](https://arxiv.org/pdf/2105.15078.pdf)
- MixerGAN: An MLP-Based Architecture for Unpaired Image-to-Image Translation [[pdf]](https://arxiv.org/pdf/2105.14110.pdf)
- On the Bias Against Inductive Biases [[pdf]](https://arxiv.org/pdf/2105.14077.pdf)
- S<sup>2</sup> MLP: Spatial-Shift MLP Architecture for Vision [[pdf]](https://arxiv.org/pdf/2106.07477.pdf)
- **[Vision Permutator]** A Permutable MLP-Like Architecture for Visual Recognition [[pdf]](https://arxiv.org/pdf/2106.12368.pdf) [[code]](https://github.com/Andrew-Qibin/VisionPermutator)
- Rethinking Token-Mixing MLP for MLP-based Vision Backbone [[pdf]](https://arxiv.org/pdf/2106.14882.pdf)
- Global Filter Networks for Image Classification [[pdf]](https://arxiv.org/pdf/2107.00645.pdf) [[code]](https://github.com/raoyongming/GFNet)
- What Makes for Hierarchical Vision Transformer? [[pdf]](https://arxiv.org/pdf/2107.02174.pdf)
- **[As-MLP]** An Axial Shifted MLP architecture for Vision [[pdf]](https://arxiv.org/pdf/2107.08391.pdf)[[code]](https://github.com/svip-lab/AS-MLP)
- **[CycleMLP]** A MLP-like Architecture for Dense Prediction [[pdf]](https://arxiv.org/pdf/2107.10224.pdf)[[code]](https://github.com/ShoufaChen/CycleMLP)
- S<sup>2</sup> MLPv2: Improved Spatial-Shift MLP Architecture for Vision [[pdf]](https://arxiv.org/pdf/2108.01072.pdf)
- **[RaftMLP]** Do MLP-based Models Dream of Winning Over Computer Vision? [[pdf]](https://arxiv.org/pdf/2108.04384.pdf) [[code]](https://github.com/okojoalg/raft-mlp)
- **[Hire-MLP]** Vision MLP via Hierarchical Rearrangement [[pdf]](https://arxiv.org/pdf/2108.13341.pdf)
- **[Sparse-MLP]** A Fully-MLP Architecture with Conditional Computation [[pdf]](https://arxiv.org/pdf/2109.02008.pdf)
- Sparse MLP for Image Recognition: Is Self-Attention Really Necessary? [[pdf]](https://arxiv.org/pdf/2109.05422.pdf)
- Patches Are All You Need? [[pdf]](https://openreview.net/pdf?id=TVHS5Y4dNvM) [[code]](https://github.com/tmp-iclr/convmixer)
- Exploring the Limits of Large Scale Pre-training [[pdf]](https://arxiv.org/pdf/2110.02095.pdf)
- Adversarial Robustness Comparison of Vision Transformer and MLP-Mixer to CNNs [[pdf]](https://arxiv.org/pdf/2110.02797.pdf) [[code]](https://github.com/phibenz/robustness_comparison_vit_mlp-mixer_cnn)
- Cascaded Cross MLP-Mixer GANs for Cross-View Image Translation [[pdf]](https://arxiv.org/pdf/2110.10183.pdf) [[code]](https://github.com/Amazingren/CrossMLP)
- Are We Ready for a New Paradigm Shift? A Survey on Visual Deep MLP [[pdf]](https://arxiv.org/pdf/2111.04060.pdf)
- MetaFormer is Actually What You Need for Vision [[pdf]](https://arxiv.org/pdf/2111.11418.pdf) [[code]](https://github.com/sail-sg/poolformer)
- An Image Patch is a Wave: Phase-Aware Vision MLP [[pdf]](https://arxiv.org/pdf/2111.12294.pdf)
- **[MorphMLP]** A Self-Attention Free, MLP-Like Backbone for Image and Video [[pdf]](https://arxiv.org/pdf/2111.12527.pdf)
- **[SWAT]**: Spatial Structure Within and Among Tokens [[pdf]](https://arxiv.org/pdf/2111.13677.pdf)
- MLP Architectures for Vision-and-Language Modeling: An Empirical Study [[pdf]](https://arxiv.org/pdf/2112.04453.pdf) [[code]](https://github.com/easonnie/mlp-vil)
- **[RepMLPNet]** Hierarchical Vision MLP with Re-parameterized Locality [[pdf]](https://arxiv.org/pdf/2112.11081.pdf) [[code]](https://github.com/DingXiaoH/RepMLP)
- **[MAXIM]** Multi-Axis MLP for Image Processing [[pdf]](https://arxiv.org/pdf/2201.02973.pdf)
- **[ShiftViT]** An Extremely Simple Alternative to Attention Mechanism [[pdf]](https://arxiv.org/pdf/2201.10801.pdf) [[code]](https://github.com/microsoft/SPACH)
- Mixing and Shifting: Exploiting Global and Local Dependencies in Vision MLPs [[pdf]](https://arxiv.org/pdf/2202.06510.pdf) [[code]](https://github.com/JegZheng/MS-MLP)
- Efficient Language Modeling with Sparse all-MLP [[pdf]](https://arxiv.org/pdf/2203.06850.pdf)
- **[ActiveMLP]** An MLP-like Architecture with Active Token Mixer [[pdf]](https://arxiv.org/pdf/2203.06108.pdf) [[code]](https://github.com/microsoft/ActiveMLP)
- Brain-inspired Multilayer Perceptron with Spiking Neurons [[pdf]](https://arxiv.org/pdf/2203.14679.pdf) [[code]](https://gitee.com/mindspore/models/tree/master/research/cv/snn_mlp)
- **[DynaMixer]** A Vision MLP Architecture with Dynamic Mixing [[pdf]](https://arxiv.org/pdf/2201.12083.pdf)
- Boosting Adversarial Transferability of MLP-Mixer [[pdf]](https://arxiv.org/pdf/2204.12204.pdf)
- MetaFormer is Actually What You Need for Vision [[pdf]](https://arxiv.org/pdf/2111.11418.pdf) [[code]](https://github.com/sail-sg/poolformer)
- **[Sequencer]** Deep LSTM for Image Classification [[pdf]](https://arxiv.org/pdf/2205.01972.pdf)
- **[Sparse Mixers]** Combining MoE and Mixing to build a more efficient BERT [[pdf]](https://arxiv.org/pdf/2205.12399.pdf)
