# routangseng-models

ONNX Q8 model hosting for 肉糖生 WebGPU chat.

Chunked into 50 MB files for GitHub Pages CORS serving.

## HuggingFace

- **ONNX model:** [bobber/routangseng-0.8b-hottake-onnx](https://huggingface.co/bobber/routangseng-0.8b-hottake-onnx)
- **Torch model:** [bobber/routangseng-0.8b-hottake](https://huggingface.co/bobber/routangseng-0.8b-hottake)
- **4B model (recommended):** [bobber/routangseng-phase10-think-sft](https://huggingface.co/bobber/routangseng-phase10-think-sft)
- **WebGPU demo:** [bobber/routangseng-chat](https://huggingface.co/spaces/bobber/routangseng-chat)
- **GPU demo:** [bobber/routangseng-chat-gpu](https://huggingface.co/spaces/bobber/routangseng-chat-gpu)
- **Project docs:** [bobber/routangseng-qwen35-4b-project](https://huggingface.co/bobber/routangseng-qwen35-4b-project)

## CDN URL

```
https://bobbercheng.github.io/routangseng-models/
```

## Files

| Component | Chunks | Size |
|---|---|---|
| `decoder_model_merged_quantized.onnx_data` | 15 × 50 MB | 721 MB |
| `embed_tokens_quantized.onnx_data` | 5 × 50 MB | 243 MB |
| `vision_encoder_quantized.onnx_data` | 2 × 50 MB | 97 MB |
| **Total** | **22 chunks** | **~1.1 GB** |
