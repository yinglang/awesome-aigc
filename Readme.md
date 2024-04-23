
# Layout Generation [Awesome-Layout-Generators](https://github.com/JosephKJ/Awesome-Layout-Generators)

Performance on RICO dataset (conditioned on element category):

Model | FID↓ | IoU↓ | Alignment↓ | Overlap↓| Sim.↑ | Max. IoU↑ 
---|---|---|---|---|---|---
conditioned on element category| 
L-VAE [19] | 122±19 | 0.41±1.5%  | 0.38±1.9% | 0.39±2.3% | 0.13±1.5%
NDN [24]   | 97±21  |  0.37±1.7% | 0.41±1.6% | 0.36±1.9% | 0.15±2.3%
Trans. [15]| 76±24  | 0.31±0.2%  | 0.30±0.8% | 0.33±0.8% | 0.20±0.1%
VTN [1]    | 82±23  | 0.30±0.1%  | 0.32±0.9% | 0.30±0.3% | 0.20±0.1%
[BLT](https://arxiv.org/pdf/2112.05112.pdf)        | 70±29  | 0.30±0.4%  | 0.20±1.1% | 0.23±0.2% | 0.21±0.2%
[empty] |
conditioned on element category + size|
L-VAE [19] | 76     |            |           |           | 0.19
NDN [24]   | 63     |            |           |           | 0.21
[BLT](https://arxiv.org/pdf/2112.05112.pdf)        | 26     |            |           |           | 0.30

LayoutGAN-W | 162.75±0.28 | 0.30±0.00 | 0.71±0.00 | 174.11±0.22 |
LayoutGAN-R | 52.01±0.62  | 0.24±0.00 | 1.13±0.04 | 69.37±0.66  |
NDN-none    | 13.76±0.28  | 0.35±0.00 | 0.56±0.03 | 54.75±0.29  |
LayoutGAN++ | 14.43±0.13  | 0.36±0.00 | 0.60±0.12 | 59.85±0.59  |
VTN         | 9.31±0.21   | 0.36±0.00 | 0.88±0.11 | 59.31±0.45  |
[LayoutDM](https://arxiv.org/pdf/2305.02567.pdf)    | 3.03±0.06   | 0.49±0.00 | 0.36±0.06 | 57.55±0.48  |
Real data   | 4.47        |0.65       | 0.26      | 50.58       |

Selected papers:

- LayoutDiffusion: Improving Graphic Layout Generation by Discrete Diffusion Probabilistic Models (ICCV 2023, microsoft) [paper](https://arxiv.org/abs/2303.11589) [code](https://github.com/microsoft/LayoutGeneration)
- Geometry Aligned Variational Transformer for Image-conditioned Layout Generation (AAAI 2022) [paper]()

# Reports

- [北大最新综述精读：RAG在AIGC中的前世今生，覆盖300篇论文！](https://mp.weixin.qq.com/s/FKv9glaGZD0qbLmB2zg6bg) [Demo]


# Friendship Link (Awesome collections)

- [JosephKJ/Awesome-Layout-Generators](https://github.com/JosephKJ/Awesome-Layout-Generators)
- [codingonion/awesome-llm-and-aigc](https://github.com/codingonion/awesome-llm-and-aigc): paper collections.
- [luban-agi/Awesome-AIGC-Tutorials](https://github.com/luban-agi/Awesome-AIGC-Tutorials): courses for Prompt Engineering, LLM, AI Painting.
- [wshzd/Awesome-AIGC)](https://github.com/wshzd/Awesome-AIGC): 大模型在垂直领域的应用和微调、部署教程.
