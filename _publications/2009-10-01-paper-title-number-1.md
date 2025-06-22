---
title: "Alignment Quality Index (AQI): Beyond Refusals: AQI as an Intrinsic Alignment Diagnostic via Latent Geometry, Cluster Divergence, and Layer wise Pooled Representations"
collection: publications
permalink: /publication/AQI
excerpt: "Alignment is no longer a luxury, it is a necessity. As large language models (LLMs) enter high-stakes domains like education, healthcare, governance, and law, their behavior must reliably reflect human-aligned values and safety constraints. Yet current evaluations rely heavily on behavioral proxies such as refusal rates, G-Eval scores, and toxicity classifiers, all of which have critical blind spots. Aligned models are often vulnerable to jailbreaking, stochasticity of generation, and alignment faking. To address this issue, we introduce the Alignment Quality Index (AQI). This novel geometric and prompt-invariant metric empirically assesses LLM alignment by analyzing the separation of safe and unsafe activations in latent space. By combining measures such as the Davies-Bouldin Score (DBS), Dunn Index (DI), Xie-Beni Index (XBI), and Calinski-Harabasz Index (CHI) across various formulations, AQI captures clustering quality to detect hidden misalignments and jailbreak risks, even when outputs appear compliant. AQI also serves as an early warning signal for alignment faking, offering a robust, decoding invariant tool for behavior agnostic safety auditing. Additionally, we propose the LITMUS dataset to facilitate robust evaluation under these challenging conditions. Empirical tests on LITMUS across different models trained under DPO, GRPO, and RLHF conditions demonstrate AQI's correlation with external judges and ability to reveal vulnerabilities missed by refusal metrics. We make our implementation publicly available to foster future research in this area.
Find the pre-print [here](https://arxiv.org/pdf/2506.13901)"
date: 2025-05-16
venue: 'arXiv preprint arXiv:2506.13901'
paperurl: '[https://arxiv.org/abs/2506.13901](https://arxiv.org/abs/2506.13901)'
citation: 'arXiv:2506.13901'
---


