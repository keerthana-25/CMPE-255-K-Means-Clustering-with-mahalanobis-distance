# K-Means Clustering with Missing Data using Mahalanobis Distance  
**CMPE 255: Data Mining – Individual Assignment**

This project explores a recent approach to clustering incomplete datasets by **jointly performing imputation and K-means clustering** using **Mahalanobis distance**, based on the paper:

> **K-Means Clustering With Incomplete Data with the Use of Mahalanobis Distances**  
> [arXiv:2411.00870](https://arxiv.org/abs/2411.00870) (2024)

Traditional K-means fails when data has missing values and when clusters are elliptical rather than spherical. This project reproduces and explains the core ideas of the paper in a simple, reproducible way, with visualizations and a Medium article that summarizes the paper for a broader audience.

---

## 🎯 **Objectives**
- Understand the limitations of standard K-means for incomplete data
- Explain joint optimization of **imputation + clustering**
- Demonstrate why **Mahalanobis distance** captures cluster shape better
- Compare against baseline approaches
- Publish an accessible Medium article summarizing the work
- Present the results in a short slide deck + recorded video

---

## 📄 **Medium Article**
A detailed article summarizing the paper, the intuition behind the method, and results from experiments is published here:

👉 [K-Means Clustering With Missing Data: A Smarter Approach Using Mahalanobis Distance](https://medium.com/@keerthanapm257/k-means-clustering-with-missing-data-a-smarter-approach-using-mahalanobis-distance-7997d60610e6)

---

## 🎥 **Slides & Video**
Presentation slides (.pdf/.ppt):  
👉 [K-Means Clustering With Missing Data - Using Mahalanobis Distance](https://www.slideshare.net/slideshow/k-means-clustering-with-missing-data-pptx-f5ea/284502499) 

Recorded walkthrough:  
👉 [YouTube video link](https://youtu.be/8_eLFUBenMA)

---

## 🧠 **Method Summary**
This approach differs from standard K-means in two ways:

### 1. Joint Learning
Instead of:
