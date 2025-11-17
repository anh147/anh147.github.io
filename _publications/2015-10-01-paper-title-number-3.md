---
title: "Expert Merging in Sparse Mixture of Experts with Nash Bargaining"
collection: publications
category: manuscripts
permalink: /publication/2025-10-17-namex
excerpt: 'NAMEx uses Nash bargaining and complex momentum to merge experts more fairly and efficiently, outperforming prior methods across tasks.'
date: 2025-10-17
venue: 'arXiv preprint'
# slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2510.16138'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

Existing expert merging strategies for Sparse Mixture of Experts (SMoE) typically rely on input-dependent or input-independent averaging of expert parameters, but often lack a principled weighting mechanism. In this work, we reinterpret expert merging through the lens of game theory, revealing cooperative and competitive dynamics among experts. Based on this perspective, we introduce Nash Merging of Experts (NAMEx), a novel framework that incorporates Nash Bargaining into the merging process, enabling more balanced and efficient collaboration among experts. Additionally, we incorporate complex momentum into NAMEx to accelerate expert propagation with theoretical guarantees for convergence. Extensive experiments across language modeling, text classification, image classification, and zero-shot robustness under data corruption show that NAMEx consistently outperforms competing methods while integrating seamlessly with popular MoE architectures. Finally, we demonstrate NAMEx’s scalability by applying it to large-scale systems, including Qwen1.5-MoE (14B) and DeepSeek-MoE (16B), where it proves effective in both zero-shot and fine-tuning settings.
