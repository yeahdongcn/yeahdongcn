# Hi, I'm Xiaodong Ye (R0CKSTAR) 👋

I build AI inference systems at [Moore Threads](https://www.mthreads.com/),
from GPU kernels and hardware backends to model serving on MUSA GPUs.

## Open-source inference

- [vLLM-MUSA](https://github.com/MooreThreads/vllm-musa) — I maintain the MUSA serving stack. Recent work includes [Mamba2 kernels via MATE](https://github.com/MooreThreads/vllm-musa/pull/312) and the [serving cookbook](https://moorethreads.github.io/vllm-musa/). I'm also working on [MATE Mega MoE and graph-safe expert parallelism over MCCL](https://github.com/MooreThreads/vllm-musa/pull/325) (draft).
- [vLLM-Omni](https://github.com/vllm-project/vllm-omni) — I helped bring [MAGI-2 Preview audio-video generation to MUSA](https://github.com/vllm-project/vllm-omni/pull/8498) ([vLLM blog](https://vllm.ai/blog/2026-10-12-magi2-preview-musa)) and upstreamed [Qwen-Image-2.1 performance improvements](https://github.com/vllm-project/vllm-omni/pull/9845).
- [SGLang](https://github.com/sgl-project/sglang) — I'm a [code owner for the MLX and MUSA backends](https://github.com/sgl-project/sglang/blob/main/.github/CODEOWNERS). I reviewed [Unlimited-OCR v2 on PyTorch MPS](https://github.com/sgl-project/sglang/pull/47921) and restored the [MUSA AOT kernel wheel build](https://github.com/sgl-project/sglang/pull/50486).
- [torchada](https://github.com/MooreThreads/torchada) — I work on CUDA compatibility for PyTorch projects on MUSA, including [shared MUSA architecture definitions and build targets](https://github.com/MooreThreads/torchada/pull/146) and [C++ extension portability](https://github.com/MooreThreads/torchada/pull/153).

I also contribute MUSA support to [llama.cpp](https://github.com/ggml-org/llama.cpp/pull/30080) and [Mooncake](https://github.com/kvcache-ai/Mooncake/pull/5359), and review changes in [SGLang-Omni](https://github.com/sgl-project/sglang-omni).

## Side projects

- [apple-smi](https://github.com/yeahdongcn/apple-smi) — GPU monitoring for Apple Silicon from the terminal, no `sudo` required.
- [gotemplate](https://github.com/yeahdongcn/gotemplate) — Go's `text/template` in MoonBit, tested against the Go implementation.
- [Nautilus Studio](https://github.com/yeahdongcn/nautilus-studio) — a storyboard-driven studio for long-form AI video.
- [NIGHT CITY — Pixel Edition](https://yeahdongcn.github.io/pixel/) — a browser RPG with art and audio generated in code.

Previously, I worked on cloud-native infrastructure and virtualization at [VMware](https://www.vmware.com/) and [Sangfor](https://www.sangfor.com/).

[Email](mailto:yeahdongcn@gmail.com) · [LinkedIn](https://www.linkedin.com/in/yeahdongcn/)
