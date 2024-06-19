# Awesome Stable Diffusion Papers

A curated list of papers related to Stable Diffusion.

## Contributing
Please feel free to send me [pull requests](https://github.com/Alululululululu/awesome-stable-diffusion-papers/pulls) (or [issues](https://github.com/Alululululululu/awesome-stable-diffusion-papers/issues)) to add papers/talks/demo etc.

## Table of Contents
- [Basic Diffusion Models](#basic-diffusion-models)
- [Image Editing Based on Iterative Denoising Process](#image-editing-based-on-iterative-denoising-process)
- [Image Generation Guided by Explicit Classifiers](#image-generation-guided-by-explicit-classifiers)
- [Multimodal Image Generation Guided by CLIP Models](#multimodal-image-generation-guided-by-clip-models)
- [Text-to-Image Models Based on Implicit Classifiers](#text-to-image-models-based-on-implicit-classifiers)
- [Regulating Generation in Implicit Classifier-Guided Process](#regulating-generation-in-implicit-classifier-guided-process)
- [Adding Conditional Control to Text-to-Image Diffusion Models](#adding-conditional-control-to-text-to-image-diffusion-models)
- [Generative Models for Feature Learning and Pretraining](#generative-models-for-feature-learning-and-pretraining)
- [Text-to-Video Generation](#text-to-video-generation)
- [Image Animation](#image-animation)
- [Pose to Video Generation](#pose-to-video-generation)
- [Stable Diffusion Series Models (Stability AI)](#stable-diffusion-series-models-stability-ai)
- [LoRA Series](#lora-series)

## Basic Diffusion Models
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [DDPM: Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) | NeurIPS | 2020 | [GitHub](https://github.com/hojonathanho/diffusion) |
| [DDIM: Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502) | ICLR | 2021 | [GitHub](https://github.com/ermongroup/ddim) |
| [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/abs/2011.13456) | ICLR | 2021 | [GitHub](https://github.com/yang-song/score_sde) |
| [Improved Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2102.09672) | ICML | 2021 |[GitHub](https://github.com/openai/improved-diffusion?tab=readme-ov-file) |
| [Variational Diffusion Models](https://arxiv.org/abs/2107.00630) | NeurIPS | 2021 | [GitHub](https://github.com/addtt/variational-diffusion-models) |

## Image Editing Based on Iterative Denoising Process
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [IVLR: Conditioning Method for Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2108.02938) | ICCV Oral | 2021 | [GitHub](https://github.com/jychoi118/ilvr_adm) |
| [SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations](https://arxiv.org/abs/2108.01073) | ICLR | 2022 | [Project](https://sde-image-editing.github.io/) |
| [RePaint: Inpainting using Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2201.09865) | CVPR | 2022 | [GitHub](https://github.com/andreas128/RePaint) |

## Image Generation Guided by Explicit Classifiers
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Diffusion Models Beat GANs on Image Synthesis](https://arxiv.org/abs/2105.05233) | NeurIPS | 2021 | [GitHub](https://github.com/openai/guided-diffusion) |

## Multimodal Image Generation Guided by CLIP Models
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [More Control for Free! Image Synthesis with Semantic Diffusion Guidance](https://arxiv.org/abs/2112.05744) | WACV | 2023 | [GitHub](https://github.com/xh-liu/SDG_code) |
| [Blended Diffusion for Text-driven Editing of Natural Images](https://arxiv.org/abs/2111.14818) | CVPR | 2022 | [GitHub](https://github.com/omriav/blended-diffusion) |
| [DiffusionCLIP: Text-Guided Diffusion Models for Robust Image Manipulation](https://arxiv.org/abs/2110.02711) | CVPR | 2022 | [GitHub](https://github.com/gwang-kim/DiffusionCLIP) |
| [Diffusion Models Already Have a Semantic Latent Space](https://arxiv.org/abs/2210.10960) | ICLR | 2023 | [GitHub](https://github.com/kwonminki/Asyrp_official) |
| [GLIGEN: Open-Set Grounded Text-to-Image Generation](https://arxiv.org/abs/2208.11919) | CVPR | 2023 | [GitHub](https://github.com/gligen/GLIGEN) |

## Text-to-Image Models Based on Implicit Classifiers
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598) | | | |
| [Multi-Concept Customization of Text-to-Image Diffusion](https://arxiv.org/abs/2205.12952) | | | |
| [Würstchen: An Efficient Architecture for Large-Scale Text-to-Image Diffusion Models](https://arxiv.org/abs/2208.13753) | | | |

## Regulating Generation in Implicit Classifier-Guided Process
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Imagic: Text-Based Real Image Editing with Diffusion Models](https://arxiv.org/abs/2210.09276) | | | |
| [UniTune: Text-Driven Image Editing by Fine Tuning an Image Generation Model on a Single Image](https://arxiv.org/abs/2205.12952) | | | |
| [DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation](https://arxiv.org/abs/2208.12242) | | | |
| [DiffEdit: Diffusion-based Semantic Image Editing with Mask Guidance](https://arxiv.org/abs/2210.11427) | CVPR | 2023 | [GitHub](https://github.com/google-research/editable-diffusion) |
| [Prompt-to-Prompt Image Editing with Cross-Attention Control](https://arxiv.org/abs/2208.01626) | NeurIPS | 2022 | [GitHub](https://github.com/google/prompt-to-prompt) |

## Adding Conditional Control to Text-to-Image Diffusion Models
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Adding Conditional Control to Text-to-Image Diffusion Models](https://arxiv.org/abs/2302.05543) | ControlNet | 2023 | [GitHub](https://github.com/lllyasviel/ControlNet) |
| [Putting People in Their Place: Affordance-Aware Human Insertion into Scenes](https://arxiv.org/abs/2303.11100) | CVPR | 2023 | [GitHub](https://github.com/edwardsmith8/PuttingPeopleInTheirPlace) |
| [BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion](https://arxiv.org/abs/2303.08933) | ICCV | 2023 | [GitHub](https://github.com/boxdiff/boxdiff) |

## Generative Models for Feature Learning and Pretraining
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [DreamTeacher: Pretraining Image Backbones with Deep Generative Models](https://arxiv.org/abs/2212.10841) | ICCV | 2023 | [GitHub](https://github.com/NVlabs/DreamTeacher) |

## Text-to-Video Generation
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation](https://arxiv.org/abs/2212.11565) | CVPR | 2023 | [GitHub](https://github.com/showlab/Tune-A-Video) |
| [StyleInV: A Temporal Style Modulated Inversion Network for Unconditional Video Generation](https://arxiv.org/abs/2205.15996) | ICCV | 2023 | [GitHub](https://github.com/TencentARC/StyleInV) |
| [ControlVideo: Training-free Controllable Text-to-Video Generation](https://arxiv.org/abs/2302.03037) | ICLR | 2024 | [GitHub](https://github.com/showlab/ControlVideo) |

## Image Animation
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Person image synthesis via denoising diffusion model](https://arxiv.org/abs/2207.12768) | ECCV | 2022 | [GitHub](https://github.com/waylonflinn/DDPM) |
| [Conditional image-to-video generation with latent flow diffusion models](https://arxiv.org/abs/2212.00552) | CVPR | 2023 | [GitHub](https://github.com/LTTM/conditional-image-to-video) |
| [Leo: Generative latent image animator for human video synthesis](https://arxiv.org/abs/2210.05466) | CVPR | 2023 | [GitHub](https://github.com/showlab/Leo) |
| [Dreampose: Fashion video synthesis with stable diffusion](https://arxiv.org/abs/2303.08134) | CVPR | 2023 | [GitHub](https://github.com/showlab/Dreampose) |

## Pose to Video Generation
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Disco: Disentangled control for referring human dance generation in real world](https://arxiv.org/abs/2304.07831) | CVPR | 2023 | [GitHub](https://github.com/showlab/Disco) |
| [Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation](https://arxiv.org/abs/2303.11114) | ICCV | 2023 | [GitHub](https://github.com/showlab/Animate-Anyone) |
| [Magicanimate: Temporally consistent human image animation using diffusion model](https://arxiv.org/abs/2303.09833) | arXiv | 2023 | [GitHub](https://github.com/showlab/Magicanimate) |
| [UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation](https://arxiv.org/abs/2303.11277) | CVPR | 2023 | [GitHub](https://github.com/showlab/UniAnimate) |

## Stable Diffusion Series Models (Stability AI)
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) | CVPR | 2022 | [GitHub](https://github.com/CompVis/latent-diffusion) |
| [Stable Diffusion](https://github.com/Stability-AI/stablediffusion) | GitHub | v2.0 | [GitHub](https://github.com/CompVis/stable-diffusion) |
| [Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2304.05200) | CVPR | 2023 | [GitHub](https://github.com/showlab/rectified-flow) |

## LoRA Series
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Lora](https://arxiv.org/abs/2106.09685) | ICLR | 2021 | [GitHub](https://github.com/microsoft/lora) |
| [QLora](https://arxiv.org/abs/2208.12242) | NeurIPS | 2022 | [GitHub](https://github.com/showlab/qlora) |
| [AdaLora](https://arxiv.org/abs/2303.11304) | ICLR | 2023 | [GitHub](https://github.com/showlab/adalora) |
| [LongLora](https://arxiv.org/abs/2304.02709) | CVPR | 2023 | [GitHub](https://github.com/showlab/longlora) |
| [SLora](https://arxiv.org/abs/2304.02719) | CVPR | 2023 | [GitHub](https://github.com/showlab/slora) |
| [oLora](https://arxiv.org/abs/2304.02725) | CVPR | 2023 | [GitHub](https://github.com/showlab/olora) |
