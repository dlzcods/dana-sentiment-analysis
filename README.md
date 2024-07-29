# Sentiment Analysis of Reviews on Dana Apps in Play Store
This project aims to design a deep learning model with certain schemes to analyze the sentiment of each user review which is then evaluated with predefined objectives. 

## Objective
- Training and test accuracy of at least 92%
- The model was able to classify 3 different classes: negative, neutral, and positive

## Dataset
To support the defined objectives, the dataset was obtained from independent scapping with a total of 139500 reviews in Indonesian.

## Modeling
| Scheme | Model      | Feature Extraction | Data Splitting |
|--------|------------|--------------------|----------------|
| 1      | Sequential | TF-IDF             | 80/20          |
| 2      | CNN        | TF-IDF             | 70/30          |
| 3      | CNN        | TF-IDF             | 80/20          |

## Model Evaluation
#### Scheme 1
![image](https://github.com/user-attachments/assets/0c5cf502-c897-495e-af31-c1397223cc1a)
<br>

#### Scheme 2
![scheme 2](https://github.com/user-attachments/assets/b408221b-d64f-42f5-be4f-995cf6870468)
<br>

#### Scheme 3
![sheme 3](https://github.com/user-attachments/assets/00dd99d5-4c64-4184-870d-1a300d1ff236)
<br>

### Summary
| Scheme | Train Accuracy | Test Accuracy |
|--------|----------------|---------------|
| 1      | 97             | 92            |
| 2      | 97             | 94            |
| 3      | 97             | 91            |
<br>

Seen from the summary and prediction results of the model that has fulfilled all the points that are the objective of this project.

## Challenges and Solutions
During the model development process, there were several challenges encountered. Below are the main challenges and the solutions implemented to overcome them:
<br>
### Data Imbalance
Challenge: The dataset had an imbalance in the number of reviews for each sentiment class.
<br>
Solution: Applied oversampling techniques such as SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset. This helped in improving the model's ability to accurately classify the minority class.
<br>
### Model Performance
Challenge: Achieving the desired accuracy on the test set while avoiding overfitting.
<br>
Solution: Implemented various model architectures and regularization techniques. For instance, added Dropout and Batch Normalization layers in the Convolutional Neural Network (CNN) model to prevent overfitting and improve generalization.
<br>
### Computational Resources
Challenge: Training deep learning models with a large dataset required significant computational power and time.
<br>
Solution: Utilized cloud-based GPU instances to accelerate the training process and ensure timely completion of the experiments.
<br>
### Hyperparameter Tuning
Challenge: Finding the optimal hyperparameters for the model to achieve the best performance.
<br>
Solution: I experimenting with different values for learning rate, batch size, and the number of layers/neurons.
