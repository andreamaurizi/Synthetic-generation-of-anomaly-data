# Synthetic-generation-of-anomaly-data
To enhance the readability and informativeness of your GitHub README for the "Synthetic-generation-of-anomaly-data" project, consider expanding it with detailed sections and improving its structure. Here’s a revised version:

---

# Synthetic Generation of Anomaly Data

Welcome to the "Synthetic Generation of Anomaly Data" project repository! This project, developed by the Laboratory of Computer Vision and Artificial Intelligence, focuses on training Convolutional Neural Networks (CNNs) for the classification of grape images into two categories: healthy or sick. Below you will find an overview of the project, including data generation, model training, and performance evaluation.

## Project Overview

The primary goal of this project is to explore the efficacy of synthetic image data in improving the performance of a CNN model for grape disease classification. The project involves several key steps:

1. **Training with Real Data**: Initially, the CNN model is trained using a dataset comprising real images of healthy and diseased grapes.
2. **Training with Synthetic Data**: A second model is trained with a combination of real images of healthy grapes and synthetic images of sick grapes. The synthetic images are created using advanced computer vision techniques.
3. **Performance Comparison**: The performance of the two models is evaluated and compared to assess the impact of synthetic data on classification accuracy.

## Data Generation

### Real Dataset
- **Source**: Images obtained from the Canopies project.
- **Content**: Includes photographs of grapes showing various conditions, such as:
  - Healthy grapes
  - Grapes with physical damage
  - Grapes with irregular maturation

### Synthetic Data Creation
Synthetic images of sick grapes are generated through the following process:
- **Pre-processing**: Conversion to grayscale, Gaussian blurring, and normalization.
- **Enhancements**: Application of morphological operations, contour segmentation, and area-based modifications.
- **Chromatic Variability**: Simulation of diverse disease symptoms by introducing color variations.

## Models

1. **Model 1**: 
   - **Training Data**: Real images of healthy and sick grapes.
   - **Purpose**: Establish a baseline performance using actual data.

2. **Model 2**:
   - **Training Data**: Real images of healthy grapes combined with synthetic images of sick grapes.
   - **Purpose**: Evaluate the impact of synthetic data on model performance.

3. **Model 3**:
   - **Training Data**: Real images of healthy grapes combined with synthetic images of sick grapes featuring chromatic variability.
   - **Purpose**: Assess the influence of chromatic variability on classification accuracy.

## Evaluation

The performance of the models is compared based on:
- **Accuracy**: The proportion of correctly classified images.
- **Precision and Recall**: Measures of the model's ability to correctly identify sick grapes.
- **Generalization**: How well the model trained with synthetic data generalizes to new, unseen data.


## Results

Detailed results and comparisons of model performances are documented in the `results/` directory. This includes:
- Model performance metrics
- Visualizations of synthetic images
- Analysis of classification accuracy

## Contributing

We welcome contributions to improve this project. If you have suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize this template according to your project's specifics. Adding sections for results, usage instructions, and contributing guidelines will provide comprehensive information and enhance the overall usability of your repository.
