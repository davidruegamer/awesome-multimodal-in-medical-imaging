[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![](https://img.shields.io/github/last-commit/Richard88888/awesome-multimodal-in-medical-imaging?color=green) 
![](https://img.shields.io/badge/PaperNumber-80-brightgreen)

# Awesome-Multimodal-Applications-In-Medical-Imaging
This repository includes resources on several applications of multi-modal learning in medical imaging.

## Overview
- [Survey](https://github.com/Richard88888/awesome-multimodal-in-medical-imaging#survey)
- [Medical Report Generation](https://github.com/Richard88888/awesome-multimodal-in-medical-imaging#medical-report-generation)
- [Medical Visual Question Answering](https://github.com/Richard88888/awesome-multimodal-in-medical-imaging#medical-visual-question-answering)
- [Medical Vision-Language Model](https://github.com/Richard88888/awesome-multimodal-in-medical-imaging#medical-vision-language-model)

## Survey ![](https://img.shields.io/badge/survey-red)
- [**arXiv 2022**] Visual Attention Methods in Deep Learning: An In-Depth Survey [[pdf]](https://arxiv.org/pdf/2204.07756.pdf)
- [**arXiv 2022**] Medical Image Understanding with Pretrained Vision Language Models: A Comprehensive Study [[pdf]](https://arxiv.org/pdf/2209.15517)
- [**arXiv 2022**] Vision+X: A Survey on Multimodal Learning in the Light of Data [[pdf]](https://arxiv.org/pdf/2210.02884)

## Medical Report Generation ![](https://img.shields.io/badge/Medical_Report_Generation-blue)
- [**NeurIPS 2021 Datasets and Benchmarks Track (Round 2)**] FFA-IR: Towards an Explainable and Reliable Medical Report Generation Benchmark [[pdf]](https://openreview.net/pdf?id=FgYTwJbjbf) [[code]](https://github.com/mlii0117/FFA-IR)
- [**arXiv 2020**] Auxiliary Signal-Guided Knowledge Encoder-Decoder for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2006.03744.pdf)
- [**CVPR 2022**] Cross-modal Clinical Graph Transformer for Ophthalmic Report Generation [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Cross-Modal_Clinical_Graph_Transformer_for_Ophthalmic_Report_Generation_CVPR_2022_paper.pdf)
- [**EMNLP 2018**] Automated Generation of Accurate & Fluent Medical X-ray Reports [[pdf]](https://aclanthology.org/2021.emnlp-main.288.pdf) [[code]](https://github.com/ginobilinie/xray_report_generation)
- [**ACL 2018**] On the Automatic Generation of Medical Imaging Reports [[pdf]](https://arxiv.org/pdf/1711.08195.pdf) [[code]](https://github.com/ginobilinie/xray_report_generation)
- [**ACL 2021**] Competence-based Multimodal Curriculum Learning for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2206.14579)
- [**NeurIPS 2018**] Hybrid Retrieval-Generation Reinforced Agent for Medical Image Report Generation [[pdf]](https://proceedings.neurips.cc/paper/2018/file/e07413354875be01a996dc560274708e-Paper.pdf)
- [**CVPR 2021**] Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2106.06963)
- [**MICCAI 2021**] AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation [[pdf]](https://link.springer.com/epdf/10.1007/978-3-030-87199-4_7?sharing_token=iMTuynS886TPRX2tpd4j_ve4RwlQNchNByi7wbcMAY77-APbzlXwOT5RhkQVJUpA8C1IDKnp8kmcMzkygX0JSaQ4fMfisgha9cEjIOOnQyQt2U7lkDP7X1X-78q5y-eDpjODrlaPQ8bIR5jMLYGNzIjbKcbHi8GzVXsvB54kSUY%3D)
- [**NAACL-HLT 2021**] Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2010.10042.pdf) [[code]](https://github.com/ysmiura/ifcc)
- [**MICCAI 2021**] RATCHET: Medical Transformer for Chest X-ray Diagnosis and Reporting [[pdf]](https://arxiv.org/pdf/2107.02104.pdf)[[code]](https://github.com/farrell236/RATCHET)
- [**arXiv 2022**] Attributed Abnormality Graph Embedding for Clinically Accurate X-Ray Report Generation [[pdf]](https://arxiv.org/pdf/2207.01208)
- [**EMNLP 2020**] Generating Radiology Reports via Memory-driven Transformer [[pdf]](https://arxiv.org/pdf/2010.16056) [[code]](https://github.com/zhjohnchan/R2Gen)
- [**ACCV 2020**] Hierarchical X-Ray Report Generation via Pathology tags and Multi Head Attention [[pdf]](https://openaccess.thecvf.com/content/ACCV2020/papers/Srinivasan_Hierarchical_X-Ray_Report_Generation_via_Pathology_tags_and_Multi_Head_ACCV_2020_paper.pdf) [[code]](https://medicalcaption.github.io/)
- [**MICCAI 2021**] Trust It or Not: Confidence-Guided Automatic Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2106.10887) 
- [**MICCAI 2021**] Surgical Instruction Generation with Transformers [[pdf]](https://arxiv.org/pdf/2107.06964)
- [**MICCAI 2021**] Class-Incremental Domain Adaptation with Smoothing and Calibration for Surgical Report Generation [[pdf]](https://arxiv.org/pdf/2107.11091) [[code]](https://github.com/XuMengyaAmy/CIDACaptioning)
- [**Nature Machine Intelligence 2022**] Generalized Radiograph Representation Learning via Cross-supervision between Images and Free-text Radiology Reports [[pdf]](https://arxiv.org/abs/2111.03452) [[code]](https://github.com/funnyzhou/refers)
- [**MICCAI 2022**] A Self-Guided Framework for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2206.09378)
- [**ACL-IJCNLP 2021**] Cross-modal Memory Networks for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2204.13258) [[code]](https://github.com/zhjohnchan/R2GenCMN)
- [**MICCAI 2022**] A Medical Semantic-Assisted Transformer for Radiographic Report Generation [[pdf]](https://arxiv.org/pdf/2208.10358)
- [**MIDL 2022**] Representative Image Feature Extraction via Contrastive Learning Pretraining for Chest X-ray Report Generation [[pdf]](https://arxiv.org/pdf/2209.01604)
- [**MICCAI 2022**] RepsNet: Combining Vision with Language for Automated Medical Reports [[pdf]](https://arxiv.org/pdf/2209.13171) [[code]](https://sites.google.com/view/repsnet)
- [**arXiv 2022**] Improving Radiology Report Generation Systems by Removing Hallucinated References to Non-existent Priors [[pdf]](https://arxiv.org/pdf/2210.06340)
- [**IEEE TNNLS 2022**] Hybrid Reinforced Medical Report Generation with M-Linear Attention and Repetition Penalty [[pdf]](https://arxiv.org/pdf/2210.13729)
- [**Medical Image Analysis 2022**] CAMANet: Class Activation Map Guided Attention Network for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2211.01412) 
- [**arXiv 2022**] Lesion Guided Explainable Few Weak-shot Medical Report Generation [[pdf]](https://arxiv.org/pdf/2211.08732.pdf) [[code]](https://github.com/jinghanSunn/Few-weak-shot-RG)
- [**arXiv 2022**] Self adaptive global-local feature enhancement for radiology report generation [[pdf]](https://arxiv.org/pdf/2211.11380)
- [**arXiv 2022**] On the Importance of Image Encoding in Automated Chest X-Ray Report Generation [[pdf]](https://arxiv.org/pdf/2211.13465) [[code]](https://github.com/mudabek/encoding-cxr-report-gen)
- [**arXiv 2022**] RoentGen: Vision-Language Foundation Model for Chest X-ray Generation [[pdf]](https://arxiv.org/pdf/2211.12737)
- [**arXiv 2022**] DeltaNet:Conditional Medical Report Generation for COVID-19 Diagnosis [[pdf]](https://arxiv.org/pdf/2211.13229) [[code]](https://github.com/LX-doctorAI1/DeltaNet)
- [**arXiv 2023**] Unified Chest X-ray and Radiology Report Generation Model with Multi-view Chest X-rays [[pdf]](https://arxiv.org/pdf/2302.12172) [[code]](https://github.com/ttumyche/UniXGen)
- [**ECCV 2022**] Cross-modal Prototype Driven Network for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2207.04818) [[code]](https://github.com/Markin-Wang/XProNet)
- [**WWW 2023**] Auxiliary signal-guided knowledge encoder-decoder for medical report generation [[pdf]](https://link.springer.com/article/10.1007/s11280-022-01013-6)
- [**CVPR 2023**] Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation [[pdf]](https://arxiv.org/pdf/2303.10323) [[code]](https://github.com/mlii0117/DCL)
- [**MIDL 2023**] Multimodal Image-Text Matching Improves Retrieval-based Chest X-Ray Report Generation [[pdf]](https://arxiv.org/pdf/2303.17579) [[code]](https://github.com/rajpurkarlab/X-REM)
- [**arXiv 2023**] Visual-Linguistic Causal Intervention for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2303.09117) [[code]](https://github.com/WissingChen/VLCI)

## Medical Visual Question Answering ![](https://img.shields.io/badge/Medical_Visual_Question_Answering-red)
- [**arXiv 2021**] MuVAM: A Multi-View Attention-based Model for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2107.03216)
- [**MICCAI 2022**] Consistency-preserving Visual Question Answering in Medical Imaging [[pdf]](https://arxiv.org/pdf/2206.13296) [[code]](https://github.com/sergiotasconmorales/consistency_vqa)
- [**TMI 2020**] A Question-Centric Model for Visual Question Answering in Medical Imaging [[pdf]](https://arxiv.org/pdf/2003.08760) [[code]](https://github.com/vuhoangminh/vqa_medical)
- [**arXiv 2021**] Medical Visual Question Answering: A Survey [[pdf]](https://arxiv.org/pdf/2111.10056)
- [**arXiv 2022**] Surgical-VQA: Visual Question Answering in Surgical Scenes using Transformer [[pdf]](https://arxiv.org/pdf/2206.11053) [[code]](https://github.com/lalithjets/Surgical_VQA)
- [**CLEF 2020 Working Notes**] HCP-MIC at VQA-Med 2020: Effective visual representation for medical visual question answering [[pdf]](http://ceur-ws.org/Vol-2696/paper_74.pdf) [[code]](https://github.com/haifangong/HCP-MIC-at-ImageCLEF-VQA-Med-2020)
- [**CLEF 2020 Working Notes**] TeamS at VQA-Med 2021: BBN-Orchestra for long-tailed medical visual question answering [[pdf]](http://ceur-ws.org/Vol-2936/paper-98.pdf) [[code]](https://github.com/d4l-data4life/BBNOrchestra-for-VQAmed2021)
- [**Nature Scientific Reports 2021**] MedFuseNet: An attention-based multimodal deep learning model for visual question answering in the medical domain [[pdf]](https://www.nature.com/articles/s41598-021-98390-1) 
- [**ECCV 2022**] Distilled Dual-Encoder Model for Vision-Language Understanding [[pdf]](https://arxiv.org/pdf/2112.08723) [[code]](https://github.com/yzd-v/MGD)
- [**arXiv 2022**] A Dual-Attention Learning Network with Word and Sentence Embedding for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2210.00220) [[code]](https://github.com/coisini-glenda/wsdan-for-medical-visual-question-answering)
- [**arXiv 2022**] MF2-MVQA: A Multi-stage Feature Fusion method for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2211.05991)
- [**arXiv 2022**] Self-supervised vision-language pretraining for Medical visual question answering [[pdf]](https://arxiv.org/pdf/2211.13594) [[code]](https://github.com/pengfeiliHEU/M2I2)
- [**arXiv 2022**] UnICLAM:Contrastive Representation Learning with Adversarial Masking for Unified and Interpretable Medical Vision Question Answering [[pdf]](https://arxiv.org/pdf/2212.10729) 
- [**arXiv 2023**] Interpretable Medical Image Visual Question Answering via Multi-Modal Relationship Graph Learning [[pdf]](https://arxiv.org/pdf/2302.09636)
- [**arXiv 2023**] Medical visual question answering using joint self-supervised learning [[pdf]](https://arxiv.org/pdf/2302.13069) 
- [**arXiv 2023**] RAMM: Retrieval-augmented Biomedical Visual Question Answering with Multi-modal Pre-training [[pdf]](https://arxiv.org/pdf/2303.00534) [[code]](https://github.com/GanjinZero/RAMM) 
- [**arXiv 2023**] Q2ATransformer: Improving Medical VQA via an Answer Querying Decoder [[pdf]](https://arxiv.org/pdf/2304.01611)
- [**arXiv 2023**] Open-Ended Medical Visual Question Answering Through Prefix Tuning of Language Models [[pdf]](https://arxiv.org/pdf/2303.05977)

## Medical Vision-Language Model ![](https://img.shields.io/badge/Medical_Vision_Language_Model-blue)
- [**ICLR 2023**] Medical Image Understanding with Pretrained Vision Language Models: A Comprehensive Study [[pdf]](https://openreview.net/pdf?id=txlWziuCE5W) [[code]](https://github.com/MembrLab/MIU-VL)
- [**EMNLP 2022**] Medclip: Contrastive learning from unpaired medical images and text [[pdf]](https://arxiv.org/pdf/2210.10163.pdf) [[code]](https://github.com/RyanWangZf/MedCLIP)
- [**arXiv 2023**] CLIP-Driven Universal Model for Organ Segmentation and Tumor Detection [[pdf]](https://arxiv.org/pdf/2301.00785.pdf) [[code]](https://github.com/ljwztc/CLIP-Driven-Universal-Model)
- [**arXiv 2023**] Towards General Purpose Medical AI: Continual Learning Medical Foundation Model [[pdf]](https://arxiv.org/pdf/2303.06580.pdf)
- [**NeurIPS Workshop 2022**] Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains [[pdf]](https://arxiv.org/pdf/2210.04133)
- [**ACL 2022**] ViLMedic: a framework for research at the intersection of vision and language in medical AI [[pdf]](https://aclanthology.org/2022.acl-demo.3.pdf) [[code]](https://github.com/jbdel/vilmedic)
- [**MICCAI 2022**] Multi-modal Masked Autoencoders for Medical Vision-and-Language Pre-training [[pdf]](https://arxiv.org/pdf/2209.07098.pdf) [[code]](https://github.com/zhjohnchan/M3AE)
- [**IEEE Journal of Biomedical and Health Informatics 2022**] Multi-Modal Understanding and Generation for Medical Images and Text via Vision-Language Pre-Training [[pdf]](https://arxiv.org/pdf/2105.11333) [[code]](https://github.com/SuperSupermoon/MedViLL)
- [**AAAI 2022**] Clinical-BERT: Vision-Language Pre-training for Radiograph Diagnosis and Reports Generation [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/download/20204/19963)
- [**arXiv 2022**] LViT: Language meets Vision Transformer in Medical Image Segmentation [[pdf]](https://arxiv.org/pdf/2206.14718) [[code]](https://github.com/HUANGLIZI/LViT)
- [**arXiv 2023**] Towards Unifying Medical Vision-and-Language Pre-training via Soft Prompts [[pdf]](https://arxiv.org/pdf/2302.08958) [[code]](https://github.com/zhjohnchan/PTUnifier)
- [**IEEE Journal of Biomedical and Health Informatics 2022**] Vision-language transformer for interpretable pathology visual question answering [[link]](https://ieeexplore.ieee.org/abstract/document/9745795)
- [**arXiv 2022**] RoentGen: Vision-Language Foundation Model for Chest X-ray Generation [[pdf]](https://arxiv.org/pdf/2211.12737)
- [**ECCV 2022**] Making the most of text semantics to improve biomedical vision–language processing [[pdf]](https://arxiv.org/pdf/2204.09817)
- [**arXiv 2023**] Large-Scale Domain-Specific Pretraining for Biomedical Vision-Language Processing [[pdf]](https://arxiv.org/pdf/2303.00915) [[code]](https://aka.ms/biomedclip)
- [**MICCAI 2022**] Berthop: An effective vision-and-language model for chest x-ray disease diagnosis [[pdf]](https://arxiv.org/pdf/2108.04938)
- [**ICLR 2023**] Advancing Radiograph Representation Learning with Masked Record Modeling [[pdf]](https://arxiv.org/pdf/2301.13155) [[code]](https://github.com/RL4M/MRM-pytorch)
- [**arXiv 2023**] ConTEXTual Net: A Multimodal Vision-Language Model for Segmentation of Pneumothorax [[pdf]](https://arxiv.org/pdf/2303.01615)
- [**arXiv 2023**] PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents [[pdf]](https://arxiv.org/pdf/2303.07240)
- [**arXiv 2023**] Open-Ended Medical Visual Question Answering Through Prefix Tuning of Language Models [[pdf]](https://arxiv.org/pdf/2303.05977)
- [**arXiv 2023**] ChatCAD: Interactive Computer-Aided Diagnosis on Medical Image using Large Language Models [[pdf]](https://arxiv.org/pdf/2302.07257)
- [**arXiv 2023**] MedKLIP: Medical Knowledge Enhanced Language-Image Pre-Training [[pdf]](https://arxiv.org/pdf/2301.02228) [[project]](https://chaoyi-wu.github.io/MedKLIP/)
- [**MICCAI 2022**] RepsNet: Combining Vision with Language for Automated Medical Reports [[pdf]](https://arxiv.org/pdf/2209.13171) [[code]](https://sites.google.com/view/repsnet)
- [**CVPR 2023**] Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing [[pdf]](https://arxiv.org/pdf/2301.04558)
- [**NeurIPS 2022**] Multi-Granularity Cross-modal Alignment for Generalized Medical Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2210.06044) [[code]](https://github.com/fuying-wang/MGCA)
