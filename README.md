# Amazing Generative Models

## Walk into Generative Models
1. [What are Diffusion Models](https://lilianweng.github.io/posts/2021-07-11-diffusion-models/)
	* Supplementary papers
	1. [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
	2. [Denoising Diffusion Implicit Models](https://arxiv.org/pdf/2010.02502)
	3. [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)
2. [An Introduction to Flow Matching](https://mlg.eng.cam.ac.uk/blog/2024/01/20/flow-matching.html)
	* Supplementary papers
	1. [Flow Matching for Generative Modeling](https://arxiv.org/abs/2210.02747)
	2. [Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow](https://arxiv.org/abs/2209.03003)

## Works
### Principle
#### Mean Flows for One-step Generative Modeling (NeurIPS 2025) [[Paper]](https://arxiv.org/abs/2505.13447) [[Code]](https://github.com/Gsunshine/meanflow)
* Compute straight marginal flow from conditional flow to achieve one-step inference.

#### Diffusion Transformers with Representation Autoencoders [[Homepage]](https://rae-dit.github.io/) [[Paper]](https://arxiv.org/abs/2510.11690) [[Code]](https://github.com/bytetriper/RAE)
* New form of image encoder for generative model, leverage strong semantic representation from pretrained foundation image encoder like DINOv2.

### Applications
#### Dynamic Typography: Bringing Text to Life via Video Diffusion Prior (ICCV 2025) [[Homepage]](https://animate-your-word.github.io/demo/) [[Paper]](https://arxiv.org/pdf/2404.11614) [[Code]](https://github.com/zliucz/animate-your-word) [[Demo]](https://animate-your-word.github.io/demo/dynamic_typography.mp4)
* Generate a dynamic typography based on video foundation model, optimized by SDS.

### 3D Generation & Representation
#### SparseFlex: High-Resolution and Arbitrary-Topology 3D Shape Modeling (ICCV 2025) [[Homepage]](https://xianglonghe.github.io/TripoSF/) [[Paper]](https://xianglonghe.github.io/TripoSF/assets/triposf.pdf) [[Code]](https://github.com/VAST-AI-Research/TripoSF)
* The SOTA work for sparse-structured (or VAE-based) latent representation.

### Video in 3D
#### ReCamMaster: Camera-Controlled Generative Rendering from A Single Video (ICCV 2025) [[Homepage]](https://jianhongbai.github.io/ReCamMaster/) [[Paper]](https://arxiv.org/pdf/2503.11647) [[Code]](https://github.com/KwaiVGI/ReCamMaster)
* Generating video in novel camera trajactory from reference video clips. (Btw, the clips in demo are nice)

### Generating in Other Ways
#### Discrete Distribution Network (ICLR 2025) [[Homepage]](https://discrete-distribution-networks.github.io/) [[Paper]](https://arxiv.org/abs/2401.00036) [[Code]](https://github.com/DIYer22/discrete_distribution_networks) [[Demo]](https://ddn-coloring-demo.diyer22.com/)
* Generating results by selecting candidate from cascade hierarchy network layers.

## Tools
### Conditioned Generation
1. [ControlNet++](https://github.com/xinsir6/ControlNetPlus)
A novel ControlNet Architecture and also a good practice, the repo provide 10+ pre-trained conditioned generative model.

## Development
