# Breast_cancer_classification
## Look into Data

![1](https://user-images.githubusercontent.com/54334941/143998570-18d5f7ff-608f-4f0f-bc44-a21a280f7a8e.png)

- 5 features with 1 binary target variable, 569 samples

## Analyze Features & Target

![2](https://user-images.githubusercontent.com/54334941/143999364-6cae4651-c5b4-4ac3-9453-e7ef08ba7850.png)

- Preprocess redundant features -> Mean parameter can represent mean area and mean radius

![3](https://user-images.githubusercontent.com/54334941/143999657-ab21bbbf-ed47-43d8-9acd-905b5746b0e5.png)

- Distributions: Linear Separability & Non-linear separability 

![5](https://user-images.githubusercontent.com/54334941/144540396-bcd8eb35-dd19-4820-a177-33f666befe3a.png) 
![6](https://user-images.githubusercontent.com/54334941/144540404-d813105a-59c4-4e41-b41c-2550cc6b02c8.png)

- Training with voting method (SVM, Random Forest, Gradient Boosting Classifier, and Hist Gradient Boosting Classifier)

![voting](https://user-images.githubusercontent.com/54334941/144540421-c405a48d-d6ba-4f3c-b0bf-8fc0c552afa7.png)

- Training with Deep Learning

![deep](https://user-images.githubusercontent.com/54334941/144540432-bdb34b22-8fa4-4518-8372-455138d1e312.png)

## Conclusion
- The data includes 569 rows with 3 features.
- Linear classifier also has good score for testset.
- False negative would be a big issue in diagnostic algorithms.

## What is the next?
- Making diagnostic model with more information.
- What mechanisms are behind the information?
- How to improve the score? 
