# Flight-Delay-Prediction)
This repository contains a comprehensive project focused on predicting flight delays using a multi-class classification approach. The project is divided into two main sections: Data Analytics and Data Science.

Project Overview)
Flight delays can have significant operational and financial impacts on the aviation industry. This project aims to predict the degree of flight delays using various machine learning models. The delay is categorized into multiple classes, allowing for a nuanced prediction rather than a simple binary outcome.

Data Analytics)
In the first part of this project, I focused on answering several data analytics questions to gain insights into the dataset.

Data Science)
The second part of the project focuses on building a predictive model for flight delays.

Preprocessing)
To prepare the data for modeling, the following preprocessing steps were applied:

    Dropping Missing Values: Removed rows with missing data to ensure model accuracy.
    Treating Class Imbalance: Used techniques such as SMOTE and cost-sensitive learning to balance the delay classes.
    Encoding Categorical Columns: Converted categorical features into numerical values using techniques like One Hot Encoding and LeaveOneOutEncoder.
    Rescaling: Applied standardization or normalization to numerical features to bring them to a similar scale.

Model Development)
Several machine learning models were developed and evaluated for their ability to predict flight delays:

    Logistic Regression:
        Baseline model to establish a simple linear relationship between features and the delay classes.

    Random Forest Classifier:
        An ensemble method that improves prediction accuracy by averaging the results of multiple decision trees.

    XGBoost Classifier:
        A powerful gradient boosting algorithm that outperforms many other models in terms of accuracy and speed.

Technologies Used)

    Python: Programming language used for all analysis and model development.
    Pandas: For data manipulation and analysis.
    Scikit-learn: For building machine learning models and preprocessing data.
    XGBoost: For implementing the XGBClassifier.
    Matplotlib/Seaborn: For data visualization.
    imbalanced-learn: For dealing with class imbalance.

Conclusion)

This project demonstrates the application of data analytics and machine learning to predict flight delays. The developed models provide a robust starting point for predicting delay classes based on historical flight data.
Acknowledgements

I would like to thank the open-source community for providing the libraries and resources used in this project.
For questions or further information, please contact [Anahita Zahedi Nameghi] at [AnahitaZahediNameghi@gmail.com].
