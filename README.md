# Film Colour Analysis and Image Classification

This project explores the fascinating use of colour in two contrasting films - "Oppenheimer" and "Barbie." Through visualisations and colour palette extraction, it provides insights into the distinct colour aesthetics employed in each film. Additionally, the study investigates the application of machine learning algorithms, specifically K-Nearest Neighbours (KNN) and Random Forest Classifiers (RFC), for classifying images based on their film of origin. The performance of these models is evaluated using two types of input data: the extracted colour palettes and the raw image pixels.

## Key Findings

1. The Random Forest Classifier achieved the highest accuracy of 0.86 when trained on the raw image data, outperforming the model trained on colour palettes.
2. While colour palette extraction aids in visualising the colour design of films, in this project, it did not provide a significant advantage as input features for image classification.

## Future Work

Potential avenues for future work include:
- Exploring alternative feature extraction techniques beyond colour palettes.
- Evaluating the performance of other machine learning models for image classification tasks.
- Optimising model performance through hyperparameter tuning and other strategies.
- Extending the analysis to a larger dataset of films to gain broader insights into colour usage across different genres and styles.
