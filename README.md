### RL post-training & ML systems

**Projects**
- **[grpo-profiling-harness](https://github.com/LeoPhilly/grpo-profiling-harness)**: where the time actually goes in a colocated GRPO step (Qwen2.5-1.5B, HF + vLLM, 1×A100). Throughput rose 5.8× from G=4 to G=32 as the bottleneck shifted from generation to training. [Design doc](https://github.com/LeoPhilly/grpo-profiling-harness/blob/main/design_doc.md)
- **[REBEL-style loss for OpenRLHF](https://github.com/OpenRLHF/OpenRLHF/pull/1247)**: a reward-gap regression loss in OpenRLHF's DPO trainer, benchmarked against DPO and IPO on UltraFeedback (PR #1247, under review). [Design doc](https://github.com/LeoPhilly/supplement-rebel-loss/blob/main/design_doc.md)

**Interested in**
- RL beyond text-only rewards: tool use, multi-step tasks, and making rewards and evals less noisy
- Robot learning: vision-language-action models (VLAs), world-action models, and efficient online RL on top of VLAs (e.g., RL tokens / RLT)
