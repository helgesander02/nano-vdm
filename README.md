# nano-vdm

A minimal inference engine for video diffusion models on consumer GPUs and NPUs.

## References

**On-device video diffusion**

- Karnewar et al. *Neodragon: Mobile Video Generation using Diffusion Transformer.* arXiv:2511.06055, 2025. [paper](https://arxiv.org/abs/2511.06055) · [model](https://huggingface.co/Qualcomm-AI-Research/Neodragon)
- Ghafoorian et al. *MobileWan: Closing the Quality Gap for Mobile Video Diffusion.* arXiv:2607.06173, 2026. [paper](https://arxiv.org/abs/2607.06173)
- Shen et al. *HeteroVDiff: Pipelining Video Diffusion across Mobile NPU and GPU with Shared Weights.* arXiv:2610.16244, 2026. [paper](https://arxiv.org/abs/2610.16244)
- Huang et al. *CineMobile: On-Device Image-to-Video Diffusion for Cinematic Camera Motion Generation.* arXiv:2607.03803, 2026. [paper](https://arxiv.org/abs/2607.03803)
- *Mobile Video Diffusion.* arXiv:2412.07583, 2024. [paper](https://arxiv.org/abs/2412.07583)

**On-device diffusion LLMs**

- Wang et al. *Efficient On-Device Diffusion LLM Inference with Mobile NPU* (LLaDA.cpp). arXiv:2606.13740, 2026. [paper](https://arxiv.org/abs/2606.13740)

**Video diffusion inference engines**

- [FastVideo](https://github.com/hao-ai-lab/FastVideo): sparse distillation (VSA + DMD2) for Wan-based models; CUDA, ROCm, and Apple Silicon via MLX.
- [xDiT](https://github.com/xdit-project/xDiT): multi-GPU parallel DiT inference plus step-caching methods. Fang et al. *xDiT: an Inference Engine for Diffusion Transformers (DiTs) with Massive Parallelism.* arXiv:2411.01738, 2024. [paper](https://arxiv.org/abs/2411.01738)
- [LightX2V](https://github.com/ModelTC/LightX2V): few-step distillation, W8A8 / W4A4 quantization, disk-CPU-GPU offloading, step caching; ports to many non-NVIDIA accelerators (Ascend, Cambricon, Hygon, Intel AIPC, and others).

**Diffusion serving systems (datacenter)**

- Yin et al. *vLLM-Omni: Fully Disaggregated Serving for Any-to-Any Multimodal Models.* arXiv:2602.02204, 2026. [paper](https://arxiv.org/abs/2602.02204) · [code](https://github.com/vllm-project/vllm-omni)
- vLLM-Omni Team. *vLLM-Omni Technical Report: A Unified Serving Runtime for Omni-Modality Generation.* arXiv:2610.09307, 2026. [paper](https://arxiv.org/abs/2610.09307)
- SGLang Diffusion. [Accelerating Video and Image Generation](https://lmsys.org/blog/2025-11-07-sglang-diffusion) (2025) · [Advanced Optimizations for Production-Ready Video Generation](https://www.lmsys.org/blog/2026-02-16-sglang-diffusion-advanced-optimizations) (2026) · [code](https://github.com/sgl-project/sglang)

**Acceleration techniques**

- Zhang et al. *SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference Acceleration.* arXiv:2410.02367, 2024. [paper](https://arxiv.org/abs/2410.02367)
- Liu et al. *Timestep Embedding Tells: It's Time to Cache for Video Diffusion Model* (TeaCache). arXiv:2411.19108, 2024. [paper](https://arxiv.org/abs/2411.19108) · [code](https://github.com/ali-vilab/TeaCache)
- First-Block Cache, in [ParaAttention](https://github.com/chengzeyi/ParaAttention).
- Yuan et al. *DiTFastAttn: Attention Compression for Diffusion Transformer Models.* arXiv:2406.08552, 2024. [paper](https://arxiv.org/abs/2406.08552)
- Zhang et al. *VSA: Faster Video Diffusion with Trainable Sparse Attention.* arXiv:2505.13389, 2025. [paper](https://arxiv.org/abs/2505.13389)

**Models**

- Wan Team. *Wan: Open and Advanced Large-Scale Video Generative Models.* arXiv:2503.20314, 2025. [paper](https://arxiv.org/abs/2503.20314)

**Edge runtimes and toolchains**

- [llama.cpp / ggml](https://github.com/ggml-org/llama.cpp), including its Hexagon NPU backend (`ggml/src/ggml-hexagon`)
- [stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp)
- [MLC-LLM](https://github.com/mlc-ai/mlc-llm)
- [ExecuTorch](https://github.com/pytorch/executorch)
- [Qualcomm AI Hub](https://aihub.qualcomm.com/) · [ai-hub-models](https://github.com/qualcomm/ai-hub-models)

**Minimal engines**

- [nano-vllm](https://github.com/GeeeekExplorer/nano-vllm) and [mini-sglang](https://github.com/sgl-project/mini-sglang)
