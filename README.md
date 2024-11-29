An Email Spam Checker application built with Django, Scikit-learn, and Pandas. This application allows users to classify messages as Spam or Ham using a trained machine learning model.


Features
  Detects whether a given email/message is Spam or Ham.
  Trained with the Naive Bayes Algorithm for text classification.
  Implements CountVectorizer for text preprocessing.
  User-friendly interface with a Django-based web applicat


Technologies Used
   Django: Backend framework to manage the web application.
   Scikit-learn: Machine Learning library for training and prediction.
   Pandas: Data manipulation and analysis.


Getting Started
Clone the Repository
To clone the repository, run the following command:
       
   git clone https://github.com/https://github.com/Deepakkumar5570/email-spam-checker.git
   cd email-spam-checker

Setup and Installation
Create a Virtual Environment (Optional but Recommended):
       python -m venv env
       source env/bin/activate  # On Windows: env\Scripts\activate

Install Required Dependencies:

Install the required Python libraries using pip:
     pip install django
     pip install pandas scikit-learn


After these steps change directory to by  cd ./spamDetection drom main directory and run:
          python manage.py runserver
If you are in main root Directory do this:
         cd ./Email_ham_spam_checker 
         cd ./spamDetection
         python manage.py runserver
       

   
