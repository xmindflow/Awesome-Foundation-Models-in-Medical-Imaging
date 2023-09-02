[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![Generic badge](https://img.shields.io/badge/Institue-XMindFlow-purple.svg)](https://shields.io/)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

:fire::fire:This is a collection of foundational models in medical imaging:fire::fire:

> [**Foundational Models in Medical Imaging: A Comprehensive Survey and Future Vision**]()<br>
> **Abstract** \
> Foundation models, large-scale, pre-trained deep-learning models adapted to a wide range of downstream tasks have garnered immense interest lately in various deep-learning problems undergoing a paradigm shift with the rise of these models. Trained on large-scale datasets to bridge the gap between different modalities, foundation models facilitate contextual reasoning, generalization, and prompt capabilities at test time. The predictions of these models can be adjusted for new tasks by augmenting the model input with task-specific hints called prompts without requiring extensive labelled data and retraining. Capitalizing on the advances in computer vision, medical imaging has also marked a growing appeal in these models. With the aim of assisting researchers in navigating this flurry, this survey intends to provide a comprehensive overview of foundation models in the discipline of medical imaging. Specifically, we start with an introduction to the basis and fundamental concepts behind foundation models prior to providing a systematic taxonomy of foundation models in the medical domain and propose a multi-perspective categorization based on the type of training, application, imaging modality, organ of interest, and algorithms. Furthermore, we emphasize the practical use case of some selected approaches and then discuss the opportunities, applications and future directions of these large-scale pre-trained models, for analyzing medical images. We discuss the open challenges and research directions for foundational models in medical imaging, including their interpretability, data and computation demands, and contextual understanding issues.

<div align='center'>
<!-- <img src="overview.svg" width="60%" height="60%"> -->
</div>

# <p align=center>`Awesome Medical Imaging Foundational Models`</p>
A curated list of awesome foundational models in medical imaging. \
This repo supplements our survey paper. We intend to continuously update it. \
_**We strongly encourage authors of relevant works to make a pull request and add their paper's information.**_

## Citation

If you find our work useful in your research, please consider citing:
```

```
----
- [Surveys](#surveys)

* [2023.08] [Towards Generalist Foundation Model for Radiology](https://arxiv.org/pdf/2308.02463.pdf) (from SJTU)
* [2023.07] [Towards Generalist Biomedical AI](https://arxiv.org/pdf/2307.14334.pdf) (from Google)
* [2023.04] [Foundation Models for Generalist Medical Artificial Intelligence](https://www.nature.com/articles/s41586-023-05881-4)
* [2022.07] [On the Opportunities and Risks of Foundation Models](https://arxiv.org/pdf/2108.07258.pdf) (Pioneer of *Foundation Models* concept)

- Textually Prompted Models
  - Contrastive
  - Generative
  - Hybrid
  - Conversational
- Visually Prompted Models
  - Adaptations
  - Generalist

# Surveys
## Summary

[MedCLIP]: ## "MedCLIP: Contrastive Learning from Unpaired Medical Images and Text"
[Expert-level detection of...]: ## "Expert-level detection of pathologies from unannotated chest X-ray images via self-supervised learning"
[Learning to Exploit...]: ## "Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing"

> **Abbreviations**:
> - TPM: *Textually Prompted Models* (&#x1F4D7;)
> - VPM: *Visually Prompted Models* (&#x1F4D8;)
> - &#x1F4D9;

 | **ID** |          **Article**           | **Year** | **Netword** |  **Algorithm**   | **Modality** |                            **Links**                             |
 | :----: | :----------------------------: | :------: | :---------: | :--------------: | :----------: | :--------------------------------------------------------------: |
 | **1**  |           [MedCLIP]            | 2022/10  |             | TPM: Contrastive |              |    [ [arXiv](https://arxiv.org/abs/2210.10163) ] [ [Code]() ]    |
 | **2**  | [Expert-level detection of...] |   2022   |             | TPM: Contrastive |              | [ [Nature](https://www.nature.com/articles/s41551-022-00936-9) ] |
 | **3**  |    [Learning to Exploit...]    | 2023/01  |             | TPM: Contrastive |              |          [ [arXiv](https://arxiv.org/abs/2301.04558) ]           |
 | **4**  |                                |          |             |                  |              |                                                                  |
 | **5**  |                                |          |             |                  |              |                                                                  |
 | **6**  |                                |          |             |                  |              |                                                                  |
 | **7**  |                                |          |             |                  |              |                                                                  |


# List of papers

&#x1F4D7; <a id="arti3"></a> **Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing** \
<span style="float: left; font-size:0.85em; color:gray">*Shruthi Bannur, Stephanie Hyland, Qianchu Liu, Fernando Pérez-García, Maximilian Ilse, Daniel C. Castro, Benedikt Boecking, Harshita Sharma, Kenza Bouzid, Anja Thieme, Anton Schwaighofer, Maria Wetscherek, Matthew P. Lungren, Aditya Nori, Javier Alvarez-Valle, Ozan Oktay*</span> \
[ [Paper](https://arxiv.org/pdf/2301.04558.pdf) | [Code]() | [Presentation]() ] <span style="float: right; font-size:0.85em;">$\textcolor{red}{\textsf{arXiv }}|\textcolor{teal}{\textsf{ 9th Jan., 2023}}$</span>
