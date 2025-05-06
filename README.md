# 🐞 Bug Buzzer — The Ultimate Programming Quiz Game
---
**Bug Buzzer** is an interactive, Java-based quiz game designed to test and entertain programmers with engaging, rule-based gameplay. With a user-friendly interface and humorous quiz rules, Bug Buzzer offers a refreshing twist on traditional MCQ quizzes, making coding education more fun and interactive.
📌 Project Type: Desktop Application (Java Swing)  
---

## 🛠️ Technologies & Tools Used

- **Programming Language**: Java (JDK 8+)
- **GUI Framework**: Java Swing & AWT
- **IDE Used**: NetBeans IDE 14
- **Graphics**: Custom icons and images
- **OOP Concepts**: Encapsulation, Inheritance, Polymorphism

---
## 🧩 How It Works

1. The user enters their name on the login screen.
2. Rules are displayed with fun descriptions to prepare the user.
3. The quiz begins with 10 questions.
4. At the end, the score is shown along with a thank-you message.
5. Users can restart the quiz.
   
---

## 🚀 Installation Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/bug-buzzer.git
cd bug-buzzer

# Compile Java files
javac quiz/application/*.java

# Launch app
java quiz.application.Login

```
Note: Ensure that the icons/score.png image resource is present in the correct directory structure (icons folder in your classpath).
      Make sure you have Java installed and properly set in your system path.
---

## 📁 Project Structure

bug-buzzer/
├── quiz/
│   └── application/
│       ├── Login.java
│       ├── Rules.java
│       ├── Quiz.java
│       └── Score.java
└── icons/
    └── score.png

---
## 🧪 Testing Highlights
| Test Case            | Expected Behavior                             |
| -------------------- | --------------------------------------------- |
| Login Flow           | Accepts valid name input and moves to Rules   |
| Rules Screen Buttons | 'Start' begins quiz, 'Back' returns to login  |
| Quiz Logic           | Accurately tracks user responses              |
| Score Calculation    | Displays correct score and allows replay      |
| UI Components        | Buttons, labels, and images display correctly |

---
🎓 Test your brain. Laugh while you learn. Take the Bug Buzzer challenge today!

