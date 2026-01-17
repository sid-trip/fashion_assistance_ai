# NeuroStyle: AI Wardrobe Consultant 

**A Hybrid AI System for Context-Aware Fashion Recommendation.**

## Project Overview
NeuroStyle is a "Zero-Shot" stylist engine. It takes a single image of a clothing item and generates a complete, stylistically consistent outfit (Bottoms, Shoes, Watch). It solves the problem of "Visual Dissonance" by combining Deep Learning for texture analysis with Semantic Rules for style logic.

**Key Innovation:**
To address dataset constraints, this project integrates **Generative AI (ESRGAN)** to upscale low-resolution thumbnails into high-fidelity assets in real-time.

## IMPORTANT NOTICE:
* This project requires to be opened in an editor that supports python-TF. **Recommended to run in google colab.**
* **Also requires your own Kaggle username and api key to download the dataset**

## Features
- **Hybrid Architecture:** ResNet50 (Visual Features) + Pandas (Semantic Logic).
- **Generative Enhancement:** Google ESRGAN for 4x Super-Resolution.
- **Interactive UI:** IPyWidgets-based dashboard for real-time testing.
- **Explainability:** K-Means Color Palette extraction and Latent Space Visualization.

## Tech Stack
- **Deep Learning:** TensorFlow, Keras, TensorFlow Hub
- **Computer Vision:** OpenCV, ResNet50
- **Algorithms:** Scikit-Learn (Nearest Neighbors, PCA, K-Means)
- **Interface:** Google Colab, IPyWidgets

## Repository Structure
- `NeuroStyle_Project.ipynb`: The main source code (Start here).
- `requirements.txt`: List of dependencies.

## ⚠️ Note on Execution
The notebook is designed to run in **Google Colab**. It automatically downloads the required datasets and models via code **(Requires Kaggle username and api key)**. No manual file setup is required.
