# Quiz App 🎯

A simple and responsive **Quiz Application** built using **HTML, CSS, and JavaScript**.  
Users can attempt multiple-choice questions, see their score at the end, and restart the quiz.

---

## 🧩 Features

- Interactive multiple-choice quiz
- Score calculation at the end of the quiz
- Simple and clean dark-themed UI
- Highlights selected option
- Restart quiz functionality
- Fully client-side – no backend required

---

## 🛠️ Tech Stack

- **HTML5** – Structure of the app  
- **CSS3** – Styling and layout (dark theme)  
- **Vanilla JavaScript** – Quiz logic and interactivity  

---

## 📂 Project Structure

```bash
quiz-app/
├── index.html      # Main HTML file
├── style.css       # Styling for the app
└── script1.js      # Quiz logic and interactivity

```
🚀 Getting Started

Follow these steps to run the project locally:

1. Clone the repository
git clone https://github.com/your-username/quiz-app.git
cd quiz-app


Replace your-username and repo name with your actual GitHub details.

2. Open the app

You can open the app in any modern browser:

Option 1: Double-click index.html

Option 2: Right-click index.html → Open with → your browser

No extra setup or installations are required.🧠 How It Works

The quiz questions are stored in a JavaScript array inside script1.js:
```
const questions = [
  {
    question: "What is the capital of France?",
    choices: ["Paris", "London", "Berlin", "Madrid"],
    answer: "Paris",
  },
  // more questions...
];
```
When the user clicks Start Quiz:

The first question is displayed.

Answer choices are rendered as buttons.

When a user selects an answer:

The selected option is highlighted.

The score is updated if the answer is correct.

The Next question button appears.

After the last question:

The final score is displayed.

A Restart Quiz button appears to retake the quiz.

🎨 UI & Styling

Dark themed background (#121212)

Card-style container for the quiz

Hover effects on answer options and buttons

Visual feedback using a .selected class for chosen answers

You can tweak the look by editing style.css.

🧩 Customization

You can easily:

Add more questions
Just append new question objects to the questions array in script1.js.

Change quiz content
Edit the question, choices, and answer fields as needed.

✅ Possible Future Enhancements

Add a timer for each question

Show correct/incorrect feedback per question

Add categories or difficulty levels

Store high scores using localStorage

📜 License

This project is licensed under the MIT License – feel free to use and modify it.
