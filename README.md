# Standard-IQ-Test-Web-App

# Overview
This is a web-based IQ assessment application built with HTML, CSS, and JavaScript. It provides a scientifically inspired IQ test based on principles from Raven's Progressive Matrices, including verbal, numerical, and spatial reasoning questions. The app features an intuitive user interface, age-normed scoring, a timer, and generates a downloadable PDF report with the user's IQ score, percentile, and interpretation.
Note: This is a screening tool for educational purposes only and is not a substitute for professional psychological assessment. Scores are estimated and clamped between 70 and 145.

# Features

30 Diverse Questions:

10 Raven-style pattern recognition questions with visual matrices (sourced from public examples).
10 Verbal reasoning questions (e.g., analogies, synonyms, antonyms).
10 Numerical reasoning questions (e.g., sequences, math problems).


Age-Normed Scoring: Compares results to population norms for ages 16-64, with mean IQ of 100 and standard deviation of 15.
Time-Based Bonus: 25-minute timer; faster completion adds bonus points to the raw score.
Intuitive UI: Responsive design using Bootstrap 5, with progress bar, navigation buttons, and mobile compatibility.
PDF Report Generation: Uses jsPDF to create a professional report including score, percentile, interpretation, and test details.
Offline Capable: Runs entirely in the browser without backend dependencies (internet required for initial image loading).

# Technologies Used

Frontend: HTML5, CSS3, JavaScript (ES6+).
Libraries:

Bootstrap 5 for styling and responsive layout.
jsPDF for PDF report generation.


No Backend: Pure client-side application.
Images: Pattern questions use publicly available Raven's matrices examples from iPrep.online (for demonstration; replace with custom assets for production).

# Usage

Start the Test:

Open the app in your browser.
Enter your age (16-64) and optional gender.
Click "Start Test".


# Taking the Test:

Answer 30 questions by selecting options (A-F for patterns).
Use "Previous" and "Next" to navigate.
Timer starts at 25:00; unfinished tests auto-submit.


# Results:

View IQ score, percentile, and interpretation on-screen.
Download the PDF report.
Option to retake the test.
