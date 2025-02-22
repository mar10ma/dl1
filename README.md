# Fine-Tuning a CNN Model for Flowers Classification 🌸🌻
📌 Overview:
This project fine-tunes a pre-trained MobileNetV2 model to classify images of different flower species. The dataset used is TensorFlow’s TF-Flowers dataset. The model was trained using transfer learning and further optimized through fine-tuning.

📌 Steps in the Project:

### 1️⃣ Load and preprocess the TF-Flowers dataset.
2️⃣ Use MobileNetV2 as a base model (without top layers).
3️⃣ Freeze the base model and add custom classification layers.
4️⃣ Train the model on the dataset (initial training).
5️⃣ Unfreeze the last 20 layers for fine-tuning to improve performance.
6️⃣ Save and deploy the fine-tuned model for flower classification.

📊 Model Performance:

✅ Fine-Tuned Accuracy: ~85%

🚀 The fine-tuned model achieves better generalization, making it more accurate in distinguishing between flower species! 🌿✨
