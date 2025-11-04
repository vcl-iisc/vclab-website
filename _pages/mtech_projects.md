---
title: "MTech Projects"
layout: default
excerpt: "VCLab, CDS, IISc"
sitemap: false
permalink: /mtech_projects/
---

### Please fill in the form [here](https://forms.gle/jCFfV8u8tSPtGGd36) by uploading your detailed CV and a statement of purpose.

<br>

#### ✨ Project Title-1: "FrameEdit: In-Context Temporal Frame Generation via LLM–Diffusion Fusion"
Details: Extending the capabilities of [GenHowTo](https://arxiv.org/abs/2312.07322) and [ShowHowTo](https://arxiv.org/abs/2412.01987), we aim to generate the n’th frame from given initial frames while ensuring temporal and structural consistency aligned with given new action prompts. We frame this as an in-context editing problem, leveraging fused Autoregressive LLMs and Generative Diffusion Transformers inspired by [Jenus-Pro](https://arxiv.org/abs/2501.17811), [OmniGen](https://arxiv.org/abs/2409.11340), and [OmniGen-v2](https://arxiv.org/abs/2506.18871), with significant potential for applications such as robotics, AR, VR, etc.

🔗 Contact person for more details: Shyam Marjit (Mail: <a href="mailto:shyam.marjit@iisc.ac.in">shyammarjit@iisc.ac.in</a>)

<br>

#### ✨ Project Title-2: "AudioLLM: On-the-fly interactive audio unmixing and editing"
Details: Inspired by [SegLLM](https://berkeley-hipie.github.io/segllm.github.io/), this project aims to design an interactive video-to-audio editing chatbot system that processes videos (real-world and synthetic) containing audio. The goal is to decompose the input audio into multiple object-centric audio tracks (refer to this [paper](https://arxiv.org/abs/2506.20995)) and associate each track with its corresponding visual object in the video. The chatbot further enables fine-grained editing of these object-centric audio components, allowing users to modify them individually or collectively according to their preferences.


🔗 Contact person for more details: Shyam Marjit (Mail: <a href="mailto:shyam.marjit@iisc.ac.in">shyammarjit@iisc.ac.in</a>)


<br>

#### ✨ Project Title-3: "Gradient Inversion Attacks in Parameter-Efficient Prompt Tuning of Vision Transformers"
Details: In Federated Learning (FL), the clients share their model gradients with the server. The server aggregates the model gradients and performs the model update, and broadcasts the new updated model to clients in the subsequent rounds. It has been shown in traditional training that when the gradients of the parameters are shared, the data can be reconstructed. This has been shown in the context of LoRa training very recently. This reconstruction problem is open in the context of prompt tuning of Vision transformers (ViT).
Outcome: Gradient inversion attack in ViT prompt tuning.

🔗 Contact person for more details: M. Yashwanth (Mail: <a href="mailto:yashwanthm@iisc.ac.in">yashwanthm@iisc.ac.in</a>)

<br>

#### ✨ Project Title-4: "Federated Aggregation via EPO Search for Multi-objective learning"
Details: In multi-objective optimization, the solution can converge to different points on the Pareto front depending upon the preferences given to various objectives. This idea has been extended to federated learning, where each client carries out multi-objective optimization (MOO) over a shared set of tasks via EPO (Exact Pareto Optimal) search. However, the clients may not share the set of tasks. Therefore, it is more reasonable to view each client as a separate lone objective and let the server conduct an EPO search over its model parameters to satisfy each client’s preferences (some modeled utility). However, the present EPO search methods show slow convergence against traditional FL methods due to gradient ascent and descent steps, and a fast-converging EPO search algorithm is an open problem.

🔗 Contact person for more details: M. Yashwanth (Mail: <a href="mailto:yashwanthm@iisc.ac.in">yashwanthm@iisc.ac.in</a>)

<br>

#### ✨ Project Title-5: "Towards Robust MultiModal Large Language Modelling"
Details: Develop a Multimodal LLM robust and generalisable towards any visual modality, not just natural images. Current MLLMs fail to generalize to modalities like sketches, segmentation maps, edge maps, etc. 1) Exploration and analysis: how good are current MLLMs? 2) Developing training regimes which force models to prefer shape:  3) Benchmarking: have we reduced texture bias? Does that allow us to transfer to unseen modalities? How well do we do on unseen classes?

Expected Outcome: A practical recipe which gives us more robust MLLMs, which not only allows us to use MLLMs on relatively special modalities like thermal images, depth maps etc, but also improves open-set performance (on unseen classes) since we now have shape-to-shape correspondence.

🔗 Contact person for more details: Rishi Gupta (Mail: <a href="mailto:rishig@iisc.ac.in">rishig@iisc.ac.in</a>)


<br>

#### ✨ Project Title-6: "Scene‑Scale and Memory‑Bounded Feed‑Forward 3DGS"
Details: Predict large‑scene Gaussians under (i) tight memory by sparse tokens, token merging, and (ii) on‑the‑fly pruning/compression while preserving quality. We may also explore distillation techniques to reduce the size of the model while preserving quality.

Expected learning outcomes: Hands-on Knowledge of transformers, knowledge distillation, and Gaussian Splatting

Reference papers: [GS‑LRM (transformer LRM)](https://arxiv.org/abs/2404.19702), [GeoLRM (geometry‑aware LRM)](https://neurips.cc/virtual/2024/poster/94280), [Long‑LRM](https://arxiv.org/html/2410.12781v2), and [FreeSplat (redundancy reduction)](https://arxiv.org/pdf/2405.17958).

🔗 Contact person for more details: Sai Dharma (Mail: <a href="mailto:dharmasai@iisc.ac.in">dharmasai@iisc.ac.in</a>)

<br>

#### ✨ Project Title-7: "Blur Robust Feed‑Forward GS"
Details: Learn camera‑aware features and exposure‑time models so a feed‑forward network can reconstruct sharp Gaussians from defocus/motion‑blurred and rolling‑shutter video without per‑scene optimization.

Reference papers: [DOF‑GS (defocus modeling)](https://arxiv.org/abs/2405.17351)
[Gaussian Splatting on the Move](https://arxiv.org/abs/2403.13327)
[BAD‑Gaussians (bundle‑adjusted deblur)](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/03633.pdf)
[BARD‑GS (dynamic blur)](https://openaccess.thecvf.com/content/CVPR2025/papers/Lu_BARD-GS_Blur-Aware_Reconstruction_of_Dynamic_Scenes_via_Gaussian_Splatting_CVPR_2025_paper.pdf)
[MoBGS (motion deblurring for dynamic 3DGS)](https://arxiv.org/abs/2504.15122)
etc.

Expected learning outcomes: Hands-on Knowledge of transformers, blur modelling, and Gaussian Splatting.

🔗 Contact person for more details: Sai Dharma (Mail: <a href="mailto:dharmasai@iisc.ac.in">dharmasai@iisc.ac.in</a>)


<br>
