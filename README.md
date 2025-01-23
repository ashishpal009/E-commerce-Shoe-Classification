# E-commerce Shoe Classification

## Project Overview
E-commerce platforms rely heavily on accurate product classification to enhance user experience and provide better recommendations. This project aims to classify images of shoes into three distinct categories: **Boots**, **Sandals**, and **Slippers** using Deep Learning techniques.

---

## Goal
The primary goal of this project is to build a deep learning model that can:
- Train on a dataset of shoe images belonging to three categories (Boots, Sandals, Slippers).
- Accurately predict the category of shoes from the test dataset.

---

## Data Description
The dataset consists of images of shoes categorized into three folders:

### Train Set
- The train set includes images belonging to 3 categories of shoes, stored in separate folders:
  - **Boots**
  - **Sandals**
  - **Slippers**

### Test Set
- The test set includes images of all 3 categories combined in a single folder. The goal is to predict the labels for these images.

---

## Instructions
1. **Train the Model:**
   - Use the `train` dataset to train a deep learning model to classify the shoe images.
   
2. **Test the Model:**
   - Use the `test` dataset to evaluate the trained model and predict the category labels for the test images.

3. **Evaluation Metric:**
   - The performance of the model will be evaluated using the **Accuracy Score**, which matches the predicted shoe category with the actual shoe label.

---

## Requirements
### Libraries
Make sure to install the following libraries before running the code:
```bash
pip install tensorflow keras numpy pandas matplotlib scikit-learn
```

### Folder Structure
The dataset should have the following structure:
```
Dataset/
|-- train/
|   |-- Boots/
|   |-- Sandals/
|   |-- Slippers/
|
|-- test/
```

---

## Steps to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   cd ecommerce_shoe_classifier
   ```

2. **Prepare the Data:**
   - Place the dataset in the specified folder structure.

3. **Train the Model:**
   - Run the training script:
     ```bash
     python train_model.py
     ```

4. **Test the Model:**
   - Run the testing script to predict labels:
     ```bash
     python test_model.py
     ```

5. **View Results:**
   - The predictions and accuracy score will be displayed in the console, and results will be saved as a CSV file.

---

## Project Files
### 1. `train_model.py`
This script is responsible for:
- Loading and preprocessing the training data.
- Defining and training the deep learning model.
- Saving the trained model for later use.

### 2. `test_model.py`
This script handles:
- Loading the saved model.
- Preprocessing the test data.
- Generating predictions for the test images.
- Calculating and displaying the accuracy score.

---

## Results
The accuracy score and predictions will be displayed after testing. Results are stored in a `results.csv` file containing:
- File name
- Predicted category

---

## License
This project is open-source and available for educational and non-commercial purposes.
