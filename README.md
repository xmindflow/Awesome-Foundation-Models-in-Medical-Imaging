# <p align=center>:fire:`Awesome Foundational Models in Medical Imaging `:fire:</p>
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)

🔥🔥 This is a collection of awesome articles about foundation models in medical imaging🔥🔥

Our survey paper on arXiv: [Foundational Models in Medical Imaging: A Comprehensive Survey and Future Vision](https://arxiv.org/abs/2310.18689) ❤️

## Citation
If you find our work useful in your research, please consider citing:

```bibtex
@article{azad2023foundational,
  title={Foundational Models in Medical Imaging: A Comprehensive Survey and Future Vision},
  author={Azad, Bobby and Azad, Reza and Eskandari, Sania and Bozorgpour, Afshin and Kazerouni, Amirhossein and Rekik, Islem and Merhof, Dorit},
  journal={arXiv preprint arXiv:2310.18689},
  year={2023}
}
```


## Overview

Foundation models, large-scale pre-trained deep learning models adaptable to various tasks, have gained interest across deep learning applications. In the medical imaging field, they enable contextual reasoning, generalization, and prompt-based task adjustments. This survey provides an overview of foundation models in medical imaging, covering fundamental concepts, taxonomy based on training strategies, application domains, imaging modalities, and more. It highlights practical use cases, applications, future directions, and challenges, including interpretability, data management, computational needs, and contextual comprehension.

<p align="center">
  <img src="https://github.com/xmindflow/Awesome-Foundation-Models-in-Medical-Imaging/assets/61879630/7a5fa0c3-b92a-4951-92cc-746e6766aa00" alt="Image Description">
</p>


We strongly encourage authors of relevant works to make a pull request and add their paper's information.
____


# Menu

## Contents
- [Survey Papers](#survey-papers)

- [Papers](#papers)
  - [Textual Prompted Models](#textual-prompted-models)
    - [Contrastive](#contrastive)
    - [Conversational](#conversational)
    - [Generative](#generative)
    - [Hybrid](#hybrid)
  - [Visual Prompted Models](#visual-prompted-models)
    - [Adaptations](#adaptations)
    - [Generalist](#generalist)

    
## Survey Papers

## Papers

### Textual Prompted Models
#### Contrastive

**Enhancing Representation in Radiography-Reports Foundation Model: A Granular Alignment Algorithm Using Masked Contrastive Learning**<br>
*Weijian Huang, Cheng Li, Hao Yang, Jiarun Liu, Shanshan Wang*<br>
[12th Sep., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2309.05904.pdf)]<br>


**A visual-language foundation model for pathology image analysis using medical Twitter**<br>
*Zhi Huang, Federico Bianchi, Mert Yuksekgonul, Thomas J. Montine, James Zou*<br>
[17th Aug., 2023] [Nature Medicine, 2023]<br>
[[Paper](https://www.nature.com/articles/s41591-023-02504-3)] [[GitHub](https://tinyurl.com/webplip)]<br>


**ELIXR: Towards a general purpose X-ray artificial intelligence system through alignment of large language models and radiology vision encoders**<br>
*Shawn Xu, Lin Yang, Christopher Kelly, Marcin Sieniek, Timo Kohlberger, Martin Ma, Wei-Hung Weng, Atilla Kiraly, Sahar Kazemzadeh, Zakkai Melamed, Jungyeon Park, Patricia Strachan, Yun Liu, Chuck Lau, Preeti Singh, Christina Chen, Mozziyar Etemadi, Sreenivasa Raju Kalidindi, Yossi Matias, Katherine Chou, Greg S. Corrado, Shravya Shetty, Daniel Tse, Shruthi Prabhakara, Daniel Golden, Rory Pilgrim, Krish Eswaran, Andrew Sellergren*<br>
[2nd Aug., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2308.01317)]<br>


**Knowledge Boosting: Rethinking Medical Contrastive Vision-Language Pre-Training**<br>
*Xiaofei Chen, Yuting He, Cheng Xue, Rongjun Ge, Shuo Li, Guanyu Yang*<br>
[14th Jul., 2023] [MICCAI, 2023]<br>
[[Paper](https://arxiv.org/pdf/2307.07246.pdf)] [[GitHub](https://github.com/ChenXiaoFei-CS/KoBo)]<br>


**Text-guided Foundation Model Adaptation for Pathological Image Classification**<br>
*Yunkun Zhang, Jin Gao, Mu Zhou, Xiaosong Wang, Yu Qiao, Shaoting Zhang, Dequan Wang*<br>
[27th Jul., 2023] [MICCAI, 2023]<br>
[[Paper](https://arxiv.org/abs/2307.14901)] [[GitHub](https://github.com/Yunkun-Zhang/CITE)]<br>


**Visual Language Pretrained Multiple Instance Zero-Shot Transfer for Histopathology Images**<br>
*Ming Y. Lu, Bowen Chen, Andrew Zhang, Drew F.K. Williamson, Richard J. Chen, Tong Ding, Long Phi Le, Yung-Sung Chuang, Faisal Mahmood*<br>
[13th Jun., 2023] [CVPR, 2023]<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Lu_Visual_Language_Pretrained_Multiple_Instance_Zero-Shot_Transfer_for_Histopathology_Images_CVPR_2023_paper.pdf)]<br>


**Large-Scale Domain-Specific Pretraining for Biomedical Vision-Language Processing**<br>
*Sheng Zhang, Yanbo Xu, Naoto Usuyama, Jaspreet Bagga, Robert Tinn, Sam Preston, Rajesh Rao, Mu Wei, Naveen Valluri, Cliff Wong, Matthew P. Lungren, Tristan Naumann, Hoifung Poon*<br>
[2nd Mar., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2303.00915)] [[GitHub](https://aka.ms/biomedclip)]<br>


**Towards Unifying Medical Vision-and-Language Pre-training via Soft Prompts**<br>
*Zhihong Chen, Shizhe Diao, Benyou Wang, Guanbin Li, Xiang Wan*<br>
[17th Feb., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2302.08958.pdf)] [[GitHub](https://github.com/zhjohnchan/PTUnifier)]<br>


**Learning to Exploit Temporal Structure for Biomedical Vision Language Processing**<br>
*Shruthi Bannur, Stephanie Hyland, Qianchu Liu, Fernando Pérez-García, Maximilian Ilse, Daniel C. Castro, Benedikt Boecking, Harshita Sharma, Kenza Bouzid, Anja Thieme, Anton Schwaighofer, Maria Wetscherek, Matthew P. Lungren, Aditya Nori, Javier Alvarez-Valle, Ozan Oktay*<br>
[11th Jan., 2023] [CVPR, 2023]<br>
[[Paper](https://arxiv.org/pdf/2301.04558.pdf)]<br>


**CLIP-Driven Universal Model for Organ Segmentation and Tumor Detection**<br>
*Jie Liu, Yixiao Zhang, Jie-Neng Chen, Junfei Xiao, Yongyi Lu, Bennett A Landman, Yixuan Yuan, Alan Yuille, Yucheng Tang, Zongwei Zhou*<br>
[2nd Jan., 2023] [ICCV, 2023]<br>
[[Paper](https://arxiv.org/abs/2301.00785)] [[GitHub](https://github.com/ljwztc/CLIP-Driven-Universal-Model)]<br>


**MedCLIP: Contrastive Learning from Unpaired Medical Images and Text**<br>
*Zifeng Wang, Zhenbang Wu, Dinesh Agarwal, Jimeng Sun*<br>
[18th Oct., 2022] [EMNLP, 2022]<br>
[[Paper](https://arxiv.org/pdf/2210.10163.pdf)] [[GitHub](https://github.com/RyanWangZf/MedCLIP)]<br>

**Expert-level detection of pathologies from unannotated chest X-ray images via self-supervised learning**<br>
*Ekin Tiu, Ellie Talius, Pujan Patel, Curtis P. Langlotz, Andrew Y. Ng, Pranav Rajpurkar*<br>
[15th Sep., 2022] [Nature Biomedical Engineering, 2022]<br>
[[Paper](https://www.nature.com/articles/s41551-022-00936-9)]<br>

---

#### Conversational

**Radiology-Llama2: Best-in-Class Large Language Model for Radiology**<br>
*Zhengliang Liu, Yiwei Li, Peng Shu, Aoxiao Zhong, Longtao Yang, Chao Ju, Zihao Wu, Chong Ma, Jie Luo, Cheng Chen, Sekeun Kim, Jiang Hu, Haixing Dai, Lin Zhao, Dajiang Zhu, Jun Liu, Wei Liu, Dinggang Shen, Tianming Liu, Quanzheng Li, Xiang Li*<br>
[29th Aug., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2309.06419)]<br>


**ClinicalGPT: Large Language Models Finetuned with Diverse Medical Data and Comprehensive Evaluation**<br>
*Guangyu Wang, Guoxing Yang, Zongxin Du, Longjun Fan, Xiaohu Li*<br>
[16th Jun., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2306.09968)]<br>


**XrayGPT: Chest Radiographs Summarization using Medical Vision-Language Models**<br>
*Omkar Thawkar, Abdelrahman Shaker, Sahal Shaji Mullappilly, Hisham Cholakkal, Rao Muhammad Anwer, Salman Khan, Jorma Laaksonen, Fahad Shahbaz Khan*<br>
[13th Jun., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2306.07971)] [[GitHub](https://github.com/mbzuai-oryx/XrayGPT)]<br>


**LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day**<br>
*Chunyuan Li, Cliff Wong, Sheng Zhang, Naoto Usuyama, Haotian Liu, Jianwei Yang, Tristan Naumann, Hoifung Poon, Jianfeng Gao*<br>
[1st Jun., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2306.00890)] [[GitHub](https://github.com/microsoft/LLaVA-Med)]<br>


**PMC-LLaMA: Towards Building Open-source Language Models for Medicine**<br>
*Chaoyi Wu, Weixiong Lin, Xiaoman Zhang, Ya Zhang, Yanfeng Wang, Weidi Xie*<br>
[27th Apr., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2304.14454)] [[GitHub](https://github.com/chaoyi-wu/PMC-LLaMA)]<br>


**Visual Med-Alpaca: A Parameter-Efficient Biomedical LLM with Visual Capabilities**<br>
*Chang Shu, Baian Chen, Fangyu Liu, Zihao Fu, Ehsan Shareghi, Nigel Collier*<br>
[11th Apr., 2023] [GitHub, 2023]<br>
[[GitHub](https://github.com/cambridgeltl/visual-med-alpaca)]<br>


**ChatDoctor: A Medical Chat Model Fine-Tuned on a Large Language Model Meta-AI (LLaMA) Using Medical Domain Knowledge**<br>
*Yunxiang Li, Zihan Li, Kai Zhang, Ruilong Dan, Steve Jiang, You Zhang*<br>
[24th Mar., 2023] [Cureus, 2023]<br>
[[Paper](https://arxiv.org/abs/2303.14070)] [[GitHub](https://github.com/Kent0n-Li/ChatDoctor)]<br>


**DeID-GPT: Zero-shot Medical Text De-Identification by GPT-4**<br>
*Zhengliang Liu, Xiaowei Yu, Lu Zhang, Zihao Wu, Chao Cao, Haixing Dai, Lin Zhao, Wei Liu, Dinggang Shen, Quanzheng Li, Tianming Liu, Dajiang Zhu, Xiang Li*<br>
[20th Mar., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2303.11032.pdf)] [[GitHub](https://github.com/yhydhx/ChatGPT-API)]<br>


**ChatCAD: Interactive Computer-Aided Diagnosis on Medical Image using Large Language Models**<br>
*Sheng Wang, Zihao Zhao, Xi Ouyang, Qian Wang, Dinggang Shen*<br>
[14th Feb., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2302.07257)]<br>


---
#### Generative

**Med-Flamingo: a Multimodal Medical Few-shot Learner**<br>
*Michael Moor, Qian Huang, Shirley Wu, Michihiro Yasunaga, Cyril Zakka, Yash Dalmia, Eduardo Pontes Reis, Pranav Rajpurkar, Jure Leskovec*<br>
[27th Jul., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2307.15189)] [[GitHub](https://github.com/snap-stanford/med-flamingo)]<br>


**Clinical-BERT: Vision-Language Pre-training for Radiograph Diagnosis and Reports Generation**<br>
*none*<br>
[22nd Jun., 2022] [AAAI, 2022]<br>
[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20204)]<br>


**Towards Expert-Level Medical Question Answering with Large Language Models**<br>
*Karan Singhal, Tao Tu, Juraj Gottweis, Rory Sayres, Ellery Wulczyn, Le Hou, Kevin Clark, Stephen Pfohl, Heather Cole-Lewis, Darlene Neal, Mike Schaekermann, Amy Wang, Mohamed Amin, Sami Lachgar, Philip Mansfield, Sushant Prakash, Bradley Green, Ewa Dominowska, Blaise Aguera y Arcas, Nenad Tomasev, Yun Liu, Renee Wong, Christopher Semturs, S. Sara Mahdavi, Joelle Barral, Dale Webster, Greg S. Corrado, Yossi Matias, Shekoofeh Azizi, Alan Karthikesalingam, Vivek Natarajan*<br>
[16th May., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2305.09617.pdf)]<br>


---
#### Hybrid

**MedBLIP: Bootstrapping Language-Image Pre-training from 3D Medical Images and Texts**<br>
*Qiuhui Chen, Xinyue Hu, Zirui Wang, Yi Hong*<br>
[18th May., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2305.10799.pdf)] [[GitHub](https://github.com/Qybc/MedBLIP)]<br>


**Vision-Language Model for Visual Question Answering in Medical Imagery**<br>
*none*<br>
[22nd Feb., 2023] [Bioengineering, 2023]<br>
[[Paper](https://www.mdpi.com/2306-5354/10/3/380)]<br>


---
### Visual Prompted Models
#### Adaptations

**Virchow: A Million-Slide Digital Pathology Foundation Model**<br>
*Eugene Vorontsov, Alican Bozkurt, Adam Casson, George Shaikovski, Michal Zelechowski, Siqi Liu, Philippe Mathieu, Alexander van Eck, Donghun Lee, Julian Viret, Eric Robert, Yi Kan Wang, Jeremy D. Kunz, Matthew C. H. Lee, Jan Bernhard, Ran A. Godrich, Gerard Oakley, Ewan Millar, Matthew Hanna, Juan Retamero, William A. Moye, Razik Yousfi, Christopher Kanan, David Klimstra, Brandon Rothrock, Thomas J. Fuchs*<br>
[14th Sep., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2309.07778)]


**SAM-Med2D**<br>
*Junlong Cheng, Jin Ye, Zhongying Deng, Jianpin Chen, Tianbin Li, Haoyu Wang, Yanzhou Su, Ziyan Huang, Jilong Chen, Lei Jiang, Hui Sun, Junjun He, Shaoting Zhang, Min Zhu, Yu Qiao,*<br>
[30th Aug., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2308.16184.pdf)] [[GitHub](https://github.com/uni-medical/SAM-Med2D)]<br>


**SAM-U: Multi-box prompts triggered uncertainty estimation for reliable SAM in medical image**<br>
*Guoyao Deng, Ke Zou, Kai Ren, Meng Wang, Xuedong Yuan, Sancong Ying, Huazhu Fu*<br>
[11th Jul., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2307.04973.pdf)]


**How to Efficiently Adapt Large Segmentation Model(SAM) to Medical Images**<br>
*Xinrong Hu, Xiaowei Xu, Yiyu Shi*<br>
[23rd Jun., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2306.13731.pdf)] [[GitHub](https://github.com/xhu248/AutoSAM)]<br>


**LVM-Med: Learning Large-Scale Self-Supervised Vision Models for Medical Imaging via Second-order Graph Matching**<br>
*Duy M. H. Nguyen, Hoang Nguyen, Nghiem T. Diep, Tan N. Pham, Tri Cao, Binh T. Nguyen, Paul Swoboda, Nhat Ho, Shadi Albarqouni, Pengtao Xie, Daniel Sonntag, Mathias Niepert*<br>
[20th Jun., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2306.11925)] [[GitHub](https://github.com/duyhominhnguyen/LVM-Med)]<br>


**Customized Segment Anything Model for Medical Image Segmentation**<br>
*Kaidong Zhang, Dong Liu*<br>
[26th Apr., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2304.13785.pdf)] [[GitHub](https://github.com/hitachinsk/SAMed)]<br>


**Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentation**<br>
*Medical SAM Adapter: Adapting Segment Anything Model for Medical Image Segmentation*<br>
[25th Apr., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2304.12620.pdf)] [[GitHub](https://github.com/WuJunde/Medical-SAM-Adapter)]<br>


**Segment Anything in Medical Images**<br>
*Jun Ma, Yuting He, Feifei Li, Lin Han, Chenyu You, Bo Wang*<br>
[24th Apr., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2304.12306)] [[GitHub](https://github.com/bowang-lab/MedSAM)]<br>


---
#### Generalist

**A foundation model for generalizable disease detection from retinal images**<br>
*Yukun Zhou, Mark A. Chia, Siegfried K. Wagner, Murat S. Ayhan, Dominic J. Williamson, Robbert R. Struyven, Timing Liu, Moucheng Xu, Mateo G. Lozano, Peter Woodward-Court, Yuka Kihara, Andre Altmann, Aaron Y. Lee, Eric J. Topol, Alastair K. Denniston, Daniel C. Alexander, Pearse A. Keane*<br>
[5th Oct., 2023] [Nature, 2023]<br>
[[Paper](https://www.nature.com/articles/s41586-023-06555-x)] [[GitHub](https://github.com/rmaphoh/RETFound_MAE)]<br>


**Towards Generalist Foundation Model for Radiology**<br>
*Chaoyi Wu, Xiaoman Zhang, Ya Zhang, Yanfeng Wang, Weidi Xie*<br>
[4th Aug., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2308.02463)] [[GitHub](https://github.com/chaoyi-wu/RadFM)]<br>


**Towards Generalist Biomedical AI**<br>
*Tao Tu, Shekoofeh Azizi, Danny Driess, Mike Schaekermann, Mohamed Amin, Pi-Chuan Chang, Andrew Carroll, Chuck Lau, Ryutaro Tanno, Ira Ktena, Basil Mustafa, Aakanksha Chowdhery, Yun Liu, Simon Kornblith, David Fleet, Philip Mansfield, Sushant Prakash, Renee Wong, Sunny Virmani, Christopher Semturs, S Sara Mahdavi, Bradley Green, Ewa Dominowska, Blaise Aguera y Arcas, Joelle Barral, Dale Webster, Greg S. Corrado, Yossi Matias, Karan Singhal, Pete Florence, Alan Karthikesalingam, Vivek Natarajan*<br>
[26th Jul., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/abs/2307.14334)] 


**BiomedGPT: A Unified and Generalist Biomedical Generative Pre trained Transformer for Vision, Language, and Multimodal Tasks**<br>
*Kai Zhang, Jun Yu, Zhiling Yan, Yixin Liu, Eashan Adhikarla, Sunyang Fu, Xun Chen, Chen Chen, Yuyin Zhou, Xiang Li, Lifang He, Brian D. Davison, Quanzheng Li, Yong Chen, Hongfang Liu, Lichao Sun*<br>
[26th May., 2023] [arXiv, 2023]<br>
[[Paper](https://arxiv.org/pdf/2305.17100.pdf)] [[GitHub](https://github.com/taokz/BiomedGPT)]<br>


**Generalist Vision Foundation Models for Medical Imaging: A Case Study of Segment Anything Model on Zero-Shot Medical Segmentation**<br>
*Peilun Shi, Jianing Qiu, Sai Mu Dalike Abaxi, Hao Wei, Frank P.-W. Lo, Wu Yuan*<br>
[25th Apr., 2023] [Diagnostics, 2023]<br>
[[Paper](https://arxiv.org/pdf/2304.12637v2.pdf)] [[GitHub](https://github.com/hwei-hw/Generalist_Vision_Foundation_Models_for_Medical_Imaging)]<br>


**Foundation models for generalist medical artificial intelligence**<br>
*Michael Moor, Oishi Banerjee, Zahra Shakeri Hossein Abad, Harlan M Krumholz, Jure Leskovec, Eric J Topol, Pranav Rajpurkar*<br>
[12th Apr., 2023] [Nature, 2023]<br>
[[Paper](https://www.nature.com/articles/s41586-023-05881-4)] 
