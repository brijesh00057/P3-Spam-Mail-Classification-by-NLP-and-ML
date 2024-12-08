<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
</head>
<body>
    <h1>Spam Email Classification Using NLP and Machine Learning</h1>
    <p>
        This project demonstrates the use of Natural Language Processing (NLP) and Machine Learning (ML) to classify emails as either spam or ham (non-spam). 
        The model has been trained on a labeled dataset and implements text preprocessing, feature extraction, and classification algorithms.
    
   </p>
  <h2>Project Features</h2>
    <ul>
        <li>Preprocessing of email data using NLP techniques (removal of HTML tags, punctuation, tokenization).</li>
        <li>Feature extraction using <strong>CountVectorizer</strong> and <strong>TF-IDF</strong>.</li>
        <li>Model training and evaluation using supervised learning algorithms such as <strong>Logistic Regression</strong> or <strong>Naive Bayes</strong>.</li>
        <li>A terminal-based application to classify email text as spam or ham in real-time.</li>
    </ul>

  <h2>How to Run the Project</h2>
    

  <h3>Step 1: Install the Required Dependencies</h3>
    <p>
        Ensure you have <strong>Anaconda</strong> installed on your system. Create a new environment and install the required packages:
    </p>
    <pre>
        conda create -n spam-classifier python=3.9
        conda activate spam-classifier
        pip install -r requirements.txt
    </pre>

   

   <h3>Step 2: Run the Terminal-Based Application</h3>
    <p>
        Once the model is trained and saved as <strong>spam.pkl</strong> and <strong>vec.pkl</strong>, run the Python application using the terminal:
    </p>
    <pre>
        python app.py
    </pre>
    <p>
        Enter the email text in the terminal interface to classify it as spam or ham.
    </p>

   <h2>Project Structure</h2>
    <ul>
        <li><strong>spam_classifier.ipynb:</strong> Jupyter Notebook for preprocessing, training, and saving the model.</li>
        <li><strong>app.py:</strong> Python script for the terminal-based application.</li>
        <li><strong>spam.pkl:</strong> Trained machine learning model.</li>
        <li><strong>vec.pkl:</strong> CountVectorizer or TF-IDF model for text transformation.</li>
        <li><strong>requirements.txt:</strong> List of required Python packages.</li>
    </ul>

</body>
</html>
