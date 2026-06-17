---
layout: project
title: "Predictive Stability vs. Fairness Instability in Clinical ECG Classification: A Multi-Run Analysis of Deep Learning Models"
permalink: /about-my-project.html

subtitle: A Study of Reproducibility, Bias, and Equity in Clinical Deep Learning Systems
project_title: "Predictive Stability vs. Fairness Instability in Clinical ECG Classification: A Multi-Run Analysis of Deep Learning Models"

problem: |
  Artificial intelligence is becoming increasingly important in healthcare, helping doctors analyze medical data and support clinical decision-making. 
  However, AI systems can sometimes perform differently for certain demographic groups, potentially contributing to healthcare disparities. This project 
  focuses on AI models that analyze electrocardiograms (ECGs), which are recordings of the heart's electrical activity used to detect cardiac conditions.

  Most studies evaluate AI models based on their overall accuracy, but fewer examine whether fairness remains consistent across multiple training runs. 
  Using the PTB-XL ECG dataset, this research investigates whether deep learning models produce stable predictions while also providing equitable outcomes 
  across different age and sex groups. By identifying and measuring fairness variability, this project aims to improve the reliability, transparency, 
  and trustworthiness of AI systems used in healthcare.

approach: |

  - Step 1 — Data Preparation and Model Development: Load and preprocess ECG recordings from the PTB-XL dataset using Python, NumPy, Pandas, and PyTorch. Build and
    train deep learning models, including a baseline 1D-CNN and a hybrid CNN-Transformer model for multi-label ECG classification.
  - Step 2 — Fairness Analysis and Bias Mitigation: Evaluate model performance across demographic groups based on age and sex. Compute fairness metrics such as False
    Negative Rate (FNR) gaps and Equalized Odds, then apply bias mitigation techniques to reduce disparities while maintaining predictive performance.
  - Step 3 — Evaluation and Statistical Testing: Perform repeated training runs to measure predictive stability and fairness variability. Analyze metrics such as
    AUROC, F1-score, and fairness measures using statistical methods and confidence intervals to determine the consistency of model behavior.
  - Step 4 — Interpretation and Communication: Use explainability techniques such as Grad-CAM to visualize model decision-making and generate research-quality figures.
    Summarize findings in a research report, presentations, and a final symposium poster highlighting the trade-offs between accuracy, fairness, and robustness in
    clinical AI systems.
    
outcome: |
  By the end of the program, I expect to produce trained deep learning models for ECG classification, a complete fairness evaluation pipeline, and a collection of
  research-quality visualizations that demonstrate both predictive performance and fairness outcomes across demographic groups. These artifacts will include model 
  performance reports, fairness metric analyses, statistical evaluations, and explainability visualizations generated using Grad-CAM.

  In addition, I will create a research poster, final presentation, and written report summarizing the project's methodology, findings, and implications for equitable 
  healthcare AI. The goal is for these materials to help researchers better understand how fairness metrics can vary across repeated training runs, even when overall 
  model performance remains stable. The resulting pipeline and analyses can serve as a foundation for future work on developing more reliable, transparent, and fair AI 
  systems for clinical applications.

final_report_url: NOT COMPLETE YET

grad_mentor:
  name: Sudip Sharma
  website: https://sudipsharma013.com.np/

faculty_mentor:
  name: Dr. Blessing Ojeme
  linkedin: https://www.linkedin.com/in/blessing-ojeme-phd-259a7342/
---
