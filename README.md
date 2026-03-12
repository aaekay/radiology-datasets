# Awesome Radiology Datasets

[![GitHub stars](https://img.shields.io/github/stars/aaekay/radiology-datasets?style=social)](https://github.com/aaekay/radiology-datasets/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/aaekay/radiology-datasets)](https://github.com/aaekay/radiology-datasets/issues)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](https://github.com/aaekay/radiology-datasets/issues)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A comprehensive, curated list of publicly available radiology datasets for AI and machine learning research. Organized by imaging modality with metadata on dataset size, image format, and available open-source models.

---

## Table of Contents

- [Chest X-rays](#chest-x-rays)
- [Musculoskeletal & Bone X-rays](#musculoskeletal--bone-x-rays)
- [Dental X-rays](#dental-x-rays)
- [Spine X-rays](#spine-x-rays)
- [Pediatric X-rays](#pediatric-x-rays)
- [CT Scans](#ct-scans)
- [MRI](#mri)
- [Ultrasound](#ultrasound)
- [Mammography](#mammography)
- [PET / Nuclear Medicine](#pet--nuclear-medicine)
- [ML Challenge Datasets](#ml-challenge-datasets)
- [Open-Source Radiology Models](#open-source-radiology-models)
- [Major Data Repositories](#major-data-repositories)
- [Contributing](#contributing)

---

## Chest X-rays

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [REVEAL-CXR](https://imaging.rsna.org) | 2026 | 13,735 chest radiographs, 12 benchmark findings | DICOM | — |
| [ReXGradient-160K](https://huggingface.co/datasets/rajpurkarlab/ReXGradient-160K) | 2025 | 160,000 studies, 273,004 images, 109,487 patients | PNG | — |
| [CheXpert Plus](https://aimi.stanford.edu/datasets/chexpert-plus) | 2024 | 223,462 image-report pairs, 64,725 patients | DICOM | [CheXagent](https://github.com/Stanford-AIMI/CheXagent) |
| [VinDr-CXR](https://physionet.org/content/vindr-cxr/1.0.0/) | 2021 | 18,000 images | DICOM | — |
| [COVID-19 Image Data Collection](https://github.com/ieee8023/covid-chestxray-dataset) | 2020 | 1,000+ images | PNG, JPG | — |
| [PadChest](http://bimcv.cipf.es/bimcv-projects/padchest/) | 2020 | 160,000+ images, 67,000 patients | DICOM | — |
| [SIIM-ACR Pneumothorax](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation) | 2019 | 12,047 images | DICOM | — |
| [MIMIC-CXR](https://physionet.org/content/mimic-cxr) | 2019 | 377,110 images, 65,379 patients | DICOM, JPG | [CheXagent](https://github.com/Stanford-AIMI/CheXagent), [LLaVA-Rad](https://huggingface.co/microsoft/llava-rad) |
| [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/) | 2019 | 224,316 images, 65,240 patients | PNG | [CheXagent](https://github.com/Stanford-AIMI/CheXagent), [NV-Reason-CXR](https://github.com/NVIDIA/NV-Reason-CXR) |
| [RSNA Pneumonia Detection](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge) | 2018 | 30,000 images | DICOM | — |
| [NIH ChestX-ray14](https://nihcc.app.box.com/v/ChestXray-NIHCC) | 2017 | 112,120 images, 30,805 patients | PNG | [CheXNet](https://stanfordmlgroup.github.io/projects/chexnet/) |
| [Indiana University CXR](https://openi.nlm.nih.gov/) | 2016 | 8,121 images, 3,996 reports | PNG, DICOM | — |
| [Shenzhen TB CXR](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#702702tuberculosis-image-data-sets) | 2014 | 662 images | PNG | — |
| [Montgomery County TB CXR](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#702702tuberculosis-image-data-sets) | 2014 | 138 images | PNG | — |
| [JSRT](http://db.jsrt.or.jp/eng.php) | 2009 | 247 images | PNG | — |

## Musculoskeletal & Bone X-rays

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [Emory Knee Radiograph (MRKR)](https://docs.ngsci.org/datasets/mrkr-emory-xray/) | 2024 | 503,261 knee radiographs, 83,011 patients | DICOM | — |
| [Bone Fracture X-ray (Simple vs. Comminuted)](https://data.mendeley.com/datasets/vg95gvhj3y/3) | 2024 | 16,061 images (2,384 original + augmented) | PNG | — |
| [FracAtlas](https://figshare.com/articles/dataset/The_dataset/22363012) | 2023 | 4,083 images, 922 fracture instances | PNG | — |
| [Osteoarthritis Initiative (OAI)](https://nda.nih.gov/oai/) | 2019 | 4,796 participants, bilateral knee X-rays + MRI | DICOM | — |
| [MURA](https://stanfordmlgroup.github.io/competitions/mura/) | 2018 | 40,561 images, 14,863 studies (upper extremity) | PNG | — |
| [RSNA Bone Age](https://www.kaggle.com/datasets/kmader/rsna-bone-age) | 2017 | 14,236 hand/wrist X-rays | PNG | — |

## Dental X-rays

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [Panoramic Dental X-ray](https://data.mendeley.com/datasets/73n3kz2k4k/3) | 2025 | 221 panoramic radiographs | PNG | — |
| [Multi-center Dental Panoramic](https://link.springer.com/article/10.1007/s10278-024-00972-8) | 2024 | 6,536 images, 3 hospitals | PNG | — |
| [DENTEX](https://huggingface.co/datasets/ibrahimhamamci/DENTEX) | 2023 | 3,903 panoramic X-rays, 4 pathology classes | PNG | — |
| [OdontoAI](https://github.com/IvisionLab/OdontoAI-Open-Panoramic-Radiographs) | 2022 | 1,000 panoramic radiographs | PNG | — |

## Spine X-rays

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [Spinal-AI2024](https://github.com/ernestchenchen/spinal-ai2024) | 2024 | 20,000 scoliosis X-ray images | PNG | — |
| [Scoliosis1K](https://zhouzi180.github.io/Scoliosis1K/) | 2024 | 1,493 video sequences, 1,050 subjects | Video | — |
| [VinDr-SpineXR](https://physionet.org/content/vindr-spinexr/) | 2021 | 10,469 images, 5,000 studies | DICOM | — |
| [Vertebrae X-ray (Scoliosis/Spondylolisthesis)](https://data.mendeley.com/datasets/xkt857dsxk/1) | 2022 | 338 subjects | PNG | — |

## Pediatric X-rays

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [PediaSHF-DX](https://www.nature.com/articles/s41597-026-07029-1) | 2026 | 10,325 elbow X-rays, 5,163 patients | PNG | — |
| [Pediatric Ulna & Radius Fractures (PediURF)](https://www.nature.com/articles/s41597-026-06666-w) | 2026 | 10,000+ pediatric forearm X-rays | PNG | — |
| [VinDr-PCXR](https://physionet.org/content/vindr-pcxr/1.0.0/) | 2022 | 9,125 pediatric chest X-rays | DICOM | — |
| [GRAZPEDWRI-DX](https://figshare.com/articles/dataset/GRAZPEDWRI-DX/14825193) | 2022 | 20,327 pediatric wrist X-rays, 6,091 patients | PNG | — |

## CT Scans

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [CADS](https://huggingface.co/datasets/mrmrx/CADS-dataset) | 2025 | 22,022 CT scans, 167 structures | NIfTI | [CADS](https://github.com/murong-xu/cads) |
| [CT-RATE](https://huggingface.co/datasets/ibrahimhamamci/CT-RATE) | 2025 | 25,692 3D chest CTs, 21,304 patients | NIfTI | [CT-CLIP](https://github.com/ibrahimethemhamamci/CT-CLIP) |
| [NLSTseg](https://portal.imaging.datacommons.cancer.gov/explore/filters/?analysis_results_id=NLSTSeg) | 2025 | 605 patients, 715 lung lesions | NIfTI | — |
| [RSNA Intracranial Aneurysm Detection](https://www.kaggle.com/competitions/rsna-2025-intracranial-aneurysm-detection) | 2025 | TBD (active challenge) | DICOM | — |
| [RSNA Lumbar Spine Degenerative](https://www.kaggle.com/competitions/rsna-2024-lumbar-spine-degenerative-classification) | 2024 | ~2,000 studies | DICOM | — |
| [RSNA Abdominal Trauma Detection](https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection) | 2023 | 4,711 studies | DICOM | — |
| [KiTS23](https://kits-challenge.org/kits23/) | 2023 | 599 CT scans | NIfTI | [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) |
| [TotalSegmentator](https://zenodo.org/records/10047292) | 2022 | 1,228 CT scans, 117 structures | NIfTI | [TotalSegmentator](https://github.com/wasserth/TotalSegmentator) |
| [RSNA Cervical Spine Fracture](https://www.kaggle.com/competitions/rsna-2022-cervical-spine-fracture-detection) | 2022 | ~2,000 studies | DICOM | — |
| [AMOS](https://zenodo.org/records/7155725) | 2022 | 500 CTs + 100 MRIs, 15 organs | NIfTI | [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) |
| [AbdomenCT-1K](https://github.com/JunMa11/AbdomenCT-1K) | 2021 | 1,112 CT scans, 4 organs | NIfTI | — |
| [KiTS21](https://github.com/neheller/kits21) | 2021 | 300 CT scans | NIfTI | — |
| [COVID-CT](https://github.com/UCSD-AI4H/COVID-CT) | 2020 | 349 CT images | PNG | — |
| [RSNA Intracranial Hemorrhage](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection) | 2019 | 874,035 images | DICOM | — |
| [CT-ORG](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=61080890) | 2019 | 140 CT scans, 6 organs | NIfTI | — |
| [Medical Segmentation Decathlon](https://medicaldecathlon.com/) | 2019 | 2,633 3D volumes, 10 tasks | NIfTI | [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) |
| [DeepLesion](https://nihcc.app.box.com/v/DeepLesion) | 2018 | 32,735 lesions, 4,427 patients | PNG (16-bit) | — |
| [LiTS](https://competitions.codalab.org/competitions/17094) | 2017 | 201 CT scans | NIfTI | — |
| [LUNA16](https://luna16.grand-challenge.org/) | 2016 | 888 CT scans, 1,186 nodules | MHD/RAW | — |
| [LIDC-IDRI](https://www.cancerimagingarchive.net/collection/lidc-idri/) | 2011 | 1,018 CT scans | DICOM | — |
| [NLST](https://cdas.cancer.gov/nlst/) | 2011 | 75,000+ CT scans, 26,722 participants | DICOM | — |

## MRI

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [BRISC](https://www.kaggle.com/datasets/briscdataset/brisc2025/) | 2026 | 6,000 brain tumor MRIs (glioma, meningioma, pituitary) | NIfTI | — |
| [BraTS-MEN-RT](https://www.synapse.org/brats) | 2026 | 570 meningioma radiotherapy MRIs, 7 centers | NIfTI | — |
| [BraTS 2025](https://zenodo.org/records/15094823) | 2025 | 1,778 cases (pre- and post-treatment) | NIfTI | [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) |
| [CMRxRecon2025](https://www.synapse.org/Synapse:syn64952554) | 2025 | Multi-center cardiac MRI, 5+ centers, 10+ scanners | k-space, DICOM | — |
| [BraTS 2024](https://www.synapse.org/brats) | 2024 | 2,728 cases (GLI + MEN-RT + PED) | NIfTI | [nnU-Net](https://github.com/MIC-DKFZ/nnUNet), [SwinUNETR](https://github.com/Project-MONAI/research-contributions) |
| [fastMRI Prostate](https://fastmri.med.nyu.edu/) | 2024 | 312 exams, 47,468 slices | DICOM, k-space | — |
| [BraTS 2023](https://www.synapse.org/brats) | 2023 | 4,500+ cases (multi-tumor) | NIfTI | [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) |
| [M&Ms](https://www.ub.edu/mnms/) | 2020 | 375 subjects, 4 vendors | NIfTI | — |
| [OASIS-3](https://www.oasis-brains.org/) | 2019 | 1,378 subjects, 2,842 MR sessions | NIfTI, DICOM | — |
| [fastMRI Brain](https://fastmri.med.nyu.edu/) | 2018 | 6,970 brain MRIs | DICOM, k-space | — |
| [fastMRI Knee](https://fastmri.med.nyu.edu/) | 2018 | 1,500+ fully sampled + 10,000 clinical | DICOM, k-space | — |
| [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/) | 2017 | 2,156 subjects, 1,112 ASD | NIfTI | — |
| [ProstateX](https://www.cancerimagingarchive.net/collection/prostatex/) | 2017 | 346 subjects, 16.67 GB | DICOM, MHD | — |
| [ACDC](https://www.creatis.insa-lyon.fr/Challenge/acdc/) | 2017 | 150 patients, cardiac cine-MRI | NIfTI | — |
| [HCP](https://www.humanconnectome.org/study/hcp-young-adult) | 2017 | 1,200 subjects | NIfTI | — |
| [IXI](https://brain-development.org/ixi-dataset/) | 2015 | 600 subjects, 3 hospitals | NIfTI | — |
| [ADNI](https://adni.loni.usc.edu/) | 2004 | 2,000+ subjects (longitudinal) | DICOM, NIfTI | — |

## Ultrasound

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [FETUS 2026](http://119.29.231.17:90/data.html) | 2026 | 5,000 fetal echocardiography scans, 14 structures | DICOM | — |
| [TN5000](https://www.nature.com/articles/s41597-025-05757-4) | 2025 | 5,000 thyroid nodule images | PNG | — |
| [FOCUS](https://zenodo.org/records/14597550) | 2025 | 300 fetal cardiac images | PNG | — |
| [Annotated Heterogeneous US Database](https://www.nature.com/articles/s41597-025-04464-4) | 2025 | 1,833 images, 13 anomaly types | PNG | — |
| [Thyroid Ultrasound Cine-clip](https://aimi.stanford.edu/datasets/thyroid-ultrasound-cine-clip) | 2023 | 167 patients, 192 nodules | DICOM | — |
| [EchoNet-Dynamic](https://echonet.github.io/dynamic/) | 2020 | 10,030 echocardiogram videos | AVI | [EchoNet](https://github.com/echonet/dynamic) |
| [BUSI](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset) | 2020 | 780 images (normal, benign, malignant) | PNG | — |
| [HC18](https://hc18.grand-challenge.org/) | 2018 | 1,334 fetal head images | PNG | — |
| [CLUST](https://clust.ethz.ch/) | 2015 | 85 2D + 24 3D liver US sequences | Various | — |

## Mammography

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [DBT-2026](https://www.cancerimagingarchive.net/collection/breast-cancer-screening-dbt/) | 2026 | 558 digital breast tomosynthesis exams with biopsies | DICOM | — |
| [NL-Breast-Screening](https://www.nature.com/articles/s41597-025-05866-0) | 2025 | 5,997 mammography exams, 4 views each | DICOM | — |
| [Mammo-Bench](https://www.medrxiv.org/content/10.1101/2025.01.31.25321510v1) | 2025 | 74,436 images, 26,500 patients | Multi-format | — |
| [M-SYNTH](https://www.fda.gov/medical-devices/science-and-research-medical-devices/m-synth-dataset-comparative-evaluation-mammography-ai) | 2024 | 45,000 synthetic mammograms | DICOM | — |
| [RSNA Screening Mammography](https://www.kaggle.com/competitions/rsna-breast-cancer-detection) | 2023 | ~20,000 studies | DICOM | — |
| [VinDr-Mammo](https://physionet.org/content/vindr-mammo/) | 2022 | 5,000 exams, 20,000 images | DICOM | — |
| [CBIS-DDSM](https://www.cancerimagingarchive.net/collection/cbis-ddsm/) | 2017 | 1,566 subjects, 163 GB | DICOM | — |
| [INbreast](https://www.kaggle.com/datasets/ramanathansp20/inbreast-dataset) | 2012 | 115 cases, 410 images | DICOM | — |
| [DDSM](http://www.eng.usf.edu/cvprg/Mammography/Database.html) | 1999 | 2,620 cases | LJPEG | — |

## PET / Nuclear Medicine

| Dataset | Year | Size | Format | Open-Source Models |
|---------|------|------|--------|--------------------|
| [PSMA-PET-CT-Lesions](https://www.cancerimagingarchive.net/collection/psma-pet-ct-lesions/) | 2026 | 597 PSMA-PET/CT studies, 378 prostate cancer patients | DICOM | — |
| [ENHANCE.PET](https://registry.opendata.aws/enhance-pet-1-6k/) | 2025 | 1,597 PET/CT images, 130 structures, ~250 GB | NIfTI | — |
| [AutoPET III](https://autopet-iv.grand-challenge.org/) | 2024 | 1,014 FDG + 597 PSMA studies | DICOM, NIfTI | [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) |
| [FDG-PET-CT-Lesions](https://www.cancerimagingarchive.net/collection/fdg-pet-ct-lesions/) | 2022 | 1,014 whole-body studies, 418 GB | DICOM | — |
| [HECKTOR](https://hecktor.grand-challenge.org/) | 2022 | 883 PET/CT studies, head & neck | NIfTI | — |

---

## ML Challenge Datasets

Radiology-specific machine learning challenges that provide curated, expert-annotated datasets.

| Challenge | Year(s) | Modality | Task | Platform |
|-----------|---------|----------|------|----------|
| [CXR-LT 2026](https://arxiv.org/abs/2602.22092) | 2026 | Chest X-ray | Long-Tailed & Zero-Shot Classification | Grand Challenge |
| [FETUS 2026](http://119.29.231.17:90/data.html) | 2026 | Ultrasound | Fetal Echocardiography Segmentation | MICCAI |
| [BraTS 2025](https://zenodo.org/records/15094823) | 2012–2025 | MRI | Brain Tumor Segmentation | Synapse / Zenodo |
| [RSNA Intracranial Aneurysm Detection](https://www.kaggle.com/competitions/rsna-2025-intracranial-aneurysm-detection) | 2025 | CTA, MRA, MRI | Detection & Localization | Kaggle |
| [CMRxRecon2025](https://www.synapse.org/Synapse:syn64952554) | 2025 | Cardiac MRI | MRI Reconstruction | Synapse |
| [RSNA Lumbar Spine Degenerative](https://www.kaggle.com/competitions/rsna-2024-lumbar-spine-degenerative-classification) | 2024 | MRI | Classification | Kaggle |
| [AutoPET](https://autopet.org/) | 2022–2024 | PET/CT | Lesion Segmentation | Grand Challenge |
| [RSNA Abdominal Trauma Detection](https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection) | 2023 | CT | Injury Detection | Kaggle |
| [RSNA Screening Mammography](https://www.kaggle.com/competitions/rsna-breast-cancer-detection) | 2023 | Mammography | Breast Cancer Detection | Kaggle |
| [KiTS](https://kits-challenge.org/kits23/) | 2019–2023 | CT | Kidney Tumor Segmentation | Grand Challenge |
| [AMOS](https://amos22.grand-challenge.org/) | 2022 | CT, MRI | Multi-Organ Segmentation | Grand Challenge |
| [RSNA Cervical Spine Fracture](https://www.kaggle.com/competitions/rsna-2022-cervical-spine-fracture-detection) | 2022 | CT | Fracture Detection | Kaggle |
| [TotalSegmentator](https://totalsegmentator.com/) | 2022 | CT | 117-Structure Segmentation | Zenodo |
| [HECKTOR](https://hecktor.grand-challenge.org/) | 2020–2022 | PET/CT | Head & Neck Tumor Segmentation | Grand Challenge |
| [RSNA Intracranial Hemorrhage](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection) | 2019 | CT | Hemorrhage Classification | Kaggle |
| [RSNA Pulmonary Embolism](https://www.kaggle.com/c/rsna-str-pulmonary-embolism-detection) | 2020 | CT | PE Detection | Kaggle |
| [Medical Segmentation Decathlon](https://medicaldecathlon.com/) | 2019 | CT, MRI | 10 Multi-Organ Tasks | Grand Challenge |
| [SIIM-ACR Pneumothorax](https://www.kaggle.com/c/siim-acr-pneumothorax-segmentation) | 2019 | X-ray | Pneumothorax Segmentation | Kaggle |
| [RSNA Pneumonia Detection](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge) | 2018 | X-ray | Pneumonia Detection | Kaggle |
| [LiTS](https://competitions.codalab.org/competitions/17094) | 2017 | CT | Liver Tumor Segmentation | CodaLab |
| [LUNA16](https://luna16.grand-challenge.org/) | 2016 | CT | Lung Nodule Detection | Grand Challenge |
| [RSNA Bone Age](https://www.kaggle.com/datasets/kmader/rsna-bone-age) | 2017 | X-ray (Hand/Wrist) | Bone Age Assessment | Kaggle |
| [DENTEX](https://huggingface.co/datasets/ibrahimhamamci/DENTEX) | 2023 | Dental X-ray | Tooth Pathology Detection | HuggingFace |
| [FracAtlas](https://figshare.com/articles/dataset/The_dataset/22363012) | 2023 | MSK X-ray | Fracture Classification & Segmentation | Figshare |

---

## Open-Source Radiology Models

Notable open-source models trained on public radiology datasets.

| Model | Training Data | Modality | Task | Link |
|-------|--------------|----------|------|------|
| [CheXagent](https://github.com/Stanford-AIMI/CheXagent) | CheXpert, MIMIC-CXR | Chest X-ray | Multi-task VLM (classification, report generation) | [HuggingFace](https://huggingface.co/StanfordAIMI/CheXagent-2-3b) |
| [LLaVA-Rad](https://huggingface.co/microsoft/llava-rad) | 697K radiology image-text pairs | Chest X-ray | Report Generation | [Paper](https://www.nature.com/articles/s41467-025-58344-x) |
| [NV-Reason-CXR](https://github.com/NVIDIA/NV-Reason-CXR) | MIMIC-CXR, CheXpert | Chest X-ray | Chain-of-Thought VLM | [HuggingFace](https://huggingface.co/nvidia/NV-Reason-CXR-3B) |
| [CheXNet](https://stanfordmlgroup.github.io/projects/chexnet/) | NIH ChestX-ray14 | Chest X-ray | Disease Classification (DenseNet-121) | [Reproductions](https://github.com/zoogzog/chexnet) |
| [CADS](https://github.com/murong-xu/cads) | 22,022 CT scans | CT | 167-Structure Segmentation | [3D Slicer Plugin](https://github.com/murong-xu/SlicerCADSWholeBodyCTSeg) |
| [CT-CLIP](https://github.com/ibrahimethemhamamci/CT-CLIP) | CT-RATE (25,692 3D chest CTs) | CT | 3D CT Zero-Shot Classification | [HuggingFace](https://huggingface.co/datasets/ibrahimhamamci/CT-RATE) |
| [TotalSegmentator](https://github.com/wasserth/TotalSegmentator) | TotalSegmentator Dataset | CT | 117-Structure Segmentation | [PyPI](https://pypi.org/project/TotalSegmentator/) |
| [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) | Multiple (MSD, KiTS, BraTS, etc.) | CT, MRI | Self-configuring Segmentation | [Paper](https://www.nature.com/articles/s41592-020-01008-z) |
| [MedSAM](https://github.com/bowang-lab/MedSAM) | 1.57M image-mask pairs, 10 modalities | Multi-modal | Universal Segmentation | [Paper](https://www.nature.com/articles/s41467-024-44824-z) |
| [MedSAM2](https://github.com/MedSAM2/MedSAM2) | 455K 3D pairs + 76K video frames | Multi-modal | 3D & Video Segmentation | [Project](https://medsam2.github.io/) |
| [SwinUNETR](https://github.com/Project-MONAI/research-contributions) | BraTS, BTCV | MRI, CT | 3D Segmentation | [MONAI](https://monai.io/) |
| [EchoNet](https://github.com/echonet/dynamic) | EchoNet-Dynamic | Echocardiography | Cardiac Function Assessment | [Paper](https://www.nature.com/articles/s41586-020-2145-8) |

---

## Major Data Repositories

Umbrella platforms hosting multiple radiology datasets.

| Repository | Description | Link |
|------------|-------------|------|
| **The Cancer Imaging Archive (TCIA)** | Largest public archive of cancer-specific medical images with DICOM data | [cancerimagingarchive.net](https://www.cancerimagingarchive.net/) |
| **PhysioNet** | Open-access clinical research data including MIMIC-CXR and VinDr datasets | [physionet.org](https://physionet.org/) |
| **OpenNeuro** | 1,240+ neuroimaging datasets (MRI, PET, EEG) with 51,000+ participants | [openneuro.org](https://openneuro.org/) |
| **MIDRC** | NIH-funded repository with 500,000+ imaging studies including COVID-19 data | [midrc.org](https://www.midrc.org/) |
| **NCI Imaging Data Commons** | Cloud-based repository of NCI cancer imaging data on Google Cloud | [portal.imaging.datacommons.cancer.gov](https://portal.imaging.datacommons.cancer.gov/) |
| **Kaggle Datasets** | Community-contributed medical imaging datasets and competitions | [kaggle.com/datasets](https://www.kaggle.com/datasets?tags=14102-Medical+Imaging) |
| **Zenodo** | Open-access repository hosting datasets like TotalSegmentator and AMOS | [zenodo.org](https://zenodo.org/) |
| **AWS Open Data Registry** | 13+ radiology datasets available on AWS infrastructure | [registry.opendata.aws](https://registry.opendata.aws/tag/radiology/) |
| **Grand Challenge** | Platform hosting medical imaging challenges and benchmark datasets | [grand-challenge.org](https://grand-challenge.org/) |

---

## Contributing

If you know of a public radiology dataset that is not listed here, we would love to include it!

### How to Contribute

1. **Star this repo** to help others find it
2. **Open an issue** with the following details:
   - Dataset name
   - Public access link
   - Imaging modality (X-ray, CT, MRI, Ultrasound, Mammography, PET, etc.)
   - Number of images or subjects
   - Image format (DICOM, NIfTI, PNG, etc.)
   - Release year
   - Any known open-source models trained on it
3. **Submit a pull request** if you want to add entries directly

### Issue Template

```
**Dataset Name:** [Name]
**Link:** [URL]
**Modality:** [X-ray / CT / MRI / Ultrasound / Mammography / PET / Other]
**Size:** [Number of images/subjects]
**Format:** [DICOM / NIfTI / PNG / JPG / Other]
**Year:** [Release year]
**Open-Source Models:** [Links or N/A]
**Notes:** [Any additional information]
```

---

If you find this resource useful, please consider giving it a star! It helps the community discover and use these datasets for advancing radiology AI research.

[![Star this repo](https://img.shields.io/github/stars/aaekay/radiology-datasets?style=for-the-badge&logo=github)](https://github.com/aaekay/radiology-datasets/stargazers)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=aaekay/radiology-datasets&type=Date)](https://star-history.com/#aaekay/radiology-datasets&Date)
