## RecycLens – AI-Based Waste Classification System using Computer Vision

## Overview
RecycLens is a Computer Vision-based system that classifies waste into categories such as plastic, metal, paper, and organic using deep learning. It helps promote proper waste segregation and environmental sustainability.

## Features
Upload or input waste images
AI-based classification
Supports multiple waste categories
Fast prediction using trained model
Easy-to-use interface

## How It Works
Input image is provided
Image is preprocessed
CNN model extracts features
Model predicts waste category
Output is displayed

## Project Structure
RecycLens/
│── __pycache__/
│── weights/                # Trained model files
│── .gitignore
│── app.py                  # Main application (API / UI logic)
│── helper.py               # Helper functions (preprocessing, prediction)
│── settings.py             # Configuration settings
│── train.py                # Model training script
│── requirements.txt        # Python dependencies
│── packages.txt            # Additional packages (if needed)
│── README.md


## Installation & Setup
# Step 1: Clone the Repository
git clone https://github.com/your-username/recyclens.git
cd recyclens
# Step 2: Create Virtual Environment (Recommended)
python -m venv venv

Activate it:

Windows:
venv\Scripts\activate
Mac/Linux:
source venv/bin/activate
# Step 3: Install Dependencies
pip install -r requirements.txt
If you are using extra system packages:

pip install -r packages.txt
# Step 4: Run the Application
python app.py
# Step 5: Access the App
Open browser
Go to:
http://localhost:5000

(or port shown in terminal)

## Output Example
Input: Plastic bottle
Output: Plastic 

## Modules Explanation
app.py → Main app logic
helper.py → Image processing + prediction
train.py → Model training
settings.py → Configurations
weights/ → Stored trained model

## Challenges Faced
Similar-looking waste types
Dataset imbalance
Lighting variations

## Author
Samridhi Tyagi
24MIM10091
