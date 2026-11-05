# Third-Party Open Source Notices

Dictare builds upon open-source software and open speech models. We gratefully acknowledge the authors and contributors of the following projects.

---

## Handy (`cjpais/Handy`)

Dictare's desktop core is built on [Handy](https://github.com/cjpais/Handy) by CJ Pais and contributors, distributed under the MIT License:

```text
MIT License

Copyright (c) 2025 CJ Pais

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Indic-Transcribe-Flex (`bodhan-ai/indic-transcribe-flex`)

Dictare supports optional on-device download of **Indic-Transcribe-Flex** (`bodhan-ai/indic-transcribe-flex`, quantized GGUF via `TheAnimatrix/indic-transcribe-flex-gguf`), developed by **Bodhan AI** and **AI4Bharat (IIT Madras)**:

- **Model Repository:** [https://huggingface.co/bodhan-ai/indic-transcribe-flex](https://huggingface.co/bodhan-ai/indic-transcribe-flex)
- **GGUF Conversion:** [https://huggingface.co/TheAnimatrix/indic-transcribe-flex-gguf](https://huggingface.co/TheAnimatrix/indic-transcribe-flex-gguf)
- **License:** [Indic Open Model License v1.0](https://huggingface.co/bodhan-ai/indic-transcribe-flex/blob/main/LICENSE)
- **Attribution Notice:** Indic-Transcribe-Flex (1.2B Canary-based FastConformer-Transformer speech model trained on 1.3M hours across 27 Indian languages and Indian-accented English) is created by Bodhan AI and AI4Bharat. Dictare downloads the quantized model weights directly from Hugging Face to the end user's local device for offline, on-device speech recognition.

---

## Speech & Audio Engines

- **`transcribe-cpp` / `ggml` / `whisper.cpp`:** MIT License (with Canary 10-slot Indic prompt extension from [`TheAnimatrix/transcribe.cpp`](https://github.com/TheAnimatrix/transcribe.cpp)).
- **Tauri (`tauri-apps/tauri`):** Apache-2.0 OR MIT License.
- **Silero VAD (`snakers4/silero-vad`):** MIT License.
- **Downloadable Speech Models:** Models downloaded by the user at runtime (such as NVIDIA Parakeet, OpenAI Whisper, Bodhan AI Indic-Transcribe-Flex, Alibaba Qwen3-ASR, UsefulSensors Moonshine) are governed by their respective model licenses as displayed in the Dictare model catalog.
