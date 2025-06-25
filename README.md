# Classification and Interpretation of Histopathology Images

This repository contains the code and resources related to the research paper:

**Classification and Interpretation of Histopathology Images: Leveraging Ensemble of EfficientNetV1 and EfficientNetV2 Models**

---

## Authors

- Mahdi Azmoodeh Kalati  
- Hasti Shabani  
- Mohammad Sadegh Maghareh  
- Zeynab Barzegar  
- Reza Lashgari  

---

## Publication Date

2025

---

## Description

Breast cancer is the second leading cause of cancer-related deaths among women, following lung cancer, as of 2024. Conventional cancer diagnosis relies on manual examination of biopsied tissues by pathologists, a time-consuming process that can vary based on the pathologist’s experience.

Early detection and accurate diagnosis are critical for effective treatment planning and patient care. The invention of whole-slide scanners has revolutionized this process by enabling the use of Computer-Aided Detection (CAD) systems for automated analysis.

Convolutional Neural Networks (CNNs) within CAD systems play a pivotal role in the automated classification of breast tissues. This study utilizes state-of-the-art CNN architectures, EfficientNetV1 and EfficientNetV2, to perform binary classification on the BreakHis dataset, which consists of histopathological images categorized as benign and malignant breast tissues.

To improve classification performance, an ensemble method combining EfficientNetV1 and EfficientNetV2 models is applied, resulting in enhanced accuracy and reliability.

---

## Repository Contents

- Implementation of EfficientNetV1 and EfficientNetV2 models  
- Ensemble techniques for histopathology image classification  
- Scripts for training, evaluation, and inference on the BreakHis dataset  
- Preprocessing and data handling utilities  

---

## Online Implementation

An interactive implementation of this work is available on Hugging Face Spaces:  
[Histopathology Classification on Hugging Face](https://huggingface.co/spaces/mahdiazmoodeh95/histopathologyclassification)  

---

## How to Use

1. Clone the repository  
2. Set up your Python environment with required dependencies 
3. Prepare the BreakHis dataset according to instructions  
4. Run training and evaluation scripts  
5. Use the provided notebooks for interpretation and analysis  

---

## Citation

If you find this work useful, please cite the paper as:

```bibtex
@article{kalati2025classification,
  title={Classification and Interpretation of Histopathology Images: Leveraging Ensemble of EfficientNetV1 and EfficientNetV2 Models},
  author={Kalati, Mahdi Azmoodeh and Shabani, Hasti and Maghareh, Mohammad Sadegh and Barzegar, Zeynab and Lashgari, Reza},
  year={2025}
}
