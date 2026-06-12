---
license: apache-2.0
title: '👶 SmolKin: Multimodal Infant Care Edge Assistant v1.0'
sdk: gradio
emoji: 📈
colorFrom: green
colorTo: yellow
thumbnail: >-
  https://cdn-uploads.huggingface.co/production/uploads/6989c34475b229ddd8f18be3/HvgOl5hXkB46nxAMvGNCi.png
short_description: 'gineered and deployed an offline-first, low-compute medical '
---
# 👶 SmolKin: Multimodal Infant Care Edge Assistant v1.0

SmolKin is a low-latency, fully offline diagnostic intelligence dashboard engineered for rural and remote clinics lacking stable internet connectivity. Developed for the **Hugging Face Build Small Hackathon**, the system leverages localized Small Language Models (SLMs) and deterministic safety sandboxes to interpret multi-modal infant symptom logs under tight resource constraints.

## 🚀 Key Features
- **0% Internet Required (Fully Offline RAG):** Eliminates dependencies on external APIs, bringing secure, low-compute diagnostics directly to edge devices.
- **Under 10ms Ingestion Latency:** Optimized data indexing pipelines ensure rapid local token processing.
- **Dynamic WHO Protocol Matrix:** Automatically maps infant cough soundwaves, clinical indicators, and raw nurse observer text arrays into specific World Health Organization triage guidelines.
- **Sleek Cyber-Slate UI:** A high-contrast, modern dark-mode interactive console with live CSS soundwave/pixel stream simulation layers.

## 🛠️ Architecture & Core Stack
- **Framework:** Python / Gradio Frontend
- **Local LLM Engine:** Hugging Face `SmolLM2-1.7B` (Inference on Local CPU/RAM)
- **Agent Orchestration:** Hugging Face `smolagents` framework executing secure, isolated data loops.
- **Hardware Optimization:** Specifically adjusted to perform efficiently on standard configurations (e.g., 4th Gen Intel i3 setups with 8GB RAM).

## 🔧 Installation & Local Deployment

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/yourusername/smolkin-multimodal-edge-assistant.git](https://github.com/yourusername/smolkin-multimodal-edge-assistant.git)
   cd smolkin-multimodal-edge-assistant
