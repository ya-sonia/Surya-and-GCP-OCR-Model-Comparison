# Comparative Analysis of OCR Models: Surya vs. GCP

## Overview
This project evaluates the performance of two Optical Character Recognition (OCR) models—**Surya** and **Google Cloud Platform (GCP)**—in extracting text from images. The goal is to determine which model provides more accurate and readable results.

## Methodology
The analysis was conducted based on:
- **Accuracy**: How closely the extracted text matches the original.
- **Error Types**: Common mistakes in the extracted text.
- **Readability**: How clear and structured the text is.
- **Consistency**: Frequency of errors across different samples.

## Findings
### 🔹 GCP OCR
- Common errors: **Unnecessary spaces** between words.
- Formatting issues: Words were sometimes broken incorrectly.
-  Incorrect handling of punctuation marks.
-  Missing Digits: Some numbers are completely missing, affecting the accuracy of numerical data in documents.

### 🔹 Surya OCR
- Better word structuring with **fewer spacing issues**.
- Good readability and usability.
- Predicting Wrong Text.
- Some Text is Missing.

## Conclusion
Based on the analysis of OCR errors in Telugu, Gujarati, and Odia, 
**Google Cloud Vision (GCP)** OCR is the best overall model due to its higher accuracy, better word segmentation, 
and multi-language support compared to Surya. However, GCP still has issues with missing digits, incorrect 
spacing, and punctuation handling, which can impact its reliability for certain applications.

## Excel Sheet for Analysis:
The dataset and analysis used for evaluating the models can be accessed in the **Google Docs Excel sheet** [here](https://docs.google.com/spreadsheets/d/1EPlpC0yaOwmFxHK59AYqwxq9d-ihYgbF/edit?usp=sharing&ouid=110672771518185269583&rtpof=true&sd=true).


## Report
You can read the full report [here](Excel_sheet_of_analysis_AND_best_model_suggest/Sonia-IITMadras_Report.pdf).

---
📌 **Author**: Sonia Yadav  
📌 **Institute**: National Institute of Technology, Srinagar  
📌 **Internship**: IIT Madras  
