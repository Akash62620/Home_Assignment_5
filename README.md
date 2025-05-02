# Home_Assignment_5
# Neural Networks Assignment — Tasks 3 & 4

##  Task 3: Basic GAN Implementation

This project implements a simple Generative Adversarial Network (GAN) using PyTorch to generate handwritten digits from the MNIST dataset.

###  Requirements
- PyTorch
- torchvision
- matplotlib
- Google Colab (recommended)

###  How to Run
1. Open the `.ipynb` file in Google Colab.
2. Install dependencies:
   ```
   !pip install torch torchvision matplotlib
   ```
3. Run all cells.
4. Download the generated images and loss plot:
   - `epoch_0.png`
   - `epoch_50.png`
   - `epoch_100.png`
   - `loss_plot.png`

### Outputs
- **epoch_0.png** → Generated samples at epoch 0  
- **epoch_50.png** → Generated samples at epoch 50  
- **epoch_100.png** → Generated samples at epoch 100  
- **loss_plot.png** → Plot showing generator and discriminator loss over time

---

##  Task 4: Data Poisoning Simulation

This project simulates a data poisoning attack on a sentiment classifier.

###  Description
- Trained a logistic regression sentiment classifier on a small dataset of movie reviews.
- Poisoned data by flipping labels on “UC Berkeley” sentences to negative.
- Compared classifier accuracy and confusion matrices **before and after poisoning**.

###  Requirements
- pandas
- scikit-learn
- seaborn
- matplotlib

### How to Run
1. Open the `.ipynb` file in Google Colab.
2. Install dependencies:
   ```
   !pip install pandas scikit-learn seaborn matplotlib
   ```
3. Run all cells.
4. Download the confusion matrix plots:
   - `confusion_matrix_before.png` *(if saved)*
   - `confusion_matrix_after.png` *(if saved)*

###  Results Summary
- Accuracy before poisoning: ~0.33  
- Accuracy after poisoning: ~0.66  
- The confusion matrices showed how data poisoning disrupted classifier performance and increased errors.

---

##  Student Info
- **Name:** Akash Pegada 
- **Course:** CS5720 Neural Network & Deep Learning  
- **Semester:** Spring 2025

---

