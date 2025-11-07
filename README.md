
# Performance Comparison of ML Regression Models

This repository presents a series of performance comparisons of Machine Learning (ML) regression models across varying datasets. The following figures display how different regression models perform with varying amounts of data, number of sensors, and sensor types. The evaluation metrics used for these comparisons are **Mean Squared Error (MSE)** and **R-squared (R²)** values. Additionally, the comparison is made between scenarios with and without data augmentation.

## Figures Overview

### Figure 7: **Performance Comparison of ML Regression Models Across Various Data Volumes**
- **Description**: This figure compares the performance of several ML regression models as the volume of data varies. The comparison is done using:
    - **(a) MSE**: Mean Squared Error
    - **(b) R²**: R-squared value
    
    The goal is to assess how well the models perform as the amount of training data increases.
  
    - **File**: `Fig-7.png`

---

### Figure 8: **Performance Comparison of Regression Models Across Varying Number of Sensors**
- **Description**: This figure shows the performance of different regression models with respect to the number of sensors used in the dataset. It compares the models using:
    - **(a) MSE**: Mean Squared Error
    - **(b) R²**: R-squared value

    The comparison is shown in two conditions:
    - **With Augmentation** (augmentation applied to the sensor data)
    - **Without Augmentation** (no data augmentation applied)

    - **File**: `Fig-8_withaug.png` (With Augmentation)
    - **File**: `Fig-8_withoutaug.png` (Without Augmentation)

---

### Figure 9: **Performance Comparison of Regression Models Across Various Sensor Types**
- **Description**: This figure compares the performance of regression models when different types of single and combined sensors are used. The evaluation is performed on:
    - **(a) MSE**: Mean Squared Error
    - **(b) R²**: R-squared value

    The results are presented in two conditions:
    - **With Augmentation** (data augmentation applied)
    - **Without Augmentation** (no data augmentation applied)
    
    - **File**: `Fig-9_with-aug.png` (With Augmentation)
    - **File**: `Fig-9_without-aug-MSE.png` (Without Augmentation - MSE)
    - **File**: `Fig-9_without-aug-R2.png` (Without Augmentation - R²)

---

## Data Analysis and Visualization

Each figure presents detailed insights into the performance of the regression models under different configurations. The MSE and R² values are used to evaluate the models, where:
- **Lower MSE** indicates better performance.
- **Higher R²** indicates better fit of the model to the data.

### Data Augmentation
- **With Augmentation**: Augmenting the data by generating synthetic data points or using techniques like jittering can help improve the model's generalization ability.
- **Without Augmentation**: Using the original dataset without any modifications, which may lead to overfitting or poor generalization if the data is limited.

---

## Files Included

- `Fig-7.png`: Performance comparison of ML regression models across varying data volumes (MSE and R²).
- `Fig-8_withaug.png`: Performance comparison of regression models across varying number of sensors with data augmentation (MSE and R²).
- `Fig-8_withoutaug.png`: Performance comparison of regression models across varying number of sensors without data augmentation (MSE and R²).
- `Fig-9_with-aug.png`: Performance comparison of regression models across various types of single and combined sensors with data augmentation (MSE and R²).
- `Fig-9_without-aug-MSE.png`: Performance comparison of regression models across various types of single and combined sensors without data augmentation (MSE).
- `Fig-9_without-aug-R2.png`: Performance comparison of regression models across various types of single and combined sensors without data augmentation (R²).

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
