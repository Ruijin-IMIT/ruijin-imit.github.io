





![can't show up](./images/example.png)



# PDCADxFoundation
# Challenge overview


# Challenge background


# Challenge tasks
## segmentation
This competition aim to promote the study of Parkinson's Disease, images

**This competition aim to promote the study of Parkinson's Disease, images**

*This competition aim to promote the study of Parkinson's Disease, images*

**This competition aim to promote the study of Parkinson's Disease, images**


~~asdf~~


## PD classification


```python
def hello():
    print("Markdown!")
```

| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:-------:|-------:|
| 单元格 | 单元格  | 单元格 |

> 引用内容  
> 多行引用

---
或 *** （分割线）



- [x] 完成作业
- [ ] 写报告



<details>
<summary>点击展开</summary>
隐藏内容...
</details>



# evaluation codes
## segmentation

## PD classification

---
layout: default \
title: About
---
# About page

This page tells you a little bit about me.


The background color is `#ffffff` for light mode and `#000000` for dark mode.


About Us

Welcome to the Foundation-Model-Driven Parkinson's Disease Auto Diagnosis Challenge (PDCADxFoundation)!  

The PDCADxFoundation Challenge is a part of the 28th International Conference on Medical Image Computing 
and Computer Assisted Intervention, MICCAI 2025, which will be held from October 6th to 10th 2024 in Marrakesh, Morocco.
About Us

Welcome to the Cardiac MRI Reconstruction Challenge 2025 (CMRxRecon2025)!  

The CMRxRecon2025 (Towards Foundation Model) Challenge is a part of the 28th International Conference on Medical Image Computing and Computer Assisted Intervention, MICCAI 2025, which will be held from September 23rd to 27th 2025 in Daejeon, Republic of Korea.

Motivation

The objective of establishing the CMRx series challenges is to provide a benchmark that enables the research community to contribute to the work of accelerated CMR imaging with universal approaches that allow more diverse applications and better performance in real-world deployment in various environments. The previous CMRxRecon2023 and CMRxRecon2024 dataset did not cover multi-center, multi-vendor, and multiple diseases. Therefore, this year we aim to make an important leap towards real-world clinical scenarios.

Background

Cardiac MRI (CMR) has become an essential tool for diagnosing and evaluating cardiovascular diseases, offering multi-parametric, high-resolution anatomical and functional data. CMR reconstruction from highly under-sampled k-space data has gained significant attention in recent research. Numerous AI-based image reconstruction algorithms have shown potential in improving imaging performance and patient experience in recovering high-quality images from aggressively undersampled k-space measurements. However, the complexity and diversity of CMR scans in real-world applications, involving various image contrasts, sampling trajectories, equipment vendors, anatomical structures, and disease types, present a great challenge for existing AI-based reconstruction methods, which are usually developed for only one or a few specific scanning settings. In practice, there are often inevitable distribution mismatches between the training data and target data, due to the diversities listed above. Therefore, building and validating universal and robust reconstruction models for handling these diversities remain to be critical technical challenges for multi-parametric CMR imaging.

CMRxRecon Series 	Modalities 	No. of Centers 	No. of Scanners 	Populations 	Sampling Tratectory 	No. of Subjects
2023 	Cine, Mapping 	1 	1 	Healthy 	2D Uniform 	~300
2024 	Cine, T1 and T2 Mapping, Blackblood, Phase contrast, Tagging. 	1 	1 	Healthy 	2D Uniform, 3D k-t Uniform, 3D k-t Gaussian，3D k-t Radial 	~300
2025 	Cine, T1, T2 and T2* Mapping, T1w, T2w, T1rho, Blackblood, Phase contrast, LGE, Perfusion. 	5+ 	10+ 	Hearthy individuals and patients with hypertrophic cardiomyopathy; dilated cardiomyopathy;myocardial infarction.; coronary artery disease; a rrhythmias, etc. 	2D and 3D k-t Uniform, 2D and 3D k-t Gaussian，2D and 3D k-t Radial 	~600

We aim to make an important leap towards real-world clinical scenarios by extending the challenge scope in two directions:

1) To evaluate the robustness and generalization performance of reconstruction foundation models in more than 5 centers and 10 scanners, all those data are unseen during training stage.

2) To evaluate the clinical performance of reconstruction foundation models under no less than 5 cardiovascular diseases (e.g., hypertrophic cardiomyopathy, dilated cardiomyopathy, myocardial infarction, coronary artery disease, arrhythmias), all those data are unseen during training stage.


# Abstract

The automatic diagnosis of Parkinson's disease (PD) has received significant attention in recent years due to the
high prevalence of PD and the need to improve the accuracy of diagnosis. Clinical diagnosis of Parkinson's disease
(PD) often leverages diagnostic biomarkers in advanced magnetic resonance imaging (MRI). Quantitative
alterations of tissue property in the deep gray matter (DGM) in MRI may indicate pathophysiological changes
related to PD. However, automatic and accurate DGM segmentation faces many challenges, and core brain
structures (i.e., SNpr and SNpe) for PD determination are particularly difficult to delineate. The lack of public
datasets and quality annotations for PD research has been the bottleneck for developing deep learning models of
clinical significance. The Ruijin Imaging Neuroscience Group has curated a multi-parametric MRI dataset for PD
research with comprehensive annotations. In this challenge, we will provide a large dataset containing 500
subjects with 3 MR modalities (T1WI, QSM, NM-MRI) and bilateral DGM (CN, PUT, GP, STN, SN, RN, and DN) mask
annotations. The challenge participants will compete in the DGM segmentation and PD diagnosis tasks. Publicly
accessible foundation models and domain adaption techniques should be utilized to tackle the challenging PD
diagnosis tasks while facing limitations in data scale and annotation. Specifically, two competition tracks are
designed: (1) maximize the accuracy of the DGM segmentation using released data and public foundation models
(2) maximize the accuracy of PD classification using released data and public foundation models.



# Tasks
## Task 1: PD-related anatomy segmentation

## Task 2: PD classification



# Data
## Data overview


No additional data allowed

Monetary awards for top-3 winners for both tracks.
The winners will be invited to submit their groundbreaking solutions (as coauthors) in a summarization paper.
Student participants in the winning teams will be considered for admission and scholarship in organizers'
institutes.

Algorithm output should be sent to organizers via e-mail. Submission instructions will be on the organizer’s
website.

Using the dataset (200 cases in total of the training data), participants will develop model adaptation approaches
using foundation models for the PD tasks. The participants should submit model predictions on the validation set
several times before submitting the final results of testing predictions. At most 2 submissions of prediction results
on the testing set are allowed. See detailed rules on the organizer's website.

This study was approved by the institutional ethics committee in Ruijin Hospital, Shanghai Jiao Tong University
School of Medicine (No.RJ2022-279). All participants provided written informed consent.

Participants could submit their results of the validation set (100 cases of the validation data with labels held
hidden before the final evaluation phase) to the server during the validation phase (3-5 submissions are allowed).
Once the validation phase ends, the organizers will release the labels for the validation set.


Annotation for the deep brain nuclei structures: One neuroradiologist manually segmented the CN, GP, PUT, SN,
RN, and DN in the bilateral hemisphere. Another radiologist with 5 years of experience in neuroimaging double-checked all the structural boundaries. Finally, those ROIs approved by these two radiologists will serve as
the ground truth for the segmentation model.
Annotation for the SN, STN structures: The ROIs for the NM-rich region (SNpc, SN) were manually traced by a
single rater on MTC magnitude images and QSM maps using SPIN software (SpinTech, Inc., Bingham Farms, MI).
The NM-based SN boundaries were traced from the last caudal slice for three to five slices until the NM-rich
region was no longer visible. Simultaneously, the iron-based SN boundaries were traced starting from one slice
below the most cranial slice where the STN was visible and continued for four to six consecutive slices to the most
caudal slice. The STN ROIs were traced from the top of the RN for two slices cranially. For all the ROIs, a dynamic
programming approach (DPA) was used to determine the final boundaries to alleviate the subjective bias. All
these boundaries were then reviewed by a second rater and modified accordingly in consensus with the first
rater.



# Evaluation metrics
Accuracy,Sensitivity,Specificity,Consistency,Precision



Sample image and annotation masks for DGM segmentation. The spatial variations of DGM structures are shown
in different slices of the T1WI MRI and QSM MRI respectively. The enlarged 3D mask on the top right corner
demonstrates the volume differences among DGM structures. Each DGM structure has the left and right regions,
colored separately.
Sample image and annotation masks for SNpc segmentation. The substantia nigra structure is partially seen in
QSM MRI, partially seen in NM MRI, and the intersection area is the SNpc region.

The Ruijin-PD dataset includes 500 multi-parametric MRI cases (50% each for PD positives and healthy controls)
with more than 105,000 images in total. Each case contains the T1WI, QSM, and NM-MRI images, with
segmentation masks on 7 PD-related anatomical structures. The PD classification label is also included. The
images for training (200 cases, with labels) and validation (100 cases, without labels) will be freely available at the
competition start date, while the testing images (200 cases) will be available at the test stage (together with the
labels for the validation set). The label for the test set will not be released. All the data and ground truth have not
been previously published and have been kept confidential.


The data splitting is based on the cross-validation principle, for maximum randomness and reliability. The split
proportion ensures adequate training samples and meaningful testing scores.



















## Data Download

> Baidu Net-disk
> 
> Google Drive
> 
> 
> 
> 
> Synapse


# Bonus
We will summarize the challenge results and submit a paper to IEEE TMI or Medical Image Analysis.







# Timeline
>[Apr. 1, 2025] Website opens for registration\
[Apr. 1, 2025] Release training images & ground truth\
[May 1, 2025] Release validation images\
[May 1, 2025] Submission system opens for validation\
[June 15, 2025] Release validation ground truth\
[June 15, 2025] Release testing images\
[June 15, 2025] Submission system opens for testing\
[Aug. 15, 2025] Testing submission deadline (codes, results, technical reports)\
[Sep. 1, 2025] Release final results of challenge\
[Sep. 10, 2025] Challenge paper submission deadline\
[Sep. 27, 2025] Top-ranking teams report during the MICCAI annual meeting\



# Contact
> PDCADxFoundation@outlook.com\
> Fakai Wang (Shanghai Jiao Tong University), fakaiwang@sjtu.edu.cn

