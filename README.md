# Image-Based Obstacle Detection and Free-Space Mapping for Path Planning

## 📌 Project Overview
This project implements an image-based obstacle detection and path planning system using classical Digital Image Processing techniques.  
The system detects obstacles from an input image, extracts free-space, and generates a collision-free path without using any dataset or machine learning model.

This project is developed as a **Complex Engineering Problem (CEP)** for the course **Digital Image Processing (CP-406)**.

---

## 🎯 Objectives
- Detect obstacles using image processing techniques  
- Extract free-space for safe navigation  
- Generate a collision-free path using graph-based search  
- Design a lightweight system suitable for unknown environments  

---

## 🧠 Methodology (High-Level)
1. Image acquisition  
2. Grayscale conversion and noise reduction  
3. Edge detection using Sobel operator  
4. Binary obstacle detection using thresholding  
5. Free-space mapping and occupancy grid generation  
6. Path planning using Breadth-First Search (BFS)  

---

## 📂 Repository Structure
├── Initial proposal.pptx # Project proposal and idea approval slides
├── PROJECT PRESENTATION.pptx # Final project presentation slides
├── PROJECT REPORT.docx # Complete CEP project report
├── project code.ipynb # Python implementation (Google Colab / Jupyter)
├── project video demo.mp4 # Working demonstration video
├── README.md # Project overview and documentation

---


---

## 🛠 Tools & Technologies
- Python  
- OpenCV  
- NumPy  
- Matplotlib  
- Google Colab / Jupyter Notebook  

---

## 📊 Performance Evaluation
The system is evaluated using:
- Obstacle and free-space detection accuracy  
- Path efficiency (collision-free path)  
- Processing time  

The results demonstrate reliable performance with low computational cost.

---

## 🚀 How to Run
1. Open `project code.ipynb` in Google Colab or Jupyter Notebook  
2. Upload an input image when prompted  
3. Run all cells to visualize obstacle detection and path planning results  

---

## 🎓 Academic Context
- **Course:** Digital Image Processing (CP-406)  
- **Semester:** 7th (Fall 2025)  
- **CEP Focus:** Image Processing System for Object Detection and Navigation  

---

## 📌 Conclusion
This project demonstrates that effective obstacle detection and path planning can be achieved using classical image processing techniques without relying on datasets or training models.


