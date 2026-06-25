# 🖼️ CIFAR-10 Image Classification using CNN and Transfer Learning

A comprehensive deep learning project comparing the performance of a **Custom Convolutional Neural Network (CNN)** with **Transfer Learning using GoogLeNet (Inception)** on the **CIFAR-10** image classification dataset. The project demonstrates the impact of pretrained models, fine-tuning strategies, and modern deep learning techniques on classification accuracy.

---

# 🚀 Features

* 🧠 Custom CNN architecture built from scratch using PyTorch
* 🔥 Transfer Learning with pretrained GoogLeNet (Inception)
* ⚡ Two-stage training:

  * Frozen backbone training
  * Fine-tuning pretrained layers
* 📊 Training & validation accuracy/loss visualization
* 📈 Model performance comparison
* 🎯 Per-class accuracy analysis
* 📉 Confusion Matrix & Error Analysis
* 🖼️ Custom image inference
* 💾 Model checkpoint saving
* 🚀 GPU (CUDA) support

---

# 🏗️ Project Workflow

```text
                CIFAR-10 Dataset
                       │
        ┌──────────────┴──────────────┐
        │                             │
        ▼                             ▼
   Custom CNN                 GoogLeNet (Pretrained)
        │                             │
        ▼                             ▼
   Model Training          Frozen Backbone Training
        │                             │
        ▼                             ▼
     Evaluation               Fine-Tuning
        │                             │
        └──────────────┬──────────────┘
                       ▼
              Performance Comparison
                       │
                       ▼
         Accuracy • Loss • Confusion Matrix
```

---

# 🛠️ Tech Stack

| Category        | Technologies                |
| --------------- | --------------------------- |
| Language        | Python                      |
| Deep Learning   | PyTorch                     |
| Computer Vision | TorchVision                 |
| Dataset         | CIFAR-10                    |
| Visualization   | Matplotlib, Seaborn         |
| Metrics         | Scikit-learn                |
| Training        | CUDA, AMP (Mixed Precision) |
| Notebook        | Jupyter Notebook            |

---

# 📂 Project Structure

```text
CIFAR10_CNN_vs_TransferLearning.ipynb
│
├── Environment Setup
├── GPU Configuration
├── Dataset Loading
├── Data Visualization
├── Custom CNN Model
├── CNN Training
├── CNN Evaluation
├── Error Analysis
├── Transfer Learning (GoogLeNet)
├── Frozen Backbone Training
├── Fine-Tuning
├── Performance Comparison
├── Per-Class Accuracy
├── Custom Image Prediction
├── Save Trained Models
└── Final Analysis
```

---

# 🧠 Models Used

## 🔹 Custom CNN

* Convolutional Layers
* Batch Normalization
* ReLU Activation
* Max Pooling
* Fully Connected Layers
* Dropout Regularization

---

## 🔹 Transfer Learning

* Pretrained GoogLeNet (Inception)
* Frozen Feature Extractor
* Fine-Tuning Strategy
* Optimized Classification Head

---

# 📊 Evaluation Metrics

The project compares both models using:

* Training Accuracy
* Validation Accuracy
* Test Accuracy
* Training Loss
* Validation Loss
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Per-Class Accuracy

---

# 📈 Visualizations

The notebook includes:

* Dataset sample visualization
* Accuracy curves
* Loss curves
* Confusion matrix
* Error analysis
* Per-class performance comparison
* Prediction results on custom images

---

# ⚙️ Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

## 2. Install Dependencies

```bash
pip install -r requirements.txt
```

## 3. Run the Notebook

```bash
jupyter notebook
```

Open:

```text
CIFAR10_CNN_vs_TransferLearning.ipynb
```

Run all cells to train and evaluate both models.

---

# 📌 Learning Outcomes

* Building CNN architectures from scratch
* Understanding convolutional neural networks
* Applying Transfer Learning in Computer Vision
* Fine-tuning pretrained models
* Training deep learning models using PyTorch
* Performance evaluation and visualization
* Comparing handcrafted and pretrained architectures

---

# 🚀 Future Improvements

* ResNet50 / EfficientNet comparison
* Vision Transformer (ViT) implementation
* Data augmentation techniques
* Hyperparameter optimization
* Model quantization
* TensorBoard integration
* ONNX / TorchScript deployment
* Streamlit or Flask web application for inference

---

# 📜 Conclusion

This project demonstrates the effectiveness of **Transfer Learning** over training a CNN from scratch on relatively small image datasets like CIFAR-10. While the custom CNN provides a strong baseline, the pretrained GoogLeNet model achieves superior accuracy, faster convergence, and better generalization through feature reuse and fine-tuning.

---

# 🤝 Contributing

Contributions and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

# 📜 License

This project is intended for educational and research purposes.

---

# 👨‍💻 Author

**Mounish Reddy**

If you found this project helpful, don't forget to ⭐ the repository!
