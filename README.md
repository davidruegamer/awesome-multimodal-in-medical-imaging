[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
[![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
![](https://img.shields.io/github/last-commit/richard-peng-xia/awesome-multimodal-in-medical-imaging?color=green)
![](https://img.shields.io/badge/PaperNumber-203-brightgreen)

# Awesome-Multimodal-Applications-In-Medical-Imaging

This repository includes resources on several applications of multi-modal learning in medical imaging, including papers related to <b>large language models (LLM)</b>. Papers involving LLM are **bold**.

## Contributing

Please feel free to send me [pull requests](https://github.com/richard-peng-xia/awesome-multimodal-in-medical-imaging/pulls) or [email](mailto:richard.peng.xia@gmail.com) to add links or to discuss with me about this area.
Markdown format:

```markdown
- [**Name of Conference or Journal + Year**] Paper Name. [[pdf]](link) [[code]](link)
```

## Overview

- [Survey](https://github.com/richard-peng-xia/awesome-multimodal-in-medical-imaging#survey)
- [Medical Report Generation](https://github.com/richard-peng-xia/awesome-multimodal-in-medical-imaging#medical-report-generation)
- [Medical Visual Question Answering](https://github.com/richard-peng-xia/awesome-multimodal-in-medical-imaging#medical-visual-question-answering)
- [Medical Vision-Language Model](https://github.com/richard-peng-xia/awesome-multimodal-in-medical-imaging#medical-vision-language-model)

## Survey ![](https://img.shields.io/badge/survey-red)

- [**arXiv 2022**] Visual Attention Methods in Deep Learning: An In-Depth Survey [[pdf]](https://arxiv.org/pdf/2204.07756.pdf)
- [**arXiv 2022**] Vision+X: A Survey on Multimodal Learning in the Light of Data [[pdf]](https://arxiv.org/pdf/2210.02884)
- [**arXiv 2023**] Vision Language Models for Vision Tasks: A Survey [[pdf]](https://arxiv.org/pdf/2304.00685) [[code]](https://github.com/jingyi0000/VLM_survey)
- [**arXiv 2023**] A Systematic Review of Deep Learning-based Research on Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2311.14199.pdf) [[code]](https://github.com/synlp/RRG-Review)
- [**Artif Intell Med 2023**] Medical Visual Question Answering: A Survey [[pdf]](https://arxiv.org/pdf/2111.10056)
- [**arXiv 2023**] Medical Vision Language Pretraining: A survey [[pdf]](https://arxiv.org/pdf/2312.06224)
- [**arXiv 2023**] CLIP in Medical Imaging: A Comprehensive Survey [[pdf]](https://arxiv.org/pdf/2312.07353) [[code]](https://github.com/zhaozh10/Awesome-CLIP-in-Medical-Imaging)
- [**arXiv 2024**] Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review [[pdf]](https://arxiv.org/pdf/2403.02469)

## Medical Report Generation ![](https://img.shields.io/badge/Medical_Report_Generation-blue)

### 2018
- [**EMNLP 2018**] Automated Generation of Accurate & Fluent Medical X-ray Reports [[pdf]](https://aclanthology.org/2021.emnlp-main.288.pdf) [[code]](https://github.com/ginobilinie/xray_report_generation)
- [**ACL 2018**] On the Automatic Generation of Medical Imaging Reports [[pdf]](https://arxiv.org/pdf/1711.08195.pdf) [[code]](https://github.com/ginobilinie/xray_report_generation)
- [**NeurIPS 2018**] Hybrid Retrieval-Generation Reinforced Agent for Medical Image Report Generation [[pdf]](https://proceedings.neurips.cc/paper/2018/file/e07413354875be01a996dc560274708e-Paper.pdf)
### 2019
- [**AAAI 2019**] Knowledge-Driven Encode, Retrieve, Paraphrase for Medical Image Report Generation [[pdf]](https://arxiv.org/pdf/1903.10122)
- [**ICDM 2019**] Automatic Generation of Medical Imaging Diagnostic Report with Hierarchical Recurrent Neural Network [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp%3Ftp%3D%26arnumber%3D8970668)
- [**MICCAI 2019**] Automatic Radiology Report Generation based on Multi-view Image Fusion and Medical Concept Enrichment [[pdf]](https://arxiv.org/pdf/1907.09085)
### 2020
- [**AAAI 2020**] When Radiology Report Generation Meets Knowledge Graph [[pdf]](https://arxiv.org/pdf/2002.08277)
- [**EMNLP 2020**] Generating Radiology Reports via Memory-driven Transformer [[pdf]](https://arxiv.org/pdf/2010.16056) [[code]](https://github.com/zhjohnchan/R2Gen)
- [**ACCV 2020**] Hierarchical X-Ray Report Generation via Pathology tags and Multi Head Attention [[pdf]](https://openaccess.thecvf.com/content/ACCV2020/papers/Srinivasan_Hierarchical_X-Ray_Report_Generation_via_Pathology_tags_and_Multi_Head_ACCV_2020_paper.pdf) [[code]](https://medicalcaption.github.io/)
### 2021
- [**NeurIPS 2021 D&B**] FFA-IR: Towards an Explainable and Reliable Medical Report Generation Benchmark [[pdf]](https://openreview.net/pdf?id=FgYTwJbjbf) [[code]](https://github.com/mlii0117/FFA-IR)
- [**ACL 2021**] Competence-based Multimodal Curriculum Learning for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2206.14579)
- [**CVPR 2021**] Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2106.06963)
- [**MICCAI 2021**] AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation [[pdf]](https://link.springer.com/epdf/10.1007/978-3-030-87199-4_7?sharing_token=iMTuynS886TPRX2tpd4j_ve4RwlQNchNByi7wbcMAY77-APbzlXwOT5RhkQVJUpA8C1IDKnp8kmcMzkygX0JSaQ4fMfisgha9cEjIOOnQyQt2U7lkDP7X1X-78q5y-eDpjODrlaPQ8bIR5jMLYGNzIjbKcbHi8GzVXsvB54kSUY%3D)
- [**NAACL-HLT 2021**] Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2010.10042.pdf) [[code]](https://github.com/ysmiura/ifcc)
- [**MICCAI 2021**] RATCHET: Medical Transformer for Chest X-ray Diagnosis and Reporting [[pdf]](https://arxiv.org/pdf/2107.02104.pdf)[[code]](https://github.com/farrell236/RATCHET)
- [**MICCAI 2021**] Trust It or Not: Confidence-Guided Automatic Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2106.10887)
- [**MICCAI 2021**] Surgical Instruction Generation with Transformers [[pdf]](https://arxiv.org/pdf/2107.06964)
- [**MICCAI 2021**] Class-Incremental Domain Adaptation with Smoothing and Calibration for Surgical Report Generation [[pdf]](https://arxiv.org/pdf/2107.11091) [[code]](https://github.com/XuMengyaAmy/CIDACaptioning)
- [**ACL 2021**] Cross-modal Memory Networks for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2204.13258) [[code]](https://github.com/zhjohnchan/R2GenCMN)
### 2022
- [**CVPR 2022**] Cross-modal Clinical Graph Transformer for Ophthalmic Report Generation [[pdf]](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Cross-Modal_Clinical_Graph_Transformer_for_Ophthalmic_Report_Generation_CVPR_2022_paper.pdf)
- [**Nature Machine Intelligence 2022**] Generalized Radiograph Representation Learning via Cross-supervision between Images and Free-text Radiology Reports [[pdf]](https://arxiv.org/abs/2111.03452) [[code]](https://github.com/funnyzhou/refers)
- [**MICCAI 2022**] A Self-Guided Framework for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2206.09378)
- [**MICCAI 2022**] A Medical Semantic-Assisted Transformer for Radiographic Report Generation [[pdf]](https://arxiv.org/pdf/2208.10358)
- [**MIDL 2022**] Representative Image Feature Extraction via Contrastive Learning Pretraining for Chest X-ray Report Generation [[pdf]](https://arxiv.org/pdf/2209.01604)
- [**MICCAI 2022**] RepsNet: Combining Vision with Language for Automated Medical Reports [[pdf]](https://arxiv.org/pdf/2209.13171) [[code]](https://sites.google.com/view/repsnet)
- [**ICML 2022**] Improving Radiology Report Generation Systems by Removing Hallucinated References to Non-existent Priors [[pdf]](https://arxiv.org/pdf/2210.06340)
- [**TNNLS 2022**] Hybrid Reinforced Medical Report Generation with M-Linear Attention and Repetition Penalty [[pdf]](https://arxiv.org/pdf/2210.13729)
- [**MedIA 2022**] CAMANet: Class Activation Map Guided Attention Network for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2211.01412)
- [**MedIA 2022**] Knowledge matters: Chest radiology report generation with general and specific knowledge [[pdf]](https://www.sciencedirect.com/sdfe/reader/pii/S1361841522001578/pdf) [[code]](https://github.com/LX-doctorAI1/GSKET)
- [**MICCAI 2022**] Lesion Guided Explainable Few Weak-shot Medical Report Generation [[pdf]](https://arxiv.org/pdf/2211.08732.pdf) [[code]](https://github.com/jinghanSunn/Few-weak-shot-RG)
- [**BMVC 2022**] On the Importance of Image Encoding in Automated Chest X-Ray Report Generation [[pdf]](https://arxiv.org/pdf/2211.13465) [[code]](https://github.com/mudabek/encoding-cxr-report-gen)
- [**arXiv 2022**] RoentGen: Vision-Language Foundation Model for Chest X-ray Generation [[pdf]](https://arxiv.org/pdf/2211.12737)
- [**COLING 2022**] DeltaNet:Conditional Medical Report Generation for COVID-19 Diagnosis [[pdf]](https://arxiv.org/pdf/2211.13229) [[code]](https://github.com/LX-doctorAI1/DeltaNet)
- [**ECCV 2022**] Cross-modal Prototype Driven Network for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2207.04818) [[code]](https://github.com/Markin-Wang/XProNet)
### 2023
- [**ICIP 2023**] Self adaptive global-local feature enhancement for radiology report generation [[pdf]](https://arxiv.org/pdf/2211.11380)
- [**TMI 2023**] Attributed Abnormality Graph Embedding for Clinically Accurate X-Ray Report Generation [[pdf]](https://arxiv.org/pdf/2207.01208)
- [**arXiv 2023**] Unified Chest X-ray and Radiology Report Generation Model with Multi-view Chest X-rays [[pdf]](https://arxiv.org/pdf/2302.12172) [[code]](https://github.com/ttumyche/UniXGen)
- [**WWW 2023**] Auxiliary signal-guided knowledge encoder-decoder for medical report generation [[pdf]](https://link.springer.com/article/10.1007/s11280-022-01013-6)
- [**CVPR 2023**] Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation [[pdf]](https://arxiv.org/pdf/2303.10323) [[code]](https://github.com/mlii0117/DCL)
- [**CVPR 2023**] KiUT: Knowledge-Injected U-Transformer for Radiology Report Generation [[pdf]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_KiUT_Knowledge-Injected_U-Transformer_for_Radiology_Report_Generation_CVPR_2023_paper.pdf)
- [**CVPR 2023**] Interactive and Explainable Region-guided Radiology Report Generation [[pdf]](https://arxiv.org/abs/2304.08295) [[code]](https://github.com/ttanida/rgrg)
- [**MIDL 2023**] Multimodal Image-Text Matching Improves Retrieval-based Chest X-Ray Report Generation [[pdf]](https://arxiv.org/pdf/2303.17579) [[code]](https://github.com/rajpurkarlab/X-REM)
- [**arXiv 2023**] Visual-Linguistic Causal Intervention for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2303.09117) [[code]](https://github.com/WissingChen/VLCI)
- [**MIDL 2023**] Vision-Language Modelling For Radiological Imaging and Reports In The Low Data Regime [[pdf]](https://arxiv.org/pdf/2303.17644)
- [**arXiv 2023**] Cross-Modal Causal Intervention for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2303.09117) [[code]](https://github.com/WissingChen/VLCI)
- [**ICASSP 2023**] MvCo-DoT:Multi-View Contrastive Domain Transfer Network for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2304.07465.pdf)
- [**CHIL 2023**] Token Imbalance Adaptation for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2304.09185) [[code]](https://github.com/woqingdoua/TIMER)
- [**AAAI 2023**] "Nothing Abnormal": Disambiguating Medical Reports via Contrastive Knowledge Infusion [[pdf]](https://arxiv.org/pdf/2305.08300) [[code]](https://github.com/ZexueHe/Med-DEPEN)
- [**arXiv 2023**] Automatic Radiology Report Generation by Learning with Increasingly Hard Negatives [[pdf]](https://arxiv.org/pdf/2305.07176)
- [**arXiv 2023**] S4M: Generating Radiology Reports by A Single Model for Multiple Body Parts [[pdf]](https://arxiv.org/pdf/2305.16685) [[code]](https://github.com/YtongXie/S4M)
- [**arXiv 2023**] Customizing General-Purpose Foundation Models for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2306.05642)
- [**CVPR 2023**] KiUT: Knowledge-injected U-Transformer for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2306.11345)
- [**arXiv 2023**] Utilizing Longitudinal Chest X-Rays and Reports to Pre-Fill Radiology Reports [[pdf]](https://arxiv.org/pdf/2306.08749) 
- [**ACL 2023**] Replace and Report: NLP Assisted Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2306.17180)
- [**ICCV 2023**] PRIOR: Prototype Representation Joint Learning from Medical Images and Reports [[pdf]](https://arxiv.org/pdf/2307.12577) [[code]](https://github.com/QtacierP/PRIOR)
- [**ICML W 2023**] Rethinking Medical Report Generation: Disease Revealing Enhancement with Knowledge Graph [[pdf]](https://arxiv.org/pdf/2307.12526) [[code]](https://github.com/wangyixinxin/mrg-kg)
- [**MICCAI 2023**] Rad-ReStruct: A Novel VQA Benchmark and Method for Structured Radiology Reporting [[pdf]](https://arxiv.org/pdf/2307.05766) [[code]](https://github.com/chantalmp/rad-restruct)
- [**arXiv 2023**] IIHT: Medical Report Generation with Image-to-Indicator Hierarchical Transformer [[pdf]](https://arxiv.org/pdf/2308.05633)
- [**arXiv 2023**] Finding-Aware Anatomical Tokens for Chest X-Ray Automated Reporting [[pdf]](https://arxiv.org/pdf/2308.15961)
- [**arXiv 2023**] PromptMRG: Diagnosis-Driven Prompts for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2308.12604)
- [**arXiv 2023**] Dynamic Multi-Domain Knowledge Networks for Chest X-ray Report Generation [[pdf]](https://arxiv.org/pdf/2310.05119)
- [**MedIA 2023**] C^2M-DoT: Cross-modal consistent multi-view medical report generation with domain transfer network [[pdf]](https://arxiv.org/pdf/2310.05355)
- [**EMNLP 2023 Findings**] Controllable Chest X-Ray Report Generation from Longitudinal Representations [[pdf]](https://arxiv.org/pdf/2310.05881)
- [**BIBM 2023**] Enhanced Knowledge Injection for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2311.00399)
- [**EMNLP 2023 Findings**] Style-Aware Radiology Report Generation with RadGraph and Few-Shot Prompting [[pdf]](https://arxiv.org/pdf/2310.17811)
- [**arXiv 2023**] **Sam-Guided Enhanced Fine-Grained Encoding with Mixed Semantic Learning for Medical Image Captioning** [[pdf]](https://arxiv.org/pdf/2311.01004)
- [**ACL 2023**] ORGAN: Observation-Guided Radiology Report Generation via Tree-Reasoning [[pdf](https://aclanthology.org/2023.acl-long.451/)] [[code]](https://github.com/wjhou/ORGan)
- [**EMNLP 2023 Findings**] RECAP: Towards Precise Radiology Report Generation via Dynamic Disease Progression Reasoning [[pdf](https://arxiv.org/abs/2310.13864)] [[code](https://github.com/wjhou/Recap)]
- [**NeurIPS W 2023**] Effectively Fine-tune to Improve Large Multimodal Models for Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2312.01504)
- [**arXiv 2023**] Radiology-Aware Model-Based Evaluation Metric for Report Generation [[pdf]](https://arxiv.org/pdf/2311.16764)
- [**arXiv 2023**] Radiology Report Generation Using Transformers Conditioned with Non-imaging Data [[pdf]](https://arxiv.org/pdf/2311.11097)
- [**arXiv 2023**] Beyond Images: An Integrative Multi-modal Approach to Chest X-Ray Report Generation [[pdf]](https://arxiv.org/pdf/2311.11090)
- [**EMNLP 2023**] PhenotypeCLIP: Phenotype-based Contrastive Learning for Medical Imaging Report Generation [[pdf]](https://aclanthology.org/2023.emnlp-main.989.pdf)
- [**arXiv 2023**] **Fine-Grained Image-Text Alignment in Medical Imaging Enables Cyclic Image-Report Generation** [[pdf]](https://arxiv.org/pdf/2312.08078)
- [**arXiv 2023**] Improving Medical Report Generation with Adapter Tuning and Knowledge Enhancement in Vision-Language Foundation Models [[pdf]](https://arxiv.org/pdf/2312.03970)
- [**NLPCC 2023**] Medical Report Generation based on Segment-Enhanced Contrastive Representation Learning [[pdf]](https://arxiv.org/pdf/2312.15869)
- [**arXiv 2023**] Fine-Grained Image-Text Alignment in Medical Imaging Enables Cyclic Image-Report Generation [[pdf]](https://arxiv.org/pdf/2312.08078)
- [**MICCAI 2023**] SGT: Scene Graph-Guided Transformer for Surgical Report Generation [[pdf]](https://link.springer.com/chapter/10.1007/978-3-031-16449-1_48) [[code]](https://github.com/ccccchenllll/SGT_master)

### 2024
- [**WACV 2024**] Complex Organ Mask Guided Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2311.02329) [[code]](https://github.com/GaryGuTC/COMG_model)
- [**TMM 2024**] From Observation to Concept: A Flexible Multi-view Paradigm for Medical Report Generation [[pdf]](https://ieeexplore.ieee.org/document/10356722)
- [**TMI 2024**] SGT++: Improved Scene Graph-guided Transformer for Surgical Report Generation [[pdf]](https://ieeexplore.ieee.org/document/10330637/)
- [**arXiv 2024**] Unmasking and Quantifying Racial Bias of Large Language Models in Medical Report Generation [[pdf]](https://arxiv.org/pdf/2401.13867)
- [**arXiv 2024**] Dual-modal Dynamic Traceback Learning for Medical Report Generation [[pdf]](https://arxiv.org/pdf/2401.13267)
- [**arXiv 2024**] MedCycle: Unpaired Medical Report Generation via Cycle-Consistency [[pdf]](https://arxiv.org/pdf/2403.13444)
- [**arXiv 2024**] Scene Graph Aided Radiology Report Generation [[pdf]](https://arxiv.org/pdf/2403.05687)

## Medical Visual Question Answering ![](https://img.shields.io/badge/Medical_Visual_Question_Answering-red)

### 2020
- [**TMI 2020**] A Question-Centric Model for Visual Question Answering in Medical Imaging [[pdf]](https://arxiv.org/pdf/2003.08760) [[code]](https://github.com/vuhoangminh/vqa_medical)
- [**CLEF 2020 Working Notes**] HCP-MIC at VQA-Med 2020: Effective visual representation for medical visual question answering [[pdf]](http://ceur-ws.org/Vol-2696/paper_74.pdf) [[code]](https://github.com/haifangong/HCP-MIC-at-ImageCLEF-VQA-Med-2020)
- [**CLEF 2020 Working Notes**] TeamS at VQA-Med 2021: BBN-Orchestra for long-tailed medical visual question answering [[pdf]](http://ceur-ws.org/Vol-2936/paper-98.pdf) [[code]](https://github.com/d4l-data4life/BBNOrchestra-for-VQAmed2021)
### 2021
- [**arXiv 2021**] MuVAM: A Multi-View Attention-based Model for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2107.03216)
- [**Nature Scientific Reports 2021**] MedFuseNet: An attention-based multimodal deep learning model for visual question answering in the medical domain [[pdf]](https://www.nature.com/articles/s41598-021-98390-1)
### 2022
- [**MICCAI 2022**] Consistency-preserving Visual Question Answering in Medical Imaging [[pdf]](https://arxiv.org/pdf/2206.13296) [[code]](https://github.com/sergiotasconmorales/consistency_vqa)
- [**MICCAI 2022**] Surgical-VQA: Visual Question Answering in Surgical Scenes using Transformer [[pdf]](https://arxiv.org/pdf/2206.11053) [[code]](https://github.com/lalithjets/Surgical_VQA)
- [**ECCV 2022**] Distilled Dual-Encoder Model for Vision-Language Understanding [[pdf]](https://arxiv.org/pdf/2112.08723) [[code]](https://github.com/yzd-v/MGD)
- [**arXiv 2022**] UnICLAM:Contrastive Representation Learning with Adversarial Masking for Unified and Interpretable Medical Vision Question Answering [[pdf]](https://arxiv.org/pdf/2212.10729)
### 2023
- [**TMI 2023**] A Dual-Attention Learning Network with Word and Sentence Embedding for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2210.00220) [[code]](https://github.com/coisini-glenda/wsdan-for-medical-visual-question-answering)
- [**ISBI 2023**] MF2-MVQA: A Multi-stage Feature Fusion method for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2211.05991)
- [**ISBI 2023**] Self-supervised vision-language pretraining for Medical visual question answering [[pdf]](https://arxiv.org/pdf/2211.13594) [[code]](https://github.com/pengfeiliHEU/M2I2)
- [**arXiv 2023**] Interpretable Medical Image Visual Question Answering via Multi-Modal Relationship Graph Learning [[pdf]](https://arxiv.org/pdf/2302.09636)
- [**ACM MM 2023**] RAMM: Retrieval-augmented Biomedical Visual Question Answering with Multi-modal Pre-training [[pdf]](https://arxiv.org/pdf/2303.00534) [[code]](https://github.com/GanjinZero/RAMM)
- [**IPMI 2023**] Q2ATransformer: Improving Medical VQA via an Answer Querying Decoder [[pdf]](https://arxiv.org/pdf/2304.01611)
- [**MICCAI 2023**] Open-Ended Medical Visual Question Answering Through Prefix Tuning of Language Models [[pdf]](https://arxiv.org/pdf/2303.05977) [[code]](https://github.com/tjvsonsbeek/open-ended-medical-vqa)
- [**arXiv 2023**] **PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering** [[pdf]](https://arxiv.org/pdf/2305.10415) [[code]](https://github.com/xiaoman-zhang/PMC-VQA)
- [**MICCAI 2023**] Masked Vision and Language Pre-training with Unimodal and Multimodal Contrastive Losses for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2307.05314) [[code]](https://github.com/pengfeiliHEU/MUMC)
- [**MICCAI 2023**] Localized Questions in Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2307.01067) [[code]](https://github.com/sergiotasconmorales/locvqa)
- [**arXiv 2023**] Multimodal Prompt Retrieval for Generative Visual Question Answering [[pdf]](https://arxiv.org/pdf/2306.17675) [[code]](https://github.com/tossowski/MultimodalPromptRetrieval)
- [**KDD 2023**] Expert Knowledge-Aware Image Difference Graph Representation Learning for Difference-Aware Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2307.11986) [[code]](https://github.com/Holipori/MIMIC-Diff-VQA)
- [**CLEF 2023**] UIT-Saviors at MEDVQA-GI 2023: Improving Multimodal Learning with Image Enhancement for Gastrointestinal Visual Question Answering [[pdf]](https://arxiv.org/pdf/2307.02783)
- [**DICTA 2023**] Visual Question Answering in the Medical Domain [[pdf]](https://arxiv.org/pdf/2309.11080)
- [**NeurIPS 2023 D&B**] EHRXQA: A Multi-Modal Question Answering Dataset for Electronic Health Records with Chest X-ray Images [[pdf]](https://arxiv.org/pdf/2310.18652) [[code]](https://github.com/baeseongsu/ehrxqa)
- [**TETCI 2023**] Parameter-Efficient Transfer Learning for Medical Visual Question Answering [[pdf]](https://ieeexplore.ieee.org/abstract/document/10256025)
- [**MICCAI 2023**] Rad-ReStruct: A Novel VQA Benchmark and Method for Structured Radiology Reporting [[pdf]](https://arxiv.org/pdf/2307.05766) [[code]](https://github.com/ChantalMP/Rad-ReStruct)
- [**arXiv 2023**] BESTMVQA: A Benchmark Evaluation System for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2312.07867) [[demo]](https://youtu.be/QkEeFlu1x4A)
- [**NeurIPS 2023**] Quilt-1m: One million image-text pairs for histopathology [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/775ec578876fa6812c062644964b9870-Paper-Datasets_and_Benchmarks.pdf) [[code-demo]](https://quilt1m.github.io/)


### 2024
- [**arXiv 2024**] MedPromptX: Grounded Multimodal Prompting for Chest X-ray Diagnosis [[pdf]](https://arxiv.org/pdf/2403.15585.pdf) [[code]](https://github.com/BioMedIA-MBZUAI/MedPromptX)
- [**arXiv 2024**] PeFoMed: Parameter Efficient Fine-tuning on Multimodal Large Language Models for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2401.02797) [[code]](https://github.com/jinlHe/PeFoMed)
- [**ICASSP 2024**] Prompt-based Personalized Federated Learning for Medical Visual Question Answering [[pdf]](https://arxiv.org/pdf/2402.09677)
- [**arXiv 2024**] RJUA-MedDQA: A Multimodal Benchmark for Medical Document Question Answering and Clinical Reasoning [[pdf]](https://arxiv.org/pdf/2402.14840)
- [**arXiv 2024**] Design as Desired: Utilizing Visual Question Answering for Multimodal Pre-training [[pdf]](https://arxiv.org/pdf/2404.00226)

## Medical Vision-Language Model ![](https://img.shields.io/badge/Medical_Vision_Language_Model-blue)

### 2022
- [**EMNLP 2022**] Medclip: Contrastive learning from unpaired medical images and text [[pdf]](https://arxiv.org/pdf/2210.10163.pdf) [[code]](https://github.com/RyanWangZf/MedCLIP)
- [**NeurIPS W 2022**] Adapting Pretrained Vision-Language Foundational Models to Medical Imaging Domains [[pdf]](https://arxiv.org/pdf/2210.04133)
- [**ACL 2022**] ViLMedic: a framework for research at the intersection of vision and language in medical AI [[pdf]](https://aclanthology.org/2022.acl-demo.3.pdf) [[code]](https://github.com/jbdel/vilmedic)
- [**MICCAI 2022**] Multi-modal Masked Autoencoders for Medical Vision-and-Language Pre-training [[pdf]](https://arxiv.org/pdf/2209.07098.pdf) [[code]](https://github.com/zhjohnchan/M3AE)
- [**JBHI 2022**] Multi-Modal Understanding and Generation for Medical Images and Text via Vision-Language Pre-Training [[pdf]](https://arxiv.org/pdf/2105.11333) [[code]](https://github.com/SuperSupermoon/MedViLL)
- [**AAAI 2022**] Clinical-BERT: Vision-Language Pre-training for Radiograph Diagnosis and Reports Generation [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/download/20204/19963)
- [**JBHI 2022**] Vision-language transformer for interpretable pathology visual question answering [[link]](https://ieeexplore.ieee.org/abstract/document/9745795)
- [**arXiv 2022**] RoentGen: Vision-Language Foundation Model for Chest X-ray Generation [[pdf]](https://arxiv.org/pdf/2211.12737)
- [**ECCV 2022**] Making the most of text semantics to improve biomedical vision–language processing [[pdf]](https://arxiv.org/pdf/2204.09817)
- [**MICCAI 2022**] RepsNet: Combining Vision with Language for Automated Medical Reports [[pdf]](https://arxiv.org/pdf/2209.13171) [[code]](https://sites.google.com/view/repsnet)
- [**NeurIPS 2022**] Multi-Granularity Cross-modal Alignment for Generalized Medical Visual Representation Learning [[pdf]](https://arxiv.org/pdf/2210.06044) [[code]](https://github.com/fuying-wang/MGCA)
- [**MICCAI 2022**] Berthop: An effective vision-and-language model for chest x-ray disease diagnosis [[pdf]](https://arxiv.org/pdf/2108.04938)
### 2023
- [**TMI 2023**] LViT: Language meets Vision Transformer in Medical Image Segmentation [[pdf]](https://arxiv.org/pdf/2206.14718) [[code]](https://github.com/HUANGLIZI/LViT)
- [**ICCV 2023**] Towards Unifying Medical Vision-and-Language Pre-training via Soft Prompts [[pdf]](https://arxiv.org/pdf/2302.08958) [[code]](https://github.com/zhjohnchan/PTUnifier)
- [**ICCV 2023**] CLIP-Driven Universal Model for Organ Segmentation and Tumor Detection [[pdf]](https://arxiv.org/pdf/2301.00785.pdf) [[code]](https://github.com/ljwztc/CLIP-Driven-Universal-Model)
- [**arXiv 2023**] Towards General Purpose Medical AI: Continual Learning Medical Foundation Model [[pdf]](https://arxiv.org/pdf/2303.06580.pdf)
- [**arXiv 2023**] Large-Scale Domain-Specific Pretraining for Biomedical Vision-Language Processing [[pdf]](https://arxiv.org/pdf/2303.00915) [[code]](https://aka.ms/biomedclip)
- [**ICLR 2023**] Medical Image Understanding with Pretrained Vision Language Models: A Comprehensive Study [[pdf]](https://openreview.net/pdf?id=txlWziuCE5W) [[code]](https://github.com/MembrLab/MIU-VL)
- [**ICLR 2023**] Advancing Radiograph Representation Learning with Masked Record Modeling [[pdf]](https://arxiv.org/pdf/2301.13155) [[code]](https://github.com/RL4M/MRM-pytorch)
- [**MICCAI 2023**] PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents [[pdf]](https://arxiv.org/pdf/2303.07240)
- [**arXiv 2023**] **ChatCAD: Interactive Computer-Aided Diagnosis on Medical Image using Large Language Models** [[pdf]](https://arxiv.org/pdf/2302.07257)[[code]](https://github.com/zhaozh10/ChatCAD)
- [**ICCV 2023**] MedKLIP: Medical Knowledge Enhanced Language-Image Pre-Training [[pdf]](https://arxiv.org/pdf/2301.02228) [[project]](https://chaoyi-wu.github.io/MedKLIP/)
- [**CVPR 2023**] Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing [[pdf]](https://arxiv.org/pdf/2301.04558)
- [**CVPR W 2023**] One-shot and Partially-Supervised Cell Image Segmentation Using Small Visual Prompt [[pdf]](https://arxiv.org/pdf/2304.07991)
- [**arXiv 2023**] CLIP-Lung: Textual Knowledge-Guided Lung Nodule Malignancy Prediction [[pdf]](https://arxiv.org/pdf/2304.08013.pdf)
- [**MICCAI 2023**] UniSeg: A Prompt-driven Universal Segmentation Model as well as A Strong Representation Learner [[pdf]](https://arxiv.org/abs/2304.03493) [[code]](https://github.com/yeerwen/UniSeg)
- [**ICCV 2023**] UniverSeg: Universal Medical Image Segmentation [[pdf]](https://arxiv.org/pdf/2304.06131) [[project website]](https://universeg.csail.mit.edu/)
- [**arXiv 2023**] Bi-VLGM : Bi-Level Class-Severity-Aware Vision-Language Graph Matching for Text Guided Medical Image Segmentation [[pdf]](https://arxiv.org/pdf/2305.12231)
- [**arXiv 2023**] **ChatCAD+: Towards a Universal and Reliable Interactive CAD using LLMs** [[pdf]](https://arxiv.org/abs/2305.15964)[[code]](https://github.com/zhaozh10/ChatCAD)
- [**arXiv 2023**] **XrayGPT: Chest Radiographs Summarization using Medical Vision-Language Models** [[pdf]](https://arxiv.org/pdf/2306.07971) [[code]](https://github.com/mbzuai-oryx/XrayGPT)
- [**arXiv 2023**] BiomedGPT: A Unified and Generalist Biomedical Generative Pre-trained Transformer for Vision, Language, and Multimodal Tasks [[pdf]](https://arxiv.org/pdf/2305.17100) [[code]](https://github.com/taokz/BiomedGPT)
- [**CHIL 2023**] Multi-modal Pre-training for Medical Vision-language Understanding and Generation: An Empirical Study with A New Benchmark [[pdf]](https://arxiv.org/pdf/2306.06494) [[code]](https://github.com/control-xl/medical-vision-langauge-transformer)
- [**arXiv 2023**] Med-UniC: Unifying Cross-Lingual Medical Vision-Language Pre-Training by Diminishing Bias [[pdf]](https://arxiv.org/pdf/2305.19894)
- [**arXiv 2023**] **OphGLM: Training an Ophthalmology Large Language-and-Vision Assistant based on Instructions and Dialogue** [[pdf]](https://arxiv.org/pdf/2306.12174) [[code]](https://github.com/ML-AILab/OphGLM)
- [**ICML W 2023**] **A ChatGPT Aided Explainable Framework for Zero-Shot Medical Image Diagnosis** [[pdf]](https://arxiv.org/pdf/2307.01981)
- [**MICCAI 2023**] M-FLAG: Medical Vision-Language Pre-training with Frozen Language Models and Latent Space Geometry Optimization [[pdf]](https://arxiv.org/pdf/2307.08347) [[code]](https://github.com/cheliu-computation/m-flag-miccai2023)
- [**arXiv 2023**] **Towards Generalist Biomedical AI** [[pdf]](https://arxiv.org/pdf/2307.14334) [[Med-PaLM]](https://sites.research.google/med-palm/)
- [**MICCAI 2023**] Knowledge Boosting: Rethinking Medical Contrastive Vision-Language Pre-Training [[pdf]](https://arxiv.org/pdf/2307.07246) [[code]](https://github.com/ChenXiaoFei-CS/KoBo)
- [**MICCAI 2023**] Unified Medical Image-Text-Label Contrastive Learning With Continuous Prompt [[pdf]](https://arxiv.org/pdf/2307.05920)
- [**arXiv 2023**] Few-shot medical image classification with simple shape and texture text descriptors using vision-language models [[pdf]](https://arxiv.org/pdf/2308.04005) [[code]](https://github.com/BrainImageAnalysis/FSC-CLIP-GPT)
- [**ICML W 2023**] **Med-Flamingo: a Multimodal Medical Few-shot Learner** [[pdf]](https://arxiv.org/pdf/2307.15189) [[code]](https://github.com/snap-stanford/med-flamingo)
- [**MICCAI 2023**] Ariadne's Thread: Using Text Prompts to Improve Segmentation of Infected Areas from Chest X-ray images [[pdf]](https://arxiv.org/pdf/2307.03942) [[code]](https://github.com/Junelin2333/LanGuideMedSeg-MICCAI2023)
- [**arXiv 2023**] A Foundation LAnguage-Image model of the Retina (FLAIR): Encoding expert knowledge in text supervision [[pdf]](https://arxiv.org/pdf/2308.07898) [[code]](https://github.com/jusiro/flair)
- [**ICCV 2023**] ViLLA: Fine-Grained Vision-Language Representation Learning from Real-World Data [[pdf]](https://arxiv.org/pdf/2308.11194) [[code]](https://github.com/stanfordmimi/villa)
- [**arXiv 2023**] IMITATE: Clinical Prior Guided Hierarchical Vision-Language Pre-training [[pdf]](https://arxiv.org/pdf/2310.07355)
- [**arXiv 2023**] Utilizing Synthetic Data for Medical Vision-Language Pre-training: Bypassing the Need for Real Images [[pdf]](https://arxiv.org/pdf/2310.07027)
- [**arXiv 2023**] **RaDialog: A Large Vision-Language Model for Radiology Report Generation and Conversational Assistance** [[pdf]](https://arxiv.org/pdf/2311.18681) [[code]](https://github.com/ChantalMP/RaDialog)
- [**MICCAI 2023**] CXR-CLIP: Toward Large Scale Chest X-ray Language-Image Pre-training [[pdf]](https://arxiv.org/pdf/2310.13292) [[code]](https://github.com/kakaobrain/cxr-clip)
- [**arXiv 2023**] BiomedJourney: Counterfactual Biomedical Image Generation by Instruction-Learning from Multimodal Patient Journeys [[pdf]](https://arxiv.org/pdf/2310.10765) [[project]](https://microsoft.github.io/BiomedJourney/)
- [**arXiv 2023**] **Qilin-Med-VL: Towards Chinese Large Vision-Language Model for General Healthcare** [[pdf]](https://arxiv.org/pdf/2310.17956) [[code]](https://github.com/williamliujl/Qilin-Med-VL)
- [**NeurIPS 2023 D&B**] **LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day** [[pdf]](https://arxiv.org/pdf/2306.00890) [[code]](https://github.com/microsoft/LLaVA-Med)
- [**arXiv 2023**] **Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data** [[pdf]](https://arxiv.org/pdf/2308.02463) [[code]](https://github.com/chaoyi-wu/RadFM)
- [**arXiv 2023**] Unified Medical Image Pre-training in Language-Guided Common Semantic Space [[pdf]](https://arxiv.org/pdf/2311.14851)
- [**arXiv 2023**] **RO-LLaMA: Generalist LLM for Radiation Oncology via Noise Augmentation and Consistency Regularization** [[pdf]](https://arxiv.org/pdf/2311.15876)
- [**arXiv 2023**] **MedXChat: Bridging CXR Modalities with a Unified Multimodal Large Model** [[pdf]](https://arxiv.org/pdf/2312.02233)
- [**arXiv 2023**] G2D: From Global to Dense Radiography Representation Learning via Vision-Language Pre-training [[pdf]](https://arxiv.org/pdf/2312.01522)
- [**npj digital medicine**] A medical multimodal large language model for future pandemics [[pdf]](https://www.nature.com/articles/s41746-023-00952-2)
- [**arXiv 2023**] **MEDAGENTS: Large Language Models as Collaborators for Zero-shot Medical Reasoning** [[pdf]](https://arxiv.org/pdf/2311.10537) [[code]](https://github.com/gersteinlab/MedAgents)
- [**arXiv 2023**] **A Foundational Multimodal Vision Language AI Assistant for Human Pathology** [[pdf]](https://arxiv.org/pdf/2312.07814)
- [**arXiv 2023**] UniDCP: Unifying Multiple Medical Vision-language Tasks via Dynamic Cross-modal Learnable Prompts [[pdf]](https://arxiv.org/pdf/2312.11171)
- [**arXiv 2023**] ECAMP: Entity-centered Context-aware Medical Vision Language Pre-training [[pdf]](https://arxiv.org/pdf/2312.13316) [[code]](https://github.com/ToniChopp/ECAMP)
### 2024
- [**CVPR 2024**] Quilt-LLaVA: Visual Instruction Tuning by Extracting Localized Narratives from Open-Source Histopathology Videos [[pdf]](https://arxiv.org/pdf/2312.04746.pdf) [[code-demo]](https://quilt-llava.github.io/)
- [**ICASSP 2024**] Freeze the backbones: A Parameter-Efficient Contrastive Approach to Robust Medical Vision-Language Pre-training [[pdf]](https://arxiv.org/pdf/2401.01179)
- [**arXiv 2024**] Vulnerabilities Unveiled: Adversarially Attacking a Multimodal Vision Language Model for Pathology Imaging [[pdf]](https://arxiv.org/pdf/2401.02565)
- [**arXiv 2024**] Masked Contrastive Reconstruction for Cross-modal Medical Image-Report Retrieval [[pdf]](https://arxiv.org/pdf/2312.15840)
- [**arXiv 2024**] CheXagent: Towards a Foundation Model for Chest X-Ray Interpretation [[pdf]](https://arxiv.org/pdf/2401.12208) [[code]](https://github.com/Stanford-AIMI/CheXagent)
- [**CVPR 2024**] OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM [[pdf]](https://arxiv.org/pdf/2402.09181)
- [**CVPR 2024**] Adapting Visual-Language Models for Generalizable Anomaly Detection in Medical Images [[pdf]](https://arxiv.org/pdf/2403.12570) [[code]](https://github.com/MediaBrain-SJTU/MVFA-AD)
- [**ICLR 2024**] **LLM-CXR: Instruction-Finetuned LLM for CXR Image Understanding and Generation** [[pdf]](https://arxiv.org/pdf/2305.11490) [[code]](https://github.com/hyn2028/llm-cxr)
- [**arXiv 2024**] **Enhancing Human-Computer Interaction in Chest X-ray Analysis using Vision and Language Model with Eye Gaze Patterns** [[pdf]](Https://arxiv.org/pdf/2404.02370)
- [**arXiv 2024**] DeViDe: Faceted medical knowledge for improved medical vision-language pre-training [[pdf]](https://arxiv.org/pdf/2404.03618)
- [**arXiv 2024**] **M3D: Advancing 3D Medical Image Analysis with Multi-Modal Large Language Models** [[pdf]](https://arxiv.org/pdf/2404.00578) [[code]](https://github.com/BAAI-DCAI/M3D)
- [**arXiv 2024**] **Dia-LLaMA: Towards Large Language Model-driven CT Report Generation** [[pdf]](https://arxiv.org/pdf/2403.16386)
- [**arXiv 2024**] **WoLF: Wide-scope Large Language Model Framework for CXR Understanding** [[pdf]](https://arxiv.org/pdf/2403.15456)
- [**CVPR 2024**] Decomposing Disease Descriptions for Enhanced Pathology Detection: A Multi-Aspect Vision-Language Pre-training Framework [[pdf]](https://arxiv.org/pdf/2403.07636) [[code]](https://github.com/HieuPhan33/MAVL)
- [**arXiv 2024**] **Large Model driven Radiology Report Generation with Clinical Quality Reinforcement Learning** [[pdf]](https://arxiv.org/pdf/2403.06728)
- [**arXiv 2024**] **MedRG: Medical Report Grounding with Multi-modal Large Language Model** [[pdf]](https://arxiv.org/abs/2303.07618)
- [**CVPR 2024**] Bootstrapping Chest CT Image Understanding by Distilling Knowledge from X-ray Expert Models [[pdf]](https://arxiv.org/pdf/2404.04936) [[code]](https://github.com/HieuPhan33/MAVL)
- [**CVPR 2024**] Continual Self-supervised Learning: Towards Universal Multi-modal Medical Data Representation Learning [[pdf]](https://arxiv.org/pdf/2311.17597) [[code]](https://github.com/yeerwen/MedCoSS)
- [**CVPR 2024**] PairAug: What Can Augmented Image-Text Pairs Do for Radiology? [[pdf]](https://arxiv.org/pdf/2404.04960) [[code]](https://github.com/YtongXie/PairAug)
- [**CVPR 2024**] MLIP: Enhancing Medical Visual Representation with Divergence Encoder and Knowledge-guided Contrastive Learning [[pdf]](https://arxiv.org/pdf/2402.02045)
