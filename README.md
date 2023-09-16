# Awesome Face Restoration & Enhancement
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![collection](https://img.shields.io/badge/Collection-Keep%20Updating-green) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=sczhou/Awesome-Face-Restoration)


A curated list of awesome face restoration & enhancement papers and resources :whale:, inspired by [awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF). 

#### Welcome to add papers and other resources related to this topic [[submit a pull request]](https://github.com/sczhou/Awesome-Face-Restoration/blob/master/how-to-PR.md) :hugs:

## Table of Contents

- [Papers](#papers)
  - [Face Image Restoration](#face-image-restoration)
  - [Face Video Restoration](#face-video-restoration)
- [Datasets](#datasets)
    - [High-Res Face Dataset](#high-resolution-face-dataset)
    - [Low-Res Face Dataset](#low-resolution-face-dataset)
    - [Video Face Dataset](#video-face-dataset)
    - [Other Face Dataset](#other-face-dataset)

## Papers

### Face Image Restoration

#### Diffusion Model

- `[CVPR 2023]` DR2: Diffusion-based Robust Degradation Remover for Blind Face Restoration, Wang et al. [Paper](https://arxiv.org/abs/2303.06885) | [Bibtex](./facebib.bib#L114-L119) 
- `[Arxiv 2022]` DifFace: Blind Face Restoration with Diffused Error Contraction, Yue et al. [Paper](https://arxiv.org/abs/2212.06512) | [Github](https://github.com/zsyOAOA/DifFace) | [Demo](https://huggingface.co/spaces/OAOA/DifFace) | [Bibtex](./facebib.bib#L121-L127)

#### Generative Prior - VQGAN
- `[NeurIPS 2022]` CodeFormer: Towards Robust Blind Face Restoration with Codebook Lookup Transformer, Zhou et al. [Paper](https://arxiv.org/abs/2206.11253) | [Project](https://shangchenzhou.com/projects/CodeFormer/) | [Github](https://github.com/sczhou/CodeFormer) | [Demo](https://huggingface.co/spaces/sczhou/CodeFormer) | [Bibtex](./facebib.bib#L1-L6)

- `[ECCV 2022]` VQFR: Blind Face Restoration with Vector-Quantized Dictionary and Parallel Decoder, Gu et al. [Paper](https://arxiv.org/abs/2205.06803) | [Project](https://ycgu.site/projects/vqfr/) | [Github](https://github.com/sczhou/CodeFormer) | [Bibtex](./facebib.bib#L8-L13)

- `[CVPR 2022]` RestoreFormer: High-Quality Blind Face Restoration from Undegraded Key-Value Pairs, Wang et al. [Paper](https://arxiv.org/abs/2201.06374) | [Github](https://github.com/wzhouxiff/RestoreFormer) | [Bibtex](./facebib.bib#L15-L20)

- `[CVPR 2022]` Rethinking Deep Face Restoration. Zhao et al. [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhao_Rethinking_Deep_Face_Restoration_CVPR_2022_paper.pdf) | [Bibtex](./facebib.bib#L85-L91)

#### Generative Prior - StyleGAN2
- `[CVPR 2021]` GFPGAN: Towards Real-World Blind Face Restoration with Generative Facial Prior, Wang et al. [Paper](https://arxiv.org/abs/2101.04061) | [Project](https://xinntao.github.io/projects/gfpgan) | [Github](https://github.com/TencentARC/GFPGAN) | [Demo](https://huggingface.co/spaces/Xintao/GFPGAN) | [Bibtex](./facebib.bib#L43-L48)

- `[CVPR 2021]` GLEAN: Generative Latent Bank for Large-Factor Image Super-Resolution, Chan et al. [Paper](https://arxiv.org/abs/2012.00739) | [Project](https://mmlab-ntu.github.io/project/glean/) | [Github](https://github.com/open-mmlab/mmediting) | [Bibtex](./facebib.bib#L36-L41)

- `[CVPR 2021]` GPEN: GAN Prior Embedded Network for Blind Face Restoration in the Wild, Yang et al. [Paper](https://arxiv.org/abs/2105.06070) | [Github](https://github.com/yangxy/GPEN) | [Bibtex](./facebib.bib#L50-L55)

#### GAN Inversion
- `[CVPR 2020]` PULSE: Self-Supervised Photo Upsampling via Latent Space Exploration of Generative Models, Menon et al. [Paper](https://arxiv.org/abs/2003.03808) | [Github](https://github.com/adamian98/pulse) | [Bibtex](./facebib.bib#L64-L69)


#### Dictionary Learning
- `[TPAMI 2022]` DMDNet: Learning Dual Memory Dictionaries for Blind Face Restoration, Li et al. [Paper](https://arxiv.org/abs/2210.08160) | [Github](https://github.com/csxmli2016/DMDNet) | [CelebRef-HQ Dataset](https://github.com/csxmli2016/DMDNet#celebref-hq-dataset) | [Bibtex](./facebib.bib#L107-L112)
- `[ECCV 2020]` DFDNet: Blind Face Restoration via Deep Multi-scale Component Dictionaries, Li et al. [Paper](https://arxiv.org/abs/2008.00418) | [Github](https://github.com/csxmli2016/DFDNet) | [Bibtex](./facebib.bib#L22-L27)

#### Reference/Exemplar Prior
- `[CVPR 2020]` ASFFNet: Enhanced Blind Face Restoration With Multi-Exemplar Images and Adaptive Spatial Feature Fusion, Li et al. [Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Li_Enhanced_Blind_Face_Restoration_With_Multi-Exemplar_Images_and_Adaptive_Spatial_CVPR_2020_paper.pdf) | [Github](https://github.com/csxmli2016/ASFFNet) | [Bibtex](./facebib.bib#L57-L62)

#### Geometry Facial Prior
- `[CVPR 2021]` PSFRGAN: Progressive Semantic-Aware Style Transformation for Blind Face Restoration, Chen et al. [Paper](https://arxiv.org/abs/2009.08709) | [Github](https://github.com/chaofengc/PSFRGAN) | [Bibtex](./facebib.bib#L29-L34)

#### 3D Face Shape Prior
- `[CVPR 2022]` SGPN: Blind Face Restoration via Integrating Face Shape and Generative Priors, Zhu et al. [Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Zhu_Blind_Face_Restoration_via_Integrating_Face_Shape_and_Generative_Priors_CVPR_2022_paper.pdf) | [Bibtex](./facebib.bib#L71-L76)

#### Personalized Restoration
- `[ArXiv 2022]` MyStyle: A Personalized Generative Prior, Nitzan et al. [Paper](https://arxiv.org/abs/2203.17272) | [Github](https://github.com/google/mystyle) | [Project](https://mystyle-personalized-prior.github.io/) | [Bibtex](./facebib.bib#L78-L83)

#### Others 

- `[TIP 2020]` Learning Spatial Attention for Face Super-Resolution, Chen et al. [Paper](https://arxiv.org/abs/2012.01211) | [Github](https://github.com/chaofengc/Face-SPARNet) | [Bibtex](./facebib.bib#L93-L98)


&nbsp;

### Face Video Restoration

- `[CVPRW 2022]` VFHQ: A High-Quality Dataset and Benchmark for Video Face Super-Resolution, Xie et al. [Paper](https://arxiv.org/abs/2205.03409) | [Project](https://liangbinxie.github.io/projects/vfhq/) | [Bibtex](./facebib.bib#L100-L105)

## Datasets
#### High-Resolution Face Dataset
| Dataset | Resolution | Description |
| :---: | :---: | :----------    |
| [FFHQ](https://github.com/NVlabs/ffhq-dataset) | 1024 x 1024 | 7,0000 high-quality face images (usually used for training) |
| [CelebA-HQ](https://github.com/nperraud/download-celebA-HQ) | 1024 x 1024 | 3,0000 high-quality face images (usually used for evaluation) |
| [CelebAMask-HQ](https://github.com/switchablenorms/CelebAMask-HQ) | 512 x 512 | 3,0000 face images with 19 facial classes |
| [CelebRef-HQ](https://github.com/csxmli2016/DMDNet#celebref-hq-dataset) | 512 x 512 | high-quality face images with multiple same-identity references |

#### Low-Resolution Face Dataset

| Dataset | Description |
| :---: | :----------    |
| [CelebA](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)  | a large-scale face attributes dataset with more than 200K celebrity images |
| [WIDER-Test](https://shangchenzhou.com/projects/CodeFormer/)  | 970 real-world severely degraded face images from the [WIDER Face dataset](http://shuoyang1213.me/WIDERFACE/) (for test)|
| [LFW-Test](https://xinntao.github.io/projects/gfpgan)  | 1711 real-world degraded faces collected from the [LFW dataset](https://vis-www.cs.umass.edu/lfw/) (for test)|
| [WebPhoto-Test](https://xinntao.github.io/projects/gfpgan)  | 407 real-world degraded faces collected from the Internet (for test)|
| [CelebChild-Test](https://xinntao.github.io/projects/gfpgan)  | 180 real-world degraded child faces collected from the Internet (for test)|

#### Video Face Dataset
| Dataset | Description |
| :---: | :----------    |
| [TalkingHead-1KH](https://github.com/tcwang0509/TalkingHead-1KH)  | 500k video clips, of which about 80k are greater than 512x512 resolution |
| [VFHQ](https://liangbinxie.github.io/projects/vfhq)  | 16,000 high-fidelity clips of diverse interview scenarios |
| [CelebV-HQ](https://celebv-hq.github.io/)  | 35,666 video clips involving 15,653 identities and 83 manually labeled facial attributes |
| [CelebV-Text](https://celebv-text.github.io/)  | 70,000 in-the-wild face video clips covering diverse visual content |



#### Other Face Dataset
| Dataset | Description |
| :---: | :----------    |
| [CelebA-Dialog](https://github.com/ziqihuangg/CelebA-Dialog)  | a large-scale visual-language face dataset with fine-grained labels and captions|
| [CelebA-Spoof](https://github.com/ZhangYuanhan-AI/CelebA-Spoof)  | a large-scale face anti-spoofing dataset with rich attributes and spoof types|
| [PPR10K](https://github.com/csjliang/PPR10K)  | a large-scale portrait photo retouching dataset |