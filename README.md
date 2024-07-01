# SVM-and-OCSVM

## SVM Project

### Overview
This project focuses on the implementation and application of Support Vector Machines (SVMs) for binary classification tasks. The primary dataset used in this project involves images classified as either "real" or "fake."

### Project Structure

1. **Data Preparation**
    - **Mounting Google Drive**: The dataset is accessed from Google Drive.
    - **Data Unzipping**: The dataset is unzipped into the working directory.
    - **Directory Setup**: Paths for training, validation, and test datasets are established.
    - **File Listing**: The images are listed from their respective directories, with real images labeled as 0 and fake images as 1.
    - **Image Preprocessing**: Images are read, converted to RGB, and resized to 32x32 pixels.

2. **Data Visualization**
    - Random samples from the training set are visualized to provide an overview of the dataset. Both real and fake images are displayed.

3. **SVM Implementation**
    - The SVM model is trained on the preprocessed dataset.
    - Hyperparameters are tuned for optimal performance.
    - The trained model is evaluated on the test dataset.

4. **Results and Analysis**
    - Model performance is analyzed using metrics such as accuracy, precision, recall, and F1-score.
    - Visualizations of the decision boundary and misclassified examples are provided.

---

## OCSVM Project

### Overview
This project explores the use of One-Class Support Vector Machines (OCSVM) for anomaly detection. The dataset utilized involves detecting deepfake images within a collection of real images.

### Project Structure

1. **Data Preparation**
    - **Mounting Google Drive**: The deepfake dataset is accessed from Google Drive.
    - **Data Unzipping**: The dataset is unzipped into the working directory.
    - **Directory Setup**: Paths for training, validation, and test datasets are established.
    - **File Listing**: The images are listed from their respective directories, with real images labeled as 0 and fake images as 1.
    - **Image Preprocessing**: Images are read, converted to RGB, and resized to 32x32 pixels.

2. **Data Visualization**
    - Random samples from the training set are visualized to provide an overview of the dataset. Both real and fake images are displayed.

3. **OCSVM Implementation**
    - The OCSVM model is trained on the preprocessed dataset.
    - The model is configured to identify anomalies within the dataset.
    - The trained model is evaluated on the test dataset.

4. **Results and Analysis**
    - Model performance is analyzed using metrics such as accuracy, precision, recall, and F1-score.
    - Visualizations of the anomaly detection results and misclassified examples are provided.
