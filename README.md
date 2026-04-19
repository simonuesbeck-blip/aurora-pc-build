# AURORA – High Performance Workstation Build

> AMD Ryzen 9 7950X3D | RTX 4080 Super | 64GB DDR5  
> Optimized for AI workloads, local LLM deployment and content creation.

---

## System Specifications

### Core Components

| Component | Detail |
|---|---|
| **CPU** | AMD Ryzen 9 7950X3D – 16 cores / 32 threads @ 4.2GHz |
| **Motherboard** | ASRock X670E Steel Legend |
| **RAM** | 64GB DDR5 @ 4800MHz – 2x 32GB (Slots 2 & 4) |
| **GPU** | NVIDIA GeForce RTX 4080 Super – 16GB VRAM |
| **Storage** | 3x 2TB NVMe M.2 SSD (6TB total) |
| **PSU** | Thermaltake 1650W |
| **CPU Cooler** | Alpenföhn AIO – 360mm radiator |
| **Case Fans** | 5x 120mm Be Quiet! Silent Wings – intake/exhaust configuration |
| **Case** | Custom / No-name |
| **OS** | Windows 11 Pro 64-bit |

### Display

| Property | Detail |
|---|---|
| Monitor | Samsung Odyssey G93SD |
| Resolution | 5120 x 1440 (Super Ultrawide) |
| Refresh Rate | 240Hz |
| HDR | Supported |
| Connection | DisplayPort |

---

## Build Philosophy

This system was not built for benchmarks – it was built for sustained 
real-world performance across demanding workloads. Component selection 
prioritized the balance between raw performance, reliability and longevity.

Key decisions:

- **Ryzen 9 7950X3D** – The 3D V-Cache architecture delivers exceptional 
  performance in both heavily threaded workloads and latency-sensitive tasks. 
  16 cores provide headroom for running local AI models alongside other 
  applications simultaneously.

- **RTX 4080 Super** – 16GB VRAM is the practical minimum for running large 
  local language models (70B parameter models at reduced precision). 
  Chosen over the 4090 for price-to-performance ratio at this VRAM tier.

- **64GB DDR5** – Allows large models to be partially offloaded to system RAM 
  without bottlenecking performance. Expandable to 128GB by adding a matching 
  2x32GB kit in Slots 1 & 3.

- **3x 2TB NVMe** – Dedicated storage for OS, AI models and project data 
  without compromise. AI model files alone can exceed 40GB per model.

- **1650W PSU** – Headroom for full GPU + CPU load during AI inference, 
  future upgrades and stable long-duration operation.

---

## Primary Use Cases

- **Local AI / LLM inference** – Running large language models via Ollama 
  without cloud dependency (Hermes3 70B, Gemma, Mistral)
- **AI image generation** – Stable Diffusion, ComfyUI, LoRA training via 
  kohya_ss
- **Content creation** – Video editing, rendering
- **Gaming** – High-refresh ultrawide gaming at 5120x1440

---

## Upgrade Path

| Upgrade | Detail |
|---|---|
| RAM | Add 2x 32GB DDR5 in Slots 1 & 3 → 128GB total |
| Storage | Additional M.2 slots available on X670E |
| GPU | PCIe 5.0 slot ready for next-gen GPU |

---

## Software Environment

| Software | Purpose |
|---|---|
| Windows 11 Pro | Primary OS |
| Ollama | Local LLM runtime |
| Open WebUI | Local AI chat interface |
| ComfyUI | AI image generation |
| kohya_ss | LoRA training |

---

## Status
> ✅ **Active daily driver** – fully operational
