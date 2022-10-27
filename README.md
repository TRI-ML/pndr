# Photo-realistic Neural Domain Randomization

Official webpage of the ECCV 2022 paper "Photo-realistic Neural Domain Randomization" by the ML Team at [Toyota Research Institute (TRI)](https://www.tri.global/our-work/machine-learning).
[**[Full paper]**](https://arxiv.org/abs/2210.12682)

## Abstract
Synthetic data is a scalable alternative to manual supervision, but it requires overcoming the sim-to-real domain gap. This discrepancy between virtual and real worlds is addressed by two seemingly opposed approaches: improving the realism of simulation or foregoing realism entirely via domain randomization. In this paper, we show that the recent progress in neural rendering enables a new unified approach we call Photo-realistic Neural Domain Randomization (PNDR). We propose to learn a composition of neural networks that acts as a physics-based ray tracer generating high-quality renderings from scene geometry alone. Our approach is modular, composed of different neural networks for materials, lighting, and rendering, thus enabling randomization of different key image generation components in a differentiable pipeline. 
Once trained, our method can be combined with other methods and used to generate photo-realistic image augmentations online and significantly more efficiently than via traditional ray-tracing. We demonstrate the usefulness of PNDR through two downstream tasks: 6D object detection and monocular depth estimation. Our experiments show that training with PNDR enables generalization to novel scenes and significantly outperforms the state of the art in terms of real-world transfer.

https://user-images.githubusercontent.com/6319371/198254722-1895ede0-41d3-43c7-9078-3fa69137b910.mp4

## References

#### Photo-realistic Neural Domain Randomization (ECCV 2022)
*Sergey Zakharov\*, Rares Ambrus\*, Vitor Guizilini, Wadim Kehl, Adrien Gaidon*

```
@inproceedings{pndr,
author = {Sergey Zakharov and Rares Ambrus and Vitor Guizilini and Wadim Kehl and Adrien Gaidon},
title = {Photo-realistic Neural Domain Randomization},
booktitle = {European Conference on Computer Vision (ECCV)},
month = {October},
year = {2022}
}
```
