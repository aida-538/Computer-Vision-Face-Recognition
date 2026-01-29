# Computer Vision: Identity Verification & Similarity Analysis

This project explores identity verification through a multi-layered approach using **MATLAB**. It evaluates the performance of modern **Deep Learning** classifiers against traditional mathematical similarity metrics and image segmentation techniques.

## 🚀 Key Technical Achievements

### 1. Deep Learning Classification
* [cite_start]**Model:** Developed a Convolutional Neural Network (CNN) to classify images into 'Me' and 'Not Me' classes[cite: 825].
* [cite_start]**Performance:** Achieved **90% accuracy** on validation sets and **70% accuracy** on test sets[cite: 828].
* [cite_start]**Validation:** Used **Confusion Matrices** to monitor correctly and incorrectly classified images during training[cite: 827, 837].



### 2. Image Segmentation Methods
[cite_start]Implemented and compared four distinct methods to isolate facial structures from backgrounds[cite: 829, 830]:
* [cite_start]**HSV & Otsu Thresholding:** Effective for intensity-based separation[cite: 829, 847, 853].
* [cite_start]**K-Means Clustering:** Used for unsupervised pixel grouping[cite: 829, 860].
* [cite_start]**SVM (Support Vector Machine):** Applied as a supervised segmentation approach[cite: 829, 865].



### 3. Quantitative Similarity Metrics
[cite_start]Conducted rigorous testing using five similarity measures to compare grayscale images against a reference[cite: 822, 823]:
* [cite_start]**SSIM (Structural Similarity Index)** and **PSNR (Peak Signal-to-Noise Ratio)**[cite: 822, 890].
* [cite_start]**MSE (Mean Squared Error)**, **Chi-square**, and **Histogram Intersection**[cite: 822, 887, 888].
* [cite_start]**Findings:** The results confirmed that images of the same person yielded significantly higher **PSNR** and **SSIM** scores than different individuals[cite: 824, 832].

## 🛠️ How to Run
1. [cite_start]Unzip the repository contents[cite: 833].
2. Open MATLAB and navigate to the project folder.
3. [cite_start]Run the `main.m` script to execute the classifier, similarity analysis, and segmentation comparison.

## 📂 Documentation
[cite_start]For full technical details on the segmentation metrics (e.g., PSNR values for Me1 vs. Ref) and deep learning architecture, see the pdf report.
