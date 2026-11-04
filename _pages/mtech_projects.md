---
title: "MTech Projects"
layout: default
excerpt: "VCLab, CDS, IISc"
sitemap: false
permalink: /mtech_projects_26/
---

### Please fill in the form [here](https://docs.google.com/forms/d/e/1FAIpQLSf4DDd8DcH01tJhQGfGy4P8tFDrFMSYkaRxyIv6yqdw0uYHTg/viewform?usp=dialog) by uploading your detailed CV and a statement of purpose. This form will be open until 15th November.

<br>

#### ✨ Project Title-1: `Physics-Grounded and Geometry-Preserving Video Generation`
🔎 Details: Developing a physics-grounded video generation framework that lifts 2D scenes into 3D representations to model realistic object and agent interactions. The framework enforces physical constraints to ensure plausible dynamics, preserves object geometry, and maintains object and agent fidelity across generated frames.

📖 Suggested reading:<br>
Perpetual Wonder: [https://arxiv.org/abs/2602.04876](https://arxiv.org/abs/2602.04876)<br>
Code Video Model: [https://code-video-model.github.io/tech_report.pdf](https://code-video-model.github.io/tech_report.pdf)<br>
PHYSLDM: [https://arxiv.org/pdf/2610.07609](https://arxiv.org/pdf/2610.07609)<br>

Video Demonstrations from 'Code Video Model' and 'Perpetual Wonder' works.

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

#### ✨ Project Title-2: `Mixture-of-Experts Architectures for Universal Multimodal Embedding Models`
🔎 Details: Universal embedding models today are mostly dense VLMs fine-tuned with contrastive loss. They trade capacity across modalities and tasks, and gains on one task (e.g. visual document retrieval) often cost another (e.g. text-only retrieval). MoE offers a way to add capacity where modalities and tasks conflict without raising per-query inference cost.

📖 Suggested reading:<br>
MoEMB: [https://arxiv.org/pdf/2609.08663](https://arxiv.org/pdf/2609.08663)<br>
MoE: [https://arxiv.org/abs/2503.07137](https://arxiv.org/abs/2503.07137)<br>


🔗 Contact person for more details: Anish Chaudhary (Mail: <a href="mailto:anishc@iisc.ac.in">anishc@iisc.ac.in</a>)


<br>

#### ✨ Project Title-3: `Agentic Model Surgery for VLMs`
🔎 Details: Agentic model surgery treats a vision-language model's (VLM) weights and training code as programs that a frontier agent can read, write and verify, using only a budget of forward passes and probe images it generates itself. Where prior work tunes a training run (Reactive Optimizers) or removes a failure mode from a language model (Weight-Space Programming), this area asks the agent to add missing visual skills, move skills between models, repair models during deployment, forget targeted concepts, and audit models from their weights alone. Its central claim, and the hook for a CVPR paper, is that for vision an agent can write new, human-readable capability into a VLM without gradient training.

📖 Suggested reading:<br>
Sparks of Weight-Space Programming: [https://rikiyat.github.io/blog/weight-space-programming/](https://rikiyat.github.io/blog/weight-space-programming/)<br>
Reactive Optimizers: [https://arxiv.org/pdf/2609.08663](https://arxiv.org/pdf/2609.08663)<br>

🔗 Contact person for more details: Shyam Marjit (Mail: <a href="mailto:shyammarjit@iisc.ac.in">shyammarjit@iisc.ac.in</a>)

<br>

#### ✨ Project Title-4: `Gradient Inversion Attacks on Vision-Language Models under Federated Parameter Efficient Fine-Tuning Framework`

🔎 Details: Early gradient inversion attacks on Vision-Language Models (VLMs) focused primarily on simple classification tasks using fixed category templates. Modern frameworks like MMGIA expand to complex tasks such as image captioning and medical report generation, but they rely on alternating two-stage optimization loops that require hundreds to thousands of backpropagation iterations, creating a severe computational time bottleneck. Crucially, existing methods assume full-parameter fine-tuning, leaving gradient inversion under Parameter-Efficient Fine-Tuning (PEFT), such as LoRA, which dominates resource-constrained FL, entirely unexplored. We intend to investigate a compelling research direction: To what extent are multimodal Vision-Language Models (VLMs) vulnerable to gradient inversion attacks when fine-tuned using Parameter-Efficient Fine-Tuning (PEFT) on single or dual modalities in Federated Learning?

📖 Suggested reading:<br>
MMGIA: [https://ijcai.org/proceedings/2025/886](https://ijcai.org/proceedings/2025/886)<br>
DAGER: [https://arxiv.org/pdf/2405.15586](https://arxiv.org/pdf/2405.15586)<br>
GIAS: [https://arxiv.org/pdf/2110.14962](https://arxiv.org/pdf/2110.14962)<br>

🔗 Contact person for more details: Dr. Siladittya Manna (Mail: <a href="mailto:siladittyam@iisc.ac.in">siladittyam@iisc.ac.in</a>) and Ritik Kumar Badiya (Mail: <a href="mailto:ritikbadiya@iisc.ac.in">ritikbadiya@iisc.ac.in</a>)

<br>

#### ✨ Project Title-5: `Federated Learning with Noisy Labels`

🔎 Details: Despite advances in federated learning with noisy labels, existing approaches often address label-noise estimation, sample correction, and client-aware aggregation without fully accounting for their interplay with severe non-IID data distributions. In particular, distinguishing client-specific annotation corruption from legitimate distributional heterogeneity remains challenging, potentially leading to erroneous label correction or the suppression of informative clients. This research will address this gap by jointly estimating label reliability and client heterogeneity and incorporating these estimates into noise-aware local optimization and global aggregation, without requiring clean server-side data or sharing raw data.

📖 Suggested reading:<br>
Federated learning with noisy labels Survey: [https://www.sciencedirect.com/science/article/pii/S0893608026003503](https://www.sciencedirect.com/science/article/pii/S0893608026003503)<br>

🔗 Contact person for more details: Dr. Siladittya Manna (Mail: <a href="mailto:siladittyam@iisc.ac.in">siladittyam@iisc.ac.in</a>)


<br>

#### ✨ Project Title-6: `Foley-Evaluation Metric`

🔎 Details: For video-to-audio generation, causality between visual events and their corresponding sounds should be preserved. This project aims to develop a metric that evaluates whether the generated sound is causally triggered by the event occurring in the video, rather than merely being associated with or conditioned on the presence of that event.

📖 Suggested reading:<br>
AVBench: [https://arxiv.org/pdf/2605.24652](https://arxiv.org/pdf/2605.24652)<br>
Foley Bench: [https://arxiv.org/pdf/2511.13219](https://arxiv.org/pdf/2511.13219)<br>

🔗 Contact person for more details: Akanksha Sharma (Mail: <a href="mailto:akanksha1@iisc.ac.in">akanksha1@iisc.ac.in</a>) and Ishan Tiwari (Mail: <a href="mailto:ishan.tiwari.it.jsr@gmail.com">ishan.tiwari.it.jsr@gmail.com</a>)

<br>

#### ✨ Project Title-7: `Towards Efficient Text/Image-to-3D Generation and Editing`

🔎 Details: Today’s 3D generators, from diffusion models to code-writing language agents, produce objects and scenes that look plausible but are costly, hard to verify and prone to structural or physical errors. This work aims to generate 3D content that is affordable, physically valid and decomposed into meaningful semantic parts that can be moved or edited easily.


📖 Suggested reading:<br>
ShapeCraft: [https://arxiv.org/pdf/2510.17603](https://arxiv.org/pdf/2510.17603)<br>
Articraft: [https://arxiv.org/pdf/2605.15187](https://arxiv.org/pdf/2605.15187)<br>


🔗 Contact person for more details: Anay Loya (Mail: <a href="mailto:anayloya@iisc.ac.in">anayloya@iisc.ac.in</a>) and Soumya Panja (Mail: <a href="mailto:anayloya@iisc.ac.in">anayloya@iisc.ac.in</a>)


**What are we looking for in applicants:** The ideal candidates should be conversant in fundamental mathematical topics such as probability and statistics, linear algebra, multivariable calculus, convex optimization etc. They must be proficient in Python, NumPy/SciPy, Scikit-learn and should possess at least beginner's knowledge in PyTorch or TensorFlow. Prior hands-on experience with machine learning and/or computer vision projects will be highly desirable.
