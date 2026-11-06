# LiveCam AI Requisite Skills

**Prototype:** browser-local real-time webcam image captioning.

## Requisite skills described by the repository
- Browser webcam access and frame capture.
- Periodic frame sampling.
- Image-captioning model integration.
- ViT encoder and GPT-2 decoder inference.
- ONNX model loading.
- Transformers.js pipeline integration.
- WebGPU acceleration.
- WASM/CPU fallback for shape-related operations.
- Browser model-weight caching.
- TypeScript and Vite application integration.
- Browser/device capability detection.

## Source context
The README describes a frame capture interval of 2.5 seconds and browser-local inference without a server or API call. Model weights are downloaded and cached on first use.

## Evidence boundary
README inspected; implementation files and actual inference performance were not inspected or measured in this pass.

See the [shared requisite-skill atlas](https://github.com/git4emet/systemsNxXD/blob/main/docs/skills/CONVERSATION_RECOVERED_SKILL_ATLAS.md).
