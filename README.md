
# 🧠 Epileptic Seizure Detection using SLT and SNN

### 🚀 Overview  
Epileptic seizures cause sudden disturbances in brain activity, leading to disrupted brain function. Early detection and diagnosis are crucial for effective treatment and management of seizures. This repository introduces a novel **SLTSNN hybrid model** that integrates:  
- **Slantlet Transform (SLT)** for advanced EEG signal processing.  
- **Spiking Neural Network (SNN)** using Leaky Integrate-and-Fire (LIF) neurons.  

This model leverages EEG signals and provides superior detection accuracy, offering a robust solution for epileptic seizure analysis on imbalanced datasets.

---

### 🗂 Features  
- 🧪 **Signal Processing with SLT**:  
  Extracts multiple linear components for better feature representation of EEG signals.  

- 🧠 **Hybrid SLTSNN Model**:  
  Combines SLT with SNN for enhanced detection potential.  

- 📊 **Performance Metrics**:  
  Achieves exceptional results with imbalanced datasets:  
  - **Precision**: `0.98`  
  - **Recall**: `0.98`  
  - **F1-score**: `0.96`  
  - **Accuracy**: `0.98`  

---
# All Folders will be uploaded here upon the publication of the paper
### 📂 Repository Structure  
```plaintext
📦 epileptic-seizure-detection
├── 📁 data/               # Contains EEG datasets (ensure privacy and compliance)
├── 📁 models/             # Hybrid SLTSNN model implementation
├── 📁 utils/              # Utility scripts (e.g., preprocessing, metrics calculation)
├── 📁 notebooks/          # Jupyter notebooks for experimentation and visualization
├── 📜 README.md           # Project overview
├── 📜 requirements.txt    # Dependencies
└── 📜 LICENSE             # Licensing information
---

### 🛠️ Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/subirbiswas192001/Epileptic-Seizures-SLTSNN-.git
   cd epileptic-seizure-detection
   ```

2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

---

### 🚀 Getting Started  

1. **Preprocess EEG Data**:  
   Use scripts in the `utils/` directory to preprocess and balance EEG datasets.  

2. **Train the SLTSNN Model**:  
   Run the training script:  
   ```bash
   python train_model.py
   ```

3. **Evaluate the Model**:  
   Use the test dataset to evaluate performance metrics:  
   ```bash
   python evaluate_model.py
   ```

4. **Visualize Results**:  
   Jupyter notebooks in `notebooks/` contain visualization and analysis workflows.  

---

### 🧪 Results  
The **SLTSNN model** demonstrated exceptional performance across multiple datasets:  
| Metric        | Value |  
|---------------|-------|  
| **Precision** | 0.98  |  
| **Recall**    | 0.98  |  
| **F1-score**  | 0.96  |  
| **Accuracy**  | 0.98  |  

---

📖 Citation
If you use this repository for your research, please cite:

@article{SLTSNN,
  title={Enhanced Detection of Epileptic Seizures Using SLT and SNN},
  author={--},
  journal={--},
  year={2025}
}

---

### 📬 Contact  
For questions or collaborations, please contact:  
📩 **subirbiswas192001@gmail.com**  

---

### 💡 License  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

---

### 🌟 Acknowledgements  
Special thanks to our research team and contributors for their support and dedication!

