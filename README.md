[![arXiv](https://img.shields.io/badge/arXiv-2310.18689-b31b1b.svg)](https://arxiv.org/abs/2310.18689)

:fire::fire: This is a collection of foundational models in medical imaging:fire::fire:

> [**Foundational Models in Medical Imaging: A Comprehensive Survey and Future Vision**]()<br>
> **Abstract** \
> Foundation models, large-scale, pre-trained deep-learning models adapted to a wide range of downstream tasks have gained significant interest lately in various deep-learning problems undergoing a paradigm shift with the rise of these models. Trained on large-scale dataset to bridge the gap between different modalities, foundation models facilitate contextual reasoning, generalization, and prompt capabilities at test time. The predictions of these models can be adjusted for new tasks by augmenting the model input with task-specific hints called prompts without requiring extensive labeled data and retraining. Capitalizing on the advances in computer vision, medical imaging has also marked a growing interest in these models. To assist researchers in navigating this direction, this survey intends to provide a comprehensive overview of foundation models in the domain of medical imaging. Specifically, we initiate our exploration by providing an exposition of the fundamental concepts forming the basis of foundation models. Subsequently, we offer a methodical taxonomy of foundation models within the medical domain, proposing a classification system primarily structured around training strategies, while also incorporating additional facets such as application domains, imaging modalities, specific organs of interest, and the algorithms integral to these models. Furthermore, we emphasize the practical use case of some selected approaches and then discuss the opportunities, applications, and future directions of these large-scale pre-trained models, for analyzing medical images. In the same vein, we address the prevailing challenges and research pathways associated with foundational models in medical imaging. These encompass the areas of interpretability, data management, computational requirements, and the nuanced issue of contextual comprehension.

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
@misc{azad2023foundational,
      title={Foundational Models in Medical Imaging: A Comprehensive Survey and Future Vision}, 
      author={Bobby Azad and Reza Azad and Sania Eskandari and Afshin Bozorgpour and Amirhossein Kazerouni and Islem Rekik and Dorit Merhof},
      year={2023},
      eprint={2310.18689},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

----

- [Surveys](#surveys)

  - [2023.04] [Foundation Models for Generalist Medical Artificial Intelligence](https://www.nature.com/articles/s41586-023-05881-4)
  - [2022.07] [On the Opportunities and Risks of Foundation Models](https://arxiv.org/pdf/2108.07258.pdf) (Pioneer of _Foundation Models_ concept)

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
[Towards Expert-Level...]: ## "Towards Expert-Level Medical Question Answering with Large Language Models"
[Clinical-BERT...]: ## "Clinical-BERT: Vision-Language Pre-training for Radiograph Diagnosis and Reports Generation"
[Med-Flamingo]: ## "Med-Flamingo: a Multimodal Medical Few-shot Learner"
[MedBLIP]: ## "MedBLIP: Bootstrapping Language-Image Pre-training from 3D Medical Images and Texts"
[XrayGPT]: ## "XrayGPT: Chest Radiographs Summarization using Medical Vision-Language Models"
[LLaVA-Med]: ## "LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day"
[Visual Med-Alpaca]: ## "Visual Med-Alpaca: A Parameter-Efficient Biomedical LLM with Visual Capabilities"
[PMC-LLaMA]: ## "PMC-LLaMA: Towards Building Open-source Language Models for Medicine"
[ClinicalGPT]: ## "ClinicalGPT: Large Language Models Finetuned with Diverse Medical Data and Comprehensive Evaluation"
[SAM-U]: ## "SAM-U: Multi-box prompts triggered uncertainty estimation for reliable SAM in medical image"
[SAMed]: ## "Customized Segment Anything Model for Medical Image Segmentation"
[AutoSAM]: ## "How to Efficiently Adapt Large Segmentation Model(SAM) to Medical Images"
[MedSAM]: ## "Segment Anything in Medical Images"
[MSA]: ## "Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentatio"
[SAM-Med2D]: ## "SAM-Med2D"
[Med-PaLM M]: ## "Towards Generalist Biomedical AI"

[Foundation models for...]: ## "Foundation models for generalist medical artificial intelligence"
[BiomedGPT]: ## "BiomedGPT: A Unified and Generalist Biomedical Generative Pre trained Transformer for Vision, Language, and Multimodal Tasks"
[Generalist Vision Foundation...]: ## "Generalist Vision Foundation Models for Medical Imaging: A Case Study of Segment Anything Model on Zero-Shot Medical Segmentation"
[RadFM]: ## "Towards Generalist Foundation Model for Radiology"

[moda]="CT, MR, PET, Dermoscopy, Endoscopy, Fundus, Histopathology, Microscopy, US, X-ray"
[moda2]: "text, radiology (CT, MRI, and X-ray), pathology, dermatology, mammography, and genomics"

> **Abbreviations**:
>
> - TPM: _Textually Prompted Models_ (&#x1F4D7;)
> - VPM: _Visually Prompted Models_ (&#x1F4D8;)
> - &#x1F4D9;

| **ID** | **Year** |    **Algorithm**    |          **Short name**           |                                   **Modality**                                   |                                                                                         **Links**                                                                                          |
| :----: | :------: | :-----------------: | :-------------------------------: | :------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|   1    | 2022/10  |  TPM:  Contrastive  |             [MedCLIP]             |                                        XR                                        |                                        [ [paper](https://arxiv.org/pdf/2210.10163.pdf) ]          [ [code](https://github.com/RyanWangZf/MedCLIP) ]                                        |
|   2    | 2022/09  |  TPM:  Contrastive  |  [Expert-level detection of...]   |                                        XR                                        |                                                              [ [paper](https://www.nature.com/articles/s41551-022-00936-9) ]                                                               |
|   3    | 2023/01  |  TPM:  Contrastive  |     [Learning to Exploit...]      |                                        XR                                        |                                                                     [ [paper](https://arxiv.org/pdf/2301.04558.pdf) ]                                                                      |
|   4    | 2023/05  |  TPM:   Generative  |     [Towards Expert-Level...]     |                                                                                  |                                                                     [ [paper](https://arxiv.org/pdf/2305.09617.pdf) ]                                                                      |
|   5    | 2020/06  |  TPM:   Generative  |        [Clinical-BERT...]         |                                        XR                                        |                                                            [ [paper](https://ojs.aaai.org/index.php/AAAI/article/view/20204) ]                                                             |
|   6    | 2023/07  |  TPM:   Generative  |          [Med-Flamingo]           |                                                                                  |                                      [ [paper](https://arxiv.org/abs/2307.15189) ]          [ [code](https://github.com/snap-stanford/med-flamingo) ]                                      |
|   7    | 2023/05  |   TPM:     Hybrid   |             [MedBLIP]             |                                       MRI                                        |                                         [ [paper](https://arxiv.org/pdf/2305.10799.pdf) ]             [ [code](https://github.com/Qybc/MedBLIP) ]                                          |
|   8    | 2023/06  | TPM: Conversational |             [XrayGPT]             |                                        XR                                        |                                        [ [paper](https://arxiv.org/abs/2306.07971) ]             [ [code](https://github.com/mbzuai-oryx/XrayGPT) ]                                        |
|   9    | 2023/06  | TPM: Conversational |            [LLaVA-Med]            |                          XR, MRI, Histology, Gross, CT                           |                                        [ [paper](https://arxiv.org/abs/2306.00890) ]             [ [code](https://github.com/microsoft/LLaVA-Med) ]                                        |
|   10   |    20    | TPM: Conversational |        [Visual Med-Alpaca]        |                                                                                  | [ [paper](https://github.com/cambridgeltl/visual-med-alpaca) ] [ [code](https://github.com/cambridgeltl/visual-med-alpaca) ] [ [page](https://cambridgeltl.github.io/visual-med-alpaca/) ] |
|   11   | 2023/04  | TPM: Conversational |            [PMC-LLaMA]            |                                       Text                                       |                                              [ [paper](https://arxiv.org/abs/2304.14454) ] [ [code](https://github.com/chaoyi-wu/PMC-LLaMA) ]                                              |
|   12   | 2023/06  | TPM: Conversational |           [ClinicalGPT]           |                                       Text                                       |                                                                       [ [paper](https://arxiv.org/abs/2306.09968) ]                                                                        |
|   13   | 2023/07  |        VPM:         |              [SAM-U]              |                                      Fundus                                      |                                                                     [ [paper](https://arxiv.org/pdf/2307.04973.pdf) ]                                                                      |
|   14   | 2023/04  |        VPM:         |              [SAMed]              |                                        CT                                        |                                         [ [paper](https://arxiv.org/pdf/2304.13785.pdf) ]           [ [code](https://github.com/hitachinskSAMed) ]                                         |
|   15   | 2023/06  |        VPM:         |             [AutoSAM]             |                                  RGB -> MRI 2D                                   |                                         [ [paper](https://arxiv.org/pdf/2306.13731.pdf) ]            [ [code](https://github.com/xhu248/AutoSAM) ]                                         |
|   16   | 2023/04  |        VPM:         |             [MedSAM]              |                            CT, MRI, OCT, Dermoscopic                             |                                        [ [paper](https://arxiv.org/abs/2304.12306) ]              [ [code](https://github.com/bowang-lab/MedSAM) ]                                         |
|   17   | 2023/04  |        VPM:         |               [MSA]               |                         CT, MRI, US, Fundus, Dermoscopic                         |                                      [ [paper](https://arxiv.org/pdf/2304.12620.pdf) ]     [ [code](https://github.com/WuJunde/Medical-SAM-Adapter) ]                                      |
|   18   | 2023/08  |  VPM:  Adaptations  |            [SAM-Med2D]            | CT, MRI, PET, Dermoscopy, Endoscopy, Fundus, Histopathology, Microscopy, US, XR  |                                       [ [paper](https://arxiv.org/pdf/2308.16184.pdf) ]        [ [code](https://github.com/uni-medical/SAM-Med2D) ]                                        |
|   19   | 2023/07  |  VPM:   Generalist  |           [Med-PaLM M]            | Text, Radiology (CT, MRI, XR), Pathology, Dermatology, Mammography, and Genomics |                                                               [ [paper](https://arxiv.org/abs/2307.14334) ]                -                                                               |
|   20   | 2023/04  |  VPM:   Generalist  |    [Foundation models for...]     |                                       Text                                       |                                                              [ [paper](https://www.nature.com/articles/s41586-023-05881-4) ]                                                               |
|   21   | 2023/05  |  VPM:   Generalist  |            [BiomedGPT]            |                         15 unique biomedical modalities                          |                                         [ [paper](https://arxiv.org/pdf/2305.17100.pdf) ]           [ [code](https://github.com/taokz/BiomedGPT) ]                                         |
|   22   | 2023/04  |  VPM:   Generalist  | [Generalist Vision Foundation...] |                             OCT, MRI, CT, XR, Fundus                             |                   [ [paper](https://arxiv.org/pdf/2304.12637v2.pdf) ]     [ [code](https://github.com/hwei-hw/Generalist_Vision_Foundation_Models_for_Medical_Imaging) ]                   |
|   23   | 2023/08  |  VPM:   Generalist  |              [RadFM]              |                                                                                  |          [ [paper](https://arxiv.org/abs/2308.02463) ]                    [ [code](https://github.com/chaoyi-wu/RadFM) ]          [ [page](https://chaoyi-wu.github.io/RadFM/) ]           |

# List of papers

&#x1F4D7; <a id="arti3"></a> **Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing** \
<span style="float: left; font-size:0.85em; color:gray">_Shruthi Bannur, Stephanie Hyland, Qianchu Liu, Fernando Pérez-García, Maximilian Ilse, Daniel C. Castro, Benedikt Boecking, Harshita Sharma, Kenza Bouzid, Anja Thieme, Anton Schwaighofer, Maria Wetscherek, Matthew P. Lungren, Aditya Nori, Javier Alvarez-Valle, Ozan Oktay_</span> \
[ [ [Paper]https://arxiv.org/pdf/2301.04558.pdf) | [ [Code]() | [Presentation]() ] <span style="float: right; font-size:0.85em;">$\textcolor{red}{\textsf{arXiv }}|\textcolor{teal}{\textsf{ 9th Jan., 2023}}$</span>
