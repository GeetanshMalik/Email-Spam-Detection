# Email-Spam-Detection

## **Project Overview**

This project aims to classify emails as **Spam** or **Non-Spam (Ham)** using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques. The model leverages text preprocessing, feature extraction, and machine learning algorithms to effectively identify and classify spam emails. The project is deployed on both **GitHub** (for version control and code sharing) and **Streamlit** (for interactive real-time classification of emails).

The final model achieves **100% accuracy** on the test dataset, and the Streamlit application allows users to upload emails and get spam classification results in real time.

## **Table of Contents**

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Streamlit Deployment](#streamlit-deployment)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [Contact](#contact)

---

## **Technologies Used**

- **Python**: The primary programming language used for the project.
- **Libraries**:
  - **NLP Libraries**: 
    - `NLTK` (Natural Language Toolkit) for text preprocessing tasks like tokenization, stopword removal, and lemmatization.
    - `spaCy` for more advanced NLP tasks (optional).
    - `TfidfVectorizer` from **Scikit-learn** for feature extraction.
  - **Machine Learning**:
    - `Scikit-learn` for implementing machine learning algorithms like Naive Bayes, Logistic Regression, SVM, and Random Forest.
  - **Data Handling**:
    - `Pandas` for data manipulation.
    - `NumPy` for numerical operations.
  - **Visualization**:
    - `Matplotlib` and `Seaborn` for visualizing evaluation metrics.
  - **Streamlit**: To create a simple, interactive web app for real-time email classification.
  

## **Installation**

To run the project locally, you need to have Python installed on your machine. Follow the instructions below to set up the project environment:

### **1. Clone the Repository**

First, clone this repository to your local machine:

```
git clone https://github.com/your-username/email-spam-classification.git
```

### **2. Install Dependencies**

Navigate to the project folder and create a virtual environment (optional but recommended):

```
cd email-spam-classification
python -m venv venv
```

Activate the virtual environment:

- On Windows:
  ```
  venv\Scripts\activate
  ```
- On Mac/Linux:
  ```
  source venv/bin/activate
  ```
Now, install the required libraries using **pip**:

pip install -r requirements.txt

The `requirements.txt` file contains all the dependencies needed to run the project.


## **Usage**

Once the dependencies are installed, you can run the project in two ways: either through the Jupyter Notebook for offline analysis or through the Streamlit app for real-time classification.

### **1. Running the Model in Jupyter Notebook (Offline)**

- Navigate to the `notebooks/` folder and open the Jupyter notebook file (`email_spam_classification.ipynb`).
- You can use this notebook to:
  - Load the dataset.
  - Preprocess the text data.
  - Train different machine learning models.
  - Evaluate the model's performance using metrics like accuracy, precision, recall, F1-score, and confusion matrix.

### **2. Running the Streamlit App (Real-Time Classification)**

To run the real-time Streamlit app, execute the following command:
streamlit run app.py

The Streamlit app will start running, and a URL will be displayed in your terminal. Open this URL in a web browser to access the email classification app.

#### **How to Use the Streamlit App**:
1. **Upload an Email**: You can upload an email file in `.txt` or `.csv` format.
2. **Real-Time Classification**: Once the email is uploaded, the app will process the email text and predict whether it is "Spam" or "Not Spam".
3. **View Results**: The classification result will be displayed on the interface with a message such as:
   - **Spam**
   - **Not Spam**

---

## **Streamlit Deployment**

The app has been deployed to **Streamlit** to make it publicly accessible for anyone to use.

**Live Demo Link**:  
[Streamlit Email Spam Classification App](https://spamclassification-geetanshmalik.streamlit.app/)

You can visit the link to interact with the model and classify emails in real-time without any local setup.


## **Model Evaluation**

The model has been evaluated using the following metrics to assess its performance:

- **Accuracy**: The final model achieved **100% accuracy** on the test set, meaning it classified all test emails correctly.
- **Precision**: The model's precision is 100%, with no false positives (i.e., no legitimate emails were misclassified as spam).
- **Recall**: The recall score is also 100%, meaning all spam emails were correctly identified.
- **F1-Score**: The F1-Score, which balances precision and recall, is also 100%.

A **confusion matrix** was used to visualize the performance, showing no false positives or false negatives.


## **Contributing**

Contributions are welcome! If you would like to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature-name`).
6. Open a pull request.

## **Contact**

If you have any questions or feedback, feel free to reach out to me:

- **Email**: (geetanshmalik337@gmail.com)
- **GitHub**: (https://github.com/GeetanshMalik/Email-Spam-Detection/tree/main)

