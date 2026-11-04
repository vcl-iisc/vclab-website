---
title: "MTech Projects"
layout: default
excerpt: "VCLab, CDS, IISc"
sitemap: false
permalink: /mtech_projects_26/
---

### Please fill in the form [here](https://docs.google.com/forms/d/e/1FAIpQLSf4DDd8DcH01tJhQGfGy4P8tFDrFMSYkaRxyIv6yqdw0uYHTg/viewform?usp=dialog) by uploading your detailed CV and a statement of purpose. This form will be open until 15th November.

<br>

#### ✨ Project Title-1: "Physics-Grounded and Geometry-Preserving Video Generation"
Details: Developing a physics-grounded video generation framework that lifts 2D scenes into 3D representations to model realistic object and agent interactions. The framework enforces physical constraints to ensure plausible dynamics, preserves object geometry, and maintains object and agent fidelity across generated frames.

📖 Suggested reading:<br>
Perpetual Wonder: [https://arxiv.org/abs/2602.04876](https://arxiv.org/abs/2602.04876)<br>
Code Video Model: [https://code-video-model.github.io/tech_report.pdf](https://code-video-model.github.io/tech_report.pdf)<br>
PHYSLDM: [https://arxiv.org/pdf/2610.07609](https://arxiv.org/pdf/2610.07609)<br>

Video Demonstrations from `Code Video Model` and `Perpetual Wonder` works.

<div align="center">
  <video width="100%" controls autoplay muted loop>
    <source src="https://code-video-model.github.io/static/demo/Demo_CodeVideoModel_New.mp4" type="video/mp4">
  </video>
</div>


<table>
  <tr>
    <td width="50%">
      <video width="100%" controls autoplay muted loop>
        <source src="https://johnzhan2023.github.io/PerpetualWonder/assets/quality_result/flower.mp4" type="video/mp4">
      </video>
    </td>
    <td width="50%">
      <video width="100%" controls autoplay muted loop>
        <source src="https://johnzhan2023.github.io/PerpetualWonder/assets/quality_result/tea_pot.mp4" type="video/mp4">
      </video>
    </td>
  </tr>
</table>



🔗 Contact person for more details: Kunsh Taneja (Mail: <a href="mailto:kunshtaneja@iisc.ac.in">kunshtaneja@iisc.ac.in</a>) and Shyam Marjit (Mail: <a href="mailto:shyammarjit@iisc.ac.in">shyammarjit@iisc.ac.in</a>)

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

**What are we looking for in applicants:** The ideal candidates should be conversant in fundamental mathematical topics such as probability and statistics, linear algebra, multivariable calculus, convex optimization etc. They must be proficient in Python, NumPy/SciPy, Scikit-learn and should possess at least beginner's knowledge in PyTorch or TensorFlow. Prior hands-on experience with machine learning and/or computer vision projects will be highly desirable.
