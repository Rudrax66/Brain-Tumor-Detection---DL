
🧠 Brain Tumor Detection
This repository contains an AI-powered web application designed to analyze brain MRI scans and detect the presence of tumors using Deep Learning. Built with PyTorch (ResNet50) and Streamlit, the tool provides real-time inference, interactive data visualizations, and downloadable medical reports.  
+4

✨ Features

Advanced AI Model: Utilizes a ResNet50 architecture pretrained on ImageNet weights for high-accuracy feature extraction.  
+1


Interactive UI: A sleek, dark-themed dashboard built with Streamlit.  

Comprehensive Analytics:


Confidence Gauge: Visualizes prediction certainty via Plotly.  


Probability Distribution: Bar charts showing "Tumor" vs. "No Tumor" likelihood.  


Pixel Intensity Graph: Analyzes the distribution of grayscale values in the MRI.  


Tumor Risk Meter: A quick-glance visual for risk assessment.  


Image Processing: Includes an enhancement toggle for contrast and an RGB channel viewer.  


Reporting: Generates a downloadable .txt report including date, image specs, and dietary recommendations.  
+1


Performance: Fast inference speed (under 500ms) thanks to model caching.  
+1

🛠️ Tech Stack
Library	Version	Purpose
Streamlit	>=1.32.0	
Web UI framework  

PyTorch	>=2.0.0	
Deep learning engine  

Torchvision	>=0.15.0	
ResNet50 model & transforms  

Pillow	>=10.0.0	
Image processing  

Plotly	>=5.18.0	
Interactive charts  

🚀 Installation & Setup
1. Clone the Repository and Navigate to the Directory
Bash
cd D:\Deep Learning

(Note: Adjust path as necessary for your local environment).  

2. Create and Activate a Virtual Environment
Bash
python -m venv myenv
myenv\Scripts\activate
.  
+1

3. Install Dependencies
Bash
pip install -r requirements.txt
.  
+1

4. Run the Application
Bash
python -m streamlit run app_short.py
.
Access the app in your browser at: http://localhost:8501.  
+1

🔬 Model Details

Architecture: ResNet50.  


Input Size: 224×224 pixels.  


Classes: 2 (No Tumor / Tumor Detected).  


Weights: IMAGENET1K_V1.  

📖 How to Use

Upload: Select a brain MRI scan in JPG, PNG, or BMP format.  


Adjust: (Optional) Use the sidebar to set the confidence threshold or enhance contrast.  


Analyze: Click the ANALYZE SCAN button.  


Review: Examine the risk meter, probability charts, and health tips.  


Export: Download the full analysis as a .txt report.  

📋 Disclaimer

This tool is built for EDUCATIONAL and RESEARCH purposes only. It is NOT a substitute for professional medical diagnosis. Always consult a qualified radiologist or neurologist for any medical concerns.  
+1

📁 Project Structure
Plaintext
D:\Deep Learning\
├── myenv\               (virtual environment)
├── app_short.py         (main Streamlit app)
└── requirements.txt     (dependencies)
.  
