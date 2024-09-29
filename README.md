🔍 Project Overview:
Developed a robust credit scoring model to predict the likelihood of loan defaults using a dataset with various customer credit behavior features.

🛠 Data Preparation:
#Using RandomOverSampler to address class imbalance by oversampling the minority class in the dataset.
#Applied MinmaxScaler for normalization
#Statistical analysis of data.

🔢 Train-Test Split and Scaling:
Split the data into 80% training and 20% testing sets.
Applied feature scaling with MinmaxScaler to normalize data.

📊 Model Evaluation:

Random Forest Classifier	- 97.19% **
Decision Tree Classifier	- 95.94% **
GB Classifier	- 90.50% **
KNN	- 88.06% **
Logistic Regression	- 78.94% **
SVM	- 78.81% **
LSTM - 89.81% 

Analyzed the confusion matrix to understand true positives, true negatives, false positives, and false negatives.

🖼 Visualization:
Visualized the confusion matrix to gain insights into the model’s performance.

Evaluating the Model: 
Assessing the model's performance with accuracy, confusion matrix, and ROC-AUC score.
Key Findings:
The model demonstrates solid predictive power for loan defaults.
Potential for integration into financial institutions' risk management systems to enhance decision-making.
