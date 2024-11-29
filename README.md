# Email Spam Checker
   An Email Spam Checker application built with Django, Scikit-learn, and Pandas. This application allows users to classify 
   messages as Spam or Ham using a trained machine learning model.

# Feature
    !: Classifies messages as Spam or Ham.
    2: Trained using the Naive Bayes Algorithm(MultiNomial Bayes) for text classification.
    3: Implements CountVectorizer for text preprocessing.
    4: User-friendly interface built with Django.

# Technologies Used
  ## Django:
        Backend framework for managing the web application.
  ## Scikit-learn:
        Machine learning library for training and prediction.
  ## Pandas 
       For data manipulation and analysis.

# Getting Started
  ## Clone repository 
       Run the Following Command
       git clone https://github.com/Deepakkumar5570/email-spam-checker.git
       cd email-spam-checker
  ## Setup and Installation 
       Create a Virtual Environment (Optional but recommended):
       python -m venv env
       source env/bin/activate  # On Windows: env\Scripts\activate
 ## Install Required Dependencies
      pip install django pandas scikit-learn

 ##  Navigate to the Project Directory:   
     cd ./Email_ham_spam_checker/spamDetection
  
 ## Run the Server:
    python manage.py runserver

## How to Use
     Open the application in your browser (default: http://127.0.0.1:8000).
     Enter your message in the input field.
     Click the Check button to classify the message.
     The application will display whether the message is Spam or Ham.

   
## Contributing
    We welcome contributions to enhance this project!

## Steps to Contribute:
    Fork this repository:
     Click the "Fork" button on the top right corner of this page to create a copy of this repository under your GitHub 
     account.

## Clone your forked repository:
      git clone https://github.com/your-username/email-spam-checker.git  
      cd email-spam-checker       
## Create a new branch for your changes: 
      git checkout -b your-feature-branch  

Make your changes:

    Improve existing functionality or add new features.
    Ensure your changes align with the goals of the project.
    Test your changes locally to confirm everything works as expected.

    Push your changes to your forked repository:

    git add .  
    git commit -m "Describe your changes"  
    git push origin your-feature-branch  
Create a pull request:

    Go to the original repository at https://github.com/Deepakkumar5570/email-spam-checker.
    Click the "Pull Requests" tab and then "New Pull Request".
    Select your branch and submit the pull request with a description of your changes.
    
## Contact
    Maintainer: Deepak Kumar
    GitHub: Deepakkumar5570
    Email: dk0778671@gmail.com
 
