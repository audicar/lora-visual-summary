# LoRA, from zero — a visual field guide

An interactive, single-file HTML explainer of LoRA (Low-Rank Adaptation): why fine-tuning is expensive, the low-rank insight, the B×A decomposition, an interactive rank slider, target modules, merging vs swappable adapters, and QLoRA.

## Viewing it

GitHub shows HTML files as source, so to see the rendered page:

- **Locally**: download [`lora-from-zero.html`](lora-from-zero.html) and open it in a browser — it is fully self-contained (no build step, no dependencies beyond Google Fonts).
- **In the browser without cloning**: open the file in the repo, press the **Raw** button, and save the page — or use a raw-content renderer if the repo is ever made public.

## Sources

Hu et al., *LoRA: Low-Rank Adaptation of Large Language Models* (2021) · Dettmers et al., *QLoRA: Efficient Finetuning of Quantized LLMs* (2023) · Hugging Face `peft` documentation.
