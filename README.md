# Brain_Tumor_Prediction_ModelV1
This project focuses on classifying brain tumors from MRI images using a Convolutional Neural Network (CNN) built with PyTorch. The dataset was sourced from Kaggle and contains MRI scans labeled into four tumor categories. The model performs multi-class image classification to assist in medical diagnostics.
Key Features:

📊 Dataset: Brain Tumor MRI Dataset (Kaggle)

🧰 Libraries Used: PyTorch, Torchvision, Matplotlib, Seaborn, Pandas, NumPy

⚙️ Preprocessing:

Image resizing to 128x128 pixels

Normalization and Tensor conversion

Train-test split with DataLoaders for batching and shuffling

🧠 Model Architecture:

3 Convolutional layers with ReLU activation and MaxPooling

Flatten layer followed by Fully Connected layers

Dropout for regularization

Final output layer with 4-class classification

🧪 Training:

Trained for 25 epochs using the AdamW optimizer and CrossEntropyLoss

Implemented on GPU if available

📈 Evaluation:

Tested on unseen data

Achieved classification accuracy on test set with loss and performance metrics reported

🖼️ Visualization:

Random sample predictions visualized with actual labels

Displayed unnormalized images to interpret model predictions visually

Outcome:
Built a reliable baseline model for automated brain tumor classification, which sets the foundation for future improvements using transfer learning (e.g., ResNet, VGG) or advanced ensemble techniques.

