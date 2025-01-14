# Diffusion Models in Vision: A Survey
Denoising diffusion models represent a recent emerging topic in computer vision, demonstrating remarkable results in the area of generative modeling. A diffusion model is a deep generative model that is based on two stages, a forward diffusion stage and a reverse diffusion stage. In the forward diffusion stage, the input data is gradually perturbed over several steps by adding Gaussian noise. In the reverse stage, a model is tasked at recovering the original input data by learning to gradually reverse the diffusion process, step by step. Diffusion models are widely appreciated for the quality and diversity of the generated samples, despite their known computational burdens, i.e. low speeds due to the high number of steps involved during sampling. This repository categorizes the papers about diffusion models, applied in computer vision, according to their target task. The classifcation is based on our survey [Diffusion Models in Vision: A Survey](https://arxiv.org/abs/2209.04747v2)

## Summary

1. [Unconditional Generation](#1)
2. [Conditional Generation](#2)
3. [Text-to-Image generation ](#3)
4. [Super-Resolution ](#4)
5. [Image Editing](#5)
6. [Region Image Editing](#6)
7. [Inpainting](#7)
8. [Image-to-Image Translation](#8)
9. [Image Segmentation ](#9)
10. [Multi-Task](#10)
11. [Medical Image-to-Image Translation](#11)
12. [Medical Image Generation](#12)
13. [Medical Image Segmentation](#13)
14. [Medical Image Anomaly Detection](#14)
15. [Video Generation](#15)
16. [Few-Shot Image Generation ](#16)
17. [Counterfactual Explanations and Estimations](#17)
18. [Image Restoration](#18)
19. [Image Registration](#19)
20. [Adversarial Purification](#20)
21. [Semantic Image Generation](#21)
22. [Shape Generation and Completion](#22)
23. [Classification](#23)
24. [Point Cloud Generation](#24)
25. [Theoretical](#25)

## Content

### Unconditional Generation <a name="1"></a>
  1. [Deep unsupervised learning using non-equilibrium thermodynamics](https://arxiv.org/pdf/1503.03585.pdf)
  2. [Denoising diffusion probabilistic models](https://arxiv.org/pdf/2006.11239.pdf)
  3. [Improved techniques for training score-based generative models](https://arxiv.org/pdf/2006.09011.pdf)
  4. [Adversarial score matching and improved sampling for image generation](https://arxiv.org/pdf/2009.05475.pdf)
  5. [Maximum likelihood training of score-based diffusion models](https://proceedings.neurips.cc/paper/2021/file/0a9fdbb17feb6ccb7ec405cfb85222c4-Paper.pdf)
  6. [D2C: Diffusion-Decoding Models for Few-Shot Conditional Generation](https://proceedings.neurips.cc/paper/2021/file/682e0e796084e163c5ca053dd8573b0c-Paper.pdf)
  7. [Diffusion Normalizing Flow](https://proceedings.neurips.cc/paper/2021/file/876f1f9954de0aa402d91bb988d12cd4-Paper.pdf)
  8. [Diffusion Schrodinger bridge with applications to score-based generative modeling](https://proceedings.neurips.cc/paper/2021/file/940392f5f32a7ade1cc201767cf83e31-Paper.pdf)
  9. [Structured denoising diffusion models in discrete state-spaces](https://proceedings.neurips.cc/paper/2021/file/958c530554f78bcd8e97125b70e6973d-Paper.pdf)
 10. [Score-based generative modeling in latent space](https://papers.nips.cc/paper/2021/file/5dca4c6b9e244d24a30b4c45601d9720-Paper.pdf)
 11. [Improved denoising diffusion probabilistic models](https://arxiv.org/pdf/2102.09672.pdf)
 12. [Denoising Diffusion Implicit Models](https://arxiv.org/pdf/2010.02502.pdf)
 13. [Non-Gaussian denoising diffusion models](https://arxiv.org/pdf/2106.07582.pdf)
 14. [Bilateral denoising diffusion models](https://arxiv.org/pdf/2108.11514.pdf)
 15. [Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes](https://arxiv.org/pdf/2111.12701.pdf)
 16. [Noise estimation for generative diffusion models](https://arxiv.org/pdf/2104.02600.pdf)
 17. [Gotta go fast when generating data with score-based models](https://arxiv.org/pdf/2105.14080.pdf)
 18. [Learning to efficiently sample from diffusion probabilistic models](https://arxiv.org/pdf/2106.03802.pdf)
 19. [Deep generative learning via Schrodinger bridge](https://arxiv.org/pdf/2106.10410.pdf)
 20. [VAEs meet Diffusion Models: Efficient and High-Fidelity Generation](https://arxiv.org/pdf/2201.00308.pdf)
 21. [Variational diffusion models](https://arxiv.org/pdf/2107.00630.pdf)
 22. [Score-based generative modeling with critically-damped Langevin diffusion](https://arxiv.org/pdf/2112.07068.pdf)
 23. [Tackling the generative learning trilemma with Denoising Diffusion GANs](https://arxiv.org/pdf/2112.07804.pdf)
 24. [Heavy-tailed denoising score matching](https://arxiv.org/abs/2112.09788)
 25. [Analytic-DPM: an Analytic Estimate of the Optimal Reverse Variance in Diffusion Probabilistic Models](https://arxiv.org/pdf/2201.06503.pdf)
 26. [Learning Fast Samplers for Diffusion Models by Differentiating Through Sample Quality](https://arxiv.org/abs/2202.05830)
 27. [Truncated Diffusion Probabilistic Models](https://arxiv.org/abs/2202.09671)
 28. [Subspace Diffusion Generative Models](https://arxiv.org/abs/2205.01490)
 29. [Maximum Likelihood Training of Implicit Nonlinear Diffusion Models](https://arxiv.org/abs/2205.13699)
 30. [On Analyzing Generative and Denoising Capabilities of Diffusion-based Deep Generative Models](https://arxiv.org/abs/2206.00070)
 31. [Diffusion-GAN: Training GANs with Diffusion](https://arxiv.org/abs/2206.02262)
 32. [Accelerating Score-based Generative Models for High-Resolution Image Synthesis](https://arxiv.org/abs/2206.04029)
### Conditional Generation <a name="2"></a>
  1. [Diffusion models beat gans on image synthesis](https://openreview.net/pdf?id=AAWuCvzaVt)
  2. [Classifier-Free Diffusion Guidance](https://openreview.net/pdf?id=qw8AKxfYbI)
  3. [On Fast Sampling of Diffusion Probabilistic Models](https://arxiv.org/pdf/2106.00132.pdf)
  4. [DiffuseVAE: Efficient, Controllable and High-Fidelity Generation from Low-Dimensional Latents](https://arxiv.org/pdf/2201.00308.pdf)
  5. [Pseudo Numerical Methods for Diffusion Models on Manifolds](https://arxiv.org/pdf/2202.09778.pdf)
  6. [Cascaded Diffusion Models for High Fidelity Image Generation](https://www.jmlr.org/papers/volume23/21-0635/21-0635.pdf)
  7. [High Fidelity Visualization of What Your Self-Supervised Representation Knows About](https://arxiv.org/abs/2112.09164)
  8. [Itô-Taylor Sampling Scheme for Denoising Diffusion Probabilistic Models using Ideal Derivatives](https://arxiv.org/abs/2112.13339)
  9. [{Dynamic Dual-Output Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Benny_Dynamic_Dual-Output_Diffusion_Models_CVPR_2022_paper.pdf)
  10. [Generating High Fidelity Data from Low-density Regions using Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Sehwag_Generating_High_Fidelity_Data_From_Low-Density_Regions_Using_Diffusion_Models_CVPR_2022_paper.pdf)
  11. [Perception Prioritized Training of Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Choi_Perception_Prioritized_Training_of_Diffusion_Models_CVPR_2022_paper.pdf)
  12. [Elucidating the Design Space of Diffusion-Based Generative Models](https://arxiv.org/pdf/2206.00364.pdf)
  13. [Progressive distillation for fast sampling of diffusion models](https://arxiv.org/pdf/2202.00512.pdf)
  14. [Denoising Likelihood Score Matching for Conditional Score-based Data Generation](https://arxiv.org/abs/2203.14206)
  15. [On Conditioning the Input Noise for Controlled Image Generation with Diffusion Models](https://arxiv.org/abs/2205.03859)
  16. [A Continuous Time Framework for Discrete Denoising Models](https://arxiv.org/abs/2205.14987)
  17. [DPM-Solver: A Fast ODE Solver for Diffusion Probabilistic Model Sampling in Around 10 Steps](https://arxiv.org/abs/2206.00927)
  18. [Compositional Visual Generation with Composable Diffusion Models](https://arxiv.org/pdf/2206.01714.pdf)
### Text-to-Image generation <a name="3"></a>
  1. [Vector quantized diffusion model for text-to-image synthesis](https://openaccess.thecvf.com/content/CVPR2022/papers/Gu_Vector_Quantized_Diffusion_Model_for_Text-to-Image_Synthesis_CVPR_2022_paper.pdf)
  2. [Hierarchical text-conditional image generation with CLIP latents](https://arxiv.org/pdf/2204.06125.pdf)
  3. [Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://arxiv.org/pdf/2205.11487.pdf)
  4. [Fast Sampling of Diffusion Models with Exponential Integrator](https://arxiv.org/abs/2204.13902)
  5. [DiVAE: Photorealistic Images Synthesis with Denoising Diffusion Decoder](https://arxiv.org/pdf/2206.00386.pdf)
  6. [Text-Guided Synthesis of Artistic Images with Retrieval-Augmented Diffusion Models](https://arxiv.org/pdf/2207.13038.pdf)
  7. [Text2Human: Text-Driven Controllable Human Image Generation](https://arxiv.org/pdf/2205.15996.pdf)
  8. [DreamBooth: Fine Tuning Text-to-Image Diffusion Models for Subject-Driven Generation](https://arxiv.org/pdf/2208.12242.pdf)
### Super-Resolution <a name="4"></a>
  1. [Image super-resolution via iterative refinement](https://arxiv.org/pdf/2104.07636.pdf)
  2. [Score-based Generative Neural Networks for Large-Scale Optimal Transport](https://arxiv.org/pdf/2110.03237.pdf)
### Image Editing<a name="5"></a>
  1. [SDEdit: Guided Image Synthesis and Editing with Stochastic Differential Equations](https://arxiv.org/abs/2108.01073)
  2. [Blended Latent Diffusion](https://arxiv.org/pdf/2206.02779.pdf)
### Region Image Editing <a name="6"></a>
  1. [Blended diffusion for text-driven editing of natural images](https://openaccess.thecvf.com/content/CVPR2022/papers/Avrahami_Blended_Diffusion_for_Text-Driven_Editing_of_Natural_Images_CVPR_2022_paper.pdf)
### Inpainting <a name="7"></a>
  1. [GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models](https://arxiv.org/pdf/2112.10741.pdf)
  2. [RePaint: Inpainting using Denoising Diffusion Probabilistic Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Lugmayr_RePaint_Inpainting_Using_Denoising_Diffusion_Probabilistic_Models_CVPR_2022_paper.pdf)
### Image-to-Image Translation <a name="8"></a>
  1. [Palette: Image-to-Image Diffusion Models](https://arxiv.org/pdf/2111.05826.pdf)
  2. [UNIT-DDPM: UNpaired Image Translation with Denoising Diffusion Probabilistic Models](https://arxiv.org/pdf/2104.05358.pdf)
  3. [EGSDE: Unpaired Image-to-Image Translation via Energy-Guided Stochastic Differential Equations](https://arxiv.org/pdf/2207.06635.pdf)
  4. [Pretraining is All You Need for Image-to-Image Translation](https://arxiv.org/pdf/2205.12952.pdf)
  5. [VQBB: Image-to-image Translation with Vector Quantized Brownian Bridge](https://arxiv.org/pdf/2205.07680.pdf)
  6. [The Swiss Army Knife for Image-to-Image Translation: Multi-Task Diffusion Models](https://arxiv.org/pdf/2204.02641.pdf)
### Image Segmentation <a name="9"></a>
  1. [Label-Efficient Semantic Segmentation with Diffusion Models](https://arxiv.org/abs/2112.03126)
  2. [SegDiff: Image Segmentation with Diffusion Probabilistic Models](https://arxiv.org/pdf/2112.00390.pdf)
### Multi-Task <a name="10"></a>
  1. [Generative modeling by estimating gradients of the data distribution](https://arxiv.org/pdf/1907.05600.pdf)
  2. [Score-Based Generative Modeling through Stochastic Differential Equations](https://arxiv.org/pdf/2011.13456.pdf)
  3. [ImageBART: Bidirectional Context with Multinomial Diffusion for Autoregressive Image Synthesis](https://openreview.net/pdf?id=-1AAgrS5FF)
  4. [Learning Energy-Based Models by Diffusion Recovery Likelihood](https://arxiv.org/pdf/2012.08125.pdf)
  5. [Conditional image generation with score-based diffusion models](https://arxiv.org/pdf/2111.13606.pdf)
  6. [More control for free! Image synthesis with semantic diffusion guidance](https://arxiv.org/pdf/2112.05744.pdf)
  7. [ILVR: Conditioning Method for Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2108.02938)
  8. [Global Context with Discrete Diffusion in Vector Quantised Modelling for Image Generation](https://arxiv.org/pdf/2112.01799.pdf)
  9. [High-Resolution Image Synthesis with Latent Diffusion Models](https://openaccess.thecvf.com/content/CVPR2022/papers/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.pdf)
  10. [Diffusion Autoencoders: Toward a Meaningful and Decodable Representation](https://openaccess.thecvf.com/content/CVPR2022/papers/Preechakul_Diffusion_Autoencoders_Toward_a_Meaningful_and_Decodable_Representation_CVPR_2022_paper.pdf)
  11. [Come-Closer-Diffuse-Faster: Accelerating Conditional Diffusion Models for Inverse Problems through Stochastic Contraction](https://openaccess.thecvf.com/content/CVPR2022/papers/Chung_Come-Closer-Diffuse-Faster_Accelerating_Conditional_Diffusion_Models_for_Inverse_Problems_Through_Stochastic_CVPR_2022_paper.pdf)
  12. [DiffusionCLIP: Text-Guided Diffusion Models for Robust Image Manipulation](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_DiffusionCLIP_Text-Guided_Diffusion_Models_for_Robust_Image_Manipulation_CVPR_2022_paper.pdf)
  13. [Understanding DDPM Latent Codes Through Optimal Transport](https://arxiv.org/abs/2202.07477)
  14. [Conditional Simulation Using Diffusion Schrödinger Bridges](https://arxiv.org/abs/2202.13460)
  15. [Retrieval-Augmented Diffusion Models](https://arxiv.org/abs/2204.11824)
  16. [Accelerating Diffusion Models via Early Stop of the Diffusion Process](https://arxiv.org/abs/2205.12524)
  17. [Diffusion Models as Plug-and-Play Priors](https://arxiv.org/pdf/2206.09012.pdf)
  18. [Non-Uniform Diffusion Models](https://arxiv.org/pdf/2207.09786.pdf)
### Medical Image-to-Image Translation <a name="11"></a>
  1. [Unsupervised Medical Image Translation with Adversarial Diffusion Models](https://arxiv.org/pdf/2207.08208.pdf)
  2. [Unsupervised Denoising of Retinal OCT with Diffusion Probabilistic Model](https://arxiv.org/pdf/2201.11760.pdf)
### Medical Image Generation <a name="12"></a>
  1. [Solving inverse problems in medical imaging with score-based generative models](https://arxiv.org/pdf/2111.08005.pdf)
  2. [Score-based diffusion models for accelerated MRI](https://arxiv.org/pdf/2110.05243.pdf)
### Medical Image Segmentation <a name="13"></a>
  1. [Diffusion Models for Implicit Image Segmentation Ensembles](https://arxiv.org/pdf/2112.03145.pdf)
### Medical Image Anomaly Detection <a name="14"></a>
  1. [Diffusion Models for Medical Anomaly Detection](https://arxiv.org/pdf/2203.04306.pdf)
  2. [Fast Unsupervised Brain Anomaly Detection and Segmentation with Diffusion Models](https://arxiv.org/pdf/2206.03461.pdf)
  3. [AnoDDPM: Anomaly Detection With Denoising Diffusion Probabilistic Models Using Simplex Noise](https://openaccess.thecvf.com/content/CVPR2022W/NTIRE/papers/Wyatt_AnoDDPM_Anomaly_Detection_With_Denoising_Diffusion_Probabilistic_Models_Using_Simplex_CVPRW_2022_paper.pdf)
  4. [What is Healthy? Generative Counterfactual Diffusion for Lesion Localization](https://arxiv.org/pdf/2207.12268.pdf)
### Video Generation <a name="15"></a>
  1. [Video Diffusion Models](https://arxiv.org/pdf/2204.03458.pdf)
  2. [Diffusion Probabilistic Modeling for Video Generation](https://arxiv.org/pdf/2203.09481.pdf)
  3. [Flexible Diffusion Modeling of Long Videos](https://arxiv.org/pdf/2205.11495.pdf)
  4. [Diffusion Models for Video Prediction and Infilling](https://arxiv.org/pdf/2206.07696.pdf)
### Few-Shot Image Generation <a name="16"></a>
  1. [Few-Shot Diffusion Models](https://arxiv.org/abs/2205.15463)
### Counterfactual Explanations and Estimations <a name="17"></a>
  1. [Diffusion Models for Counterfactual Explanations](https://arxiv.org/pdf/2203.15636.pdf)
  2. [Diffusion Causal Models for Counterfactual Estimation](https://proceedings.mlr.press/v177/sanchez22a/sanchez22a.pdf)
### Image Restoration <a name="18"></a>
  1. [Restoring Vision in Adverse Weather Conditions with Patch-Based Denoising Diffusion Models](https://arxiv.org/pdf/2207.14626.pdf)
  2. [Denoising Diffusion Restoration Models](https://arxiv.org/pdf/2201.11793.pdf)
### Image Registration <a name="19"></a>
  1. [DiffuseMorph: Unsupervised Deformable Image Registration Along Continuous Trajectory Using Diffusion Models](https://arxiv.org/pdf/2112.05149.pdf)
### Adversarial Purification <a name="20"></a>
  1. [Diffusion Models for Adversarial Purification](https://arxiv.org/pdf/2205.07460.pdf)
### Semantic Image Generation <a name="21"></a>
  1. [Semantic Image Synthesis via Diffusion Models](https://arxiv.org/pdf/2207.00050.pdf)
### Shape Generation and Completion <a name="22"></a>
  1. [3D shape generation and completion through point-voxel diffusion](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_3D_Shape_Generation_and_Completion_Through_Point-Voxel_Diffusion_ICCV_2021_paper.pdf)
### Classification <a name="23"></a>
  1. [Score-based generative classifiers](https://arxiv.org/pdf/2110.00473.pdf)
### Point Cloud Generation <a name="24"></a>
  1. [Diffusion Probabilistic Models for 3D Point Cloud Generation](https://openaccess.thecvf.com/content/CVPR2021/papers/Luo_Diffusion_Probabilistic_Models_for_3D_Point_Cloud_Generation_CVPR_2021_paper.pdf)
### Theoretical <a name="25"></a>
  1. [A variational perspective on diffusion-based generative models and score matching](https://proceedings.neurips.cc/paper/2021/file/c11abfd29e4d9b4d4b566b01114d8486-Paper.pdf)
