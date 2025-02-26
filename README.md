# DermaVision
GH 2025

## Overview
DermaVision is an AI-powered diagnostic assistant designed to enhance early detection and diagnosis of skin diseases by integrating deep learning with structured patient data analysis. The system classifies dermatoscopic images into seven skin lesion types using CNN models (EfficientNet, ResNet) and analyzes patient data using ML models (Random Forest, XGBoost). Ensemble learning fuses insights from both models for comprehensive and accurate diagnosis.

## Running the Code in Google Colab
1.Click on the Colab Notebook link in the repository.<br>
2.Go to "Runtime" and select "Change runtime type," then choose "T4 GPU" for faster computations.<br>
3.Click on "Run all" in the Runtime menu to execute all cells sequentially.<br>

## Dataset and Install Dependencies
Code snippets are available for installing the Skin Cancer MNIST: HAM10000 dataset and required libraries.

## Expected Output
1.The model processes input images and classifies them into one of seven skin lesion categories.<br>
2. The expected output is the predicted disease.<br>

## Test Cases
1.Enter the path to the skin lesion image: /content/HAM10000/ham10000_images_part_2/ISIC_0031985.jpg <br>
  Enter patient age: 20 <br>
  Enter patient sex (male/female): female <br>
  Enter lesion location (e.g., back, scalp, face, etc.): lower extremity <br>

2.Upload the "user input 1.jpg" file to Google Colab under the DermaVision GH 2025 repository, then execute Test Case 2.<br>
  Enter the path to the skin lesion image: /content/user input 1.jpg <br>
  Enter patient age: 50 <br>
  Enter patient sex (male/female): male <br>
  Enter lesion location (e.g., back, scalp, face, etc.): scalp <br>

3.Enter the path to the skin lesion image: /content/HAM10000/ham10000_images_part_2/ISIC_0030276.jpg <br>
  Enter patient age: 80 <br>
  Enter patient sex (male/female): male <br>
  Enter lesion location (e.g., back, scalp, face, etc.): back <br>

4.Upload the "user input 2.jpg" file to Google Colab under the DermaVision GH 2025 repository, then execute Test Case 2.<br>
  Enter the path to the skin lesion image: /content/user input 2.jpg <br>
  Enter patient age: 32 <br>
  Enter patient sex (male/female): female <br>
  Enter lesion location (e.g., back, scalp, face, etc.): face <br>





