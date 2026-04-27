# BFP4 &mdash; NVFP4 &amp; MXFP4 Block-Float Formats

A bit-level deep dive into the two 4-bit block-floating-point formats that arrived with NVIDIA Blackwell &mdash; the open OCP **MXFP4** spec (32-element blocks, E8M0 shared scale) and NVIDIA's higher-accuracy **NVFP4** (16-element blocks, FP8 micro-scale + FP32 macro-scale). Covers the history of BFP from 1980s DSPs through Microsoft MSFP to the OCP MX standard, the FP4 E2M1 element lattice, the 5th-gen tensor-core MMA path and Transformer Engine v2 integration, throughput across Volta&ndash;Blackwell, and a quality / bandwidth comparison against FP8, BF16, FP6, INT4 and GGUF formats. Includes an interactive BFP4 block decoder so you can drag scales and mantissas and watch the real-number values change.

**Live site:** https://brendanjameslynskey.github.io/NVIDIA_GPU_38_BFP4_Formats/

Part of the [NVIDIA GPU Architectures series](https://github.com/BrendanJamesLynskey/LLM_Hub_NVIDIA_GPUs).
