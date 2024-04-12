# 3D-segmentation
Collection of latest open source models on 3D segmentation

# Repository Name: Papers on [Segmentation]

This repository contains a curated list of papers related to [3D Segmentation], including direct links to the papers, authors, and a brief summary of each paper's contributions. The papers are organized by themes/topics/year/publication venue as applicable.

## Table of Contents
- [CT Segmentation Papers](#theme1)
- [CT Segmentation Datasets](#theme2)
- [CT Segmentation Disease/Tumours](#theme3)
- [How to Contribute](#how-to-contribute)

---

## <a name="theme1"></a>CT Segmentation Papers

### Fully Automated, Semantic Segmentation of Whole-Body 18F-FDG PET/CT Images Based on Data-Centric Artificial Intelligence
- **Authors:** Lalith Kumar Shiyam Sundar et al.
- **Link:** [Paper](https://jnm.snmjournals.org/content/63/12/1941) [Code](https://github.com/ENHANCE-PET/MOOSE)
- **Summary:** Publicly available segmenting upto 120 structures using nn-unet framework

### Softmax for Arbitrary Label Trees (SALT)
- **Authors:** University Medicine Essen
- **Link:** [Paper](https://github.com/UMEssen/SALT)
- **Summary:** Segmentation upto 145 anatomical structures from CT Imaages. 

## <a name="theme2"></a>CT Segmentation Dataset

## Head and Neck Organ At Risk CT & MR Segmentation Challenge (HaN-Seg)
- **Authors:** Gašper Podobnik, Primož Strojan, Primož Peterlin, Bulat Ibragimov, Tomaž Vrtovec
- **Link:** [Paper](https://aapm.onlinelibrary.wiley.com/doi/full/10.1002/mp.16197) [Dataset](https://han-seg2023.grand-challenge.org/)
- **Summary:** 30 Structures Labels of 42 cases available.
- **Category:** Head and Neck

### StructSeg 2019 
- **Authors:** 
- **Link:** [Challenge](https://structseg2019.grand-challenge.org/)
- **Summary:** 22 Organs from 50 Head and Neck CT. 6 Organs from 50 Chest CT. In addition, lung and nasopharynx cancer annotated.
- **Category:** Head and Neck and Chest

### SegRap2023: A Benchmark of Organs-at-Risk and Gross Tumor Volume Segmentation for Radiotherapy Planning of Nasopharyngeal Carcinoma
- **Authors:** Luo, Xiangde et al. 
- **Link:** [Paper](https://arxiv.org/abs/2312.09576) [Dataset](https://segrap2023.grand-challenge.org/dataset/)
- **Summary:** 54 Structures Labels of 120 cases available.
- **Category:** Head and Neck

### Body Maps: Towards 3D Atlas of Human Body
- **Authors:** Li, Wenxuan et al.
- **Link:** [Challenge](https://codalab.lisn.upsaclay.fr/competitions/16919) [Github](https://github.com/johnson111788/BodyMaps) [Dataset](https://zenodo.org/records/10687640)
- **Summary:** 10142 CT Volumes with 25 antaomical structures voxel level annotations. W-1K is proprietary dataset of 1000 CT-volumes reserved for testing having 15 anatomical structures labels. 
- **Category:** Abdomen

### AMOS: A Large-Scale Abdominal Multi-Organ Benchmark for Versatile Medical Image Segmentation
- **Authors:** Ji et al. 
- **Link:** [Challenge](https://amos22.grand-challenge.org/) [Dataset](https://zenodo.org/records/7155725#.Y0OOCOxBztM)
- **Summary:** 15 Organs masks available for 300 cases.
- **Category:** Abdomen

## MICCAI FLARE 2023
- **Authors:** 
- **Link:** [Challenge](https://codalab.lisn.upsaclay.fr/competitions/12239)
- **Summary:** 2200 Labelled data and 1800 unlabelled CTs. 
- **Category:** Abdomen
  
### Medical Segmentation Decathlon (MSD)
- **Authors:** 
- **Link:** [Challenge](https://decathlon-10.grand-challenge.org/)
- **Summary:** Segmentation available for Hepatic Vessels, Pancreas, Liver, Colon, Spleen, Lungs from CT Images.
- **Category:** Abdomen and Chest

### Multi-site, Multi-domain Airway Tree Modeling
- **Authors:** Zhang et al.
- **Link:** [Challenge](https://atm22.grand-challenge.org/dataset/))
- **Summary:** Lung airways masks for 300 cases.
- **Category:** Chest

### AeroPath: An airway segmentation benchmark dataset with challenging pathology
- **Authors:** Stoverud et al.
- **Link:** [Github](https://github.com/raidionics/AeroPath)
- **Summary:** Lung Airways for 27 severe cases and the webapp hosted on Hugging Face.
- **Category:** Chest

### VerSE : A vertebrae labelling and segmentation benchmark for multi-detector ct images.
- **Authors:** Anjany et al. 
- **Link:** [Paper](https://www.sciencedirect.com/science/article/pii/S1361841521002127)
- **Summary:**  374 CT images with veretebrae labels. 
- **Category:** Chest

### Towards Unifying Anatomy Segmentation: Automated Generation of a Full-body CT Dataset
- **Authors:** Jaus et al. 
- **Link:** [Paper](https://arxiv.org/abs/2307.13375) [Code](https://github.com/alexanderjaus/AtlasDataset.git)
- **Summary:** Segmenting 144 labels using nnunetv1 from whole-body FDG-PET/CT public dataset
- **Category:** Full Body

### TotalSegmentatator
- **Authors:** Jakob et al. 
- **Link:** [Dataset](https://zenodo.org/records/10047292)
- **Summary:** Masks for 117 labels publicly available for 1228 CT Images
- **Category:** Full Body
## <a name="theme2"></a>CT Segmentation Disease / Tumours 

### Voxel-level segmentation of pathologically-proven Adrenocortical carcinoma with Ki-67 expression
- **Authors:** Ahmed et al. 
- **Link:** [Dataset](https://www.cancerimagingarchive.net/collection/adrenal-acc-ki67-seg/))
- **Summary:** Adrenal cancer for 53 subjects 
- **Category:** Adrenal

### 
- **Authors:** Roth et al. 
- **Link:** [Dataset](https://covid-segmentation.grand-challenge.org/)))
- **Summary:** Unenhanced chest CTs from 199 and 50 patients, respectively, with positive RT-PCR for SARS-CoV-2 and ground truth annotations of COVID-19 lesions in the lung.
- **Category:** COVID-19
  

## <a name="how-to-contribute"></a>How to Contribute

We welcome contributions to this repository! If you would like to add a paper, suggest a theme, or improve the summaries, please follow these steps:

1. Fork the repository.
2. Make your changes or additions.
3. Submit a pull request with a clear description of your changes.

For more detailed instructions, see [CONTRIBUTING.md](LINK_TO_YOUR_CONTRIBUTING_GUIDELINES).

---

For any questions or suggestions, please open an issue in this repository.
