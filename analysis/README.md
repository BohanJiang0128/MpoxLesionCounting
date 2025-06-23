# Analysis Code

Created by Bohan Jiang on 4/28/2025  
Last updated by Bohan Jiang on 4/28/2025

This directory contains scripts and Jupyter notebooks for analyzing segmentation model performance, used in the JMI publication.

## 📘 Files

- `*_Comprehensive.ipynb`:  
  Calculates performance metrics such as precision, recall, and F1 score. Also includes contour mapping logic for visualization.

- `*_SharedErrorAnalysis.ipynb`:  
  Compares outputs from two networks to visualize shared and differing errors.

- `BlandAltmanPlots.ipynb`:  
  Plots Bland-Altman LoA (limits of agreement) between network predictions and ground truth.  
  *Note: This code is adapted from Andrew’s earlier work.*

## 📈 Output

These analyses help validate and interpret model results in the context of clinical accuracy and agreement.
