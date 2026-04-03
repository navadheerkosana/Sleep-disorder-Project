# Sleep-Disorder-Classification-Using-Optimizes-Ensemble-Machine-Learning-and-Genetic-Algorithms

This project focuses on the classification of sleep disorders such as insomnia and sleep apnea using demographic, lifestyle, and health-related data. The objective is to build an accurate and reliable machine learning system that can assist in early detection of sleep disorders and support healthcare decision-making.

The model is trained on the Sleep Health and Lifestyle dataset, which consists of 400 records with features including age, gender, occupation, sleep duration, sleep quality, stress level, BMI, blood pressure, physical activity level, and daily steps. The data undergoes preprocessing steps such as missing value handling, label encoding, feature scaling, and correlation analysis to ensure high-quality inputs.

Multiple supervised machine learning algorithms are implemented and evaluated, including Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Decision Tree, and Random Forest. In addition, a deep learning model based on Artificial Neural Networks (ANN) is developed to capture complex non-linear relationships within the dataset.

To improve model performance, a Genetic Algorithm (GA) is integrated for feature selection and hyperparameter optimization. This optimization process enhances generalization capability, reduces overfitting, and significantly improves classification accuracy.

📊 Performance Results

The models are evaluated using accuracy, precision, recall, and F1-score, along with confusion matrix analysis. Experimental results show:

SVM Accuracy: 90.5%

KNN Accuracy: 89.0%

Decision Tree Accuracy: 89.9%

Random Forest Accuracy: 91.2%

ANN Accuracy: 93.8%

ANN + Genetic Algorithm Accuracy: 97.8% (Best Performance)

The optimized ANN with GA achieves the highest accuracy and demonstrates superior reliability in distinguishing between normal sleep, insomnia, and sleep apnea cases.

This project highlights the effectiveness of combining deep learning with evolutionary optimization techniques for healthcare applications and provides a scalable foundation for future extensions using larger datasets, wearable sensor data, and real-world clinical deployment.
