# Explainability Ensemble for Images

## Project Overview

This project explores the combination of different explainability techniques for image classification tasks to generate more robust explanations. The main idea is to apply multiple XAI methods and then find an effective way to integrate their results for a comprehensive understanding of model predictions.

## Research Question

Which is the best way to take advantage of different explainability techniques?

## Main Idea

Select an image classification task and apply different explainable AI (XAI) techniques. Then, find a way to combine the results to generate a more robust explanation compared to using each technique individually.

## Possible Steps

1. **Choose the dataset and deep learning models to be applied:**
   - Examples: ImageNet with pre-trained ResNet, MNIST with a custom CNN.
   - This project uses the ImageNet dataset and the InceptionV3 model.

2. **Select three explainability techniques suitable for image tasks:**
   - We suggest using SHAP, LIME, and Grad-CAM, as they are well-documented with available tutorials.

3. **Apply each technique individually and analyze the pros and cons of each:**
   - For example: Technique 1 highlights both relevant and irrelevant features, Technique 2 doesn't work well for certain classes, etc.

4. **Combine the techniques to obtain more robust explanations:**
   - This step is the explorative and creative part. Possible approaches include averaging feature maps across techniques, using one technique for identifying main regions and another for finer details, and so on.
   - The project implements different ensemble strategies, including simple averaging and weighted averaging based on individual method performance.


## How to Run

1. **Install necessary packages:**
2. **Run the notebook cells in order:**
   - The notebook is structured to guide you through data loading, model setup, application of XAI techniques, and ensemble methods.

## Results and Discussion

- The project provides visualizations and analysis of individual explanations and ensemble results.
- It discusses the strengths and limitations of different combination approaches.
- Further research and experimentation are encouraged to optimize the ensemble strategy.


## Future Work

- Experiment with different datasets and models.
- Explore more advanced ensemble techniques, such as using machine learning models to combine explanations.
- Evaluate the robustness of explanations on adversarial examples.



## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.


## License

[Choose a license (e.g., MIT License)](https://choosealicense.com/)
