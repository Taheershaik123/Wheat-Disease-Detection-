Wheat Leaf Disease Detection and Segmentation 🌾🦠
This project detects and classifies 15 types of wheat leaf diseases using EfficientNetB0 and highlights infected areas with a U-Net segmentation model. It provides early and accurate disease identification for improved crop management and yield.

📌 Features
🌿 Classifies 15 wheat leaf diseases (including Healthy).

🧠 EfficientNetB0 for high-accuracy classification.

🎯 U-Net to segment and highlight infected regions.

📊 Visualizations: Accuracy/Loss plots, Confusion Matrix, Precision-Recall-F1 Score bar chart.

🔍 Overlayed masks show the diseased parts on prediction images.

📁 Dataset Structure
Organized into:

bash
Copy
Edit
data/
├── train/
├── valid/
└── test/
Each folder contains 15 subfolders for each class of disease.

🛠️ Requirements
TensorFlow

OpenCV

NumPy, Matplotlib, Seaborn

Pandas

Scikit-learn

Install using:

bash
Copy
Edit
pip install tensorflow opencv-python numpy matplotlib seaborn pandas scikit-learn
🚀 How to Run
Place dataset in the correct structure.

Train the classification model (EfficientNetB0).

Train the U-Net segmentation model.

Run predictions using predict_image("path/to/image").

📈 Evaluation
Classification report and confusion matrix for test data.

Per-class precision, recall, and F1-score.

Overlayed segmentation masks for diseased areas.

🧠 Models Used
EfficientNetB0 – for classification.

U-Net – for lesion segmentation.

📸 Sample Output
Class: Black Rust, Confidence: 98%

Segmented infected areas shown in blue contours.

✍️ Author
Shaik Taheer
MCA Student, Lovely Professional University
📍 Nellore, Andhra Pradesh

