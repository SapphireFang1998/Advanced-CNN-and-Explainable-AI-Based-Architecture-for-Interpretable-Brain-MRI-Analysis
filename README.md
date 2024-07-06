# Advanced CNN and Explainable AI Based Architecture for Interpretable Brain MRI Analysis

## Abstract
Deep learning practitioners have been using Convolutional Neural Networks (CNNs) for some time now and it has been a favourite topic for image based machine learning approaches for some time. On the other hand, day by day people are becoming more and more interested in understanding how deep learning models are working and thus Explainable AIs (XAIs) are being used to find it out. In this study, CNN and XAI are used to show a new way to make Brain MRI research easier to understand. The "Brain MRI Dataset" on Figshare has 5285 T1-weighted brain MRI pictures that are used in our method. These images have been put into 37 categories. Based on the dataset, the suggested model did well. It was accurate about 86\% of the time and had high precision, recall, and F1 scores. Our use of the Explainable AI model, Local Interpretable Model-agnostic Explanations (LIME) framework is remarkable because it gives reasons for each prediction that are local and do not depend on the prediction model. We now have a better idea of how the AI makes choices, which makes us believe and understand automated diagnostic systems in medical imaging even more. Diagnostic tools for medicine can be more open and effective when they use both deep learning frameworks and AI that can be explained.

## Table of Contents
- [Dataset](#dataset)
- [Proposed Methodology](#proposed-methodology)
- [Experimental Setups](#experimental-setups)
- [Results](#results)
- [Explainable AI](#explainable-ai)
- [Contact Information](#contact-information)
- [Citation](#citation)

## Dataset

The dataset used for training and evaluation is "Brain MRI Dataset" available on Figshare. You can find the dataset <a href="https://figshare.com/articles/dataset/Brain_MRI_Dataset/14778750/2">here</a>.

## Proposed Methodology
![Proposed Methodology](Images/ProposedMethodology.pdf)

## Experimental Setups
    
### Anaconda with VSCode
- **Environment:**
  - Python Version: 3.6.13 
  - Tensforflow Version: 2.6.2
  - Keras Version: 2.6.0
  - Processor: Intel i5 13400F
  - GPU: NVIDIA GeForce RTX 3060 (12 GB)
  - RAM: 16 GB
  - Storage: 512 GB NVMe SSD + 1 TB HDD
    


## Results
### Performance Evaluation of CNN Classification Model for Brain MRI Dataset

| Model | Accuracy | Precision | Recall | F1 Score |
|-------|----------|-----------|--------|----------|
| CNN   |   0.86   |   0.92    |  0.81  |   0.85   |

## Explainable AI
- **Correctly Classified:**
![Explainable AI](Images/CorrectlyClassified/CC1.jpeg)
![Explainable AI](Images/CorrectlyClassified/CC2.jpeg)
![Explainable AI](Images/CorrectlyClassified/CC3.jpeg)
![Explainable AI](Images/CorrectlyClassified/CC4.jpeg)

- **Misclassified:**
![Explainable AI](Images/Misclassified/MC1.jpeg)
![Explainable AI](Images/Misclassified/MC2.jpeg)
![Explainable AI](Images/Misclassified/MC3.jpeg)
![Explainable AI](Images/Misclassified/MC4.jpeg)

## Contact Information

For any questions or further inquiries, please feel free to reach out:

- **Shuvashis Sarkar**
  - Email: [shuvashisofficial@gmail.com](mailto:shuvashisofficial@gmail.com)

- **Shamim Rahim Refat**
  - Email: [n.a.refat2000@gmail.com](mailto:n.a.refat2000@gmail.com)

- **Faika Fairuj Preotee**
  - Email: [faikafairuj2001@gmail.com](mailto:faikafairuj2001@gmail.com)
    
## Citation

If you find the research work helpful, please consider citing our paper:



