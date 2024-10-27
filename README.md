# Sentinel-2 Image Classification of Crozon Coastal Area

This repository documents the workflow for **classifying Sentinel-2 images** of the coastal region near **Crozon, France**. Using ESA's SNAP software, the project includes class separability analysis, visual exploration with scatter and profile plots, statistical analysis, and final classification results. This README provides a structured overview of each processing step.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Study Area: Crozon, France](#study-area-crozon-france)
3. [Class Separability Analysis](#class-separability-analysis)
4. [Scatter Plot Analysis](#scatter-plot-analysis)
5. [Profile Plot Analysis](#profile-plot-analysis)
6. [Statistical Analysis](#statistical-analysis)
7. [Classification Results](#classification-results)

---

## Introduction

This project focuses on **classifying land cover types** within the Crozon coastal area using Sentinel-2 satellite imagery. Classification is performed using SNAP, taking advantage of the software's tools for class analysis and data visualization. The resulting classification provides insight into the spatial distribution of land cover classes, supporting environmental and coastal studies.

---

## Study Area: Crozon, France

The analysis is conducted on Sentinel-2 images of **Crozon, a coastal region in France**. This area was selected for its diverse land cover types, making it an ideal test case for assessing class separability and classification accuracy.

![image](https://github.com/user-attachments/assets/b2bfb4ce-fdd7-486d-8516-d57df935c3e6)


---

## Class Separability Analysis

The class separability analysis examines how well different land cover classes can be distinguished in the selected bands of the Sentinel-2 imagery. By comparing spectral signatures, this step helps optimize classification accuracy.

![image](https://github.com/user-attachments/assets/2ce58bfa-e6f4-41b3-bbe7-0e1d00c0fb5f)


---

## Scatter Plot Analysis

**Scatter plots** provide a visual assessment of spectral class separability by plotting the reflectance values of different bands against each other. This helps to identify potential class overlaps and informs the selection of appropriate bands for classification.

![image](https://github.com/user-attachments/assets/563e36a5-0e55-4804-90e1-dee36aa5c927)


---

## Profile Plot Analysis

**Profile plots** display the spectral signature of selected classes across different Sentinel-2 bands, offering insights into their distinct reflectance patterns. This step aids in refining the classification model by highlighting distinguishing features of each class.

![image](https://github.com/user-attachments/assets/3ab972c4-f176-42a5-a430-80eee7ad2bce)


---

## Statistical Analysis

Using SNAP's statistical tools, this section calculates summary statistics (e.g., mean, standard deviation) for each land cover class, allowing for quantitative comparison and validation of class separability. The results guide adjustments to the classification process for improved accuracy.

![image](https://github.com/user-attachments/assets/84625e02-75ed-4440-bc76-9fdf303fbd6f)


---

## Classification Results

The classification results illustrate the distribution of land cover types within the Crozon region, as mapped from Sentinel-2 imagery. The final classified image is presented, showing how effectively different land cover types were identified based on spectral analysis.

![image](https://github.com/user-attachments/assets/cc0ee97f-e0a1-4006-8fe3-45899dc8c0c0)
