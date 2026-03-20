# ShadowGeneration

**Embedding Physical Reasoning into Diffusion-Based Shadow Generation**  
Shilin Hu, Jingyi Xu, Akshat Dave, Dimitris Samaras, Hieu Le  
arXiv, 2025. [[arXiv](https://arxiv.org/abs/2512.06174)]

This repository currently provides **qualitative results**.  
**Code and training/inference instructions will be released in a future update.**

---

## Overview

We propose a **physics-grounded diffusion-based shadow generation** pipeline that leverages **monocular 3D geometry** to recover a **dominant light direction** and derive a **coarse shadow estimate** via **geometric ray-based reasoning** to anchor shadow placement. By predicting **confidence scores** for both lighting and shadow estimates and using them to adaptively modulate conditioning during generation, our method produces photorealistic shadows with improved localization and geometric consistency.

![Teaser](assets/teaser.png)

---

## Results

### Comparison with SOTA

<figure>
  <img src="assets/qualsota.png" alt="Qualitative Results" width="80%"/>
  <figcaption><em>Visual results in both BOS (with background reference object–shadow pairs) and BOS-free (single object–shadow pair). Our method produces higher image fidelity and more accurate shadow masks that better respect occluder–receiver–illumination relationships.</em> </figcaption>
</figure>

---

## Citation

If you find this work useful, please cite:

```bibtex
@misc{hu2026embeddingphysicalreasoningdiffusionbased,
      title={Embedding Physical Reasoning into Diffusion-Based Shadow Generation}, 
      author={Shilin Hu and Jingyi Xu and Akshat Dave and Dimitris Samaras and Hieu Le},
      year={2026},
      eprint={2512.06174},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2512.06174}, 
}
