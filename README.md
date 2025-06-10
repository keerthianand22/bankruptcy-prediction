# Predicting Bankruptcy using SAS Enterprise Miner

This project was developed as part of the Data Mining course at Purdue University. It focuses on predicting firm bankruptcy using financial indicators and advanced machine learning techniques within SAS Enterprise Miner.

## Project Summary

We built a predictive model that identifies firms at risk of bankruptcy with high accuracy. The core objective was to address the challenges of class imbalance and improve prediction performance using ensemble methods.

## Key Highlights

- Analyzed over 10,000 financial records with 64 predictors to detect early signs of bankruptcy.
- Tackled significant class imbalance (only 2.11% of firms were bankrupt) using oversampling.
- Applied prior probability adjustment to align predictions with real-world class distribution.
- Developed multiple Neural Networks with varying configurations to capture diverse data patterns.
- Combined models using ensemble techniques to improve generalization and robustness.
- Achieved **96.088% prediction accuracy**, ranking 2nd on the private Kaggle competition leaderboard.

## Methodology

### Data Preprocessing

- Replicated minority class records (bankrupt firms) 5 times using SAS code node to balance the dataset.
- Adjusted prior probabilities to mitigate the effects of oversampling and maintain realistic class proportions.

### Model Building

- Created three Neural Networks with varied iteration and seed configurations.
- Ensemble method integrated predictions to minimize bias and variance.
- Conducted multiple sampling rounds to improve model diversity.
- Partitioned data into training and validation sets for performance evaluation.

### Evaluation

- Compared multiple ensemble configurations to identify the most effective architecture.
- The top-performing model achieved 96.088% accuracy, while the second-best model reached 94.05%.

## Tools & Skills Used

- **Tools**: SAS Enterprise Miner
- **Techniques**: Oversampling, Ensemble Modeling, Neural Networks, Classification
- **Skills**: Model Evaluation, Financial Risk Analysis, Imbalanced Dataset Handling

## Team Members

- Ajay Shankar  
- Krithiga Rajan Sangeetha Rajan  
- Keerthi Anand Sangeetha Rajan

## Acknowledgments

This work was completed as a part of the Data Mining final project at Purdue University. We thank the instructional team for their guidance and the opportunity to explore real-world applications of machine learning in financial risk prediction.
