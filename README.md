# Portfolio

## About Me
I have earned a degree in Master of Science in Business Analytics from the Zicklin School of Business, with a concentration in Data Analytics. Through my academic journey, I've built expertise in machine learning, statistical modeling, and advanced data analysis techniques. My portfolio demonstrates my proficiency in end-to-end data science workflows - from exploratory data analysis and feature engineering to model development and evaluation. Each project showcases my ability to extract meaningful insights from complex datasets using Python and R, while creating compelling visualizations to communicate findings effectively. I am passionate about leveraging data science to solve real-world problems and drive data-informed decision-making.

Connect with me on [LinkedIn](https://www.linkedin.com/in/matthew-paz/) or send me an [email](mailto:paz.matthew@me.com).

## Projects

## Text Classification with NLP & Machine Learning: Detecting Review Authenticity

This project focuses on developing and evaluating NLP-based classification models to identify verified and unverified product reviews in e-commerce platforms. With fake reviews influencing $152 billion in global online spending, the project aims to enhance trust in online review systems through advanced text analysis and machine learning techniques.

## Libraries and Tools Used
- pandas
- NLTK
- scikit-learn
- matplotlib
- seaborn
- imbalanced-learn (for SMOTE)

## Technical Highlights
- Processed a balanced dataset of 200,000 e-commerce reviews using stratified sampling
- Engineered NLP features including:
  - Part-of-speech tagging (nouns, adjectives, verbs)
  - Named Entity Recognition for product/brand mentions
  - Sentiment analysis scores
  - Text statistics and linguistic patterns
- Addressed significant class imbalance (96% verified vs 4% unverified) using SMOTE
- Implemented and compared multiple classification models

## Conclusion
The Random Forest classifier emerged as the best-performing model with an overall accuracy of 86%, achieving high precision in identifying both verified (88%) and unverified (81%) reviews. The model effectively handles the class imbalance challenge, demonstrated by balanced F1 scores (0.89/0.78) for both classes. This solution provides a robust framework for enhancing trust in e-commerce platforms by accurately flagging potential unverified reviews.

## Impact
- Achieved 86% accuracy in distinguishing verified from unverified reviews
- Created a scalable framework for automated review authentication
- Demonstrated practical application of NLP techniques in real-world business problems

[Text Classification with NLP & Machine Learning Project](https://nbviewer.org/github/mattpaznyc/review-trust-nlp/blob/main/review_classifier.ipynb)

  ## Marketing Binary Classification Project

This project focuses on building and evaluating binary classification models to predict whether a consumer will respond to an offer from a sales campaign, with a binary target variable representing acceptance (1) or not-accepted (0). The analysis involves Exploratory Data Analysis (EDA), feature engineering, model selection, and performance evaluation.

### R Packages Used
- dplyr
- ggplot2
- caret
- pROC
- e1071
- RColorBrewer
- ROSE
- ggcorrplot

### Conclusion
Maximizing precision ensures that the model accurately identifies true positives (responders) while minimizing false positives (non-responders). This is crucial in marketing, where targeting the right customers impacts campaign success and cost-effectiveness.

In this project, I evaluated several models for classifying customer responses to marketing campaigns. The Support Vector Machine (SVM) model achieved the highest precision score of 0.85, correctly identifying likely responders 85% of the time.

This high precision makes the SVM model highly effective for this classification task. By using the SVM model, marketers can better target potential customers, leading to more successful and efficient campaigns.

### Summary
- **Importance of Precision**: High precision minimizes false positives, crucial for effective marketing.
- **Model Performance**: The SVM model achieved the highest precision score of 0.85 among the evaluated models.
- **Implications**: Implementing the SVM model can enhance the accuracy of marketing campaigns, improving their efficiency and effectiveness.

[Binary Classification Project](Projects/BinaryClassificationProject.html)

## NYC Airbnb Dashboard

This dashboard showcases my ability to handle real-world data, perform comprehensive Exploratory Data Analysis (EDA), and create interactive visualizations that can help in making informed business decisions. It demonstrates proficiency in data analysis, visualization, and web application development.

### Technologies Used:
- **Python:** Core language for data processing.
- **Streamlit:** Framework for creating the interactive web application.
- **Plotly:** Library for creating dynamic visualizations.

### Dashboard Functionality

![Dashboard Functionality](Images/Dashboardvid.gif)

[NYC Airbnb Dashboard](https://nyc-airbnb-dashboard.streamlit.app/)

## Articles:
Here are some of my articles published on Medium:

* [Data Cleaning with Python](https://medium.com/@matthew.paz/data-cleaning-with-python-dealing-with-the-inevitability-of-missing-data-9cc9ab172e14)
* [Introduction to SQLite3](https://medium.com/@matthew.paz/introduction-to-sql-with-sqlite-f8a4f4f6c161)
* [Time Series Analysis Tutorial](https://medium.com/@matthew.paz/time-series-analysis-with-python-a-tutorial-for-beginners-898a3300ce9a)
