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

**Models and kernels**

- Wan Team. *Wan: Open and Advanced Large-Scale Video Generative Models.* arXiv:2503.20314, 2025. [paper](https://arxiv.org/abs/2503.20314)
- Zhang et al. *SageAttention: Accurate 8-Bit Attention for Plug-and-play Inference Acceleration.* arXiv:2410.02367, 2024. [paper](https://arxiv.org/abs/2410.02367)

**Engines**

- [llama.cpp](https://github.com/ggml-org/llama.cpp), including its Hexagon NPU backend (`ggml/src/ggml-hexagon`)
- [nano-vllm](https://github.com/GeeeekExplorer/nano-vllm) and [mini-sglang](https://github.com/sgl-project/mini-sglang), for the minimal-engine style
