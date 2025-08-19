🌍 Satellite Image Captioning Model for Environmental Data
📖 Overview

This project demonstrates a synthetic satellite image captioning pipeline that combines simulated environmental image features (e.g., vegetation, water, urban) with natural language processing to generate descriptive captions. The project provides a benchmark-ready dataset (>100 samples) and a baseline deep learning model for training and evaluation.

🛠 Features

Synthetic dataset of satellite-like environmental features.

Baseline image–caption deep learning model using CNN (for features) and LSTM (for text).

Training, validation, and inference pipeline.

Outputs captions describing environmental conditions.

Supports dataset export in CSV/Excel for benchmarking.

📂 Project Structure
Satellite-Image-Captioning-Model-for-Environmental-Data/
│── data/                      # Synthetic dataset (CSV, Excel)
│── satellite_captioning.py    # Main training & evaluation script
│── requirements.txt           # Python dependencies
│── README.md                  # Project documentation
│── outputs/                   # Saved models & generated captions

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/Satellite-Image-Captioning-Model-for-Environmental-Data.git
cd Satellite-Image-Captioning-Model-for-Environmental-Data

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Model
python satellite_captioning.py --epochs 20 --batch_size 16

📊 Example Outputs

Synthetic sample captions may include:

"Dense vegetation with small water bodies"

"Urban settlement surrounded by bare land"

"River flowing through agricultural fields"

👤 Author Amos Meremu Dogiye

github: https://github.com/Dogiye12

📜 License

This project is licensed under the MIT License.
