Project Title: Measuring Music Engagement in Real-Time: The Role of Physiological Biomarkers

Project Description:

This project presents an intelligent system for real-time emotional engagement tracking during music and video experiences using Heart Rate Variability (HRV) data from wearable sensors. Originally designed to support individuals with Alzheimer’s Disease and Related Dementias (ADRD), the system enables objective, non-invasive monitoring of emotional states, which can be critical in therapeutic music interventions and personalized care.

Traditional methods for measuring emotional response in dementia care rely on caregiver observations or subjective reports. This system bridges that gap by combining physiological biomarkers with machine learning to detect emotions like Happy, Sad, or Relaxed—helping clinicians and caregivers better understand and optimize music-based therapies.

Key Features:
A) HRV Signal Processing: Extracts and synchronizes HRV data with timestamped media clips.
B) Emotion Labeling: Combines physiological metrics with survey responses (Q1–Q4) to infer emotional impact.
C) Machine Learning Models: Implements Random Forest classifiers to predict emotional states across:
- Audio-only clips
- Video clips
- Combined media sessions
D) Visual Insights: Provides boxplots, confusion matrices, and feature importance plots to interpret model performance.
E) Scalable Design: Supports real-time emotion tracking for clinical, entertainment, and research environments.

Technology Stack:
Data & ML: Python, Scikit-learn, Pandas, XGBoost
Visualization: Seaborn, Matplotlib, Power BI
Frontend: Flutter
Backend: Django API + Firebase
Hardware: Empatica EmbracePlus (HRV wrist sensor)

Included in this Submission:
1. Final Project Report (PDF/Word) - Contains problem overview, system design, methods, analysis results, and visuals.
2. Project Code:
   - shprojectlatest.py: Final implementation notebook exported as a Python script.
3. Visual Outputs:
   - Plots and confusion matrices for emotion classification and HRV analysis.
4. README.txt (this file)


How to Run:
1. Open the script (`shprojectlatest.py`) in Google Colab or a Jupyter-compatible environment.
2. Upload the required HRV and label Excel/CSV files as prompted.
3. Follow the notebook flow to preprocess data, visualize HRV trends, and train emotion classification models.

---
