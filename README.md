# FlashAttention Turing — NVIDIA T4 Prebuilt Wheel

Prebuilt FlashAttention-Turing wheel for NVIDIA Tesla T4 / Turing SM75 GPUs.

This project provides a ready-to-install binary wheel so users do not need
to compile FlashAttention-Turing themselves.

## Compatibility

| Component | Version |
|---|---|
| GPU | NVIDIA Tesla T4 |
| CUDA Architecture | SM75 / Compute Capability 7.5 |
| Python | 3.13 |
| PyTorch | 2.11.0+cu128 |
| CUDA | 12.8 |
| OS | Linux x86_64 |

## Wheel

`flash_attn_turing-0.0.0-cp313-torch211-cu128-sm75-t4-linux_x86_64.whl`

## Installation

Install PyTorch first with a compatible CUDA 12.8 build.

Then install the wheel:

```bash
pip install flash_attn_turing-0.0.0-cp313-torch211-cu128-sm75-t4-linux_x86_64.whl --no-deps
