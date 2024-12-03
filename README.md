Interactive JavaScript Quiz Application
Overview
This project is an interactive JavaScript-based quiz application that enables users to answer multiple-choice questions. The application dynamically renders questions, evaluates answers in real-time, tracks user scores, and displays detailed results at the end of the quiz.

Designed with simplicity and usability in mind, this quiz is perfect for educational purposes, coding challenges, or small-scale assessments.

Features
Dynamic Question Loading:

Questions and options are loaded dynamically from a structured JSON object.
User-Friendly Navigation:

"Next" and "Previous" buttons allow users to move between questions smoothly.
Navigation buttons are disabled appropriately at the quiz boundaries.
Real-Time Answer Validation:

Answers are checked as the user progresses, and scores are updated dynamically.
Score Display and Summary:

At the end of the quiz, a detailed result summary shows the user's total score and correct answers for each question.
Responsive Design:

The application adapts to various screen sizes, making it usable on both desktop and mobile devices.
Secure Input Handling:

Special characters in options and answers are escaped to prevent cross-site scripting (XSS) attacks.
Technologies Used
Frontend:

HTML5
CSS3
JavaScript (ES5)
jQuery
Frameworks and Libraries:

jQuery for DOM manipulation and event handling.
FontAwesome for result indicators (correct and incorrect icons).
How It Works
Quiz Data:

All quiz data is stored in a JSON-like object named quiz.JS.
Each question contains:
id: Unique identifier.
question: Question text.
options: List of possible answers.
answer: Correct answer.
score: Tracks if the question was answered correctly.
status: Tracks if the user's answer is correct or incorrect.
Dynamic Rendering:

Questions and options are rendered dynamically using jQuery.
Radio buttons are used for answer selection.
Answer Validation:

User's selection is validated against the correct answer.
The score is incremented for each correct answer.
Result Display:

After completing the quiz, the total score is displayed along with a summary of all questions, correct answers, and user scores.
