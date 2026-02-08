# BrainDead 2K26 Submission 🧠

**Team Name:** Salman
**Event:** Revelation 2K26 | IIEST Shibpur

---

## 📂 Repository Overview
This repository contains the complete submission for the **BrainDead 2K26** AI challenge. It includes:
1.  **Code Solution:** A working Hybrid Movie Recommender System (Problem 1).
2.  **Project Report:** A detailed technical analysis of both problem statements.
3.  **Demo Video:** A simulation of the Cognitive Radiology Agent.

---

## 🎬 Problem Statement 1: ReelSense (Movie Recommender)

### **Approach: Hybrid Filtering with Explainability**
We tackled the "Cold Start" and "Diversity" problems by combining two powerful techniques:
* **Content-Based Filtering:** Uses TF-IDF vectorization on movie genres to find similar items.
* **Collaborative Filtering:** Uses TruncatedSVD (Matrix Factorization) to identify latent user preferences.



### **Key Features**
* ✅ **Natural Language Explanations:** The system tells you *why* a movie was recommended (e.g., *"Because you liked Toy Story..."*).
* ✅ **Diversity Re-Ranking:** Prevents the "echo chamber" effect by ensuring the top recommendations cover multiple genres.
* ✅ **RMSE Score:** Our model achieved a Root Mean Squared Error of **1.9981**.

### **How to Run**
1.  Open the `.ipynb` file in Google Colab.
2.  Upload `movies.csv` and `ratings.csv` (or use the built-in downloader).
3.  Run all cells to see the recommendations and visualizations.

---

## 🩻 Problem Statement 2: NeuroRad-X (Radiology Agent)

### **Proposed Architecture**
To automate radiology reporting, we designed **NeuroRad-X**, a cognitive framework that mimics a human radiologist.



### **Core Modules**
1.  **PRO-FA (Hierarchical Visual Alignment):** A Vision Transformer that sees the X-ray at Pixel, Region, and Organ levels.
2.  **MIX-MLP (Knowledge-Enhanced Classification):** A clinical checklist layer that predicts disease tags before writing the report.
3.  **RCTA (Triangular Cognitive Attention):** Ensures the text output matches both the image and the patient's history.

*Note: The implementation for this problem is provided as a theoretical design and simulation demo due to data access constraints.*

---

## 📁 File Structure
* `BrainDead_Submission_Report.pdf` - The main technical report.
* `BrainDead_ReelSense_Submission.ipynb` - Source code for the Movie Recommender.
* `NeuroRad_Demo.mp4` - Video demonstration of the Radiology AI in action.

---
