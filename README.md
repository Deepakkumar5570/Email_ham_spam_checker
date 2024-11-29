<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Email Spam Checker - README</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: #fff;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        h1, h2, h3 {
            color: #ffde59;
        }
        a {
            color: #00c9ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        ul {
            margin: 10px 0;
            padding-left: 20px;
        }
        pre {
            background: #1e1e1e;
            color: #d4d4d4;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background: #ff6347;
            color: #fff;
            text-transform: uppercase;
            font-weight: bold;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
            text-decoration: none;
        }
        .button:hover {
            background: #d80000;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Email Spam Checker</h1>
        <p>
            An <strong>Email Spam Checker</strong> application built with Django, Scikit-learn, and Pandas. This application allows users to classify messages as 
            <span style="color: #00ff7f;">Ham</span> or <span style="color: #ff6347;">Spam</span> using a trained machine learning model.
        </p>

        <h2>Features</h2>
        <ul>
            <li>Classifies messages as <strong>Spam</strong> or <strong>Ham</strong>.</li>
            <li>Trained with the <strong>Naive Bayes Algorithm</strong> for text classification.</li>
            <li>Uses <strong>CountVectorizer</strong> for text preprocessing.</li>
            <li>User-friendly interface with a Django-based web application.</li>
        </ul>

        <h2>Technologies Used</h2>
        <ul>
            <li><strong>Django:</strong> Backend framework to manage the web application.</li>
            <li><strong>Scikit-learn:</strong> Machine learning library for training and prediction.</li>
            <li><strong>Pandas:</strong> For data manipulation and analysis.</li>
        </ul>

        <h2>Getting Started</h2>
        <h3>Clone the Repository</h3>
        <pre>
git clone https://github.com/Deepakkumar5570/email-spam-checker.git
cd email-spam-checker
        </pre>

        <h3>Setup and Installation</h3>
        <ol>
            <li>Create a Virtual Environment (Optional but Recommended):
                <pre>
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
                </pre>
            </li>
            <li>Install Required Dependencies:
                <pre>
pip install django
pip install pandas
pip install scikit-learn
                </pre>
            </li>
            <li>Navigate to the project directory:
                <pre>
# From the main root directory:
cd ./Email_ham_spam_checker
cd ./spamDetection
                </pre>
            </li>
            <li>Run the server:
                <pre>
python manage.py runserver
                </pre>
            </li>
        </ol>

        <h2>How to Use</h2>
        <ol>
            <li>Open the web application in your browser (default: <a href="http://127.0.0.1:8000" target="_blank">http://127.0.0.1:8000</a>).</li>
            <li>Enter your message in the input field.</li>
            <li>Click the <span class="button">Check</span> button.</li>
            <li>The application will classify the message as <span style="color: #00ff7f;">Ham</span> or <span style="color: #ff6347;">Spam</span>.</li>
        </ol>

        <h2>Contact</h2>
        <p>
            <strong>Maintainer:</strong> Deepak Kumar <br>
            <a href="mailto:your-email@example.c">dk0778671@gmail.com</a> <br>
            <a href="https://github.com/Deepakkumar5570" target="_blank">GitHub Profile</a>
        </p>
    </div>
</body>
</html>
