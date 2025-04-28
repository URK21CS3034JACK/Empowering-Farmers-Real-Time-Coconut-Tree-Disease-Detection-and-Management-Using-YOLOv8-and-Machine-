Empowering Farmers: Real-Time Coconut Tree Disease Detection and Management Using YOLOv8 and Machine Learning Technique 🌴🌿
Overview
This project aims to assist farmers by detecting diseases in coconut trees in real-time using advanced computer vision techniques. Powered by the YOLOv8 object detection model and supported by machine learning, the system provides instant feedback along with disease management recommendations to help farmers take immediate action and protect their crops.

Features
🌟 Real-time coconut tree disease detection from images or live video

🧠 Highly accurate detection using YOLOv8

📊 Confidence scores and disease management suggestions

🔥 Visual explanations with EigenCAM for better interpretability

🎯 User-friendly web interface built with Streamlit

📈 High performance with low false positive and false negative rates

Technologies Used
YOLOv8 (You Only Look Once, version 8)

Machine Learning (ML)

Python

Streamlit (for UI)

OpenCV (for video and image handling)

EigenCAM (for model interpretability)

Google Colab / Jupyter Notebook (for training)

NVIDIA GPU (for model training acceleration)

Project Structure
bash
Copy
Edit
├── data/                  # Dataset (images of coconut tree diseases)
├── models/                # Trained YOLOv8 model weights
├── streamlit_app.py        # Main Streamlit UI application
├── training/               # Model training notebooks and scripts
├── utils/                  # Helper functions for preprocessing and visualization
├── README.md               # Project documentation
├── requirements.txt        # List of required Python libraries
Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/coconut-disease-detection.git
cd coconut-disease-detection
Install required libraries:

nginx
Copy
Edit
pip install -r requirements.txt
Run the Streamlit app:

arduino
Copy
Edit
streamlit run streamlit_app.py
Dataset
The dataset consists of labeled images of healthy and diseased coconut trees, covering common diseases such as:

Yellowing Disease

Bud Rot

Leaf Blight

Root Wilt

📦 Note: Dataset link or upload instructions can be provided here.

Results
Achieved a mean average precision (mAP) of over 90%.

False positive and false negative rates were kept minimal.

Real-time detection speed with a frame rate of over 20 FPS on GPU.

Future Work
Extend the system to support multiple crop types.

Integrate drone-based aerial image analysis.

Develop mobile app deployment for field usage.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Ultralytics YOLOv8

Streamlit Community

Open-source datasets and contributions from agricultural research organizations.
