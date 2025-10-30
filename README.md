 # 🌸 Iris Flower Classification Project: KNN vs. Logistic Regression
 This project is a foundational machine learning exercise focusing on the classification of the classic Iris dataset.
 We train and critically compare two primary classification algorithms: a linear model and a distance-based model.
# 🎯 Project Goals
To master essential data preparation techniques like Feature Scaling.

To build and optimize the K-Nearest Neighbors (KNN) classifier.

To train and interpret the Multinomial Logistic Regression model.

To perform a comparison and critical analysis of both models 

 ## 🛠️ Methodology and Steps
     1-Data Preparation
     The Iris dataset is loaded and split into $80\%$ training and $20\%$ testing sets
 
    2-Feature Scaling:
     is applied using StandardScaler.(Reflection: The importance of scaling for distance-based algorithms like KNN is highlighted).

    3- K-Nearest Neighbors (KNN) models :
      are trained across various $K$ values ($1, 3, 5, 7, 9, 11, 15, 20$).
      The optimal $K$ value (which achieved $100\%$ accuracy in our run) is identified.
      A plot of Accuracy vs. $K$ is generated for visual analysis.

    4- Logistic Regression :
     A Multinomial Logistic Regression model is trained ($\max\_iter=1000$).
      The model's Coefficients are printed and interpreted to assess feature importance (e.g., how petal length influences classification).

    5- Model ComparisonPerformance
     is compared using the Classification Report (Accuracy, Precision, Recall, F1-Score).
     Confusion Matrices are generated to visualize specific error types for each model.
     (Reflection: The analysis focuses on why a simpler model (Logistic Regression) or a more complex one (KNN) might perform better)


# 🧠 Key Insights
Scaling is critical for distance-based models like KNN.

KNN adapts better to non-linear data.

Logistic Regression remains powerful, interpretable, and scalable for larger datasets.

Choosing the right model depends on data structure, interpretability needs, and computational efficiency.

# 🧩 Technologies Used
Python 3.11

scikit-learn

numpy

pandas

matplotlib
