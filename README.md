# BERT Inference Lab

A hands-on lab exploring BERT inference, ONNX model optimization, and model serving with NVIDIA Triton Inference Server.

## Notebooks

1. **BERT Basics** — Model loading and inference with Hugging Face Transformers.
2. **ONNX Export** — Exporting the model to ONNX format.
3. **ONNX Runtime** — Running inference and comparing outputs with the original model.
4. **Triton Inference Server** — Deploying the ONNX model and testing HTTP inference.
5. **Performance Benchmarking** — Comparing inference latency and throughput, including Triton dynamic batching.

## Tech Stack

- Python
- Hugging Face Transformers
- PyTorch
- ONNX & ONNX Runtime
- NVIDIA Triton Inference Server
- Docker
- NumPy & Pandas

## Model

[`textattack/bert-base-uncased-SST-2`](https://huggingface.co/textattack/bert-base-uncased-SST-2) — a BERT model fine-tuned for binary sentiment classification.

## Goals

- Understand the ONNX inference workflow.
- Compare local inference with HTTP-based model serving.
- Explore latency, throughput, and dynamic batching.
- Practice model deployment and performance evaluation.

## Status

A learning project focused on practical AI inference and model serving experiments.