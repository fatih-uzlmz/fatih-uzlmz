# Hi, I'm Fatih Uzulmez 👋

I'm a Computer Science & Engineering student at UC Merced and an **open-source contributor** focused on distributed training and on-device ML infrastructure.

## 🚀 Key Meta / PyTorch Contributions

- **[MoE Synchronization Fix](https://github.com/pytorch/torchtitan/pull/2416):** Diagnosed and resolved numerical divergence in Mixture of Experts (MoE) by implementing all-reduce operations at the router boundary.

- **[DDP Rank-Aware Logging](https://github.com/pytorch/torchtitan/pull/2383):** Resolved architectural inconsistencies in Distributed Data Parallel sequences to ensure accurate state reporting.

- **[ExecuTorch SmolLM2 Token Fallback](https://github.com/pytorch/executorch/pull/22633):** Fixed BOS/EOT fallback handling for absent tokenizer IDs while preserving valid token ID `0`; added six-case regression coverage and optional-dependency-safe CI collection.

- **[ExecuTorch HWC Image Inputs](https://github.com/pytorch/executorch/pull/22888):** Added HWC and 1×HWC support to `make_image_input` while preserving CHW behavior; added explicit handling for ambiguous layouts and regression coverage across supported inputs.

## ✨ Key Google / Neuroglancer Contributions 

- **[Safari State Share Clipboard Fix](https://github.com/google/neuroglancer/pull/1107):** Fixed Safari clipboard failures caused by expired user activation during asynchronous state sharing; added a promise-backed clipboard flow, a manual-copy fallback, and regression coverage.

### 🛠️ Technical Focus

- **Languages:** Python, C++, Java, JavaScript
- **Infrastructure:** Distributed Data Parallel (DDP), Multi-GPU Synchronization, LLM Scaling (TorchTitan/TorchTune), On-Device ML (ExecuTorch)
