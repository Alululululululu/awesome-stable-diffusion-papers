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
| [Blended Diffusion for Text-driven Editing of Natural Images](https://arxiv.org/abs/2111.14818) | CVPR | 2022 | [GitHub](https://github.com/omriav/blended-diffusion) |
| [DiffusionCLIP: Text-Guided Diffusion Models for Robust Image Manipulation](https://arxiv.org/abs/2110.02711) | CVPR | 2022 | [GitHub](https://github.com/gwang-kim/DiffusionCLIP) |
| [More Control for Free! Image Synthesis with Semantic Diffusion Guidance](https://arxiv.org/abs/2112.05744) | WACV | 2023 | [GitHub](https://github.com/xh-liu/SDG_code) |
| [Diffusion Models Already Have a Semantic Latent Space](https://arxiv.org/abs/2210.10960) | ICLR | 2023 | [GitHub](https://github.com/kwonminki/Asyrp_official) |
| [GLIGEN: Open-Set Grounded Text-to-Image Generation](https://arxiv.org/abs/2301.07093) | CVPR | 2023 | [GitHub](https://github.com/gligen/GLIGEN) |

## Text-to-Image Models Based on Implicit Classifiers
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598) | NeurIPS | 2021 | [GitHub](https://github.com/coderpiaobozhe/classifier-free-diffusion-guidance-Pytorch?tab=readme-ov-file) |
| [Multi-Concept Customization of Text-to-Image Diffusion](https://arxiv.org/abs/2212.04488) | CVPR | 2023 | [Project](https://www.cs.cmu.edu/~custom-diffusion/) |
| [Würstchen: An Efficient Architecture for Large-Scale Text-to-Image Diffusion Models](https://arxiv.org/abs/2306.00637) | ICLR oral | 2024| [GitHub](https://github.com/dome272/Wuerstchen) |

## Regulating Generation in Implicit Classifier-Guided Process
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Prompt-to-Prompt Image Editing with Cross-Attention Control](https://arxiv.org/abs/2208.01626) | ICLR | 2022 | [Project](https://prompt-to-prompt.github.io/) |
| [Imagic: Text-Based Real Image Editing with Diffusion Models](https://arxiv.org/abs/2210.09276) | CVPR | 2023 | [Project](https://imagic-editing.github.io/) |
| [UniTune: Text-Driven Image Editing by Fine Tuning an Image Generation Model on a Single Image](https://arxiv.org/abs/2210.09477) | TOG | 2023 | [GitHub](https://github.com/xuduo35/UniTune) |
| [DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation](https://arxiv.org/abs/2208.12242) | CVPR | 2023 | [GitHub](https://github.com/google/dreambooth) |
| [DiffEdit: Diffusion-based Semantic Image Editing with Mask Guidance](https://arxiv.org/abs/2210.11427) | ICLR | 2023 | [GitHub](https://github.com/Xiang-cd/DiffEdit-stable-diffusion) |

## Adding Conditional Control to Text-to-Image Diffusion Models
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Adding Conditional Control to Text-to-Image Diffusion Models](https://arxiv.org/abs/2302.05543) | ControlNet | 2023 | [GitHub](https://github.com/lllyasviel/ControlNet) |
| [Putting People in Their Place: Affordance-Aware Human Insertion into Scenes](https://arxiv.org/abs/2304.14406) | CVPR | 2023 | [GitHub](https://github.com/adobe-research/affordance-insertion) |
| [BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion](https://arxiv.org/abs/2307.10816) | ICCV | 2023 | [GitHub](https://github.com/showlab/BoxDiff) |

## Generative Models for Feature Learning and Pretraining
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [DreamTeacher: Pretraining Image Backbones with Deep Generative Models](https://arxiv.org/abs/2307.07487) | ICCV | 2023 |  |

## Text-to-Video Generation
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Tune-A-Video: One-Shot Tuning of Image Diffusion Models for Text-to-Video Generation](https://arxiv.org/abs/2212.11565) | ICCV | 2023 | [GitHub](https://github.com/showlab/Tune-A-Video) |
| [StyleInV: A Temporal Style Modulated Inversion Network for Unconditional Video Generation](https://arxiv.org/abs/2308.16909) | ICCV | 2023 | [GitHub](https://github.com/johannwyh/StyleInV) |
| [ControlVideo: Training-free Controllable Text-to-Video Generation](https://arxiv.org/abs/2305.13077) | ICLR | 2024 | [GitHub](https://github.com/YBYBZhang/ControlVideo) |

## Image Animation
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Person Image Synthesis via Denoising Diffusion Model](https://arxiv.org/abs/2211.12500) | CVPR | 2023 | [Project](https://github.com/ankanbhunia/PIDM) |
| [Conditional Image-to-Video Generation with Latent Flow Diffusion Models](https://arxiv.org/abs/2303.13744) | CVPR | 2023 | [GitHub](https://github.com/nihaomiao/CVPR23_LFDM) |
| [LEO: Generative Latent Image Animator for Human Video Synthesis](https://arxiv.org/abs/2305.03989) | arXiv | 2023 | [Project](https://wyhsirius.github.io/LEO-project/) |
| [DreamPose: Fashion Image-to-Video Synthesis via Stable Diffusion](https://grail.cs.washington.edu/projects/dreampose/static/pdfs/DreamPose.pdf) | ICCV | 2023 | [GitHub](https://grail.cs.washington.edu/projects/dreampose/) |

## Pose to Video Generation
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [DisCo: Disentangled Control for Realistic Human Dance Generation](https://arxiv.org/abs/2307.00040) | CVPR | 2024 | [Project](https://disco-dance.github.io/) |
| [Animate Anyone: Consistent and Controllable Image-to-Video Synthesis for Character Animation](https://arxiv.org/abs/2311.17117) | CVPR | 2024 | [Project](https://humanaigc.github.io/animate-anyone/) |
| [MagicAnimate: Temporally Consistent Human Image Animation using Diffusion Model](https://arxiv.org/abßs/2311.16498) | CVPR | 2024 | [Project](https://showlab.github.io/magicanimate/) |
| [UniAnimate: Taming Unified Video Diffusion Models for Consistent Human Image Animation](https://arxiv.org/abs/2406.01188) | arxiv | 2024 | [GitHub](https://github.com/ali-vilab/UniAnimate) |

## Stable Diffusion Series Models (Stability AI)
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752) v1.0| CVPR | 2022 | [GitHub](https://github.com/CompVis/latent-diffusion) |
| Stable Diffusion v2.0|  |  | [GitHub](https://github.com/Stability-AI/stablediffusion) |
| [Scaling Rectified Flow Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2403.03206) |  | 2024 | [Demo](https://huggingface.co/spaces/stabilityai/stable-diffusion-3-medium) |

## LoRA Series
| Title | Venue | Year | Link/Code |
| --- | --- | --- | --- |
| [Lora](https://arxiv.org/abs/2106.09685) | ICLR | 2022 | [GitHub](https://github.com/microsoft/LoRA) |
| [QLora](https://arxiv.org/abs/2305.14314) | NeurIPS | 2023 | [GitHub](https://github.com/artidoro/qlora) |
| [AdaLora](https://arxiv.org/abs/2303.10512) | ICLR | 2023 | [GitHub](https://github.com/QingruZhang/AdaLoRA) |
| [LongLora](https://arxiv.org/abs/2309.12307) | CVPR | 2023 | [GitHub](https://github.com/dvlab-research/LongLoRA) |
| [SLora](https://arxiv.org/abs/2308.06522) | NeurIPS Oral | 2023 | [GitHub](https://github.com/S-LoRA/S-LoRA) |
| [oLora](https://arxiv.org/abs/2406.01775) |  | 2024 |  |
