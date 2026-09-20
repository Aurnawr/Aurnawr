# Hi, I'm Arnav

Second-year undergraduate at **IIT Roorkee** and a core member of the **Data Science Group**. I work on efficient and reliable multimodal generative models — mostly on why vision-language models hallucinate, and whether the fixes we publish for it actually do what we claim.

## What I work on

- **VLM hallucination, mechanistically.** I'm finishing a reproducibility and extension study of contrastive decoding methods (VCD, SID, ICD, OLM, PBA) on POPE and MME. The short version of the finding: contrastive decoding behaves like a distribution shifter rather than a visual-grounding corrector — the Yes-rate shifts are robust, the accuracy gains often aren't.
- **Interpretability tooling.** Activation patching, logit lens, causal tracing, CKA — mostly in service of answering *why* a method works before believing *that* it works.
- **Efficient generation.** Diffusion distillation, and the general question of what you can remove from a model without losing what matters.

I care more about mechanism than leaderboard deltas. A result I can't explain isn't finished.

## Selected work

- **B-DENSE** — ICLR 2026 workshop paper.
- **cd-rethink** — statistical reanalysis of contrastive decoding for VLM hallucination: bootstrap CIs, flip-level TP/FP decomposition, and a code-level audit of published implementations. (Paper in revision.)

## Open source

Recent contributions to the tooling I use in my own research:

- **TransformerLens** — fixed a `stop_at_layer` guard (#1769, merged).
- **lmms-eval** — answer-parsing fixes for the MathVision task.

Currently looking at evaluation-fidelity issues: cases where a benchmark harness reports a score that doesn't match the number in the original paper.

## Toolbox

Python · PyTorch · Qwen2.5-VL · LLaVA · TransformerLens · nnsight · lm-eval-harness · vLLM

## Elsewhere

I'm looking for research internships where the work is model understanding rather than model deployment. If that's the kind of thing your lab does, I'd be glad to hear from you.

- Email: bendrearnav6@gmail.com
- Scholar / site: (https://aurnawr.github.io/)
