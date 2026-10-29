# Third-party notices

ZYN-DICT bundles local speech and language models plus runtime libraries.
Those components keep their original licenses.

> Qwen is licensed under the Qwen RESEARCH LICENSE AGREEMENT, Copyright (c) Alibaba Cloud. All Rights Reserved.

## Models

| Component | Role | License |
|---|---|---|
| [Whisper large-v3-turbo](https://github.com/openai/whisper) (CTranslate2: [faster-whisper-large-v3-turbo](https://huggingface.co/mobiuslabsgmbh/faster-whisper-large-v3-turbo)) | Speech recognition | MIT — `licenses/Whisper-LICENSE.txt` |
| [Qwen2.5-3B-Instruct](https://huggingface.co/Qwen/Qwen2.5-3B-Instruct-GGUF) Q4_K_M | Grammar / punctuation polish | **Qwen Research License** (non-commercial research / evaluation unless you obtain a commercial grant) — `licenses/Qwen-Research-LICENSE.txt` |

## Runtime

| Component | Role | License |
|---|---|---|
| [llama.cpp](https://github.com/ggml-org/llama.cpp) (Vulkan) | Local LLM inference | MIT — `licenses/llama.cpp-LICENSE.txt` |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) / [CTranslate2](https://github.com/OpenNMT/CTranslate2) | Speech inference | MIT |
| [PySide6 / Qt](https://doc.qt.io/qtforpython-6/licenses.html) | Desktop UI | LGPL / GPL / Qt commercial (libraries remain replaceable) |
| NVIDIA CUDA / cuBLAS / cuDNN | Optional GPU acceleration | NVIDIA redistributable terms (not an NVIDIA driver installer) |
| PyInstaller | Packaging | GPL with bootloader exception |

The application itself is not MIT or Apache licensed. See `LICENSE`.
